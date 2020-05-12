---
category: stats
title: "US - Florida State Coronavirus (COVID-19) Live Stats"
excerpt: "Live stats of COVID-19 in US-Florida. Total Cases: 40982 (+386), Deaths: 1735 (+13), Recoveries: 1046(-)."
publishedDateTime: 2020-05-12T01:45:10Z
updatedDateTime: 2020-05-12T01:45:10Z
webUrl: "https://smartable.ai/apps/coronavirus/stats/us-fl/"
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
  - url: "https://smartable.azureedge.net/coronavirus/sites/2/2020/us-fl.jpg"
    width: 900
    height: 564
    title: "US - Florida State Coronavirus (COVID-19) Live Stats"

---
<div class="total-stats" style="text-align: center;">
    <h3>
	    <div style="font-size: 18px; font-weight: 400;">Total Confirmed Cases:</div>
	    40982 (<span class='red'>+386</span>)
    </h3>
    <h3>
	    <div style="font-size: 18px; font-weight: 400;">Total Deaths:</div>
	    1735 (<span class='red'>+13</span>)
    </h3>
    <h3>
	    <div style="font-size: 18px; font-weight: 400;">Total Recovered:</div>
	    1046 (-)
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
      ['1/22/2020', 0, 0, 0],['1/23/2020', 0, 0, 0],['1/24/2020', 0, 0, 0],['1/25/2020', 0, 0, 0],['1/26/2020', 0, 0, 0],['1/27/2020', 0, 0, 0],['1/28/2020', 0, 0, 0],['1/29/2020', 0, 0, 0],['1/30/2020', 0, 0, 0],['1/31/2020', 0, 0, 0],['2/1/2020', 0, 0, 0],['2/2/2020', 0, 0, 0],['2/3/2020', 0, 0, 0],['2/4/2020', 0, 0, 0],['2/5/2020', 0, 0, 0],['2/6/2020', 0, 0, 0],['2/7/2020', 0, 0, 0],['2/8/2020', 0, 0, 0],['2/9/2020', 0, 0, 0],['2/10/2020', 0, 0, 0],['2/11/2020', 0, 0, 0],['2/12/2020', 0, 0, 0],['2/13/2020', 0, 0, 0],['2/14/2020', 0, 0, 0],['2/15/2020', 0, 0, 0],['2/16/2020', 0, 0, 0],['2/17/2020', 0, 0, 0],['2/18/2020', 0, 0, 0],['2/19/2020', 0, 0, 0],['2/20/2020', 0, 0, 0],['2/21/2020', 0, 0, 0],['2/22/2020', 0, 0, 0],['2/23/2020', 0, 0, 0],['2/24/2020', 0, 0, 0],['2/25/2020', 0, 0, 0],['2/26/2020', 0, 0, 0],['2/27/2020', 0, 0, 0],['2/28/2020', 0, 0, 0],['2/29/2020', 0, 0, 0],['3/1/2020', 0, 0, 0],['3/2/2020', 1, 0, 0],['3/3/2020', 2, 0, 0],['3/4/2020', 2, 0, 0],['3/5/2020', 3, 0, 0],['3/6/2020', 3, 0, 0],['3/7/2020', 7, 0, 0],['3/8/2020', 10, 2, 0],['3/9/2020', 13, 2, 0],['3/10/2020', 15, 2, 0],['3/11/2020', 24, 2, 0],['3/12/2020', 50, 2, 0],['3/13/2020', 76, 3, 0],['3/14/2020', 78, 4, 0],['3/15/2020', 149, 5, 0],['3/16/2020', 162, 5, 0],['3/17/2020', 217, 7, 0],['3/18/2020', 328, 8, 0],['3/19/2020', 533, 9, 0],['3/20/2020', 664, 11, 0],['3/21/2020', 764, 13, 0],['3/22/2020', 1007, 13, 0],['3/23/2020', 1227, 18, 0],['3/24/2020', 1467, 23, 0],['3/25/2020', 1978, 23, 0],['3/26/2020', 2484, 29, 0],['3/27/2020', 3198, 46, 0],['3/28/2020', 4038, 56, 0],['3/29/2020', 4950, 60, 0],['3/30/2020', 5704, 71, 0],['3/31/2020', 6741, 85, 0],['4/1/2020', 7773, 101, 0],['4/2/2020', 9008, 144, 0],['4/3/2020', 10268, 170, 0],['4/4/2020', 11545, 195, 0],['4/5/2020', 12350, 221, 0],['4/6/2020', 13629, 254, 0],['4/7/2020', 14747, 296, 0],['4/8/2020', 15698, 323, 0],['4/9/2020', 16826, 371, 0],['4/10/2020', 17968, 419, 0],['4/11/2020', 18986, 446, 0],['4/12/2020', 19863, 461, 0],['4/13/2020', 21019, 499, 0],['4/14/2020', 21628, 571, 163],['4/15/2020', 22511, 596, 174],['4/16/2020', 23340, 668, 174],['4/17/2020', 24759, 726, 174],['4/18/2020', 25492, 748, 174],['4/19/2020', 26314, 774, 174],['4/20/2020', 27058, 823, 174],['4/21/2020', 27869, 867, 174],['4/22/2020', 28586, 927, 174],['4/23/2020', 29642, 987, 174],['4/24/2020', 30543, 1046, 174],['4/25/2020', 30840, 1055, 686],['4/26/2020', 31532, 1075, 686],['4/27/2020', 32139, 1088, 686],['4/28/2020', 32846, 1171, 686],['4/29/2020', 33193, 1218, 686],['4/30/2020', 33690, 1268, 686],['5/1/2020', 34562, 1309, 686],['5/2/2020', 35463, 1364, 686],['5/3/2020', 36078, 1379, 686],['5/4/2020', 36898, 1399, 686],['5/5/2020', 37439, 1471, 686],['5/6/2020', 38002, 1539, 686],['5/7/2020', 38828, 1600, 686],['5/8/2020', 39199, 1669, 686],['5/9/2020', 40001, 1716, 1046],['5/10/2020', 40596, 1722, 1046],['5/11/2020', 40982, 1735, 1046],
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
      [29.7938, -82.4944, "Alachua", 312, 5],[30.2752, -82.1603, "Baker", 25, 3],[30.2549, -85.9511, "Bay", 76, 3],[29.9474, -82.1129, "Bradford", 48, 2],[28.6928, -80.8468, "Brevard", 328, 9],[26.1901, -80.3659, "Broward", 5858, 257],[26.8946, -81.9098, "Charlotte", 329, 33],[28.8006, -82.3372, "Citrus", 106, 11],[30.0472, -81.7855, "Clay", 300, 19],[26.07, -81.4279, "Collier", 752, 27],[30.1855, -82.6026, "Columbia", 103, 2],[30.3165, -81.4118, "Duval", 1164, 29],[30.4158, -87.3028, "Escambia", 638, 18],[29.4198, -81.3235, "Flagler", 147, 4],[30.4992, -84.4582, "Gadsden", 128, 0],[26.8338, -81.0985, "Glades", 7, 1],[26.7325, -80.9518, "Hendry", 145, 5],[28.469, -82.5999, "Hernando", 100, 5],[27.5908, -81.5081, "Highlands", 98, 8],[27.9904, -82.3018, "Hillsborough", 1432, 37],[27.6378, -80.4855, "Indian River", 100, 8],[30.7943, -85.226, "Jackson", 91, 0],[29.1635, -81.5349, "Lake", 242, 14],[26.663, -81.9535, "Lee", 1268, 65],[30.4551, -84.2527, "Leon", 254, 6],[29.4479, -82.468, "Levy", 20, 0],[27.4799, -82.3452, "Manatee", 776, 74],[29.4494, -82.2211, "Marion", 210, 5],[27.2161, -80.24, "Martin", 255, 6],[25.5516, 80.6327, "Miami-Dade", 14007, 487],[25.2574, -80.3242, "Monroe", 89, 3],[30.5927, -81.8224, "Nassau", 60, 1],[30.5773, -86.6611, "Okaloosa", 169, 5],[28.4727, -81.4169, "Orange", 1505, 36],[28.3349, -81.3539, "Osceola", 572, 12],[26.6815, -80.1265, "Palm Beach", 3870, 237],[28.3232, -82.4319, "Pasco", 297, 9],[27.8764, -82.7779, "Pinellas", 861, 60],[27.8868, -81.8213, "Polk", 636, 33],[29.6502, -81.5998, "Putnam", 126, 4],[30.769, -86.9824, "Santa Rosa", 173, 9],[27.3328, -82.4616, "Sarasota", 426, 57],[28.7893, -81.276, "Seminole", 415, 11],[30.19, -81.3704, "St. Johns", 223, 4],[27.4096, -80.3538, "St. Lucie", 282, 25],[28.6335, -81.9986, "Sumter", 244, 14],[30.2956, -82.9847, "Suwannee", 146, 18],[29.028, -81.0755, "Volusia", 548, 28],[30.0282, -84.3936, "Wakulla", 29, 1],[30.9746, -86.3099, "Walton", 61, 2],[30.6332, -85.5874, "Washington", 12, 0],[30.7234, -85.9374, "Holmes", 10, 0],[30.5722, -85.1264, "Calhoun", 27, 0],[30.0638, -82.239, "Union", 6, 0],[30.1148, -85.1935, "Gulf", 1, 0],[30.4716, -83.413, "Madison", 61, 3],[27.5469, -81.8103, "Hardee", 36, 0],[27.2172, -80.7927, "Okeechobee", 28, 0],[29.652, -84.8881, "Franklin", 2, 0],[29.4498, -83.2819, "Dixie", 13, 0],[30.477, -83.7604, "Jefferson", 28, 2],[30.3317, -82.7562, "Hamilton", 18, 0],[27.2214, -81.8587, "DeSoto", 47, 5],[29.6795, -83.3837, "Taylor", 3, 0],[29.6092, -82.8146, "Gilchrist", 6, 0],[30.0511, -83.1768, "Lafayette", 3, 0],[30.3906, -84.9857, "Liberty", 198, 0],
    ]);
    var options = {
      backgroundColor: {fill:'transparent',stroke:'#FFF' ,strokeWidth:0 }, 
      displayMode: 'markers',
      region: 'US-FL', 
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
      [{v:"Alachua", f:"Alachua"}, 312, 0, 307, 5, 0, 0],[{v:"Baker", f:"Baker"}, 25, 0, 22, 3, 0, 0],[{v:"Bay", f:"Bay"}, 76, 0, 73, 3, 0, 0],[{v:"Bradford", f:"Bradford"}, 48, 0, 46, 2, 0, 0],[{v:"Brevard", f:"Brevard"}, 328, 0, 319, 9, 0, 0],[{v:"Broward", f:"Broward"}, 5858, 0, 5601, 257, 0, 0],[{v:"Charlotte", f:"Charlotte"}, 329, 0, 296, 33, 0, 0],[{v:"Citrus", f:"Citrus"}, 106, 0, 95, 11, 0, 0],[{v:"Clay", f:"Clay"}, 300, 0, 281, 19, 0, 0],[{v:"Collier", f:"Collier"}, 752, 0, 725, 27, 0, 0],[{v:"Columbia", f:"Columbia"}, 103, 0, 101, 2, 0, 0],[{v:"Duval", f:"Duval"}, 1164, 0, 1135, 29, 0, 0],[{v:"Escambia", f:"Escambia"}, 638, 0, 620, 18, 0, 0],[{v:"Flagler", f:"Flagler"}, 147, 0, 143, 4, 0, 0],[{v:"Gadsden", f:"Gadsden"}, 128, 0, 128, 0, 0, 0],[{v:"Glades", f:"Glades"}, 7, 0, 6, 1, 0, 0],[{v:"Hendry", f:"Hendry"}, 145, 0, 133, 5, 0, 7],[{v:"Hernando", f:"Hernando"}, 100, 0, 95, 5, 0, 0],[{v:"Highlands", f:"Highlands"}, 98, 0, 90, 8, 0, 0],[{v:"Hillsborough", f:"Hillsborough"}, 1432, 0, 1395, 37, 0, 0],[{v:"Indian River", f:"Indian River"}, 100, 0, 92, 8, 0, 0],[{v:"Jackson", f:"Jackson"}, 91, 0, 91, 0, 0, 0],[{v:"Lake", f:"Lake"}, 242, 0, 228, 14, 0, 0],[{v:"Lee", f:"Lee"}, 1268, 0, 1203, 65, 0, 0],[{v:"Leon", f:"Leon"}, 254, 0, 248, 6, 0, 0],[{v:"Levy", f:"Levy"}, 20, 0, 16, 0, 0, 4],[{v:"Manatee", f:"Manatee"}, 776, 0, 702, 74, 0, 0],[{v:"Marion", f:"Marion"}, 210, 0, 205, 5, 0, 0],[{v:"Martin", f:"Martin"}, 255, 0, 249, 6, 0, 0],[{v:"Miami-Dade", f:"Miami-Dade"}, 14007, 0, 13520, 487, 0, 0],[{v:"Monroe", f:"Monroe"}, 89, 0, 86, 3, 0, 0],[{v:"Nassau", f:"Nassau"}, 60, 0, 59, 1, 0, 0],[{v:"Okaloosa", f:"Okaloosa"}, 169, 0, 164, 5, 0, 0],[{v:"Orange", f:"Orange"}, 1505, 0, 1469, 36, 0, 0],[{v:"Osceola", f:"Osceola"}, 572, 0, 560, 12, 0, 0],[{v:"Palm Beach", f:"Palm Beach"}, 3870, 0, 3633, 237, 0, 0],[{v:"Pasco", f:"Pasco"}, 297, 0, 288, 9, 0, 0],[{v:"Pinellas", f:"Pinellas"}, 861, 0, 801, 60, 0, 0],[{v:"Polk", f:"Polk"}, 636, 0, 603, 33, 0, 0],[{v:"Putnam", f:"Putnam"}, 126, 0, 122, 4, 0, 0],[{v:"Santa Rosa", f:"Santa Rosa"}, 173, 0, 164, 9, 0, 0],[{v:"Sarasota", f:"Sarasota"}, 426, 0, 369, 57, 0, 0],[{v:"Seminole", f:"Seminole"}, 415, 0, 241, 11, 0, 163],[{v:"St. Johns", f:"St. Johns"}, 223, 0, 219, 4, 0, 0],[{v:"St. Lucie", f:"St. Lucie"}, 282, 0, 257, 25, 0, 0],[{v:"Sumter", f:"Sumter"}, 244, 0, 230, 14, 0, 0],[{v:"Suwannee", f:"Suwannee"}, 146, 0, 128, 18, 0, 0],[{v:"Volusia", f:"Volusia"}, 548, 0, 520, 28, 0, 0],[{v:"Wakulla", f:"Wakulla"}, 29, 0, 28, 1, 0, 0],[{v:"Walton", f:"Walton"}, 61, 0, 59, 2, 0, 0],[{v:"Washington", f:"Washington"}, 12, 0, 12, 0, 0, 0],[{v:"Holmes", f:"Holmes"}, 10, 0, 10, 0, 0, 0],[{v:"Calhoun", f:"Calhoun"}, 27, 0, 27, 0, 0, 0],[{v:"Union", f:"Union"}, 6, 0, 6, 0, 0, 0],[{v:"Gulf", f:"Gulf"}, 1, 0, 1, 0, 0, 0],[{v:"Madison", f:"Madison"}, 61, 0, 58, 3, 0, 0],[{v:"Hardee", f:"Hardee"}, 36, 0, 36, 0, 0, 0],[{v:"Okeechobee", f:"Okeechobee"}, 28, 0, 28, 0, 0, 0],[{v:"Franklin", f:"Franklin"}, 2, 0, 2, 0, 0, 0],[{v:"Dixie", f:"Dixie"}, 13, 0, 13, 0, 0, 0],[{v:"Jefferson", f:"Jefferson"}, 28, 0, 26, 2, 0, 0],[{v:"Hamilton", f:"Hamilton"}, 18, 0, 18, 0, 0, 0],[{v:"DeSoto", f:"DeSoto"}, 47, 0, 42, 5, 0, 0],[{v:"Taylor", f:"Taylor"}, 3, 0, 3, 0, 0, 0],[{v:"Gilchrist", f:"Gilchrist"}, 6, 0, 6, 0, 0, 0],[{v:"Lafayette", f:"Lafayette"}, 3, 0, 3, 0, 0, 0],[{v:"Liberty", f:"Liberty"}, 198, 0, 198, 0, 0, 0],
    ]);
    data.setProperty(0, 0, 'style', 'min-width:100px');
    var table = new google.visualization.Table(document.getElementById('geo_table'));
    table.draw(data, {allowHtml: true, sortColumn: 2, sortAscending: false, width: '660px', height: '100%'});
  }
