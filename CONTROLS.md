
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

- *input-repeater*
```yml
- name: social
  type: input-repeater
  label: Social Links
  help:
  schema:
    name: link
    type: text
  value: ['https://www.facebook.com/ThemeXpert','https://www.twitter.com/themexpert']
```

- *group-repeater*
```yml
- name: tabs
   type: group-repeater
   schema:
     - name: title
       value: Tab Title

     - name: content
       type: editor
       value: Lorem ipsum dolor sit amet timeam deleniti mnesarchum ex sed

     - name: enable_icon
       type: switch

     - name: icon
       type : icon
   value:
     - title: Tab Title
       content: Lorem ipsum dolor sit amet timeam deleniti mnesarchum ex sed
```

- *link*
```yml
- name : link
  type : link
  help : If you would like to make your blurb a link, input your destination URL here.
```

- *slider*
```yml
- name: icon_font_size
  type: slider
  lable: Icon Font Size
  value : 0
```
