# Lapathoniia Ecosystem Project Template

Це публічний шаблон репозиторію для проєктів, які хочуть бути доданими до
екосистеми Lapathoniia.

Якщо ваш сервіс, застосунок, дослідницький прототип або внутрішній інструмент
використовує Lapathoniia API, створіть власний репозиторій на основі цього
шаблону, заповніть `lapathoniia.project.json` і надішліть посилання на GitHub
репозиторій через форму екосистеми.

## Що потрібно зробити

1. Натисніть **Use this template** у GitHub.
2. Створіть публічний репозиторій для свого проєкту.
3. Відредагуйте `lapathoniia.project.json`.
4. Замініть `assets/logo.svg` на логотип вашого проєкту.
5. За бажанням замініть `assets/cover.svg` на обкладинку або скріншот.
6. Надішліть URL репозиторію у форму Lapathoniia Ecosystem.

## Структура

```text
lapathoniia.project.json
assets/
  logo.svg
  cover.svg
docs/
  submission-checklist.md
README.md
```

## Manifest

Основний файл:

```text
lapathoniia.project.json
```

У ньому має бути публічна інформація, яку можна показати на сайті та в
застосунках Lapathoniia.

```json
{
  "name": "Назва проєкту",
  "team": "Назва команди або організації",
  "description_uk": "Короткий опис українською.",
  "description_en": "Short English description.",
  "website": "https://example.com",
  "demo": "https://example.com/demo",
  "github": "https://github.com/your-org/your-repo",
  "logo": "assets/logo.svg",
  "cover": "assets/cover.svg",
  "category": "education",
  "models": [
    "LapaLLM-Gemma-3-12B-v0.1.2-instruct"
  ],
  "contact_email": "team@example.com"
}
```

## Категорії

Рекомендовані значення для `category`:

```text
education
research
business
developer-tools
content
public-sector
healthcare
legal
other
```

## Моделі

Вкажіть моделі Lapathoniia, які використовує ваш проєкт:

```text
LapaLLM-Gemma-3-12B-v0.1.2-instruct
MamayLM-Gemma-3-12B-IT-v1.0
```

## Важливо

Не додавайте в репозиторій:

- Lapathoniia API keys;
- паролі;
- приватні email-списки;
- персональні дані користувачів;
- приватні логи запитів;
- production `.env` файли.

Цей репозиторій має містити лише інформацію, яку можна публічно показувати.

## Публікація в екосистемі

Після відправлення GitHub URL ми надішлемо лист-підтвердження на email, з яким
ви реєстрували beta-доступ до Lapathoniia.

Проєкт з'явиться в екосистемі після підтвердження та модерації.

Lapathoniia може показувати проєкти на сайті, у застосунках і в weekly activity
блоках. Ранжування може базуватися на агрегованій API-активності за останні 7
днів. API-ключі, приватні запити, email-адреси та точні технічні логи не
публікуються.

