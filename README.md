## 🎭 Автоматизация тестирования на Playwright (JS/TS)

> **Портфолио выполненных практических заданий в рамках курса по Playwright**  
> Курс: [«Автоматизация тестирования c Playwright на JS/TS: полный курс»](https://stepik.org/course/228133/info)  
> Цель — демонстрация навыков автоматизации веб-тестирования для позиции **Automation QA Engineer**

---

### 🧩 Структура репозитория

```
├── .github/
├── .gitignore
├── tests/
│ ├── Locators/
│ ├── Actions/
│ ├── Assertions/
├── package-lock.json/
├── playwright.config.ts
├── package.json
└── README.md
```

---

### 🚀 Как запустить тесты локально

📋 Требования

Убедитесь, что у вас установлено:

- **Node.js** версии 18 или выше ([скачать](https://nodejs.org/))
- **Git** ([скачать](https://git-scm.com/))

⚙️ Установка и запуск
```
Откройте терминал (командную строку) и выполните команды:

1. Клонируйте репозиторий
git clone https://github.com/OksanaKZ/Playwright-tests-portfolio.git
cd Playwright-tests-portfolio

2. Установите зависимости
npm install

3. Установите браузеры для Playwright
npx playwright install

4. Запустите все тесты
npx playwright test

5. После выполнения тестов откройте HTML-отчёт  
npx playwright show-report  
```
