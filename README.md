## 🎭 Автоматизация тестирования на Playwright (JS/TS)

> **Портфолио выполненных практических заданий в рамках курса по Playwright**  
> Курс: [«Автоматизация тестирования c Playwright на JS/TS: полный курс»](https://stepik.org/course/228133/info)  
> Цель — демонстрация навыков автоматизации веб-тестирования для позиции **Automation QA Engineer**

---

### 🧩 Структура репозитория

```
📦 root/
├── 📂 .github/ # CI/CD настройки
│ └── 📂 workflows/
│ └── 📄 playwright.yml
│
├── 📂 tests/ # Все тесты
│ │
│ ├── 📂 locators/ # Поиск элементов (8 файлов)
│ │ ├── 🎯 getByRole.spec.ts
│ │ ├── 🔍 getByText.spec.ts
│ │ ├── 🏷️ getByLabel.spec.ts
│ │ ├── ✏️ getByPlaceholder.spec.ts
│ │ ├── 🖼️ getByAltText.spec.ts
│ │ ├── 📌 getByTitle.spec.ts
│ │ ├── 🆔 getByTestId.spec.ts
│ │ └── 🎨 css.spec.ts
│ │
│ ├── 📂 actions/ # Действия с элементами (5 файлов)
│ │ ├── 🖱️ click.spec.ts
│ │ ├── ✨ hover.spec.ts
│ │ ├── ⌨️ fill.spec.ts
│ │ ├── ✅ check.spec.ts
│ │ └── 📋 selectOptions.spec.ts
│ │
│ └── 📂 assertions/ # Проверки (7 файлов)
│ ├── 👁️ toBeVisible.spec.ts
│ ├── 📝 toContainText.spec.ts
│ ├── 🔤 toHaveText.spec.ts
│ ├── 💾 toHaveValue.spec.ts
│ ├── 🏷️ toHaveAttribute.spec.ts
│ ├── 🎨 toHaveClass.spec.ts
│ └── 🔗 toHaveUrl.spec.ts
│
├── ⚙️ playwright.config.ts # Конфигурация Playwright
├── 📦 package.json # Зависимости
├── 🔒 package-lock.json # Lock-файл
├── 🙈 .gitignore # Git ignore
└── 📖 README.md # Документация
```

---

### 🚀 Как запустить тесты локально

```
Убедитесь, что у вас установлено:

- Node.js версии 18 или выше ([скачать](https://nodejs.org/))
- Git ([скачать](https://git-scm.com/))

Откройте терминал (командную строку) и выполните команды:

1. Склонируйте репозиторий
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
