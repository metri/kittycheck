* Написать одностраничный хоумпейдж на kittycheck.com на английском языке.
* Задеплоить всё на нжинксе
    - пока передеплоил на нжинксе но через питон
* <del>Пропиарить в твиттере бобука</del>
* <del>Сделать так, чтобы снаружи подключалось всё одной строчкой.</del> done in [8971b5a](https://github.com/bobuk/kittycheck/commit/8971b5ad7590ac223aa901972e7465923a56b3b3)
* <del>Сделать так, чтобы при ембеде в страницу можно было принудительно указать site_uniq_id</del>
   - задается через мета-тег `<meta name="kittycheck_site_uniq_id" content="72f06eedb2fd5971d8fa9df1918793fe" />`
* <del>Задокументировать, как потребитель может регулировать положение кошечки на странице</del>
   - осуществляется с помощью мета-тега `<meta name="kittycheck_position" content="top=10,left=10" />`
   - syndicut: возможно стоит убрать этот код, все равно css можно задавать и обычным способом
* <del>Перекрасить крутилку у китечки в благородный серый цвет и сделать опцию, позволяющую перекрашивать крутилку</del>
   - осуществляется с помощью мета-тега `<meta name="kittycheck_checkin_color" content="#BADA55" />`
   - можно писать в формате hex, rgb(a)
   - по умолчанию `rgba(0,0,0,0.2)`