</script>

<span style="font-size: 13px">All COVID-19 data displayed on the page is available through our FREE <a href="https://developer.smartable.ai">API program</a>. This US - Florida State Coronavirus (COVID-19) Live Stats is refreshed every hour using credible data sources, including the country/state's official government website, <a href="https://en.wikipedia.org/wiki/2019%E2%80%9320_coronavirus_pandemic" target="_blank">data available on wikipedia pages</a>, latest news reports, <a href="https://systems.jhu.edu/research/public-health/ncov/" target="_blank">Johns Hopkins University CSSE 2019-nCoV Dashboard</a>, <a href="https://www.who.int/emergencies/diseases/novel-coronavirus-2019/situation-reports" target="_blank">WHO Situation Reports</a>, <a href="https://www.cdc.gov/coronavirus/2019-ncov/index.html" target="_blank">CDC Situation Updates</a>, and <a href="https://ncov.dxy.cn/ncovh5/view/pneumonia" target="_blank">DXY.cn</a>.</span>

<h2 id="news" class="center" style="margin-top: 60px; font-size: 25px;">Local Government Help Information</h2>
<div class="info center">
<a href="http://www.floridahealth.gov/diseases-and-conditions/COVID-19/" target="_blank">Florida Department of Health</a> 407-723-5004
</div>
<h2 id="news" class="center" style="margin-top: 60px; font-size: 25px;">Trending Coronavirus News in US-Florida</h2>
<div class="row">
<div class="col-md-6 col-sm-12">
  <div class="content-card">
	<a href="https://www.cnn.com/us/live-news/us-coronavirus-update-05-08-20/h_beb73d006f4333247f560b87a92175fc"><div class="card-image" style="background-image: url(https://cdn.cnn.com/cnnnext/dam/assets/200213175739-03-coronavirus-0213-super-tease.jpg)"></div></a>
	<div class="content">
		<div class="card-title"><a href="https://www.cnn.com/us/live-news/us-coronavirus-update-05-08-20/h_beb73d006f4333247f560b87a92175fc">Barbershops and salons can reopen Monday in most of Florida, DeSantis says</a></div>
		<div class="card-excerpt">They can operate under “enhanced safety protocols,” but the governor has not defined those protocols. Other states have clear guidelines.</div>
		<div class="card-meta">
			<span class="card-provider">Tampa Bay Times</span> • <span class="card-date">5/9/2020</span>
		</div>
	</div>
  </div>
