# AutoPilotIT Project Mapper

Generate an AI-readable bundle and semantic map of a .NET solution.

This tool scans a .NET solution and produces a structured project bundle designed to give AI tools and developers deep context about the entire codebase.

The goal is to make it easier to:
- review large projects
- generate documentation context
- audit systems
- provide full project context to AI assistants

## Output

The tool generates artifacts such as:

- semantic map of the codebase
- combined readable code bundle
- database schema snapshot
- contract vs database diff
- configuration snapshot (secrets redacted)

These artifacts can be used to give AI assistants a much better understanding of a project than pasting individual files.

## Why

AI tools work much better when they have broader context about a system.  
Instead of manually selecting files, this tool creates a structured bundle representing the entire solution.

## Status

Early version. Built originally for internal use while developing AutoPilotIT.

## About

Created by AutoPilotIT  
https://autopilotit.net
