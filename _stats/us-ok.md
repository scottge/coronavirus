---
category: stats
title: "US - Oklahoma State Coronavirus (COVID-19) Live Stats"
excerpt: "Live stats of COVID-19 in US-Oklahoma. Total Cases: 4613 (+20), Deaths: 274 (+2), Recoveries: 3204(-)."
publishedDateTime: 2020-05-11T23:45:10Z
updatedDateTime: 2020-05-11T23:45:10Z
webUrl: "https://smartable.ai/apps/coronavirus/stats/us-ok/"
type: article
heat: 100

provider:
  name: Smartable AI
  domain: smartable.ai
  images:
    - url: "https://smartable.azureedge.net/media/2020/02/logo.png"
      width: 50
      height: 50

topics:
  - Coronavirus
  - Coronavirus in US

images:
  - url: "https://smartable.azureedge.net/coronavirus/sites/2/2020/us-ok.jpg"
    width: 900
    height: 564
    title: "US - Oklahoma State Coronavirus (COVID-19) Live Stats"

---
<div class="total-stats" style="text-align: center;">
    <h3>
	    <div style="font-size: 18px; font-weight: 400;">Total Confirmed Cases:</div>
	    4613 (<span class='red'>+20</span>)
    </h3>
    <h3>
	    <div style="font-size: 18px; font-weight: 400;">Total Deaths:</div>
	    274 (<span class='red'>+2</span>)
    </h3>
    <h3>
	    <div style="font-size: 18px; font-weight: 400;">Total Recovered:</div>
	    3204 (-)
    </h3>
</div>

<script type="text/javascript" src="https://www.gstatic.com/charts/loader.js"></script>

