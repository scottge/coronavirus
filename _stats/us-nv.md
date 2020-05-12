---
category: stats
title: "US - Nevada State Coronavirus (COVID-19) Live Stats"
excerpt: "Live stats of COVID-19 in US-Nevada. Total Cases: 6152 (-), Deaths: 312 (+6), Recoveries: 4197(-)."
publishedDateTime: 2020-05-12T03:45:09Z
updatedDateTime: 2020-05-12T03:45:09Z
webUrl: "https://smartable.ai/apps/coronavirus/stats/us-nv/"
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
  - url: "https://smartable.azureedge.net/coronavirus/sites/2/2020/us-nv.jpg"
    width: 900
    height: 564
    title: "US - Nevada State Coronavirus (COVID-19) Live Stats"

---
<div class="total-stats" style="text-align: center;">
    <h3>
	    <div style="font-size: 18px; font-weight: 400;">Total Confirmed Cases:</div>
	    6152 (-)
    </h3>
    <h3>
	    <div style="font-size: 18px; font-weight: 400;">Total Deaths:</div>
	    312 (<span class='red'>+6</span>)
    </h3>
    <h3>
	    <div style="font-size: 18px; font-weight: 400;">Total Recovered:</div>
	    4197 (-)
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
      ['1/22/2020', 0, 0, 0],['1/23/2020', 0, 0, 0],['1/24/2020', 0, 0, 0],['1/25/2020', 0, 0, 0],['1/26/2020', 0, 0, 0],['1/27/2020', 0, 0, 0],['1/28/2020', 0, 0, 0],['1/29/2020', 0, 0, 0],['1/30/2020', 0, 0, 0],['1/31/2020', 0, 0, 0],['2/1/2020', 0, 0, 0],['2/2/2020', 0, 0, 0],['2/3/2020', 0, 0, 0],['2/4/2020', 0, 0, 0],['2/5/2020', 0, 0, 0],['2/6/2020', 0, 0, 0],['2/7/2020', 0, 0, 0],['2/8/2020', 0, 0, 0],['2/9/2020', 0, 0, 0],['2/10/2020', 0, 0, 0],['2/11/2020', 0, 0, 0],['2/12/2020', 0, 0, 0],['2/13/2020', 0, 0, 0],['2/14/2020', 0, 0, 0],['2/15/2020', 0, 0, 0],['2/16/2020', 0, 0, 0],['2/17/2020', 0, 0, 0],['2/18/2020', 0, 0, 0],['2/19/2020', 0, 0, 0],['2/20/2020', 0, 0, 0],['2/21/2020', 0, 0, 0],['2/22/2020', 0, 0, 0],['2/23/2020', 0, 0, 0],['2/24/2020', 0, 0, 0],['2/25/2020', 0, 0, 0],['2/26/2020', 0, 0, 0],['2/27/2020', 0, 0, 0],['2/28/2020', 0, 0, 0],['2/29/2020', 0, 0, 0],['3/1/2020', 0, 0, 0],['3/2/2020', 0, 0, 0],['3/3/2020', 0, 0, 0],['3/4/2020', 0, 0, 0],['3/5/2020', 1, 0, 0],['3/6/2020', 2, 0, 0],['3/7/2020', 2, 0, 0],['3/8/2020', 4, 0, 0],['3/9/2020', 4, 0, 0],['3/10/2020', 4, 0, 0],['3/11/2020', 7, 0, 0],['3/12/2020', 10, 0, 0],['3/13/2020', 19, 0, 0],['3/14/2020', 20, 0, 0],['3/15/2020', 25, 0, 0],['3/16/2020', 44, 1, 0],['3/17/2020', 54, 1, 0],['3/18/2020', 83, 1, 0],['3/19/2020', 94, 1, 0],['3/20/2020', 159, 2, 0],['3/21/2020', 155, 2, 0],['3/22/2020', 189, 2, 0],['3/23/2020', 242, 4, 0],['3/24/2020', 283, 6, 0],['3/25/2020', 403, 14, 0],['3/26/2020', 534, 10, 0],['3/27/2020', 619, 10, 0],['3/28/2020', 733, 14, 0],['3/29/2020', 915, 15, 0],['3/30/2020', 1039, 18, 0],['3/31/2020', 1133, 26, 0],['4/1/2020', 1294, 32, 18],['4/2/2020', 1479, 38, 26],['4/3/2020', 1554, 43, 28],['4/4/2020', 1732, 46, 28],['4/5/2020', 1826, 46, 35],['4/6/2020', 1959, 46, 35],['4/7/2020', 2118, 72, 37],['4/8/2020', 2305, 72, 44],['4/9/2020', 2442, 81, 44],['4/10/2020', 2587, 102, 863],['4/11/2020', 2731, 111, 988],['4/12/2020', 2820, 114, 988],['4/13/2020', 3007, 121, 1163],['4/14/2020', 3119, 130, 1243],['4/15/2020', 3186, 131, 1394],['4/16/2020', 3295, 142, 1524],['4/17/2020', 3497, 142, 1657],['4/18/2020', 3616, 151, 1763],['4/19/2020', 3700, 158, 1873],['4/20/2020', 3802, 163, 1951],['4/21/2020', 3909, 163, 2037],['4/22/2020', 4053, 187, 2196],['4/23/2020', 4177, 194, 2312],['4/24/2020', 4403, 200, 2407],['4/25/2020', 4539, 206, 2407],['4/26/2020', 4640, 206, 2407],['4/27/2020', 4717, 219, 2647],['4/28/2020', 4822, 225, 2647],['4/29/2020', 4935, 237, 2905],['4/30/2020', 5054, 243, 2905],['5/1/2020', 5179, 249, 2905],['5/2/2020', 5391, 257, 2905],['5/3/2020', 5474, 262, 2905],['5/4/2020', 5726, 266, 2905],['5/5/2020', 5664, 276, 2905],['5/6/2020', 5743, 286, 4197],['5/7/2020', 5887, 293, 4197],['5/8/2020', 5926, 301, 4197],['5/9/2020', 6081, 306, 4197],['5/10/2020', 6152, 306, 4197],['5/11/2020', 6152, 312, 4197],
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
      [39.1511, -119.7474, "Carson", 55, 2],[36.0796, -115.094, "Clark", 4750, 260],[38.9609, -119.7688, "Douglas", 24, 0],[40.7239, -115.479, "Elko", 45, 1],[41.49, -117.5323, "Humboldt", 67, 3],[39.2639, -119.6356, "Lyon", 42, 0],[38.8655, -117.9238, "Nye", 44, 0],[40.5608, -119.6035, "Washoe", 1095, 39],[38.9157, -115.0643, "White Pine", 3, 0],[37.952, -114.4434, "Lincoln", 1, 0],[39.4151, -118.7165, "Churchill", 5, 1],[38.6468, -118.7572, "Mineral", 4, 0],[39.4978, -117.0741, "Lander", 17, 0],
    ]);
    var options = {
      backgroundColor: {fill:'transparent',stroke:'#FFF' ,strokeWidth:0 }, 
      displayMode: 'markers',
      region: 'US-NV', 
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
      [{v:"Carson", f:"Carson"}, 55, 0, 53, 2, 0, 0],[{v:"Clark", f:"Clark"}, 4750, 0, 2346, 260, 0, 2144],[{v:"Douglas", f:"Douglas"}, 24, 0, 17, 0, 0, 7],[{v:"Elko", f:"Elko"}, 45, 0, 38, 1, 0, 6],[{v:"Humboldt", f:"Humboldt"}, 67, 0, 59, 3, 0, 5],[{v:"Lyon", f:"Lyon"}, 42, 0, 37, 0, 0, 5],[{v:"Nye", f:"Nye"}, 44, 0, 42, 0, 0, 2],[{v:"Washoe", f:"Washoe"}, 1095, 0, 832, 39, 0, 224],[{v:"White Pine", f:"White Pine"}, 3, 0, 3, 0, 0, 0],[{v:"Lincoln", f:"Lincoln"}, 1, 0, 0, 0, 0, 14],[{v:"Churchill", f:"Churchill"}, 5, 0, 4, 1, 0, 0],[{v:"Mineral", f:"Mineral"}, 4, 0, 4, 0, 0, 0],[{v:"Lander", f:"Lander"}, 17, 0, 17, 0, 0, 0],
    ]);
    data.setProperty(0, 0, 'style', 'min-width:100px');
    var table = new google.visualization.Table(document.getElementById('geo_table'));
    table.draw(data, {allowHtml: true, sortColumn: 2, sortAscending: false, width: '660px', height: '100%'});
  }
