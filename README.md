# Лендинг Нейроключ

Готовый лендинг для обучающего курса по ChatGPT и нейро-ассистентам.

## 🚀 Быстрая публикация на GitHub Pages

### Шаг 1: Создайте репозиторий на GitHub

1. Откройте https://github.com/new
2. Введите название репозитория: `neurokey-landing`
3. Выберите **Public**
4. **НЕ** добавляйте README, .gitignore или лицензию
5. Нажмите **Create repository**

### Шаг 2: Загрузите файлы

После создания репозитория GitHub покажет команды. Скопируйте **ваш URL репозитория** (он будет выглядеть как `https://github.com/ВАШ_USERNAME/neurokey-landing.git`)

Затем выполните эти команды в терминале (в папке с распакованными файлами):

```bash
# Добавьте ваш репозиторий (ЗАМЕНИТЕ URL на ваш!)
git remote add origin https://github.com/ВАШ_USERNAME/neurokey-landing.git

# Отправьте файлы на GitHub
git push -u origin main
```

**Если Git попросит авторизацию:**
- Введите ваш GitHub username
- В качестве пароля используйте Personal Access Token (не обычный пароль!)
- Как создать токен: https://github.com/settings/tokens

### Шаг 3: Включите GitHub Pages

1. Перейдите в ваш репозиторий на GitHub
2. Откройте **Settings** → **Pages**
3. В разделе **Source** выберите:
   - Branch: `main`
   - Folder: `/ (root)`
4. Нажмите **Save**

Через 1-2 минуты сайт будет доступен по адресу:
```
https://ВАШ_USERNAME.github.io/neurokey-landing/
```

### Шаг 4: Подключите свой домен (опционально)

1. В настройках Pages введите ваш домен в поле **Custom domain**
2. У вашего регистратора домена добавьте DNS-записи:

**Для корневого домена (example.com):**
```
A запись → 185.199.108.153
A запись → 185.199.109.153
A запись → 185.199.110.153
A запись → 185.199.111.153
```

**Для поддомена (www.example.com или key.example.com):**
```
CNAME запись → ВАШ_USERNAME.github.io
```

3. Подождите 5-30 минут для обновления DNS
4. GitHub автоматически установит SSL-сертификат

## 📁 Структура файлов

```
neurokey-landing/
├── index.html              # Главная страница
├── assets/                 # Стили и JavaScript
│   ├── index-xxx.css
│   └── index-xxx.js
├── logo.png               # Логотип
├── photo1.jpg             # Фото для героя
├── photo2.jpg             # Фото "Что ты получишь"
├── photo3.jpg             # Фото "Программа"
├── photo4.jpg             # Фото "Бонус"
├── photo5.png             # Фото автора
├── testimonial.png        # Скриншот отзыва
├── .htaccess             # Настройки для Apache
└── README.md             # Эта инструкция
```

## 🔧 Обновление сайта

Чтобы обновить сайт после изменений:

```bash
git add .
git commit -m "Описание изменений"
git push
```

Изменения появятся на сайте через 1-2 минуты.

## ❓ Частые вопросы

### Сайт не открывается
- Подождите 2-3 минуты после включения Pages
- Проверьте, что выбрана ветка `main` и папка `/ (root)`
- Убедитесь, что репозиторий Public

### Как изменить цену или текст?
- Отредактируйте файл `index.html`
- Выполните команды обновления (см. выше)

### Как добавить свои изображения?
- Замените файлы photo1.jpg, photo2.jpg и т.д.
- Выполните команды обновления

### Git просит пароль
- Используйте Personal Access Token вместо пароля
- Создайте токен: Settings → Developer settings → Personal access tokens → Tokens (classic) → Generate new token
- Выберите scope: `repo`

## 📞 Поддержка

Если возникли проблемы:
- Документация GitHub Pages: https://docs.github.com/pages
- Проверьте статус GitHub: https://www.githubstatus.com

## 📄 Лицензия

Все права принадлежат автору курса - Оле Стукаловой (MALINKA.LAB)

---

**Готово к публикации!** Следуйте инструкциям выше для размещения на GitHub Pages.