<div id="time_series_chart" style="width: 100%; height: 400px;"></div>
<script type="text/javascript">
  google.charts.load('current', {'packages':['corechart']});
  google.charts.setOnLoadCallback(drawChart);
  function drawChart() {
    var data = google.visualization.arrayToDataTable([
      ['Date', 'Total Cases', 'Total Deaths', 'Total Recovered'],
      ['1/22/2020', 0, 0, 0],['1/23/2020', 0, 0, 0],['1/24/2020', 0, 0, 0],['1/25/2020', 0, 0, 0],['1/26/2020', 0, 0, 0],['1/27/2020', 0, 0, 0],['1/28/2020', 0, 0, 0],['1/29/2020', 0, 0, 0],['1/30/2020', 0, 0, 0],['1/31/2020', 0, 0, 0],['2/1/2020', 0, 0, 0],['2/2/2020', 0, 0, 0],['2/3/2020', 0, 0, 0],['2/4/2020', 0, 0, 0],['2/5/2020', 0, 0, 0],['2/6/2020', 0, 0, 0],['2/7/2020', 0, 0, 0],['2/8/2020', 0, 0, 0],['2/9/2020', 0, 0, 0],['2/10/2020', 0, 0, 0],['2/11/2020', 0, 0, 0],['2/12/2020', 0, 0, 0],['2/13/2020', 0, 0, 0],['2/14/2020', 0, 0, 0],['2/15/2020', 0, 0, 0],['2/16/2020', 0, 0, 0],['2/17/2020', 0, 0, 0],['2/18/2020', 0, 0, 0],['2/19/2020', 0, 0, 0],['2/20/2020', 0, 0, 0],['2/21/2020', 0, 0, 0],['2/22/2020', 0, 0, 0],['2/23/2020', 0, 0, 0],['2/24/2020', 0, 0, 0],['2/25/2020', 0, 0, 0],['2/26/2020', 0, 0, 0],['2/27/2020', 0, 0, 0],['2/28/2020', 0, 0, 0],['2/29/2020', 0, 0, 0],['3/1/2020', 0, 0, 0],['3/2/2020', 0, 0, 0],['3/3/2020', 0, 0, 0],['3/4/2020', 0, 0, 0],['3/5/2020', 0, 0, 0],['3/6/2020', 0, 0, 0],['3/7/2020', 1, 0, 0],['3/8/2020', 1, 0, 0],['3/9/2020', 1, 0, 0],['3/10/2020', 2, 0, 0],['3/11/2020', 2, 0, 0],['3/12/2020', 3, 0, 0],['3/13/2020', 4, 0, 0],['3/14/2020', 4, 0, 0],['3/15/2020', 7, 0, 0],['3/16/2020', 10, 0, 0],['3/17/2020', 21, 0, 0],['3/18/2020', 31, 0, 0],['3/19/2020', 44, 1, 0],['3/20/2020', 49, 1, 0],['3/21/2020', 53, 1, 0],['3/22/2020', 68, 2, 0],['3/23/2020', 81, 2, 0],['3/24/2020', 106, 3, 0],['3/25/2020', 164, 6, 1],['3/26/2020', 248, 7, 1],['3/27/2020', 322, 8, 1],['3/28/2020', 377, 15, 1],['3/29/2020', 431, 16, 1],['3/30/2020', 483, 17, 1],['3/31/2020', 568, 23, 1],['4/1/2020', 721, 30, 1],['4/2/2020', 881, 34, 1],['4/3/2020', 990, 38, 1],['4/4/2020', 1162, 42, 1],['4/5/2020', 1254, 46, 383],['4/6/2020', 1329, 51, 409],['4/7/2020', 1474, 67, 409],['4/8/2020', 1526, 79, 409],['4/9/2020', 1686, 80, 409],['4/10/2020', 1794, 88, 409],['4/11/2020', 1868, 94, 409],['4/12/2020', 1970, 96, 409],['4/13/2020', 2069, 99, 409],['4/14/2020', 2184, 108, 1060],['4/15/2020', 2263, 123, 1060],['4/16/2020', 2357, 131, 1060],['4/17/2020', 2465, 136, 1060],['4/18/2020', 2570, 139, 1534],['4/19/2020', 2631, 140, 1575],['4/20/2020', 2712, 143, 1614],['4/21/2020', 2839, 164, 1703],['4/22/2020', 2926, 170, 1774],['4/23/2020', 3049, 179, 1886],['4/24/2020', 3228, 193, 1964],['4/25/2020', 3196, 194, 2080],['4/26/2020', 3256, 195, 2139],['4/27/2020', 3284, 197, 2167],['4/28/2020', 3413, 207, 2260],['4/29/2020', 3478, 214, 2319],['4/30/2020', 3623, 222, 2401],['5/1/2020', 3726, 227, 2401],['5/2/2020', 3854, 238, 2401],['5/3/2020', 3975, 238, 2401],['5/4/2020', 4156, 243, 2682],['5/5/2020', 4130, 247, 2682],['5/6/2020', 4206, 253, 2909],['5/7/2020', 4333, 260, 2985],['5/8/2020', 4428, 266, 3064],['5/9/2020', 4495, 270, 3064],['5/10/2020', 4593, 272, 3204],['5/11/2020', 4613, 274, 3204],
    ]);
    var options = {
      curveType: 'none',
      chartArea: {'width': '80%', 'height': '80%'},
      legend: { position: 'top' },
      lineWidth: 5,
      colors: ['#f60109', '#444444', '#81B71F']
    };
    var chart = new google.visualization.LineChart(document.getElementById('time_series_chart'));
    chart.draw(data, options);
  }
</script>