</div>
<div class="col-md-6 col-sm-12">
  <div class="content-card">
	<a href="https://www.cnn.com/us/live-news/us-coronavirus-update-05-08-20/h_c1e1dc774839f57d49718f5f0aa1cfe1"><div class="card-image" style="background-image: url(https://dynaimage.cdn.cnn.com/cnn/digital-images/w_900,h_601/6c47ecdf-6510-4cc4-802f-aba30a590622.jpg)"></div></a>
	<div class="content">
		<div class="card-title"><a href="https://www.cnn.com/us/live-news/us-coronavirus-update-05-08-20/h_c1e1dc774839f57d49718f5f0aa1cfe1">New nursing facility near JU taking in long-term care patients with COVID-19</a></div>
		<div class="card-excerpt">A new skilled nursing facility near the campus of Jacksonville University is partnering with the state to accept long-term care residents with COVID-19. Dolphin Pointe Health Care is working with the Florida Agency for Health Care Administration to isolate contagious COVID-19 patients that don’t require hospitalization,</div>
		<div class="card-meta">
			<span class="card-provider">Jacksonville Daily Record</span> • <span class="card-date">5/8/2020</span>
		</div>
	</div>
  </div>
</div>
<div class="col-md-6 col-sm-12">
  <div class="content-card">
	<a href="https://www.palmbeachpost.com/news/20200508/coronavirus-florida-gardens-mall-set-to-reopen-may-15"><div class="card-image" style="background-image: url(https://www.palmbeachpost.com/apps/pbcsi.dll/bilde?Site=LK&Date=20200508&Category=NEWS&ArtNo=200508175&Ref=AR)"></div></a>
	<div class="content">
		<div class="card-title"><a href="https://www.palmbeachpost.com/news/20200508/coronavirus-florida-gardens-mall-set-to-reopen-may-15">Coronavirus Florida: Gardens Mall set to reopen May 15</a></div>
		<div class="card-excerpt">The Palm Beach Post will continue to provide essential coverage of the coronavirus for free. You can have coronavirus news delivered directly to your inbox by signing up for our Coronavirus Newsletter.</div>
		<div class="card-meta">
			<span class="card-provider">Palm Beach Post</span> • <span class="card-date">5/8/2020</span>
		</div>
	</div>
  </div>
