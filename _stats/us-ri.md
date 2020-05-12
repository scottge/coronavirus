---
category: stats
title: "US - Rhode Island Coronavirus (COVID-19) Live Stats"
excerpt: "Live stats of COVID-19 in US-Rhode Island. Total Cases: 11614 (+164), Deaths: 444 (+14), Recoveries: 730(-)."
publishedDateTime: 2020-05-12T21:45:15Z
updatedDateTime: 2020-05-12T21:45:15Z
webUrl: "https://smartable.ai/apps/coronavirus/stats/us-ri/"
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
  - url: "https://smartable.azureedge.net/coronavirus/sites/2/2020/us-ri.jpg"
    width: 900
    height: 564
    title: "US - Rhode Island Coronavirus (COVID-19) Live Stats"

---
<div class="total-stats" style="text-align: center;">
    <h3>
	    <div style="font-size: 18px; font-weight: 400;">Total Confirmed Cases:</div>
	    11614 (<span class='red'>+164</span>)
    </h3>
    <h3>
	    <div style="font-size: 18px; font-weight: 400;">Total Deaths:</div>
	    444 (<span class='red'>+14</span>)
    </h3>
    <h3>
	    <div style="font-size: 18px; font-weight: 400;">Total Recovered:</div>
	    730 (-)
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
      ['1/22/2020', 0, 0, 0],['1/23/2020', 0, 0, 0],['1/24/2020', 0, 0, 0],['1/25/2020', 0, 0, 0],['1/26/2020', 0, 0, 0],['1/27/2020', 0, 0, 0],['1/28/2020', 0, 0, 0],['1/29/2020', 0, 0, 0],['1/30/2020', 0, 0, 0],['1/31/2020', 0, 0, 0],['2/1/2020', 0, 0, 0],['2/2/2020', 0, 0, 0],['2/3/2020', 0, 0, 0],['2/4/2020', 0, 0, 0],['2/5/2020', 0, 0, 0],['2/6/2020', 0, 0, 0],['2/7/2020', 0, 0, 0],['2/8/2020', 0, 0, 0],['2/9/2020', 0, 0, 0],['2/10/2020', 0, 0, 0],['2/11/2020', 0, 0, 0],['2/12/2020', 0, 0, 0],['2/13/2020', 0, 0, 0],['2/14/2020', 0, 0, 0],['2/15/2020', 0, 0, 0],['2/16/2020', 0, 0, 0],['2/17/2020', 0, 0, 0],['2/18/2020', 0, 0, 0],['2/19/2020', 0, 0, 0],['2/20/2020', 0, 0, 0],['2/21/2020', 0, 0, 0],['2/22/2020', 0, 0, 0],['2/23/2020', 0, 0, 0],['2/24/2020', 0, 0, 0],['2/25/2020', 0, 0, 0],['2/26/2020', 0, 0, 0],['2/27/2020', 0, 0, 0],['2/28/2020', 0, 0, 0],['2/29/2020', 0, 0, 0],['3/1/2020', 1, 0, 0],['3/2/2020', 2, 0, 0],['3/3/2020', 2, 0, 0],['3/4/2020', 2, 0, 0],['3/5/2020', 2, 0, 0],['3/6/2020', 2, 0, 0],['3/7/2020', 3, 0, 0],['3/8/2020', 3, 0, 0],['3/9/2020', 3, 0, 0],['3/10/2020', 3, 0, 0],['3/11/2020', 3, 0, 0],['3/12/2020', 5, 0, 0],['3/13/2020', 5, 0, 0],['3/14/2020', 22, 0, 0],['3/15/2020', 20, 0, 0],['3/16/2020', 21, 0, 0],['3/17/2020', 23, 0, 0],['3/18/2020', 33, 0, 0],['3/19/2020', 44, 0, 0],['3/20/2020', 54, 0, 0],['3/21/2020', 66, 0, 0],['3/22/2020', 83, 0, 0],['3/23/2020', 106, 0, 0],['3/24/2020', 124, 0, 0],['3/25/2020', 132, 0, 0],['3/26/2020', 165, 0, 0],['3/27/2020', 203, 0, 0],['3/28/2020', 239, 2, 0],['3/29/2020', 294, 3, 0],['3/30/2020', 408, 4, 0],['3/31/2020', 488, 8, 0],['4/1/2020', 566, 10, 0],['4/2/2020', 657, 12, 0],['4/3/2020', 711, 14, 0],['4/4/2020', 806, 17, 0],['4/5/2020', 922, 25, 0],['4/6/2020', 1082, 27, 0],['4/7/2020', 1229, 30, 0],['4/8/2020', 1450, 35, 0],['4/9/2020', 1727, 43, 0],['4/10/2020', 2015, 49, 0],['4/11/2020', 2349, 56, 0],['4/12/2020', 2665, 63, 0],['4/13/2020', 2976, 73, 0],['4/14/2020', 3251, 80, 0],['4/15/2020', 3529, 87, 0],['4/16/2020', 3838, 105, 0],['4/17/2020', 4177, 118, 0],['4/18/2020', 4491, 137, 0],['4/19/2020', 4706, 150, 0],['4/20/2020', 5090, 155, 0],['4/21/2020', 5500, 171, 0],['4/22/2020', 5829, 181, 0],['4/23/2020', 6256, 189, 342],['4/24/2020', 6794, 223, 377],['4/25/2020', 7129, 215, 342],['4/26/2020', 7439, 226, 342],['4/27/2020', 7708, 233, 342],['4/28/2020', 7926, 239, 342],['4/29/2020', 8247, 251, 342],['4/30/2020', 8621, 266, 342],['5/1/2020', 8954, 281, 342],['5/2/2020', 9289, 296, 342],['5/3/2020', 9477, 320, 342],['5/4/2020', 9652, 487, 342],['5/5/2020', 9933, 355, 342],['5/6/2020', 10205, 370, 665],['5/7/2020', 10530, 388, 665],['5/8/2020', 10779, 399, 730],['5/9/2020', 10989, 418, 730],['5/10/2020', 11274, 422, 730],['5/11/2020', 11450, 430, 730],['5/12/2020', 11614, 444, 730],
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
      [41.6988, -71.7339, "Kent", 859, 28],[41.4803, -71.3205, "Newport", 182, 1],[41.8882, -71.4774, "Providence", 8674, 203],[41.5151, -71.72, "Washington", 406, 20],[41.7257893, -71.3111773, "Bristol", 171, 1],
    ]);
    var options = {
      backgroundColor: {fill:'transparent',stroke:'#FFF' ,strokeWidth:0 }, 
      displayMode: 'markers',
      region: 'US-RI', 
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
      [{v:"Kent", f:"Kent"}, 859, 0, 831, 28, 0, 0],[{v:"Newport", f:"Newport"}, 182, 0, 181, 1, 0, 0],[{v:"Providence", f:"Providence"}, 8674, 0, 8471, 203, 0, 0],[{v:"Washington", f:"Washington"}, 406, 0, 386, 20, 0, 0],[{v:"Bristol", f:"Bristol"}, 171, 0, 170, 1, 0, 0],
    ]);
    data.setProperty(0, 0, 'style', 'min-width:100px');
    var table = new google.visualization.Table(document.getElementById('geo_table'));
    table.draw(data, {allowHtml: true, sortColumn: 2, sortAscending: false, width: '660px', height: '100%'});
  }
