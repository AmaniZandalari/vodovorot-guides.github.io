---
title: Обзор Ковенантов – Шаман Стихии
layout: page
last_update: 2020-10-11
wow: 9.0.1
toc: true
author: Amani
---

# Вступление

**Ковенанты** – это новые фракции, к которым игроки примкнут в ходе путешествия по Темным Землям. Всего их четыре, и каждый из них дает доступ к двум способностям – одна общая, и одна уникальная для класса. В связи с тем, что шаман позиционируется как «гибридный класс», все наши уникальные способности ковенантов имеют также лечащую часть, в той или иной степени.

Выбор ковенанта происходит после прокачки, но во время неё мы сможем опробовать все способности и принять решение. Также выбор ковенанта дает доступ к уникальному комплекту доспехов, и возможность связать свою душу с одним из медиумов, чтобы получить дополнительные усиления.

**Помните, что правки способностей ковенантов идут практически каждую неделю и сейчас нет смысла ничего выбирать, для этого следует дождаться релиза.** Тоже самое касается медиумов – сейчас мало смысла о них говорить, так как все постоянно меняется.

# Кирии

<p align="center" width="100%">
    <img src="/assets/img/kyrian_idle1.png"> 
</p>

## Классовая способность 

{{ site.data.covenants.vt }} – мы устанавливаем тотем, который при каждом использовании атакующей способности бьет вокруг себя шестерых врагов, а при применении лечащих заклинаний, он отхилит шестерых союзников. Нанесение урона и лечение от тотема срабатывает максимум по три раза, и никак не связаны между собой. То есть мы не лишаемся урона от тотема, если после его установки используем несколько заклинаний лечения, и наоборот. Сам тотем стоит 30 секунд, а повторное применение переместит его на новое место.

* Если цель находится в движении, то использовать этот тотем становится не очень удобно.  
* Перестановка тотема не тратит ГКД, но имеет отдельный кулдаун – 3 сек.  
* Мобы не агрятся на тотем, то есть его можно ставить заранее до пула.  
* Кулдаун в 1 минуту хорошо подходит под многие бои в Замке Нафрия, так как сочетается с фазами выхода аддов или дополнительного урона по боссу.  
* Тотем имеет не очень большой радиус действия.  
* Необходимо тратить ГКД для реализации саппорт потенциала этой способности.  
* Отхил срабатывает в том числе от установки {{ site.data.spells.hst }}.   
* Тотем имеет всего 5 ед. здоровья, что делает очень проблематичным его использование в ПвП.  
* {{ site.data.conduits.dirge }} – проводник, усиливающий эту способность. Увеличивает наносимый урон и исцеление по одной цели, которая находится ближе всех к {{ site.data.covenants.vt }}. Крайне хорош в бою против одной цели.

## Общая способность  

{{ site.data.covenants.steward }} – призывает распорядителя, который приносит нам {{ site.data.covenants.phial }}, восполняющий 15% здоровья и снимающий проклятья, болезни, яды и эффекты кровотечения. Распорядитель также предоставляет ряд полезных услуг, типа банка, перековки, почты или починки.

* Флакон имеет три заряда и кулдаун 3 минуты, но отсчет начинается только после выхода из боя.  
* Флакон не делит время восстановления ни с {{ site.data.spells.pot }}, ни с {{ site.data.spells.healthstone }}.
* Может быть полезен для снятия различных дебаффов в рейде или Мифик+.  
* Не снимает магические эффекты, которые обычно самые опасные, а проклятия шаман может снять самостоятельно.
* На данный момент, судя по тестам, в рейде достаточно часто накладываются опасные кровотечения, что делает эту способность достаточно эффективной.

# Вентиры

<p align="center" width="100%">
    <img src="/assets/img/venthyr_idle1.png"> 
</p>

## Классовая способность  

{{ site.data.covenants.ch }} –  похожа на смесь двух наших заклинаний, {{ site.data.spells.cl }} и {{ site.data.spells.ch }}, но на пять целей и с кулдауном в полторы минуты.

* Нанесение урона и отхил срабатывает одновременно.
* Снижает своё время восстановления на 5 секунд за каждое критическое попадание этой способностью, в том числе и от лечения.
* Максимум время восстановления может снизиться до 40 сек.
* У Элема {{ site.data.covenants.ch }} дублируется с помощью таланта {{ site.data.spells.ecs }}. То есть кулдаун сокращается еще больше, как за два применения по цене одного.
* В сочетании с талантом {{ site.data.spells.ag }} она очень сильно хилит, практически как рейд сейв.  
* В первую очередь исцеляет самые раненые цели, то есть является «смарт-хилом».
* **Важно!** Хоть эта способность и выглядит так, будто она перескакивает от одной цели к другой, как {{ site.data.spells.cl }}, механика её работы кардинально отличается. По  сути это круговое АоЕ, которое лечит и дамажит 5 целей вокруг основной. Радиус действия – 20 метров вокруг первоначальной цели. 
* {{ site.data.conduits.harvest }} – проводник, усиливающий эту способность. Увеличение шанса Критического удара как поднимает урон, так и потенциально снижает кулдаун {{ site.data.covenants.ch }}.  

