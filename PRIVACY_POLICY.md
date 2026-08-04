# Guild Doctor Privacy Policy

Last updated: August 3, 2026

Guild Doctor is a read-only Discord diagnostic created and operated by Roadwyrm ("we", "us", or "our"). This policy explains the information Guild Doctor processes and why.

## Information processed

When a server owner runs a diagnostic, Guild Doctor may process Discord structural information needed to answer the requested diagnostic question, including server, role, channel, category, thread, permission, overwrite, and hierarchy metadata. It may also process Discord object IDs needed to link those records.

Guild Doctor is designed not to collect message content or member profile content for its structural diagnostics. It does not use the Message Content intent.

## How information is used

Information is used only to produce the requested read-only diagnostic. Guild Doctor contacts Discord only through the configured Discord application connection and does not make Discord write requests as part of its diagnostic workflow.

## Storage and sharing

Diagnostic output is stored only where the server owner runs and saves it. Roadwyrm does not operate a separate analytics service for Guild Doctor, sell diagnostic data, or share it with advertisers. A server owner controls any local files or reports they choose to retain, share, or delete.

## Security

The bot token is used only to authenticate the configured Discord application and must be kept secret. Do not place a token in chat, public repositories, screenshots, or support issues. If you believe a token was exposed, reset it in the Discord Developer Portal and update the protected runtime configuration.

## Changes and contact

We may update this policy when Guild Doctor changes. The current version is published in the public repository. For privacy questions, open an issue at https://github.com/Roadwyrm/guild-doctor/issues.

