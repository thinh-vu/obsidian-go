---
aliases: [{{date:YYYY-MM-DD}}]
---
🗓  {{date:YYYY-MM-DD}} {{time:HH:mm}}
___
# Mood 😄

# Today I learned 🧭

# Summary 💬

# Journey ⛵️

# Tag 🔖

# Person 🙋‍♂️

# Media 📸

# On this day 🧠
```dataview
table
from ""
where contains(file.name, "{{date:-DD}}") and contains(file.name, "{{date:-MM-}}") = false or contains(file.name, "{{date:-DD-DD}}") = true

```