</script>

<span style="font-size: 13px">All COVID-19 data displayed on the page is available through our FREE <a href="https://developer.smartable.ai">API program</a>. This US - Nevada State Coronavirus (COVID-19) Live Stats is refreshed every hour using credible data sources, including the country/state's official government website, <a href="https://en.wikipedia.org/wiki/2019%E2%80%9320_coronavirus_pandemic" target="_blank">data available on wikipedia pages</a>, latest news reports, <a href="https://systems.jhu.edu/research/public-health/ncov/" target="_blank">Johns Hopkins University CSSE 2019-nCoV Dashboard</a>, <a href="https://www.who.int/emergencies/diseases/novel-coronavirus-2019/situation-reports" target="_blank">WHO Situation Reports</a>, <a href="https://www.cdc.gov/coronavirus/2019-ncov/index.html" target="_blank">CDC Situation Updates</a>, and <a href="https://ncov.dxy.cn/ncovh5/view/pneumonia" target="_blank">DXY.cn</a>.</span>

<h2 id="news" class="center" style="margin-top: 60px; font-size: 25px;">Local Government Help Information</h2>
<div class="info center">
<a href="http://dpbh.nv.gov/Programs/OPHIE/dta/Hot_Topics/Coronavirus/" target="_blank">DHHS - Nevada Department of Health</a>
</div>

