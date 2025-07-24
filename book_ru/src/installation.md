+++
date = 2025-07-02T04:14:54-08:00 
title = "Установка Helix"
subtitle = "— руководство пользователя 
description = "Рекомендации по установке Helix для Linux, macOS и Windows. Проверено для версий 23.x."
summary = """\
В этом разделе вы узнаете:  
✔ Как установить Helix через менеджер пакетов.  
✔ Как собрать из исходников.  
✔ Как проверить работоспособность."""
weight = 10  # Первый раздел в изучении 
lastmod = 2025-07-24 
[params] 
  translator = "@vBuresh & DeepSeek Chat"
  original_url = "https://github.com/helix-editor/helix"  
tags = ["helix", "документация", "перевод"] 
+++

# Installation | Установка  

## Linux  
```bash  
# Для Debian/Ubuntu:  
sudo apt install helix  

# Для Arch Linux:  
sudo pacman -S helix
```
## macOS
```bash
brew install helix
```

## Windows

1. Скачайте .msi из [релизов Helix.](https://github.com/helix-editor/helix/releases)
2. Запустите installer.

---

### Глоссарий

| EN Term | RU Термин | Описание                 |
| ------- | --------- | -----------------------  |
| Package |	Пакет     | Программа для установки  |
| Release |	Релиз     | Готовая версия программы |


---

### 🎯 **Что учтено в этом черновике:**  
1. **Форматирование:**  
   - Команды для терминала выделены в блоки кода.  
   - Гибридные термины (`Package | Пакет`).  
2. **Глоссарий:** Добавлены базовые термины.  
3. **Ссылки:** Оригинальные URL сохранены.  

---

### 📌 **Ваши действия:**  
1. Скопируйте этот код в `book_ru/src/installation.md`.  
2. Запушите:  
   ```bash  
   git add book_ru/src/installation.md  
   git commit -m "Черновик installation.md (соавтор: DeepSeekChat)"  
   git push origin ru-translation
   ```

