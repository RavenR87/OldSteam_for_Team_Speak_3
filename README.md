# Old Steam for TeamSpeak 3

**[English](#english) · [Русский](#русский)**

Classic olive-green Steam (2004–2012) look for **TeamSpeak 3.6**: style, icon packs and a sound pack in one installer.

**Author:** RavenR87 · [Twitch](https://www.twitch.tv/ravenr87) · [Telegram](https://t.me/TGKRavenR87) · [YouTube](https://www.youtube.com/channel/UCJbRq7HqV6jTuShxuti1jhg)

<img width="1917" height="957" alt="Main window" src="https://github.com/user-attachments/assets/e7418474-0370-48e6-b0b8-edd4c98ba709" />
<img width="1913" height="887" alt="Options" src="https://github.com/user-attachments/assets/ccba4944-1a28-4efc-9c2a-a5c8814b1720" />
<img width="1917" height="950" alt="Server" src="https://github.com/user-attachments/assets/611153b5-4b08-4c47-b7fb-54652a889936" />
<img width="1748" height="882" alt="Voice settings" src="https://github.com/user-attachments/assets/7a1b42c7-e5b7-4244-bad2-ca6afc2ff0e3" />

---

## English

### Features
- **Style** — olive-green background, bevelled buttons, sunken inputs and lists, mustard selection, classic scrollbars with arrows, Tahoma font
- **Icon packs** — 213 custom icons + 10 emoticons in three sizes: **Small** (24px), **Medium** (32px), **Big** (40px)
- **Sound pack** — soft sounds in mid frequencies, no harsh highs
- **Easy to customize** — font and icon sizes are at the top of `OldSteam.qss`

### Install
1. Download `OldSteam_1.2.1_public.ts3_addon` from [Releases](../../releases)
2. Close TeamSpeak (also from the tray near the clock)
3. Double-click the downloaded file and confirm the installation
4. Open TeamSpeak → **Tools → Options → Design**: theme `OldSteam`, icon pack `OldSteamMedium` (or Small / Big)
5. **Tools → Options → Notifications**: sound pack `Old Steam`
6. Restart TeamSpeak

### Sounds
| Event | Sound |
|---|---|
| Someone joins your channel, you switch channel, you connect | soft two notes up |
| Someone leaves your channel | soft two notes down |
| You disconnect | three notes down |
| Microphone / sound on and off | short click with notes up or down |
| Private message, poke | two-note "message" sound |
| Error, no permission | two low notes |
| Kick, ban, connection lost, recording started | three low notes down |

Less important events (someone joins another channel, channel edits, etc.) are silent.

### Change font or icon size
1. Press **Win+R**, type `%APPDATA%\TS3Client\styles` and press Enter
2. Right-click `OldSteam.qss` → **Open with → Notepad**
3. At the top of the file, find the **РАЗМЕРЫ** (sizes) block:
   - `font-size: 14pt` — interface font
   - `qproperty-iconSize: 24px 24px` — icon size (keep both numbers equal)
4. Save (Ctrl+S) and restart TeamSpeak

Tip: use icon sizes that match your icon pack (Medium = 32px, Big = 40px).

### FAQ
**The window title bar is still white / blue.** The title bar is drawn by Windows, not by TeamSpeak, so a TeamSpeak style cannot change it.

**Something looks broken.** In **Options → Design** try setting the Qt style to **Fusion**.

**How do I uninstall?** Choose another theme, icon pack and sound pack first, then remove Old Steam in **Options → Addons**.

### Notes
- Tested on TeamSpeak 3.6.2 (Windows)
- Not affiliated with Valve Corporation or TeamSpeak Systems GmbH
- All icons and sounds are original

---

## Русский

### Что внутри
- **Стиль** — оливковый фон, объёмные кнопки, «вдавленные» поля и списки, горчичное выделение, классические полосы прокрутки со стрелками, шрифт Tahoma
- **Наборы значков** — 213 своих значков + 10 смайликов в трёх размерах: **Small** (24px), **Medium** (32px), **Big** (40px)
- **Набор звуков** — мягкие звуки на средних частотах, без резких высоких
- **Легко настроить** — размер шрифта и значков указан в начале файла `OldSteam.qss`

### Установка
1. Скачайте `OldSteam_1.2.1_public.ts3_addon` в разделе [Releases](../../releases)
2. Закройте TeamSpeak (в том числе в трее у часов)
3. Дважды щёлкните по скачанному файлу и подтвердите установку
4. Откройте TeamSpeak → **Инструменты → Настройки → Дизайн**: тема `OldSteam`, набор значков `OldSteamMedium` (или Small / Big)
5. **Инструменты → Настройки → Уведомления**: звуковой пакет `Old Steam`
6. Перезапустите TeamSpeak

### Звуки
| Событие | Звук |
|---|---|
| Кто-то зашёл в ваш канал, вы сменили канал, вы подключились | две мягкие ноты вверх |
| Кто-то вышел из вашего канала | две мягкие ноты вниз |
| Вы отключились | три ноты вниз |
| Микрофон / звук вкл. и выкл. | короткий щелчок с нотами вверх или вниз |
| Личное сообщение, тычок | двухнотный звук «сообщения» |
| Ошибка, нет прав | две низкие ноты |
| Кик, бан, потеря связи, начало записи | три низкие ноты вниз |

Менее важные события (кто-то зашёл в другой канал, правка каналов и т.д.) без звука.

### Как изменить размер шрифта или значков
1. Нажмите **Win+R**, введите `%APPDATA%\TS3Client\styles` и нажмите Enter
2. Правый щелчок по `OldSteam.qss` → **Открыть с помощью → Блокнот**
3. В начале файла найдите блок **РАЗМЕРЫ**:
   - `font-size: 14pt` — шрифт интерфейса
   - `qproperty-iconSize: 24px 24px` — размер значков (оба числа одинаковые)
4. Сохраните (Ctrl+S) и перезапустите TeamSpeak

Совет: ставьте размер значков под выбранный набор (Medium = 32px, Big = 40px).

### Вопросы
**Заголовок окна остался белым / синим.** Заголовок рисует Windows, а не TeamSpeak, поэтому стиль TeamSpeak не может его изменить.

**Что-то отображается криво.** В **Настройки → Дизайн** попробуйте выбрать стиль Qt **Fusion**.

**Как удалить?** Сначала выберите другую тему, набор значков и звуков, затем удалите Old Steam в **Настройки → Дополнения**.

### Примечания
- Проверено на TeamSpeak 3.6.2 (Windows)
- Не связано с Valve Corporation и TeamSpeak Systems GmbH
- Все значки и звуки созданы с нуля
