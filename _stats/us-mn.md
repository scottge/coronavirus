---
category: stats
title: "US - Minnesota State Coronavirus (COVID-19) Live Stats"
excerpt: "Live stats of COVID-19 in US-Minnesota. Total Cases: 12494 (+694), Deaths: 614 (+23), Recoveries: 8223(+687)."
publishedDateTime: 2020-05-12T18:45:13Z
updatedDateTime: 2020-05-12T18:45:13Z
webUrl: "https://smartable.ai/apps/coronavirus/stats/us-mn/"
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
  - url: "https://smartable.azureedge.net/coronavirus/sites/2/2020/us-mn.jpg"
    width: 900
    height: 564
    title: "US - Minnesota State Coronavirus (COVID-19) Live Stats"

---
<div class="total-stats" style="text-align: center;">
    <h3>
	    <div style="font-size: 18px; font-weight: 400;">Total Confirmed Cases:</div>
	    12494 (<span class='red'>+694</span>)
    </h3>
    <h3>
	    <div style="font-size: 18px; font-weight: 400;">Total Deaths:</div>
	    614 (<span class='red'>+23</span>)
    </h3>
    <h3>
	    <div style="font-size: 18px; font-weight: 400;">Total Recovered:</div>
	    8223 (<span class='green'>+687</span>)
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
      ['1/22/2020', 0, 0, 0],['1/23/2020', 0, 0, 0],['1/24/2020', 0, 0, 0],['1/25/2020', 0, 0, 0],['1/26/2020', 0, 0, 0],['1/27/2020', 0, 0, 0],['1/28/2020', 0, 0, 0],['1/29/2020', 0, 0, 0],['1/30/2020', 0, 0, 0],['1/31/2020', 0, 0, 0],['2/1/2020', 0, 0, 0],['2/2/2020', 0, 0, 0],['2/3/2020', 0, 0, 0],['2/4/2020', 0, 0, 0],['2/5/2020', 0, 0, 0],['2/6/2020', 0, 0, 0],['2/7/2020', 0, 0, 0],['2/8/2020', 0, 0, 0],['2/9/2020', 0, 0, 0],['2/10/2020', 0, 0, 0],['2/11/2020', 0, 0, 0],['2/12/2020', 0, 0, 0],['2/13/2020', 0, 0, 0],['2/14/2020', 0, 0, 0],['2/15/2020', 0, 0, 0],['2/16/2020', 0, 0, 0],['2/17/2020', 0, 0, 0],['2/18/2020', 0, 0, 0],['2/19/2020', 0, 0, 0],['2/20/2020', 0, 0, 0],['2/21/2020', 0, 0, 0],['2/22/2020', 0, 0, 0],['2/23/2020', 0, 0, 0],['2/24/2020', 0, 0, 0],['2/25/2020', 0, 0, 0],['2/26/2020', 0, 0, 0],['2/27/2020', 0, 0, 0],['2/28/2020', 0, 0, 0],['2/29/2020', 0, 0, 0],['3/1/2020', 0, 0, 0],['3/2/2020', 0, 0, 0],['3/3/2020', 0, 0, 0],['3/4/2020', 0, 0, 0],['3/5/2020', 0, 0, 0],['3/6/2020', 1, 0, 0],['3/7/2020', 1, 0, 0],['3/8/2020', 1, 0, 0],['3/9/2020', 2, 0, 0],['3/10/2020', 2, 0, 0],['3/11/2020', 5, 0, 0],['3/12/2020', 13, 0, 0],['3/13/2020', 14, 0, 0],['3/14/2020', 32, 0, 0],['3/15/2020', 35, 0, 0],['3/16/2020', 73, 0, 0],['3/17/2020', 66, 0, 0],['3/18/2020', 77, 0, 0],['3/19/2020', 89, 0, 0],['3/20/2020', 116, 0, 0],['3/21/2020', 138, 1, 0],['3/22/2020', 170, 1, 24],['3/23/2020', 236, 1, 24],['3/24/2020', 263, 1, 24],['3/25/2020', 288, 1, 122],['3/26/2020', 347, 2, 122],['3/27/2020', 399, 4, 122],['3/28/2020', 442, 5, 122],['3/29/2020', 504, 9, 122],['3/30/2020', 577, 10, 260],['3/31/2020', 630, 12, 260],['4/1/2020', 690, 17, 342],['4/2/2020', 743, 18, 342],['4/3/2020', 790, 22, 410],['4/4/2020', 866, 24, 440],['4/5/2020', 936, 29, 451],['4/6/2020', 987, 30, 470],['4/7/2020', 1070, 34, 549],['4/8/2020', 1155, 39, 632],['4/9/2020', 1243, 50, 675],['4/10/2020', 1337, 57, 732],['4/11/2020', 1428, 64, 732],['4/12/2020', 1622, 70, 842],['4/13/2020', 1651, 70, 842],['4/14/2020', 1718, 79, 909],['4/15/2020', 1832, 87, 940],['4/16/2020', 1935, 95, 1020],['4/17/2020', 2093, 111, 1066],['4/18/2020', 2236, 121, 1118],['4/19/2020', 2379, 134, 1160],['4/20/2020', 2493, 143, 1160],['4/21/2020', 2590, 160, 1160],['4/22/2020', 2745, 179, 1160],['4/23/2020', 2965, 200, 1536],['4/24/2020', 3208, 221, 1536],['4/25/2020', 3464, 244, 1654],['4/26/2020', 3617, 272, 1774],['4/27/2020', 3835, 286, 1842],['4/28/2020', 4198, 301, 1912],['4/29/2020', 4660, 319, 2043],['4/30/2020', 5150, 343, 2172],['5/1/2020', 5676, 366, 2284],['5/2/2020', 6257, 395, 2397],['5/3/2020', 6682, 419, 3015],['5/4/2020', 7262, 428, 4212],['5/5/2020', 7856, 455, 4614],['5/6/2020', 8593, 485, 5005],['5/7/2020', 9371, 508, 5308],['5/8/2020', 10088, 534, 5697],['5/9/2020', 10797, 558, 6322],['5/10/2020', 11277, 578, 6882],['5/11/2020', 11800, 591, 7536],['5/12/2020', 12494, 614, 8223],
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
      [45.3293, -93.2197, "Anoka", 571, 29],[47.5065, -94.997, "Beltrami", 6, 0],[45.7525, -94.2317, "Benton", 93, 2],[45.5723, -96.294, "Big Stone", 2, 0],[43.9626, -94.1666, "Blue earth", 22, 0],[44.8254, -93.7842, "Carver", 92, 1],[47.0568, -93.9126, "Cass", 8, 1],[45.6875, -92.9654, "Chisago", 20, 1],[46.7105, -96.5579, "Clay", 247, 17],[47.6962, -95.4287, "Clearwater", 2, 0],[43.9096, -95.0461, "Cottonwood", 47, 0],[44.9096, -93.1301, "Dakota", 471, 15],[44.1529, -92.8995, "Dodge", 26, 0],[45.9741, -95.2925, "Douglas", 16, 0],[43.7677, -94.0174, "Faribault", 12, 0],[44.4088, -93.0303, "Goodhue", 25, 0],[44.9394, -93.5891, "Hennepin", 3744, 398],[45.7223, -93.1717, "Isanti", 8, 0],[47.3207, -93.7859, "Itasca", 33, 0],[43.6288, -94.9886, "Jackson", 33, 0],[45.4054, -94.8397, "Kandiyohi", 316, 1],[44.2236, -93.5747, "Le Sueur", 30, 0],[44.3814, -96.1812, "Lincoln", 4, 0],[47.3219, -95.9512, "Mahnomen", 3, 1],[43.6441, -94.4621, "Martin", 112, 4],[44.9431, -94.5197, "Meeker", 21, 0],[43.5133, -92.5078, "Mower", 45, 0],[44.3296, -93.9659, "Nicollet", 21, 2],[43.9952, -92.3814, "Olmsted", 374, 9],[46.3798, -96.1309, "Otter Tail", 25, 0],[44.9964, -93.0616, "Ramsey", 986, 47],[44.5283, -94.7231, "Renville", 6, 0],[44.4551, -93.1697, "Rice", 126, 2],[44.7251, -93.4409, "Scott", 155, 1],[45.4416, -93.5981, "Sherburne", 114, 1],[44.6728, -94.232, "Sibley", 4, 0],[47.5312, -92.2399, "St. Louis", 96, 12],[45.465, -94.3222, "Stearns", 1443, 6],[43.8683, -93.0552, "Steele", 65, 0],[44.3707, -92.042, "Wabasha", 13, 0],[46.629, -95.0878, "Wadena", 4, 0],[43.8938, -93.4939, "Waseca", 16, 0],[45.0598, -92.9777, "Washington", 256, 15],[44.0535, -94.8378, "Watonwan", 25, 0],[46.2769, -96.3122, "Wilkin", 12, 3],[43.9837, -91.868, "Winona", 71, 15],[45.092, -93.7453, "Wright", 110, 1],[44.1488, -94.4945, "Brown", 9, 1],[45.5947, -96.8327, "Traverse", 3, 0],[46.5616, -92.6279, "Carlton", 64, 0],[44.4488, -95.7897, "Lyon", 18, 0],[43.7659, -93.5645, "Freeborn", 46, 0],[46.169, -94.363, "Crow Wing", 24, 1],[44.6918, -95.6194, "Yellow Medicine", 3, 0],[47.9209, -94.2132, "Koochiching", 2, 0],[44.7699, -94.1513, "McLeod", 13, 0],[47.6966, -96.144, "Polk", 53, 1],[43.6992, -91.2823, "Houston", 2, 0],[43.9546, -96.1905, "Pipestone", 7, 0],[44.0704, -95.6668, "Murray", 29, 0],[44.2098, -95.1297, "Redwood", 3, 0],[45.2814, -95.7559, "Swift", 8, 0],[48.8445, -95.7624, "Roseau", 1, 0],[45.8367, -92.9683, "Pine", 73, 0],[43.8266, -95.4823, "Nobles", 1269, 2],[46.8066, -95.3526, "Becker", 25, 0],[43.5275, -96.3591, "Rock", 19, 0],[46.324, -95.0903, "Todd", 38, 0],[47.8837, -96.2727, "Red Lake", 2, 0],[43.8879, -94.1583, "Blue Earth", 67, 0],[43.6137, -92.4263, "Fillmore", 13, 1],[45.0127, -96.1889, "Lac qui Parle", 2, 0],[47.1761, -96.8015, "Norman", 10, 0],[45.5689, -93.59, "Mille Lacs", 7, 1],[46.5303, -93.7051, "Aitkin", 2, 0],[48.8577, -96.8019, "Kittson", 1, 0],[48.2929, -96.1945, "Marshall", 8, 0],[45.9772, -94.1008, "Morrison", 14, 0],[44.9583, -95.3672, "Chippewa", 14, 0],[48.0135, -96.2137, "Pennington", 1, 0],[45.9329034, -93.2883531, "Kanabec", 10, 0],[45.9729315, -96.0471362, "Grant", 2, 0],[45.5472257, -95.4363717, "Pope", 5, 0],[47.5964304, -91.4964639, "Lake", 1, 0],[45.5215118, -95.9522178, "Stevens", 1, 0],
    ]);
    var options = {
      backgroundColor: {fill:'transparent',stroke:'#FFF' ,strokeWidth:0 }, 
      displayMode: 'markers',
      region: 'US-MN', 
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
      [{v:"Anoka", f:"Anoka"}, 571, 0, 542, 29, 0, 0],[{v:"Beltrami", f:"Beltrami"}, 6, 0, 6, 0, 0, 0],[{v:"Benton", f:"Benton"}, 93, 0, 91, 2, 0, 0],[{v:"Big Stone", f:"Big Stone"}, 2, 0, 2, 0, 0, 0],[{v:"Blue earth", f:"Blue earth"}, 22, 0, 22, 0, 0, 0],[{v:"Carver", f:"Carver"}, 92, 0, 91, 1, 0, 0],[{v:"Cass", f:"Cass"}, 8, 0, 7, 1, 0, 0],[{v:"Chisago", f:"Chisago"}, 20, 0, 19, 1, 0, 0],[{v:"Clay", f:"Clay"}, 247, 0, 230, 17, 0, 0],[{v:"Clearwater", f:"Clearwater"}, 2, 0, 2, 0, 0, 0],[{v:"Cottonwood", f:"Cottonwood"}, 47, 0, 47, 0, 0, 0],[{v:"Dakota", f:"Dakota"}, 471, 0, 456, 15, 0, 0],[{v:"Dodge", f:"Dodge"}, 26, 0, 26, 0, 0, 0],[{v:"Douglas", f:"Douglas"}, 16, 0, 16, 0, 0, 0],[{v:"Faribault", f:"Faribault"}, 12, 0, 12, 0, 0, 0],[{v:"Goodhue", f:"Goodhue"}, 25, 0, 25, 0, 0, 0],[{v:"Hennepin", f:"Hennepin"}, 3744, 0, 3346, 398, 0, 0],[{v:"Isanti", f:"Isanti"}, 8, 0, 8, 0, 0, 0],[{v:"Itasca", f:"Itasca"}, 33, 0, 33, 0, 0, 0],[{v:"Jackson", f:"Jackson"}, 33, 0, 33, 0, 0, 0],[{v:"Kandiyohi", f:"Kandiyohi"}, 316, 0, 315, 1, 0, 0],[{v:"Le Sueur", f:"Le Sueur"}, 30, 0, 30, 0, 0, 0],[{v:"Lincoln", f:"Lincoln"}, 4, 0, 4, 0, 0, 0],[{v:"Mahnomen", f:"Mahnomen"}, 3, 0, 2, 1, 0, 0],[{v:"Martin", f:"Martin"}, 112, 0, 108, 4, 0, 0],[{v:"Meeker", f:"Meeker"}, 21, 0, 21, 0, 0, 0],[{v:"Mower", f:"Mower"}, 45, 0, 45, 0, 0, 0],[{v:"Nicollet", f:"Nicollet"}, 21, 0, 19, 2, 0, 0],[{v:"Olmsted", f:"Olmsted"}, 374, 0, 365, 9, 0, 0],[{v:"Otter Tail", f:"Otter Tail"}, 25, 0, 25, 0, 0, 0],[{v:"Ramsey", f:"Ramsey"}, 986, 0, 939, 47, 0, 0],[{v:"Renville", f:"Renville"}, 6, 0, 6, 0, 0, 0],[{v:"Rice", f:"Rice"}, 126, 0, 124, 2, 0, 0],[{v:"Scott", f:"Scott"}, 155, 0, 154, 1, 0, 0],[{v:"Sherburne", f:"Sherburne"}, 114, 0, 113, 1, 0, 0],[{v:"Sibley", f:"Sibley"}, 4, 0, 4, 0, 0, 0],[{v:"St. Louis", f:"St. Louis"}, 96, 0, 84, 12, 0, 0],[{v:"Stearns", f:"Stearns"}, 1443, 0, 1437, 6, 0, 0],[{v:"Steele", f:"Steele"}, 65, 0, 65, 0, 0, 0],[{v:"Wabasha", f:"Wabasha"}, 13, 0, 13, 0, 0, 0],[{v:"Wadena", f:"Wadena"}, 4, 0, 4, 0, 0, 0],[{v:"Waseca", f:"Waseca"}, 16, 0, 16, 0, 0, 0],[{v:"Washington", f:"Washington"}, 256, 0, 241, 15, 0, 0],[{v:"Watonwan", f:"Watonwan"}, 25, 0, 25, 0, 0, 0],[{v:"Wilkin", f:"Wilkin"}, 12, 0, 9, 3, 0, 0],[{v:"Winona", f:"Winona"}, 71, 0, 56, 15, 0, 0],[{v:"Wright", f:"Wright"}, 110, 0, 109, 1, 0, 0],[{v:"Brown", f:"Brown"}, 9, 0, 8, 1, 0, 0],[{v:"Traverse", f:"Traverse"}, 3, 0, 3, 0, 0, 0],[{v:"Carlton", f:"Carlton"}, 64, 0, 64, 0, 0, 0],[{v:"Lyon", f:"Lyon"}, 18, 0, 18, 0, 0, 0],[{v:"Freeborn", f:"Freeborn"}, 46, 0, 46, 0, 0, 0],[{v:"Crow Wing", f:"Crow Wing"}, 24, 0, 23, 1, 0, 0],[{v:"Yellow Medicine", f:"Yellow Medicine"}, 3, 0, 3, 0, 0, 0],[{v:"Koochiching", f:"Koochiching"}, 2, 0, 2, 0, 0, 0],[{v:"McLeod", f:"McLeod"}, 13, 0, 13, 0, 0, 0],[{v:"Polk", f:"Polk"}, 53, 0, 52, 1, 0, 0],[{v:"Houston", f:"Houston"}, 2, 0, 2, 0, 0, 0],[{v:"Pipestone", f:"Pipestone"}, 7, 0, 7, 0, 0, 0],[{v:"Murray", f:"Murray"}, 29, 0, 29, 0, 0, 0],[{v:"Redwood", f:"Redwood"}, 3, 0, 3, 0, 0, 0],[{v:"Swift", f:"Swift"}, 8, 0, 8, 0, 0, 0],[{v:"Roseau", f:"Roseau"}, 1, 0, 1, 0, 0, 0],[{v:"Pine", f:"Pine"}, 73, 0, 73, 0, 0, 0],[{v:"Nobles", f:"Nobles"}, 1269, 0, 1267, 2, 0, 0],[{v:"Becker", f:"Becker"}, 25, 0, 25, 0, 0, 0],[{v:"Rock", f:"Rock"}, 19, 0, 19, 0, 0, 0],[{v:"Todd", f:"Todd"}, 38, 0, 38, 0, 0, 0],[{v:"Red Lake", f:"Red Lake"}, 2, 0, 2, 0, 0, 0],[{v:"Blue Earth", f:"Blue Earth"}, 67, 0, 67, 0, 0, 0],[{v:"Fillmore", f:"Fillmore"}, 13, 0, 12, 1, 0, 0],[{v:"Lac qui Parle", f:"Lac qui Parle"}, 2, 0, 2, 0, 0, 0],[{v:"Norman", f:"Norman"}, 10, 0, 10, 0, 0, 0],[{v:"Mille Lacs", f:"Mille Lacs"}, 7, 0, 6, 1, 0, 0],[{v:"Aitkin", f:"Aitkin"}, 2, 0, 2, 0, 0, 0],[{v:"Kittson", f:"Kittson"}, 1, 0, 1, 0, 0, 0],[{v:"Marshall", f:"Marshall"}, 8, 0, 8, 0, 0, 0],[{v:"Morrison", f:"Morrison"}, 14, 0, 14, 0, 0, 0],[{v:"Chippewa", f:"Chippewa"}, 14, 0, 14, 0, 0, 0],[{v:"Pennington", f:"Pennington"}, 1, 0, 1, 0, 0, 0],[{v:"Kanabec", f:"Kanabec"}, 10, 0, 10, 0, 0, 0],[{v:"Grant", f:"Grant"}, 2, 0, 2, 0, 0, 0],[{v:"Pope", f:"Pope"}, 5, 0, 5, 0, 0, 0],[{v:"Lake", f:"Lake"}, 1, 0, 1, 0, 0, 0],[{v:"Stevens", f:"Stevens"}, 1, 0, 1, 0, 0, 0],
    ]);
    data.setProperty(0, 0, 'style', 'min-width:100px');
    var table = new google.visualization.Table(document.getElementById('geo_table'));
    table.draw(data, {allowHtml: true, sortColumn: 2, sortAscending: false, width: '660px', height: '100%'});
  }
