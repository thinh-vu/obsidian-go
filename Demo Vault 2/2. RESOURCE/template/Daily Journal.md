---

aliases: [{{date:YYYY-MM-DD}}]
---

🗓  {{date:YYYY-MM-DD}} {{time:HH:mm}}

___

# Win the Day ✨

# Reflection 💬

# On this day 🧠

```dataview
table
from ""
where contains(file.name, "{{date:-DD}}") and contains(file.name, "{{date:-MM-}}") = false or contains(file.name, "{{date:-DD-DD}}") = true
```