---
category: stats
title: "US - Indiana State Coronavirus (COVID-19) Live Stats"
excerpt: "Live stats of COVID-19 in US-Indiana. Total Cases: 24006 (+619), Deaths: 1490 (+43), Recoveries: 1559(-)."
publishedDateTime: 2020-05-10T05:45:41Z
updatedDateTime: 2020-05-10T05:45:41Z
webUrl: "https://smartable.ai/apps/coronavirus/stats/us-in/"
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
  - url: "https://smartable.azureedge.net/coronavirus/sites/2/2020/us-in.jpg"
    width: 900
    height: 564
    title: "US - Indiana State Coronavirus (COVID-19) Live Stats"

---
<div class="total-stats" style="text-align: center;">
    <h3>
	    <div style="font-size: 18px; font-weight: 400;">Total Confirmed Cases:</div>
	    24006 (<span class='red'>+619</span>)
    </h3>
    <h3>
	    <div style="font-size: 18px; font-weight: 400;">Total Deaths:</div>
	    1490 (<span class='red'>+43</span>)
    </h3>
    <h3>
	    <div style="font-size: 18px; font-weight: 400;">Total Recovered:</div>
	    1559 (-)
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
      ['1/22/2020', 0, 0, 0],['1/23/2020', 0, 0, 0],['1/24/2020', 0, 0, 0],['1/25/2020', 0, 0, 0],['1/26/2020', 0, 0, 0],['1/27/2020', 0, 0, 0],['1/28/2020', 0, 0, 0],['1/29/2020', 0, 0, 0],['1/30/2020', 0, 0, 0],['1/31/2020', 0, 0, 0],['2/1/2020', 0, 0, 0],['2/2/2020', 0, 0, 0],['2/3/2020', 0, 0, 0],['2/4/2020', 0, 0, 0],['2/5/2020', 0, 0, 0],['2/6/2020', 0, 0, 0],['2/7/2020', 0, 0, 0],['2/8/2020', 0, 0, 0],['2/9/2020', 0, 0, 0],['2/10/2020', 0, 0, 0],['2/11/2020', 0, 0, 0],['2/12/2020', 0, 0, 0],['2/13/2020', 0, 0, 0],['2/14/2020', 0, 0, 0],['2/15/2020', 0, 0, 0],['2/16/2020', 0, 0, 0],['2/17/2020', 0, 0, 0],['2/18/2020', 0, 0, 0],['2/19/2020', 0, 0, 0],['2/20/2020', 0, 0, 0],['2/21/2020', 0, 0, 0],['2/22/2020', 0, 0, 0],['2/23/2020', 0, 0, 0],['2/24/2020', 0, 0, 0],['2/25/2020', 0, 0, 0],['2/26/2020', 0, 0, 0],['2/27/2020', 0, 0, 0],['2/28/2020', 0, 0, 0],['2/29/2020', 0, 0, 0],['3/1/2020', 0, 0, 0],['3/2/2020', 0, 0, 0],['3/3/2020', 0, 0, 0],['3/4/2020', 0, 0, 0],['3/5/2020', 0, 0, 0],['3/6/2020', 1, 0, 0],['3/7/2020', 1, 0, 0],['3/8/2020', 2, 0, 0],['3/9/2020', 3, 0, 0],['3/10/2020', 6, 0, 0],['3/11/2020', 11, 0, 0],['3/12/2020', 12, 0, 0],['3/13/2020', 12, 0, 0],['3/14/2020', 15, 0, 0],['3/15/2020', 20, 0, 0],['3/16/2020', 24, 2, 0],['3/17/2020', 30, 2, 0],['3/18/2020', 39, 2, 0],['3/19/2020', 61, 2, 0],['3/20/2020', 87, 3, 0],['3/21/2020', 128, 4, 0],['3/22/2020', 204, 7, 0],['3/23/2020', 271, 7, 0],['3/24/2020', 370, 12, 0],['3/25/2020', 479, 14, 0],['3/26/2020', 657, 17, 0],['3/27/2020', 981, 25, 0],['3/28/2020', 1232, 31, 0],['3/29/2020', 1514, 32, 0],['3/30/2020', 1787, 35, 0],['3/31/2020', 2159, 49, 0],['4/1/2020', 2569, 65, 0],['4/2/2020', 3039, 78, 0],['4/3/2020', 3437, 102, 0],['4/4/2020', 3973, 117, 0],['4/5/2020', 4431, 128, 0],['4/6/2020', 4976, 144, 0],['4/7/2020', 5530, 174, 0],['4/8/2020', 5963, 204, 28],['4/9/2020', 6371, 246, 28],['4/10/2020', 6925, 301, 58],['4/11/2020', 7451, 331, 58],['4/12/2020', 7941, 344, 105],['4/13/2020', 8310, 354, 105],['4/14/2020', 8515, 387, 131],['4/15/2020', 8949, 436, 146],['4/16/2020', 9537, 480, 150],['4/17/2020', 10154, 519, 150],['4/18/2020', 10641, 545, 173],['4/19/2020', 11211, 562, 1557],['4/20/2020', 11688, 577, 1559],['4/21/2020', 12097, 635, 1559],['4/22/2020', 12438, 666, 1559],['4/23/2020', 13039, 706, 1559],['4/24/2020', 13041, 706, 1559],['4/25/2020', 14399, 785, 175],['4/26/2020', 15023, 813, 175],['4/27/2020', 15971, 932, 175],['4/28/2020', 16592, 992, 175],['4/29/2020', 17186, 1065, 175],['4/30/2020', 17989, 1114, 175],['5/1/2020', 18626, 1166, 175],['5/2/2020', 19310, 1229, 175],['5/3/2020', 19944, 1246, 175],['5/4/2020', 20518, 1264, 175],['5/5/2020', 21046, 1326, 175],['5/6/2020', 21885, 1377, 1559],['5/7/2020', 22748, 1414, 1559],['5/8/2020', 23387, 1447, 1559],['5/9/2020', 24006, 1490, 1559],
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
      [39.8522, -77.2865, "Adams", 9, 1],[41.1966, -84.9245, "Allen", 800, 63],[39.2094, -85.9183, "Bartholomew", 342, 25],[40.0106, -86.4997, "Boone", 228, 30],[39.3085, -86.1227, "Brown", 25, 1],[40.5452, -86.5242, "Carroll", 71, 2],[40.8644, -86.5, "Cass", 1507, 3],[38.5395, -85.7655, "Clark", 374, 26],[39.2769, -87.1126, "Clay", 24, 1],[40.1944, -86.6671, "Clinton", 85, 2],[38.3714, -86.3444, "Crawford", 21, 1],[39.0676, -84.9053, "Dearborn", 148, 13],[39.4279, -85.6286, "Decatur", 218, 31],[41.3147, -84.9012, "DeKalb", 24, 2],[40.3138, -85.5009, "Delaware", 219, 15],[38.3934, -86.9404, "Dubois", 42, 0],[41.5336, -86.0138, "Elkhart", 436, 18],[39.6582, -85.141, "Fayette", 54, 4],[38.3513, -85.9372, "Floyd", 230, 29],[40.1089, -87.1577, "Fountain", 15, 2],[39.4233, -85.0114, "Franklin", 107, 8],[41.0192, -86.4125, "Fulton", 36, 1],[38.2786, -87.377, "Gibson", 7, 0],[40.6126, -85.5592, "Grant", 170, 16],[38.9879, -87.0813, "Greene", 150, 11],[39.9658, -86.1461, "Hamilton", 920, 82],[39.8857, -85.6086, "Hancock", 264, 18],[38.124, -85.9736, "Harrison", 156, 12],[39.8065, -86.5401, "Hendricks", 951, 63],[39.9973, -85.2512, "Henry", 73, 2],[40.4483, -86.1345, "Howard", 242, 10],[40.741, -85.5618, "Huntington", 13, 2],[38.8247, -86.1716, "Jackson", 274, 1],[40.9059, -87.1612, "Jasper", 46, 1],[38.9853, -85.6106, "Jennings", 95, 5],[39.4638, -86.1345, "Johnson", 790, 87],[38.7991, -87.4604, "Knox", 21, 0],[41.0743, -85.8923, "Kosciusko", 40, 2],[41.648, -85.4179, "LaGrange", 37, 2],[41.443, -87.4702, "Lake", 2392, 128],[41.7563, -86.8181, "LaPorte", 321, 11],[38.9172, -86.5557, "Lawrence", 116, 16],[40.2743, -85.8371, "Madison", 497, 65],[39.8362, -86.1752, "Marion", 7245, 430],[41.2159, -86.4236, "Marshall", 32, 1],[40.602, -85.9275, "Miami", 123, 1],[39.1637, -86.5257, "Monroe", 142, 9],[40.0428, -86.8975, "Montgomery", 125, 3],[39.5337, -86.3778, "Morgan", 194, 9],[40.9523, -87.299, "Newton", 66, 10],[41.4277, -85.355, "Noble", 128, 15],[38.9531, -84.8546, "Ohio", 9, 0],[38.5462, -86.6202, "Orange", 113, 18],[39.2861, -86.7726, "Owen", 28, 1],[41.685, -86.9804, "Porter", 309, 9],[38.2042, -87.9151, "Posey", 15, 0],[39.5211, -86.7995, "Putnam", 89, 5],[40.1898, -85.2037, "Randolph", 35, 2],[39.2373, -85.0931, "Ripley", 99, 6],[39.4981, -85.4676, "Rush", 47, 2],[38.6854, -85.7831, "Scott", 79, 2],[39.6738, -85.7052, "Shelby", 311, 22],[41.6228, -86.3377, "St. Joseph", 785, 30],[41.1989, -86.8922, "Starke", 22, 2],[41.6432, -85.005, "Steuben", 63, 1],[39.0973, -87.4074, "Sullivan", 20, 0],[38.7427, -85.0783, "Switzerland", 16, 0],[40.5076, -86.8527, "Tippecanoe", 225, 2],[40.3795, -86.0868, "Tipton", 21, 1],[38.024, -87.512, "Vanderburgh", 182, 2],[39.4936, -87.2667, "Vigo", 77, 6],[40.9807, -85.8393, "Wabash", 64, 2],[40.1973, -87.527, "Warren", 13, 1],[38.0469, -87.2847, "Warrick", 121, 20],[38.5549, -86.2778, "Washington", 48, 1],[39.9447, -84.8308, "Wayne", 138, 5],[40.6568, -85.2225, "Wells", 10, 0],[40.6622, -86.8678, "White", 145, 1],[41.2308, -85.3201, "Whitley", 22, 1],[38.7369, -85.5387, "Jefferson", 35, 0],[40.4882, -87.0857, "Benton", 12, 0],[40.492, -85.1468, "Jay", 21, 0],[40.4537, -85.3736, "Blackford", 13, 1],[38.1692, -86.8257, "Spencer", 10, 1],[39.7665, -87.2295, "Parke", 17, 0],[39.6349, -84.926, "Union", 19, 0],[38.7221, -86.8002, "Martin", 7, 0],[38.6679, -86.9974, "Daviess", 56, 17],[39.667, -87.5203, "Vermillion", 8, 0],[41.0535, -86.6037, "Pulaski", 34, 0],[37.9106, -86.7377, "Perry", 21, 0],[38.3827, -87.2129, "Pike", 2, 0],
    ]);
    var options = {
      backgroundColor: {fill:'transparent',stroke:'#FFF' ,strokeWidth:0 }, 
      displayMode: 'markers',
      region: 'US-IN', 
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
      [{v:"Adams", f:"Adams"}, 9, 0, 8, 1, 0, 0],[{v:"Allen", f:"Allen"}, 800, 19, 737, 63, 0, 0],[{v:"Bartholomew", f:"Bartholomew"}, 342, 11, 317, 25, 1, 0],[{v:"Boone", f:"Boone"}, 228, 6, 198, 30, 0, 0],[{v:"Brown", f:"Brown"}, 25, 0, 24, 1, 0, 0],[{v:"Carroll", f:"Carroll"}, 71, 1, 69, 2, 0, 0],[{v:"Cass", f:"Cass"}, 1507, 10, 1504, 3, 0, 0],[{v:"Clark", f:"Clark"}, 374, 16, 348, 26, 0, 0],[{v:"Clay", f:"Clay"}, 24, 0, 23, 1, 0, 0],[{v:"Clinton", f:"Clinton"}, 85, 5, 83, 2, 0, 0],[{v:"Crawford", f:"Crawford"}, 21, 0, 20, 1, 0, 0],[{v:"Dearborn", f:"Dearborn"}, 148, 2, 135, 13, 0, 0],[{v:"Decatur", f:"Decatur"}, 218, 2, 187, 31, 0, 0],[{v:"DeKalb", f:"DeKalb"}, 24, 0, 22, 2, 0, 0],[{v:"Delaware", f:"Delaware"}, 219, 5, 204, 15, 0, 0],[{v:"Dubois", f:"Dubois"}, 42, 4, 42, 0, 0, 0],[{v:"Elkhart", f:"Elkhart"}, 436, 26, 418, 18, 2, 0],[{v:"Fayette", f:"Fayette"}, 54, 2, 50, 4, 0, 0],[{v:"Floyd", f:"Floyd"}, 230, 4, 201, 29, 0, 0],[{v:"Fountain", f:"Fountain"}, 15, 1, 13, 2, 0, 0],[{v:"Franklin", f:"Franklin"}, 107, 3, 46, 8, 0, 53],[{v:"Fulton", f:"Fulton"}, 36, 2, 35, 1, 0, 0],[{v:"Gibson", f:"Gibson"}, 7, 0, 7, 0, 0, 0],[{v:"Grant", f:"Grant"}, 170, 5, 154, 16, 1, 0],[{v:"Greene", f:"Greene"}, 150, 4, 139, 11, 0, 0],[{v:"Hamilton", f:"Hamilton"}, 920, 17, 838, 82, 0, 0],[{v:"Hancock", f:"Hancock"}, 264, 18, 246, 18, 1, 0],[{v:"Harrison", f:"Harrison"}, 156, 3, 144, 12, 0, 0],[{v:"Hendricks", f:"Hendricks"}, 951, 24, 888, 63, 3, 0],[{v:"Henry", f:"Henry"}, 73, 3, 71, 2, 0, 0],[{v:"Howard", f:"Howard"}, 242, 8, 232, 10, 0, 0],[{v:"Huntington", f:"Huntington"}, 13, 0, 11, 2, 0, 0],[{v:"Jackson", f:"Jackson"}, 274, 23, 273, 1, 0, 0],[{v:"Jasper", f:"Jasper"}, 46, 0, 45, 1, 0, 0],[{v:"Jennings", f:"Jennings"}, 95, 2, 90, 5, 0, 0],[{v:"Johnson", f:"Johnson"}, 790, 21, 700, 87, 4, 3],[{v:"Knox", f:"Knox"}, 21, 0, 21, 0, 0, 0],[{v:"Kosciusko", f:"Kosciusko"}, 40, 0, 38, 2, 0, 0],[{v:"LaGrange", f:"LaGrange"}, 37, 0, 35, 2, 0, 0],[{v:"Lake", f:"Lake"}, 2392, 33, 2264, 128, 7, 0],[{v:"LaPorte", f:"LaPorte"}, 321, 14, 310, 11, 0, 0],[{v:"Lawrence", f:"Lawrence"}, 116, 1, 100, 16, 0, 0],[{v:"Madison", f:"Madison"}, 497, 14, 432, 65, 0, 0],[{v:"Marion", f:"Marion"}, 7245, 167, 6815, 430, 5, 0],[{v:"Marshall", f:"Marshall"}, 32, 0, 31, 1, 0, 0],[{v:"Miami", f:"Miami"}, 123, 1, 122, 1, 0, 0],[{v:"Monroe", f:"Monroe"}, 142, 1, 133, 9, 0, 0],[{v:"Montgomery", f:"Montgomery"}, 125, 11, 122, 3, 1, 0],[{v:"Morgan", f:"Morgan"}, 194, 8, 185, 9, 0, 0],[{v:"Newton", f:"Newton"}, 66, 2, 56, 10, 0, 0],[{v:"Noble", f:"Noble"}, 128, 1, 113, 15, 0, 0],[{v:"Ohio", f:"Ohio"}, 9, 2, 9, 0, 0, 0],[{v:"Orange", f:"Orange"}, 113, 5, 95, 18, 1, 0],[{v:"Owen", f:"Owen"}, 28, 2, 27, 1, 0, 0],[{v:"Porter", f:"Porter"}, 309, 6, 236, 9, 1, 64],[{v:"Posey", f:"Posey"}, 15, 0, 15, 0, 0, 0],[{v:"Putnam", f:"Putnam"}, 89, 4, 84, 5, 0, 0],[{v:"Randolph", f:"Randolph"}, 35, 6, 33, 2, 0, 0],[{v:"Ripley", f:"Ripley"}, 99, 0, 93, 6, 0, 0],[{v:"Rush", f:"Rush"}, 47, 0, 45, 2, 0, 0],[{v:"Scott", f:"Scott"}, 79, 6, 77, 2, 0, 0],[{v:"Shelby", f:"Shelby"}, 311, 11, 289, 22, 0, 0],[{v:"St. Joseph", f:"St. Joseph"}, 785, 12, 755, 30, 1, 0],[{v:"Starke", f:"Starke"}, 22, 1, 20, 2, 0, 0],[{v:"Steuben", f:"Steuben"}, 63, 0, 62, 1, 0, 0],[{v:"Sullivan", f:"Sullivan"}, 20, 1, 20, 0, 0, 0],[{v:"Switzerland", f:"Switzerland"}, 16, 0, 16, 0, 0, 0],[{v:"Tippecanoe", f:"Tippecanoe"}, 225, 18, 223, 2, 0, 0],[{v:"Tipton", f:"Tipton"}, 21, 1, 20, 1, 0, 0],[{v:"Vanderburgh", f:"Vanderburgh"}, 182, 7, 125, 2, 0, 55],[{v:"Vigo", f:"Vigo"}, 77, 2, 71, 6, 0, 0],[{v:"Wabash", f:"Wabash"}, 64, 0, 62, 2, 0, 0],[{v:"Warren", f:"Warren"}, 13, 0, 12, 1, 0, 0],[{v:"Warrick", f:"Warrick"}, 121, 2, 101, 20, 1, 0],[{v:"Washington", f:"Washington"}, 48, 3, 47, 1, 0, 0],[{v:"Wayne", f:"Wayne"}, 138, 12, 133, 5, 2, 0],[{v:"Wells", f:"Wells"}, 10, 1, 10, 0, 0, 0],[{v:"White", f:"White"}, 145, 6, 144, 1, 0, 0],[{v:"Whitley", f:"Whitley"}, 22, 0, 21, 1, 0, 0],[{v:"Jefferson", f:"Jefferson"}, 35, 1, 35, 0, 0, 0],[{v:"Benton", f:"Benton"}, 12, 0, 12, 0, 0, 0],[{v:"Jay", f:"Jay"}, 21, 2, 21, 0, 0, 0],[{v:"Blackford", f:"Blackford"}, 13, 0, 12, 1, 0, 0],[{v:"Spencer", f:"Spencer"}, 10, 1, 9, 1, 0, 0],[{v:"Parke", f:"Parke"}, 17, 1, 17, 0, 0, 0],[{v:"Union", f:"Union"}, 19, 3, 19, 0, 0, 0],[{v:"Martin", f:"Martin"}, 7, 0, 7, 0, 0, 0],[{v:"Daviess", f:"Daviess"}, 56, 0, 39, 17, 0, 0],[{v:"Vermillion", f:"Vermillion"}, 8, 0, 8, 0, 0, 0],[{v:"Pulaski", f:"Pulaski"}, 34, 1, 34, 0, 0, 0],[{v:"Perry", f:"Perry"}, 21, 2, 21, 0, 0, 0],[{v:"Pike", f:"Pike"}, 2, 0, 2, 0, 0, 0],
    ]);
    data.setProperty(0, 0, 'style', 'min-width:100px');
    var table = new google.visualization.Table(document.getElementById('geo_table'));
    table.draw(data, {allowHtml: true, sortColumn: 2, sortAscending: false, width: '660px', height: '100%'});
  }
