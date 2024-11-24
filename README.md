# Самый ML хакатон Краснодар 
# Кейс для хакатона: «Умная система поддержки бизнеса»
<a name="readme-top"></a>
<p align="center">  
<img width="30%" src="./photo_5314467012107429274_c%20(1).jpg" alt="banner">
</p>
  <p align="center">
    <!--<h1 align="center">LLAIM</h1>-->
  </p>
  <p align="center">
    <p></p>
    <!-- <p><strong>Интеллектуальный пульт составителя.</strong></p> -->

  </p>
</div>

**Содержание:**
- [Проблематика задачи](#title1)
- [Описание решения](#title2)
- [Оценка наших моделей](#title4)
- [Инструкция по установке](#title5)
### Разработан в рамках [хакатона](https://avalab.yonote.ru/share/24970531-c84b-4e50-ae75-08f894355959) командой "Feature_88".
### Live версия доступна [тут](https://web.telegram.org/k/#@MindfulBiz_Feature_88_Bot)

## <h3 align="start"><a id="title1">Проблематика задачи 🧐</a></h3>  
В условиях экономической нестабильности и постоянных изменений в законодательстве бизнес нуждается в поддержке государства и некоммерческих организаций. Однако для предпринимателей поиск актуальной информации о мерах поддержки часто превращается в сложный и длительный процесс. Они сталкиваются со множеством проблем, включая:

1. **Разрозненность источников**: Информация о мерах поддержки публикуется на различных платформах — от федеральных порталов до региональных сайтов и сайтов конкретных ведомств. Каждый из них предоставляет свои данные в собственном формате, а иногда информация может дублироваться, но с разными условиями, создавая путаницу.
2. **Неоднородность структуры данных**: Постановления, законы и программы поддержки не унифицированы, их трудно сравнить. В результате бизнесу сложно определить, какие меры подходят именно для него.
3. **Частые обновления и изменения**: Регулятивные акты могут часто изменяться, добавляя новые меры или изменяя старые. Это приводит к устареванию информации в некоторых источниках, а обновление данных вручную отнимает много времени.
4. **Недостаток персонализации**: Варианты поддержки могут сильно различаться в зависимости от конкретной ситуации бизнеса — его масштаба, сектора, региона и т. д. Предприниматели часто тратят время на фильтрацию информации, которая может им не подходить.
5. **Сложность языка**: Официальные документы и постановления написаны сложным юридическим языком, трудным для быстрого понимания. Бизнес, особенно малый, не всегда имеет юридических специалистов для интерпретации этих документов.


## <h3 align="start"><a id="title2">Описание решения 📝</a></h3>

![](https://github.com/ioann2233/Feature_88_Krasnodar/blob/main/%D1%83%D1%81%D0%BA%D0%BE%D1%801.gif)


*Телеграмм-бот (удобство) 📍
* Ипользованием инновационного подхода через агентов ⚡
* Голосовой ввод
* Аналаз информации с различных источников 
### Структура проекта 🧱

```
├──
```

## <h3 align="start"><a id="title4">Оценка наших моделей 🧑‍🏫🕵️</a></h3> 


  
В своем решении мы использовали агентов - что является более гибким решением чем парсер определенного сайта 🤯
Также мы использовали нейронную сеть для решение задачи голосового ввода - VoiceToText
Были проведены исследования по wer, cer метрикам - мы остановились на speach_recog

## <h3 align="start"><a id="title5">Инструкция по установке 🧐</a></h3> 
Так как был развернут бот с использованием сторонних API РЕКОМЕНДУЕТСЯ ЗАПУСКАТЬ c помощью пакетного менеджера `conda`
