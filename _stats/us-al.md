---
category: stats
title: "US - Alabama State Coronavirus (COVID-19) Live Stats"
excerpt: "Live stats of COVID-19 in US-Alabama. Total Cases: 9669 (+284), Deaths: 393 (+8), Recoveries: 20(-)."
publishedDateTime: 2020-05-10T05:45:41Z
updatedDateTime: 2020-05-10T05:45:41Z
webUrl: "https://smartable.ai/apps/coronavirus/stats/us-al/"
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
  - url: "https://smartable.azureedge.net/coronavirus/sites/2/2020/us-al.jpg"
    width: 900
    height: 564
    title: "US - Alabama State Coronavirus (COVID-19) Live Stats"

---
<div class="total-stats" style="text-align: center;">
    <h3>
	    <div style="font-size: 18px; font-weight: 400;">Total Confirmed Cases:</div>
	    9669 (<span class='red'>+284</span>)
    </h3>
    <h3>
	    <div style="font-size: 18px; font-weight: 400;">Total Deaths:</div>
	    393 (<span class='red'>+8</span>)
    </h3>
    <h3>
	    <div style="font-size: 18px; font-weight: 400;">Total Recovered:</div>
	    20 (-)
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
      ['1/22/2020', 0, 0, 0],['1/23/2020', 0, 0, 0],['1/24/2020', 0, 0, 0],['1/25/2020', 0, 0, 0],['1/26/2020', 0, 0, 0],['1/27/2020', 0, 0, 0],['1/28/2020', 0, 0, 0],['1/29/2020', 0, 0, 0],['1/30/2020', 0, 0, 0],['1/31/2020', 0, 0, 0],['2/1/2020', 0, 0, 0],['2/2/2020', 0, 0, 0],['2/3/2020', 0, 0, 0],['2/4/2020', 0, 0, 0],['2/5/2020', 0, 0, 0],['2/6/2020', 0, 0, 0],['2/7/2020', 0, 0, 0],['2/8/2020', 0, 0, 0],['2/9/2020', 0, 0, 0],['2/10/2020', 0, 0, 0],['2/11/2020', 0, 0, 0],['2/12/2020', 0, 0, 0],['2/13/2020', 0, 0, 0],['2/14/2020', 0, 0, 0],['2/15/2020', 0, 0, 0],['2/16/2020', 0, 0, 0],['2/17/2020', 0, 0, 0],['2/18/2020', 0, 0, 0],['2/19/2020', 0, 0, 0],['2/20/2020', 0, 0, 0],['2/21/2020', 0, 0, 0],['2/22/2020', 0, 0, 0],['2/23/2020', 0, 0, 0],['2/24/2020', 0, 0, 0],['2/25/2020', 0, 0, 0],['2/26/2020', 0, 0, 0],['2/27/2020', 0, 0, 0],['2/28/2020', 0, 0, 0],['2/29/2020', 0, 0, 0],['3/1/2020', 0, 0, 0],['3/2/2020', 0, 0, 0],['3/3/2020', 0, 0, 0],['3/4/2020', 0, 0, 0],['3/5/2020', 0, 0, 0],['3/6/2020', 0, 0, 0],['3/7/2020', 0, 0, 0],['3/8/2020', 0, 0, 0],['3/9/2020', 0, 0, 0],['3/10/2020', 0, 0, 0],['3/11/2020', 0, 0, 0],['3/12/2020', 0, 0, 0],['3/13/2020', 6, 0, 0],['3/14/2020', 12, 0, 0],['3/15/2020', 22, 0, 0],['3/16/2020', 29, 0, 0],['3/17/2020', 39, 0, 0],['3/18/2020', 52, 0, 0],['3/19/2020', 78, 0, 0],['3/20/2020', 106, 0, 0],['3/21/2020', 131, 0, 0],['3/22/2020', 157, 0, 0],['3/23/2020', 196, 0, 0],['3/24/2020', 242, 0, 0],['3/25/2020', 439, 1, 0],['3/26/2020', 532, 1, 0],['3/27/2020', 640, 4, 0],['3/28/2020', 722, 9, 0],['3/29/2020', 831, 10, 0],['3/30/2020', 948, 11, 0],['3/31/2020', 1000, 24, 0],['4/1/2020', 1108, 28, 0],['4/2/2020', 1270, 32, 0],['4/3/2020', 1535, 38, 0],['4/4/2020', 1633, 44, 0],['4/5/2020', 1841, 45, 0],['4/6/2020', 2006, 53, 0],['4/7/2020', 2197, 64, 0],['4/8/2020', 2499, 67, 0],['4/9/2020', 2839, 78, 0],['4/10/2020', 3009, 80, 0],['4/11/2020', 3263, 93, 0],['4/12/2020', 3583, 93, 0],['4/13/2020', 3803, 103, 0],['4/14/2020', 3953, 114, 0],['4/15/2020', 4241, 123, 0],['4/16/2020', 4402, 137, 0],['4/17/2020', 4523, 151, 0],['4/18/2020', 4723, 147, 0],['4/19/2020', 4903, 160, 0],['4/20/2020', 5078, 164, 0],['4/21/2020', 5327, 185, 0],['4/22/2020', 5610, 201, 0],['4/23/2020', 5832, 202, 0],['4/24/2020', 5832, 203, 0],['4/25/2020', 6213, 213, 20],['4/26/2020', 6423, 222, 20],['4/27/2020', 6543, 231, 20],['4/28/2020', 6752, 245, 20],['4/29/2020', 6925, 262, 20],['4/30/2020', 7089, 274, 20],['5/1/2020', 7340, 278, 20],['5/2/2020', 7613, 292, 20],['5/3/2020', 7889, 294, 20],['5/4/2020', 8115, 302, 20],['5/5/2020', 8438, 318, 20],['5/6/2020', 8693, 344, 20],['5/7/2020', 9046, 373, 20],['5/8/2020', 9385, 385, 20],['5/9/2020', 9669, 393, 20],
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
      [32.6793, -86.4607, "Autauga", 68, 4],[30.2758, -87.7014, "Baldwin", 216, 5],[32.9597, -87.1334, "Bibb", 45, 1],[33.8789, -86.8241, "Blount", 44, 0],[32.0764, -85.5244, "Bullock", 22, 1],[31.5429, -86.7246, "Butler", 178, 6],[33.5966, -85.869, "Calhoun", 124, 3],[32.7876, -85.3057, "Chambers", 314, 22],[34.1839, -85.775, "Cherokee", 22, 0],[32.917, -86.7203, "Chilton", 64, 1],[31.7131, -88.2917, "Choctaw", 61, 0],[33.3129, -85.7508, "Clay", 26, 1],[33.7297, -85.4312, "Cleburne", 13, 1],[31.3276, -85.8459, "Coffee", 146, 1],[34.7559, -87.7007, "Colbert", 64, 2],[32.9791, -86.0358, "Coosa", 31, 1],[31.3006, -86.3975, "Covington", 50, 1],[31.8495, -86.2057, "Crenshaw", 38, 0],[34.0452, -86.8837, "Cullman", 63, 0],[32.4166, -87.0336, "Dallas", 102, 3],[34.4939, -85.8435, "DeKalb", 142, 2],[32.6314, -86.3268, "Elmore", 135, 4],[31.0127, -87.2541, "Escambia", 36, 3],[33.9446, -85.9319, "Etowah", 170, 10],[34.5056, -87.7282, "Franklin", 216, 1],[32.9938, -87.9071, "Greene", 70, 3],[31.1858, -85.2359, "Houston", 104, 4],[34.6438, -86.0491, "Jackson", 59, 2],[33.544, -86.6599, "Jefferson", 1109, 60],[33.7589, -88.1144, "Lamar", 13, 0],[34.9652, -87.3735, "Lauderdale", 88, 3],[34.6718, -87.4063, "Lawrence", 22, 0],[32.6049, -85.5948, "Lee", 422, 30],[34.9847, -86.8373, "Limestone", 57, 0],[32.1801, -86.6888, "Lowndes", 96, 5],[32.4551, -85.8066, "Macon", 47, 2],[34.8491, -86.5222, "Madison", 247, 4],[32.498, -87.8298, "Marengo", 77, 4],[33.9443, -87.8704, "Marion", 96, 7],[34.5189, -86.2492, "Marshall", 543, 8],[30.2525, -88.1438, "Mobile", 1452, 83],[31.3074, -87.4992, "Monroe", 15, 1],[32.3473, -86.2666, "Montgomery", 576, 15],[34.4676, -86.7936, "Morgan", 92, 0],[33.322, -87.904, "Pickens", 65, 2],[31.8021, -85.9665, "Pike", 89, 0],[33.4198, -85.4903, "Randolph", 102, 6],[32.2401, -85.4147, "Russell", 77, 0],[33.2846, -86.8756, "Shelby", 362, 17],[33.5609, -86.2668, "St. Clair", 81, 1],[33.3891, -86.0361, "Talladega", 73, 2],[33.0567, -85.9312, "Tallapoosa", 316, 42],[33.2302, -87.4827, "Tuscaloosa", 274, 4],[33.7503, -87.0483, "Walker", 106, 0],[31.2649, -88.0284, "Washington", 51, 2],[32.0701, -87.2914, "Wilcox", 80, 4],[34.1496, -87.4027, "Winston", 20, 0],[33.8922, -87.7328, "Fayette", 7, 0],[32.9968, -87.6272, "Hale", 66, 2],[32.5982, -88.1891, "Sumter", 98, 4],[31.9111, -87.7419, "Clarke", 53, 1],[31.3001, -87.027, "Conecuh", 13, 0],[31.2999, -85.4502, "Dale", 43, 0],[31.3501, -85.3523, "Henry", 28, 1],[31.781, -85.5583, "Barbour", 58, 1],[32.6318, -87.3172, "Perry", 19, 0],[31.0437, -85.8764, "Geneva", 13, 0],
    ]);
    var options = {
      backgroundColor: {fill:'transparent',stroke:'#FFF' ,strokeWidth:0 }, 
      displayMode: 'markers',
      region: 'US-AL', 
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
      [{v:"Autauga", f:"Autauga"}, 68, 1, 64, 4, 0, 0],[{v:"Baldwin", f:"Baldwin"}, 216, 8, 211, 5, 0, 0],[{v:"Bibb", f:"Bibb"}, 45, 1, 44, 1, 1, 0],[{v:"Blount", f:"Blount"}, 44, 0, 44, 0, 0, 0],[{v:"Bullock", f:"Bullock"}, 22, 1, 21, 1, 0, 0],[{v:"Butler", f:"Butler"}, 178, 16, 172, 6, 3, 0],[{v:"Calhoun", f:"Calhoun"}, 124, 1, 121, 3, 0, 0],[{v:"Chambers", f:"Chambers"}, 314, 3, 292, 22, 0, 0],[{v:"Cherokee", f:"Cherokee"}, 22, 1, 22, 0, 0, 0],[{v:"Chilton", f:"Chilton"}, 64, 1, 63, 1, 0, 0],[{v:"Choctaw", f:"Choctaw"}, 61, 2, 61, 0, 0, 0],[{v:"Clay", f:"Clay"}, 26, 0, 25, 1, 0, 0],[{v:"Cleburne", f:"Cleburne"}, 13, 0, 12, 1, 0, 0],[{v:"Coffee", f:"Coffee"}, 146, 3, 145, 1, 0, 0],[{v:"Colbert", f:"Colbert"}, 64, 1, 62, 2, 0, 0],[{v:"Coosa", f:"Coosa"}, 31, 0, 30, 1, 0, 0],[{v:"Covington", f:"Covington"}, 50, 0, 49, 1, 0, 0],[{v:"Crenshaw", f:"Crenshaw"}, 38, 5, 38, 0, 0, 0],[{v:"Cullman", f:"Cullman"}, 63, 1, 63, 0, 0, 0],[{v:"Dallas", f:"Dallas"}, 102, 7, 99, 3, 0, 0],[{v:"DeKalb", f:"DeKalb"}, 142, 6, 140, 2, 0, 0],[{v:"Elmore", f:"Elmore"}, 135, 5, 131, 4, 0, 0],[{v:"Escambia", f:"Escambia"}, 36, 1, 33, 3, 0, 0],[{v:"Etowah", f:"Etowah"}, 170, 4, 160, 10, 0, 0],[{v:"Franklin", f:"Franklin"}, 216, 14, 215, 1, 0, 0],[{v:"Greene", f:"Greene"}, 70, 0, 67, 3, 0, 0],[{v:"Houston", f:"Houston"}, 104, 2, 100, 4, 0, 0],[{v:"Jackson", f:"Jackson"}, 59, 0, 57, 2, 0, 0],[{v:"Jefferson", f:"Jefferson"}, 1109, 15, 1049, 60, 1, 0],[{v:"Lamar", f:"Lamar"}, 13, 0, 13, 0, 0, 0],[{v:"Lauderdale", f:"Lauderdale"}, 88, 1, 85, 3, 0, 0],[{v:"Lawrence", f:"Lawrence"}, 22, 1, 22, 0, 0, 0],[{v:"Lee", f:"Lee"}, 422, 3, 392, 30, 0, 0],[{v:"Limestone", f:"Limestone"}, 57, 2, 57, 0, 0, 0],[{v:"Lowndes", f:"Lowndes"}, 96, 8, 91, 5, 0, 0],[{v:"Macon", f:"Macon"}, 47, 3, 45, 2, 0, 0],[{v:"Madison", f:"Madison"}, 247, 3, 243, 4, 0, 0],[{v:"Marengo", f:"Marengo"}, 77, 1, 73, 4, 0, 0],[{v:"Marion", f:"Marion"}, 96, 1, 89, 7, 0, 0],[{v:"Marshall", f:"Marshall"}, 543, 18, 535, 8, 0, 0],[{v:"Mobile", f:"Mobile"}, 1452, 45, 1369, 83, 2, 0],[{v:"Monroe", f:"Monroe"}, 15, 0, 14, 1, 0, 0],[{v:"Montgomery", f:"Montgomery"}, 576, 43, 561, 15, 0, 0],[{v:"Morgan", f:"Morgan"}, 92, 5, 92, 0, 0, 0],[{v:"Pickens", f:"Pickens"}, 65, 2, 63, 2, 0, 0],[{v:"Pike", f:"Pike"}, 89, 2, 89, 0, 0, 0],[{v:"Randolph", f:"Randolph"}, 102, 2, 96, 6, 0, 0],[{v:"Russell", f:"Russell"}, 77, 4, 77, 0, 0, 0],[{v:"Shelby", f:"Shelby"}, 362, 4, 345, 17, 0, 0],[{v:"St. Clair", f:"St. Clair"}, 81, 2, 80, 1, 0, 0],[{v:"Talladega", f:"Talladega"}, 73, 1, 71, 2, 0, 0],[{v:"Tallapoosa", f:"Tallapoosa"}, 316, 1, 274, 42, 1, 0],[{v:"Tuscaloosa", f:"Tuscaloosa"}, 274, 5, 270, 4, 0, 0],[{v:"Walker", f:"Walker"}, 106, 1, 106, 0, 0, 0],[{v:"Washington", f:"Washington"}, 51, 3, 49, 2, 0, 0],[{v:"Wilcox", f:"Wilcox"}, 80, 3, 76, 4, 0, 0],[{v:"Winston", f:"Winston"}, 20, 0, 20, 0, 0, 0],[{v:"Fayette", f:"Fayette"}, 7, 0, 7, 0, 0, 0],[{v:"Hale", f:"Hale"}, 66, 4, 64, 2, 0, 0],[{v:"Sumter", f:"Sumter"}, 98, 5, 94, 4, 0, 0],[{v:"Clarke", f:"Clarke"}, 53, 0, 52, 1, 0, 0],[{v:"Conecuh", f:"Conecuh"}, 13, 1, 13, 0, 0, 0],[{v:"Dale", f:"Dale"}, 43, 3, 43, 0, 0, 0],[{v:"Henry", f:"Henry"}, 28, 1, 27, 1, 0, 0],[{v:"Barbour", f:"Barbour"}, 58, 5, 57, 1, 0, 0],[{v:"Perry", f:"Perry"}, 19, 1, 19, 0, 0, 0],[{v:"Geneva", f:"Geneva"}, 13, 1, 13, 0, 0, 0],
    ]);
    data.setProperty(0, 0, 'style', 'min-width:100px');
    var table = new google.visualization.Table(document.getElementById('geo_table'));
    table.draw(data, {allowHtml: true, sortColumn: 2, sortAscending: false, width: '660px', height: '100%'});
  }