</div>
<div class="col-md-6 col-sm-12">
  <div class="content-card">
	<a href="https://www.cnn.com/us/live-news/us-coronavirus-update-05-08-20/h_a74afe094b96b31a0296c1322979bb8e"><div class="card-image" style="background-image: url(https://cdn.cnn.com/cnnnext/dam/assets/200213175739-03-coronavirus-0213-super-tease.jpg)"></div></a>
	<div class="content">
		<div class="card-title"><a href="https://www.cnn.com/us/live-news/us-coronavirus-update-05-08-20/h_a74afe094b96b31a0296c1322979bb8e">Coronavirus Florida: County beaches to reopen May 18 under county plan</a></div>
		<div class="card-excerpt">This content is being provided for free as a public service to our readers during the coronavirus outbreak. Please support local journalism by subscribing to The Palm Beach Post. If you want breaking coronavirus news directly in your inbox,</div>
		<div class="card-meta">
			<span class="card-provider">Palm Beach Post</span> • <span class="card-date">5/8/2020</span>
		</div>
	</div>
  </div>
</div>
<div class="col-md-6 col-sm-12">
  <div class="content-card">
	<a href="https://www.cnn.com/videos/us/2020/05/08/florida-man-grocery-store-tirade-miami-beach-mxp-vpx.hln"><div class="card-image" style="background-image: url(https://cdn.cnn.com/cnnnext/dam/assets/200508033357-florida-man-yells-fake-pandemic-super-tease.jpg)"></div></a>
	<div class="content">
		<div class="card-title"><a href="https://www.cnn.com/videos/us/2020/05/08/florida-man-grocery-store-tirade-miami-beach-mxp-vpx.hln">Florida man calls the coronavirus 'fake pandemic' in tirade</a></div>
		<div class="card-excerpt">Footage of a man in Florida shows him screaming at an officer outside a Miami Beach grocery store after he resisted wearing a mask.</div>
		<div class="card-meta">
			<span class="card-provider">CNN</span> • <span class="card-date">5/8/2020</span>
		</div>
	</div>
  </div>
