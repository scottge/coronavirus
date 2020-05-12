---
category: stats
title: "US - Kansas State Coronavirus (COVID-19) Live Stats"
excerpt: "Live stats of COVID-19 in US-Kansas. Total Cases: 7274 (+32), Deaths: 182 (+1), Recoveries: 1675(-)."
publishedDateTime: 2020-05-12T15:45:10Z
updatedDateTime: 2020-05-12T15:45:10Z
webUrl: "https://smartable.ai/apps/coronavirus/stats/us-ks/"
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
  - url: "https://smartable.azureedge.net/coronavirus/sites/2/2020/us-ks.jpg"
    width: 900
    height: 564
    title: "US - Kansas State Coronavirus (COVID-19) Live Stats"

---
<div class="total-stats" style="text-align: center;">
    <h3>
	    <div style="font-size: 18px; font-weight: 400;">Total Confirmed Cases:</div>
	    7274 (<span class='red'>+32</span>)
    </h3>
    <h3>
	    <div style="font-size: 18px; font-weight: 400;">Total Deaths:</div>
	    182 (<span class='red'>+1</span>)
    </h3>
    <h3>
	    <div style="font-size: 18px; font-weight: 400;">Total Recovered:</div>
	    1675 (-)
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
      ['1/22/2020', 0, 0, 0],['1/23/2020', 0, 0, 0],['1/24/2020', 0, 0, 0],['1/25/2020', 0, 0, 0],['1/26/2020', 0, 0, 0],['1/27/2020', 0, 0, 0],['1/28/2020', 0, 0, 0],['1/29/2020', 0, 0, 0],['1/30/2020', 0, 0, 0],['1/31/2020', 0, 0, 0],['2/1/2020', 0, 0, 0],['2/2/2020', 0, 0, 0],['2/3/2020', 0, 0, 0],['2/4/2020', 0, 0, 0],['2/5/2020', 0, 0, 0],['2/6/2020', 0, 0, 0],['2/7/2020', 0, 0, 0],['2/8/2020', 0, 0, 0],['2/9/2020', 0, 0, 0],['2/10/2020', 0, 0, 0],['2/11/2020', 0, 0, 0],['2/12/2020', 0, 0, 0],['2/13/2020', 0, 0, 0],['2/14/2020', 0, 0, 0],['2/15/2020', 0, 0, 0],['2/16/2020', 0, 0, 0],['2/17/2020', 0, 0, 0],['2/18/2020', 0, 0, 0],['2/19/2020', 0, 0, 0],['2/20/2020', 0, 0, 0],['2/21/2020', 0, 0, 0],['2/22/2020', 0, 0, 0],['2/23/2020', 0, 0, 0],['2/24/2020', 0, 0, 0],['2/25/2020', 0, 0, 0],['2/26/2020', 0, 0, 0],['2/27/2020', 0, 0, 0],['2/28/2020', 0, 0, 0],['2/29/2020', 0, 0, 0],['3/1/2020', 0, 0, 0],['3/2/2020', 0, 0, 0],['3/3/2020', 0, 0, 0],['3/4/2020', 0, 0, 0],['3/5/2020', 0, 0, 0],['3/6/2020', 0, 0, 0],['3/7/2020', 0, 0, 0],['3/8/2020', 1, 0, 0],['3/9/2020', 1, 0, 0],['3/10/2020', 1, 0, 0],['3/11/2020', 1, 0, 0],['3/12/2020', 5, 1, 0],['3/13/2020', 6, 1, 0],['3/14/2020', 8, 1, 0],['3/15/2020', 9, 1, 0],['3/16/2020', 11, 1, 0],['3/17/2020', 18, 1, 0],['3/18/2020', 22, 1, 0],['3/19/2020', 36, 1, 0],['3/20/2020', 48, 1, 0],['3/21/2020', 57, 2, 0],['3/22/2020', 67, 2, 0],['3/23/2020', 85, 2, 0],['3/24/2020', 102, 2, 0],['3/25/2020', 137, 3, 0],['3/26/2020', 172, 3, 0],['3/27/2020', 219, 4, 0],['3/28/2020', 269, 5, 0],['3/29/2020', 330, 7, 0],['3/30/2020', 374, 8, 0],['3/31/2020', 441, 9, 0],['4/1/2020', 495, 10, 0],['4/2/2020', 558, 14, 0],['4/3/2020', 630, 18, 3],['4/4/2020', 699, 21, 3],['4/5/2020', 751, 22, 3],['4/6/2020', 849, 25, 4],['4/7/2020', 928, 29, 4],['4/8/2020', 1051, 34, 4],['4/9/2020', 1111, 42, 4],['4/10/2020', 1178, 50, 16],['4/11/2020', 1275, 55, 53],['4/12/2020', 1337, 56, 53],['4/13/2020', 1391, 62, 53],['4/14/2020', 1441, 69, 258],['4/15/2020', 1504, 71, 258],['4/16/2020', 1617, 80, 391],['4/17/2020', 1742, 84, 421],['4/18/2020', 1854, 86, 421],['4/19/2020', 1941, 94, 444],['4/20/2020', 2065, 102, 444],['4/21/2020', 2210, 109, 444],['4/22/2020', 2418, 112, 444],['4/23/2020', 2721, 113, 444],['4/24/2020', 2879, 117, 604],['4/25/2020', 3137, 120, 604],['4/26/2020', 3280, 120, 604],['4/27/2020', 3477, 124, 604],['4/28/2020', 3655, 127, 604],['4/29/2020', 3842, 134, 769],['4/30/2020', 4419, 134, 801],['5/1/2020', 4523, 136, 852],['5/2/2020', 4895, 140, 904],['5/3/2020', 5166, 143, 904],['5/4/2020', 5394, 157, 981],['5/5/2020', 5658, 161, 981],['5/6/2020', 6002, 164, 1675],['5/7/2020', 6340, 165, 1675],['5/8/2020', 6699, 168, 1675],['5/9/2020', 6879, 173, 1675],['5/10/2020', 7031, 175, 1675],['5/11/2020', 7242, 181, 1675],['5/12/2020', 7274, 182, 1675],
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
      [39.571, -95.3037, "Atchison", 14, 0],[37.8365, -94.882, "Bourbon", 6, 1],[37.9636, -97.146, "Butler", 18, 0],[37.0752, -94.6353, "Cherokee", 8, 0],[39.4301, -96.9997, "Clay", 5, 1],[38.2622, -95.7423, "Coffey", 50, 8],[37.543, -94.7024, "Crawford", 8, 1],[39.7518, -94.8889, "Doniphan", 8, 0],[38.9344, -95.0956, "Douglas", 57, 0],[37.9864, -100.9937, "Finney", 992, 4],[37.7304, -99.937, "Ford", 1135, 7],[38.5482, -95.1011, "Franklin", 26, 0],[38.9593, -100.487, "Gove", 1, 0],[38.0364, -97.3463, "Harvey", 10, 0],[39.2395, -95.9651, "Jackson", 4, 0],[39.4159, -95.3304, "Jefferson", 13, 0],[38.8454, -94.8521, "Johnson", 611, 52],[39.1084, -95.0829, "Leavenworth", 939, 6],[38.179, -94.7053, "Linn", 6, 0],[38.4028, -96.1924, "Lyon", 334, 4],[38.5511, -97.4274, "McPherson", 26, 0],[39.5096, -98.4331, "Mitchell", 3, 0],[37.014, -95.9316, "Montgomery", 21, 2],[38.6623, -96.4917, "Morris", 3, 0],[37.5186, -95.1742, "Neosho", 3, 0],[38.7793, -95.557, "Osage", 6, 0],[38.9692, -97.7591, "Ottawa", 4, 0],[39.2499, -96.3145, "Pottawatomie", 21, 0],[38.1011, -97.992, "Reno", 53, 0],[39.299, -96.8276, "Riley", 58, 0],[38.7736, -97.8645, "Saline", 25, 2],[37.5649, -97.3527, "Sedgwick", 469, 19],[38.8911, -95.6999, "Shawnee", 166, 5],[38, -98.7611, "Stafford", 1, 0],[37.3252, -101.2065, "Stevens", 18, 0],[37.3899, -97.643, "Sumner", 4, 1],[37.8682, -95.7533, "Woodson", 6, 0],[39.1234, -94.7443, "Wyandotte", 1121, 65],[38.5245, -98.5369, "Barton", 22, 1],[37.0803, -96.0962, "Chautauqua", 4, 0],[37.23, -95.1836, "Labette", 22, 0],[37.6777, -98.7465, "Pratt", 1, 0],[38.1818, -95.4905, "Anderson", 1, 0],[39.4519, -97.5297, "Cloud", 4, 0],[37.0679, -96.9958, "Cowley", 3, 1],[38.3744, -97.3024, "Marion", 7, 1],[39.5046, -98.5475, "Osborne", 2, 0],[38.6597, -94.8569, "Miami", 6, 0],[37.7191, -96.224, "Greenwood", 3, 0],[39.9343, -98.0351, "Jewell", 4, 0],[39.0271, -96.8497, "Geary", 16, 0],[39.0689, -96.167, "Wabaunsee", 27, 0],[39.7832, -97.8961, "Republic", 4, 0],[37.0038, -101.8944, "Morton", 4, 0],[37.0144, -98.6492, "Barber", 1, 0],[38.4791, -100.9023, "Scott", 4, 0],[37.0466, -100.9295, "Seward", 707, 0],[39.2532, -99.5634, "Rooks", 7, 0],[38.8816, -99.3219, "Ellis", 9, 0],[38.0415, -102.0078, "Hamilton", 10, 0],[39.6694, -99.1225, "Phillips", 1, 0],[37.982, -101.1333, "Kearny", 31, 0],[37.5699, -101.7443, "Stanton", 9, 0],[38.9358, -97.1246, "Dickinson", 2, 0],[39.7665, -98.9198, "Smith", 2, 0],[39.3366, -102.0373, "Sherman", 5, 0],[38.3732, -96.6459, "Chase", 4, 0],[37.525, -95.6614, "Wilson", 1, 0],[37.5925, -100.4502, "Gray", 8, 0],[37.4822, -100.8465, "Haskell", 16, 0],[39.3558, -100.4396, "Sheridan", 2, 0],[37.937, -99.2547, "Edwards", 4, 0],[37.0405, -99.9876, "Clark", 19, 1],[37.6175, -99.1058, "Kiowa", 2, 0],[38.3462, -98.2045, "Rice", 3, 0],[37.2836, -100.343, "Meade", 22, 0],[37.5772, -101.3547, "Grant", 11, 0],[39.7451077, -95.9832577, "Nemaha", 1, 0],[39.7877848, -101.7979613, "Cheyenne", 2, 0],[37.3936365, -96.1526985, "Elk", 1, 0],[37.1096002, -98.0465185, "Harper", 1, 0],[39.8413319, -97.179026, "Washington", 1, 0],[39.7959566, -99.9912254, "Norton", 2, 0],[39.770047, -95.4777811, "Brown", 1, 0],[38.615225, -98.2212979, "Ellsworth", 2, 0],
    ]);
    var options = {
      backgroundColor: {fill:'transparent',stroke:'#FFF' ,strokeWidth:0 }, 
      displayMode: 'markers',
      region: 'US-KS', 
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
      [{v:"Atchison", f:"Atchison"}, 14, 0, 12, 0, 0, 2],[{v:"Bourbon", f:"Bourbon"}, 6, 0, 0, 1, 0, 5],[{v:"Butler", f:"Butler"}, 18, 1, 9, 0, 0, 9],[{v:"Cherokee", f:"Cherokee"}, 8, 0, 2, 0, 0, 6],[{v:"Clay", f:"Clay"}, 5, 0, 3, 1, 0, 1],[{v:"Coffey", f:"Coffey"}, 50, 0, 15, 8, 0, 27],[{v:"Crawford", f:"Crawford"}, 8, 0, 7, 1, 0, 0],[{v:"Doniphan", f:"Doniphan"}, 8, 0, 8, 0, 0, 0],[{v:"Douglas", f:"Douglas"}, 57, 0, 18, 0, 0, 39],[{v:"Finney", f:"Finney"}, 992, 0, 980, 4, 0, 8],[{v:"Ford", f:"Ford"}, 1135, 3, 1128, 7, 0, 0],[{v:"Franklin", f:"Franklin"}, 26, 0, 14, 0, 0, 12],[{v:"Gove", f:"Gove"}, 1, 0, 1, 0, 0, 0],[{v:"Harvey", f:"Harvey"}, 10, 0, 7, 0, 0, 3],[{v:"Jackson", f:"Jackson"}, 4, 0, 4, 0, 0, 0],[{v:"Jefferson", f:"Jefferson"}, 13, 0, 9, 0, 0, 4],[{v:"Johnson", f:"Johnson"}, 611, 7, 559, 52, 0, 0],[{v:"Leavenworth", f:"Leavenworth"}, 939, 2, 900, 6, 0, 33],[{v:"Linn", f:"Linn"}, 6, 0, 6, 0, 0, 0],[{v:"Lyon", f:"Lyon"}, 334, 4, 294, 4, 0, 36],[{v:"McPherson", f:"McPherson"}, 26, 0, 14, 0, 0, 12],[{v:"Mitchell", f:"Mitchell"}, 3, 0, 3, 0, 0, 0],[{v:"Montgomery", f:"Montgomery"}, 21, 0, 12, 2, 0, 7],[{v:"Morris", f:"Morris"}, 3, 0, 1, 0, 0, 2],[{v:"Neosho", f:"Neosho"}, 3, 0, 3, 0, 0, 0],[{v:"Osage", f:"Osage"}, 6, 0, 3, 0, 0, 3],[{v:"Ottawa", f:"Ottawa"}, 4, 0, 4, 0, 0, 0],[{v:"Pottawatomie", f:"Pottawatomie"}, 21, 0, 16, 0, 0, 5],[{v:"Reno", f:"Reno"}, 53, 0, 47, 0, 0, 6],[{v:"Riley", f:"Riley"}, 58, 0, 45, 0, 0, 13],[{v:"Saline", f:"Saline"}, 25, 2, 23, 2, 0, 0],[{v:"Sedgwick", f:"Sedgwick"}, 469, 0, 306, 19, 0, 144],[{v:"Shawnee", f:"Shawnee"}, 166, 0, 81, 5, 0, 80],[{v:"Stafford", f:"Stafford"}, 1, 0, 1, 0, 0, 0],[{v:"Stevens", f:"Stevens"}, 18, 0, 18, 0, 0, 0],[{v:"Sumner", f:"Sumner"}, 4, 0, 3, 1, 0, 0],[{v:"Woodson", f:"Woodson"}, 6, 0, 2, 0, 0, 4],[{v:"Wyandotte", f:"Wyandotte"}, 1121, 11, 944, 65, 1, 112],[{v:"Barton", f:"Barton"}, 22, 0, 21, 1, 0, 0],[{v:"Chautauqua", f:"Chautauqua"}, 4, 0, 4, 0, 0, 0],[{v:"Labette", f:"Labette"}, 22, 0, 4, 0, 0, 18],[{v:"Pratt", f:"Pratt"}, 1, 0, 1, 0, 0, 0],[{v:"Anderson", f:"Anderson"}, 1, 0, 1, 0, 0, 0],[{v:"Cloud", f:"Cloud"}, 4, 0, 2, 0, 0, 2],[{v:"Cowley", f:"Cowley"}, 3, 0, 2, 1, 0, 0],[{v:"Marion", f:"Marion"}, 7, 1, 6, 1, 0, 0],[{v:"Osborne", f:"Osborne"}, 2, 0, 2, 0, 0, 0],[{v:"Miami", f:"Miami"}, 6, 0, 5, 0, 0, 1],[{v:"Greenwood", f:"Greenwood"}, 3, 0, 2, 0, 0, 1],[{v:"Jewell", f:"Jewell"}, 4, 0, 4, 0, 0, 0],[{v:"Geary", f:"Geary"}, 16, 0, 15, 0, 0, 1],[{v:"Wabaunsee", f:"Wabaunsee"}, 27, 0, 26, 0, 0, 1],[{v:"Republic", f:"Republic"}, 4, 0, 2, 0, 0, 2],[{v:"Morton", f:"Morton"}, 4, 0, 4, 0, 0, 0],[{v:"Barber", f:"Barber"}, 1, 0, 1, 0, 0, 0],[{v:"Scott", f:"Scott"}, 4, 0, 4, 0, 0, 0],[{v:"Seward", f:"Seward"}, 707, 0, 707, 0, 0, 0],[{v:"Rooks", f:"Rooks"}, 7, 1, 7, 0, 0, 0],[{v:"Ellis", f:"Ellis"}, 9, 0, 5, 0, 0, 4],[{v:"Hamilton", f:"Hamilton"}, 10, 0, 10, 0, 0, 0],[{v:"Phillips", f:"Phillips"}, 1, 0, 1, 0, 0, 0],[{v:"Kearny", f:"Kearny"}, 31, 0, 31, 0, 0, 0],[{v:"Stanton", f:"Stanton"}, 9, 0, 8, 0, 0, 1],[{v:"Dickinson", f:"Dickinson"}, 2, 0, 2, 0, 0, 0],[{v:"Smith", f:"Smith"}, 2, 0, 2, 0, 0, 0],[{v:"Sherman", f:"Sherman"}, 5, 0, 5, 0, 0, 0],[{v:"Chase", f:"Chase"}, 4, 0, 4, 0, 0, 0],[{v:"Wilson", f:"Wilson"}, 1, 0, 1, 0, 0, 0],[{v:"Gray", f:"Gray"}, 8, 0, 8, 0, 0, 0],[{v:"Haskell", f:"Haskell"}, 16, 0, 16, 0, 0, 0],[{v:"Sheridan", f:"Sheridan"}, 2, 0, 2, 0, 0, 0],[{v:"Edwards", f:"Edwards"}, 4, 0, 4, 0, 0, 0],[{v:"Clark", f:"Clark"}, 19, 0, 18, 1, 0, 0],[{v:"Kiowa", f:"Kiowa"}, 2, 0, 2, 0, 0, 0],[{v:"Rice", f:"Rice"}, 3, 0, 3, 0, 0, 0],[{v:"Meade", f:"Meade"}, 22, 0, 22, 0, 0, 0],[{v:"Grant", f:"Grant"}, 11, 0, 11, 0, 0, 0],[{v:"Nemaha", f:"Nemaha"}, 1, 0, 1, 0, 0, 0],[{v:"Cheyenne", f:"Cheyenne"}, 2, 0, 2, 0, 0, 0],[{v:"Elk", f:"Elk"}, 1, 0, 1, 0, 0, 0],[{v:"Harper", f:"Harper"}, 1, 0, 1, 0, 0, 0],[{v:"Washington", f:"Washington"}, 1, 0, 1, 0, 0, 0],[{v:"Norton", f:"Norton"}, 2, 0, 2, 0, 0, 0],[{v:"Brown", f:"Brown"}, 1, 0, 1, 0, 0, 0],[{v:"Ellsworth", f:"Ellsworth"}, 2, 0, 2, 0, 0, 0],
    ]);
    data.setProperty(0, 0, 'style', 'min-width:100px');
    var table = new google.visualization.Table(document.getElementById('geo_table'));
    table.draw(data, {allowHtml: true, sortColumn: 2, sortAscending: false, width: '660px', height: '100%'});
  }
</script>

<span style="font-size: 13px">All COVID-19 data displayed on the page is available through our FREE <a href="https://developer.smartable.ai">API program</a>. This US - Kansas State Coronavirus (COVID-19) Live Stats is refreshed every hour using credible data sources, including the country/state's official government website, <a href="https://en.wikipedia.org/wiki/2019%E2%80%9320_coronavirus_pandemic" target="_blank">data available on wikipedia pages</a>, latest news reports, <a href="https://systems.jhu.edu/research/public-health/ncov/" target="_blank">Johns Hopkins University CSSE 2019-nCoV Dashboard</a>, <a href="https://www.who.int/emergencies/diseases/novel-coronavirus-2019/situation-reports" target="_blank">WHO Situation Reports</a>, <a href="https://www.cdc.gov/coronavirus/2019-ncov/index.html" target="_blank">CDC Situation Updates</a>, and <a href="https://ncov.dxy.cn/ncovh5/view/pneumonia" target="_blank">DXY.cn</a>.</span>

<h2 id="news" class="center" style="margin-top: 60px; font-size: 25px;">Local Government Help Information</h2>
<div class="info center">
<a href="http://www.kdheks.gov/coronavirus/index.htm" target="_blank">Kansas Department of Health and Environment</a>
</div>

