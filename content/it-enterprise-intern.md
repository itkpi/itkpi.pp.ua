---
title: "Здравствуйте, меня зовут Федя и я бывший интерн корпорации IT-Enterprise"
date: 2016-02-12T13:27:46.637676+00:00
draft: false
author: f.klimenko
email: klimenko.fyodor@gmail.com
---

<div class="image-wrapper">
    <img src="/images/2016/02/1455283571_3d5e41125b254776b4dc7f21902cdbc0.jpg" class="post-image full-img">
</div>

**ДИСКЛЕЙМЕР**: эта статья является субъективной точкой зрения автора этого текста и не отображает точку зрения администрации “ІТ КПІ”.

Также адмистрация “ІТ КПІ” снимает с себя всю отвественность за этот материал и все материалы, автором которых является не администратор блога (а именно — **itkpi**).

*В IT-Enterprise открыт новый набор в интернатуру. Там из тебя сделают настоящего разработчика программного обеспечения. Там ты поднимешь скиллы C# и научишься писать запросы, чтобы они не вылетали ни в Microsoft SQL Server, ни в Oracle.*

*Да, возможно это неплохой вариант для студентов первых курсов, но со мной группе был парень, который отказался от работы в GlobalLogic ради интернатуры в IT-Enterprise. И мне почему-то жалко этого парня…*

*А ниже - моя история.*

## Начало
Все началось еще в школе – на уроках информатики я узнал о языках программирования, типах данных и простых управляющих конструкциях. Тогда с друзьями начал немного писать на Pascal’е. Потом университет, там все говорили о дженериках, асинхронности, быстром C++, элегантном Prolog’e и… Меня затянуло.

Так прошло пару лет, я перепробывал еще пару ЯП, но в конечном итоге понял, что больше всего меня вставляет C# с его мощным и красивым кодом. С помощью C#, используя антипаттерн Smart UI, я быстро писал программы с настоящими кнопками, которые на ура впаривал преподавателям как лабы и смело бежал на поляну, чтобы обсудить с корешами последние тенденции в программировании.

Дальше – хуже.

Я читал книги по базам данных, начал вникать в шаблоны и, в конечном итоге, понял, что все, что было раньше – это детский лепет. И если программировать, то только по-взрослому.

Я решил найти большую компанию, в которой смогу пуститься во все тяжкие.

Весь сентябрь 2015 я искал работу на должности младшего разработчика. Везде отсылал свое резюме, на многих собеседованиях побывал и, к сожалению, безуспешно. Мне все время чего-то не хватало: то JS слабо знаю, то про многопоточность не дочитал. 

И тут, где-то в конце октября, на сайте DOU натыкаюсь на объявление о наборе в интернатуру корпорации «IT-Enterprise». Требования к соискателям небольшие – вменяемость, огонь в глазах, основы C# и SQL.

Дочитав объявление до конца, я представил будущее: я прохожу небольшой конкурс и попадаю в «кузню разработчиков», где 100 часов кряду буду прокачивать hard skills, пить казенный кофе, кушать плюшки, слушать лекции о внутреннем продукте и выполнять всякие практические задания. Далее я сдаю аттестацию и попадаю на стажировку – там вообще все будет отлично: 240 часов реальных проектов, сложных ERP-систем и полного agile. А дальше – такая долгожданная реальная работа! К тому же офис на территории КПИ и возможность работать по гибкому графику – это бесценно, особенно для студента.

Недолго думая, я отправил резюме с сопроводительным письмом на edu.kpi@it.ua и принялся гуглить контору. На сайте IT-Enterprise написано, что они – очень крупная корпорация, уже очень давно на рынке (дольше, чем я на свете), делают крутые ERP-системы для больших предприятий по всему СНГ, собирают и снимают на видеокамеру всякие форумы, где презентуют свой софт, потом выкладывают эти видосы на youtube и вообще они очень крутые ребята. Но профиль на DOU практически пустой, в LinkedIn’e вообще никакой информации нету и, в целом, “IT-Enterprise” хреново гуглился.

## Конкурс. 1 этап – анкетирование.
В ответ на мое письмо получаю просьбу заполнить  анкету в течение двух дней. Вопросы в анкете были или предельно заезженные, или предельно философские. Я приведу некоторые из них, чтобы вы понимали, о чем я:
1. Назовите Ваши положительные качества.
2. Есть ли у Вас жизненные цели?
3. В какой «зоне жизни» (личная жизнь, работа, здоровье или самообразование) вы считаете себя наиболее реализованным?
4. Будет ли Вас поддерживать семья, если вы будете задерживаться на работе?
5. Почему одни сотрудники эффективно работают в отсутствии руководителя, а другие нет?

