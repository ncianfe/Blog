---
title: Industrial Conflicts in Switzerland
author: Nicola Cianferoni
date: '2021-06-10'
slug: industrial-conflicts-in-switzerland
categories: [Industrial conflicts]
tags: []
subtitle: ''
summary: ''
authors: []
lastmod: '2021-06-10T21:34:04+02:00'
featured: no
image:
  caption: ''
  focal_point: ''
  preview_only: no
projects: []
---

<script src="{{< blogdown/postref >}}index_files/htmlwidgets/htmlwidgets.js"></script>
<script src="{{< blogdown/postref >}}index_files/plotly-binding/plotly.js"></script>
<script src="{{< blogdown/postref >}}index_files/typedarray/typedarray.min.js"></script>
<script src="{{< blogdown/postref >}}index_files/jquery/jquery.min.js"></script>
<link href="{{< blogdown/postref >}}index_files/crosstalk/css/crosstalk.css" rel="stylesheet" />
<script src="{{< blogdown/postref >}}index_files/crosstalk/js/crosstalk.min.js"></script>
<link href="{{< blogdown/postref >}}index_files/plotly-htmlwidgets-css/plotly-htmlwidgets.css" rel="stylesheet" />
<script src="{{< blogdown/postref >}}index_files/plotly-main/plotly-latest.min.js"></script>

``` r
ggplotly(
  strikes_ch %>%
  ggplot(aes(x=year, y=nb)) +
  geom_smooth(se=F) +
  geom_line(size=1) +
  labs(title = "Number of strikes in Switzerland",
       caption="Source: Swiss federal office for statistics") +
  theme_ipsum()
)
```

