
# MySQL Incremental Backup System

A lightweight, automated system for incremental MySQL backups with email alerts. Designed for small datasets and runs entirely on a single VM.
Features

    Incremental Backups: Automatically backs up changes since the last backup.

    Email Alerts: Sends notifications for backup success or failure.

    Restore Script: Easily restore the database from a backup.

## Setup

    Requirements:

        MySQL installed on the VM.

        Python 3 for running scripts.

        Cron for scheduling backups.

    Configuration:

        Update email settings in the backup script.

        Schedule the backup script using cron.

## Usage

    Backups: Automatically performed at scheduled intervals.

    Restore: Use the provided script to restore the database.

    Logs: Check logs for backup status and details.
