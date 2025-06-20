# 🧙‍♂️ DND World Weave
**DND World Weave** — это минималистичное веб-приложение для онлайн-игры в Dungeons & Dragons в формате ваншотов. Разработано в рамках дипломной работы с акцентом на простоту, скорость запуска и базовые инструменты для мастера и игроков.

---

## ✨ Возможности
- 🎲 Броски кубиков в чате
- 🗺 Отображение карты и токенов
- 💬 Текстовый чат
- 🔊 Поддержка голосового общения (планируется)
- 🧑‍🤝‍🧑 Система лобби и сессий
- 🔐 Аутентификация через JWT
- 📦 Полностью разделённые frontend и backend

---

## 🛠️ Стек технологий
| Компонент     | Технологии                              |
|---------------|------------------------------------------|
| Backend       | Node.js, Express, Socket.IO              |
| База данных   | PostgreSQL + Prisma                      |
| Аутентификация| JWT                                      |
| Реалтайм      | WebSocket                                |
| Контейнеризация| Docker + docker-compose                 |
| Хранение      | AWS S3 (для файлов, если используется)  |

---

## 🚀 Быстрый старт

1. Клонируй репозиторий
git clone https://github.com/Nurkhan-Bakhitzhan/dnd_worldweave.git

2. Запусти backend
cd backend
npm install
npx prisma generate
npx prisma migrate dev
npm run dev

Убедись, что у тебя настроены .env переменные, включая DATABASE_URL

3. Запуск клиента (frontend)
cd frontend
npm install
npm run dev

📸 Скриншоты
![image](https://github.com/user-attachments/assets/f8bfe45c-b1f0-4357-a67a-18bc48ec34db)
![image](https://github.com/user-attachments/assets/7702823d-8647-4541-802d-53b22fd82799)
![image](https://github.com/user-attachments/assets/7ef480c5-bb48-4eeb-884b-70a2b9634b35)
![image](https://github.com/user-attachments/assets/98ff07b2-4e14-4fb5-b807-bd24b213f46e)
![image](https://github.com/user-attachments/assets/acc6594a-d19e-4977-b616-f546c854650e)
![image](https://github.com/user-attachments/assets/825d504a-1118-41bf-8484-900262435844)


📚 Контекст проекта
Этот проект разработан как часть дипломной работы. Его цель — создать базовый, но гибкий инструмент для проведения DnD-сессий без лишней сложности, с фокусом на взаимодействие между людьми, а не автоматизацию боя.  