<div id="htmlwidget-1" style="width:672px;height:480px;" class="plotly html-widget"></div>
<script type="application/json" data-for="htmlwidget-1">{"x":{"data":[{"x":[1927,1928.17721518987,1929.35443037975,1930.53164556962,1931.70886075949,1932.88607594937,1934.06329113924,1935.24050632911,1936.41772151899,1937.59493670886,1938.77215189873,1939.94936708861,1941.12658227848,1942.30379746835,1943.48101265823,1944.6582278481,1945.83544303797,1947.01265822785,1948.18987341772,1949.36708860759,1950.54430379747,1951.72151898734,1952.89873417722,1954.07594936709,1955.25316455696,1956.43037974684,1957.60759493671,1958.78481012658,1959.96202531646,1961.13924050633,1962.3164556962,1963.49367088608,1964.67088607595,1965.84810126582,1967.0253164557,1968.20253164557,1969.37974683544,1970.55696202532,1971.73417721519,1972.91139240506,1974.08860759494,1975.26582278481,1976.44303797468,1977.62025316456,1978.79746835443,1979.9746835443,1981.15189873418,1982.32911392405,1983.50632911392,1984.6835443038,1985.86075949367,1987.03797468354,1988.21518987342,1989.39240506329,1990.56962025316,1991.74683544304,1992.92405063291,1994.10126582278,1995.27848101266,1996.45569620253,1997.63291139241,1998.81012658228,1999.98734177215,2001.16455696203,2002.3417721519,2003.51898734177,2004.69620253165,2005.87341772152,2007.05063291139,2008.22784810127,2009.40506329114,2010.58227848101,2011.75949367089,2012.93670886076,2014.11392405063,2015.29113924051,2016.46835443038,2017.64556962025,2018.82278481013,2020],"y":[37.5485636390991,35.952447425905,34.3941151816527,32.872457100206,31.3863633754274,29.9347242011806,28.516429771328,27.1303702797335,25.7754359202596,24.4505168867695,23.1546594437274,21.888712859588,20.654683073479,19.4545949292844,18.2904732708883,17.1643429421751,16.0782287870288,15.0341556493338,14.0341483729741,13.0802318018342,12.1698034239349,11.2742092892165,10.3938315735707,9.53554254361689,8.70621446597497,7.91271960726447,7.16193023410493,6.46071861311628,5.81595701091792,5.23451769412977,4.72530729096171,4.32715055447608,4.03730118902354,3.8355486741855,3.70168248954349,3.61549211467888,3.55676702917315,3.50529671260771,3.440870644564,3.34327830462347,3.25309724190757,3.23494139891135,3.2752199801723,3.35994533277219,3.47512980379283,3.60678574031602,3.74092548942351,3.86356139819713,3.96070581371865,4.01837108306986,4.03485001487577,4.03794255137378,4.0346800572279,4.03067001592118,4.0315199109367,4.0428372257575,4.07022944386666,4.11930404874724,4.19566852388229,4.30262443402872,4.4216445006644,4.5483346410905,4.68379967841306,4.82914443573803,4.98547373617149,5.15389240281938,5.33550525878779,5.53141712718264,5.74273283110998,5.97050491149151,6.21367171536193,6.47117181162143,6.74269843861536,7.02794483468927,7.32660423818849,7.63836988745853,7.9629350208449,8.2999928766929,8.64923669334813,9.01035970915587],"text":["year: 1927.000<br />nb: 37.548564","year: 1928.177<br />nb: 35.952447","year: 1929.354<br />nb: 34.394115","year: 1930.532<br />nb: 32.872457","year: 1931.709<br />nb: 31.386363","year: 1932.886<br />nb: 29.934724","year: 1934.063<br />nb: 28.516430","year: 1935.241<br />nb: 27.130370","year: 1936.418<br />nb: 25.775436","year: 1937.595<br />nb: 24.450517","year: 1938.772<br />nb: 23.154659","year: 1939.949<br />nb: 21.888713","year: 1941.127<br />nb: 20.654683","year: 1942.304<br />nb: 19.454595","year: 1943.481<br />nb: 18.290473","year: 1944.658<br />nb: 17.164343","year: 1945.835<br />nb: 16.078229","year: 1947.013<br />nb: 15.034156","year: 1948.190<br />nb: 14.034148","year: 1949.367<br />nb: 13.080232","year: 1950.544<br />nb: 12.169803","year: 1951.722<br />nb: 11.274209","year: 1952.899<br />nb: 10.393832","year: 1954.076<br />nb:  9.535543","year: 1955.253<br />nb:  8.706214","year: 1956.430<br />nb:  7.912720","year: 1957.608<br />nb:  7.161930","year: 1958.785<br />nb:  6.460719","year: 1959.962<br />nb:  5.815957","year: 1961.139<br />nb:  5.234518","year: 1962.316<br />nb:  4.725307","year: 1963.494<br />nb:  4.327151","year: 1964.671<br />nb:  4.037301","year: 1965.848<br />nb:  3.835549","year: 1967.025<br />nb:  3.701682","year: 1968.203<br />nb:  3.615492","year: 1969.380<br />nb:  3.556767","year: 1970.557<br />nb:  3.505297","year: 1971.734<br />nb:  3.440871","year: 1972.911<br />nb:  3.343278","year: 1974.089<br />nb:  3.253097","year: 1975.266<br />nb:  3.234941","year: 1976.443<br />nb:  3.275220","year: 1977.620<br />nb:  3.359945","year: 1978.797<br />nb:  3.475130","year: 1979.975<br />nb:  3.606786","year: 1981.152<br />nb:  3.740925","year: 1982.329<br />nb:  3.863561","year: 1983.506<br />nb:  3.960706","year: 1984.684<br />nb:  4.018371","year: 1985.861<br />nb:  4.034850","year: 1987.038<br />nb:  4.037943","year: 1988.215<br />nb:  4.034680","year: 1989.392<br />nb:  4.030670","year: 1990.570<br />nb:  4.031520","year: 1991.747<br />nb:  4.042837","year: 1992.924<br />nb:  4.070229","year: 1994.101<br />nb:  4.119304","year: 1995.278<br />nb:  4.195669","year: 1996.456<br />nb:  4.302624","year: 1997.633<br />nb:  4.421645","year: 1998.810<br />nb:  4.548335","year: 1999.987<br />nb:  4.683800","year: 2001.165<br />nb:  4.829144","year: 2002.342<br />nb:  4.985474","year: 2003.519<br />nb:  5.153892","year: 2004.696<br />nb:  5.335505","year: 2005.873<br />nb:  5.531417","year: 2007.051<br />nb:  5.742733","year: 2008.228<br />nb:  5.970505","year: 2009.405<br />nb:  6.213672","year: 2010.582<br />nb:  6.471172","year: 2011.759<br />nb:  6.742698","year: 2012.937<br />nb:  7.027945","year: 2014.114<br />nb:  7.326604","year: 2015.291<br />nb:  7.638370","year: 2016.468<br />nb:  7.962935","year: 2017.646<br />nb:  8.299993","year: 2018.823<br />nb:  8.649237","year: 2020.000<br />nb:  9.010360"],"type":"scatter","mode":"lines","name":"fitted values","line":{"width":3.77952755905512,"color":"rgba(51,102,255,1)","dash":"solid"},"hoveron":"points","showlegend":false,"xaxis":"x","yaxis":"y","hoverinfo":"text","frame":null},{"x":[1927,1928,1929,1930,1931,1932,1933,1934,1935,1936,1937,1938,1939,1940,1941,1942,1943,1944,1945,1946,1947,1948,1949,1950,1951,1952,1953,1954,1955,1956,1957,1958,1959,1960,1961,1962,1963,1964,1965,1966,1967,1968,1969,1970,1971,1972,1973,1974,1975,1976,1977,1978,1979,1980,1981,1982,1983,1984,1985,1986,1987,1988,1989,1990,1991,1992,1993,1994,1995,1996,1997,1998,1999,2000,2001,2002,2003,2004,2005,2006,2007,2008,2009,2010,2011,2012,2013,2014,2015,2016,2017,2018,2020,null],"y":[26,45,39,31,25,38,35,20,17,41,37,17,7,6,15,19,19,18,35,55,29,28,12,6,8,8,6,6,4,5,2,3,4,8,0,2,4,1,2,2,1,1,1,3,11,5,0,3,6,19,9,10,8,5,1,1,5,2,3,1,0,4,2,2,1,3,0,8,2,3,2,7,5,8,3,4,9,8,5,3,2,8,3,3,7,7,11,8,13,8,11,8,3,4],"text":["year: 1927<br />nb: 26","year: 1928<br />nb: 45","year: 1929<br />nb: 39","year: 1930<br />nb: 31","year: 1931<br />nb: 25","year: 1932<br />nb: 38","year: 1933<br />nb: 35","year: 1934<br />nb: 20","year: 1935<br />nb: 17","year: 1936<br />nb: 41","year: 1937<br />nb: 37","year: 1938<br />nb: 17","year: 1939<br />nb:  7","year: 1940<br />nb:  6","year: 1941<br />nb: 15","year: 1942<br />nb: 19","year: 1943<br />nb: 19","year: 1944<br />nb: 18","year: 1945<br />nb: 35","year: 1946<br />nb: 55","year: 1947<br />nb: 29","year: 1948<br />nb: 28","year: 1949<br />nb: 12","year: 1950<br />nb:  6","year: 1951<br />nb:  8","year: 1952<br />nb:  8","year: 1953<br />nb:  6","year: 1954<br />nb:  6","year: 1955<br />nb:  4","year: 1956<br />nb:  5","year: 1957<br />nb:  2","year: 1958<br />nb:  3","year: 1959<br />nb:  4","year: 1960<br />nb:  8","year: 1961<br />nb:  0","year: 1962<br />nb:  2","year: 1963<br />nb:  4","year: 1964<br />nb:  1","year: 1965<br />nb:  2","year: 1966<br />nb:  2","year: 1967<br />nb:  1","year: 1968<br />nb:  1","year: 1969<br />nb:  1","year: 1970<br />nb:  3","year: 1971<br />nb: 11","year: 1972<br />nb:  5","year: 1973<br />nb:  0","year: 1974<br />nb:  3","year: 1975<br />nb:  6","year: 1976<br />nb: 19","year: 1977<br />nb:  9","year: 1978<br />nb: 10","year: 1979<br />nb:  8","year: 1980<br />nb:  5","year: 1981<br />nb:  1","year: 1982<br />nb:  1","year: 1983<br />nb:  5","year: 1984<br />nb:  2","year: 1985<br />nb:  3","year: 1986<br />nb:  1","year: 1987<br />nb:  0","year: 1988<br />nb:  4","year: 1989<br />nb:  2","year: 1990<br />nb:  2","year: 1991<br />nb:  1","year: 1992<br />nb:  3","year: 1993<br />nb:  0","year: 1994<br />nb:  8","year: 1995<br />nb:  2","year: 1996<br />nb:  3","year: 1997<br />nb:  2","year: 1998<br />nb:  7","year: 1999<br />nb:  5","year: 2000<br />nb:  8","year: 2001<br />nb:  3","year: 2002<br />nb:  4","year: 2003<br />nb:  9","year: 2004<br />nb:  8","year: 2005<br />nb:  5","year: 2006<br />nb:  3","year: 2007<br />nb:  2","year: 2008<br />nb:  8","year: 2009<br />nb:  3","year: 2010<br />nb:  3","year: 2011<br />nb:  7","year: 2012<br />nb:  7","year: 2013<br />nb: 11","year: 2014<br />nb:  8","year: 2015<br />nb: 13","year: 2016<br />nb:  8","year: 2017<br />nb: 11","year: 2018<br />nb:  8","year: 2020<br />nb:  3","year:   NA<br />nb:  4"],"type":"scatter","mode":"lines","line":{"width":3.77952755905512,"color":"rgba(0,0,0,1)","dash":"solid"},"hoveron":"points","showlegend":false,"xaxis":"x","yaxis":"y","hoverinfo":"text","frame":null}],"layout":{"margin":{"t":95.7011207970112,"r":39.8505603985056,"b":86.8410128684101,"l":70.9007887090079},"font":{"color":"rgba(0,0,0,1)","family":"Arial Narrow","size":15.2760481527605},"title":{"text":"<b> Number of strikes in Switzerland <\/b>","font":{"color":"rgba(0,0,0,1)","family":"Arial Narrow","size":23.9103362391034},"x":0,"xref":"paper"},"xaxis":{"domain":[0,1],"automargin":true,"type":"linear","autorange":false,"range":[1922.35,2024.65],"tickmode":"array","ticktext":["1925","1950","1975","2000"],"tickvals":[1925,1950,1975,2000],"categoryorder":"array","categoryarray":["1925","1950","1975","2000"],"nticks":null,"ticks":"","tickcolor":null,"ticklen":3.81901203819012,"tickwidth":0,"showticklabels":true,"tickfont":{"color":"rgba(77,77,77,1)","family":"Arial Narrow","size":15.2760481527605},"tickangle":-0,"showline":false,"linecolor":null,"linewidth":0,"showgrid":true,"gridcolor":"rgba(204,204,204,1)","gridwidth":0.265670402656704,"zeroline":false,"anchor":"y","title":{"text":"year","font":{"color":"rgba(0,0,0,1)","family":"Arial Narrow","size":11.9551681195517}},"hoverformat":".2f"},"yaxis":{"domain":[0,1],"automargin":true,"type":"linear","autorange":false,"range":[-2.75,57.75],"tickmode":"array","ticktext":["0","20","40"],"tickvals":[0,20,40],"categoryorder":"array","categoryarray":["0","20","40"],"nticks":null,"ticks":"","tickcolor":null,"ticklen":3.81901203819012,"tickwidth":0,"showticklabels":true,"tickfont":{"color":"rgba(77,77,77,1)","family":"Arial Narrow","size":15.2760481527605},"tickangle":-0,"showline":false,"linecolor":null,"linewidth":0,"showgrid":true,"gridcolor":"rgba(204,204,204,1)","gridwidth":0.265670402656704,"zeroline":false,"anchor":"x","title":{"text":"nb","font":{"color":"rgba(0,0,0,1)","family":"Arial Narrow","size":11.9551681195517}},"hoverformat":".2f"},"shapes":[{"type":"rect","fillcolor":null,"line":{"color":null,"width":0,"linetype":[]},"yref":"paper","xref":"paper","x0":0,"x1":1,"y0":0,"y1":1}],"showlegend":false,"legend":{"bgcolor":null,"bordercolor":null,"borderwidth":0,"font":{"color":"rgba(0,0,0,1)","family":"Arial Narrow","size":12.2208385222084}},"hovermode":"closest","barmode":"relative"},"config":{"doubleClick":"reset","showSendToCloud":false},"source":"A","attrs":{"92a2200039d4":{"x":{},"y":{},"type":"scatter"},"92a26ed49db5":{"x":{},"y":{}}},"cur_data":"92a2200039d4","visdat":{"92a2200039d4":["function (y) ","x"],"92a26ed49db5":["function (y) ","x"]},"highlight":{"on":"plotly_click","persistent":false,"dynamic":false,"selectize":false,"opacityDim":0.2,"selected":{"opacity":1},"debounce":0},"shinyEvents":["plotly_hover","plotly_click","plotly_selected","plotly_relayout","plotly_brushed","plotly_brushing","plotly_clickannotation","plotly_doubleclick","plotly_deselect","plotly_afterplot","plotly_sunburstclick"],"base_url":"https://plot.ly"},"evals":[],"jsHooks":[]}</script>

