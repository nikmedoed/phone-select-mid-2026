# Обработка обзоров телефонов

Источник транскриптов: `D:\System\Users\sirne\Downloads\13`.

## Правила

- Это единственный рабочий файл по обзорам. Не заводить отдельные CSV/README/duplicates.
- В очереди должны оставаться только файлы, которые реально надо читать. Дубли, шорты без смысла и нерелевантные ролики удалять из очереди, а не таскать статусами.
- После чтения обзора сразу обновлять соответствующий `data/models/*.yaml`: критерии, риски, firstCheck/specs, если вывод влияет на выбор.
- В этот файл писать только краткий журнал: какой файл обработан и какие поля спеки поменялись. Подробная правда должна жить в `data/models/*.yaml`.
- Не переписывать `input/ЗАПРОС.md`; он остаётся источником требований.

## Что вытаскивать

- Камера, видео, быстрый снимок, фронталка, батарея/GPS, нагрев, прошивка, уведомления, Google Pay, eSIM/SKU, связь/bands/GPS lock, эргономика без чехла, прочность, цена/value.
- Полезные замечания и комментарии по опыту использования, хаки
- Важные признаки для сравнения 

Не тащить
- распаковку, рекламную воду и голые спеки без опыта.
- Комментарии по кривым китайксим версиям, что мы не будем брать, при наличии глобальной

## Текущие выводы

- OnePlus 15: обработаны ещё 8 обзоров. Оставлен как рациональный value/автономность, но камера не причина покупки: вечерний tele/ширик, tele close-focus/macro, AI-дорисовка на зуме и видео/фронталка слабее Oppo/Vivo/iPhone. Добавлены уточнения по Global/India/CN-комплектам, отсутствию БП/записи звонков в Global, сильной связи/GPS, жестам/Plus Key, 165 Гц только в отдельных играх, быстрой камере и долгой автономности.
- OPPO Find X9 Pro: усилен как камерный кандидат; добавлен плюс по стабильности/нагреву против OnePlus 15, но сохранены риски цены, веса, Global/SKU, Google Pay/eSIM и ColorOS/background.
- OnePlus 13: обработаны первые 8 обзоров. Усилен как value-альтернатива OP15: фото чаще стабильнее/естественнее, старый Alert Slider удобен, автономность 8-10 ч экрана, экран/вибро/скорость сильные. Риски: только Global/eSIM, CN без eSIM/Android Auto и с SIM/OTA/Google-возней; видео не уровень камерофонов, 3x телевик средний, стеклянные версии скользкие, 2.5D-стекло сложнее защищать, под тяжелой нагрузкой возможны нагрев/FPS lock.
- Honor Magic 8 Pro: после 12 релевантных обзоров выглядит одним из самых сбалансированных флагманов: 3D Face ID, экран, звук, связь, автономность и tele-зум сильные; риски смещены в SKU/eSIM/ёмкость батареи, CN-настройку MagicOS/AI/фона, видео, ультраширик и Honor-обработку цвета/дорисовки.
- OnePlus 15: обработаны ещё 8 обзоров. В `data/models/oneplus15.yaml` уточнены риски CN/прошивки: OTA и Google могут работать, но eSIM аппаратно не появляется, B20/агрегация требуют проверки. Добавлены блики экрана против S25 Ultra, вес до 218 г, медленная зарядка без SuperVOOC, видео-артефакты, Telegram-группировка уведомлений, нюансы Smart Switch/шаринга/O+ Connect, высокие кнопки и подтверждение 10-14 ч экрана у долгого владельца.