</script>

<span style="font-size: 13px">All COVID-19 data displayed on the page is available through our FREE <a href="https://developer.smartable.ai">API program</a>. This US - Alabama State Coronavirus (COVID-19) Live Stats is refreshed every hour using credible data sources, including the country/state's official government website, <a href="https://en.wikipedia.org/wiki/2019%E2%80%9320_coronavirus_pandemic" target="_blank">data available on wikipedia pages</a>, latest news reports, <a href="https://systems.jhu.edu/research/public-health/ncov/" target="_blank">Johns Hopkins University CSSE 2019-nCoV Dashboard</a>, <a href="https://www.who.int/emergencies/diseases/novel-coronavirus-2019/situation-reports" target="_blank">WHO Situation Reports</a>, <a href="https://www.cdc.gov/coronavirus/2019-ncov/index.html" target="_blank">CDC Situation Updates</a>, and <a href="https://ncov.dxy.cn/ncovh5/view/pneumonia" target="_blank">DXY.cn</a>.</span>

<h2 id="news" class="center" style="margin-top: 60px; font-size: 25px;">Local Government Help Information</h2>
<div class="info center">
<a href="http://alabamapublichealth.gov/infectiousdiseases/2019-coronavirus.html" target="_blank">Alabama Department of Public Health (ADPH)</a>
</div>
<h2 id="news" class="center" style="margin-top: 60px; font-size: 25px;">Trending Coronavirus News in US-Alabama</h2>
<div class="row">
<div class="col-md-6 col-sm-12">
  <div class="content-card">
	<a href="https://www.al.com/news/2020/05/almost-60-of-alabamas-329-new-coronavirus-cases-from-5-counties-county-by-county-numbers.html"><div class="card-image" style="background-image: url(https://arc-anglerfish-arc2-prod-advancelocal.s3.amazonaws.com/public/WONF5QA6I5ATTJB5DQIYJ6GTLY.jpg)"></div></a>
	<div class="content">
		<div class="card-title"><a href="https://www.al.com/news/2020/05/almost-60-of-alabamas-329-new-coronavirus-cases-from-5-counties-county-by-county-numbers.html">Almost 60% of Alabama’s 329 new coronavirus cases from 5 counties; county-by-county numbers</a></div>
		<div class="card-excerpt">Alabama added 329 coronavirus cases overnight with almost 60 percent of all new cases coming from five counties. The Alabama Public Health’s May 6 10 a.m. figures</div>
		<div class="card-meta">
			<span class="card-provider">al.com</span> • <span class="card-date">5/6/2020</span>
		</div>
	</div>
  </div>
