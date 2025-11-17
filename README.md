# "Odesa for Children" – Information Portal

**Project Goal:** to create a unified online resource that brings together information about education, healthcare, leisure, and child development in Odesa.

🔗 **Live:** [View Live Project](https://zealous-stone-02d05a803.6.azurestaticapps.net/)
📄 **Presentation:** [Download PDF](https://github.com/OleksandrY-Portfolio/ProjectOdesa-Demo/blob/main/%D0%94%D0%B8%D0%BF%D0%BB%D0%BE%D0%BC_%D0%86%D0%BD%D1%84%D0%BE%D1%80%D0%BC%D0%B0%D1%86%D1%96%D0%B9%D0%BD%D0%B8%D0%B9%20%D0%BF%D0%BE%D1%80%D1%82%D0%B0%D0%BB.pdf)

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

## 👥 Team
| Role | Member |
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
