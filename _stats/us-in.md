---
category: stats
title: "US - Indiana State Coronavirus (COVID-19) Live Stats"
excerpt: "Live stats of COVID-19 in US-Indiana. Total Cases: 24643 (+191), Deaths: 1540 (+32), Recoveries: 1559(-)."
publishedDateTime: 2020-05-11T18:45:16Z
updatedDateTime: 2020-05-11T18:45:16Z
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
	    24643 (<span class='red'>+191</span>)
    </h3>
    <h3>
	    <div style="font-size: 18px; font-weight: 400;">Total Deaths:</div>
	    1540 (<span class='red'>+32</span>)
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
      ['1/22/2020', 0, 0, 0],['1/23/2020', 0, 0, 0],['1/24/2020', 0, 0, 0],['1/25/2020', 0, 0, 0],['1/26/2020', 0, 0, 0],['1/27/2020', 0, 0, 0],['1/28/2020', 0, 0, 0],['1/29/2020', 0, 0, 0],['1/30/2020', 0, 0, 0],['1/31/2020', 0, 0, 0],['2/1/2020', 0, 0, 0],['2/2/2020', 0, 0, 0],['2/3/2020', 0, 0, 0],['2/4/2020', 0, 0, 0],['2/5/2020', 0, 0, 0],['2/6/2020', 0, 0, 0],['2/7/2020', 0, 0, 0],['2/8/2020', 0, 0, 0],['2/9/2020', 0, 0, 0],['2/10/2020', 0, 0, 0],['2/11/2020', 0, 0, 0],['2/12/2020', 0, 0, 0],['2/13/2020', 0, 0, 0],['2/14/2020', 0, 0, 0],['2/15/2020', 0, 0, 0],['2/16/2020', 0, 0, 0],['2/17/2020', 0, 0, 0],['2/18/2020', 0, 0, 0],['2/19/2020', 0, 0, 0],['2/20/2020', 0, 0, 0],['2/21/2020', 0, 0, 0],['2/22/2020', 0, 0, 0],['2/23/2020', 0, 0, 0],['2/24/2020', 0, 0, 0],['2/25/2020', 0, 0, 0],['2/26/2020', 0, 0, 0],['2/27/2020', 0, 0, 0],['2/28/2020', 0, 0, 0],['2/29/2020', 0, 0, 0],['3/1/2020', 0, 0, 0],['3/2/2020', 0, 0, 0],['3/3/2020', 0, 0, 0],['3/4/2020', 0, 0, 0],['3/5/2020', 0, 0, 0],['3/6/2020', 1, 0, 0],['3/7/2020', 1, 0, 0],['3/8/2020', 2, 0, 0],['3/9/2020', 3, 0, 0],['3/10/2020', 6, 0, 0],['3/11/2020', 11, 0, 0],['3/12/2020', 12, 0, 0],['3/13/2020', 12, 0, 0],['3/14/2020', 15, 0, 0],['3/15/2020', 20, 0, 0],['3/16/2020', 24, 2, 0],['3/17/2020', 30, 2, 0],['3/18/2020', 39, 2, 0],['3/19/2020', 61, 2, 0],['3/20/2020', 87, 3, 0],['3/21/2020', 128, 4, 0],['3/22/2020', 204, 7, 0],['3/23/2020', 271, 7, 0],['3/24/2020', 370, 12, 0],['3/25/2020', 479, 14, 0],['3/26/2020', 657, 17, 0],['3/27/2020', 981, 25, 0],['3/28/2020', 1232, 31, 0],['3/29/2020', 1514, 32, 0],['3/30/2020', 1787, 35, 0],['3/31/2020', 2159, 49, 0],['4/1/2020', 2569, 65, 0],['4/2/2020', 3039, 78, 0],['4/3/2020', 3437, 102, 0],['4/4/2020', 3973, 117, 0],['4/5/2020', 4431, 128, 0],['4/6/2020', 4976, 144, 0],['4/7/2020', 5530, 174, 0],['4/8/2020', 5963, 204, 28],['4/9/2020', 6371, 246, 28],['4/10/2020', 6925, 301, 58],['4/11/2020', 7451, 331, 58],['4/12/2020', 7941, 344, 105],['4/13/2020', 8310, 354, 105],['4/14/2020', 8515, 387, 131],['4/15/2020', 8949, 436, 146],['4/16/2020', 9537, 480, 150],['4/17/2020', 10154, 519, 150],['4/18/2020', 10641, 545, 173],['4/19/2020', 11211, 562, 1557],['4/20/2020', 11688, 577, 1559],['4/21/2020', 12097, 635, 1559],['4/22/2020', 12438, 666, 1559],['4/23/2020', 13039, 706, 1559],['4/24/2020', 13041, 706, 1559],['4/25/2020', 14399, 785, 175],['4/26/2020', 15023, 813, 175],['4/27/2020', 15971, 932, 175],['4/28/2020', 16592, 992, 175],['4/29/2020', 17186, 1065, 175],['4/30/2020', 17989, 1114, 175],['5/1/2020', 18626, 1166, 175],['5/2/2020', 19310, 1229, 175],['5/3/2020', 19944, 1246, 175],['5/4/2020', 20518, 1264, 175],['5/5/2020', 21046, 1326, 175],['5/6/2020', 21885, 1377, 1559],['5/7/2020', 22748, 1414, 1559],['5/8/2020', 23387, 1447, 1559],['5/9/2020', 24006, 1490, 1559],['5/10/2020', 24452, 1508, 1559],['5/11/2020', 24643, 1540, 1559],
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
      [39.8522, -77.2865, "Adams", 9, 1],[41.1966, -84.9245, "Allen", 821, 63],[39.2094, -85.9183, "Bartholomew", 349, 29],[40.0106, -86.4997, "Boone", 237, 34],[39.3085, -86.1227, "Brown", 26, 1],[40.5452, -86.5242, "Carroll", 71, 2],[40.8644, -86.5, "Cass", 1522, 4],[38.5395, -85.7655, "Clark", 382, 30],[39.2769, -87.1126, "Clay", 24, 1],[40.1944, -86.6671, "Clinton", 89, 2],[38.3714, -86.3444, "Crawford", 21, 1],[39.0676, -84.9053, "Dearborn", 150, 13],[39.4279, -85.6286, "Decatur", 220, 31],[41.3147, -84.9012, "DeKalb", 24, 2],[40.3138, -85.5009, "Delaware", 225, 15],[38.3934, -86.9404, "Dubois", 45, 0],[41.5336, -86.0138, "Elkhart", 487, 18],[39.6582, -85.141, "Fayette", 62, 4],[38.3513, -85.9372, "Floyd", 233, 29],[40.1089, -87.1577, "Fountain", 16, 2],[39.4233, -85.0114, "Franklin", 107, 8],[41.0192, -86.4125, "Fulton", 36, 1],[38.2786, -87.377, "Gibson", 8, 0],[40.6126, -85.5592, "Grant", 172, 17],[38.9879, -87.0813, "Greene", 151, 13],[39.9658, -86.1461, "Hamilton", 935, 84],[39.8857, -85.6086, "Hancock", 266, 19],[38.124, -85.9736, "Harrison", 158, 12],[39.8065, -86.5401, "Hendricks", 976, 65],[39.9973, -85.2512, "Henry", 84, 2],[40.4483, -86.1345, "Howard", 246, 10],[40.741, -85.5618, "Huntington", 14, 2],[38.8247, -86.1716, "Jackson", 280, 1],[40.9059, -87.1612, "Jasper", 46, 1],[38.9853, -85.6106, "Jennings", 98, 5],[39.4638, -86.1345, "Johnson", 822, 89],[38.7991, -87.4604, "Knox", 22, 0],[41.0743, -85.8923, "Kosciusko", 42, 2],[41.648, -85.4179, "LaGrange", 39, 2],[41.443, -87.4702, "Lake", 2469, 134],[41.7563, -86.8181, "LaPorte", 324, 11],[38.9172, -86.5557, "Lawrence", 117, 17],[40.2743, -85.8371, "Madison", 512, 66],[39.8362, -86.1752, "Marion", 7405, 448],[41.2159, -86.4236, "Marshall", 33, 1],[40.602, -85.9275, "Miami", 126, 1],[39.1637, -86.5257, "Monroe", 143, 9],[40.0428, -86.8975, "Montgomery", 128, 5],[39.5337, -86.3778, "Morgan", 200, 9],[40.9523, -87.299, "Newton", 66, 10],[41.4277, -85.355, "Noble", 133, 16],[38.9531, -84.8546, "Ohio", 9, 0],[38.5462, -86.6202, "Orange", 115, 19],[39.2861, -86.7726, "Owen", 28, 1],[41.685, -86.9804, "Porter", 320, 10],[38.2042, -87.9151, "Posey", 15, 0],[39.5211, -86.7995, "Putnam", 90, 5],[40.1898, -85.2037, "Randolph", 37, 2],[39.2373, -85.0931, "Ripley", 101, 6],[39.4981, -85.4676, "Rush", 48, 2],[38.6854, -85.7831, "Scott", 81, 2],[39.6738, -85.7052, "Shelby", 325, 23],[41.6228, -86.3377, "St. Joseph", 817, 30],[41.1989, -86.8922, "Starke", 22, 2],[41.6432, -85.005, "Steuben", 63, 2],[39.0973, -87.4074, "Sullivan", 20, 0],[38.7427, -85.0783, "Switzerland", 16, 0],[40.5076, -86.8527, "Tippecanoe", 234, 2],[40.3795, -86.0868, "Tipton", 21, 1],[38.024, -87.512, "Vanderburgh", 185, 2],[39.4936, -87.2667, "Vigo", 81, 7],[40.9807, -85.8393, "Wabash", 64, 2],[40.1973, -87.527, "Warren", 13, 1],[38.0469, -87.2847, "Warrick", 123, 20],[38.5549, -86.2778, "Washington", 48, 1],[39.9447, -84.8308, "Wayne", 150, 5],[40.6568, -85.2225, "Wells", 10, 0],[40.6622, -86.8678, "White", 148, 1],[41.2308, -85.3201, "Whitley", 22, 1],[38.7369, -85.5387, "Jefferson", 36, 0],[40.4882, -87.0857, "Benton", 12, 0],[40.492, -85.1468, "Jay", 23, 0],[40.4537, -85.3736, "Blackford", 14, 1],[38.1692, -86.8257, "Spencer", 10, 1],[39.7665, -87.2295, "Parke", 20, 0],[39.6349, -84.926, "Union", 19, 0],[38.7221, -86.8002, "Martin", 7, 0],[38.6679, -86.9974, "Daviess", 56, 17],[39.667, -87.5203, "Vermillion", 8, 0],[41.0535, -86.6037, "Pulaski", 34, 0],[37.9106, -86.7377, "Perry", 24, 0],[38.3827, -87.2129, "Pike", 3, 0],
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
      [{v:"Adams", f:"Adams"}, 9, 0, 8, 1, 0, 0],[{v:"Allen", f:"Allen"}, 821, 5, 758, 63, 0, 0],[{v:"Bartholomew", f:"Bartholomew"}, 349, 3, 320, 29, 3, 0],[{v:"Boone", f:"Boone"}, 237, 4, 203, 34, 1, 0],[{v:"Brown", f:"Brown"}, 26, 0, 25, 1, 0, 0],[{v:"Carroll", f:"Carroll"}, 71, 0, 69, 2, 0, 0],[{v:"Cass", f:"Cass"}, 1522, 2, 1518, 4, 1, 0],[{v:"Clark", f:"Clark"}, 382, 3, 352, 30, 0, 0],[{v:"Clay", f:"Clay"}, 24, 0, 23, 1, 0, 0],[{v:"Clinton", f:"Clinton"}, 89, 1, 87, 2, 0, 0],[{v:"Crawford", f:"Crawford"}, 21, 0, 20, 1, 0, 0],[{v:"Dearborn", f:"Dearborn"}, 150, 0, 137, 13, 0, 0],[{v:"Decatur", f:"Decatur"}, 220, 0, 189, 31, 0, 0],[{v:"DeKalb", f:"DeKalb"}, 24, 0, 22, 2, 0, 0],[{v:"Delaware", f:"Delaware"}, 225, 0, 210, 15, 0, 0],[{v:"Dubois", f:"Dubois"}, 45, 0, 45, 0, 0, 0],[{v:"Elkhart", f:"Elkhart"}, 487, 3, 469, 18, 0, 0],[{v:"Fayette", f:"Fayette"}, 62, 0, 58, 4, 0, 0],[{v:"Floyd", f:"Floyd"}, 233, 1, 204, 29, 0, 0],[{v:"Fountain", f:"Fountain"}, 16, 0, 14, 2, 0, 0],[{v:"Franklin", f:"Franklin"}, 107, 0, 46, 8, 0, 53],[{v:"Fulton", f:"Fulton"}, 36, 0, 35, 1, 0, 0],[{v:"Gibson", f:"Gibson"}, 8, 0, 8, 0, 0, 0],[{v:"Grant", f:"Grant"}, 172, 0, 155, 17, 0, 0],[{v:"Greene", f:"Greene"}, 151, 0, 138, 13, 2, 0],[{v:"Hamilton", f:"Hamilton"}, 935, 5, 851, 84, 0, 0],[{v:"Hancock", f:"Hancock"}, 266, 0, 247, 19, 0, 0],[{v:"Harrison", f:"Harrison"}, 158, 1, 146, 12, 0, 0],[{v:"Hendricks", f:"Hendricks"}, 976, 7, 911, 65, 0, 0],[{v:"Henry", f:"Henry"}, 84, 3, 82, 2, 0, 0],[{v:"Howard", f:"Howard"}, 246, 1, 236, 10, 0, 0],[{v:"Huntington", f:"Huntington"}, 14, 0, 12, 2, 0, 0],[{v:"Jackson", f:"Jackson"}, 280, 2, 279, 1, 0, 0],[{v:"Jasper", f:"Jasper"}, 46, 0, 45, 1, 0, 0],[{v:"Jennings", f:"Jennings"}, 98, 1, 93, 5, 0, 0],[{v:"Johnson", f:"Johnson"}, 822, 15, 730, 89, 0, 3],[{v:"Knox", f:"Knox"}, 22, 1, 22, 0, 0, 0],[{v:"Kosciusko", f:"Kosciusko"}, 42, 1, 40, 2, 0, 0],[{v:"LaGrange", f:"LaGrange"}, 39, 1, 37, 2, 0, 0],[{v:"Lake", f:"Lake"}, 2469, 24, 2335, 134, 2, 0],[{v:"LaPorte", f:"LaPorte"}, 324, 0, 313, 11, 0, 0],[{v:"Lawrence", f:"Lawrence"}, 117, 0, 100, 17, 1, 0],[{v:"Madison", f:"Madison"}, 512, 6, 446, 66, 1, 0],[{v:"Marion", f:"Marion"}, 7405, 69, 6957, 448, 4, 0],[{v:"Marshall", f:"Marshall"}, 33, 0, 32, 1, 0, 0],[{v:"Miami", f:"Miami"}, 126, 1, 125, 1, 0, 0],[{v:"Monroe", f:"Monroe"}, 143, 0, 134, 9, 0, 0],[{v:"Montgomery", f:"Montgomery"}, 128, 1, 123, 5, 0, 0],[{v:"Morgan", f:"Morgan"}, 200, 3, 191, 9, 0, 0],[{v:"Newton", f:"Newton"}, 66, 0, 56, 10, 0, 0],[{v:"Noble", f:"Noble"}, 133, 1, 117, 16, 1, 0],[{v:"Ohio", f:"Ohio"}, 9, 0, 9, 0, 0, 0],[{v:"Orange", f:"Orange"}, 115, 1, 96, 19, 0, 0],[{v:"Owen", f:"Owen"}, 28, 0, 27, 1, 0, 0],[{v:"Porter", f:"Porter"}, 320, 5, 246, 10, 0, 64],[{v:"Posey", f:"Posey"}, 15, 0, 15, 0, 0, 0],[{v:"Putnam", f:"Putnam"}, 90, 0, 85, 5, 0, 0],[{v:"Randolph", f:"Randolph"}, 37, 0, 35, 2, 0, 0],[{v:"Ripley", f:"Ripley"}, 101, 0, 95, 6, 0, 0],[{v:"Rush", f:"Rush"}, 48, 0, 46, 2, 0, 0],[{v:"Scott", f:"Scott"}, 81, 0, 79, 2, 0, 0],[{v:"Shelby", f:"Shelby"}, 325, 6, 302, 23, 0, 0],[{v:"St. Joseph", f:"St. Joseph"}, 817, 7, 787, 30, 0, 0],[{v:"Starke", f:"Starke"}, 22, 0, 20, 2, 0, 0],[{v:"Steuben", f:"Steuben"}, 63, 0, 61, 2, 0, 0],[{v:"Sullivan", f:"Sullivan"}, 20, 0, 20, 0, 0, 0],[{v:"Switzerland", f:"Switzerland"}, 16, 0, 16, 0, 0, 0],[{v:"Tippecanoe", f:"Tippecanoe"}, 234, 1, 232, 2, 0, 0],[{v:"Tipton", f:"Tipton"}, 21, 0, 20, 1, 0, 0],[{v:"Vanderburgh", f:"Vanderburgh"}, 185, 0, 128, 2, 0, 55],[{v:"Vigo", f:"Vigo"}, 81, 1, 74, 7, 0, 0],[{v:"Wabash", f:"Wabash"}, 64, 0, 62, 2, 0, 0],[{v:"Warren", f:"Warren"}, 13, 0, 12, 1, 0, 0],[{v:"Warrick", f:"Warrick"}, 123, 0, 103, 20, 0, 0],[{v:"Washington", f:"Washington"}, 48, 0, 47, 1, 0, 0],[{v:"Wayne", f:"Wayne"}, 150, 1, 145, 5, 0, 0],[{v:"Wells", f:"Wells"}, 10, 0, 10, 0, 0, 0],[{v:"White", f:"White"}, 148, 0, 147, 1, 0, 0],[{v:"Whitley", f:"Whitley"}, 22, 0, 21, 1, 0, 0],[{v:"Jefferson", f:"Jefferson"}, 36, 1, 36, 0, 0, 0],[{v:"Benton", f:"Benton"}, 12, 0, 12, 0, 0, 0],[{v:"Jay", f:"Jay"}, 23, 1, 23, 0, 0, 0],[{v:"Blackford", f:"Blackford"}, 14, 0, 13, 1, 0, 0],[{v:"Spencer", f:"Spencer"}, 10, 0, 9, 1, 0, 0],[{v:"Parke", f:"Parke"}, 20, 1, 20, 0, 0, 0],[{v:"Union", f:"Union"}, 19, 0, 19, 0, 0, 0],[{v:"Martin", f:"Martin"}, 7, 0, 7, 0, 0, 0],[{v:"Daviess", f:"Daviess"}, 56, 0, 39, 17, 0, 0],[{v:"Vermillion", f:"Vermillion"}, 8, 0, 8, 0, 0, 0],[{v:"Pulaski", f:"Pulaski"}, 34, 0, 34, 0, 0, 0],[{v:"Perry", f:"Perry"}, 24, 1, 24, 0, 0, 0],[{v:"Pike", f:"Pike"}, 3, 0, 3, 0, 0, 0],
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

</div>

