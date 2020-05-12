---
category: stats
title: "US - Missouri State Coronavirus (COVID-19) Live Stats"
excerpt: "Live stats of COVID-19 in US-Missouri. Total Cases: 10149 (+141), Deaths: 507 (+10), Recoveries: 2529(+466)."
publishedDateTime: 2020-05-12T03:45:09Z
updatedDateTime: 2020-05-12T03:45:09Z
webUrl: "https://smartable.ai/apps/coronavirus/stats/us-mo/"
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
  - url: "https://smartable.azureedge.net/coronavirus/sites/2/2020/us-mo.jpg"
    width: 900
    height: 564
    title: "US - Missouri State Coronavirus (COVID-19) Live Stats"

---
<div class="total-stats" style="text-align: center;">
    <h3>
	    <div style="font-size: 18px; font-weight: 400;">Total Confirmed Cases:</div>
	    10149 (<span class='red'>+141</span>)
    </h3>
    <h3>
	    <div style="font-size: 18px; font-weight: 400;">Total Deaths:</div>
	    507 (<span class='red'>+10</span>)
    </h3>
    <h3>
	    <div style="font-size: 18px; font-weight: 400;">Total Recovered:</div>
	    2529 (<span class='green'>+466</span>)
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
      ['1/22/2020', 0, 0, 0],['1/23/2020', 0, 0, 0],['1/24/2020', 0, 0, 0],['1/25/2020', 0, 0, 0],['1/26/2020', 0, 0, 0],['1/27/2020', 0, 0, 0],['1/28/2020', 0, 0, 0],['1/29/2020', 0, 0, 0],['1/30/2020', 0, 0, 0],['1/31/2020', 0, 0, 0],['2/1/2020', 0, 0, 0],['2/2/2020', 0, 0, 0],['2/3/2020', 0, 0, 0],['2/4/2020', 0, 0, 0],['2/5/2020', 0, 0, 0],['2/6/2020', 0, 0, 0],['2/7/2020', 0, 0, 0],['2/8/2020', 0, 0, 0],['2/9/2020', 0, 0, 0],['2/10/2020', 0, 0, 0],['2/11/2020', 0, 0, 0],['2/12/2020', 0, 0, 0],['2/13/2020', 0, 0, 0],['2/14/2020', 0, 0, 0],['2/15/2020', 0, 0, 0],['2/16/2020', 0, 0, 0],['2/17/2020', 0, 0, 0],['2/18/2020', 0, 0, 0],['2/19/2020', 0, 0, 0],['2/20/2020', 0, 0, 0],['2/21/2020', 0, 0, 0],['2/22/2020', 0, 0, 0],['2/23/2020', 0, 0, 0],['2/24/2020', 0, 0, 0],['2/25/2020', 0, 0, 0],['2/26/2020', 0, 0, 0],['2/27/2020', 0, 0, 0],['2/28/2020', 0, 0, 0],['2/29/2020', 0, 0, 0],['3/1/2020', 0, 0, 0],['3/2/2020', 0, 0, 0],['3/3/2020', 0, 0, 0],['3/4/2020', 0, 0, 0],['3/5/2020', 0, 0, 0],['3/6/2020', 0, 0, 0],['3/7/2020', 0, 0, 0],['3/8/2020', 1, 0, 0],['3/9/2020', 1, 0, 0],['3/10/2020', 1, 0, 0],['3/11/2020', 1, 0, 0],['3/12/2020', 2, 0, 0],['3/13/2020', 4, 0, 0],['3/14/2020', 6, 0, 0],['3/15/2020', 5, 0, 0],['3/16/2020', 9, 0, 0],['3/17/2020', 16, 0, 0],['3/18/2020', 21, 1, 0],['3/19/2020', 39, 1, 0],['3/20/2020', 68, 2, 0],['3/21/2020', 79, 3, 0],['3/22/2020', 134, 3, 0],['3/23/2020', 180, 3, 0],['3/24/2020', 241, 7, 0],['3/25/2020', 328, 7, 0],['3/26/2020', 461, 8, 0],['3/27/2020', 614, 8, 0],['3/28/2020', 745, 9, 0],['3/29/2020', 821, 12, 0],['3/30/2020', 972, 12, 0],['3/31/2020', 1212, 14, 0],['4/1/2020', 1433, 21, 28],['4/2/2020', 1621, 21, 28],['4/3/2020', 1858, 28, 28],['4/4/2020', 2014, 37, 33],['4/5/2020', 2106, 41, 68],['4/6/2020', 2428, 55, 69],['4/7/2020', 2733, 74, 69],['4/8/2020', 2917, 76, 74],['4/9/2020', 3059, 79, 108],['4/10/2020', 3358, 88, 167],['4/11/2020', 3509, 99, 184],['4/12/2020', 3627, 101, 191],['4/13/2020', 3821, 113, 219],['4/14/2020', 4056, 127, 316],['4/15/2020', 4246, 139, 404],['4/16/2020', 4468, 147, 469],['4/17/2020', 4653, 159, 497],['4/18/2020', 4781, 168, 506],['4/19/2020', 4925, 169, 510],['4/20/2020', 5040, 175, 540],['4/21/2020', 5228, 178, 1232],['4/22/2020', 5390, 182, 1236],['4/23/2020', 5534, 207, 1522],['4/24/2020', 6257, 234, 1536],['4/25/2020', 6881, 283, 1536],['4/26/2020', 7029, 283, 1536],['4/27/2020', 7239, 300, 1536],['4/28/2020', 7376, 327, 1536],['4/29/2020', 7576, 338, 1536],['4/30/2020', 7766, 343, 1536],['5/1/2020', 7954, 351, 1727],['5/2/2020', 8328, 377, 1918],['5/3/2020', 8434, 377, 1918],['5/4/2020', 8887, 383, 1987],['5/5/2020', 8977, 400, 1987],['5/6/2020', 9266, 425, 2063],['5/7/2020', 9482, 448, 2063],['5/8/2020', 9692, 479, 2063],['5/9/2020', 9810, 493, 2063],['5/10/2020', 10008, 497, 2063],['5/11/2020', 10149, 507, 2529],
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
      [40.1484, -92.3787, "Adair", 12, 0],[40.3392, -95.392, "Atchison", 2, 0],[36.6707, -93.9399, "Barry", 6, 0],[38.071, -94.08, "Bates", 6, 1],[38.2474, -93.371, "Benton", 8, 0],[37.3171, -90.0282, "Bollinger", 4, 0],[39.2105, -92.1342, "Boone", 102, 1],[39.7226, -94.6404, "Buchanan", 442, 3],[38.6452, -92.1151, "Callaway", 23, 1],[37.8136, -92.5143, "Camden", 36, 1],[37.2368, -89.7978, "Cape Girardeau", 51, 1],[37.0082, -91.0113, "Carter", 3, 1],[38.7306, -94.4736, "Cass", 70, 8],[37.6233, -93.8036, "Cedar", 9, 0],[39.4233, -92.8025, "Chariton", 6, 0],[37.0459, -93.2953, "Christian", 20, 0],[39.1545, -94.5452, "Clay", 107, 2],[39.5644, -94.4615, "Clinton", 14, 0],[38.5157, -92.0647, "Cole", 56, 1],[38.9341, -92.7025, "Cooper", 9, 0],[38.0948, -91.2953, "Crawford", 8, 0],[36.0404, -90.1158, "Dunklin", 24, 2],[38.3361, -90.9711, "Franklin", 137, 13],[37.1193, -93.3683, "Greene", 103, 8],[38.4331, -93.9342, "Henry", 9, 1],[39.1363, -94.1307, "Jackson", 1165, 30],[37.0711, -94.4573, "Jasper", 30, 0],[38.3655, -90.3645, "Jefferson", 309, 12],[38.5833, -93.6952, "Johnson", 63, 0],[39.099724, -94.578331, "Kansas", 475, 15],[38.9877, -93.5683, "Lafayette", 62, 2],[39.1682, -90.7879, "Lincoln", 77, 41],[39.6713, -93.6341, "Livingston", 4, 0],[39.7509, -92.5646, "Macon", 3, 0],[38.2848, -91.7217, "Maries", 2, 0],[36.5746, -94.3912, "McDonald", 5, 0],[38.6611, -92.6661, "Moniteau", 59, 0],[38.9125, -91.5323, "Montgomery", 7, 0],[38.6696, -92.8763, "Morgan", 7, 0],[37.0355, -94.5379, "Newton", 13, 1],[38.4414, -92.0005, "Osage", 5, 0],[36.3318, -89.8242, "Pemiscot", 63, 3],[37.7836, -89.918, "Perry", 45, 0],[38.6211, -93.4101, "Pettis", 64, 0],[39.2622, -90.8287, "Pike", 13, 0],[39.1924, -94.622, "Platte", 66, 0],[37.7562, -92.1274, "Pulaski", 36, 1],[39.5844, -91.3987, "Ralls", 1, 0],[39.5114, -92.4411, "Randolph", 8, 0],[39.1956, -94.0523, "Ray", 12, 0],[37.4574, -91.212, "Reynolds", 2, 0],[36.6234, -90.8219, "Ripley", 5, 0],[37.0938, -89.5547, "Scott", 80, 5],[39.7432, -92.2602, "Shelby", 1, 0],[38.8664, -90.2084, "St. Charles", 670, 47],[37.8618, -90.5892, "St. Francois", 33, 2],[38.6103, -90.4125, "St. Louis", 3932, 262],[37.0237, -89.8196, "Stoddard", 29, 0],[36.8054, -93.4709, "Stone", 3, 0],[36.6058, -93.2338, "Taney", 12, 2],[38.8262, -91.2322, "Warren", 28, 0],[37.1072, -92.4189, "Wright", 10, 0],[40.2684, -94.0281, "Harrison", 6, 0],[37.3886, -92.8304, "Webster", 16, 0],[38.0147, -90.2214, "Ste. Genevieve", 9, 1],[39.5495, -94.0396, "Caldwell", 3, 0],[38.6983, -91.4342, "Gasconade", 3, 0],[36.7632, -90.4136, "Butler", 27, 0],[39.8139, -94.5507, "DeKalb", 4, 0],[36.6311, -91.9602, "Howell", 5, 0],[36.6111, -89.7061, "New Madrid", 12, 0],[40.288, -95.0795, "Nodaway", 5, 0],[39.194, -93.3636, "Saline", 219, 0],[40.3921, -91.9261, "Clark", 1, 0],[37.7025, -91.8661, "Phelps", 3, 0],[40.2166, -94.5381, "Gentry", 1, 0],[40.4045, -94.4465, "Worth", 1, 0],[39.8767, -93.1868, "Linn", 5, 1],[37.4872, -90.296, "Madison", 3, 0],[37.8435, -93.1676, "Dallas", 2, 0],[39.2279, -92.8394, "Howard", 3, 0],[36.5974, -91.6461, "Oregon", 2, 0],[37.6331, -93.5769, "Polk", 1, 0],[40.467, -91.9736, "Scotland", 4, 0],[37.7651, -90.7723, "Washington", 9, 1],[37.9891, -93.6637, "St. Clair", 2, 0],[37.8445, -94.3492, "Vernon", 5, 0],[39.8388, -94.8205, "Andrew", 8, 0],[37.2837, -90.6354, "Iron", 2, 0],[39.9861, -95.1433, "Holt", 1, 0],[39.9106, -93.9642, "Daviess", 3, 0],[38.3512, -92.5766, "Miller", 3, 0],[39.7097, -91.3936, "Marion", 5, 0],[40.1295, -91.5266, "Lewis", 6, 1],[39.2747, -91.5763, "Audrain", 2, 0],[39.4579, -93.5239, "Carroll", 3, 0],[36.7789, -89.3841, "Mississippi", 49, 0],[37.1500679, -93.8248241, "Lawrence", 7, 0],[40.1836505, -93.1779659, "Sullivan", 2, 0],[37.0388739, -90.5257823, "Wayne", 1, 0],[37.6965235, -92.539603, "Laclede", 2, 0],
    ]);
    var options = {
      backgroundColor: {fill:'transparent',stroke:'#FFF' ,strokeWidth:0 }, 
      displayMode: 'markers',
      region: 'US-MO', 
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
      [{v:"Adair", f:"Adair"}, 12, 0, 7, 0, 0, 5],[{v:"Atchison", f:"Atchison"}, 2, 0, 2, 0, 0, 0],[{v:"Barry", f:"Barry"}, 6, 0, 6, 0, 0, 0],[{v:"Bates", f:"Bates"}, 6, 0, 5, 1, 0, 0],[{v:"Benton", f:"Benton"}, 8, 0, 8, 0, 0, 0],[{v:"Bollinger", f:"Bollinger"}, 4, 0, 4, 0, 0, 0],[{v:"Boone", f:"Boone"}, 102, 0, 21, 1, 0, 80],[{v:"Buchanan", f:"Buchanan"}, 442, 0, 439, 3, 0, 0],[{v:"Callaway", f:"Callaway"}, 23, 0, 7, 1, 0, 15],[{v:"Camden", f:"Camden"}, 36, 0, 22, 1, 0, 13],[{v:"Cape Girardeau", f:"Cape Girardeau"}, 51, 0, 50, 1, 0, 0],[{v:"Carter", f:"Carter"}, 3, 0, 2, 1, 0, 0],[{v:"Cass", f:"Cass"}, 70, 1, 62, 8, 0, 0],[{v:"Cedar", f:"Cedar"}, 9, 0, 9, 0, 0, 0],[{v:"Chariton", f:"Chariton"}, 6, 0, 6, 0, 0, 0],[{v:"Christian", f:"Christian"}, 20, 0, 20, 0, 0, 0],[{v:"Clay", f:"Clay"}, 107, 0, 105, 2, 0, 0],[{v:"Clinton", f:"Clinton"}, 14, 0, 14, 0, 0, 0],[{v:"Cole", f:"Cole"}, 56, 0, 18, 1, 0, 37],[{v:"Cooper", f:"Cooper"}, 9, 0, 7, 0, 0, 2],[{v:"Crawford", f:"Crawford"}, 8, 0, 8, 0, 0, 0],[{v:"Dunklin", f:"Dunklin"}, 24, 0, 9, 2, 0, 13],[{v:"Franklin", f:"Franklin"}, 137, 0, 90, 13, 0, 34],[{v:"Greene", f:"Greene"}, 103, 0, 49, 8, 0, 46],[{v:"Henry", f:"Henry"}, 9, 0, 8, 1, 0, 0],[{v:"Jackson", f:"Jackson"}, 1165, 0, 1133, 30, 0, 2],[{v:"Jasper", f:"Jasper"}, 30, 0, 19, 0, 0, 11],[{v:"Jefferson", f:"Jefferson"}, 309, 0, 202, 12, 0, 95],[{v:"Johnson", f:"Johnson"}, 63, 0, 31, 0, 0, 32],[{v:"Kansas", f:"Kansas"}, 475, 0, 460, 15, 0, 0],[{v:"Lafayette", f:"Lafayette"}, 62, 0, 37, 2, 0, 23],[{v:"Lincoln", f:"Lincoln"}, 77, 0, 0, 41, 0, 38],[{v:"Livingston", f:"Livingston"}, 4, 0, 4, 0, 0, 0],[{v:"Macon", f:"Macon"}, 3, 0, 2, 0, 0, 1],[{v:"Maries", f:"Maries"}, 2, 0, 2, 0, 0, 0],[{v:"McDonald", f:"McDonald"}, 5, 0, 5, 0, 0, 0],[{v:"Moniteau", f:"Moniteau"}, 59, 0, 55, 0, 0, 4],[{v:"Montgomery", f:"Montgomery"}, 7, 0, 5, 0, 0, 2],[{v:"Morgan", f:"Morgan"}, 7, 0, 7, 0, 0, 0],[{v:"Newton", f:"Newton"}, 13, 0, 12, 1, 0, 0],[{v:"Osage", f:"Osage"}, 5, 0, 2, 0, 0, 3],[{v:"Pemiscot", f:"Pemiscot"}, 63, 0, 60, 3, 0, 0],[{v:"Perry", f:"Perry"}, 45, 0, 10, 0, 0, 35],[{v:"Pettis", f:"Pettis"}, 64, 0, 62, 0, 0, 2],[{v:"Pike", f:"Pike"}, 13, 0, 7, 0, 0, 6],[{v:"Platte", f:"Platte"}, 66, 0, 53, 0, 0, 13],[{v:"Pulaski", f:"Pulaski"}, 36, 0, 31, 1, 0, 4],[{v:"Ralls", f:"Ralls"}, 1, 0, 1, 0, 0, 0],[{v:"Randolph", f:"Randolph"}, 8, 0, 7, 0, 0, 1],[{v:"Ray", f:"Ray"}, 12, 0, 12, 0, 0, 0],[{v:"Reynolds", f:"Reynolds"}, 2, 0, 2, 0, 0, 0],[{v:"Ripley", f:"Ripley"}, 5, 0, 5, 0, 0, 0],[{v:"Scott", f:"Scott"}, 80, 0, 62, 5, 0, 13],[{v:"Shelby", f:"Shelby"}, 1, 0, 1, 0, 0, 0],[{v:"St. Charles", f:"St. Charles"}, 670, 2, 623, 47, 1, 0],[{v:"St. Francois", f:"St. Francois"}, 33, 0, 15, 2, 0, 16],[{v:"St. Louis", f:"St. Louis"}, 3932, 0, 2726, 262, 0, 944],[{v:"Stoddard", f:"Stoddard"}, 29, 0, 29, 0, 0, 0],[{v:"Stone", f:"Stone"}, 3, 0, 3, 0, 0, 0],[{v:"Taney", f:"Taney"}, 12, 0, 10, 2, 0, 0],[{v:"Warren", f:"Warren"}, 28, 0, 22, 0, 0, 6],[{v:"Wright", f:"Wright"}, 10, 0, 10, 0, 0, 0],[{v:"Harrison", f:"Harrison"}, 6, 0, 6, 0, 0, 0],[{v:"Webster", f:"Webster"}, 16, 0, 16, 0, 0, 0],[{v:"Ste. Genevieve", f:"Ste. Genevieve"}, 9, 0, 8, 1, 0, 0],[{v:"Caldwell", f:"Caldwell"}, 3, 0, 3, 0, 0, 0],[{v:"Gasconade", f:"Gasconade"}, 3, 0, 1, 0, 0, 2],[{v:"Butler", f:"Butler"}, 27, 0, 15, 0, 0, 12],[{v:"DeKalb", f:"DeKalb"}, 4, 0, 4, 0, 0, 0],[{v:"Howell", f:"Howell"}, 5, 0, 5, 0, 0, 0],[{v:"New Madrid", f:"New Madrid"}, 12, 0, 12, 0, 0, 0],[{v:"Nodaway", f:"Nodaway"}, 5, 0, 5, 0, 0, 0],[{v:"Saline", f:"Saline"}, 219, 0, 195, 0, 0, 24],[{v:"Clark", f:"Clark"}, 1, 0, 1, 0, 0, 0],[{v:"Phelps", f:"Phelps"}, 3, 0, 3, 0, 0, 0],[{v:"Gentry", f:"Gentry"}, 1, 0, 1, 0, 0, 0],[{v:"Worth", f:"Worth"}, 1, 0, 1, 0, 0, 0],[{v:"Linn", f:"Linn"}, 5, 0, 4, 1, 0, 0],[{v:"Madison", f:"Madison"}, 3, 0, 3, 0, 0, 0],[{v:"Dallas", f:"Dallas"}, 2, 0, 2, 0, 0, 0],[{v:"Howard", f:"Howard"}, 3, 0, 1, 0, 0, 2],[{v:"Oregon", f:"Oregon"}, 2, 0, 2, 0, 0, 0],[{v:"Polk", f:"Polk"}, 1, 0, 1, 0, 0, 0],[{v:"Scotland", f:"Scotland"}, 4, 0, 4, 0, 0, 0],[{v:"Washington", f:"Washington"}, 9, 0, 8, 1, 0, 0],[{v:"St. Clair", f:"St. Clair"}, 2, 0, 2, 0, 0, 0],[{v:"Vernon", f:"Vernon"}, 5, 0, 5, 0, 0, 0],[{v:"Andrew", f:"Andrew"}, 8, 0, 8, 0, 0, 0],[{v:"Iron", f:"Iron"}, 2, 0, 2, 0, 0, 0],[{v:"Holt", f:"Holt"}, 1, 0, 1, 0, 0, 0],[{v:"Daviess", f:"Daviess"}, 3, 0, 3, 0, 0, 0],[{v:"Miller", f:"Miller"}, 3, 0, 3, 0, 0, 0],[{v:"Marion", f:"Marion"}, 5, 0, 5, 0, 0, 0],[{v:"Lewis", f:"Lewis"}, 6, 0, 5, 1, 0, 0],[{v:"Audrain", f:"Audrain"}, 2, 0, 2, 0, 0, 0],[{v:"Carroll", f:"Carroll"}, 3, 0, 3, 0, 0, 0],[{v:"Mississippi", f:"Mississippi"}, 49, 0, 49, 0, 0, 0],[{v:"Lawrence", f:"Lawrence"}, 7, 0, 7, 0, 0, 0],[{v:"Sullivan", f:"Sullivan"}, 2, 0, 2, 0, 0, 0],[{v:"Wayne", f:"Wayne"}, 1, 0, 1, 0, 0, 0],[{v:"Laclede", f:"Laclede"}, 2, 0, 2, 0, 0, 0],
    ]);
    data.setProperty(0, 0, 'style', 'min-width:100px');
    var table = new google.visualization.Table(document.getElementById('geo_table'));
    table.draw(data, {allowHtml: true, sortColumn: 2, sortAscending: false, width: '660px', height: '100%'});
  }