</script>

<span style="font-size: 13px">All COVID-19 data displayed on the page is available through our FREE <a href="https://developer.smartable.ai">API program</a>. This US - Indiana State Coronavirus (COVID-19) Live Stats is refreshed every hour using credible data sources, including the country/state's official government website, <a href="https://en.wikipedia.org/wiki/2019%E2%80%9320_coronavirus_pandemic" target="_blank">data available on wikipedia pages</a>, latest news reports, <a href="https://systems.jhu.edu/research/public-health/ncov/" target="_blank">Johns Hopkins University CSSE 2019-nCoV Dashboard</a>, <a href="https://www.who.int/emergencies/diseases/novel-coronavirus-2019/situation-reports" target="_blank">WHO Situation Reports</a>, <a href="https://www.cdc.gov/coronavirus/2019-ncov/index.html" target="_blank">CDC Situation Updates</a>, and <a href="https://ncov.dxy.cn/ncovh5/view/pneumonia" target="_blank">DXY.cn</a>.</span>

<h2 id="news" class="center" style="margin-top: 60px; font-size: 25px;">Local Government Help Information</h2>
<div class="info center">
<a href="https://www.in.gov/isdh/28470.htm" target="_blank">Indiana State Department of Health</a> 317-233-7125
</div>
<h2 id="news" class="center" style="margin-top: 60px; font-size: 25px;">Trending Coronavirus News in US-Indiana</h2>
<div class="row">
<div class="col-md-6 col-sm-12">
  <div class="content-card">
	<a href="https://cbs4indy.com/news/indiana-reporting-650-new-coronavirus-cases-31-additional-deaths/"><div class="card-image" style="background-image: url(https://cbs4indy.com/wp-content/uploads/sites/22/2020/05/0507_Featured.png?w=1280&h=720&crop=1)"></div></a>
	<div class="content">
		<div class="card-title"><a href="https://cbs4indy.com/news/indiana-reporting-650-new-coronavirus-cases-31-additional-deaths/">Indiana reporting 650 new coronavirus cases, 31 additional deaths</a></div>
		<div class="card-excerpt">INDIANAPOLIS — The Indiana State Department of Health (ISDH) reported 650 new positive coronavirus cases since Tuesday at noon, bringing the state’s total to 22,503. ISDH also announced an</div>
		<div class="card-meta">
			<span class="card-provider">WTTV</span> • <span class="card-date">5/7/2020</span>
		</div>
	</div>
  </div>
