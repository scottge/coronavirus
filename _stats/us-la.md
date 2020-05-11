---
category: stats
title: "US - Louisiana State Coronavirus (COVID-19) Live Stats"
excerpt: "Live stats of COVID-19 in US-Louisiana. Total Cases: 31417 (+562), Deaths: 2267 (+40), Recoveries: 20316(-)."
publishedDateTime: 2020-05-10T05:45:41Z
updatedDateTime: 2020-05-10T05:45:41Z
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
	    31417 (<span class='red'>+562</span>)
    </h3>
    <h3>
	    <div style="font-size: 18px; font-weight: 400;">Total Deaths:</div>
	    2267 (<span class='red'>+40</span>)
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
      ['1/22/2020', 0, 0, 0],['1/23/2020', 0, 0, 0],['1/24/2020', 0, 0, 0],['1/25/2020', 0, 0, 0],['1/26/2020', 0, 0, 0],['1/27/2020', 0, 0, 0],['1/28/2020', 0, 0, 0],['1/29/2020', 0, 0, 0],['1/30/2020', 0, 0, 0],['1/31/2020', 0, 0, 0],['2/1/2020', 0, 0, 0],['2/2/2020', 0, 0, 0],['2/3/2020', 0, 0, 0],['2/4/2020', 0, 0, 0],['2/5/2020', 0, 0, 0],['2/6/2020', 0, 0, 0],['2/7/2020', 0, 0, 0],['2/8/2020', 0, 0, 0],['2/9/2020', 0, 0, 0],['2/10/2020', 0, 0, 0],['2/11/2020', 0, 0, 0],['2/12/2020', 0, 0, 0],['2/13/2020', 0, 0, 0],['2/14/2020', 0, 0, 0],['2/15/2020', 0, 0, 0],['2/16/2020', 0, 0, 0],['2/17/2020', 0, 0, 0],['2/18/2020', 0, 0, 0],['2/19/2020', 0, 0, 0],['2/20/2020', 0, 0, 0],['2/21/2020', 0, 0, 0],['2/22/2020', 0, 0, 0],['2/23/2020', 0, 0, 0],['2/24/2020', 0, 0, 0],['2/25/2020', 0, 0, 0],['2/26/2020', 0, 0, 0],['2/27/2020', 0, 0, 0],['2/28/2020', 0, 0, 0],['2/29/2020', 0, 0, 0],['3/1/2020', 0, 0, 0],['3/2/2020', 0, 0, 0],['3/3/2020', 0, 0, 0],['3/4/2020', 0, 0, 0],['3/5/2020', 0, 0, 0],['3/6/2020', 0, 0, 0],['3/7/2020', 0, 0, 0],['3/8/2020', 0, 0, 0],['3/9/2020', 1, 0, 0],['3/10/2020', 1, 0, 0],['3/11/2020', 6, 0, 0],['3/12/2020', 22, 0, 0],['3/13/2020', 35, 0, 0],['3/14/2020', 78, 1, 0],['3/15/2020', 103, 2, 0],['3/16/2020', 157, 3, 0],['3/17/2020', 221, 4, 0],['3/18/2020', 278, 7, 0],['3/19/2020', 278, 7, 0],['3/20/2020', 537, 14, 0],['3/21/2020', 763, 20, 0],['3/22/2020', 837, 20, 0],['3/23/2020', 1172, 35, 0],['3/24/2020', 1388, 46, 0],['3/25/2020', 1795, 65, 0],['3/26/2020', 2305, 83, 0],['3/27/2020', 2746, 119, 0],['3/28/2020', 3315, 137, 0],['3/29/2020', 3540, 151, 0],['3/30/2020', 4025, 185, 0],['3/31/2020', 5238, 239, 0],['4/1/2020', 6425, 273, 0],['4/2/2020', 9122, 310, 0],['4/3/2020', 10210, 370, 0],['4/4/2020', 12496, 409, 0],['4/5/2020', 13010, 477, 0],['4/6/2020', 14867, 512, 0],['4/7/2020', 16284, 582, 0],['4/8/2020', 17030, 652, 0],['4/9/2020', 18283, 702, 0],['4/10/2020', 19253, 755, 0],['4/11/2020', 20014, 806, 0],['4/12/2020', 20595, 840, 0],['4/13/2020', 21016, 884, 0],['4/14/2020', 21518, 1013, 0],['4/15/2020', 21946, 1103, 0],['4/16/2020', 22517, 1156, 0],['4/17/2020', 23118, 1213, 0],['4/18/2020', 23580, 1267, 0],['4/19/2020', 23928, 1296, 0],['4/20/2020', 24523, 1328, 0],['4/21/2020', 24854, 1405, 0],['4/22/2020', 25258, 1473, 0],['4/23/2020', 25739, 1599, 0],['4/24/2020', 26159, 1661, 14927],['4/25/2020', 26512, 1703, 14927],['4/26/2020', 26773, 1729, 14927],['4/27/2020', 27068, 1740, 17303],['4/28/2020', 27286, 1801, 17303],['4/29/2020', 27660, 1845, 17303],['4/30/2020', 28001, 1905, 17303],['5/1/2020', 28558, 1944, 17303],['5/2/2020', 29140, 1993, 17303],['5/3/2020', 29340, 2012, 17303],['5/4/2020', 29701, 2065, 17303],['5/5/2020', 29996, 2115, 20316],['5/6/2020', 30399, 2167, 20316],['5/7/2020', 30652, 2208, 20316],['5/8/2020', 30855, 2227, 20316],['5/9/2020', 31417, 2267, 20316],
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
      [30.4037, -92.2145, "Acadia", 151, 11],[30.867, -92.7986, "Allen", 90, 9],[30.1828, -90.8674, "Ascension", 689, 46],[29.9886, -91.0555, "Assumption", 208, 11],[30.954, -92.1884, "Avoyelles", 74, 7],[30.5289, -93.4391, "Beauregard", 46, 4],[32.3261, -93.2837, "Bienville", 78, 17],[32.5606, -93.5625, "Bossier", 310, 20],[32.6091, -93.8841, "Caddo", 1743, 129],[30.2393, -93.0128, "Calcasieu", 490, 38],[32.0288, -92.1408, "Caldwell", 48, 0],[31.8492, -91.6599, "Catahoula", 83, 3],[32.793, -93.0582, "Claiborne", 59, 9],[32.0181, -93.7237, "De Soto", 213, 13],[30.5467, -91.1225, "East Baton Rouge", 2348, 179],[32.8133, -91.1826, "East Carroll", 17, 0],[30.9682, -91.1125, "East Feliciana", 136, 21],[30.5696, -92.3169, "Evangeline", 67, 1],[32.1651, -91.721, "Franklin", 188, 4],[31.43, -92.4829, "Grant", 18, 0],[30.0049, -91.8202, "Iberia", 285, 26],[30.161, -91.1495, "Iberville", 495, 36],[32.2719, -92.7303, "Jackson", 59, 4],[29.6499, -90.1121, "Jefferson", 6679, 396],[30.2355, -92.7481, "Jefferson Davis", 67, 6],[30.3126, -92.0387, "Lafayette", 498, 22],[29.5164, -90.3291, "Lafourche", 706, 59],[32.5329, -92.6361, "Lincoln", 106, 11],[30.4953, -90.7467, "Livingston", 277, 22],[32.4067, -91.1915, "Madison", 12, 0],[32.7749, -91.9058, "Morehouse", 60, 5],[31.6547, -93.1999, "Natchitoches", 98, 9],[29.9511, -90.0715, "Orleans", 6674, 468],[32.4883, -92.1619, "Ouachita", 836, 25],[29.3443, -89.4683, "Plaquemines", 189, 17],[30.6824, -91.4248, "Pointe Coupee", 126, 17],[31.3414, -92.4096, "Rapides", 351, 12],[32.0256, -93.3406, "Red River", 36, 6],[32.4902, -91.8651, "Richland", 99, 1],[31.6118, -93.4077, "Sabine", 17, 1],[29.8625, -89.8877, "St. Bernard", 512, 20],[29.9986, -90.4036, "St. Charles", 594, 43],[30.0917, -90.8844, "St. James", 257, 20],[29.9205, -90.6458, "St. John the Baptist", 801, 76],[30.528, -92.0851, "St. Landry", 211, 49],[30.3368, -91.8476, "St. Martin", 257, 21],[29.8113, -91.6705, "St. Mary", 242, 26],[30.3687, -89.7495, "St. Tammany", 1447, 130],[30.7646, -90.5114, "Tangipahoa", 652, 27],[29.3864, -90.7081, "Terrebonne", 523, 37],[33.0073, -92.7224, "Union", 162, 8],[29.975, -92.1266, "Vermilion", 41, 2],[30.9344, -92.9268, "Vernon", 18, 2],[30.8479, -90.1459, "Washington", 335, 26],[32.525, -93.4118, "Webster", 97, 4],[30.4456, -91.2098, "West Baton Rouge", 122, 25],[30.7851, -91.3787, "West Feliciana", 183, 6],[31.924, -92.6425, "Winn", 51, 2],[31.713, -91.4453, "Concordia", 43, 5],[30.6823, -90.6545, "St. Helena", 35, 1],[32.6038, -91.4814, "West Carroll", 4, 0],[29.9717, -93.3947, "Cameron", 3, 0],[32.0723, -91.239, "Tensas", 6, 0],[31.7002461, -92.2236667, "La Salle", 31, 0],[31.7002461, -92.2236667, "LaSalle", 33, 0],
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
      [{v:"Acadia", f:"Acadia"}, 151, 9, 140, 11, 0, 0],[{v:"Allen", f:"Allen"}, 90, 0, 81, 9, 0, 0],[{v:"Ascension", f:"Ascension"}, 689, 14, 643, 46, 0, 0],[{v:"Assumption", f:"Assumption"}, 208, 2, 197, 11, 2, 0],[{v:"Avoyelles", f:"Avoyelles"}, 74, 0, 67, 7, 0, 0],[{v:"Beauregard", f:"Beauregard"}, 46, 2, 42, 4, 0, 0],[{v:"Bienville", f:"Bienville"}, 78, 0, 61, 17, 1, 0],[{v:"Bossier", f:"Bossier"}, 310, 2, 290, 20, 1, 0],[{v:"Caddo", f:"Caddo"}, 1743, 31, 1614, 129, 1, 0],[{v:"Calcasieu", f:"Calcasieu"}, 490, 9, 452, 38, 0, 0],[{v:"Caldwell", f:"Caldwell"}, 48, 1, 48, 0, 0, 0],[{v:"Catahoula", f:"Catahoula"}, 83, 24, 80, 3, 0, 0],[{v:"Claiborne", f:"Claiborne"}, 59, 0, 50, 9, 0, 0],[{v:"De Soto", f:"De Soto"}, 213, 5, 200, 13, 0, 0],[{v:"East Baton Rouge", f:"East Baton Rouge"}, 2348, 64, 2169, 179, 8, 0],[{v:"East Carroll", f:"East Carroll"}, 17, 2, 17, 0, 0, 0],[{v:"East Feliciana", f:"East Feliciana"}, 136, 3, 115, 21, 2, 0],[{v:"Evangeline", f:"Evangeline"}, 67, 0, 66, 1, 0, 0],[{v:"Franklin", f:"Franklin"}, 188, 42, 184, 4, 0, 0],[{v:"Grant", f:"Grant"}, 18, 1, 18, 0, 0, 0],[{v:"Iberia", f:"Iberia"}, 285, 2, 259, 26, 0, 0],[{v:"Iberville", f:"Iberville"}, 495, 2, 459, 36, 1, 0],[{v:"Jackson", f:"Jackson"}, 59, 1, 55, 4, 0, 0],[{v:"Jefferson", f:"Jefferson"}, 6679, 69, 6283, 396, 4, 0],[{v:"Jefferson Davis", f:"Jefferson Davis"}, 67, 1, 61, 6, 0, 0],[{v:"Lafayette", f:"Lafayette"}, 498, 17, 476, 22, 1, 0],[{v:"Lafourche", f:"Lafourche"}, 706, 8, 647, 59, 2, 0],[{v:"Lincoln", f:"Lincoln"}, 106, 3, 95, 11, 0, 0],[{v:"Livingston", f:"Livingston"}, 277, 9, 255, 22, 3, 0],[{v:"Madison", f:"Madison"}, 12, 4, 12, 0, 0, 0],[{v:"Morehouse", f:"Morehouse"}, 60, 3, 55, 5, 0, 0],[{v:"Natchitoches", f:"Natchitoches"}, 98, 6, 89, 9, 1, 0],[{v:"Orleans", f:"Orleans"}, 6674, 29, 6206, 468, 4, 0],[{v:"Ouachita", f:"Ouachita"}, 836, 16, 811, 25, 0, 0],[{v:"Plaquemines", f:"Plaquemines"}, 189, 4, 172, 17, 0, 0],[{v:"Pointe Coupee", f:"Pointe Coupee"}, 126, 1, 109, 17, 0, 0],[{v:"Rapides", f:"Rapides"}, 351, 13, 339, 12, 1, 0],[{v:"Red River", f:"Red River"}, 36, 2, 30, 6, 0, 0],[{v:"Richland", f:"Richland"}, 99, 4, 98, 1, 0, 0],[{v:"Sabine", f:"Sabine"}, 17, 0, 16, 1, 0, 0],[{v:"St. Bernard", f:"St. Bernard"}, 512, 4, 492, 20, 0, 0],[{v:"St. Charles", f:"St. Charles"}, 594, 0, 551, 43, 0, 0],[{v:"St. James", f:"St. James"}, 257, 0, 237, 20, 0, 0],[{v:"St. John the Baptist", f:"St. John the Baptist"}, 801, 10, 725, 76, 0, 0],[{v:"St. Landry", f:"St. Landry"}, 211, 7, 162, 49, 0, 0],[{v:"St. Martin", f:"St. Martin"}, 257, 2, 236, 21, 1, 0],[{v:"St. Mary", f:"St. Mary"}, 242, 18, 216, 26, 1, 0],[{v:"St. Tammany", f:"St. Tammany"}, 1447, 31, 1317, 130, 5, 0],[{v:"Tangipahoa", f:"Tangipahoa"}, 652, 7, 625, 27, 0, 0],[{v:"Terrebonne", f:"Terrebonne"}, 523, 22, 486, 37, 1, 0],[{v:"Union", f:"Union"}, 162, 9, 154, 8, 0, 0],[{v:"Vermilion", f:"Vermilion"}, 41, 1, 39, 2, 0, 0],[{v:"Vernon", f:"Vernon"}, 18, 1, 16, 2, 0, 0],[{v:"Washington", f:"Washington"}, 335, 23, 309, 26, 2, 0],[{v:"Webster", f:"Webster"}, 97, 0, 93, 4, 0, 0],[{v:"West Baton Rouge", f:"West Baton Rouge"}, 122, 3, 97, 25, 1, 0],[{v:"West Feliciana", f:"West Feliciana"}, 183, 7, 177, 6, 0, 0],[{v:"Winn", f:"Winn"}, 51, 2, 49, 2, 0, 0],[{v:"Concordia", f:"Concordia"}, 43, 0, 38, 5, 0, 0],[{v:"St. Helena", f:"St. Helena"}, 35, 3, 34, 1, 0, 0],[{v:"West Carroll", f:"West Carroll"}, 4, 0, 4, 0, 0, 0],[{v:"Cameron", f:"Cameron"}, 3, 0, 3, 0, 0, 0],[{v:"Tensas", f:"Tensas"}, 6, 3, 6, 0, 0, 0],[{v:"La Salle", f:"La Salle"}, 31, 1, 31, 0, 0, 0],[{v:"LaSalle", f:"LaSalle"}, 33, 2, 33, 0, 0, 0],
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
<div class="col-md-6 col-sm-12">
  <div class="content-card">
	<a href="https://www.cbsnews.com/news/louisiana-lawmakers-to-consider-strike-at-governors-stay-at-home-order/"><div class="card-image" style="background-image: url(https://cbsnews2.cbsistatic.com/hub/i/r/2020/05/06/0d0ada19-c92f-4046-b515-38751debb461/thumbnail/1200x630/a994d3506dfce63f4c076087ae6a1b5e/gettyimages-1221857816.jpg)"></div></a>
	<div class="content">
		<div class="card-title"><a href="https://www.cbsnews.com/news/louisiana-lawmakers-to-consider-strike-at-governors-stay-at-home-order/">Louisiana lawmakers to consider strike at governor's stay-at-home order</a></div>
		<div class="card-excerpt">State Republican lawmakers criticized Governor John Bel Edwards' decision to extend his stay-at-home order through May 15.</div>
		<div class="card-meta">
			<span class="card-provider">CBS News</span> • <span class="card-date">5/6/2020</span>
		</div>
	</div>
  </div>