<div id="geo_chart" style="width: 100%; height: 500px;"></div>
<script type="text/javascript">
  google.charts.load('current', {
    'packages':['geochart'],
    'mapsApiKey': 'AIzaSyDk1HhVhLaveyKrUhhHZ5YwzIpEcbdal6U'
  });
  google.charts.setOnLoadCallback(drawRegionsMap);
  function drawRegionsMap() {
    var data = google.visualization.arrayToDataTable([
      ['LATITUDE', 'LONGITUDE', 'DESCRIPTION', 'Total Cases', 'Total Deaths'],
      [35.9845, -94.6036, "Adair", 74, 3],[35.2974, -99.6284, "Beckham", 6, 0],[33.9899, -96.2304, "Bryan", 12, 1],[34.9362, -98.1363, "Caddo", 108, 9],[35.6014, -98.1247, "Canadian", 111, 3],[34.4779, -97.4661, "Carter", 6, 1],[35.9642, -94.8912, "Cherokee", 30, 1],[34.0244, -95.2972, "Choctaw", 3, 0],[35.2335, -97.3471, "Cleveland", 456, 32],[34.6197, -98.7522, "Comanche", 124, 2],[34.1954, -98.5881, "Cotton", 5, 2],[36.8739, -95.0947, "Craig", 13, 0],[36.0821, -96.5819, "Creek", 82, 7],[35.5384, -98.6872, "Custer", 11, 0],[36.3013, -94.9979, "Delaware", 92, 16],[36.4061, -97.8701, "Garfield", 22, 1],[34.8392, -97.6105, "Garvin", 15, 1],[34.9227, -97.7763, "Grady", 45, 2],[34.6268, -99.1373, "Jackson", 19, 0],[36.6788, -97.3281, "Kay", 48, 7],[34.9508, -95.0814, "Latimer", 5, 1],[34.9699, -94.7205, "Le Flore", 13, 1],[35.895, -96.8702, "Lincoln", 17, 2],[35.9324, -97.263, "Logan", 18, 1],[33.7935, -97.1426, "Love", 3, 0],[36.477, -95.0195, "Mayes", 24, 4],[35.2404, -97.5998, "McClain", 85, 2],[35.5559, -95.6525, "Muskogee", 29, 6],[36.2747, -97.4551, "Noble", 7, 0],[36.9146, -95.8047, "Nowata", 22, 0],[35.5706, -97.5567, "Oklahoma", 945, 43],[35.7769, -96.0279, "Okmulgee", 17, 0],[36.5698, -96.708, "Osage", 88, 8],[36.9316, -94.8706, "Ottawa", 34, 1],[36.1857, -96.4904, "Pawnee", 29, 2],[36.2313, -96.9302, "Payne", 45, 1],[34.8353, -95.8357, "Pittsburg", 39, 3],[34.8659, -96.6678, "Pontotoc", 10, 2],[35.3525, -96.9647, "Pottawatomie", 54, 4],[36.1832, -95.7663, "Rogers", 70, 5],[35.2346, -96.65, "Seminole", 21, 2],[35.4578, -94.4984, "Sequoyah", 14, 3],[34.616, -97.8207, "Stephens", 22, 1],[36.861, -101.2161, "Texas", 403, 3],[36.1593, -95.941, "Tulsa", 700, 36],[35.9641, -95.3791, "Wagoner", 129, 17],[36.9008, -95.9254, "Washington", 296, 29],[35.0514, -99.5099, "Greer", 65, 6],[34.2356, -96.217, "Atoka", 1, 0],[35.9814, -97.9106, "Kingfisher", 8, 0],[36.4379, -99.2045, "Woodward", 2, 0],[34.8662, -98.8759, "Kiowa", 7, 0],[36.9248, -97.6571, "Grant", 2, 0],[36.3882, -98.1779, "Major", 5, 1],[34.0043, -95.0895, "McCurtain", 8, 0],[35.156, -99.0594, "Washita", 1, 0],[34.3413, -98.8706, "Tillman", 19, 0],[35.2043, -95.8893, "McIntosh", 5, 0],[34.0826, -97.9788, "Jefferson", 3, 0],[36.8517, -100.0552, "Beaver", 20, 0],[36.1548, -98.9296, "Dewey", 2, 0],[34.0867, -96.7742, "Marshall", 2, 0],[35.4903, -96.4793, "Okfuskee", 1, 0],[36.5791, -98.4578, "Alfalfa", 1, 0],[34.2407, -96.7566, "Johnston", 4, 0],[35.2569, -94.9225, "Haskell", 5, 0],[36.5849, -98.8784, "Woods", 3, 0],[36.6174, -99.7484, "Harper", 1, 0],[34.4977, -96.9899, "Murray", 2, 0],[36.5633, -102.795, "Cimarron", 1, 0],[34.4820384, -95.3102505, "Pushmataha", 1, 0],[35.8825489, -98.3964938, "Blaine", 3, 0],
    ]);
    var options = {
      backgroundColor: {fill:'transparent',stroke:'#FFF' ,strokeWidth:0 }, 
      displayMode: 'markers',
      region: 'US-OK', 
      resolution: 'metros',
      colorAxis: {colors: ['#F27D81', '#f60109']},
      sizeAxis: {minSize:3,  maxSize:12},
    };
    var chart = new google.visualization.GeoChart(document.getElementById('geo_chart'));
    chart.draw(data, options);
  };