## Очередь
- OnePlus 15 | `yNFnYqUxzW0` | `NA - ОНИ сотворили ЗВЕРЯ! ONEPLUS 15 - козыри, косяки, сюрпризы [yNFnYqUxzW0].txt`
- OnePlus 15 | `OHi5qkCmfbA` | `NA - Обзор OnePlus 15 — восторг! Лучший смартфон по соотношению цена-качество в 2025-м! [OHi5qkCmfbA].txt`
- OnePlus 15 | `f4XUEhbOBNs` | `NA - Обзор OnePlus 15T — компакт на 3 дня автономности! [f4XUEhbOBNs].txt`
- OnePlus 15 | `sWrkldzPpY8` | `NA - Полный обзор OnePlus 15. Когда ценник удивил. [sWrkldzPpY8].txt`
- OnePlus 15 | `cPIgVAD4OHU` | `NA - ТОП 20 Новых фишек ONEPLUS 15 и OXYGEN 16. ЧТО НОВОГО？ [cPIgVAD4OHU].txt`
- Samsung Galaxy S25+ | `XUEOiK-zrBM` | `041 - Честный обзор Samsung Galaxy S25 Plus ⧸  Арстайл ⧸ [XUEOiK-zrBM].txt`
- Samsung Galaxy S25+ | `VQyhuhtCzj8` | `042 - Недооцененный Флагман🔥 Смартфон Samsung Galaxy S25 Plus или Лучше Apple iPhone 13 Pro Max Бестселлер [VQyhuhtCzj8].txt`
- Samsung Galaxy S25+ | `_C0En7jiGgI` | `043 - Samsung S25, S25+ и Ultra. Брать или нет в 2026？ [_C0En7jiGgI].txt`
- Samsung Galaxy S25+ | `B5xDrQ6Cctg` | `045 - Samsung Galaxy S25+ и S25FE. В чем разница и что же взять？ [B5xDrQ6Cctg].txt`
- Samsung Galaxy S25+ | `Vc777BuHRVg` | `047 - Samsung Galaxy S25 Ultra, S25 Plus и S25 — первые впечатления от новинок! [Vc777BuHRVg].txt`
- Samsung Galaxy S25+ | `ATyD12fDShQ` | `048 - Samsung S25 vs S25+ [ATyD12fDShQ].txt`
- Samsung Galaxy S25+ | `GgmInWD14Bg` | `050 - Обзор Samsung Galaxy S25+ - средний класс с массой недостатков [GgmInWD14Bg].txt`
- Samsung Galaxy S25+ | `mo7rXIA8Xpk` | `051 - SAMSUNG Galaxy S25+ — Распаковка и первый взгляд [mo7rXIA8Xpk].txt`
- Samsung Galaxy S25+ | `Ck64MdgK8Rk` | `052 - Десять причин купить Samsung Galaxy S25 Plus [Ck64MdgK8Rk].txt`
- Samsung Galaxy S25+ | `Tb4h294AXVA` | `053 - Samsung S25 Plus - Poco F8 Ultra Что выбрать？ [Tb4h294AXVA].txt`
- Samsung Galaxy S25+ | `QJEP9sTyuPA` | `054 - Samsung Galaxy S25 и S25+ ｜ Стоит обновляться？ [QJEP9sTyuPA].txt`
- Samsung Galaxy S25+ | `jd4pbOsxTMc` | `055 - Десять причин не покупать Samsung Galaxy S25 Plus [jd4pbOsxTMc].txt`
- Samsung Galaxy S25+ | `EHhBkAxNfhk` | `057 - БЕССТЫДНОЕ сравнение Samsung Galaxy S26 Plus и Galaxy S25 Plus! ⧸ Арстайл ⧸ [EHhBkAxNfhk].txt`
- Samsung Galaxy S25+ | `R-Avs-y5FjU` | `060 - Честное сравнение Samsung Galaxy S25 Plus и Galaxy S24 Plus!  ⧸  Арстайл ⧸ [R-Avs-y5FjU].txt`
- Samsung Galaxy S25+ | `ISadrOUkoEw` | `073 - SAMSUNG Galaxy S26+ — чем отличается от Galaxy S25+ и стоит ли менять？ [ISadrOUkoEw].txt`
- Samsung Galaxy S25+ | `xEN54hlK2cA` | `086 - Samsung galaxy s26 plus vs s26 ultra s25 ultra и s25+ обзор и сравнение экранов и камер [xEN54hlK2cA].txt`
- Samsung Galaxy S26+ | `qnDkK9pxZ6A` | `070 - Galaxy S26 Plus - ЛУЧШИЙ ОБЗОР [qnDkK9pxZ6A].txt`
- Samsung Galaxy S26+ | `0Bh2wr8ogk4` | `071 - Солидный флагман с AI-фишками - Samsung Galaxy S26+ [0Bh2wr8ogk4].txt`
- Samsung Galaxy S26+ | `-JtPBpdXM24` | `074 - Samsung Galaxy S26 и S26+ — что покупать в 2026 и стоит ли менять S25？ [-JtPBpdXM24].txt`
- Samsung Galaxy S26+ | `l-lw-XRrQU4` | `075 - SAMSUNG Galaxy S26+ — обзор： Snapdragon 8 Elite, Galaxy AI, камеры и автономность [l-lw-XRrQU4].txt`
- Samsung Galaxy S26+ | `1AHKuOyN79o` | `076 - Samsung S26+ vs S26 Ultra 🔥 Стоит ли переплачивать？ [1AHKuOyN79o].txt`
- Samsung Galaxy S26+ | `J0eosmb1p8g` | `078 - Samsung Galaxy S26 Plus - Новый старый флагман [J0eosmb1p8g].txt`
- Samsung Galaxy S26+ | `qI3qdOGRXcI` | `080 - Впервые 2 нм в смартфоне. Про Samsung Galaxy S26+ [qI3qdOGRXcI].txt`
- Samsung Galaxy S26+ | `dG2VxyZDVmY` | `081 - Samsung Galaxy S26, S26+ и S26 Ultra — вся новая линейка уже здесь! [dG2VxyZDVmY].txt`
- Samsung Galaxy S26+ | `2jtF2jauSXU` | `082 - Флагман и средний сегмент (A57 vs S26+) В чем разница, что вы не получаете и получаете [2jtF2jauSXU].txt`
- Samsung Galaxy S26+ | `UGBR3nshztQ` | `084 - Samsung Galaxy S26 Plus первый обзор на русском [UGBR3nshztQ].txt`
- Samsung Galaxy S26+ | `2GUP8e1FAqc` | `087 - Samsung Galaxy S26 и S26 Plus - ЧЕСТНЫЙ ОБЗОР! Стоит ли обновляться？ [2GUP8e1FAqc].txt`