</div>
<div class="col-md-6 col-sm-12">
  <div class="content-card">
	<a href="https://apnews.com/638f679ef28a1982dfe14d03829bde1a"><div class="card-image" style="background-image: url(https://storage.googleapis.com/afs-prod/media/f0da2855770b44a8971dc36664b488fd/3000.jpeg)"></div></a>
	<div class="content">
		<div class="card-title"><a href="https://apnews.com/638f679ef28a1982dfe14d03829bde1a">Indiana launching new coronavirus testing at 20 sites</a></div>
		<div class="card-excerpt">Indiana’s expanded coronavirus testing program is set to start Wednesday at 20 sites around the state, although those tests still won’t be available to everybody. The</div>
		<div class="card-meta">
			<span class="card-provider">Associated Press</span> • <span class="card-date">5/5/2020</span>
		</div>
	</div>
  </div>
</div>
<div class="col-md-6 col-sm-12">
  <div class="content-card">
	<a href="https://www.wlwt.com/article/coronavirus-latest-20-969-cases-in-ohio-5-245-in-kentucky-21-033-in-indiana/32095068"><div class="card-image" style="background-image: url(https://kubrick.htvapps.com/htv-prod-media.s3.amazonaws.com/images/coronavirus-indy-1583511980.jpg?crop=1.00xw:1.00xh;0,0&resize=1200:*)"></div></a>
	<div class="content">
		<div class="card-title"><a href="https://www.wlwt.com/article/coronavirus-latest-20-969-cases-in-ohio-5-245-in-kentucky-21-033-in-indiana/32095068">Coronavirus latest: 20,969 cases in Ohio; 5,245 in Kentucky; 21,033 in Indiana</a></div>
		<div class="card-excerpt">The COVID-19 outbreak is continuing to change everyday life for millions of Americans. Leaders across the county, including the Tri-State area, are implementing measures to stop the spread, shutting down schools and restaurants and canceling events.</div>
		<div class="card-meta">
			<span class="card-provider">WLWT</span> • <span class="card-date">5/5/2020</span>
		</div>
	</div>
  </div>