</div>
<div class="col-md-6 col-sm-12">
  <div class="content-card">
	<a href="https://www.al.com/news/2020/05/alabama-reports-270-new-coronavirus-cases-7615-overall-6-counties-have-double-digit-growth.html"><div class="card-image" style="background-image: url(https://arc-anglerfish-arc2-prod-advancelocal.s3.amazonaws.com/public/QV53B2FYO5AHFCRVAWOHKSG6Y4.JPG)"></div></a>
	<div class="content">
		<div class="card-title"><a href="https://www.al.com/news/2020/05/alabama-reports-270-new-coronavirus-cases-7615-overall-6-counties-have-double-digit-growth.html">Alabama reports 270 new coronavirus cases; 7,615 overall; 6 counties have double-digit growth</a></div>
		<div class="card-excerpt">Alabama reported 280 new coronavirus cases in the last day with 6 counties posting double-digit growth. The May 3, 2020 10 a.m. data from the Alabama Department of Public Health shows the state has 7,</div>
		<div class="card-meta">
			<span class="card-provider">al.com</span> • <span class="card-date">5/3/2020</span>
		</div>
	</div>
  </div>
</div>
<div class="col-md-6 col-sm-12">
  <div class="content-card">
	<a href="https://www.al.com/news/2020/05/7345-coronavirus-cases-in-alabama-up-277-overnight-mobile-adds-68-new-cases.html"><div class="card-image" style="background-image: url(https://arc-anglerfish-arc2-prod-advancelocal.s3.amazonaws.com/public/WKZEYAVS2NDENBULG5HZXULUDU.jpg)"></div></a>
	<div class="content">
		<div class="card-title"><a href="https://www.al.com/news/2020/05/7345-coronavirus-cases-in-alabama-up-277-overnight-mobile-adds-68-new-cases.html">7,345 coronavirus cases in Alabama, up 277 overnight; Mobile adds 68 new cases</a></div>
		<div class="card-excerpt">According to the Alabama Department of Public Health’s May 2 9:30 a.m. numbers, Alabama has 7,345 cases of COVID-19 with 289 deaths. Nationally, there are 1,105,078 confirmed cases of coronavirus with 64,</div>
		<div class="card-meta">
			<span class="card-provider">al.com</span> • <span class="card-date">5/2/2020</span>
		</div>
	</div>
  </div>
