﻿# itra-course-project
  
Итоговый проект бесплатного курса от компании iTransition.  
  
Превью: https://mern-collections.vercel.app/
 
Stack: MongoDB, Express.js, React.js, Node.js (MERN)  
Подробнее про фронтенд: https://github.com/DefK1lla/itra-course-proj-client    
Подробнее про бэкенд: https://github.com/DefK1lla/itra-course-proj-server    
  
Web-приложение для управления личными коллекциями (книги, марки, виски, и т.д. — в тексте ниже это называется айтемы).  
Есть три вида пользователей. Гость, зарегистрированный пользователь и администратор. Гостью доступен только режим чтения. Пользователь может создать коллекци, айтемы и писать комментарии. Администратору же доступна админ-панель, в которой он может удалять, блокировать и разблокировать пользователя. А также, админ может дать или забрать у пользователя роль администратора. Авторизация пользователя происходит с помощью JWT токена.  
Каждый пользователь может управлять только своими айтемами и коллекциями. Администратор имеет доступ к управлению всем на сайте, в том числе и коллекциями/айтемами других пользователей.  
Каждая коллекция имеет название, описание (с поддержкой markdown), тему (одно значение из фиксированного справочника), опционального изображения (загружается на облако AWS).  
Дополнительно коллеция позволяет указать поля, которые будут у каждого айтема. Плюс у айтемов есть фиксированные поля (id, название, тэги). На уровне коллекции для айтемов можно выбрать любой набор из следующих доступных: целочисленные поля, строковые поля, многострочные тексты, логические да/нет чекбоксы, поля даты. Для каждого из выбранных полей пользователь задает название.  
Каждый айтем также содежрит лайки (не более одного от одного пользователя на каждый айтем).  
Сайт подддерживает два языка: английский и русский. А также две визуальные темы: светлую и темную. Сайт полностью адаптивен.