</div>
<div class="col-md-6 col-sm-12">
  <div class="content-card">
	<a href="https://www.nola.com/news/coronavirus/article_d985e124-8e20-11ea-87dd-471ac36bebd1.html"><div class="card-image" style="background-image: url(https://bloximages.newyork1.vip.townnews.com/nola.com/content/tncms/assets/v3/editorial/0/f4/0f40b716-7ad6-11ea-ba1c-27308f798040/5e8fc7b1eba6d.preview.png)"></div></a>
	<div class="content">
		<div class="card-title"><a href="https://www.nola.com/news/coronavirus/article_d985e124-8e20-11ea-87dd-471ac36bebd1.html">Coronavirus in Louisiana, May 5: Death toll climbs past 2K; Orleans reports 18 new cases</a></div>
		<div class="card-excerpt">Louisiana saw 51 new coronavirus-related deaths reported Monday, bringing the state's total to 2,042 as cases crept toward 30,000.</div>
		<div class="card-meta">
			<span class="card-provider">NOLA.com</span> • <span class="card-date">5/5/2020</span>
		</div>
	</div>
  </div>
</div>
<div class="col-md-6 col-sm-12">
  <div class="content-card">
	<a href="https://www.theadvertiser.com/story/news/2020/05/05/louisiana-coronavirus-nearly-entire-prison-dorm-tests-positive-most-without-symptoms/3083679001/"><div class="card-image" style="background-image: url(https://www.gannett-cdn.com/presto/2019/03/25/PGRF/33561a45-530b-43e3-8185-03c9f328538f-for_online_jail.jpg?auto=webp&crop=2009,1134,x0,y0&format=pjpg&width=1200)"></div></a>
	<div class="content">
		<div class="card-title"><a href="https://www.theadvertiser.com/story/news/2020/05/05/louisiana-coronavirus-nearly-entire-prison-dorm-tests-positive-most-without-symptoms/3083679001/">Coronavirus: Nearly entire Louisiana prison dorm tests positive for COVID-19</a></div>
		<div class="card-excerpt">Two-thirds of the women at Elayn Hunt Correctional Center in St. Gabriel who tested positive showed no symptoms.</div>
		<div class="card-meta">
			<span class="card-provider">The Daily Advertiser</span> • <span class="card-date">5/5/2020</span>
		</div>
	</div>
  </div>
