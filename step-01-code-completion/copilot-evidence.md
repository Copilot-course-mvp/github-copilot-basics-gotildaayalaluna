
# Copilot Evidence — Step 01

## Prompt 1

`Complete the normalize_username function following the docstring rules: trim, lowercase, replace spaces with underscores, remove invalid chars, collapse repeated underscores, and strip leading/trailing underscores.`

## Why you accepted/rejected the suggestion

Accepted — Copilot generated the correct sequence of str.strip(), str.lower(), str.replace(), and re.sub() calls matching all six rules in the docstring. The output passed the test cases on the first try.

## Final check

Also implemented build_slug using re.sub to replace non-alphanumeric sequences with a single hyphen and stripping edge hyphens. Both functions pass all unit tests.
