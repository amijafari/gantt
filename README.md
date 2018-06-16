
dhtmlxGantt v.5.1
=================

[![Join the chat at https://gitter.im/dhtmlx/dhtmlx](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/dhtmlx/dhtmlx) 

dhtmlxGantt is an open source JavaScript Gantt chart that helps you illustrate a project schedule in a nice-looking chart. It can show the dependencies between tasks as lines and allows you to set up different relationships between tasks (finish-to-start, start-to-start, end-to-end). dhtmlxGantt provides flexible API and a large number of event handles, which gives you the freedom to customize it for your needs. 

[https://dhtmlx.com/docs/products/dhtmlxGantt](https://dhtmlx.com/docs/products/dhtmlxGantt)


Persian (Jalali) Calendar Support
---------
Using [PersianDate](https://github.com/babakhani/PersianDate) for date conversion.

### Usage
1. Download Project files.
2. Add DHTMLX Gantt resources.
    ```html
    <script type="text/javascript" src="codebase/dhtmlxgantt.js"></script>
    <link rel="stylesheet" type="text/css" href="codebase/dhtmlxgantt.css">
    ```
3. Setup Persian:
    Load dependencies:
    ```html
    <script type="text/javascript" src="persian-date.min.js"></script>
    <script type="text/javascript" src="codebase/locale/locale_fa.js"></script>
    ```
    Config gantt chart to render in Persian:
    ```javascript
    gantt.config.calendar = 'persian';
    ```


License
----------

This software is allowed to use under GPL or you need to obtain Commercial or Enterprise License
to use it in non-GPL project. Please contact sales@dhtmlx.com for details

(c) Dinamenta UAB


Useful links
-------------

- Online  documentation
  https://docs.dhtmlx.com/gantt/
  
- Support forum
  https://forum.dhtmlx.com/viewforum.php?f=15
