---
category: stats
title: "US - Wisconsin State Coronavirus (COVID-19) Live Stats"
excerpt: "Live stats of COVID-19 in US-Wisconsin. Total Cases: 10421 (-), Deaths: 410 (+1), Recoveries: 5014(-)."
publishedDateTime: 2020-05-12T17:45:10Z
updatedDateTime: 2020-05-12T17:45:10Z
webUrl: "https://smartable.ai/apps/coronavirus/stats/us-wi/"
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
  - url: "https://smartable.azureedge.net/coronavirus/sites/2/2020/us-wi.jpg"
    width: 900
    height: 564
    title: "US - Wisconsin State Coronavirus (COVID-19) Live Stats"

---
<div class="total-stats" style="text-align: center;">
    <h3>
	    <div style="font-size: 18px; font-weight: 400;">Total Confirmed Cases:</div>
	    10421 (-)
    </h3>
    <h3>
	    <div style="font-size: 18px; font-weight: 400;">Total Deaths:</div>
	    410 (<span class='red'>+1</span>)
    </h3>
    <h3>
	    <div style="font-size: 18px; font-weight: 400;">Total Recovered:</div>
	    5014 (-)
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
      ['1/22/2020', 0, 0, 0],['1/23/2020', 0, 0, 0],['1/24/2020', 0, 0, 0],['1/25/2020', 0, 0, 0],['1/26/2020', 0, 0, 0],['1/27/2020', 0, 0, 0],['1/28/2020', 0, 0, 0],['1/29/2020', 0, 0, 0],['1/30/2020', 0, 0, 0],['1/31/2020', 0, 0, 0],['2/1/2020', 0, 0, 0],['2/2/2020', 0, 0, 0],['2/3/2020', 0, 0, 0],['2/4/2020', 0, 0, 0],['2/5/2020', 0, 0, 0],['2/6/2020', 0, 0, 0],['2/7/2020', 0, 0, 0],['2/8/2020', 0, 0, 0],['2/9/2020', 0, 0, 0],['2/10/2020', 0, 0, 0],['2/11/2020', 0, 0, 0],['2/12/2020', 0, 0, 0],['2/13/2020', 0, 0, 0],['2/14/2020', 0, 0, 0],['2/15/2020', 0, 0, 0],['2/16/2020', 0, 0, 0],['2/17/2020', 0, 0, 0],['2/18/2020', 0, 0, 0],['2/19/2020', 0, 0, 0],['2/20/2020', 0, 0, 0],['2/21/2020', 0, 0, 0],['2/22/2020', 0, 0, 0],['2/23/2020', 0, 0, 0],['2/24/2020', 0, 0, 0],['2/25/2020', 0, 0, 0],['2/26/2020', 0, 0, 0],['2/27/2020', 0, 0, 0],['2/28/2020', 0, 0, 0],['2/29/2020', 0, 0, 0],['3/1/2020', 0, 0, 0],['3/2/2020', 0, 0, 0],['3/3/2020', 0, 0, 0],['3/4/2020', 0, 0, 0],['3/5/2020', 0, 0, 0],['3/6/2020', 0, 0, 0],['3/7/2020', 0, 0, 0],['3/8/2020', 0, 0, 0],['3/9/2020', 0, 0, 0],['3/10/2020', 3, 0, 0],['3/11/2020', 4, 0, 1],['3/12/2020', 8, 0, 1],['3/13/2020', 29, 0, 1],['3/14/2020', 37, 0, 1],['3/15/2020', 34, 0, 1],['3/16/2020', 48, 0, 1],['3/17/2020', 90, 0, 1],['3/18/2020', 114, 0, 1],['3/19/2020', 160, 2, 1],['3/20/2020', 219, 3, 1],['3/21/2020', 282, 4, 1],['3/22/2020', 383, 4, 1],['3/23/2020', 425, 5, 1],['3/24/2020', 481, 5, 1],['3/25/2020', 638, 7, 1],['3/26/2020', 728, 10, 1],['3/27/2020', 926, 14, 1],['3/28/2020', 1055, 17, 1],['3/29/2020', 1164, 18, 1],['3/30/2020', 1285, 24, 1],['3/31/2020', 1412, 25, 1],['4/1/2020', 1568, 28, 1],['4/2/2020', 1741, 38, 1],['4/3/2020', 1998, 51, 1],['4/4/2020', 2128, 60, 1],['4/5/2020', 2320, 75, 1],['4/6/2020', 2511, 85, 1],['4/7/2020', 2578, 93, 1],['4/8/2020', 2812, 103, 65],['4/9/2020', 2890, 111, 84],['4/10/2020', 3068, 128, 84],['4/11/2020', 3213, 137, 84],['4/12/2020', 3341, 144, 84],['4/13/2020', 3428, 155, 87],['4/14/2020', 3555, 170, 87],['4/15/2020', 3721, 183, 87],['4/16/2020', 3876, 197, 93],['4/17/2020', 4053, 206, 135],['4/18/2020', 4199, 212, 194],['4/19/2020', 4346, 220, 196],['4/20/2020', 4541, 234, 196],['4/21/2020', 4625, 244, 196],['4/22/2020', 4845, 248, 196],['4/23/2020', 5052, 258, 196],['4/24/2020', 5356, 263, 196],['4/25/2020', 5689, 267, 2313],['4/26/2020', 5913, 273, 2313],['4/27/2020', 6083, 282, 2313],['4/28/2020', 6291, 300, 2313],['4/29/2020', 6522, 308, 3210],['4/30/2020', 6854, 316, 3210],['5/1/2020', 7250, 322, 3210],['5/2/2020', 7661, 335, 3210],['5/3/2020', 7965, 340, 3723],['5/4/2020', 8237, 341, 3973],['5/5/2020', 8567, 354, 4131],['5/6/2020', 8902, 363, 4348],['5/7/2020', 9218, 375, 4348],['5/8/2020', 9593, 384, 4348],['5/9/2020', 9941, 398, 4348],['5/10/2020', 10221, 401, 5014],['5/11/2020', 10421, 409, 5014],['5/12/2020', 10421, 410, 5014],
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
      [46.4354, -91.06, "Bayfield", 3, 1],[44.317, -88.0972, "Brown", 1924, 18],[43.9491, -88.0942, "Calumet", 41, 1],[45.1988, -91.5666, "Chippewa", 30, 0],[44.5605, -90.5905, "Clark", 24, 4],[43.3154, -89.5367, "Columbia", 32, 1],[43.0186, -89.5498, "Dane", 474, 23],[43.5271, -88.5615, "Dodge", 74, 1],[46.2409, -91.7995, "Douglas", 11, 0],[44.8893, -91.9084, "Dunn", 14, 0],[44.803, -91.4387, "Eau Claire", 57, 0],[43.8377, -88.3465, "Fond du Lac", 101, 3],[42.9793, -90.6491, "Grant", 68, 9],[42.6168, -89.3756, "Green", 33, 0],[42.8419, -90.3961, "Iowa", 10, 0],[46.4104, -90.2695, "Iron", 2, 1],[44.2981, -90.8419, "Jackson", 14, 1],[43.0165, -88.6999, "Jefferson", 51, 2],[43.6531, -90.2239, "Juneau", 21, 1],[42.5707, -88.1044, "Kenosha", 693, 16],[43.9075, -90.9165, "La Crosse", 33, 0],[44.9615, -89.6457, "Marathon", 25, 1],[45.0556, -87.7476, "Marinette", 21, 1],[43.7653, -89.4599, "Marquette", 3, 1],[42.937, -88.0018, "Milwaukee", 4022, 231],[43.8132, -90.5268, "Monroe", 15, 1],[45.8047, -89.1708, "Oneida", 7, 0],[44.4449, -88.5768, "Outagamie", 117, 2],[43.3847, -87.9439, "Ozaukee", 107, 9],[44.7509, -92.3814, "Pierce", 13, 0],[44.2607, -89.4087, "Portage", 7, 0],[42.8088, -88.215, "Racine", 724, 16],[43.1857, -90.2012, "Richland", 13, 2],[42.8386, -89.0698, "Rock", 361, 13],[43.4814, -89.7719, "Sauk", 72, 3],[43.6766, -87.9478, "Sheboygan", 66, 2],[44.9691, -92.4381, "St. Croix", 29, 0],[45.991, -89.5332, "Vilas", 4, 0],[42.8372, -88.734, "Walworth", 240, 10],[43.4204, -88.3443, "Washington", 118, 4],[43.1229, -88.3838, "Waukesha", 409, 23],[44.395, -88.7394, "Waupaca", 13, 1],[44.0391, -88.7378, "Winnebago", 100, 1],[44.6057, -89.8549, "Wood", 4, 0],[46.5986, -90.6618, "Ashland", 2, 0],[44.4214, -92.0044, "Buffalo", 6, 1],[45.0659, -87.133, "Door", 22, 3],[45.3006, -88.5146, "Oconto", 28, 0],[43.3516, -91.0935, "Crawford", 17, 0],[44.0253, -89.8861, "Adams", 4, 1],[44.9347, -88.7334, "Menominee", 2, 0],[44.3705, -91.3476, "Trempealeau", 5, 0],[45.5353, -92.0269, "Barron", 12, 0],[45.459, -91.2734, "Rusk", 4, 0],[44.1525, -87.9517, "Manitowoc", 19, 1],[45.0046, -89.0411, "Shawano", 25, 0],[45.8431, -88.6673, "Florence", 2, 0],[44.1788, -89.2442, "Waushara", 4, 0],[44.4607, -87.5133, "Kewaunee", 29, 1],[42.5801, -90.0235, "Lafayette", 13, 0],[45.7976, -91.3005, "Sawyer", 4, 0],[45.7159, -92.3965, "Polk", 5, 0],[45.5301, -90.5868, "Price", 1, 0],[43.9704, -88.9505, "Green Lake", 8, 0],[45.8445, -91.5502, "Washburn", 1, 0],[43.5576968, -90.8294002, "Vernon", 3, 0],[45.3743102, -89.7725799, "Lincoln", 1, 0],[45.6704497, -88.8375807, "Forest", 4, 0],
    ]);
    var options = {
      backgroundColor: {fill:'transparent',stroke:'#FFF' ,strokeWidth:0 }, 
      displayMode: 'markers',
      region: 'US-WI', 
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
      [{v:"Bayfield", f:"Bayfield"}, 3, 0, 2, 1, 0, 0],[{v:"Brown", f:"Brown"}, 1924, 0, 1906, 18, 0, 0],[{v:"Calumet", f:"Calumet"}, 41, 0, 40, 1, 0, 0],[{v:"Chippewa", f:"Chippewa"}, 30, 0, 30, 0, 0, 0],[{v:"Clark", f:"Clark"}, 24, 0, 20, 4, 0, 0],[{v:"Columbia", f:"Columbia"}, 32, 0, 31, 1, 0, 0],[{v:"Dane", f:"Dane"}, 474, 0, 450, 23, 0, 1],[{v:"Dodge", f:"Dodge"}, 74, 0, 73, 1, 0, 0],[{v:"Douglas", f:"Douglas"}, 11, 0, 11, 0, 0, 0],[{v:"Dunn", f:"Dunn"}, 14, 0, 14, 0, 0, 0],[{v:"Eau Claire", f:"Eau Claire"}, 57, 0, 57, 0, 0, 0],[{v:"Fond du Lac", f:"Fond du Lac"}, 101, 0, 98, 3, 0, 0],[{v:"Grant", f:"Grant"}, 68, 0, 59, 9, 2, 0],[{v:"Green", f:"Green"}, 33, 0, 33, 0, 0, 0],[{v:"Iowa", f:"Iowa"}, 10, 0, 10, 0, 0, 0],[{v:"Iron", f:"Iron"}, 2, 0, 1, 1, 0, 0],[{v:"Jackson", f:"Jackson"}, 14, 0, 13, 1, 0, 0],[{v:"Jefferson", f:"Jefferson"}, 51, 0, 49, 2, 0, 0],[{v:"Juneau", f:"Juneau"}, 21, 0, 20, 1, 0, 0],[{v:"Kenosha", f:"Kenosha"}, 693, 0, 677, 16, 0, 0],[{v:"La Crosse", f:"La Crosse"}, 33, 0, 10, 0, 0, 23],[{v:"Marathon", f:"Marathon"}, 25, 0, 24, 1, 0, 0],[{v:"Marinette", f:"Marinette"}, 21, 0, 20, 1, 0, 0],[{v:"Marquette", f:"Marquette"}, 3, 0, 2, 1, 0, 0],[{v:"Milwaukee", f:"Milwaukee"}, 4022, 0, 3791, 231, 0, 0],[{v:"Monroe", f:"Monroe"}, 15, 0, 7, 1, 0, 7],[{v:"Oneida", f:"Oneida"}, 7, 0, 7, 0, 0, 0],[{v:"Outagamie", f:"Outagamie"}, 117, 0, 115, 2, 0, 0],[{v:"Ozaukee", f:"Ozaukee"}, 107, 0, 98, 9, 0, 0],[{v:"Pierce", f:"Pierce"}, 13, 0, 13, 0, 0, 0],[{v:"Portage", f:"Portage"}, 7, 0, 7, 0, 0, 0],[{v:"Racine", f:"Racine"}, 724, 0, 708, 16, 0, 0],[{v:"Richland", f:"Richland"}, 13, 0, 11, 2, 0, 0],[{v:"Rock", f:"Rock"}, 361, 0, 348, 13, 0, 0],[{v:"Sauk", f:"Sauk"}, 72, 0, 69, 3, 0, 0],[{v:"Sheboygan", f:"Sheboygan"}, 66, 0, 37, 2, 0, 27],[{v:"St. Croix", f:"St. Croix"}, 29, 0, 29, 0, 0, 0],[{v:"Vilas", f:"Vilas"}, 4, 0, 4, 0, 0, 0],[{v:"Walworth", f:"Walworth"}, 240, 0, 212, 10, 0, 18],[{v:"Washington", f:"Washington"}, 118, 0, 114, 4, 0, 0],[{v:"Waukesha", f:"Waukesha"}, 409, 0, 266, 23, 0, 120],[{v:"Waupaca", f:"Waupaca"}, 13, 0, 12, 1, 0, 0],[{v:"Winnebago", f:"Winnebago"}, 100, 0, 99, 1, 0, 0],[{v:"Wood", f:"Wood"}, 4, 0, 4, 0, 0, 0],[{v:"Ashland", f:"Ashland"}, 2, 0, 2, 0, 0, 0],[{v:"Buffalo", f:"Buffalo"}, 6, 0, 5, 1, 0, 0],[{v:"Door", f:"Door"}, 22, 0, 19, 3, 0, 0],[{v:"Oconto", f:"Oconto"}, 28, 0, 28, 0, 0, 0],[{v:"Crawford", f:"Crawford"}, 17, 0, 17, 0, 0, 0],[{v:"Adams", f:"Adams"}, 4, 0, 3, 1, 0, 0],[{v:"Menominee", f:"Menominee"}, 2, 0, 2, 0, 0, 0],[{v:"Trempealeau", f:"Trempealeau"}, 5, 0, 5, 0, 0, 0],[{v:"Barron", f:"Barron"}, 12, 0, 12, 0, 0, 0],[{v:"Rusk", f:"Rusk"}, 4, 0, 4, 0, 0, 0],[{v:"Manitowoc", f:"Manitowoc"}, 19, 0, 18, 1, 0, 0],[{v:"Shawano", f:"Shawano"}, 25, 0, 25, 0, 0, 0],[{v:"Florence", f:"Florence"}, 2, 0, 2, 0, 0, 0],[{v:"Waushara", f:"Waushara"}, 4, 0, 4, 0, 0, 0],[{v:"Kewaunee", f:"Kewaunee"}, 29, 0, 28, 1, 0, 0],[{v:"Lafayette", f:"Lafayette"}, 13, 0, 13, 0, 0, 0],[{v:"Sawyer", f:"Sawyer"}, 4, 0, 4, 0, 0, 0],[{v:"Polk", f:"Polk"}, 5, 0, 5, 0, 0, 0],[{v:"Price", f:"Price"}, 1, 0, 1, 0, 0, 0],[{v:"Green Lake", f:"Green Lake"}, 8, 0, 8, 0, 0, 0],[{v:"Washburn", f:"Washburn"}, 1, 0, 1, 0, 0, 0],[{v:"Vernon", f:"Vernon"}, 3, 0, 3, 0, 0, 0],[{v:"Lincoln", f:"Lincoln"}, 1, 0, 1, 0, 0, 0],[{v:"Forest", f:"Forest"}, 4, 0, 4, 0, 0, 0],
    ]);
    data.setProperty(0, 0, 'style', 'min-width:100px');
    var table = new google.visualization.Table(document.getElementById('geo_table'));
    table.draw(data, {allowHtml: true, sortColumn: 2, sortAscending: false, width: '660px', height: '100%'});
  }
