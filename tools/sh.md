---
title: Posix SH
description: The standardized shell found on all POSIX systems
published: true
date: 2021-01-26T00:08:36.235Z
tags: 
editor: markdown
dateCreated: 2021-01-25T23:35:20.175Z
---

**Website**: <https://en.wikipedia.org/wiki/Unix_shell>

On most UNIX-like systems there `/bin/sh`, a symbolic link to system\'s default [POSIX](/topics/posix) shell.

`/bin/sh` links to `BASH` on most systems, but on Ubuntu it links to `DASH` (another POSIX compliant shell) for efficiency purposes.

## Historical Notes

Historically, `sh` was its own shell, called the Bourne Shell.

`Bash` (Bourne Again Shell) was made as an extension of `sh`, and has since overtaken it as the widely accepted standard. The Bourne Shell is no longer used on most systems, as `/bin/sh` is now a symbolic link.

## Resources

External resources such as tutorials and documentation
