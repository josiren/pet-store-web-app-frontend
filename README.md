# Шаблон для разработки веб-приложений на React, Vite и Redux с использованием методологии Feature-Sliced Design (FSD).

## 🔄 Развертывание

### Клонирование репозитория

```
git clone https://github.com/josiren/react-vite-fsd-theming-template.git
cd react-vite-fsd-theming-template
```

### Установка Bun (если еще не установлен)

```
curl -fsSL https://bun.sh/install | bash
```

### Установка зависимостей

```
bun install
```

### Запуск в режиме разработки

```
bunx run dev
```

### Сборка проекта

```
bun run build
```

### Линтинг кода

```
bun run lint
```

### Форматирование кода (prettier)

```
bun run format
```

### Предварительный просмотр сборки

```
bun run preview
```

## 🚀 Ключевые особенности

- **Технологический стек**:

  - **React**: Используется для создания пользовательского интерфейса.
  - **Vite**: Современный инструмент сборки для быстрой разработки и высокой производительности.
  - **Redux**: Управление состоянием приложения.

- **Feature-Sliced Design (FSD)**:

  - Структура проекта организована по методологии FSD, что обеспечивает четкое разделение
    функциональности на независимые модули или "фичи".
  - Упрощает масштабирование и поддержку кода.

- **Темизация**:

  - Поддержка светлой и темной тем.
  - Реализована через **ThemeProvider** из **@emotion/styled**, что упрощает управление глобальными
    стилями.
  - Позволяет адаптировать внешний вид приложения к предпочтениям пользователя.

- **Типографика**:

  - В проекте реализована система типографики, которая позволяет использовать различные варианты
    текстов для улучшения визуального восприятия контента.
  - Типографика организована в виде объекта `typographyList`, который содержит ключи для различных
    заголовков и текстовых элементов, таких как `h1`, `h2`, `body1` и т.д.

- **Стилизация компонентов**:

  - Использование **@emotion/styled** для создания стилизованных компонентов с поддержкой CSS-in-JS.
  - Возможность динамического изменения стилей в зависимости от состояния приложения.

- **Гибкость и расширяемость**:

  - Легкое управление темизацией.
  - Идеально подходит как для обучения, так и для создания коммерческих приложений.