``` r
strikes_ch %>%
  ggplot(aes(x=year, y=days)) +
  geom_smooth(se=F) +
  geom_line(size=1) +
  labs(title = "Lost working days because of labour conflicts in Switzerland",
       caption="Source: Swiss federal office for statistics") +
  theme_ipsum()
```

<img src="{{< blogdown/postref >}}index_files/figure-html/unnamed-chunk-1-2.png" width="672" />

``` r
strikes_ch %>%
  ggplot(aes(x=year, y=workers)) +
  geom_smooth(se=F) +
  geom_line(size=1) +
  labs(title = "Workers involved in labour conflicts in Switzerland",
       caption="Source: Swiss federal office for statistics") +
  theme_ipsum()
```

<img src="{{< blogdown/postref >}}index_files/figure-html/unnamed-chunk-1-3.png" width="672" />

``` r
strikes_ch %>%
  ggplot(aes(x=year, y=intensity)) +
  geom_smooth(se=F) +
  geom_line(size=1) +
  labs(title = "Intensity of labour conflicts in Switzerland",
       subtitle = "Lost working days multiplied by the number of workers and strikes",
       caption="Source: Swiss federal office for statistics") +
  theme_ipsum()
```

<img src="{{< blogdown/postref >}}index_files/figure-html/unnamed-chunk-1-4.png" width="672" />
