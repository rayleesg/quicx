# Quicx page builder rc1
Download: https://github.com/themexpert/quicx/files/121275/pkg_quicx-pro.zip

## Shortcuts
- `ctrl+s` (on layout builder)-> save page
- `ctrl+s` (on modal)-> update form + close modal
- `shift+s` (on modal)-> update form (does not close modal)+ save page
- `ctrl+p` -> open preview
- `ctrl+shift+p` (on layout builder) -> save page and open preview
- `shift+p` (on modal) -> updates form and opens preview (shift+s, ctrl+p combo)


## Elements
- [ ] slider
- [ ] testimonial
- [ ] testimonial-pro
- [ ] animated number
- [ ] bar counter
- [ ] circle counter
- [ ] contact form
- [ ] countdown timer
- [ ] email opt in
- [ ] carousel
- [ ] carousel pro
- [ ] gallery
- [ ] filterable gallery
- [ ] maps
- [ ] pricing table
- [ ] video slider
- [ ] social network follow icon
- [ ] pinterest gallery
- [ ] instagram gallery
- [ ] article
- [ ] audio


## Controls
- *select*
```yml
- name: type
  type: select
  value: accordion
  help: Expandable allow multiple sections to stay open.
  options:
    accordion: Accordion
    expandable: Expandable
```

- *typography*
```yml
- name: header_font
  type: typography
  label: Header Font
```

- *color*
```yml
- name: header_bg_color
  type: color
  label: Header Background
```

- *text*
```yml
- name: title
  type: text
```

- *textarea*
```yml
- name: content
  type: textarea
```

- *editor*
```yml
- name: content
  type: editor
```

- *switch*
```yml
- name: enable_icon
  type: switch
```

- *icon*
```yml
- name: icon
  type : icon
```

- *image*
```yml
- name: bg_image
  type: image
  label: Background Image
```

- *margin*
```yml
- name: margin
  type: margin
```

- *padding*
```yml
- name: margin
  type: margin
```
