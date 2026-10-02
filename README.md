<div align="center">

# Тимофей Бойчук
### Python Backend Developer & Infrastructure Enthusiast

[![Telegram](https://img.shields.io/badge/Telegram-@Menvswild-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white)](https://t.me/Menvswild)
[![Website](https://img.shields.io/badge/Сайт-menvswild.ru-0A66C2?style=for-the-badge&logo=google-chrome&logoColor=white)](https://menvswild.ru)
[![Email](https://img.shields.io/badge/Email-menvswildyt@gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:menvswildyt@gmail.com)

</div>

---

### Обо мне

Специализируюсь на серверной разработке на **Python**, проектировании асинхронных API и сетевой инфраструктуре. Есть практический опыт создания отказоустойчивых сервисов реального времени, работы с геоданными в PostgreSQL/PostGIS, настройки прокси- и VPN-решений, а также администрирования Linux-серверов.

* 📍 **Локация:** Туапсе, Краснодарский край (МСК, UTC+3)
* 🚀 **Фокус:** Бэкенд-разработка, распределенные сервисы, автоматизация процессов
* 🛠️ **Инфраструктура:** Linux VPS, Docker Compose, Caddy / Nginx, мониторинг (Sentry, Prometheus)

---

### Стек технологий

<table>
  <tr>
    <td width="25%" valign="top"><b>Бэкенд и языки</b></td>
    <td width="75%">
      <img src="https://img.shields.io/badge/Python_3.11+-3776AB?style=flat-square&logo=python&logoColor=white" />
      <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" />
      <img src="https://img.shields.io/badge/asyncio-3776AB?style=flat-square&logo=python&logoColor=white" />
      <img src="https://img.shields.io/badge/aiogram_3.x-2CA5E0?style=flat-square&logo=telegram&logoColor=white" />
      <img src="https://img.shields.io/badge/SQLAlchemy_2.0-D71F00?style=flat-square&logo=sqlalchemy&logoColor=white" />
      <img src="https://img.shields.io/badge/WebSockets-010101?style=flat-square&logo=socketdotio&logoColor=white" />
    </td>
  </tr>
  <tr>
    <td valign="top"><b>Данные и кеш</b></td>
    <td>
      <img src="https://img.shields.io/badge/PostgreSQL_16-4169E1?style=flat-square&logo=postgresql&logoColor=white" />
      <img src="https://img.shields.io/badge/PostGIS_3.4-336791?style=flat-square&logo=postgis&logoColor=white" />
      <img src="https://img.shields.io/badge/Redis_7-DC382D?style=flat-square&logo=redis&logoColor=white" />
      <img src="https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white" />
    </td>
  </tr>
  <tr>
    <td valign="top"><b>DevOps и серверы</b></td>
    <td>
      <img src="https://img.shields.io/badge/Linux_Admin-FCC624?style=flat-square&logo=linux&logoColor=black" />
      <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" />
      <img src="https://img.shields.io/badge/Docker_Compose-2496ED?style=flat-square&logo=docker&logoColor=white" />
      <img src="https://img.shields.io/badge/Caddy-1F88C0?style=flat-square&logo=caddy&logoColor=white" />
      <img src="https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white" />
      <img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white" />
    </td>
  </tr>
  <tr>
    <td valign="top"><b>Сети и безопасность</b></td>
    <td>
      <img src="https://img.shields.io/badge/TCP/IP_%26_UDP-00599C?style=flat-square" />
      <img src="https://img.shields.io/badge/TLS/SSL_%26_SNI-43B02A?style=flat-square" />
      <img src="https://img.shields.io/badge/VLESS_Reality-000000?style=flat-square" />
      <img src="https://img.shields.io/badge/Xray_/_Sing--box-1E88E5?style=flat-square" />
      <img src="https://img.shields.io/badge/Wireshark-1679A7?style=flat-square&logo=wireshark&logoColor=white" />
    </td>
  </tr>
</table>

---

### Проекты и опыт

#### 🛰️ [Платформа «ВПОИСКЕ»](https://menvswild.ru)
*Цифровая realtime-платформа для координации поисково-спасательных операций в природной и городской среде.*
* **Архитектура бэкенда:** FastAPI, SQLAlchemy 2.0 (async), PostgreSQL 16 + PostGIS 3.4.
* **Геосервисы:** обработка полигонов поисковых зон, построение координатной сетки, сглаживание GPS-треков полевых поисковиков (алгоритм Дугласа-Пекера).
* **Сетевой слой и realtime:** WebSocket-каналы с отслеживанием присутствия участников, кеширование геопозиций в Redis 7, оффлайн-буферизация пакетов.
* **Инфраструктура:** Docker Compose, обратное проксирование Caddy с автоматическим TLS, мониторинг метрик и сбоев (Prometheus, Sentry).

#### 🛡️ Коммерческий сервис AXIS VPN & Telegram-бот
*Инфраструктура распределенной прокси-сети и система автоматического биллинга.*
* Спроектировал распределенную сеть серверов на протоколах VLESS Reality и Xray со стабильной маскировкой трафика.
* Разработал Telegram-бота на aiogram 3.x с управлением жизненным циклом конфигураций, мониторингом доступности узлов и мультивалютным биллингом (850+ успешных платежей).

---

### Статистика активности

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=MenVsWild1&show_icons=true&theme=radical&hide_border=true&locale=ru" alt="GitHub Stats" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=MenVsWild1&layout=compact&theme=radical&hide_border=true&locale=ru" alt="Top Languages" />
</div>

---

<div align="center">

*Открыт к предложениям о сотрудничестве, интересным проектам и удаленной работе.*  
[Написать в Telegram](https://t.me/Menvswild) • [Отправить письмо](mailto:menvswildyt@gmail.com)

</div>
