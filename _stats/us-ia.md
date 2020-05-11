---
category: stats
title: "US - Iowa State Coronavirus (COVID-19) Live Stats"
excerpt: "Live stats of COVID-19 in US-Iowa. Total Cases: 12373 (+395), Deaths: 271 (+6), Recoveries: 5249(+564)."
publishedDateTime: 2020-05-11T18:45:16Z
updatedDateTime: 2020-05-11T18:45:16Z
webUrl: "https://smartable.ai/apps/coronavirus/stats/us-ia/"
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
  - url: "https://smartable.azureedge.net/coronavirus/sites/2/2020/us-ia.jpg"
    width: 900
    height: 564
    title: "US - Iowa State Coronavirus (COVID-19) Live Stats"

---
<div class="total-stats" style="text-align: center;">
    <h3>
	    <div style="font-size: 18px; font-weight: 400;">Total Confirmed Cases:</div>
	    12373 (<span class='red'>+395</span>)
    </h3>
    <h3>
	    <div style="font-size: 18px; font-weight: 400;">Total Deaths:</div>
	    271 (<span class='red'>+6</span>)
    </h3>
    <h3>
	    <div style="font-size: 18px; font-weight: 400;">Total Recovered:</div>
	    5249 (<span class='green'>+564</span>)
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
      ['1/22/2020', 0, 0, 0],['1/23/2020', 0, 0, 0],['1/24/2020', 0, 0, 0],['1/25/2020', 0, 0, 0],['1/26/2020', 0, 0, 0],['1/27/2020', 0, 0, 0],['1/28/2020', 0, 0, 0],['1/29/2020', 0, 0, 0],['1/30/2020', 0, 0, 0],['1/31/2020', 0, 0, 0],['2/1/2020', 0, 0, 0],['2/2/2020', 0, 0, 0],['2/3/2020', 0, 0, 0],['2/4/2020', 0, 0, 0],['2/5/2020', 0, 0, 0],['2/6/2020', 0, 0, 0],['2/7/2020', 0, 0, 0],['2/8/2020', 0, 0, 0],['2/9/2020', 0, 0, 0],['2/10/2020', 0, 0, 0],['2/11/2020', 0, 0, 0],['2/12/2020', 0, 0, 0],['2/13/2020', 0, 0, 0],['2/14/2020', 0, 0, 0],['2/15/2020', 0, 0, 0],['2/16/2020', 0, 0, 0],['2/17/2020', 0, 0, 0],['2/18/2020', 0, 0, 0],['2/19/2020', 0, 0, 0],['2/20/2020', 0, 0, 0],['2/21/2020', 0, 0, 0],['2/22/2020', 0, 0, 0],['2/23/2020', 0, 0, 0],['2/24/2020', 0, 0, 0],['2/25/2020', 0, 0, 0],['2/26/2020', 0, 0, 0],['2/27/2020', 0, 0, 0],['2/28/2020', 0, 0, 0],['2/29/2020', 0, 0, 0],['3/1/2020', 0, 0, 0],['3/2/2020', 0, 0, 0],['3/3/2020', 0, 0, 0],['3/4/2020', 0, 0, 0],['3/5/2020', 0, 0, 0],['3/6/2020', 0, 0, 0],['3/7/2020', 0, 0, 0],['3/8/2020', 0, 0, 0],['3/9/2020', 3, 0, 0],['3/10/2020', 8, 0, 0],['3/11/2020', 13, 0, 0],['3/12/2020', 16, 0, 0],['3/13/2020', 17, 0, 0],['3/14/2020', 18, 0, 0],['3/15/2020', 22, 0, 0],['3/16/2020', 23, 0, 0],['3/17/2020', 29, 0, 0],['3/18/2020', 39, 0, 0],['3/19/2020', 45, 0, 0],['3/20/2020', 46, 0, 0],['3/21/2020', 70, 0, 0],['3/22/2020', 90, 0, 0],['3/23/2020', 105, 0, 0],['3/24/2020', 125, 1, 0],['3/25/2020', 146, 1, 0],['3/26/2020', 179, 1, 0],['3/27/2020', 235, 3, 0],['3/28/2020', 298, 3, 0],['3/29/2020', 336, 4, 0],['3/30/2020', 424, 6, 0],['3/31/2020', 497, 7, 0],['4/1/2020', 552, 9, 3],['4/2/2020', 614, 11, 3],['4/3/2020', 700, 11, 3],['4/4/2020', 788, 14, 3],['4/5/2020', 869, 22, 3],['4/6/2020', 946, 25, 3],['4/7/2020', 1048, 26, 89],['4/8/2020', 1145, 27, 89],['4/9/2020', 1270, 29, 476],['4/10/2020', 1388, 31, 506],['4/11/2020', 1510, 34, 585],['4/12/2020', 1587, 41, 674],['4/13/2020', 1710, 43, 674],['4/14/2020', 1902, 49, 674],['4/15/2020', 1998, 53, 908],['4/16/2020', 2144, 60, 987],['4/17/2020', 2336, 64, 1007],['4/18/2020', 2516, 74, 1095],['4/19/2020', 2905, 75, 1171],['4/20/2020', 3162, 79, 1171],['4/21/2020', 3644, 83, 1171],['4/22/2020', 3751, 90, 1171],['4/23/2020', 3927, 96, 1492],['4/24/2020', 4450, 107, 1492],['4/25/2020', 5093, 112, 1604],['4/26/2020', 5479, 118, 1604],['4/27/2020', 5873, 127, 2021],['4/28/2020', 6380, 136, 2164],['4/29/2020', 6843, 148, 2164],['4/30/2020', 7145, 162, 2697],['5/1/2020', 7875, 167, 2926],['5/2/2020', 8641, 175, 3156],['5/3/2020', 9169, 184, 3156],['5/4/2020', 9721, 188, 3486],['5/5/2020', 10125, 207, 3572],['5/6/2020', 10406, 219, 3803],['5/7/2020', 11064, 231, 3803],['5/8/2020', 11457, 243, 4685],['5/9/2020', 11688, 252, 4685],['5/10/2020', 11978, 265, 4685],['5/11/2020', 12373, 271, 5249],
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
      [41.29, -94.5601, "Adair", 3, 0],[43.2084, -91.296, "Allamakee", 111, 4],[40.8017, -92.8871, "Appanoose", 6, 3],[41.592, -94.8811, "Audubon", 10, 0],[41.9054, -92.1804, "Benton", 35, 1],[42.492, -92.3522, "Black Hawk", 1493, 23],[41.9669, -93.8176, "Boone", 34, 0],[42.6201, -91.7295, "Buchanan", 23, 0],[42.7518, -92.7957, "Butler", 12, 0],[42.1225, -94.7837, "Carroll", 6, 0],[41.7399, -90.9738, "Cedar", 42, 1],[42.9442, -93.3871, "Cerro Gordo", 15, 0],[42.9269, -91.3879, "Clayton", 23, 2],[41.8227, -90.5448, "Clinton", 56, 1],[42.0757, -95.1013, "Crawford", 176, 1],[41.5905, -94.1963, "Dallas", 676, 6],[40.86, -91.3146, "Des Moines", 39, 1],[43.3742, -95.1744, "Dickinson", 6, 0],[42.4477, -90.8448, "Dubuque", 191, 7],[42.8636, -91.8864, "Fayette", 24, 0],[41.8452, -94.307, "Guthrie", 33, 0],[43.1864, -93.6076, "Hancock", 3, 0],[42.2435, -93.0625, "Hardin", 12, 0],[41.8082, -96.0274, "Harrison", 17, 0],[40.9232, -91.401, "Henry", 43, 1],[41.7557, -92.1859, "Iowa", 27, 0],[42.3624, -90.5422, "Jackson", 7, 0],[41.7008, -93.0794, "Jasper", 238, 8],[41.6699, -91.5984, "Johnson", 551, 7],[42.1141, -91.0903, "Jones", 31, 0],[41.3651, -91.9533, "Keokuk", 7, 0],[43.0749, -94.0892, "Kossuth", 2, 0],[42.1494, -91.6209, "Linn", 827, 58],[41.2855, -92.5371, "Mahaska", 20, 1],[42.0067, -92.7749, "Marshall", 721, 3],[42.0208, -95.966, "Monona", 12, 0],[40.981, -95.1029, "Montgomery", 4, 0],[41.5898, -91.0271, "Muscatine", 488, 22],[40.6561, -95.2349, "Page", 10, 0],[41.6776, -93.7946, "Polk", 2238, 60],[41.3912, -95.4778, "Pottawattamie", 85, 2],[41.5833, -92.5274, "Poweshiek", 79, 5],[41.6915, -90.6746, "Scott", 280, 8],[41.7263, -95.4754, "Shelby", 19, 0],[42.9749, -96.3216, "Sioux", 84, 0],[42.1073, -93.6462, "Story", 58, 1],[41.9648, -92.5746, "Tama", 329, 13],[40.7324, -94.9005, "Taylor", 1, 0],[40.7011, -91.8005, "Van Buren", 8, 0],[40.9176, -92.2177, "Wapello", 218, 0],[41.3709, -93.3862, "Warren", 42, 0],[41.2139, -91.5367, "Washington", 159, 7],[42.3616, -94.2955, "Webster", 9, 0],[43.1014, -92.0463, "Winneshiek", 24, 0],[42.3975, -96.3516, "Woodbury", 1627, 8],[42.6593, -93.5012, "Wright", 6, 0],[43.4391, -92.784, "Mitchell", 3, 0],[43.0167, -95.0367, "Clay", 9, 0],[41.227, -93.9295, "Madison", 11, 1],[42.669, -92.3342, "Bremer", 58, 5],[42.4798, -91.5915, "Delaware", 10, 1],[41.0543, -92.0138, "Jefferson", 7, 0],[41.1772, -91.1881, "Louisa", 282, 3],[43.3093, -96.4351, "Lyon", 16, 0],[42.811, -96.2666, "Plymouth", 59, 0],[41.018, -95.7995, "Mills", 8, 0],[43.2459, -92.4393, "Howard", 13, 0],[42.4338, -92.9265, "Grundy", 17, 0],[40.7679, -91.5165, "Lee", 18, 0],[43.1814, -95.6553, "O'Brien", 15, 0],[41.0413, -93.9489, "Clarke", 6, 0],[42.3898, -93.728, "Hamilton", 10, 0],[41.2057, -92.8843, "Marion", 13, 0],[43.1173, -92.4155, "Chickasaw", 6, 0],[42.7578, -93.1041, "Franklin", 7, 0],[43.4711, -93.6168, "Winnebago", 3, 0],[42.033, -94.237, "Greene", 13, 0],[42.8916, -95.1488, "Buena Vista", 32, 0],[43.3534, -93.2106, "Worth", 2, 0],[43.2863, -95.6087, "Osceola", 19, 0],[40.948, -94.2192, "Union", 1, 0],[41.2343, -95.1392, "Cass", 1, 0],[42.5756, -95.7202, "Cherokee", 4, 0],[42.868, -94.184, "Humboldt", 7, 0],[43.34943, -94.6863782, "Emmet", 1, 0],[42.6918039, -94.645035, "Pocahontas", 3, 0],[40.6913838, -92.3813621, "Davis", 9, 0],[40.8146492, -93.8248241, "Decatur", 1, 0],[42.3785903, -94.645035, "Calhoun", 1, 0],[43.0615947, -92.8577105, "Floyd", 4, 1],[42.3573517, -95.1432068, "Sac", 2, 0],[40.6677356, -93.3388917, "Wayne", 1, 0],[41.0040981, -92.8577105, "Monroe", 4, 0],[43.1580878, -94.645035, "Palo Alto", 1, 0],[40.7400403, -95.6457951, "Fremont", 1, 0],
    ]);
    var options = {
      backgroundColor: {fill:'transparent',stroke:'#FFF' ,strokeWidth:0 }, 
      displayMode: 'markers',
      region: 'US-IA', 
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
      [{v:"Adair", f:"Adair"}, 3, 0, 3, 0, 0, 0],[{v:"Allamakee", f:"Allamakee"}, 111, 0, 107, 4, 0, 0],[{v:"Appanoose", f:"Appanoose"}, 6, 0, 3, 3, 0, 0],[{v:"Audubon", f:"Audubon"}, 10, 0, 10, 0, 0, 0],[{v:"Benton", f:"Benton"}, 35, 0, 34, 1, 0, 0],[{v:"Black Hawk", f:"Black Hawk"}, 1493, 0, 1470, 23, 0, 0],[{v:"Boone", f:"Boone"}, 34, 0, 34, 0, 0, 0],[{v:"Buchanan", f:"Buchanan"}, 23, 0, 23, 0, 0, 0],[{v:"Butler", f:"Butler"}, 12, 0, 12, 0, 0, 0],[{v:"Carroll", f:"Carroll"}, 6, 0, 6, 0, 0, 0],[{v:"Cedar", f:"Cedar"}, 42, 0, 41, 1, 0, 0],[{v:"Cerro Gordo", f:"Cerro Gordo"}, 15, 0, 15, 0, 0, 0],[{v:"Clayton", f:"Clayton"}, 23, 0, 21, 2, 0, 0],[{v:"Clinton", f:"Clinton"}, 56, 0, 55, 1, 0, 0],[{v:"Crawford", f:"Crawford"}, 176, 0, 175, 1, 0, 0],[{v:"Dallas", f:"Dallas"}, 676, 0, 670, 6, 0, 0],[{v:"Des Moines", f:"Des Moines"}, 39, 0, 38, 1, 0, 0],[{v:"Dickinson", f:"Dickinson"}, 6, 0, 6, 0, 0, 0],[{v:"Dubuque", f:"Dubuque"}, 191, 0, 184, 7, 0, 0],[{v:"Fayette", f:"Fayette"}, 24, 0, 24, 0, 0, 0],[{v:"Guthrie", f:"Guthrie"}, 33, 0, 33, 0, 0, 0],[{v:"Hancock", f:"Hancock"}, 3, 0, 3, 0, 0, 0],[{v:"Hardin", f:"Hardin"}, 12, 0, 12, 0, 0, 0],[{v:"Harrison", f:"Harrison"}, 17, 0, 17, 0, 0, 0],[{v:"Henry", f:"Henry"}, 43, 0, 42, 1, 0, 0],[{v:"Iowa", f:"Iowa"}, 27, 0, 27, 0, 0, 0],[{v:"Jackson", f:"Jackson"}, 7, 0, 7, 0, 0, 0],[{v:"Jasper", f:"Jasper"}, 238, 0, 230, 8, 0, 0],[{v:"Johnson", f:"Johnson"}, 551, 0, 544, 7, 0, 0],[{v:"Jones", f:"Jones"}, 31, 0, 31, 0, 0, 0],[{v:"Keokuk", f:"Keokuk"}, 7, 0, 7, 0, 0, 0],[{v:"Kossuth", f:"Kossuth"}, 2, 0, 2, 0, 0, 0],[{v:"Linn", f:"Linn"}, 827, 0, 769, 58, 0, 0],[{v:"Mahaska", f:"Mahaska"}, 20, 0, 19, 1, 0, 0],[{v:"Marshall", f:"Marshall"}, 721, 0, 718, 3, 0, 0],[{v:"Monona", f:"Monona"}, 12, 0, 12, 0, 0, 0],[{v:"Montgomery", f:"Montgomery"}, 4, 0, 4, 0, 0, 0],[{v:"Muscatine", f:"Muscatine"}, 488, 0, 466, 22, 0, 0],[{v:"Page", f:"Page"}, 10, 0, 10, 0, 0, 0],[{v:"Polk", f:"Polk"}, 2238, 0, 2178, 60, 0, 0],[{v:"Pottawattamie", f:"Pottawattamie"}, 85, 0, 83, 2, 0, 0],[{v:"Poweshiek", f:"Poweshiek"}, 79, 0, 74, 5, 0, 0],[{v:"Scott", f:"Scott"}, 280, 0, 272, 8, 0, 0],[{v:"Shelby", f:"Shelby"}, 19, 0, 19, 0, 0, 0],[{v:"Sioux", f:"Sioux"}, 84, 0, 84, 0, 0, 0],[{v:"Story", f:"Story"}, 58, 0, 57, 1, 0, 0],[{v:"Tama", f:"Tama"}, 329, 0, 316, 13, 0, 0],[{v:"Taylor", f:"Taylor"}, 1, 0, 1, 0, 0, 0],[{v:"Van Buren", f:"Van Buren"}, 8, 0, 8, 0, 0, 0],[{v:"Wapello", f:"Wapello"}, 218, 0, 218, 0, 0, 0],[{v:"Warren", f:"Warren"}, 42, 0, 42, 0, 0, 0],[{v:"Washington", f:"Washington"}, 159, 0, 152, 7, 0, 0],[{v:"Webster", f:"Webster"}, 9, 0, 9, 0, 0, 0],[{v:"Winneshiek", f:"Winneshiek"}, 24, 0, 24, 0, 0, 0],[{v:"Woodbury", f:"Woodbury"}, 1627, 0, 1616, 8, 0, 3],[{v:"Wright", f:"Wright"}, 6, 0, 6, 0, 0, 0],[{v:"Mitchell", f:"Mitchell"}, 3, 0, 3, 0, 0, 0],[{v:"Clay", f:"Clay"}, 9, 0, 9, 0, 0, 0],[{v:"Madison", f:"Madison"}, 11, 0, 10, 1, 0, 0],[{v:"Bremer", f:"Bremer"}, 58, 0, 53, 5, 0, 0],[{v:"Delaware", f:"Delaware"}, 10, 0, 9, 1, 0, 0],[{v:"Jefferson", f:"Jefferson"}, 7, 0, 7, 0, 0, 0],[{v:"Louisa", f:"Louisa"}, 282, 0, 279, 3, 0, 0],[{v:"Lyon", f:"Lyon"}, 16, 0, 16, 0, 0, 0],[{v:"Plymouth", f:"Plymouth"}, 59, 0, 59, 0, 0, 0],[{v:"Mills", f:"Mills"}, 8, 0, 8, 0, 0, 0],[{v:"Howard", f:"Howard"}, 13, 0, 13, 0, 0, 0],[{v:"Grundy", f:"Grundy"}, 17, 0, 17, 0, 0, 0],[{v:"Lee", f:"Lee"}, 18, 0, 18, 0, 0, 0],[{v:"O'Brien", f:"O'Brien"}, 15, 0, 15, 0, 0, 0],[{v:"Clarke", f:"Clarke"}, 6, 0, 6, 0, 0, 0],[{v:"Hamilton", f:"Hamilton"}, 10, 0, 10, 0, 0, 0],[{v:"Marion", f:"Marion"}, 13, 0, 13, 0, 0, 0],[{v:"Chickasaw", f:"Chickasaw"}, 6, 0, 6, 0, 0, 0],[{v:"Franklin", f:"Franklin"}, 7, 0, 7, 0, 0, 0],[{v:"Winnebago", f:"Winnebago"}, 3, 0, 3, 0, 0, 0],[{v:"Greene", f:"Greene"}, 13, 0, 13, 0, 0, 0],[{v:"Buena Vista", f:"Buena Vista"}, 32, 0, 32, 0, 0, 0],[{v:"Worth", f:"Worth"}, 2, 0, 2, 0, 0, 0],[{v:"Osceola", f:"Osceola"}, 19, 0, 19, 0, 0, 0],[{v:"Union", f:"Union"}, 1, 0, 1, 0, 0, 0],[{v:"Cass", f:"Cass"}, 1, 0, 1, 0, 0, 0],[{v:"Cherokee", f:"Cherokee"}, 4, 0, 4, 0, 0, 0],[{v:"Humboldt", f:"Humboldt"}, 7, 0, 7, 0, 0, 0],[{v:"Emmet", f:"Emmet"}, 1, 0, 1, 0, 0, 0],[{v:"Pocahontas", f:"Pocahontas"}, 3, 0, 3, 0, 0, 0],[{v:"Davis", f:"Davis"}, 9, 0, 9, 0, 0, 0],[{v:"Decatur", f:"Decatur"}, 1, 0, 1, 0, 0, 0],[{v:"Calhoun", f:"Calhoun"}, 1, 0, 1, 0, 0, 0],[{v:"Floyd", f:"Floyd"}, 4, 0, 3, 1, 0, 0],[{v:"Sac", f:"Sac"}, 2, 0, 2, 0, 0, 0],[{v:"Wayne", f:"Wayne"}, 1, 0, 1, 0, 0, 0],[{v:"Monroe", f:"Monroe"}, 4, 0, 4, 0, 0, 0],[{v:"Palo Alto", f:"Palo Alto"}, 1, 0, 1, 0, 0, 0],[{v:"Fremont", f:"Fremont"}, 1, 0, 1, 0, 0, 0],
    ]);
    data.setProperty(0, 0, 'style', 'min-width:100px');
    var table = new google.visualization.Table(document.getElementById('geo_table'));
    table.draw(data, {allowHtml: true, sortColumn: 2, sortAscending: false, width: '660px', height: '100%'});
  }
