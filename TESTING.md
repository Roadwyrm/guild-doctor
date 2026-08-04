# Guild Doctor Test-Suite Governance

## Current product validation

Run from `C:\GuildDoctor` with no `GUILD_DOCTOR_DISCORD_TOKEN` in the test
process:

```powershell
Remove-Item Env:GUILD_DOCTOR_DISCORD_TOKEN -ErrorAction SilentlyContinue
& .\.venv\Scripts\python.exe -m pytest -q
```

This is the default suite. It validates the current approved source, including
the Stage 7 report surface and Stage 8 read-only interaction safeguards.

## Historical freeze probes

Seventeen Stage 5/6 files assert an earlier source tree had exactly twelve
commands and no Stage 7 implementation. The current approved source has the
thirteenth `server-report` command and later Stage 7/8 files, so those tests
are marked `historical_freeze`. They are retained as immutable evidence; they
are not current-release failures.

```powershell
& .\.venv\Scripts\python.exe -m pytest -q -m historical_freeze
```

This command is an archival comparison, not a current-release gate. It is
expected to report conflicts where later approved source intentionally changed
the historical frozen surface.

## Required focused checks

```powershell
$stage7 = Get-ChildItem .\tests\test_stage7*.py | ForEach-Object FullName
$stage8 = Get-ChildItem .\tests\test_stage8*.py | ForEach-Object FullName
& .\.venv\Scripts\python.exe -m pytest -q .\tests\test_integration_pass5.py @stage7 @stage8
```

These checks remain offline and token-free unless a separate live command is
explicitly authorized.
