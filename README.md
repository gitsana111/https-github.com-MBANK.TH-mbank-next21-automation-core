# https-github.com-MBANK.TH-mbank-next21-automation-core
Automation core for MBANK Next21: LINE, Notion, Google Drive, audit logging, and daily summary workflows.
# MBANK Next21 Automation Core

MBANK Next21 Automation Core is the workflow engine that powers operational automation across LINE, Google Drive, and Notion.

This repository contains the automation logic used to process incoming events (such as receipt uploads), store assets, log operational data, and generate daily summaries for financial operations.

## Architecture Overview

LINE → Webhook → Processing → Storage → Summary

Components:
- LINE Messaging API
- Make.com Webhook
- Google Drive
- Notion
- Scheduler

## Core Features

- Automated receipt intake from LINE
- Asset storage in Google Drive
- Transaction logging in Notion
- Audit-friendly trace logging
- Daily financial summary automation
- Event-driven architecture for reliability

## Maintainer

**MBANK.TH**

Primary maintainer of MBANK Next21 automation infrastructure.

## License

MIT