</script>

<span style="font-size: 13px">All COVID-19 data displayed on the page is available through our FREE <a href="https://developer.smartable.ai">API program</a>. This US - Rhode Island Coronavirus (COVID-19) Live Stats is refreshed every hour using credible data sources, including the country/state's official government website, <a href="https://en.wikipedia.org/wiki/2019%E2%80%9320_coronavirus_pandemic" target="_blank">data available on wikipedia pages</a>, latest news reports, <a href="https://systems.jhu.edu/research/public-health/ncov/" target="_blank">Johns Hopkins University CSSE 2019-nCoV Dashboard</a>, <a href="https://www.who.int/emergencies/diseases/novel-coronavirus-2019/situation-reports" target="_blank">WHO Situation Reports</a>, <a href="https://www.cdc.gov/coronavirus/2019-ncov/index.html" target="_blank">CDC Situation Updates</a>, and <a href="https://ncov.dxy.cn/ncovh5/view/pneumonia" target="_blank">DXY.cn</a>.</span>

<h2 id="news" class="center" style="margin-top: 60px; font-size: 25px;">Local Government Help Information</h2>
<div class="info center">
<a href="https://health.ri.gov/diseases/ncov2019/" target="_blank">Rhode Island Department of Health</a> 401-222-8022
</div>

