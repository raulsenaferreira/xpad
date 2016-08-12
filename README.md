# xpad
A system that extends (and empower) the functionalities of [dontpad.com](http://dontpad.com/)

## Motivation
I already had a basic programming background in PHP and recently i was hired to manage a team in a IT project inside of IPEA. The team decided to build this project using Lumen, so i decided to learn Laravel/Lumen (starting from the time that i'm writing this README file :P) and thus, i can contribute better with my team.

Dontpad.com is a great idea developed by André Faria made on top of "Distraction Free Writing" idea. The explanation about the creation of this system may be find [here] (http://blog.andrefaria.com/projetos)

Today, donpad allow you write in an blank page (using any URL) and allows you download all data as .zip file. However, anyone that wants to access these URLs can view and edit these messages, and sometimes it brings a lot of troubles.

My first idea is develop a simple mechanism to difficult that someone access this data whitout the permition of authors or collaborators and extend some functionalities to ths tool like, easy secure sharing, the possibility to hide content and "easy personal authentication" without use a database or a file and etc. The main goal is to do it without sacrifice the simplicity and flexibility of the original tool.

## Requirements
This project is under development and uses [Laravel](https://laravel.com/) to build the extend functionalities and authentications and uses the flexibility of [Lumen](https://lumen.laravel.com/) to build REST APIs.
