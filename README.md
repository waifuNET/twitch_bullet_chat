# 🌸 WaifNET — Twitch Bullet Chat Overlay

🎥 Лёгкий HTML-оверлей для OBS с "пулевыми" (плавающими) сообщениями чата в стиле японских стримов. Работает с Twitch, не требует логина. Поддерживает цветные ники и смайлики.

🎥 Lightweight HTML overlay for OBS with danmaku-style (floating) chat messages like Japanese livestreams. Works with Twitch, no login required, supports colors and emotes.

---

## 🔧 Настройка / Configuration

Настройка выполняется через параметры в URL:

| Параметр | Описание (RU)                                | Description (EN)                               | Пример |
|----------|-----------------------------------------------|------------------------------------------------|--------|
| `channel` | Ник Twitch-канала                              | Twitch channel name                            | `?channel=aivamorn` |
| `rect`    | Вертикальный диапазон отображения в %, top-bottom | Vertical position range in %, top-bottom        | `&rect=0,100` |
| `speed` *(опционально)* | Скорость полёта текста в px/сек         | Scrolling speed in pixels per second            | `&speed=150` |

---

## 🔗 Пример использования

**GitHub Pages:**

👉 [https://waifunet.github.io/twitch_bullet_chat/?channel=aivamorn&rect=0,100](https://waifunet.github.io/twitch_bullet_chat/?channel=aivamorn&rect=0,100)

📌 Можно вставить прямо в OBS или браузер.

---

## 🎮 Использование с OBS

1. В OBS выбери `Добавить` → `Browser Source`  
2. Вставь ссылку, как выше  
3. Установи размер: `1920x1080`  
4. Поставь галочку: ✅ `Allow Transparency`  
5. Готово!

---

## 💖 Особенности

- ✅ Цветные ники как на Twitch
- ✅ Поддержка обычных и GIF смайликов
- ✅ Сообщения в случайной позиции по вертикали
- ✅ Полностью работает без авторизации
- ✅ Поддержка OBS и прозрачности
- ⚙️ Параметры в URL: быстро и удобно
