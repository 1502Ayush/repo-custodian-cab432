# repo-custodian-cab432

A tiny command-line notes app, used as the target repository for a CAB432 Assignment 2 AI triage agent.

## What this is

notes is a small CLI tool for jotting down and searching plain-text notes from the terminal. Notes are stored as individual Markdown files in a local notes/ directory, one file per note, named by a slugified title and timestamp.

## Features

notes add TITLE creates a new note and opens it in the editor. notes list shows all notes, most recent first. notes search QUERY runs a full-text search across all notes. notes rm ID deletes a note by id.

## Installation

Install globally with npm: npm install -g cab432-notes

## Configuration

By default notes are stored in the .cab432-notes directory in the user's home folder. Override the location with the NOTES_DIR environment variable.

## Known limitations

There is no sync between devices; notes are local-only for now. Search is a simple substring match, not fuzzy or ranked. There is no support for tags or folders yet.

## Contributing

Issues and pull requests are welcome. This repository is currently maintained with the help of an automated triage agent that labels and summarises new issues.