</script>

<span style="font-size: 13px">All COVID-19 data displayed on the page is available through our FREE <a href="https://developer.smartable.ai">API program</a>. This US - Missouri State Coronavirus (COVID-19) Live Stats is refreshed every hour using credible data sources, including the country/state's official government website, <a href="https://en.wikipedia.org/wiki/2019%E2%80%9320_coronavirus_pandemic" target="_blank">data available on wikipedia pages</a>, latest news reports, <a href="https://systems.jhu.edu/research/public-health/ncov/" target="_blank">Johns Hopkins University CSSE 2019-nCoV Dashboard</a>, <a href="https://www.who.int/emergencies/diseases/novel-coronavirus-2019/situation-reports" target="_blank">WHO Situation Reports</a>, <a href="https://www.cdc.gov/coronavirus/2019-ncov/index.html" target="_blank">CDC Situation Updates</a>, and <a href="https://ncov.dxy.cn/ncovh5/view/pneumonia" target="_blank">DXY.cn</a>.</span>

<h2 id="news" class="center" style="margin-top: 60px; font-size: 25px;">Local Government Help Information</h2>
<div class="info center">
<a href="https://health.mo.gov/living/healthcondiseases/communicable/novel-coronavirus/" target="_blank">Missouri Department of Health and Senior Services</a> 573-751-6113
</div>
<h2 id="news" class="center" style="margin-top: 60px; font-size: 25px;">Trending Coronavirus News in US-Missouri</h2>
<div class="row">
<div class="col-md-6 col-sm-12">
  <div class="content-card">
	<a href="https://www.stltoday.com/news/local/education/reading-writing-and-separation-how-coronavirus-could-change-missouri-schools-when-they-reopen/article_1fcf2373-db85-5c7d-8fbf-8c014b313692.html"><div class="card-image" style="background-image: url(https://bloximages.newyork1.vip.townnews.com/stltoday.com/content/tncms/assets/v3/editorial/2/43/24350be0-a775-5ce6-b8e9-06ee9cdf03c7/5e791a10a3746.image.jpg?resize=1024%2C715)"></div></a>
	<div class="content">
		<div class="card-title"><a href="https://www.stltoday.com/news/local/education/reading-writing-and-separation-how-coronavirus-could-change-missouri-schools-when-they-reopen/article_1fcf2373-db85-5c7d-8fbf-8c014b313692.html">Reading, writing and separation: How coronavirus could change Missouri schools when they reopen</a></div>
		<div class="card-excerpt">The report recommends canceling or reorganizing sports, extracurricular activities and before- and after-school programs.</div>
		<div class="card-meta">
			<span class="card-provider">St. Louis Post-Dispatch</span> • <span class="card-date">5/6/2020</span>
		</div>
	</div>
  </div>
</div>

</div>