</script>

<span style="font-size: 13px">All COVID-19 data displayed on the page is available through our FREE <a href="https://developer.smartable.ai">API program</a>. This US - Iowa State Coronavirus (COVID-19) Live Stats is refreshed every hour using credible data sources, including the country/state's official government website, <a href="https://en.wikipedia.org/wiki/2019%E2%80%9320_coronavirus_pandemic" target="_blank">data available on wikipedia pages</a>, latest news reports, <a href="https://systems.jhu.edu/research/public-health/ncov/" target="_blank">Johns Hopkins University CSSE 2019-nCoV Dashboard</a>, <a href="https://www.who.int/emergencies/diseases/novel-coronavirus-2019/situation-reports" target="_blank">WHO Situation Reports</a>, <a href="https://www.cdc.gov/coronavirus/2019-ncov/index.html" target="_blank">CDC Situation Updates</a>, and <a href="https://ncov.dxy.cn/ncovh5/view/pneumonia" target="_blank">DXY.cn</a>.</span>

<h2 id="news" class="center" style="margin-top: 60px; font-size: 25px;">Local Government Help Information</h2>
<div class="info center">
<a href="https://idph.iowa.gov/Emerging-Health-Issues/Novel-Coronavirus" target="_blank">Iowa Department of Public Health</a>
</div>
<h2 id="news" class="center" style="margin-top: 60px; font-size: 25px;">Trending Coronavirus News in US-Iowa</h2>
<div class="row">
<div class="col-md-6 col-sm-12">
  <div class="content-card">
	<a href="https://www.sfgate.com/news/article/Iowa-sees-12-new-COVID-19-deaths-nearly-300-new-15251096.php"><div class="card-image" style="background-image: url(https://d29xw9s9x32j3w.cloudfront.net/players/library/placeholder.png)"></div></a>
	<div class="content">
		<div class="card-title"><a href="https://www.sfgate.com/news/article/Iowa-sees-12-new-COVID-19-deaths-nearly-300-new-15251096.php">Iowa sees 12 new COVID-19 deaths, nearly 300 new cases</a></div>
		<div class="card-excerpt">Iowa state health officials said Wednesday the state has seen 12 new COVID-19 deaths from the previous day, bringing the state's total to 219. The Iowa Department of Public Health also announced another one-day jump in confirmed cases of the new coronavirus by 293 from Tuesday to Wednesday.</div>
		<div class="card-meta">
			<span class="card-provider">SFGate</span> • <span class="card-date">5/6/2020</span>
		</div>
	</div>
  </div>
</div>
<div class="col-md-6 col-sm-12">
  <div class="content-card">
	<a href="https://thehill.com/homenews/state-watch/496303-more-than-half-of-workforce-at-tyson-plant-in-iowa-tests-positive-for"><div class="card-image" style="background-image: url(https://thehill.com/sites/default/files/article_images/tysonfoods08162016getty.jpg)"></div></a>
	<div class="content">
		<div class="card-title"><a href="https://thehill.com/homenews/state-watch/496303-more-than-half-of-workforce-at-tyson-plant-in-iowa-tests-positive-for">Over half of workforce at Tyson plant in Iowa tests positive for coronavirus</a></div>
		<div class="card-excerpt">More than half of the workforce at a Tyson Foods pork processing plant in Perry, Iowa, has tested positive for COVID-19, the disease caused by the novel coronavirus.</div>
		<div class="card-meta">
			<span class="card-provider">The Hill</span> • <span class="card-date">5/5/2020</span>
		</div>
	</div>
  </div>
</div>

</div>

