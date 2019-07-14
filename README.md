# ifd-highlighter

Highlighter for ifd file(interactive fiction data)

## Usage

Ifd is a kind of file based on YAML, its a part of [if-maker](https://github.com/DiscreteTom/if-maker).

This extension provide syntax highlighting and code snippets for ifd files.

## Ifd schema

```yaml
include:
  - other ifd file name
item-id:
  name: string
  description: string
  classes:
    - class name
  onMount: |
    python code here
    ^
  onUnmount: |
    python code here
    ^
  data:
    any data here
  actions:
    - name: string
      code: |
        python code here
        ^
```