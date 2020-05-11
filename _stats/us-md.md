---
category: stats
title: "US - Maryland State Coronavirus (COVID-19) Live Stats"
excerpt: "Live stats of COVID-19 in US-Maryland. Total Cases: 33373 (+786), Deaths: 1683 (+39), Recoveries: 2041(-)."
publishedDateTime: 2020-05-11T23:45:10Z
updatedDateTime: 2020-05-11T23:45:10Z
webUrl: "https://smartable.ai/apps/coronavirus/stats/us-md/"
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
  - url: "https://smartable.azureedge.net/coronavirus/sites/2/2020/us-md.jpg"
    width: 900
    height: 564
    title: "US - Maryland State Coronavirus (COVID-19) Live Stats"

---
<div class="total-stats" style="text-align: center;">
    <h3>
	    <div style="font-size: 18px; font-weight: 400;">Total Confirmed Cases:</div>
	    33373 (<span class='red'>+786</span>)
    </h3>
    <h3>
	    <div style="font-size: 18px; font-weight: 400;">Total Deaths:</div>
	    1683 (<span class='red'>+39</span>)
    </h3>
    <h3>
	    <div style="font-size: 18px; font-weight: 400;">Total Recovered:</div>
	    2041 (-)
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
      ['1/22/2020', 0, 0, 0],['1/23/2020', 0, 0, 0],['1/24/2020', 0, 0, 0],['1/25/2020', 0, 0, 0],['1/26/2020', 0, 0, 0],['1/27/2020', 0, 0, 0],['1/28/2020', 0, 0, 0],['1/29/2020', 0, 0, 0],['1/30/2020', 0, 0, 0],['1/31/2020', 0, 0, 0],['2/1/2020', 0, 0, 0],['2/2/2020', 0, 0, 0],['2/3/2020', 0, 0, 0],['2/4/2020', 0, 0, 0],['2/5/2020', 0, 0, 0],['2/6/2020', 0, 0, 0],['2/7/2020', 0, 0, 0],['2/8/2020', 0, 0, 0],['2/9/2020', 0, 0, 0],['2/10/2020', 0, 0, 0],['2/11/2020', 0, 0, 0],['2/12/2020', 0, 0, 0],['2/13/2020', 0, 0, 0],['2/14/2020', 0, 0, 0],['2/15/2020', 0, 0, 0],['2/16/2020', 0, 0, 0],['2/17/2020', 0, 0, 0],['2/18/2020', 0, 0, 0],['2/19/2020', 0, 0, 0],['2/20/2020', 0, 0, 0],['2/21/2020', 0, 0, 0],['2/22/2020', 0, 0, 0],['2/23/2020', 0, 0, 0],['2/24/2020', 0, 0, 0],['2/25/2020', 0, 0, 0],['2/26/2020', 0, 0, 0],['2/27/2020', 0, 0, 0],['2/28/2020', 0, 0, 0],['2/29/2020', 0, 0, 0],['3/1/2020', 0, 0, 0],['3/2/2020', 0, 0, 0],['3/3/2020', 0, 0, 0],['3/4/2020', 0, 0, 0],['3/5/2020', 0, 0, 0],['3/6/2020', 3, 0, 0],['3/7/2020', 3, 0, 0],['3/8/2020', 5, 0, 0],['3/9/2020', 5, 0, 0],['3/10/2020', 5, 0, 0],['3/11/2020', 9, 0, 0],['3/12/2020', 12, 0, 0],['3/13/2020', 20, 0, 0],['3/14/2020', 27, 0, 3],['3/15/2020', 32, 0, 3],['3/16/2020', 40, 0, 3],['3/17/2020', 58, 0, 3],['3/18/2020', 81, 1, 3],['3/19/2020', 99, 1, 3],['3/20/2020', 138, 2, 3],['3/21/2020', 178, 3, 3],['3/22/2020', 225, 3, 3],['3/23/2020', 259, 3, 3],['3/24/2020', 311, 4, 3],['3/25/2020', 373, 4, 3],['3/26/2020', 511, 4, 3],['3/27/2020', 691, 5, 3],['3/28/2020', 956, 8, 3],['3/29/2020', 1110, 13, 3],['3/30/2020', 1261, 13, 46],['3/31/2020', 1473, 17, 46],['4/1/2020', 1765, 29, 53],['4/2/2020', 2066, 34, 53],['4/3/2020', 2445, 39, 53],['4/4/2020', 2829, 48, 73],['4/5/2020', 3223, 60, 73],['4/6/2020', 3610, 83, 184],['4/7/2020', 3912, 95, 288],['4/8/2020', 4958, 114, 288],['4/9/2020', 5547, 126, 288],['4/10/2020', 6279, 156, 55],['4/11/2020', 6938, 180, 55],['4/12/2020', 7413, 207, 55],['4/13/2020', 8063, 229, 55],['4/14/2020', 10983, 330, 55],['4/15/2020', 11445, 339, 55],['4/16/2020', 12097, 338, 55],['4/17/2020', 12772, 421, 55],['4/18/2020', 13421, 452, 55],['4/19/2020', 13928, 472, 55],['4/20/2020', 14646, 511, 55],['4/21/2020', 15124, 600, 917],['4/22/2020', 15646, 709, 981],['4/23/2020', 16440, 754, 981],['4/24/2020', 17314, 871, 981],['4/25/2020', 17766, 875, 1165],['4/26/2020', 18581, 910, 1177],['4/27/2020', 19487, 945, 1263],['4/28/2020', 20113, 1016, 1263],['4/29/2020', 20849, 1078, 1263],['4/30/2020', 21742, 1140, 1263],['5/1/2020', 23103, 1194, 1390],['5/2/2020', 24473, 1251, 1517],['5/3/2020', 25462, 1281, 1517],['5/4/2020', 26408, 1317, 1517],['5/5/2020', 27117, 1390, 1517],['5/6/2020', 28163, 1437, 1903],['5/7/2020', 29374, 1503, 1903],['5/8/2020', 30485, 1560, 2041],['5/9/2020', 31534, 1614, 2041],['5/10/2020', 32587, 1644, 2041],['5/11/2020', 33373, 1683, 2041],
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
      [39.1457, -76.7745, "Anne Arundel", 2472, 121],[39.424, -76.6177, "Baltimore", 3878, 191],[38.4728, -76.4895, "Calvert", 207, 11],[38.917, -75.9419, "Caroline", 133, 0],[39.657, -77.1683, "Carroll", 560, 58],[39.7003, -76.0586, "Cecil", 242, 13],[38.2646, -76.8496, "Charles", 749, 54],[39.3237, -77.3411, "Frederick", 1257, 74],[39.2924, -79.3525, "Garrett", 6, 0],[39.5839, -76.3637, "Harford", 609, 25],[39.1941, -76.7427, "Howard", 1206, 29],[39.3425, -75.8787, "Kent", 113, 13],[39.1547, -77.2405, "Montgomery", 6796, 382],[38.7849, -76.8721, "Prince George's", 9512, 353],[38.9853, -76.1677, "Queen Anne's", 80, 9],[38.0831, -75.8521, "Somerset", 43, 0],[38.1155, -76.4771, "St. Mary's", 241, 8],[38.7884, -76.2243, "Talbot", 60, 1],[39.3767, -77.7341, "Washington", 276, 9],[38.2672, -75.8938, "Wicomico", 571, 15],[38.1655, -75.3968, "Worcester", 107, 4],[38.3357, -76.2238, "Dorchester", 95, 2],[39.5653, -78.7054, "Allegany", 146, 12],
    ]);
    var options = {
      backgroundColor: {fill:'transparent',stroke:'#FFF' ,strokeWidth:0 }, 
      displayMode: 'markers',
      region: 'US-MD', 
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
      [{v:"Anne Arundel", f:"Anne Arundel"}, 2472, 9, 2351, 121, 0, 0],[{v:"Baltimore", f:"Baltimore"}, 3878, 16, 3687, 191, 0, 0],[{v:"Calvert", f:"Calvert"}, 207, 1, 196, 11, 0, 0],[{v:"Caroline", f:"Caroline"}, 133, 0, 133, 0, 0, 0],[{v:"Carroll", f:"Carroll"}, 560, 0, 502, 58, 0, 0],[{v:"Cecil", f:"Cecil"}, 242, 0, 229, 13, 0, 0],[{v:"Charles", f:"Charles"}, 749, 1, 695, 54, 0, 0],[{v:"Frederick", f:"Frederick"}, 1257, 6, 1131, 74, 0, 52],[{v:"Garrett", f:"Garrett"}, 6, 0, 6, 0, 0, 0],[{v:"Harford", f:"Harford"}, 609, 4, 584, 25, 0, 0],[{v:"Howard", f:"Howard"}, 1206, 1, 1177, 29, 0, 0],[{v:"Kent", f:"Kent"}, 113, 0, 100, 13, 0, 0],[{v:"Montgomery", f:"Montgomery"}, 6796, 34, 6411, 382, 0, 3],[{v:"Prince George's", f:"Prince George's"}, 9512, 16, 9159, 353, 0, 0],[{v:"Queen Anne's", f:"Queen Anne's"}, 80, 0, 71, 9, 0, 0],[{v:"Somerset", f:"Somerset"}, 43, 0, 43, 0, 0, 0],[{v:"St. Mary's", f:"St. Mary's"}, 241, 0, 233, 8, 0, 0],[{v:"Talbot", f:"Talbot"}, 60, 0, 59, 1, 0, 0],[{v:"Washington", f:"Washington"}, 276, 0, 267, 9, 0, 0],[{v:"Wicomico", f:"Wicomico"}, 571, 0, 556, 15, 0, 0],[{v:"Worcester", f:"Worcester"}, 107, 1, 103, 4, 0, 0],[{v:"Dorchester", f:"Dorchester"}, 95, 0, 93, 2, 0, 0],[{v:"Allegany", f:"Allegany"}, 146, 0, 134, 12, 0, 0],
    ]);
    data.setProperty(0, 0, 'style', 'min-width:100px');
    var table = new google.visualization.Table(document.getElementById('geo_table'));
    table.draw(data, {allowHtml: true, sortColumn: 2, sortAscending: false, width: '660px', height: '100%'});
  }
