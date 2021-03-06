---
category: stats
title: "US - Louisiana State Coronavirus (COVID-19) Live Stats"
excerpt: "Live stats of COVID-19 in US-Louisiana. Total Cases: 32050 (+235), Deaths: 2347 (+39), Recoveries: 20316(-)."
publishedDateTime: 2020-05-12T23:45:15Z
updatedDateTime: 2020-05-12T23:45:15Z
webUrl: "https://smartable.ai/apps/coronavirus/stats/us-la/"
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
  - url: "https://smartable.azureedge.net/coronavirus/sites/2/2020/us-la.jpg"
    width: 900
    height: 564
    title: "US - Louisiana State Coronavirus (COVID-19) Live Stats"

---
<div class="total-stats" style="text-align: center;">
    <h3>
	    <div style="font-size: 18px; font-weight: 400;">Total Confirmed Cases:</div>
	    32050 (<span class='red'>+235</span>)
    </h3>
    <h3>
	    <div style="font-size: 18px; font-weight: 400;">Total Deaths:</div>
	    2347 (<span class='red'>+39</span>)
    </h3>
    <h3>
	    <div style="font-size: 18px; font-weight: 400;">Total Recovered:</div>
	    20316 (-)
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
      ['1/22/2020', 0, 0, 0],['1/23/2020', 0, 0, 0],['1/24/2020', 0, 0, 0],['1/25/2020', 0, 0, 0],['1/26/2020', 0, 0, 0],['1/27/2020', 0, 0, 0],['1/28/2020', 0, 0, 0],['1/29/2020', 0, 0, 0],['1/30/2020', 0, 0, 0],['1/31/2020', 0, 0, 0],['2/1/2020', 0, 0, 0],['2/2/2020', 0, 0, 0],['2/3/2020', 0, 0, 0],['2/4/2020', 0, 0, 0],['2/5/2020', 0, 0, 0],['2/6/2020', 0, 0, 0],['2/7/2020', 0, 0, 0],['2/8/2020', 0, 0, 0],['2/9/2020', 0, 0, 0],['2/10/2020', 0, 0, 0],['2/11/2020', 0, 0, 0],['2/12/2020', 0, 0, 0],['2/13/2020', 0, 0, 0],['2/14/2020', 0, 0, 0],['2/15/2020', 0, 0, 0],['2/16/2020', 0, 0, 0],['2/17/2020', 0, 0, 0],['2/18/2020', 0, 0, 0],['2/19/2020', 0, 0, 0],['2/20/2020', 0, 0, 0],['2/21/2020', 0, 0, 0],['2/22/2020', 0, 0, 0],['2/23/2020', 0, 0, 0],['2/24/2020', 0, 0, 0],['2/25/2020', 0, 0, 0],['2/26/2020', 0, 0, 0],['2/27/2020', 0, 0, 0],['2/28/2020', 0, 0, 0],['2/29/2020', 0, 0, 0],['3/1/2020', 0, 0, 0],['3/2/2020', 0, 0, 0],['3/3/2020', 0, 0, 0],['3/4/2020', 0, 0, 0],['3/5/2020', 0, 0, 0],['3/6/2020', 0, 0, 0],['3/7/2020', 0, 0, 0],['3/8/2020', 0, 0, 0],['3/9/2020', 1, 0, 0],['3/10/2020', 1, 0, 0],['3/11/2020', 6, 0, 0],['3/12/2020', 22, 0, 0],['3/13/2020', 35, 0, 0],['3/14/2020', 78, 1, 0],['3/15/2020', 103, 2, 0],['3/16/2020', 157, 3, 0],['3/17/2020', 221, 4, 0],['3/18/2020', 278, 7, 0],['3/19/2020', 278, 7, 0],['3/20/2020', 537, 14, 0],['3/21/2020', 763, 20, 0],['3/22/2020', 837, 20, 0],['3/23/2020', 1172, 35, 0],['3/24/2020', 1388, 46, 0],['3/25/2020', 1795, 65, 0],['3/26/2020', 2305, 83, 0],['3/27/2020', 2746, 119, 0],['3/28/2020', 3315, 137, 0],['3/29/2020', 3540, 151, 0],['3/30/2020', 4025, 185, 0],['3/31/2020', 5238, 239, 0],['4/1/2020', 6425, 273, 0],['4/2/2020', 9122, 310, 0],['4/3/2020', 10210, 370, 0],['4/4/2020', 12496, 409, 0],['4/5/2020', 13010, 477, 0],['4/6/2020', 14867, 512, 0],['4/7/2020', 16284, 582, 0],['4/8/2020', 17030, 652, 0],['4/9/2020', 18283, 702, 0],['4/10/2020', 19253, 755, 0],['4/11/2020', 20014, 806, 0],['4/12/2020', 20595, 840, 0],['4/13/2020', 21016, 884, 0],['4/14/2020', 21518, 1013, 0],['4/15/2020', 21946, 1103, 0],['4/16/2020', 22517, 1156, 0],['4/17/2020', 23118, 1213, 0],['4/18/2020', 23580, 1267, 0],['4/19/2020', 23928, 1296, 0],['4/20/2020', 24523, 1328, 0],['4/21/2020', 24854, 1405, 0],['4/22/2020', 25258, 1473, 0],['4/23/2020', 25739, 1599, 0],['4/24/2020', 26159, 1661, 14927],['4/25/2020', 26512, 1703, 14927],['4/26/2020', 26773, 1729, 14927],['4/27/2020', 27068, 1740, 17303],['4/28/2020', 27286, 1801, 17303],['4/29/2020', 27660, 1845, 17303],['4/30/2020', 28001, 1905, 17303],['5/1/2020', 28558, 1944, 17303],['5/2/2020', 29140, 1993, 17303],['5/3/2020', 29340, 2012, 17303],['5/4/2020', 29701, 2065, 17303],['5/5/2020', 29996, 2115, 20316],['5/6/2020', 30399, 2167, 20316],['5/7/2020', 30652, 2208, 20316],['5/8/2020', 30855, 2227, 20316],['5/9/2020', 31417, 2267, 20316],['5/10/2020', 31600, 2286, 20316],['5/11/2020', 31815, 2308, 20316],['5/12/2020', 32050, 2347, 20316],
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
      [30.4037, -92.2145, "Acadia", 152, 11],[30.867, -92.7986, "Allen", 90, 9],[30.1828, -90.8674, "Ascension", 695, 48],[29.9886, -91.0555, "Assumption", 228, 11],[30.954, -92.1884, "Avoyelles", 75, 7],[30.5289, -93.4391, "Beauregard", 46, 4],[32.3261, -93.2837, "Bienville", 78, 20],[32.5606, -93.5625, "Bossier", 312, 21],[32.6091, -93.8841, "Caddo", 1765, 133],[30.2393, -93.0128, "Calcasieu", 496, 38],[32.0288, -92.1408, "Caldwell", 48, 0],[31.8492, -91.6599, "Catahoula", 85, 3],[32.793, -93.0582, "Claiborne", 59, 9],[32.0181, -93.7237, "De Soto", 215, 14],[30.5467, -91.1225, "East Baton Rouge", 2398, 188],[32.8133, -91.1826, "East Carroll", 23, 0],[30.9682, -91.1125, "East Feliciana", 136, 21],[30.5696, -92.3169, "Evangeline", 67, 1],[32.1651, -91.721, "Franklin", 208, 4],[31.43, -92.4829, "Grant", 18, 0],[30.0049, -91.8202, "Iberia", 286, 26],[30.161, -91.1495, "Iberville", 501, 36],[32.2719, -92.7303, "Jackson", 67, 5],[29.6499, -90.1121, "Jefferson", 6755, 402],[30.2355, -92.7481, "Jefferson Davis", 68, 6],[30.3126, -92.0387, "Lafayette", 508, 22],[29.5164, -90.3291, "Lafourche", 713, 59],[32.5329, -92.6361, "Lincoln", 107, 11],[30.4953, -90.7467, "Livingston", 281, 24],[32.4067, -91.1915, "Madison", 13, 0],[32.7749, -91.9058, "Morehouse", 65, 5],[31.6547, -93.1999, "Natchitoches", 100, 9],[29.9511, -90.0715, "Orleans", 6693, 470],[32.4883, -92.1619, "Ouachita", 842, 25],[29.3443, -89.4683, "Plaquemines", 190, 17],[30.6824, -91.4248, "Pointe Coupee", 136, 17],[31.3414, -92.4096, "Rapides", 370, 13],[32.0256, -93.3406, "Red River", 36, 6],[32.4902, -91.8651, "Richland", 103, 1],[31.6118, -93.4077, "Sabine", 19, 1],[29.8625, -89.8877, "St. Bernard", 514, 20],[29.9986, -90.4036, "St. Charles", 595, 43],[30.0917, -90.8844, "St. James", 257, 20],[29.9205, -90.6458, "St. John the Baptist", 801, 77],[30.528, -92.0851, "St. Landry", 215, 50],[30.3368, -91.8476, "St. Martin", 260, 21],[29.8113, -91.6705, "St. Mary", 250, 26],[30.3687, -89.7495, "St. Tammany", 1463, 136],[30.7646, -90.5114, "Tangipahoa", 670, 28],[29.3864, -90.7081, "Terrebonne", 528, 39],[33.0073, -92.7224, "Union", 169, 10],[29.975, -92.1266, "Vermilion", 41, 2],[30.9344, -92.9268, "Vernon", 18, 2],[30.8479, -90.1459, "Washington", 342, 26],[32.525, -93.4118, "Webster", 100, 4],[30.4456, -91.2098, "West Baton Rouge", 123, 29],[30.7851, -91.3787, "West Feliciana", 184, 6],[31.924, -92.6425, "Winn", 52, 2],[31.713, -91.4453, "Concordia", 43, 5],[30.6823, -90.6545, "St. Helena", 35, 1],[32.6038, -91.4814, "West Carroll", 5, 0],[29.9717, -93.3947, "Cameron", 3, 0],[32.0723, -91.239, "Tensas", 6, 0],[31.7002461, -92.2236667, "La Salle", 33, 0],[31.7002461, -92.2236667, "LaSalle", 33, 0],
    ]);
    var options = {
      backgroundColor: {fill:'transparent',stroke:'#FFF' ,strokeWidth:0 }, 
      displayMode: 'markers',
      region: 'US-LA', 
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
      [{v:"Acadia", f:"Acadia"}, 152, 0, 141, 11, 0, 0],[{v:"Allen", f:"Allen"}, 90, 0, 81, 9, 0, 0],[{v:"Ascension", f:"Ascension"}, 695, 0, 647, 48, 0, 0],[{v:"Assumption", f:"Assumption"}, 228, 0, 217, 11, 0, 0],[{v:"Avoyelles", f:"Avoyelles"}, 75, 0, 68, 7, 0, 0],[{v:"Beauregard", f:"Beauregard"}, 46, 0, 42, 4, 0, 0],[{v:"Bienville", f:"Bienville"}, 78, 0, 58, 20, 2, 0],[{v:"Bossier", f:"Bossier"}, 312, 0, 291, 21, 0, 0],[{v:"Caddo", f:"Caddo"}, 1765, 0, 1632, 133, 0, 0],[{v:"Calcasieu", f:"Calcasieu"}, 496, 0, 458, 38, 0, 0],[{v:"Caldwell", f:"Caldwell"}, 48, 0, 48, 0, 0, 0],[{v:"Catahoula", f:"Catahoula"}, 85, 0, 82, 3, 0, 0],[{v:"Claiborne", f:"Claiborne"}, 59, 0, 50, 9, 0, 0],[{v:"De Soto", f:"De Soto"}, 215, 0, 201, 14, 0, 0],[{v:"East Baton Rouge", f:"East Baton Rouge"}, 2398, 0, 2210, 188, 0, 0],[{v:"East Carroll", f:"East Carroll"}, 23, 0, 23, 0, 0, 0],[{v:"East Feliciana", f:"East Feliciana"}, 136, 0, 115, 21, 0, 0],[{v:"Evangeline", f:"Evangeline"}, 67, 0, 66, 1, 0, 0],[{v:"Franklin", f:"Franklin"}, 208, 0, 204, 4, 0, 0],[{v:"Grant", f:"Grant"}, 18, 0, 18, 0, 0, 0],[{v:"Iberia", f:"Iberia"}, 286, 0, 260, 26, 0, 0],[{v:"Iberville", f:"Iberville"}, 501, 0, 465, 36, 0, 0],[{v:"Jackson", f:"Jackson"}, 67, 0, 62, 5, 0, 0],[{v:"Jefferson", f:"Jefferson"}, 6755, 0, 6353, 402, 0, 0],[{v:"Jefferson Davis", f:"Jefferson Davis"}, 68, 0, 62, 6, 0, 0],[{v:"Lafayette", f:"Lafayette"}, 508, 0, 486, 22, 0, 0],[{v:"Lafourche", f:"Lafourche"}, 713, 0, 654, 59, 0, 0],[{v:"Lincoln", f:"Lincoln"}, 107, 0, 96, 11, 0, 0],[{v:"Livingston", f:"Livingston"}, 281, 0, 257, 24, 0, 0],[{v:"Madison", f:"Madison"}, 13, 0, 13, 0, 0, 0],[{v:"Morehouse", f:"Morehouse"}, 65, 0, 60, 5, 0, 0],[{v:"Natchitoches", f:"Natchitoches"}, 100, 0, 91, 9, 0, 0],[{v:"Orleans", f:"Orleans"}, 6693, 0, 6223, 470, 0, 0],[{v:"Ouachita", f:"Ouachita"}, 842, 0, 817, 25, 0, 0],[{v:"Plaquemines", f:"Plaquemines"}, 190, 0, 173, 17, 0, 0],[{v:"Pointe Coupee", f:"Pointe Coupee"}, 136, 0, 119, 17, 0, 0],[{v:"Rapides", f:"Rapides"}, 370, 0, 357, 13, 0, 0],[{v:"Red River", f:"Red River"}, 36, 0, 30, 6, 0, 0],[{v:"Richland", f:"Richland"}, 103, 0, 102, 1, 0, 0],[{v:"Sabine", f:"Sabine"}, 19, 0, 18, 1, 0, 0],[{v:"St. Bernard", f:"St. Bernard"}, 514, 0, 494, 20, 0, 0],[{v:"St. Charles", f:"St. Charles"}, 595, 0, 552, 43, 0, 0],[{v:"St. James", f:"St. James"}, 257, 0, 237, 20, 0, 0],[{v:"St. John the Baptist", f:"St. John the Baptist"}, 801, 0, 724, 77, 1, 0],[{v:"St. Landry", f:"St. Landry"}, 215, 0, 165, 50, 0, 0],[{v:"St. Martin", f:"St. Martin"}, 260, 0, 239, 21, 0, 0],[{v:"St. Mary", f:"St. Mary"}, 250, 0, 224, 26, 0, 0],[{v:"St. Tammany", f:"St. Tammany"}, 1463, 0, 1327, 136, 0, 0],[{v:"Tangipahoa", f:"Tangipahoa"}, 670, 0, 642, 28, 0, 0],[{v:"Terrebonne", f:"Terrebonne"}, 528, 0, 489, 39, 0, 0],[{v:"Union", f:"Union"}, 169, 0, 159, 10, 0, 0],[{v:"Vermilion", f:"Vermilion"}, 41, 0, 39, 2, 0, 0],[{v:"Vernon", f:"Vernon"}, 18, 0, 16, 2, 0, 0],[{v:"Washington", f:"Washington"}, 342, 0, 316, 26, 0, 0],[{v:"Webster", f:"Webster"}, 100, 0, 96, 4, 0, 0],[{v:"West Baton Rouge", f:"West Baton Rouge"}, 123, 0, 94, 29, 3, 0],[{v:"West Feliciana", f:"West Feliciana"}, 184, 0, 178, 6, 0, 0],[{v:"Winn", f:"Winn"}, 52, 0, 50, 2, 0, 0],[{v:"Concordia", f:"Concordia"}, 43, 0, 38, 5, 0, 0],[{v:"St. Helena", f:"St. Helena"}, 35, 0, 34, 1, 0, 0],[{v:"West Carroll", f:"West Carroll"}, 5, 0, 5, 0, 0, 0],[{v:"Cameron", f:"Cameron"}, 3, 0, 3, 0, 0, 0],[{v:"Tensas", f:"Tensas"}, 6, 0, 6, 0, 0, 0],[{v:"La Salle", f:"La Salle"}, 33, 0, 33, 0, 0, 0],[{v:"LaSalle", f:"LaSalle"}, 33, 0, 33, 0, 0, 0],
    ]);
    data.setProperty(0, 0, 'style', 'min-width:100px');
    var table = new google.visualization.Table(document.getElementById('geo_table'));
    table.draw(data, {allowHtml: true, sortColumn: 2, sortAscending: false, width: '660px', height: '100%'});
  }
