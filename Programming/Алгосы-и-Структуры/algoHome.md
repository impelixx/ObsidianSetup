# 📘 Домашняя страница: algoHome


---

Добро пожаловать на домашнюю страницу **algoHome**. Здесь собраны все конспекты, учебные материалы и полезные ресурсы, чтобы вам было легче изучать этот предмет.

---

## 🗂️ Конспекты занятий
```dataview
table file.name as "📄 Конспект", file.ctime as "📅 Дата создания"
from ""
where contains(file.path, this.file.folder) and file.name != this.file.name
sort file.ctime desc
```
