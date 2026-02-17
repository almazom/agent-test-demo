---
name: AI Auto-Fixer
on: push
engine: copilot
permissions:
  contents: read
  # ❌ УДАЛИТЕ СТРОКУ НИЖЕ (она вызывает ошибку):
  # pull-requests: write

safe-outputs:
  create-pull-request:
    title-prefix: "[Auto-Fix] "
    draft: true
---

# Инструкция для Агента...
(оставьте остальной текст без изменений)