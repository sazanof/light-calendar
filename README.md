# Light Calendar

### Introduction

A simple but yet powerful calendar and datepicker component written in javascript with full featured API.


Option                | Type       | Default
-------               | ------     |-----------------------------
**year**              | *Number*   | new Date().getFullYear()
**month**             | *Number*   | new Date().getMonth()
**dayNames**          | *Array*    | ["Su", "Mo", "Tu", "We", "Th", "Fr", "Sa"]
**dayNamesFull**      | *Array*    | ["Sunday", "Monday", "Tuesday", "Wednesday", "Thursday", "Friday", "Saturday"]
**monthNames**        | *Array*    | ["Jan", "Feb", "Mar", "Apr", "May", "Jun", "Jul", "Aug", "Sep", "Oct", "Nov", "Dec"]
**monthNamesFull**    | *Array*    | ["January", "February", "March", "April", "May", "June", "July", "August", "September", "October", "November", "December"]
**offset**            | *Number*   | null
**outsideClose**            | *Boolean*   | false
**startDay**          | *Number*   | 0
**weekNumbers**       | *Boolean*  | false
**selectOtherMonths** | *Boolean*  | false
**showOtherMonths**   | *Boolean*  | true
**showNavigation**    | *Boolean*  | true
**months**            | *Numeric*  | 1
**inline**            | *Boolean*  | false
**disablePast**       | *Boolean*  | false
**dateFormat**        | *String*   | 'Y-m-d'
**position**          | *String*   | 'bottom'
**minDate**           | *Date*     | null
**onBeforeOpen**      | *Function* | function () {}
**onBeforeClose**     | *Function* | function () {}
**onOpen**            | *Function* | function () {}
**onClose**           | *Function* | function () {}
**onSelect**          | *Function* | function () {}
**onBeforeShowDay**   | *Function* | function () { return [true, '']; }