</div>
<div class="col-md-6 col-sm-12">
  <div class="content-card">
	<a href="https://www.nola.com/news/coronavirus/article_d985e124-8e20-11ea-87dd-471ac36bebd1.html"><div class="card-image" style="background-image: url(https://bloximages.newyork1.vip.townnews.com/nola.com/content/tncms/assets/v3/editorial/8/41/8415a6f4-8a27-11ea-ba41-63a57f798592/5ea9925f6ea71.image.jpg?resize=1024%2C682)"></div></a>
	<div class="content">
		<div class="card-title"><a href="https://www.nola.com/news/coronavirus/article_d985e124-8e20-11ea-87dd-471ac36bebd1.html">Coronavirus in Louisiana, May 4: 333 new cases, 22 deaths statewide reported Monday</a></div>
		<div class="card-excerpt">Another 333 coronavirus cases and 22 deaths were reported across Louisiana on Monday. That total included another 19 cases and six deaths in Orleans Parish, according to the the daily noon update from the Louisiana Department of Health.</div>
		<div class="card-meta">
			<span class="card-provider">NOLA.com</span> • <span class="card-date">5/4/2020</span>
		</div>
	</div>
  </div>
</div>
<div class="col-md-6 col-sm-12">
  <div class="content-card">
	<a href="https://www.theadvocate.com/baton_rouge/news/coronavirus/article_3f3170d4-8e1b-11ea-8ea9-fbbffccf9893.html"><div class="card-image" style="background-image: url(https://bloximages.newyork1.vip.townnews.com/theadvocate.com/content/tncms/assets/v3/editorial/8/79/879ff78b-de3e-5525-ad0c-801a1f30e370/5eb037638d29e.image.jpg?resize=1024%2C768)"></div></a>
	<div class="content">
		<div class="card-title"><a href="https://www.theadvocate.com/baton_rouge/news/coronavirus/article_3f3170d4-8e1b-11ea-8ea9-fbbffccf9893.html">75% in attendance and many without masks: Louisiana legislature reconvenes amid coronavirus</a></div>
		<div class="card-excerpt">Louisiana House gaveled in Monday to restart the legislative session that was suspended for more than a month because of the coronavirus pandemic.</div>
		<div class="card-meta">
			<span class="card-provider">The Advocate</span> • <span class="card-date">5/4/2020</span>
		</div>
	</div>
  </div>