Вопрос о «зоне жизни» и моей самореализации в ней вообще меня сильно расстроил – пришлось выпить. Поэтому потратил я на заполнение анкеты, в общей сложности, как раз два дня.

Также в анкете поинтересовались моей ожидаемой зароботной платой в гривнах - пришлось 25 умножать на 500.

В любом случае, с дедлайном в 2 дня я справился – отправляю.

## Конкурс. 2 этап – тест по БД
Через неделю получаю письмо с тестом по базам данных T-SQL. Задач несколько: ответить на теоретический вопрос про нормировку базы и написать 5 запросов на T-SQL к небольшой схеме с очень странными названиями таблиц и атрибутов. Сами таблицы и их структуру – смотрите ниже на картинке.

![erd](http://itkpi.pp.ua/images/2016/02/1455281617_536a81e589194cc1ac331a9dc4dbf42f.jpg)

Как видите, названия реально хардкорные, русский мир прям. Когда их читаешь, аж жалко становится ребят, которые пишут запросы к таким таблицам… Себя жалко, то есть.

Над заданием посидел около половины дня – узнал пару новых для себя приколов в T-SQL, выполнил и отправил.

## Конкурс. 3 этап – C sharp
Получаю следующую задачу: написать небольшую Winforms программулину, что будет читать данные из БД, реагировать на нажатие клавиш и группировать данные в таблице по выбранному критерию.

Тут-то я постарался на славу – делал по шаблону MVP, с кучей интерфейсов, инкапсулировал SQL код в отдельном слое… Короче, банда четырех мною бы гордилась!

## Конкурс. Итог.
Длилась проверка моих знаний ровно 17 дней. Единственное, что меня удивляло, что отвечали мне с корпоративной почты иногда по ночам или рано утром.

Ну, ничего себе, трудоголики работают в корпорации IT-Enterprise, скажите?

## Собеседование и соглашение.
Отбор я прошел. Меня пригласили на собеседование в центральный киевский офис на самих Осокорках.

Я приехал на проспект Бажана 14а и общался там с тетей по имени Елена Сивак. Как выяснилось, именно Елена вела с нами переписку, проверяла тестовые задания и писала замечания. Она классически попросила меня рассказать о себе, потом немного рассказала о IT-Enterprise и, наконец-то, предложила мне участие в интернатуре. Но дальше что-то пошло не так…

Может кто-то из вас проходил отбор на курсы в компании EPAM? Я – в свое время, да. Там, кстати, тоже нужно пройти тестирование и собеседование. В случае успешного интервью тебя поздравляют, торжественно приглашают на курсы, и через пару недель ты идешь на курсы, – ничего лишнего.

Но здесь произошло иначе: меня торжественно поздравили, достали распечатанное соглашение в двух экземплярах, попросили ознакомиться и подписать.

Смысл соглашения такой:
1. Корпорация IT-Enterprise выделяет 15 тысяч гривен на мое обучение в интернатуре (этот грант она выдает сама себе, прям кредит китайского правительства)
2. А я обязуюсь посещать все занятия в интернатуре, что длится 100 часов; выполнять все задания; быть прилежным интерном; в конце обучения в интернатуре сдать аттестацию, т.е. провести полный рабочий день в офисе, выполняя реальную задачу над каким-то проектом под руководством тим-лида. И за этот день, если я успешно выполнил поставленную задачу, мне даже выплатят бонус в размере 2-3 тысяч гривен.
3. В случае успешной аттестации, я становлюсь стажером в компании на 240 часов.
4. В случае успешной стажировки, я становлюсь сотрудником компании и обязуюсь отработать в ней 1 год.
5. В случае моего увольнение по собственному желанию или из-за некомпетентности, я обязуюсь возместить компании сумму, что была потрачена на мое обучение.

Читал я внимательно, но, к сожалению, недостаточно. Задумался я тогда, в первую очередь, о том, что это же контракт на целый год! Но с другой стороны, год в крутой и крупной компании (которая к тому же готова меня учить!) с интересными проектами – это совсем мало, тем более,- это реальный опыт разработки.

Мне тогда однозначно следовало вчитываться в детали соглашения, потом попросить у Елены методичку , по которой нас будут учить, выяснить четко, чем мы будем заниматься, кого из нас будут готовить, какие задачи мы будем выполнять и многое-многое другое. Может тогда бы я одумался…

Но я дурак на радостях подписал и побежал домой кушать борщи.

## Занятия в интернатуре. Первые впечатления.
Таких как я, интернов, было где-то 15 человек. Каждого интерна посадили на определенное место, которое закреплено за ним, выдали специальные магнитные карточки, которая открывает дверь офиса, и мы начали занятие.

Рассказывали про архитектуру главного приложения корпорации «IT-Enterprise» под названием «IT-предприятие», про стек технологий, который используется в нем. А в конце мы читали небольшие pdf-файлы с инструкциями по эксплуатации компьютера, о правилах поведении в офисе, на кухне и в туалете, описанием штрафов в случае, если сотрудник забыл магнитную карточку дома и прочее.

В целом, мое личное впечатление от занятий Елены (да, она еще и лекции вела) не самое лучшее: лекции растянутые и нудные. Каждый раз, приходя домой после занятия, я задавал себе вопрос: «Что нового я узнал? Какие hard skills я прокачал?».

Ответы были – ничего и никакие.

Утешал себя я мыслью, что это только первые вступительные занятия и ради работы своей мечты, я могу потерпеть.

## Занятия в интернатуре. Озарение.
На занятии эдак пятом-шестом мне стало ясно- кого из нас готовят.

Как оказалось, разработчики IT-Enterprise создали ERP-систему, в которой тоже можно разрабатывать – т.е. добавлять всякие окошки, делать таблицы, писать запросы и многое другое. Нас начали учить разрабатывать в самой программе «IT-предприятие» (которая, кстати, достаточно кривовата), но, благо, с возможностью вызова Visual Studio для того, чтобы она красиво подсвечивала код и заканчивала слова. Ну, а процесс отладки написанного кода внутри программы превращается в целую эпопею.

Также мне удалось порыться в коде самой программы «IT-предприятие». Да, там шикарная бизнес-логика, от которой бухгалтера и финансовые директора компаний-заказчиков, уверен, в восторге, но также огромное количество легаси кода, костылей и оберток, введенных для того, чтобы древние модули работали корректным образом.

Сам процесс разработки внутри программы, как я упоминал, достаточно примитивен. Они, наверняка, хотели сделать так, чтобы любой человек без навыков программирования мог создать все необходимые себе окошки со статистикой и прочим. Но, как оказалось, без навыков программирования тут не справиться!

Итого, заказчик, у которого внедряется программа «IT-Предприятие», вынужден просить компанию «IT-Enterprise» кастомизировать и допилить программу, согласно его нуждам. И именно это допиливание с помощью всевозможных корпоративных API внутри самой программы и есть первоочередной задачей выпускников интернатуры.

## Занятия в интернатуре. Мои страхи.
Да, возможно через некоторое время работы в компании тебя допустят к ядру приложения и ты станешь крутым синьором, будешь писать разные причудливые костыли, разрабатывать архитектуру и кушать сыры, но когда это будет?

Я начал бояться, что в конце интернатуры я стану специалистом в «IT-Предприятие», а не в .NET и базах данных. А это повод задуматься.

Единственное, что могло развеять все мои сомнения – это мое вознаграждение. Именно поэтому я написал вот такое письмо Елене Сивак:

![Image alt text](http://itkpi.pp.ua/images/2016/02/1455282206_4dee8c0ee1554cc18fcdb65087c9cf7b.jpg)

Ее ответ меня несколько удивил:

![Image alt text](http://itkpi.pp.ua/images/2016/02/1455282206_72aa15daa2154986a9040fe526ef5bfb.jpg)

Такой feedback в формате «каждому по заслугам» меня не устроил, ведь я же писал в анкете, что хочу точную и определенную цифру в точном и определенном диапазоне.
Мною было решено не сдаваться и написано новое письмо, с просьбой уточнить – сколько получает в среднем интерн, который прошел аттестацию, во время стажировки, и сколько получает в среднем интерн,  прошедший стажировку, во время самой работы.

Прошел день и два, но ответа я не дождался. А молчание – тоже ответ.

Итого, получается так: я  тупо подписал бумажку, согласно которой должен посещать занятия и сдать аттестацию, а потом должен отработать год в компании при любом раскладе. А если не отработаю, то буду должен компании 15 тысяч. К тому же, в договоре ничего не говорится о моем вознаграждении, а мой вопрос о заработной плате игнорируют.

## Занятия в интернатуре. Решение.
Перспектива стать разработчиком окошек в программе «IT-Enterprise» с призрачной заработной платой меня не совсем устраивала. Я решил проститься с интернатурой и Еленой Сивак лично.

Наверняка, я бы вообще забил на курсы, но мне совесть не позволила, ведь мне выдали специальную магнитную карточку и ее следует вернуть.

## Финал. Директора уходят по-английски. Ну, почти по-английски.
Предварительно отправляю Елене Сивак письмо, в котором говорю, что по личным обстоятельствам вынужден отказаться от участия в интернатуре, и прошу уточнить время, когда могу прийти и передать карточку. Ответ, как обычно, не получаю.

В любом случае, я прихожу перед началом занятия в офис корпорации и встречаюсь с Еленой. Она просит меня зайти в переговорку и подождать ее там. Спустя пару минут заходит Елена и какой-то чувак (как оказалось – это директор учебного центра корпорации).

Двое сели напротив меня и с этого момента Елена не промолвила ни слова. А диалог с директором у нас был где-то такой:

```
— Ну, Федор, как вы докатились до такой жизни?
— Вы шутите? Что значит "Как вы докатились"?
— Я хочу спросить: почему вы собираетесь от нас уходить?
— Ну, по личным обстоятельствам.
— А какие у вас личные обстоятельства? Вы куда-то уезжаете?
— Можно и так сказать. Но думаю, что мои личные обстоятельства не должны вас интересовать.
— Если вы переезжаете или не можете посещать занятия в ближайшем будущем, то мы вам можем предложить пройти обучение удаленно или закончить его через пару месяцев.
— Нет, вы не понимаете... Я ухожу, полностью и навсегда. И я не могу и не смогу никогда посещать занятия и закончить интернатуру, а тем более у вас работать.
— Хорошо. Но вы понимаете, что если вы не назовете мне причину, то я буду думать, что вы уходите по собственному желанию. А тогда вы, согласно договору, что мы подписали, должны компенсировать нам сумму затраченную на ваше обучение.
— Но в договоре говориться, что я должен буду компенсировать только в том случае, если увольняюсь из компании по собственному желанию.
— Да, верно.
— Но я не увольняюсь. Я ухожу из интернатуры.
— Нет, вы неправильно поняли договор. Там написано…
— Я знаю, что там написано. Но вы понимаете договор иначе, чем я! Нам что в суде нужно будет разбираться?
— Если нужно, то будем разбираться в суде.
— Но я хочу уточнить. Вы говорите, что я должен компенсировать сумму, что была потрачена на мое обучение, верно? Но я же не все обучение отходил! Почему тогда я должен компенсировать все 15 тысяч гривен?
— Все 15 тысяч не нужно. Мы посчитаем количество занятий до сегодняшнего дня и определим долю, которую вы заплатите.
— Подождите, а где в договоре написана формула, по которой будет вычисляться моя доля?
— Молодой человек, вы мне не дерзите. И, кстати, этого всего можно избежать, если вы сейчас вернетесь на занятия и сдадите аттестацию.
```
Тут я задумался: а если я плохо сдам аттестацию, то они же не будут брать меня на стажировку. А, значит, после заваленной аттестации я смогу просто уйти.
```
— То есть получается, если я отхожу все занятия и плохо сдам аттестацию, то вы меня не примете на работу и я никому не буду должен денег?
— Именно так и получается.
```
Молчание. 15 К у меня нету - это мне было известно точно.

Я даже подумал о том, чтобы вернуться прямо сейчас на занятия. Но тут же представил себе такую ситуацию, расклад пессимиста: я заканчиваю интернатуру, сдаю аттестацию специально плохо, чтобы уйти от них и не быть должным денег, но мою аттестационную работу все равно засчитывают и зачисляют меня в штат на ставку, к примеру, 2 рубля в месяц. И самое забавное: я не смогу от них уйти по собственному желанию, ведь, согласно договору, должен буду им 15 тысяч.

Я еще раз попытался доказать директору, что я не должен никому и ничего, а он мне - обратное. Далее я прошу принести наш договор, чтобы обсуждать его по существу, читаю и повторно поясняю собеседнику пару пунктов, но директор неумолим.

Еще через пару минут он встает, выходит из переговорки и напоследок говорит:
```
— Я не вижу смысла с вами больше общаться. Либо вы возвращаетесь на занятия, сдаете аттестацию, получаете вознаграждение и перспективную работу либо сдаете карточку и уходите, а мы с вами потом свяжемся.
```

Но, видать, рассказы директора о долях, которые следует компенсировать, не произвели должного впечатления, ведь я, все-таки, отдал магнитную карточку Елене, поблагодарил за уделенное мне время, попрощался и ушел от них навсегда.

Кстати, уже почти полгода прошло, а со мной никто не связался. Не нужны им, видать, эти 15 тысяч.

Tags: it-enterprise, intern, kpi