</div>
<div class="col-md-6 col-sm-12">
  <div class="content-card">
	<a href="https://www.orlandosentinel.com/coronavirus/os-ne-coronavirus-third-state-inmate-dies-florida-corrections-20200416-baffem42szetpkevbgyg3yopze-story.html"><div class="card-image" style="background-image: url(https://www.orlandosentinel.com/resizer/8kjjWwq6vDvUAf0sAvPO7hlxruU=/1200x0/top/arc-anglerfish-arc2-prod-tronc.s3.amazonaws.com/public/GHXR5JBTTFAKHJ4ASOUGMO6SGM.JPG)"></div></a>
	<div class="content">
		<div class="card-title"><a href="https://www.orlandosentinel.com/coronavirus/os-ne-coronavirus-third-state-inmate-dies-florida-corrections-20200416-baffem42szetpkevbgyg3yopze-story.html">Coronavirus testing at most Florida prisons remains limited, especially at privately run facilities</a></div>
		<div class="card-excerpt">While the state corrections department has recently expanded testing to include some asymptomatic inmates at the three prisons with the largest confirmed outbreaks, testing remains limited beyond those facilities — especially at some privately run prisons.</div>
		<div class="card-meta">
			<span class="card-provider">Orlando Sentinel</span> • <span class="card-date">5/8/2020</span>
		</div>
	</div>
  </div>
