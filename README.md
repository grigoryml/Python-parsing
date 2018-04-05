# Python-parsing
Yandex search log keywords parsing


Input Log example
			timestamp	datetime	device	numdoc	region	request	urls
			1520974800	2018-03-14 00:00	desktop	277053268	191	https://yandex.ru/search/?text=sad story скачать бесплатно mp3 в хорошем качестве&rl=416	http://mp3party.net/music/8507899;http://muz-color.ru/?s=Sad+Story+%28Out+Of+Luck%29;https://muzofond.org/search/merk%20kremont%20sad%20story
			1520974800	2018-03-14 00:00	touch	19987730	2	https://yandex.ru/search/?text=ольгино баня&flag=l6707	http://www.bani.spb.ru/olgino.html;https://sauna.spb.ru/olgino.html;https://spb.hipdir.com/banya-olgino/
			1520974800	2018-03-14 00:00	touch	196215754	26955	https://yandex.ru/search/?text=фирменный магазин марко в г минске скидки акции	http://www.marko.by/actions/;https://marko.vitrini.by/catalog/;http://www.marko.by/actions/97.html
			1520974800	2018-03-14 00:00	desktop	3909882795	101704	https://yandex.ru/search/?text=порно&rl=313	http://porno365.xxx/;https://prostoporno.sex/categories/;http://pornolomka.net/
			1520974800	2018-03-14 00:00	desktop	106605468	213	https://yandex.ru/search/?text=нужно ли мыть гречку перед варкой&id=hYYVGyK1cLWHo94T&client=980022	http://www.bolshoyvopros.ru/questions/1466048-nado-li-myt-grechku-pered-varkoj.html;http://2oa.ru/nuzhno-li-myt-grechku-pered-varkoy/;https://otvet.mail.ru/question/35010174
			1520974801	2018-03-14 00:00	touch	171673301	16

Output Log example
      sad story скачать бесплатно mp3 в хорошем качестве
      ольгино баня
      фирменный магазин марко в г минске скидки акции
      порно
      нужно ли мыть гречку перед варкой
      сергей из ярославля дом 2?
      красный дракон фильм 2002
      земельно оценочные работы в земельном кадастре
      Динамо (Санкт-Петербург) Химки 16 марта