</div>
<div class="col-md-6 col-sm-12">
  <div class="content-card">
	<a href="https://abc7chicago.com/covid-19-testing-near-me-hammond-indiana-reopen-coronavirus/6152239/"><div class="card-image" style="background-image: url(https://cdn.abcotvs.com/dip/images/6152218_050520-wls-hammond-testing5-vid.jpg)"></div></a>
	<div class="content">
		<div class="card-title"><a href="https://abc7chicago.com/covid-19-testing-near-me-hammond-indiana-reopen-coronavirus/6152239/">Coronavirus Indiana: COVID-19 testing site opening in Hammond, Ind.</a></div>
		<div class="card-excerpt">HAMMOND, Ind. (WLS) -- A new drive-thru COVID-19 testing site opens Tuesday in Hammond, Indiana. Much of Indiana has loosened stay-at-home restrictions, but not in Lake County, which has a much higher rate of cases than neighboring counties.</div>
		<div class="card-meta">
			<span class="card-provider">ABC 7 Chicago</span> • <span class="card-date">5/5/2020</span>
		</div>
	</div>
  </div>
</div>
<div class="col-md-6 col-sm-12">
  <div class="content-card">
	<a href="https://www.sfgate.com/news/article/Indiana-Supreme-Court-to-hold-May-oral-arguments-15242101.php"><div class="card-image" style="background-image: url(https://d29xw9s9x32j3w.cloudfront.net/players/library/placeholder.png)"></div></a>
	<div class="content">
		<div class="card-title"><a href="https://www.sfgate.com/news/article/Indiana-Supreme-Court-to-hold-May-oral-arguments-15242101.php">Indiana Supreme Court to hold May oral arguments remotely</a></div>
		<div class="card-excerpt">For the first time in its history, the Indiana Supreme Court will hold oral arguments using videoconferencing when it hears cases in May. That will honor social distancing guidelines during the ongoing public health emergency caused by coronavirus pandemic,</div>
		<div class="card-meta">
			<span class="card-provider">SFGate</span> • <span class="card-date">5/2/2020</span>
		</div>
	</div>
  </div>
