# Політика конфіденційності — Фітнес Трекер

**Дата останнього оновлення:** 26 липня 2026 р.

Цей документ описує, які дані збирає застосунок **Фітнес Трекер** (пакет `com.fitness.tracker`) та як вони використовуються.

## 1. Хто ми

Фітнес Трекер розробляється незалежним розробником. З питань щодо цієї політики або ваших даних звертайтесь: **foxiho.dev@gmail.com**.

## 2. Які дані ми збираємо

### 2.1. Дані, що зберігаються лише на вашому пристрої
Ці дані **ніколи не покидають ваш телефон** і не передаються нам чи будь-кому іншому:
- Історія тренувань (вправи, підходи, повторення, вага, тривалість, калорії)
- Параметри тіла (вага, зріст)
- Шаблони тренувань
- Досягнення та серії тренувань (streaks)
- Налаштування застосунку (мова, одиниці виміру)

Ці дані зберігаються в локальній базі даних на вашому пристрої (Room/SQLite) і видаляються повністю, якщо ви видалите застосунок.

### 2.2. Дані кроків (Health Connect)
Якщо ви надаєте дозвіл, застосунок читає дані про кількість кроків через **Android Health Connect** та/або сенсор кроків вашого пристрою — виключно для показу вашої денної/тижневої статистики кроків усередині застосунку. Ці дані не передаються третім сторонам.

### 2.3. Дані, що надсилаються для AI-аналізу (Google Gemini API)
Якщо ви користуєтесь функцією **AI-аналізу** у вашому профілі, окремі дані (наприклад, статистика тренувань чи параметри тіла, які ви бачите на екрані аналізу) надсилаються до **Google Gemini API** (Generative Language API) для генерації персоналізованих порад. Обробка цих даних регулюється [Політикою конфіденційності Google](https://policies.google.com/privacy). Ми не зберігаємо копії цих запитів на власних серверах — у нас немає власних серверів; запит іде напряму з вашого пристрою до Google.

### 2.4. Реклама
Наразі рекламні мережі (Google AdMob) **не активні** в застосунку. Якщо рекламу буде увімкнено в майбутньому, цю політику буде оновлено відповідно, із зазначенням, які дані збирає рекламна мережа.

## 3. Чого ми НЕ робимо
- Ми не вимагаємо реєстрації чи входу через акаунт.
- Ми не продаємо та не передаємо ваші особисті дані третім сторонам у комерційних цілях.
- Ми не збираємо ваші дані на власних серверах — застосунок працює локально, за винятком запитів до Health Connect (сенсори пристрою) та Gemini API (лише за вашою явною дією).

## 4. Дозволи застосунку
| Дозвіл | Навіщо потрібен |
|---|---|
| Фізична активність (Activity Recognition) | Підрахунок кроків |
| Health Connect (кроки) | Синхронізація даних кроків з інших джерел (наприклад, Mi Fitness) |
| Сповіщення | Нагадування про тренування, індикатор активного тренування |
| Точні будильники (Exact Alarms) | Своєчасні нагадування про тренування у вибраний вами час |

## 5. Видалення даних
Оскільки всі особисті дані зберігаються локально на вашому пристрої, ви можете видалити їх у будь-який момент:
- Видаливши застосунок, або
- Очистивши дані застосунку через Налаштування Android → Застосунки → Фітнес Трекер → Очистити дані.

## 6. Діти
Застосунок не призначений для дітей віком до 13 років і свідомо не збирає дані дітей цієї вікової категорії.

## 7. Зміни до цієї політики
Ми можемо оновлювати цю політику конфіденційності. Дата останнього оновлення завжди вказана вгорі документа.

## 8. Контакти
З питань щодо цієї політики: **foxiho.dev@gmail.com**

---

# Privacy Policy — Fitness Tracker (English)

**Last updated:** July 26, 2026

This document describes what data the **Fitness Tracker** app (package `com.fitness.tracker`) collects and how it is used.

## 1. Who we are

Fitness Tracker is developed by an independent developer. For any questions about this policy or your data, contact: **foxiho.dev@gmail.com**.

## 2. What data we collect

### 2.1. Data stored only on your device
This data **never leaves your phone** and is never sent to us or anyone else:
- Workout history (exercises, sets, reps, weight, duration, calories)
- Body parameters (weight, height)
- Workout templates
- Achievements and workout streaks
- App settings (language, units)

This data is stored in a local database on your device (Room/SQLite) and is fully deleted if you uninstall the app.

### 2.2. Step data (Health Connect)
If you grant permission, the app reads your step count via **Android Health Connect** and/or your device's step sensor — solely to display your daily/weekly step statistics within the app. This data is not shared with third parties.

### 2.3. Data sent for AI analysis (Google Gemini API)
If you use the **AI analysis** feature in your profile, certain data (such as workout statistics or body parameters shown on the analysis screen) is sent to the **Google Gemini API** (Generative Language API) to generate personalized advice. This processing is governed by [Google's Privacy Policy](https://policies.google.com/privacy). We do not keep copies of these requests on our own servers — we don't operate any servers; the request goes directly from your device to Google.

### 2.4. Advertising
Advertising networks (Google AdMob) are **not currently active** in the app. If ads are enabled in the future, this policy will be updated accordingly, specifying what data the ad network collects.

## 3. What we do NOT do
- We do not require account registration or login.
- We do not sell or share your personal data with third parties for commercial purposes.
- We do not collect your data on our own servers — the app works locally, except for requests to Health Connect (device sensors) and the Gemini API (only upon your explicit action).

## 4. App permissions
| Permission | Why it's needed |
|---|---|
| Physical Activity Recognition | Step counting |
| Health Connect (steps) | Syncing step data from other sources (e.g. Mi Fitness) |
| Notifications | Workout reminders, active workout indicator |
| Exact Alarms | Timely workout reminders at your chosen time |

## 5. Data deletion
Since all personal data is stored locally on your device, you can delete it at any time by:
- Uninstalling the app, or
- Clearing app data via Android Settings → Apps → Fitness Tracker → Clear Data.

## 6. Children
The app is not directed at children under 13 and does not knowingly collect data from children in this age group.

## 7. Changes to this policy
We may update this privacy policy from time to time. The last updated date is always shown at the top of this document.

## 8. Contact
For questions about this policy: **foxiho.dev@gmail.com**