</script>

<div id="geo_table"></div>
<script type="text/javascript">
  google.charts.load('current', {'packages':['table']});
  google.charts.setOnLoadCallback(drawTable);
  function drawTable() {
    var data = new google.visualization.DataTable();
    data.addColumn('string', 'Location');
    data.addColumn('number', 'Total Cases');
    data.addColumn('number', 'New Cases');
    data.addColumn('number', 'Active Cases');
    data.addColumn('number', 'Total Deaths');
    data.addColumn('number', 'New Deaths');
    data.addColumn('number', 'Total Recovered');
    data.addRows([
      [{v:"Adair", f:"Adair"}, 74, 0, 39, 3, 0, 32],[{v:"Beckham", f:"Beckham"}, 6, 0, 5, 0, 0, 1],[{v:"Bryan", f:"Bryan"}, 12, 0, 8, 1, 0, 3],[{v:"Caddo", f:"Caddo"}, 108, 0, 87, 9, 0, 12],[{v:"Canadian", f:"Canadian"}, 111, 0, 45, 3, 0, 63],[{v:"Carter", f:"Carter"}, 6, 0, 4, 1, 0, 1],[{v:"Cherokee", f:"Cherokee"}, 30, 0, 10, 1, 0, 19],[{v:"Choctaw", f:"Choctaw"}, 3, 0, 2, 0, 0, 1],[{v:"Cleveland", f:"Cleveland"}, 456, 0, 171, 32, 0, 253],[{v:"Comanche", f:"Comanche"}, 124, 0, 73, 2, 0, 49],[{v:"Cotton", f:"Cotton"}, 5, 0, 0, 2, 0, 3],[{v:"Craig", f:"Craig"}, 13, 0, 8, 0, 0, 5],[{v:"Creek", f:"Creek"}, 82, 0, 23, 7, 0, 52],[{v:"Custer", f:"Custer"}, 11, 0, 3, 0, 0, 8],[{v:"Delaware", f:"Delaware"}, 92, 0, 37, 16, 0, 39],[{v:"Garfield", f:"Garfield"}, 22, 0, 14, 1, 0, 7],[{v:"Garvin", f:"Garvin"}, 15, 0, 4, 1, 0, 10],[{v:"Grady", f:"Grady"}, 45, 0, 26, 2, 0, 17],[{v:"Jackson", f:"Jackson"}, 19, 0, 12, 0, 0, 7],[{v:"Kay", f:"Kay"}, 48, 0, 4, 7, 0, 37],[{v:"Latimer", f:"Latimer"}, 5, 0, 2, 1, 0, 2],[{v:"Le Flore", f:"Le Flore"}, 13, 0, 8, 1, 0, 4],[{v:"Lincoln", f:"Lincoln"}, 17, 0, 7, 2, 0, 8],[{v:"Logan", f:"Logan"}, 18, 0, 8, 1, 0, 9],[{v:"Love", f:"Love"}, 3, 0, 2, 0, 0, 1],[{v:"Mayes", f:"Mayes"}, 24, 0, 7, 4, 0, 13],[{v:"McClain", f:"McClain"}, 85, 0, 83, 2, 0, 0],[{v:"Muskogee", f:"Muskogee"}, 29, 0, 3, 6, 0, 20],[{v:"Noble", f:"Noble"}, 7, 0, 2, 0, 0, 5],[{v:"Nowata", f:"Nowata"}, 22, 0, 13, 0, 0, 9],[{v:"Oklahoma", f:"Oklahoma"}, 945, 0, 446, 43, 0, 456],[{v:"Okmulgee", f:"Okmulgee"}, 17, 0, 3, 0, 0, 14],[{v:"Osage", f:"Osage"}, 88, 0, 41, 8, 0, 39],[{v:"Ottawa", f:"Ottawa"}, 34, 0, 16, 1, 0, 17],[{v:"Pawnee", f:"Pawnee"}, 29, 0, 7, 2, 0, 20],[{v:"Payne", f:"Payne"}, 45, 0, 15, 1, 0, 29],[{v:"Pittsburg", f:"Pittsburg"}, 39, 0, 25, 3, 0, 11],[{v:"Pontotoc", f:"Pontotoc"}, 10, 0, 0, 2, 0, 8],[{v:"Pottawatomie", f:"Pottawatomie"}, 54, 0, 23, 4, 0, 27],[{v:"Rogers", f:"Rogers"}, 70, 0, 41, 5, 0, 24],[{v:"Seminole", f:"Seminole"}, 21, 0, 15, 2, 0, 4],[{v:"Sequoyah", f:"Sequoyah"}, 14, 0, 4, 3, 0, 7],[{v:"Stephens", f:"Stephens"}, 22, 0, 6, 1, 0, 15],[{v:"Texas", f:"Texas"}, 403, 0, 394, 3, 0, 6],[{v:"Tulsa", f:"Tulsa"}, 700, 0, 323, 36, 0, 341],[{v:"Wagoner", f:"Wagoner"}, 129, 0, 54, 17, 0, 58],[{v:"Washington", f:"Washington"}, 296, 0, 158, 29, 0, 109],[{v:"Greer", f:"Greer"}, 65, 0, 16, 6, 0, 43],[{v:"Atoka", f:"Atoka"}, 1, 0, 0, 0, 0, 1],[{v:"Kingfisher", f:"Kingfisher"}, 8, 0, 2, 0, 0, 6],[{v:"Woodward", f:"Woodward"}, 2, 0, 1, 0, 0, 1],[{v:"Kiowa", f:"Kiowa"}, 7, 0, 5, 0, 0, 2],[{v:"Grant", f:"Grant"}, 2, 0, 0, 0, 0, 2],[{v:"Major", f:"Major"}, 5, 0, 3, 1, 0, 1],[{v:"McCurtain", f:"McCurtain"}, 8, 0, 8, 0, 0, 0],[{v:"Washita", f:"Washita"}, 1, 0, 1, 0, 0, 0],[{v:"Tillman", f:"Tillman"}, 19, 0, 17, 0, 0, 2],[{v:"McIntosh", f:"McIntosh"}, 5, 0, 5, 0, 0, 0],[{v:"Jefferson", f:"Jefferson"}, 3, 0, 2, 0, 0, 1],[{v:"Beaver", f:"Beaver"}, 20, 0, 20, 0, 0, 0],[{v:"Dewey", f:"Dewey"}, 2, 0, 1, 0, 0, 1],[{v:"Marshall", f:"Marshall"}, 2, 0, 1, 0, 0, 1],[{v:"Okfuskee", f:"Okfuskee"}, 1, 0, 0, 0, 0, 1],[{v:"Alfalfa", f:"Alfalfa"}, 1, 0, 0, 0, 0, 1],[{v:"Johnston", f:"Johnston"}, 4, 0, 3, 0, 0, 1],[{v:"Haskell", f:"Haskell"}, 5, 0, 4, 0, 0, 1],[{v:"Woods", f:"Woods"}, 3, 0, 3, 0, 0, 0],[{v:"Harper", f:"Harper"}, 1, 0, 1, 0, 0, 0],[{v:"Murray", f:"Murray"}, 2, 0, 1, 0, 0, 1],[{v:"Cimarron", f:"Cimarron"}, 1, 0, 1, 0, 0, 0],[{v:"Pushmataha", f:"Pushmataha"}, 1, 0, 1, 0, 0, 0],[{v:"Blaine", f:"Blaine"}, 3, 0, 3, 0, 0, 0],
    ]);
    data.setProperty(0, 0, 'style', 'min-width:100px');
    var table = new google.visualization.Table(document.getElementById('geo_table'));
    table.draw(data, {allowHtml: true, sortColumn: 2, sortAscending: false, width: '660px', height: '100%'});
  }