</div>
<div class="col-md-6 col-sm-12">
  <div class="content-card">
	<a href="https://www.al.com/news/2020/05/almost-60-of-alabamas-new-coronavirus-cases-come-from-4-counties.html"><div class="card-image" style="background-image: url(https://arc-anglerfish-arc2-prod-advancelocal.s3.amazonaws.com/public/LKLOTLL3ARBF7J7JQOH25SU434.JPG)"></div></a>
	<div class="content">
		<div class="card-title"><a href="https://www.al.com/news/2020/05/almost-60-of-alabamas-new-coronavirus-cases-come-from-4-counties.html">Almost 60% of Alabama’s new coronavirus cases come from 4 counties</a></div>
		<div class="card-excerpt">Alabama added 125 coronavirus cases in the last day, with 4 counties accounting for almost 60 percent of those. The Alabama Department of Public Health’s May 1 9:30 a.m. data shows the state has 7,068 cases of COVID-19 with 279 deaths.</div>
		<div class="card-meta">
			<span class="card-provider">al.com</span> • <span class="card-date">5/1/2020</span>
		</div>
	</div>
  </div>
</div>
<div class="col-md-6 col-sm-12">
  <div class="content-card">
	<a href="https://www.al.com/news/2020/04/42-of-alabamas-new-coronavirus-cases-come-from-1-county.html"><div class="card-image" style="background-image: url(https://arc-anglerfish-arc2-prod-advancelocal.s3.amazonaws.com/public/GKZSKKHY4FF47KAMXBDCIMDZY4.jpg)"></div></a>
	<div class="content">
		<div class="card-title"><a href="https://www.al.com/news/2020/04/42-of-alabamas-new-coronavirus-cases-come-from-1-county.html">42% of Alabama’s new coronavirus cases come from 1 county</a></div>
		<div class="card-excerpt">Mobile continues to Alabama’s coronavirus hotspot. The Alabama Department of Public Health’s 10:30 a.m. number shows 199 new coronavirus cases in the state in the last 24 hours, bringing the total number statewide to 6,</div>
		<div class="card-meta">
			<span class="card-provider">al.com</span> • <span class="card-date">4/29/2020</span>
		</div>
	</div>
  </div>
</div>

</div>