</div>
<div class="col-md-6 col-sm-12">
  <div class="content-card">
	<a href="https://www.nola.com/news/coronavirus/article_4fc2f816-8d51-11ea-878a-afab88e5e725.html"><div class="card-image" style="background-image: url(https://bloximages.newyork1.vip.townnews.com/nola.com/content/tncms/assets/v3/editorial/c/47/c4715ae4-8898-11ea-9e03-ff4bc45c3475/5ea6f51e14bd6.image.jpg?resize=1024%2C682)"></div></a>
	<div class="content">
		<div class="card-title"><a href="https://www.nola.com/news/coronavirus/article_4fc2f816-8d51-11ea-878a-afab88e5e725.html">Coronavirus in Louisiana: 40 new cases, 4 deaths in New Orleans area; see latest data</a></div>
		<div class="card-excerpt">Nineteen new deaths have been reported in connection to the the novel coronavirus in Louisiana over the past 24 hours, according to the latest Louisiana Department of Health data released</div>
		<div class="card-meta">
			<span class="card-provider">NOLA.com</span> • <span class="card-date">5/3/2020</span>
		</div>
	</div>
  </div>
</div>
<div class="col-md-6 col-sm-12">
  <div class="content-card">
	<a href="https://www.nola.com/news/coronavirus/article_99ea7c8a-8ba7-11ea-a898-6b6bd269502b.html"><div class="card-image" style="background-image: url(https://bloximages.newyork1.vip.townnews.com/nola.com/content/tncms/assets/v3/editorial/7/ad/7ad2ec4e-78e0-11ea-aae7-e3b48e8f4717/5e8c95b666c97.image.jpg?resize=1024%2C683)"></div></a>
	<div class="content">
		<div class="card-title"><a href="https://www.nola.com/news/coronavirus/article_99ea7c8a-8ba7-11ea-a898-6b6bd269502b.html">Coronavirus in Louisiana: 151 new cases, 25 deaths in Orleans and Jefferson, see statewide data</a></div>
		<div class="card-excerpt">Health officials are reporting 43 new positive cases of coronavirus in New Orleans and 108 new cases in Jefferson Parish bringing the total for the two parishes to 12,800 on</div>
		<div class="card-meta">
			<span class="card-provider">NOLA.com</span> • <span class="card-date">5/1/2020</span>
		</div>
	</div>
  </div>
</div>

</div>