</div>
<div class="col-md-6 col-sm-12">
  <div class="content-card">
	<a href="https://www.cnn.com/us/live-news/us-coronavirus-update-04-24-20/h_b44f4acb29e965d27f24f88f2faac123"><div class="card-image" style="background-image: url(https://cdn.cnn.com/cnnnext/dam/assets/200213175739-03-coronavirus-0213-super-tease.jpg)"></div></a>
	<div class="content">
		<div class="card-title"><a href="https://www.cnn.com/us/live-news/us-coronavirus-update-04-24-20/h_b44f4acb29e965d27f24f88f2faac123">Let us reopen: Palm Beach County makes its plea to the governor</a></div>
		<div class="card-excerpt">Palm Beach County sent Gov. Ron DeSantis a letter Thursday asking for him to consider easing coronavirus restrictions in the county.</div>
		<div class="card-meta">
			<span class="card-provider">Sun Sentinel</span> • <span class="card-date">5/7/2020</span>
		</div>
	</div>
  </div>
</div>
<div class="col-md-6 col-sm-12">
  <div class="content-card">
	<a href="https://www.washingtonpost.com/politics/a-mall-in-florida-has-reopened--steps-away-from-a-coronavirus-testing-facility/2020/05/07/595483e2-8fca-11ea-a9c0-73b93422d691_story.html"><div class="card-image" style="background-image: url(https://www.washingtonpost.com/resizer/kLtN8dhzjqTRQP38Nj_0HsSlL8A=/1440x0/smart/arc-anglerfish-washpost-prod-washpost.s3.amazonaws.com/public/XKMT4ZEQZUI6VKOAOO4TIIWWSE.jpg)"></div></a>
	<div class="content">
		<div class="card-title"><a href="https://www.washingtonpost.com/politics/a-mall-in-florida-has-reopened--steps-away-from-a-coronavirus-testing-facility/2020/05/07/595483e2-8fca-11ea-a9c0-73b93422d691_story.html">A mall in Florida has reopened — steps away from a coronavirus testing facility</a></div>
		<div class="card-excerpt">The mall is emblematic of retail outlets, restaurants and other businesses that have started to resume business amid the covid-19 pandemic.</div>
		<div class="card-meta">
			<span class="card-provider">Washington Post</span> • <span class="card-date">5/7/2020</span>
		</div>
	</div>
  </div>
