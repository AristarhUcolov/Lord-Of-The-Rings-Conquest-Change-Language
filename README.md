# 🎮 Lord of The Rings: Conquest - Language Changer
### Смена языка игры "Властелин Колец: Противостояние"

[English](#english) | [Русский](#russian)

---

## <a name="english"></a>🇬🇧 English

### 📖 Description
This repository provides Windows Registry files that allow you to change the language of **The Lord of the Rings: Conquest** game between English and Russian.

The game doesn't have a built-in language switcher in the settings menu, so changing the language requires modifying Windows Registry entries. This tool simplifies the process by providing pre-configured `.reg` files.

### 📋 Requirements
- Windows Operating System (7, 8, 10, 11)
- The Lord of the Rings: Conquest game installed
- Administrator privileges to modify Windows Registry

### 🚀 How to Use

#### To Switch to English:
1. Download or save the file: `Lord of The Rings - English.reg`
2. Double-click the file
3. Click **"Yes"** when Windows asks for confirmation
4. Click **"OK"** when the registry modification is complete
5. Launch the game - it will now be in English

#### To Switch to Russian:
1. Download or save the file: `Lord of The Rings - Russian.reg`
2. Double-click the file
3. Click **"Yes"** when Windows asks for confirmation
4. Click **"OK"** when the registry modification is complete
5. Launch the game - it will now be in Russian

### ⚠️ Important Notes
- **Always create a system restore point** before modifying the Windows Registry
- These files modify the following registry keys:
  - `HKEY_LOCAL_MACHINE\SOFTWARE\WOW6432Node\Electronic Arts\The Lord of the Rings - Conquest`
  - `HKEY_LOCAL_MACHINE\SOFTWARE\WOW6432Node\Electronic Arts\The Lord of the Rings - Conquest\1.0`
- The paths in the registry files assume standard installation directories. If your game is installed elsewhere, you may need to edit the `.reg` files manually
- Close the game completely before applying the registry changes

### 🔧 Troubleshooting
**Language didn't change after applying the .reg file:**
- Make sure you ran the file as Administrator
- Verify that the game is installed in the default directory
- Try restarting your computer
- Check that you closed the game before applying changes

**Game won't start after language change:**
- Restore your system to a previous restore point
- Reinstall the game if necessary

### 📝 How It Works
The registry files modify two main settings:
- `Locale`: Changes to "en" for English or "ru" for Russian
- `Language`: Sets the language code (1 for English, 16 for Russian)
- `LanguageName`: Sets the display name of the language

### 📄 License
This project is provided as-is for educational and convenience purposes. The Lord of the Rings: Conquest is owned by Electronic Arts.

---

## <a name="russian"></a>🇷🇺 Русский

### 📖 Описание
Этот репозиторий содержит файлы реестра Windows, которые позволяют изменить язык игры **Властелин Колец: Противостояние** между английским и русским.

В игре нет встроенного переключателя языка в меню настроек, поэтому для смены языка требуется изменить записи в реестре Windows. Этот инструмент упрощает процесс, предоставляя предварительно настроенные `.reg` файлы.

### 📋 Требования
- Операционная система Windows (7, 8, 10, 11)
- Установленная игра "Властелин Колец: Противостояние"
- Права администратора для изменения реестра Windows

### 🚀 Как использовать

#### Переключение на английский язык:
1. Скачайте или сохраните файл: `Lord of The Rings - English.reg`
2. Дважды кликните по файлу
3. Нажмите **"Да"**, когда Windows попросит подтверждение
4. Нажмите **"OK"**, когда изменение реестра завершится
5. Запустите игру - теперь она будет на английском языке

#### Переключение на русский язык:
1. Скачайте или сохраните файл: `Lord of The Rings - Russian.reg`
2. Дважды кликните по файлу
3. Нажмите **"Да"**, когда Windows попросит подтверждение
4. Нажмите **"OK"**, когда изменение реестра завершится
5. Запустите игру - теперь она будет на русском языке

### ⚠️ Важные примечания
- **Всегда создавайте точку восстановления системы** перед изменением реестра Windows
- Эти файлы изменяют следующие ключи реестра:
  - `HKEY_LOCAL_MACHINE\SOFTWARE\WOW6432Node\Electronic Arts\The Lord of the Rings - Conquest`
  - `HKEY_LOCAL_MACHINE\SOFTWARE\WOW6432Node\Electronic Arts\The Lord of the Rings - Conquest\1.0`
- Пути в файлах реестра предполагают стандартные директории установки. Если ваша игра установлена в другом месте, возможно, потребуется вручную отредактировать `.reg` файлы
- Полностью закройте игру перед применением изменений реестра

### 🔧 Решение проблем
**Язык не изменился после применения .reg файла:**
- Убедитесь, что вы запустили файл от имени администратора
- Проверьте, что игра установлена в стандартную директорию
- Попробуйте перезагрузить компьютер
- Убедитесь, что игра была закрыта перед применением изменений

**Игра не запускается после смены языка:**
- Восстановите систему до предыдущей точки восстановления
- При необходимости переустановите игру

### 📝 Как это работает
Файлы реестра изменяют два основных параметра:
- `Locale`: Меняется на "en" для английского или "ru" для русского
- `Language`: Устанавливает код языка (1 для английского, 16 для русского)
- `LanguageName`: Устанавливает отображаемое название языка

### 📄 Лицензия
Этот проект предоставляется как есть в образовательных целях и для удобства. Права на игру "Властелин Колец: Противостояние" принадлежат Electronic Arts.
