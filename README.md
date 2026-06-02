# PS3 Local Content Verifier

A small local tool for checking PS3 files against a user-provided database.

The goal is simple: users bring their own database and their own local files, then the tool checks whether the files match by size and checksums.

## What it does

- Imports a local JSON database
- Scans local PS3 files and folders
- Calculates MD5, SHA1, and SHA256
- Compares files by title ID, size, and hashes
- Reports verified, mismatched, unknown, or unsupported files

## What it does not do

- It does not download files
- It does not include Sony CDN links
- It does not include game files
- It does not include licenses, RAP/RIF files, keys, or DKEYs
- It does not include any third-party game database

Users are responsible for their own files and databases.

## Status

Early planning stage.