</div>
<div class="col-md-6 col-sm-12">
  <div class="content-card">
	<a href="https://www.cnn.com/us/live-news/us-coronavirus-update-05-07-20/h_2eb36420707fc1ccc49f1f8e9f9e585c"><div class="card-image" style="background-image: url(https://cdn.cnn.com/cnnnext/dam/assets/200213175739-03-coronavirus-0213-super-tease.jpg)"></div></a>
	<div class="content">
		<div class="card-title"><a href="https://www.cnn.com/us/live-news/us-coronavirus-update-05-07-20/h_2eb36420707fc1ccc49f1f8e9f9e585c">Miami Beach extends its emergency orders one more week</a></div>
		<div class="card-excerpt">Miami Beach commissioners may be eager for businesses to reopen, but the city isn’t budging. Today, the city manager extended his State of Emergency Declaration</div>
		<div class="card-meta">
			<span class="card-provider">Time Out</span> • <span class="card-date">5/7/2020</span>
		</div>
	</div>
  </div>
</div>
<div class="col-md-6 col-sm-12">
  <div class="content-card">
	<a href="https://www.cnn.com/us/live-news/us-coronavirus-update-05-08-20/h_c1e1dc774839f57d49718f5f0aa1cfe1"><div class="card-image" style="background-image: url(https://cdn.cnn.com/cnnnext/dam/assets/200213175739-03-coronavirus-0213-super-tease.jpg)"></div></a>
	<div class="content">
		<div class="card-title"><a href="https://www.cnn.com/us/live-news/us-coronavirus-update-05-08-20/h_c1e1dc774839f57d49718f5f0aa1cfe1">State’s COVID-19 testing policy an ‘unmitigated disaster’ for residents of elder homes</a></div>
		<div class="card-excerpt">On March 12, three days before state officials took any formal action against the emerging coronavirus pandemic, Doug Adkins put his 155-bed assisted living facility on full lock down.</div>
		<div class="card-meta">
			<span class="card-provider">Miami Herald</span> • <span class="card-date">5/7/2020</span>
		</div>
	</div>
  </div>
</div>

</div>

