---
title: Las Pegasus
layout: default
css: "/assets/css/index.css"

cover-img:
  - "/img/big-imgs/las_pegasus (1).jpg" : "Las Pegasus"
  - "/img/big-imgs/las_pegasus (2).jpg" : "Las Pegasus"
  - "/img/big-imgs/las_pegasus (3).jpg" : "Las Pegasus"
  - "/img/big-imgs/las_pegasus (4).jpg" : "Las Pegasus"
  - "/img/big-imgs/las_pegasus (5).jpg" : "Las Pegasus"
  - "/img/big-imgs/las_pegasus (6).jpg" : "Las Pegasus"
  - "/img/big-imgs/las_pegasus (7).jpg" : "Las Pegasus"
---

{%- capture thumbnail -%}
      {% if post.thumbnail-img %}
        {{ post.thumbnail-img }}
      {% elsif post.cover-img %}
        {% if post.cover-img.first %}
          {{ post.cover-img[0].first.first }}
        {% else %}
          {{ post.cover-img }}
        {% endif %}
      {% else %}
      {% endif %}
    {% endcapture %}
    {% assign thumbnail=thumbnail | strip %}

# <center>Добро пожаловать на сайт проекта Las Pegasus!</center>
## <center>IP Адресс сервера: 95.84.136.207:27015</center>

### О проекте Las Pegasus
><span style="color:white">Ну, тут типа о проекте, но пока не написано.</span>

### Про сам сервер и игровой режим
><span style="color:white">В текущий момент работа сервера стабилизируется, постепенно вводятся новые функции (для дальнейшего развития режима C&Box)
и разрабатывается сам режим C&Box, так что-же это такое?<br>Вкратце: это модульный игровой режим, в основе которого лежит функционал
для работы других игровых режимов (примером тому выступает сервер **[Las Pegasus] | Brony Server | [Beta]**, находящийся по адресу `95.84.136.207:27015`),
в данном режиме используется режим SandBox и Cinema ([by FarukGamer](https://github.com/FarukGamer/cinema)) и оба этих режима работают отдельно друг от друга! В дальнейшем будет
реализован более простой модуль, который позволит налету подгружать со стороны сервера все изменения на сторону клиента... Дайте просто немного времени :)</span>