</script>

<span style="font-size: 13px">All COVID-19 data displayed on the page is available through our FREE <a href="https://developer.smartable.ai">API program</a>. This US - Wisconsin State Coronavirus (COVID-19) Live Stats is refreshed every hour using credible data sources, including the country/state's official government website, <a href="https://en.wikipedia.org/wiki/2019%E2%80%9320_coronavirus_pandemic" target="_blank">data available on wikipedia pages</a>, latest news reports, <a href="https://systems.jhu.edu/research/public-health/ncov/" target="_blank">Johns Hopkins University CSSE 2019-nCoV Dashboard</a>, <a href="https://www.who.int/emergencies/diseases/novel-coronavirus-2019/situation-reports" target="_blank">WHO Situation Reports</a>, <a href="https://www.cdc.gov/coronavirus/2019-ncov/index.html" target="_blank">CDC Situation Updates</a>, and <a href="https://ncov.dxy.cn/ncovh5/view/pneumonia" target="_blank">DXY.cn</a>.</span>

<h2 id="news" class="center" style="margin-top: 60px; font-size: 25px;">Local Government Help Information</h2>
<div class="info center">
<a href="https://www.dhs.wisconsin.gov/disease/covid-19.htm" target="_blank">Wisconsin Department of Health Services</a>
</div>
<h2 id="news" class="center" style="margin-top: 60px; font-size: 25px;">Trending Coronavirus News in US-Wisconsin</h2>
<div class="row">
<div class="col-md-6 col-sm-12">
  <div class="content-card">
	<a href="https://www.usatoday.com/story/news/politics/2020/05/07/coronavirus-wisconsin-plans-free-testing-minority-communities/3092830001/"><div class="card-image" style="background-image: url(https://www.gannett-cdn.com/presto/2020/04/27/PMJS/dc6b6efb-10a0-43be-9a07-37c59820ed62-Corona_TEST_00708.JPG?auto=webp&crop=3899,2194,x0,y0&format=pjpg&width=1200)"></div></a>
	<div class="content">
		<div class="card-title"><a href="https://www.usatoday.com/story/news/politics/2020/05/07/coronavirus-wisconsin-plans-free-testing-minority-communities/3092830001/">Wisconsin governor plans free coronavirus testing for all African Americans, Latinos</a></div>
		<div class="card-excerpt">Gov. Tony Evers' plan is an effort to combat the staggering racial and ethnic disparities Wisconsin and many other states are facing.</div>
		<div class="card-meta">
			<span class="card-provider">USA Today</span> • <span class="card-date">5/7/2020</span>
		</div>
	</div>
  </div>
</div>

</div>

