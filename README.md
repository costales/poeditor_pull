# What is this?

A shell script that exports all translations from POEditor in `po` format, calling its API.

# Run it

`python3 poeditor_pull.py`

# Needs

Linux shell.

Dependencies: `python3 python3-request python3-ujson`

Before launch it, export your POEditor API keys:

```
export poeditor_api=12345678901234567890
export poeditor_id=123456
```