</div>
<div class="col-md-6 col-sm-12">
  <div class="content-card">
	<a href="https://www.usatoday.com/story/money/2020/05/01/coronavirus-tyson-increases-bonuses-frontline-workers/3064769001/"><div class="card-image" style="background-image: url(https://www.gannett-cdn.com/presto/2020/04/16/USAT/431ee6d4-dda9-44f5-9e40-ed9f4f0756f4-AP_596776141462.jpg?auto=webp&crop=3503,1970,x0,y0&format=pjpg&width=1200)"></div></a>
	<div class="content">
		<div class="card-title"><a href="https://www.usatoday.com/story/money/2020/05/01/coronavirus-tyson-increases-bonuses-frontline-workers/3064769001/">Almost 900 Tyson Food workers in Indiana test positive for coronavirus per report</a></div>
		<div class="card-excerpt">But after reopening, it quickly closed again, with officials saying it would stay shuttered until all 2,200 workers were tested for the coronavirus and the company deemed the facility safe for workers.</div>
		<div class="card-meta">
			<span class="card-provider">USA Today</span> • <span class="card-date">5/1/2020</span>
		</div>
	</div>
  </div>
</div>
<div class="col-md-6 col-sm-12">
  <div class="content-card">
	<a href="https://www.foxnews.com/health/nearly-900-tyson-foods-plant-indiana-test-positive-coronavirus"><div class="card-image" style="background-image: url(https://a57.foxnews.com/static.foxnews.com/foxnews.com/content/uploads/2020/04/640/320/AP-Tyson-1.jpg?ve=1&tl=1)"></div></a>
	<div class="content">
		<div class="card-title"><a href="https://www.foxnews.com/health/nearly-900-tyson-foods-plant-indiana-test-positive-coronavirus">Nearly 900 workers at Tyson Foods plant in Indiana test positive for coronavirus</a></div>
		<div class="card-excerpt">Almost 900 workers at a Tyson Foods plant in Indiana have tested positive for the coronavirus, according to a report on Wednesday.</div>
		<div class="card-meta">
			<span class="card-provider">Fox News</span> • <span class="card-date">4/30/2020</span>
		</div>
	</div>
  </div>
