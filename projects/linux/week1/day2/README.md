# Day 2 — File Operations

**Date:** 2026-05-19  
**Focus:** cp, mv, rm, rmdir, find, man, tldr

## Commands practiced
- `cp file1.txt backups/` — copy single file
- `cp -r backups backups_copy` — recursive copy
- `mv file1.txt renamed_file.txt` — rename
- `rm file3.txt` — remove (tested)
- `find find_lab -name "*.txt"` — find all txt files
- `man cp`, `tldr find` — quick help

## Lab structure

## Output example
$ find find_lab -type f -name "*.txt"
find_lab/a/file1.txt
find_lab/b/file2.txt
find_lab/c/file3.txt
