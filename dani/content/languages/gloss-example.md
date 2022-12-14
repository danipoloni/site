---
title: "Gloss Example"
date: 2022-11-29T21:15:22+04:00
draft: true
summary: "Примеры шаблона глоссирования"
---

Упрощенные варианты фразы и траскрипта генерируются автоматически. Для этого из соответствующих строк исключаются "-". 
{{< gloss 
  phrase="nevi qep u-van-u li laka omi ka-tomu-cme" 
  transcript="неви кеп у-ван-у ли лака оми ка-тому-шме"
  dt_gloss="девочка SBJ PL-готовить-PL OBJ суп быть.3sPRS уже-есть-чтобы"
  sm_gloss="девочка ею готовки его суп есть поесть-чтобы"
  translation="девочка имеет обыкновение готовить суп, чтобы поесть" 
>}}

Если в исходной фразе есть дефисы, не относящиеся к глоссированию, можно задать упрощенные варианты фразы и транскрипта вручную.
{{< gloss 
  phrase="nev-u kne luni pon-poni omi ka-tomu-cme"
  sm_phrase="nevu kne luni pon-poni omi katomucme"
  transcript="нев-у кне луни пон-пони оми ка-тому-шме"
  sm_transcript="неву кне луни пон-пони оми катомушме"
  dt_gloss="девочка-PL SBJ гладить хороший~DIM быть.3sPRS PFV-есть-чтобы"
  sm_gloss=""
  translation="девочки гладят кого-то хорошего" 
>}}

Глоссы, как и транскрипт, можно опустить, тогда они не будут отображены. 
{{< gloss 
  phrase=""
  sm_phrase=""
  transcript="неви кеп у-ван-у ли лака оми ка-тому-шме"
  sm_transcript=""
  dt_gloss=""
  sm_gloss=""
  translation="девочка имеет обыкновение готовить суп, чтобы поесть" 
>}}