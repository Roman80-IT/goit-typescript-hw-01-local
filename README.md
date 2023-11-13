# TypeScript (hw-01)

## Локальна установка

Для встановлення **TypeScript** локально для конкретного проекту (тобто без глобального доступу) потрібно виконати наступні кроки:

- Перейди до каталогу вашого проекту за допомогою командного рядка або терміналу.

- Виконай наступну команду для ініціалізації проекту та створення файлу `package.json`, який використовується для управління залежностями проекту:

```
npm init -y

```

Опція `-y` дозволяє створити package.json без запитань.

Встанови **TypeScript** локально в кореневому каталозі проекту, виконавши команду:

```
npm install typescript

$ typescript -v  // version of tsctypescript
bash: typescript: command not found

tsc --init
bash: tsc: command not found
```

Ця команда встановить **TypeScript** у проекті і додасть його до файлу `package.json` як залежність проекту.

Після встановлення **TypeScript**, можна створити файли `TypeScript` (розширення `.ts`) у проекті і почати розробку.

Для компіляції файлів **TypeScript** у **_JavaScript_**, використовуй команду `tsc` (_TypeScript Compiler_) в кореневому каталозі проекту. Наприклад:

```
npx tsc yourfile.ts
```

Якщо встановлено **TypeScript** локально в проекті, можна використовувати `npx` для запуску **TypeScript Compiler** локально.

За допомогою цих кроків можна встановити **TypeScript** локально для конкретного проекту і користуватися його можливостями без глобального встановлення.

## Глобальна установка

`npm install -g typescript`