## Общая способность 

{{ site.data.covenants.door }} – телепорт на 35 метров со временем произнесения 1.5 сек.

* Перемещение с помощью {{ site.data.covenants.door }} не агрит противников на своем пути.  
* Для пропуска групп врагов в Мифик+ использовать его вряд-ли получится, так как дальность телепорта довольно маленькая.  
* Потенциально будет полезен в рейде, где достаточно много моментов когда нужно быстро оказаться в другом месте, чтобы перекрыть войдзону или вынести какой-нибудь дебафф.

# Некролорды

<p align="center" width="100%">
    <img src="/assets/img/necro_idle1.png"> 
</p>

## Классовая способность 

{{ site.data.covenants.pw }} – поражает одну цель, нанося небольшой урон противнику и накладывая на него {{ site.data.spells.fs }}. Применяется мгновенно. Время восстановления 45 сек. Наш следующий {{ site.data.spells.lvb }} также применится ко всем целям под {{ site.data.spells.fs }} c 80% от своего изначального урона.

* На все дублированные Выбросы лавы может сработать Искусность: {{ site.data.spells.elem_mastery }}, шанс рассчитывается отдельно для каждой цели, и они также дают Энергию Водоворота.  
* Учитывая кулдаун и длительность  {{ site.data.spells.fs }}, мы сможем поддерживать его максимум на трех врагах, и накладывать четвертый за счёт {{ site.data.covenants.pw }}.  
* Активный {{ site.data.spells.fe }} позволяет поддерживать еще больше шоков.  
* Полностью отсутствует саппорт потенциал.  
* Лучше всего себя показывает в бою против разрозненных целей, где необходимо поддерживать сразу несколько {{ site.data.spells.fs }}.  
* {{ site.data.covenants.pw }} может давать достаточно сильный бурст на Арене, к тому же чаще, чем другие способности ковенантов.  
* {{ site.data.conduits.wave }} – проводник, усиливающий эту способность. Дает 20-40% шанс сбросить кулдаун {{ site.data.covenants.pw }} при её использовании. Рандомный шанс срабатывания может понравится не всем, но если напрокает – урон вырастает достаточно ощутимо, особенно на АоЕ.

## Общая способность  

{{ site.data.covenants.fleshcraft }} – абсорб на 20%, который кастуется 4 сек.

* В зависимости от количества и качества мертвых врагов вокруг персонажа, значение абсорбра может быть повышено, вплоть до 50%.  
* Этот щит можно накладывать на себя после смерти пака в Мифик+ или прямо перед пулом босса, благо время действия позволяет.  
* В бою четырехсекундный каст щита приведет к потере урона, но если это будет вопрос жизни и смерти, то выбора не останется.  

# Ночной народец

<p align="center" width="100%">
    <img src="/assets/img/fae_idle1.png"> 
</p>

## Классовая способность  

{{ site.data.covenants.ft }} – потоковое АоЕ заклинание со временем восстановления 2 мин., которое наносит в выбранной области урон четырем противникам каждые полсекунды в течении трёх секунд. Урон делится между всеми пораженными целями. После окончания каста, повторная активация способности испускает волну исцеления вокруг персонажа, отхиливая 4 союзников на 15% от нанесенного урона.

* Урон от этой способности усиливается от таланта {{ site.data.spells.mote }}.  
* На самом деле эта способность наносит урон 7 раз, а не 6. Подсказка на Вовхеде не учитывает «initial tick», то есть урон на 0 секунде использования.
* Единственная способность ковенантов, урон которой не увеличивается на АоЕ, а просто делится в зависимости от количества целей.
* {{ site.data.conduits.fae }} – проводник, усиливающий эту способность. Уменьшает время произнесения и увеличивает урон, но для способности с кулдауном в 2 минуты это достаточно слабо.  
* На данный момент эта способность крайне слаба, ждем тюнинг или переработку.  

## Общая способность 

{{ site.data.covenants.soulshape }} – раз в полторы минуты позволяет превращаться в лисохвоста на 12 сек. В момент превращения совершается телепорт на 15 метров вперед. 

* Телепорт во время действия лисохвоста можно применить еще раз, его время восстановления составляет 4 сек., но при выходе из формы лисохвоста обратно вернуться уже не получится.
* Скорость передвижения лисохвоста не стакается с призрачным волком.
* В зоне отдыха длительность действия {{ site.data.covenants.soulshape }} не ограничена.
* Для шамана эта способность ценна в первую очередь как телепорт, а не как ускорение.
* Имеет 24 различных облика, которые открываются по мере прокачки ковенанта, есть даже раптор и волк!