</script>

<span style="font-size: 13px">All COVID-19 data displayed on the page is available through our FREE <a href="https://developer.smartable.ai">API program</a>. This US - Maryland State Coronavirus (COVID-19) Live Stats is refreshed every hour using credible data sources, including the country/state's official government website, <a href="https://en.wikipedia.org/wiki/2019%E2%80%9320_coronavirus_pandemic" target="_blank">data available on wikipedia pages</a>, latest news reports, <a href="https://systems.jhu.edu/research/public-health/ncov/" target="_blank">Johns Hopkins University CSSE 2019-nCoV Dashboard</a>, <a href="https://www.who.int/emergencies/diseases/novel-coronavirus-2019/situation-reports" target="_blank">WHO Situation Reports</a>, <a href="https://www.cdc.gov/coronavirus/2019-ncov/index.html" target="_blank">CDC Situation Updates</a>, and <a href="https://ncov.dxy.cn/ncovh5/view/pneumonia" target="_blank">DXY.cn</a>.</span>

<h2 id="news" class="center" style="margin-top: 60px; font-size: 25px;">Local Government Help Information</h2>
<div class="info center">
<a href="https://phpa.health.maryland.gov/Pages/Novel-coronavirus.aspx" target="_blank">Maryland Department of Health</a>
</div>

