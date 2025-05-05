## 📦 Download

You can download the latest version here:  
👉 [📥 Download Clipboard Text Reader (RAR file)](https://drive.google.com/file/d/1Sc2W-eWm5jo6GIqzHVCfGfiO80IdBgk7/view?usp=sharing)
🎯 The program is written in Python. The archive includes the source code — feel free to modify and improve it as you like.

# 📋 Clipboard Text Reader

A small utility that reads text from the clipboard aloud.  
Designed for use with subtitle OCR tools like **LunaTranslator**. > 📌(https://docs.lunatranslator.org/en/)


---

## How I use it

I use this program together with **LunaTranslator**, which captures subtitles from the screen using OCR and copies them to the clipboard.

Yes, LunaTranslator has built-in text-to-speech, but it often stutters or repeats text.  
So I created my own tool to solve that.

### Steps:
1. Launch LunaTranslator, set the screen capture area, enable OCR, and clipboard output.
2. Run **Clipboard Text Reader**, press **Start/Stop**.  
   After stopping, new text from the clipboard will be read — not the previous one.

### Features:
- Smart text filtering: avoids repeating the same lines.
- Adjustable similarity threshold for saving and reading.
- Voice selection (uses system-installed voices).
- Hotkeys can be customized in `Settings.ini`.

---

## 🤔 Why I created this

In games without voice-over, reading subtitles during intense action scenes is inconvenient.  
So I built a tool to help — it reads subtitles out loud automatically.

---

## 🇷🇺 Описание на русском
> 🎯 Программа написана на Python. В архиве прилагается исходный код — можно дорабатывать и улучшать.

Маленькая программа для озвучивания текста из буфера обмена.  
Отлично работает в связке с **LunaTranslator** (распознаёт субтитры с экрана и копирует в буфер).

В отличие от встроенной озвучки в Луне, здесь нет заиканий и повторов.

### Как пользоваться:
1. Запускаем LunaTranslator: настраиваем захват экрана, включаем OCR и вывод текста в буфер.
2. Запускаем эту программу, нажимаем **Старт/Стоп**.
   После паузы программа начнёт читать **новый** текст, а не старый.

### Возможности:
- Умное сравнение текста, чтобы не повторялся.
- Настройка процентов схожести для сохранения и чтения текста.
- Выбор голоса (если установлен в системе).
- Горячие клавиши задаются в `Settings.ini`.

---

> ⚙️ Created with help from ChatGPT and Gemini  
> If needed, I can share my LunaTranslator settings too.
