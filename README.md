# Quicx page builder rc1
Download: https://github.com/themexpert/quicx/files/121275/pkg_quicx-pro.zip

## Shortcuts
- `ctrl+s` (on layout builder)-> save page
- `ctrl+s` (on modal)-> update form + close modal
- `shift+s` (on modal)-> update form (does not close modal)+ save page
- `ctrl+p` -> open preview
- `ctrl+shift+p` (on layout builder) -> save page and open preview
- `shift+p` (on modal) -> updates form and opens preview (shift+s, ctrl+p combo)

## Controls
- select
```yml
    - name: type
      type: select
      value: accordion
      help: Accordion allow one section to stay open at a time. Expandable allow multiple sections to stay open.
      options:
        accordion: Accordion
        expandable: Expandable
```