</script>

<span style="font-size: 13px">All COVID-19 data displayed on the page is available through our FREE <a href="https://developer.smartable.ai">API program</a>. This US - Louisiana State Coronavirus (COVID-19) Live Stats is refreshed every hour using credible data sources, including the country/state's official government website, <a href="https://en.wikipedia.org/wiki/2019%E2%80%9320_coronavirus_pandemic" target="_blank">data available on wikipedia pages</a>, latest news reports, <a href="https://systems.jhu.edu/research/public-health/ncov/" target="_blank">Johns Hopkins University CSSE 2019-nCoV Dashboard</a>, <a href="https://www.who.int/emergencies/diseases/novel-coronavirus-2019/situation-reports" target="_blank">WHO Situation Reports</a>, <a href="https://www.cdc.gov/coronavirus/2019-ncov/index.html" target="_blank">CDC Situation Updates</a>, and <a href="https://ncov.dxy.cn/ncovh5/view/pneumonia" target="_blank">DXY.cn</a>.</span>

<h2 id="news" class="center" style="margin-top: 60px; font-size: 25px;">Local Government Help Information</h2>
<div class="info center">
<a href="http://ldh.la.gov/index.cfm/page/3835" target="_blank">Louisiana Department of Health</a> 855-523-2652
</div>
<h2 id="news" class="center" style="margin-top: 60px; font-size: 25px;">Trending Coronavirus News in US-Louisiana</h2>
<div class="row">
<div class="col-md-6 col-sm-12">
  <div class="content-card">
	<a href="https://www.foxnews.com/us/louisiana-sheriff-sues-china-coronavirus"><div class="card-image" style="background-image: url(https://cf-images.us-east-1.prod.boltdns.net/v1/static/694940094001/f33c1360-73c1-4973-b722-e3ab9b105a85/a7aacdd9-9f68-438f-b8d7-63cdb0737d8e/1280x720/match/image.jpg)"></div></a>
	<div class="content">
		<div class="card-title"><a href="https://www.foxnews.com/us/louisiana-sheriff-sues-china-coronavirus">Louisiana sheriff sues China for 'economic damages' caused by coronavirus</a></div>
		<div class="card-excerpt">Tangipahoa Parish Sheriff Daniel Edwards filed a class-action lawsuit in the state of  Friday against the People’s Republic of China on the basis of “economic damages” caused by the novel coronavirus.</div>
		<div class="card-meta">
			<span class="card-provider">Fox News</span> • <span class="card-date">5/8/2020</span>
		</div>
	</div>
  </div>
</div>

</div>

