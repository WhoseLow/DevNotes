---
creation date: <% tp.file.creation_date() %>
tags: daily_note <% tp.file.title.split('-') %>
type: daily_note
---

# <% tp.file.title %> 
<< [[<% tp.date.now("YYYY-MM-DD", -1, tp.file.title, "YYYY-MM-DD") %>]] | [[<% tp.date.now("YYYY-MM-DD", 1, tp.file.title, "YYYY-MM-DD") %>]]>> 

## Tasks

#### Over Due
```tasks

not done

due before <% tp.date.now("YYYY-MM-DD") %>

```

#### Due Today
```tasks

not done

due on <% tp.date.now("YYYY-MM-DD") %>

path does not include Templates

```

#### New Today




## Other Tasks

#### No Due Date
```tasks

not done

no due date

path does not include Templates

```

#### Done Today

```tasks

done on <% tp.date.now("YYYY-MM-DD") %>

path does not include Templates

```
