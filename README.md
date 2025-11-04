# 🏙️ Інформаційний портал "Одеса для дітей"

**Мета проєкту:** створити єдиний онлайн-ресурс для об’єднання інформації про навчання, медицину, дозвілля та розвиток дітей в Одесі.

## 🎯 Основна ідея
Портал об'єднує освітні, медичні та культурні сервіси міста, надає оновлюваний календар подій, інтерактивну карту установ, відеоуроки та зручний пошук для батьків і школярів.

## ⚙️ Технології
**Back-End:** ASP.NET Core, C#  
**База даних:** **Azure Cosmos DB** (NoSQL, масштабована модель)  
**Кешування:** Серверне кешування через `IMemoryCache`
**ORM / доступ до даних:** адаптовані репозиторії / SDK для Cosmos DB  
**Front-End:** React / Vue (SPA), адаптивний UI (Bootstrap / TailwindCSS), інтерактивна карта (Leaflet.js / Google Maps)  
**DevOps:** Docker, CI/CD (GitHub Actions)

## 💡 Основні можливості
- Єдина точка доступу до міських сервісів  
- Оновлюваний календар подій  
- Інтерактивна карта закладів  
- Онлайн-уроки через YouTube API  
- Панель адміністратора для контент-менеджменту  

## 🧠 Архітектура
- Клієнт–серверна модель із REST API на ASP.NET Core  
- Дані зберігаються у Cosmos DB — гнучка схема, оптимізована під читання/пошук  
- Короткочасні запити та результати кешуються локально на сервері через `IMemoryCache`  

## 👥 Команда
| Роль | Учасник |
|------|----------|
| Scrum Master | Керівник проєкту | Крістіна Черкезян |
| UI/UX Designer | Інна Ночовкіна  |
| Front-End Developer | Євген Нечипуренко | 
| **Back-End Developer** | **Олександр Єлєнок** |
| DevOps Engineer |Іван Сливняк|

## 🔮 Подальший розвиток
- Мобільний застосунок (Android/iOS)  
- Онлайн-щоденник школяра  
- Рейтинги та відгуки закладів  
- Інтеграція з міським проєктом “Місто Одеса”

========================================================================================================================================================================================

# 🏙️ "Odesa for Children" – Information Portal

**Project Goal:** to create a unified online resource that brings together information about education, healthcare, leisure, and child development in Odesa.

## 🎯 Main Idea
The portal unites educational, medical, and cultural city services.
It provides an up-to-date events calendar, an interactive institutions map, online lessons, and a convenient search interface for parents and students.

## ⚙️ Technologies
**Back-End:** ASP.NET Core, C#  
**Database:** **Azure Cosmos DB** (NoSQL)  
**Caching:** Server-side caching using `IMemoryCache`
**ORM /Data Access:** Custom repositories / Cosmos DB SDK
**Front-End:** React / Vue (SPA), responsive UI (Bootstrap / TailwindCSS), interactive map (Leaflet.js / Google Maps)
**DevOps:** Docker, CI/CD (GitHub Actions)

## 💡 Key Features
- Single access point to all city services
- Continuously updated events calendar
- Interactive institutions map
- Online lessons via YouTube API integration
- Admin panel for content management

## 🧠 Architecture
- lient–server model with REST API built on ASP.NET Core
- Data stored in Azure Cosmos DB — flexible schema optimized for read and search operations
- Short-term queries and responses cached locally on the server using IMemoryCache

## 👥 Команда
| Роль | Учасник |
|------|----------|
| Scrum Master | Project Manager | Khrystyna Cherkezian |
| UI/UX Designer | Inna Nochovkina  |
| Front-End Developer | Yevhen Nechypurenko | 
| **Back-End Developer** | **Oleksandr Yelienok** |
| DevOps Engineer |Ivan Slyvnyak|

## 🔮 Future Development
- Mobile application (Android / iOS)
- Student online diary
- Institution ratings and parent reviews
- Integration with the city platform “Odesa City”

---
