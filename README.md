# clock-widget-forum

![status](https://img.shields.io/badge/status-active-2ea44f?style=flat-square)
![type](https://img.shields.io/badge/type-forum_widget-blue?style=flat-square)
![version](https://img.shields.io/badge/version-1.0.0-fc4955?style=flat-square)
![license](https://img.shields.io/badge/license-MIT-lightgrey?style=flat-square)

Simple sidebar clock widget for forums.

Works on `Invision Community (IPS)` or any forum that allows custom HTML + JavaScript widgets.

---

## What it does

This widget shows a live clock with a date and a few timezones:

- local time (auto-detected)
- UTC
- New York
- Tokyo

Everything updates in real time without any backend or setup.

---

## Tech stacks

![HTML](https://img.shields.io/badge/HTML5-Structure-E34F26?style=for-the-badge\&logo=html5\&logoColor=white)
![CSS](https://img.shields.io/badge/CSS3-Styling-1572B6?style=for-the-badge\&logo=css3\&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-Logic-F7DF1E?style=for-the-badge\&logo=javascript\&logoColor=black)

---

## Install

Copy code, paste the full into a `PHP & TXT Widget` sidebar widget.

That’s it, no configuration.

---

## Demo

![Demo](https://img.shields.io/badge/demo-live-blue?style=for-the-badge\&logo=vercel)

👉 https://fersteldev.pl/clock-widget-forum.html

---

## Important

>[!NOTE]
>This widget relies on JavaScript. If your forum blocks scripts in widgets, it will not work.

>[!TIP]  
If you want accurate timezone handling, make sure your forum allows `Intl.DateTimeFormat`.

---

## Timezones used

Default configuration:

```js
UTC
America/New_York
Asia/Tokyo
```

## Custom timezones

You can change or add timezones by editing the `format()` in JavaScript section.

Example:

```js
document.getElementById("ny").innerText = format("America/New_York");
document.getElementById("tokyo").innerText = format("Asia/Tokyo");
document.getElementById("utc").innerText = format("UTC");
```

## Author

![Author](https://img.shields.io/badge/author-fersteldev-blue?style=for-the-badge)

---
