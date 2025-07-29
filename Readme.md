# VS Code Settings Configuration

Этот файл содержит настройки для VS Code, оптимизированные для веб-разработки (Laravel, JavaScript, TypeScript, HTML/CSS и др.).

## Основные настройки интерфейса

- **`window.commandCenter`**: `true` — включает центр команд в заголовке окна
- **`window.customTitleBarVisibility`**: `"auto"` — автоматическое отображение кастомной панели заголовка
- **`window.density.editorTabHeight`**: `"compact"` — делает вкладки редактора более узкими
- **`workbench.colorTheme`**: `"GitHub Dark Default"` — тёмная тема интерфейса
- **`workbench.activityBar.location`**: `"hidden"` — скрывает боковую панель активности
- **`workbench.statusBar.visible`**: `true` — показывает статусбар внизу
- **`workbench.editor.tabSizing`**: `"shrink"` — сжимает вкладки при нехватке места
- **`workbench.panel.defaultLocation`**: `"right"` — размещает панель (терминал, проблемы и т.д.) справа
- **`workbench.fontAliasing`**: `"antialiased"` — включает сглаживание шрифтов

## Настройки редактора

### Шрифты и отображение
- **`editor.fontFamily`**: `"'Fira Code', 'JetBrains Mono', 'monospace', monospace"` — основной шрифт с поддержкой лигатур
- **`editor.fontSize`**: `16` — размер шрифта
- **`editor.lineHeight`**: `28.5` — высота строки
- **`editor.fontLigatures`**: `true` — включает лигатуры для Fira Code
- **`editor.renderWhitespace`**: `"all"` — показывает все пробельные символы

### Форматирование и табуляция
- **`editor.tabSize`**: `4` — размер табуляции
- **`editor.insertSpaces`**: `false` — использует табы вместо пробелов
- **`editor.formatOnSave`**: `true` — автоматическое форматирование при сохранении
- **`editor.defaultFormatter`**: `"esbenp.prettier-vscode"` — Prettier как форматтер по умолчанию

### Поведение
- **`editor.smoothScrolling`**: `true` — плавная прокрутка
- **`editor.stickyScroll.enabled`**: `true` — "липкая" прокрутка для навигации
- **`editor.copyWithSyntaxHighlighting`**: `false` — копирует текст без подсветки синтаксиса

## Языковые настройки

### HTML/Blade
- **`blade.format.enable`**: `true` — включает форматирование для Blade
- **`bladeFormatter.format.useTabs`**: `true` — использует табы в Blade
- **`bladeFormatter.format.wrapAttributes`**: `"force-expand-multiline"` — перенос атрибутов на новые строки

### CSS/SCSS
- **`css.format.enable`**: `true` — форматирование CSS
- **`scss.format.enable`**: `true` — форматирование SCSS

### JavaScript/TypeScript
- **`javascript.preferences.quoteStyle`**: `"single"` — одинарные кавычки
- **`typescript.preferences.quoteStyle`**: `"single"` — одинарные кавычки

### PHP/Laravel
- **`[php]`**: Laravel Pint как форматтер по умолчанию
- **`laravel-pint.enable`**: `true` — включает Laravel Pint
- **`namespaceResolver.sortOnSave`**: `true` — сортирует use-декларации при сохранении

## Терминал
- **`terminal.integrated.fontFamily`**: `"'Fira Code'"` — шрифт терминала
- **`terminal.integrated.fontSize`**: `13` — размер шрифта терминала
- **`terminal.integrated.cursorStyle`**: `"block"` — стиль курсора "блок"

## Prettier
- **`prettier.useTabs`**: `true` — использовать табы
- **`prettier.semi`**: `false` — без точек с запятой
- **`prettier.singleQuote`**: `true` — одинарные кавычки

## Отключенные функции
- Хлебные крошки (`breadcrumbs.enabled`: `false`)
- Подсказки при старте (`workbench.tips.enabled`: `false`)
- Подсветка парных скобок (`editor.matchBrackets`: `"always"`)
- Мини-карта (`editor.minimap.enabled`: `false`)

## Ассоциации файлов
- `.blade.php` → Blade
- `.tpl` → HTML