# 🍌 Banana Dial Player

**Banana Dial** — это интерактивный музыкальный проект от [Andr oDei](https://indexmod.xyz), в котором банан вращается по кругу и воспроизводит 12 песен на разных языках мира. Просто тапни по банану и наслаждайся!

## 🌀 Как работает

* На экране — круг с числами от 1 до 12, как циферблат.
* В центре — банан, указывающий на текущее число.
* При каждом клике:

  * банан поворачивается на 30° по часовой стрелке,
  * проигрывается следующая песня из папки `/audio`.

## 📁 Структура проекта

```
/
├── index.html
├── /img/
│   └── banana.png
├── /audio/
│   ├── 01-Tri-Banana-russian.m4a
│   ├── 02-Le-Banana-Split-french.m4a
│   ├── ...
│   └── 12-Banana-Boat-Song-german.m4a
├── /favicon/
│   └── ... иконки сайта
```

## 🌍 Языки треков

Russian, French, English, Chinese, Hebrew, Portuguese, Swedish, Turkish, Japanese, Hindi, German.

## 🧪 Запуск

1. Клонируй репозиторий:

   ```bash
   git clone https://github.com/yourname/banana-dial.git
   ```
2. Открой `index.html` в браузере.
3. Наслаждайся.

## 📦 Зависимости

Никаких — работает на чистом HTML/CSS/JS без библиотек.

## 🧠 OG-интеграция

Поддержка Open Graph:

* `og:title`: Banana Dial by Andr oDei
* `og:description`: Tap the banana to spin and play music from around the world: Russian, French, English, Chinese, Hebrew, Portuguese, Swedish, Turkish, Japanese, Hindi, German.
* `og:image`: `/img/banana.png`

## 🥁 Автор

[Andr oDei](https://indexmod.xyz) — исследователь ритмов, языков и фруктов 🍌
