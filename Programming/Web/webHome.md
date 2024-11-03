# 📘 Домашняя страница: webHome


---

Добро пожаловать на домашнюю страницу по **webHome**. Здесь собраны все конспекты, учебные материалы и полезные ресурсы, чтобы вам было легче изучать этот предмет.

---

## 🗂️ Конспекты занятий

```dataview
table file.name as "📄 Конспект", file.ctime as "📅 Дата создания"
from ""
where contains(file.path, this.file.folder) and file.name != this.file.name
sort file.ctime desc
```
