# Start Guild Doctor on Windows

This package contains the completed **Guild Doctor Stage 2** release and the
completed Stage 3 Pass 1, Pass 2, Pass 3, Pass 4, and Pass 5 analysis engines.
It is read-only and intended for a disposable Discord test server. Stage 3
overall is in progress; Pass 6 is the next stage and has not started.

## 1. Extract the ZIP

Extract the downloaded ZIP to a simple location such as:

```text
C:\GuildDoctor
```

## 2. Install

Open the extracted folder. Right-click `INSTALL_GUILD_DOCTOR.ps1` and choose **Run with PowerShell**.

If Windows blocks the script, open PowerShell inside the folder and run:

```powershell
Set-ExecutionPolicy -Scope Process Bypass
.\INSTALL_GUILD_DOCTOR.ps1
```

## 3. Start the test bot

Run:

```powershell
.\START_GUILD_DOCTOR_TEST.ps1
```

The script asks for:

- The disposable test server Guild ID
- The Guild Doctor bot token

The token input is hidden and is kept only in the running PowerShell process. It is not written to a file.

To run the completed Pass 5 verifier, use:

```powershell
powershell.exe -NoProfile -ExecutionPolicy Bypass -File "C:\GuildDoctor\RUN_GUILD_DOCTOR_PASS5.ps1"
```

The verifier prompts for the disposable Guild ID and hidden bot token, displays flushed progress, and writes the four evidence files under `pass5-evidence`.

## 4. Test in Discord

After the bot reports that it is connected, use:

```text
/guild-doctor status
```

Only the server owner is authorized during the private alpha.

## Important

- Use a disposable server that you own.
- Never paste the bot token into ChatGPT, Discord, screenshots, or source control.
- Do not grant Administrator.
- Keep the PowerShell window open while Guild Doctor is running.