</div>
<div class="col-md-6 col-sm-12">
  <div class="content-card">
	<a href="https://triblive.com/local/regional/covid-19-concerns-cancel-jimmy-stewart-airshow-in-indiana-county/"><div class="card-image" style="background-image: url(https://triblive.com/wp-content/uploads/2020/04/2604608_web1_gtr-MikeGoulianAerosports-050120.jpg)"></div></a>
	<div class="content">
		<div class="card-title"><a href="https://triblive.com/local/regional/covid-19-concerns-cancel-jimmy-stewart-airshow-in-indiana-county/">Covid-19 concerns cancel Jimmy Stewart Airshow in Indiana County</a></div>
		<div class="card-excerpt">Indiana County officials have canceled the Jimmy Stewart Airshow, planned for June 6 and 7, because of coronavirus concerns. The cancellation notice, posted late this week on the Indiana County Jimmy Stewart Airport website,</div>
		<div class="card-meta">
			<span class="card-provider">TribLIVE.com</span> • <span class="card-date">4/30/2020</span>
		</div>
	</div>
  </div>
</div>
<div class="col-md-6 col-sm-12">
  <div class="content-card">
	<a href="https://www.chron.com/news/article/Indiana-tops-1-000-in-confirmed-likely-15234363.php"><div class="card-image" style="background-image: url(https://d29xw9s9x32j3w.cloudfront.net/players/library/placeholder.png)"></div></a>
	<div class="content">
		<div class="card-title"><a href="https://www.chron.com/news/article/Indiana-tops-1-000-in-confirmed-likely-15234363.php">Contractor picked to spur Indiana's coronavirus tracing</a></div>
		<div class="card-excerpt">Indiana now has more than 1,000 people die with confirmed or likely coronavirus infections since the outbreak hit the state early last month, health officials said. The Indiana State Department of Health reported 63 additional deaths,</div>
		<div class="card-meta">
			<span class="card-provider">Houston Chronicle</span> • <span class="card-date">4/29/2020</span>
		</div>
	</div>
  </div>
</div>

</div>

