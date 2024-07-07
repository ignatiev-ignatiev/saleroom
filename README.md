# Исследование объявлений о продаже квартир

У нас в распоряжении данные сервиса Яндекс.Недвижимость — архив объявлений о продаже квартир в Санкт-Петербурге и соседних населённых пунктах за несколько лет. Нужно научиться определять рыночную стоимость объектов недвижимости. Наша задача — установить параметры. 

# Общий вывод

Мы рассмотрели данные по файлу за выделенный учетный период. В целом большинство данных удалось заменить либо убрать, однако были моменты в которых данных не хватало. После проведения работы по обработке и анализу данных, связанных с пропущенными и некорректными значениями, становится очевидным, что необходимо обратить внимание на заполнение данных, а также на корректность выгрузки данных из программы. Ошибки, как опечатки, в целом отсутствовали, что значительно упростило процесс предобработки данных для последующего анализа.

В ТОП-5 входят ближайшие к Санкт-Петербургу города и сгорода области:Пушкин,Гатчина,Всеволожск,Выборг. Цена конечно в основном зависит от площади квартиры, однако как мы увидели на примере с этажностью, что этаж может быть очень одним из факторов различия цены. Также на цену значильно влияет размещение от центра. Сроки продаж- это либо быстрые сделки до 30 дней, либо сделки от 2 до 3 месяцев в основном. Большинство объектов имеют площадь от 30 до 62 кв. стоимостью от 2 до 6 млн. руб., в основном это одно-двух комнатные квартиры с высотой потолков — от 2.6 до 2.7 м.
