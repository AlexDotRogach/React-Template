# Getting Started with this template

/components - basic components with a ban on importing other parts of the application;
/services - functions for communicating with the backend;
/forms - Forms components;
/layouts - components without logic that determine the positioning of the components inside themselves and adapt to different screen sizes;
/pages — components referred to by routes do not contain any logic other than passing route parameters and defining layouts;
/tools - logical solutions (validations, reductions, calculations)

Each component is formatted as
ComponentName/ - folder for grouping everything related to the component
- index.js - export;
- ComponentName.js - code of the child component during decomposition;
- ComponentName.test.js - unit tests of the component;
- ComponentName.module.css - component styles;
---------------------------------------------------------------------------
// translate:
/components — базовые компоненты с запретом импорта других частей приложения;
/services — функции общения с бекендом;
/forms — Форм компоненты;
/layouts — компоненты без логики определяющие позиционирование компонент внутри себя и адаптацию под разные размеры экрана;
/pages — компоненты на которые ссылаются роуты, не содержат в себе логики кроме передачи параметров роута и определения лэйаутов;
/tools — логические решения (валидации, сокращения, вычисления)

Каждая компонента оформляется как
ComponentName/ — папка для группировки всего что относится к компоненте
— index.js — экспорт ;
— ComponentName.jsx — код дочерней компоненты при декомпозиции;
— ComponentName.test.js — юнит тесты компоненты;
— ComponentName.module.css - стили компонента;