# Birthdayy Page 🎉🎂

A feature-rich, delightful web application engineered to help you effortlessly track birthdays, manage personal relationship milestones, and send automated wishes so you never miss celebrating your friends, family, and colleagues' special days.

---

## 🌟 Key Features

* **Chronological Birthday Dashboard**: Visualizes upcoming birthdays sorted by date, complete with live countdown timers and age indicators.
* **Smart Reminders & Notification System**: Sends proactive alerts ahead of time, giving you ample opportunity to prepare cards, gifts, or messages.
* **Custom Message & Wish Generator**: Integrated templates to quickly draft or generate personalized birthday wishes tailored for each recipient.
* **Comprehensive Contact Management**: Easily add, edit, or remove birthdays along with important notes, zodiac signs, gift ideas, and category tags (e.g., Family, Friends, Work).
* **Data Persistence**: Stores your contacts safely using local storage or cloud synchronization so your data is always accessible.
* **Responsive & Delightful UI**: Designed with a clean, modern aesthetic for seamless usage across desktop and mobile browsers.

---

## 🛠️ Built With
Frontend: React / Next.js / Vanilla JavaScript

Styling: Tailwind CSS / Custom CSS

Date Manipulation: Native JavaScript Date API / Date-fns

Storage: Browser LocalStorage

--

## 🏗️ Project Architecture & Structure

The codebase is organized into a modular structure to keep components, utility functions, and state management clean and maintainable:

```text
Birthdayy/
│
├── public/                # Static assets, icons, and images
├── src/
│   ├── components/        # Reusable UI widgets (cards, modals, notification banners)
│   ├── context/           # State management for contacts, themes, and reminders
│   ├── utils/             # Helper functions (date formatting, countdown logic)
│   ├── App.jsx            # Root application component
│   └── main.jsx           # Application entry point
