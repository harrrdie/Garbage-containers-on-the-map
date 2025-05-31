# 📊 Основной алгоритм (RU):
1. **Пользователь может загрузить ZIP архив** с фотографиями мусорных контейнеров.
2. **Пользователь может загрузить Excel файл** с данными о контейнерах.
3. Программа **читает данные** и извлекает:
   - **Номер площадки** (для сопоставления с фото)
   - **Широту**
   - **Долготу**
   - **Дополнительную информацию** (наименование, район, график)
4. В зависимости от **наличия фотографии** добавляется маркер с соответствующим **цветом** на карту:
   - 🟢 Зеленый - есть фото
   - 🔴 Красный - нет фото

---

# ⚙️ Набор технологий, инструментов и библиотек (RU):

## 🖥️ Языки программирования:
- **HTML5** – Структура страницы
- **CSS** – Стилизация элементов
- **JavaScript** – Основная логика приложения

## 📚 Библиотеки:
- **Leaflet** – Для работы с картами
- **SheetJS (xlsx)** – Для чтения Excel файлов
- **JSZip** – Для работы с ZIP архивами
- **Bootstrap 5.3.0** – Для оформления интерфейса

---

# 📊 Main Algorithm (EN):
1. **User can upload ZIP archive** with container photos
2. **User can upload Excel file** with container data
3. Program **reads data** and extracts:
   - **Site ID** (for photo matching)
   - **Latitude**
   - **Longitude**
   - **Additional info** (name, district, schedule)
4. Depending on **photo availability**, adds marker with corresponding **color**:
   - 🟢 Green - has photo
   - 🔴 Red - no photo

---

# ⚙️ Set of Technologies, Tools and Libraries (EN):

## 🖥️ Programming Languages:
- **HTML5** – Page structure
- **CSS** – Elements styling
- **JavaScript** – Application logic

## 📚 Libraries:
- **Leaflet** – For maps
- **SheetJS (xlsx)** – For Excel files
- **JSZip** – For ZIP archives
- **Bootstrap 5.3.0** – For UI styling
