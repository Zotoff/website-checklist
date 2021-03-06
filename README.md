# website-checklist
Чеклист для оценки вёрстки сайта

## Общие требования

**Соответствие макету**
Расположение блоков должно быть 1:1 по сравнению с макетом. 
Допускается расхождение до 5px для текста. 
Разрешены и даже приветствуются правки размеров и расположения криво нарисованных блоков (разница размерах в 1-2px на разных страницах).

## Технические стандарты
- [ ] - Кодировка: UTF-8
- [ ] - DOCTYPE: HTML5

**Валидность:**

- [ ] - Стили сайта соответствуют стандарту CSS3, за исключением хаков и вендорных свойств. 
<http://jigsaw.w3.org/css-validator> * ![Low](http://bit.ly/2oyJPNe)

- [ ] - Верстка сайта соответствует стандарту HTML5 за исключением уникальных свойств браузеров и результатов выдачи WYSIWYG-редакторов. <http://validator.w3.org>

- [ ] - Не должно быть JavaScript-ошибок. (Обратите внимание что console.log под IE7-8 ломает код и вызывает ошибки)

- [ ] - Микроформаты должны быть. Как минимум – hCard. Желательно также hCalendar, XFN, hAtom

- [ ] - Проверка статическими анализаторами качества кода: CSSLint и JSHint

- [ ] - Определить наличие соответствия верстки стандарту доступности: WCAG Он имеет три уровня сложности, если проходит хотя бы WCAG1 A (Priority 1) – уже хорошо. Идеальный вариант – WCAG2 Priority 3 (AAA). Самый просто способ проверить что скорей всего WCAG1 Priority A соблюдён — www.cynthiasays.com (или addon Web Developer →Инструменты →Проверить WAI).

- [ ] - Automated testing Testomato