</script>

<span style="font-size: 13px">All COVID-19 data displayed on the page is available through our FREE <a href="https://developer.smartable.ai">API program</a>. This US - Oklahoma State Coronavirus (COVID-19) Live Stats is refreshed every hour using credible data sources, including the country/state's official government website, <a href="https://en.wikipedia.org/wiki/2019%E2%80%9320_coronavirus_pandemic" target="_blank">data available on wikipedia pages</a>, latest news reports, <a href="https://systems.jhu.edu/research/public-health/ncov/" target="_blank">Johns Hopkins University CSSE 2019-nCoV Dashboard</a>, <a href="https://www.who.int/emergencies/diseases/novel-coronavirus-2019/situation-reports" target="_blank">WHO Situation Reports</a>, <a href="https://www.cdc.gov/coronavirus/2019-ncov/index.html" target="_blank">CDC Situation Updates</a>, and <a href="https://ncov.dxy.cn/ncovh5/view/pneumonia" target="_blank">DXY.cn</a>.</span>

<h2 id="news" class="center" style="margin-top: 60px; font-size: 25px;">Local Government Help Information</h2>
<div class="info center">
<a href="https://www.ok.gov/health/Prevention_and_Preparedness/Acute_Disease_Service/Disease_Information/Coronavirus_Disease_2019/index.html" target="_blank">Oklahoma State Department of Health</a> 877-215-8336
</div>
<h2 id="news" class="center" style="margin-top: 60px; font-size: 25px;">Trending Coronavirus News in US-Oklahoma</h2>
<div class="row">
<div class="col-md-6 col-sm-12">
  <div class="content-card">
	<a href="https://www.nbcnews.com/video/three-mcdonald-s-employees-wounded-in-shooting-over-covid-19-restrictions-83135045778"><div class="card-image" style="background-image: url(https://media13.s-nbcnews.com/j/MSNBC/Components/Video/202005/NC_mcdonaldsshooting0507_1920x1080.nbcnews-fp-1200-630.jpg)"></div></a>
	<div class="content">
		<div class="card-title"><a href="https://www.nbcnews.com/video/three-mcdonald-s-employees-wounded-in-shooting-over-covid-19-restrictions-83135045778">Three McDonald's employees wounded in Oklahoma shooting over COVID-19 restrictions</a></div>
		<div class="card-excerpt">Three employees at an Oklahoma City McDonald's were wounded Wednesday when a woman became angry and fired shots after being told the dining room was closed due to the coronavirus pandemic. KFOR's Taylor Adams reports.</div>
		<div class="card-meta">
			<span class="card-provider">NBC News</span> • <span class="card-date">5/7/2020</span>
		</div>
	</div>
  </div>
</div>

</div>

