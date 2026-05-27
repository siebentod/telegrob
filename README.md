# Telegrob

Кастомный телеграм клиент с расширенным функционалом плеера с ластфм скробблером + возможностью сортировать посты в канале по популярности и другие понадобившиеся мне функции

- Вход по QR.
- Каталог постов в SQLite; навигация и ссылки на посты.
- Скачивание медиа и массовая выгрузка аудио в выбранную папку.
- Нативное воспроизведение музыки из постов (буфер, очередь, seek).
- Глобальная очередь и трей.

## Screenshots

<table style="width:100%;border-collapse:collapse;">
	<tr>
		<td style="width:50%;padding:4px;vertical-align:top;">
			<img src="public/screenshots/telegrob-1.png" alt="Telegrob - Main view" style="width:100%;height:auto;" />
		</td>
		<td style="width:50%;padding:4px;vertical-align:top;">
			<img src="public/screenshots/telegrob-2.png" alt="Telegrob - Channel view" style="width:100%;height:auto;" />
		</td>
	</tr>
</table>

## Структура проекта

```
src/
├── assets/
├── components/
├── db/
├── hooks/
├── lib/
├── pages/
├── store/
└── App.tsx
src-tauri/
└── src/
    ├── lastfm/
    ├── telegram/
    ├── app_tray.rs
    ├── lib.rs
    └── main.rs
```

## Technologies

- React, TypeScript, Vite
- Tauri for desktop
- grammers, Drizzle, SQLite, TailwindCSS, Zustand
