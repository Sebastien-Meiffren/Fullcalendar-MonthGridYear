# Fullcalendar-MonthGridYear
MonthGridYear implementation for [Fullcalendar](https://fullcalendar.io/)

## Requirements
* Jquery 3.5.1
* Fullcalendar version 5.4.0

_Those versions are the one used in my own project. Never tested with anything else_

## Current Version Beta 1.0
⚠ This is a simple implementation of the monthGridYear view ⚠  
Currently, you need to refresh the render to make sure that the height / width of the elements are correct

## HOWTO
1. Get the monthGridYear.js file 
2. import the file in your project
3. make sure you have bootstrap installed
4. include the new view in your setup of FullCalendar



            initialView: 'MonthGridYear',
            headerToolbar: {
                left: 'monthGridYear dayGridMonth',
                center: 'title'
            },
            views: {
                monthGridYear: MonthGridYear
            }


## Demo
_see [demo.html](demo.html)_