</script>

<span style="font-size: 13px">All COVID-19 data displayed on the page is available through our FREE <a href="https://developer.smartable.ai">API program</a>. This US - Minnesota State Coronavirus (COVID-19) Live Stats is refreshed every hour using credible data sources, including the country/state's official government website, <a href="https://en.wikipedia.org/wiki/2019%E2%80%9320_coronavirus_pandemic" target="_blank">data available on wikipedia pages</a>, latest news reports, <a href="https://systems.jhu.edu/research/public-health/ncov/" target="_blank">Johns Hopkins University CSSE 2019-nCoV Dashboard</a>, <a href="https://www.who.int/emergencies/diseases/novel-coronavirus-2019/situation-reports" target="_blank">WHO Situation Reports</a>, <a href="https://www.cdc.gov/coronavirus/2019-ncov/index.html" target="_blank">CDC Situation Updates</a>, and <a href="https://ncov.dxy.cn/ncovh5/view/pneumonia" target="_blank">DXY.cn</a>.</span>

<h2 id="news" class="center" style="margin-top: 60px; font-size: 25px;">Local Government Help Information</h2>
<div class="info center">
<a href="https://www.health.state.mn.us/diseases/coronavirus/index.html" target="_blank">Minnesota Department of Health</a> 651-201-3920
</div>
<h2 id="news" class="center" style="margin-top: 60px; font-size: 25px;">Trending Coronavirus News in US-Minnesota</h2>
<div class="row">
<div class="col-md-6 col-sm-12">
  <div class="content-card">
	<a href="https://www.twincities.com/2020/05/07/irish-fair-of-minnesota-in-august-canceled-because-of-coronavirus/"><div class="card-image" style="background-image: url(https://www.twincities.com/wp-content/uploads/2019/08/jea-Irish-Fair12.jpg?w=1024&h=576)"></div></a>
	<div class="content">
		<div class="card-title"><a href="https://www.twincities.com/2020/05/07/irish-fair-of-minnesota-in-august-canceled-because-of-coronavirus/">Irish Fair of Minnesota in August canceled because of coronavirus</a></div>
		<div class="card-excerpt">Even the luck of the you-know-who couldn’t save the 2020 Irish Fair of Minnesota, which was scheduled for August on St. Paul’s Harriet Island. Organizers announced Thursday morning</div>
		<div class="card-meta">
			<span class="card-provider">TwinCities.com</span> • <span class="card-date">5/7/2020</span>
		</div>
	</div>
  </div>
</div>

</div>

