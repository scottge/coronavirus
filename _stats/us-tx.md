---
category: stats
title: "US - Texas State Coronavirus (COVID-19) Live Stats"
excerpt: "Live stats of COVID-19 in US-Texas. Total Cases: 41095 (+240), Deaths: 1153 (-), Recoveries: 23592(-)."
publishedDateTime: 2020-05-12T17:45:10Z
updatedDateTime: 2020-05-12T17:45:10Z
webUrl: "https://smartable.ai/apps/coronavirus/stats/us-tx/"
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
  - url: "https://smartable.azureedge.net/coronavirus/sites/2/2020/us-tx.jpg"
    width: 900
    height: 564
    title: "US - Texas State Coronavirus (COVID-19) Live Stats"

---
<div class="total-stats" style="text-align: center;">
    <h3>
	    <div style="font-size: 18px; font-weight: 400;">Total Confirmed Cases:</div>
	    41095 (<span class='red'>+240</span>)
    </h3>
    <h3>
	    <div style="font-size: 18px; font-weight: 400;">Total Deaths:</div>
	    1153 (-)
    </h3>
    <h3>
	    <div style="font-size: 18px; font-weight: 400;">Total Recovered:</div>
	    23592 (-)
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
      ['1/22/2020', 0, 0, 0],['1/23/2020', 0, 0, 0],['1/24/2020', 0, 0, 0],['1/25/2020', 0, 0, 0],['1/26/2020', 0, 0, 0],['1/27/2020', 0, 0, 0],['1/28/2020', 0, 0, 0],['1/29/2020', 0, 0, 0],['1/30/2020', 0, 0, 0],['1/31/2020', 0, 0, 0],['2/1/2020', 0, 0, 0],['2/2/2020', 0, 0, 0],['2/3/2020', 0, 0, 0],['2/4/2020', 0, 0, 0],['2/5/2020', 0, 0, 0],['2/6/2020', 0, 0, 0],['2/7/2020', 0, 0, 0],['2/8/2020', 0, 0, 0],['2/9/2020', 0, 0, 0],['2/10/2020', 0, 0, 0],['2/11/2020', 0, 0, 0],['2/12/2020', 0, 0, 0],['2/13/2020', 0, 0, 0],['2/14/2020', 0, 0, 0],['2/15/2020', 0, 0, 0],['2/16/2020', 0, 0, 0],['2/17/2020', 0, 0, 0],['2/18/2020', 0, 0, 0],['2/19/2020', 0, 0, 0],['2/20/2020', 0, 0, 0],['2/21/2020', 0, 0, 0],['2/22/2020', 0, 0, 0],['2/23/2020', 0, 0, 0],['2/24/2020', 0, 0, 0],['2/25/2020', 0, 0, 0],['2/26/2020', 0, 0, 0],['2/27/2020', 0, 0, 0],['2/28/2020', 0, 0, 0],['2/29/2020', 0, 0, 0],['3/1/2020', 0, 0, 0],['3/2/2020', 0, 0, 0],['3/3/2020', 0, 0, 0],['3/4/2020', 0, 0, 0],['3/5/2020', 3, 0, 0],['3/6/2020', 4, 0, 0],['3/7/2020', 8, 0, 0],['3/8/2020', 11, 0, 0],['3/9/2020', 13, 0, 0],['3/10/2020', 16, 0, 0],['3/11/2020', 21, 0, 0],['3/12/2020', 27, 0, 0],['3/13/2020', 44, 0, 0],['3/14/2020', 60, 0, 0],['3/15/2020', 63, 0, 0],['3/16/2020', 85, 0, 0],['3/17/2020', 110, 1, 0],['3/18/2020', 196, 3, 0],['3/19/2020', 306, 5, 0],['3/20/2020', 429, 4, 4],['3/21/2020', 582, 5, 4],['3/22/2020', 643, 7, 11],['3/23/2020', 758, 9, 11],['3/24/2020', 955, 12, 11],['3/25/2020', 1229, 15, 15],['3/26/2020', 1563, 21, 15],['3/27/2020', 1937, 26, 15],['3/28/2020', 2455, 30, 15],['3/29/2020', 2792, 37, 15],['3/30/2020', 3147, 45, 15],['3/31/2020', 3809, 54, 15],['4/1/2020', 4355, 66, 254],['4/2/2020', 5069, 77, 377],['4/3/2020', 5734, 100, 528],['4/4/2020', 6567, 116, 640],['4/5/2020', 7209, 136, 684],['4/6/2020', 8050, 150, 763],['4/7/2020', 8932, 160, 976],['4/8/2020', 9777, 189, 1194],['4/9/2020', 11208, 210, 1365],['4/10/2020', 12105, 238, 1709],['4/11/2020', 13023, 266, 1873],['4/12/2020', 13677, 283, 2068],['4/13/2020', 14275, 305, 2401],['4/14/2020', 15015, 342, 2680],['4/15/2020', 15907, 375, 2957],['4/16/2020', 16876, 414, 3278],['4/17/2020', 17849, 451, 3537],['4/18/2020', 18704, 476, 3760],['4/19/2020', 19260, 490, 4020],['4/20/2020', 19751, 507, 4268],['4/21/2020', 20574, 533, 4578],['4/22/2020', 21321, 556, 4910],['4/23/2020', 22650, 604, 5262],['4/24/2020', 22905, 616, 5262],['4/25/2020', 24195, 643, 9986],['4/26/2020', 25015, 667, 9986],['4/27/2020', 25516, 682, 11170],['4/28/2020', 26464, 724, 11170],['4/29/2020', 27566, 759, 11786],['4/30/2020', 28777, 821, 12507],['5/1/2020', 29837, 842, 13699],['5/2/2020', 31142, 875, 14891],['5/3/2020', 32227, 889, 15544],['5/4/2020', 33058, 917, 16621],['5/5/2020', 34238, 960, 16665],['5/6/2020', 35330, 1006, 17687],['5/7/2020', 36550, 1029, 18707],['5/8/2020', 37727, 1079, 19604],['5/9/2020', 38696, 1111, 23589],['5/10/2020', 39890, 1133, 23589],['5/11/2020', 40855, 1153, 23592],['5/12/2020', 41095, 1153, 23592],
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
      [32.2963, -102.5297, "Andrews", 21, 0],[32.0561, -95.5043, "Anderson", 41, 0],[31.2345, -94.7665, "Angelina", 100, 0],[28.167, -97.006, "Aransas", 2, 0],[28.9643, -98.4957, "Atascosa", 24, 1],[29.7965, -96.1051, "Austin", 15, 0],[30.2819, -97.2448, "Bastrop", 110, 2],[35.1075, -101.3628, "Armstrong", 2, 0],[31.0525, -97.479, "Bell", 220, 3],[29.5545, -98.3404, "Bexar", 1920, 57],[30.4298, -98.3609, "Blanco", 6, 0],[34.06854817, -102.8299707, "Bailey", 3, 0],[33.5076, -94.6167, "Bowie", 107, 11],[29.6383, -98.9869, "Bandera", 6, 0],[29.0455, -95.5673, "Brazoria", 673, 9],[30.5852, -96.296, "Brazos", 278, 18],[31.8249, -98.7895, "Brown", 38, 6],[28.5277, -97.7831, "Bee", 6, 0],[30.346, -96.5311, "Burleson", 15, 0],[30.5677, -98.2751, "Burnet", 26, 0],[29.8785, -97.6831, "Caldwell", 30, 0],[28.4463, -96.4205, "Calhoun", 36, 3],[26.0566, -97.4235, "Cameron", 527, 23],[32.0562, -97.7507, "Bosque", 5, 0],[33.1378, -94.0591, "Cass", 20, 2],[34.5324, -102.3111, "Castro", 23, 1],[29.7269, -94.8549, "Chambers", 50, 0],[31.8968, -95.152, "Cherokee", 20, 1],[29.81008251, -103.2520326, "Brewster", 1, 0],[33.1795, -96.493, "Collin", 941, 29],[34.53026962, -101.2084947, "Briscoe", 1, 0],[29.6997, -98.1148, "Comal", 65, 6],[27.22, -98.0645, "Brooks", 1, 0],[31.9005, -98.6044, "Comanche", 4, 1],[31.4187, -97.5114, "Coryell", 208, 2],[31.3919, -102.3503, "Crane", 2, 0],[32.7767, -96.797, "Dallas", 6123, 145],[32.9307, -102.1256, "Dawson", 30, 1],[34.8232, -102.4001, "Deaf Smith", 59, 0],[32.4056, -99.5039, "Callahan", 6, 1],[33.133, -97.3014, "Denton", 946, 25],[28.9829, -97.505, "DeWitt", 15, 1],[32.9997, -94.9668, "Camp", 7, 0],[32.2136, -98.6721, "Eastland", 3, 0],[35.5707, -101.1731, "Carson", 3, 0],[32.0105, -102.3587, "Ector", 103, 4],[31.811, -106.1643, "El Paso", 1340, 33],[32.314, -97.0053, "Ellis", 211, 11],[32.0875, -98.3391, "Erath", 15, 1],[31.3711, -97.0763, "Falls", 6, 0],[34.4293, -100.2516, "Childress", 2, 0],[33.4275, -96.3407, "Fannin", 23, 1],[33.9299, -98.3676, "Clay", 3, 0],[30.064, -96.6958, "Fayette", 25, 1],[33.5997, -102.6133, "Cochran", 1, 0],[29.5693, -95.8143, "Fort Bend", 1385, 38],[31.88911733, -100.5297533, "Coke", 1, 0],[33.176, -95.2253, "Franklin", 3, 0],[31.76736834, -99.45240766, "Coleman", 2, 0],[32.9419, -102.5657, "Gaines", 3, 0],[29.4128, -94.9658, "Galveston", 686, 29],[34.96489496, -100.2700111, "Collingsworth", 4, 0],[33.6233, -96.7286, "Grayson", 91, 0],[29.7055, -96.5563, "Colorado", 16, 0],[32.4893, -94.8521, "Gregg", 118, 0],[30.3874, -96.0895, "Grimes", 42, 1],[29.4892, -98.1094, "Guadalupe", 97, 0],[31.2162, -99.844, "Concho", 1, 0],[34.2791, -101.8968, "Hale", 37, 4],[33.5703, -97.0129, "Cooke", 12, 0],[30.1933, -94.193, "Hardin", 115, 3],[29.7752, -95.3103, "Harris", 8176, 179],[34.07783319, -100.2785062, "Cottle", 4, 1],[32.5886, -94.4468, "Harrison", 186, 9],[30.0392, -97.8915, "Hays", 209, 2],[32.3075, -96.0138, "Henderson", 41, 0],[33.6413, -101.2377, "Crosby", 2, 1],[26.2585, -98.5787, "Hidalgo", 394, 8],[32.1419, -97.3972, "Hill", 19, 1],[36.0579, -102.5123, "Dallam", 14, 1],[33.4133, -102.1552, "Hockley", 21, 1],[32.4885, -97.8357, "Hood", 22, 3],[33.3222, -95.5606, "Hopkins", 8, 0],[31.3177, -95.4564, "Houston", 13, 0],[33.3716, -95.6912, "Delta", 1, 0],[32.9324, -96.2471, "Hunt", 57, 3],[28.8325, -96.5388, "Jackson", 14, 0],[30.6578, -93.9001, "Jasper", 22, 2],[33.4701, -100.8556, "Dickens", 1, 0],[30.0522, -94.3332, "Jefferson", 381, 25],[28.4461, -99.7604, "Dimmit", 1, 0],[32.4311, -97.1021, "Johnson", 150, 4],[34.8674, -100.6592, "Donley", 26, 0],[28.8858, -97.7134, "Karnes", 3, 0],[27.7609, -98.2389, "Duval", 5, 0],[32.7315, -96.159, "Kaufman", 120, 1],[29.7844, -98.7289, "Kendall", 19, 0],[27.5095, -97.861, "Kleberg", 11, 1],[33.6689, -95.5462, "Lamar", 89, 4],[34.012, -102.4147, "Lamb", 7, 0],[29.4428, -96.9436, "Lavaca", 6, 1],[31.2579, -95.9796, "Leon", 9, 0],[30.047, -94.7908, "Liberty", 66, 1],[31.307, -96.6293, "Limestone", 15, 1],[30.7807, -98.4393, "Llano", 3, 0],[33.6901, -101.9893, "Lubbock", 598, 50],[33.9835, -101.3367, "Floyd", 4, 0],[32.9652, -101.8309, "Lynn", 5, 1],[32.1315, -101.7928, "Martin", 3, 1],[28.8727, -96.2172, "Matagorda", 64, 5],[28.947, -100.6237, "Maverick", 31, 0],[31.7897, -96.461, "Freestone", 7, 0],[31.3818, -97.2127, "McLennan", 94, 4],[28.8885, -99.0988, "Frio", 34, 0],[29.3532, -99.1621, "Medina", 32, 2],[32.0249, -102.1137, "Midland", 101, 11],[30.874, -97.1289, "Milam", 20, 1],[33.17969345, -101.2984114, "Garza", 3, 0],[33.7835, -97.7302, "Montague", 9, 1],[30.2903, -99.2459, "Gillespie", 4, 0],[30.3883, -95.6963, "Montgomery", 724, 17],[31.86942909, -101.5207776, "Glasscock", 1, 0],[36.0444, -102.008, "Moore", 527, 9],[28.6708, -97.3916, "Goliad", 7, 0],[33.0306, -94.725, "Morris", 9, 0],[29.2698, -97.7658, "Gonzales", 59, 2],[31.8126, -94.8411, "Nacogdoches", 211, 9],[35.5479, -100.965, "Gray", 75, 0],[32.0925, -96.7174, "Navarro", 36, 2],[27.8094, -97.8455, "Nueces", 147, 3],[35.2456, -102.4262, "Oldham", 3, 1],[30.1291, -93.9967, "Orange", 85, 2],[32.7508, -97.6999, "Parker", 45, 0],[30.9988, -94.8275, "Polk", 35, 0],[35.1989, -101.831, "Potter", 1179, 17],[31.6997, -98.1208, "Hamilton", 7, 0],[35.0539, -101.8186, "Randall", 379, 3],[36.066, -101.4769, "Hansford", 12, 2],[31.4046, -103.5057, "Reeves", 7, 0],[30.877, -96.5956, "Robertson", 5, 0],[32.917, -96.4377, "Rockwall", 104, 5],[31.8662, -94.9833, "Rusk", 40, 1],[30.5898, -95.1307, "San Jacinto", 11, 0],[35.8914, -102.3933, "Hartley", 8, 2],[28.0969, -97.865, "San Patricio", 22, 0],[31.944, -94.2457, "Shelby", 152, 5],[32.2222, -95.2217, "Smith", 178, 4],[35.9097, -100.3839, "Hemphill", 1, 0],[26.3859, -98.899, "Starr", 14, 0],[34.5374, -101.7743, "Swisher", 12, 0],[32.7732, -97.3517, "Tarrant", 3745, 104],[32.4522, -99.8666, "Taylor", 386, 6],[33.3377, -102.2059, "Terry", 12, 0],[31.4426, -100.4501, "Tom Green", 84, 1],[30.4088, -98.0451, "Travis", 2171, 65],[32.2795, -101.3496, "Howard", 6, 1],[32.586, -95.1127, "Upshur", 17, 0],[29.3214, -99.4696, "Uvalde", 7, 0],[29.3708, -100.88, "Val Verde", 13, 0],[35.7026, -101.5317, "Hutchinson", 21, 0],[32.554, -95.8639, "Van Zandt", 18, 1],[28.8285, -96.985, "Victoria", 150, 5],[33.1636, -98.3891, "Jack", 4, 0],[30.705, -95.5545, "Walker", 342, 2],[30.0996, -96.0781, "Waller", 39, 0],[30.1586, -96.3965, "Washington", 164, 18],[27.6555, -99.6178, "Webb", 437, 17],[29.1119, -96.4123, "Wharton", 41, 0],[26.8827, -98.8948, "Jim Hogg", 3, 0],[33.9072, -98.529, "Wichita", 75, 2],[27.7132, -98.1346, "Jim Wells", 7, 0],[26.4634, -97.9088, "Willacy", 14, 1],[30.513, -97.7382, "Williamson", 380, 14],[32.8898, -100.1329, "Jones", 95, 0],[29.2358, -97.9636, "Wilson", 36, 4],[33.2099, -97.7709, "Wise", 30, 2],[33.1896, -102.8271, "Yoakum", 2, 0],[33.195, -98.7436, "Young", 4, 1],[30.8502, -93.7537, "Newton", 4, 0],[30.9213, -94.6001, "Tyler", 7, 0],[30.0772, -99.2381, "Kerr", 9, 0],[30.48678918, -99.74856473, "Kimble", 1, 0],[28.4668, -98.1784, "Live Oak", 5, 0],[33.468, -99.5236, "Knox", 1, 0],[28.4364, -99.2367, "La Salle", 2, 0],[31.305, -94.2699, "San Augustine", 21, 1],[32.9305, -95.5761, "Wood", 14, 0],[32.2436, -94.4561, "Panola", 168, 8],[31.0755, -97.9727, "Lampasas", 8, 0],[30.1833, -96.9279, "Lee", 5, 0],[36.27783108, -100.2733151, "Lipscomb", 2, 0],[32.5509, -98.4979, "Palo Pinto", 9, 2],[33.1658, -95.1105, "Titus", 35, 0],[30.9376, -95.3254, "Trinity", 11, 0],[31.0252, -95.7539, "Madison", 3, 0],[32.7634, -94.3511, "Marion", 16, 0],[30.748, -99.2288, "Mason", 28, 0],[30.8926, -102.8847, "Pecos", 15, 0],[31.1993, -99.5809, "McCulloch", 3, 0],[26.9027, -99.2612, "Zapata", 7, 0],[32.3571, -101.0132, "Mitchell", 1, 0],[33.8992, -100.8561, "Motley", 1, 0],[32.9011, -95.9397, "Rains", 2, 0],[32.0851, -100.3194, "Nolan", 2, 0],[32.6366, -100.7523, "Scurry", 2, 0],[36.3932, -100.7974, "Ochiltree", 29, 1],[32.7566, -98.9125, "Stephens", 1, 0],[31.7545, -103.1541, "Winkler", 3, 0],[34.5157, -102.8846, "Parmer", 19, 0],[34.148, -99.3, "Wilbarger", 2, 0],[33.5523, -94.7804, "Red River", 9, 0],[35.6924, -100.6416, "Roberts", 2, 0],[31.4541, -93.7979, "Sabine", 2, 0],[36.4937, -101.7937, "Sherman", 23, 0],[28.7221, -99.8327, "Zavala", 2, 0],[28.3238976, -97.15766311, "Refugio", 1, 0],[31.8314342, -99.97616148, "Runnels", 2, 0],[35.5291, -100.4394, "Wheeler", 14, 0],[32.73587756, -99.35401337, "Shackelford", 1, 0],
    ]);
    var options = {
      backgroundColor: {fill:'transparent',stroke:'#FFF' ,strokeWidth:0 }, 
      displayMode: 'markers',
      region: 'US-TX', 
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
      [{v:"Andrews", f:"Andrews"}, 21, 0, 18, 0, 0, 3],[{v:"Anderson", f:"Anderson"}, 41, 0, 39, 0, 0, 2],[{v:"Angelina", f:"Angelina"}, 100, 0, 100, 0, 0, 0],[{v:"Aransas", f:"Aransas"}, 2, 0, 2, 0, 0, 0],[{v:"Atascosa", f:"Atascosa"}, 24, 0, 17, 1, 0, 6],[{v:"Austin", f:"Austin"}, 15, 0, 15, 0, 0, 0],[{v:"Bastrop", f:"Bastrop"}, 110, 0, 102, 2, 0, 6],[{v:"Armstrong", f:"Armstrong"}, 2, 0, 2, 0, 0, 0],[{v:"Bell", f:"Bell"}, 220, 0, 159, 3, 0, 58],[{v:"Bexar", f:"Bexar"}, 1920, 19, 1502, 57, 1, 361],[{v:"Blanco", f:"Blanco"}, 6, 0, 6, 0, 0, 0],[{v:"Bailey", f:"Bailey"}, 3, 0, 3, 0, 0, 0],[{v:"Bowie", f:"Bowie"}, 107, 2, 96, 11, 1, 0],[{v:"Bandera", f:"Bandera"}, 6, 0, 6, 0, 0, 0],[{v:"Brazoria", f:"Brazoria"}, 673, 12, 454, 9, 0, 210],[{v:"Brazos", f:"Brazos"}, 278, 7, 210, 18, 0, 50],[{v:"Brown", f:"Brown"}, 38, 0, 21, 6, 0, 11],[{v:"Bee", f:"Bee"}, 6, 0, 6, 0, 0, 0],[{v:"Burleson", f:"Burleson"}, 15, 0, 15, 0, 0, 0],[{v:"Burnet", f:"Burnet"}, 26, 0, 26, 0, 0, 0],[{v:"Caldwell", f:"Caldwell"}, 30, 0, 30, 0, 0, 0],[{v:"Calhoun", f:"Calhoun"}, 36, 0, 33, 3, 0, 0],[{v:"Cameron", f:"Cameron"}, 527, 15, 356, 23, 1, 148],[{v:"Bosque", f:"Bosque"}, 5, 0, 5, 0, 0, 0],[{v:"Cass", f:"Cass"}, 20, 0, 15, 2, 0, 3],[{v:"Castro", f:"Castro"}, 23, 0, 22, 1, 0, 0],[{v:"Chambers", f:"Chambers"}, 50, 0, 29, 0, 0, 21],[{v:"Cherokee", f:"Cherokee"}, 20, 0, 13, 1, 0, 6],[{v:"Brewster", f:"Brewster"}, 1, 0, 1, 0, 0, 0],[{v:"Collin", f:"Collin"}, 941, 21, 483, 29, 1, 429],[{v:"Briscoe", f:"Briscoe"}, 1, 0, 1, 0, 0, 0],[{v:"Comal", f:"Comal"}, 65, 0, 40, 6, 0, 19],[{v:"Brooks", f:"Brooks"}, 1, 0, 1, 0, 0, 0],[{v:"Comanche", f:"Comanche"}, 4, 0, 3, 1, 0, 0],[{v:"Coryell", f:"Coryell"}, 208, 0, 206, 2, 0, 0],[{v:"Crane", f:"Crane"}, 2, 0, 0, 0, 0, 2],[{v:"Dallas", f:"Dallas"}, 6123, 0, 5976, 145, 0, 2],[{v:"Dawson", f:"Dawson"}, 30, 0, 28, 1, 0, 1],[{v:"Deaf Smith", f:"Deaf Smith"}, 59, 0, 57, 0, 0, 2],[{v:"Callahan", f:"Callahan"}, 6, 0, 5, 1, 0, 0],[{v:"Denton", f:"Denton"}, 946, 24, 600, 25, 0, 321],[{v:"DeWitt", f:"DeWitt"}, 15, 0, 8, 1, 0, 6],[{v:"Camp", f:"Camp"}, 7, 0, 7, 0, 0, 0],[{v:"Eastland", f:"Eastland"}, 3, 0, 3, 0, 0, 0],[{v:"Carson", f:"Carson"}, 3, 0, 3, 0, 0, 0],[{v:"Ector", f:"Ector"}, 103, 1, 76, 4, 0, 23],[{v:"El Paso", f:"El Paso"}, 1340, 0, 1186, 33, 0, 121],[{v:"Ellis", f:"Ellis"}, 211, 0, 200, 11, 0, 0],[{v:"Erath", f:"Erath"}, 15, 0, 14, 1, 0, 0],[{v:"Falls", f:"Falls"}, 6, 0, 6, 0, 0, 0],[{v:"Childress", f:"Childress"}, 2, 0, 2, 0, 0, 0],[{v:"Fannin", f:"Fannin"}, 23, 0, 22, 1, 0, 0],[{v:"Clay", f:"Clay"}, 3, 0, 3, 0, 0, 0],[{v:"Fayette", f:"Fayette"}, 25, 0, 24, 1, 0, 0],[{v:"Cochran", f:"Cochran"}, 1, 0, 1, 0, 0, 0],[{v:"Fort Bend", f:"Fort Bend"}, 1385, 0, 1243, 38, 0, 104],[{v:"Coke", f:"Coke"}, 1, 0, 1, 0, 0, 0],[{v:"Franklin", f:"Franklin"}, 3, 0, 3, 0, 0, 0],[{v:"Coleman", f:"Coleman"}, 2, 0, 2, 0, 0, 0],[{v:"Gaines", f:"Gaines"}, 3, 0, 3, 0, 0, 0],[{v:"Galveston", f:"Galveston"}, 686, 1, 414, 29, 0, 243],[{v:"Collingsworth", f:"Collingsworth"}, 4, 0, 4, 0, 0, 0],[{v:"Grayson", f:"Grayson"}, 91, 0, 91, 0, 0, 0],[{v:"Colorado", f:"Colorado"}, 16, 0, 16, 0, 0, 0],[{v:"Gregg", f:"Gregg"}, 118, 0, 102, 0, 0, 16],[{v:"Grimes", f:"Grimes"}, 42, 0, 41, 1, 0, 0],[{v:"Guadalupe", f:"Guadalupe"}, 97, 0, 70, 0, 0, 27],[{v:"Concho", f:"Concho"}, 1, 0, 1, 0, 0, 0],[{v:"Hale", f:"Hale"}, 37, 0, 28, 4, 0, 5],[{v:"Cooke", f:"Cooke"}, 12, 0, 12, 0, 0, 0],[{v:"Hardin", f:"Hardin"}, 115, 0, 74, 3, 0, 38],[{v:"Harris", f:"Harris"}, 8176, 0, 6538, 179, 0, 1459],[{v:"Cottle", f:"Cottle"}, 4, 0, 3, 1, 0, 0],[{v:"Harrison", f:"Harrison"}, 186, 0, 177, 9, 0, 0],[{v:"Hays", f:"Hays"}, 209, 5, 136, 2, 0, 71],[{v:"Henderson", f:"Henderson"}, 41, 0, 41, 0, 0, 0],[{v:"Crosby", f:"Crosby"}, 2, 0, 1, 1, 0, 0],[{v:"Hidalgo", f:"Hidalgo"}, 394, 5, 307, 8, 0, 79],[{v:"Hill", f:"Hill"}, 19, 0, 18, 1, 0, 0],[{v:"Dallam", f:"Dallam"}, 14, 0, 12, 1, 0, 1],[{v:"Hockley", f:"Hockley"}, 21, 0, 20, 1, 0, 0],[{v:"Hood", f:"Hood"}, 22, 0, 14, 3, 0, 5],[{v:"Hopkins", f:"Hopkins"}, 8, 0, 8, 0, 0, 0],[{v:"Houston", f:"Houston"}, 13, 0, 13, 0, 0, 0],[{v:"Delta", f:"Delta"}, 1, 0, 1, 0, 0, 0],[{v:"Hunt", f:"Hunt"}, 57, 0, 54, 3, 0, 0],[{v:"Jackson", f:"Jackson"}, 14, 0, 11, 0, 0, 3],[{v:"Jasper", f:"Jasper"}, 22, 0, 19, 2, 0, 1],[{v:"Dickens", f:"Dickens"}, 1, 0, 1, 0, 0, 0],[{v:"Jefferson", f:"Jefferson"}, 381, 0, 320, 25, 0, 36],[{v:"Dimmit", f:"Dimmit"}, 1, 0, 1, 0, 0, 0],[{v:"Johnson", f:"Johnson"}, 150, 0, 146, 4, 0, 0],[{v:"Donley", f:"Donley"}, 26, 0, 13, 0, 0, 13],[{v:"Karnes", f:"Karnes"}, 3, 0, 1, 0, 0, 2],[{v:"Duval", f:"Duval"}, 5, 0, 5, 0, 0, 0],[{v:"Kaufman", f:"Kaufman"}, 120, 0, 119, 1, 0, 0],[{v:"Kendall", f:"Kendall"}, 19, 0, 11, 0, 0, 8],[{v:"Kleberg", f:"Kleberg"}, 11, 0, 10, 1, 0, 0],[{v:"Lamar", f:"Lamar"}, 89, 0, 85, 4, 0, 0],[{v:"Lamb", f:"Lamb"}, 7, 0, 7, 0, 0, 0],[{v:"Lavaca", f:"Lavaca"}, 6, 0, 4, 1, 0, 1],[{v:"Leon", f:"Leon"}, 9, 0, 9, 0, 0, 0],[{v:"Liberty", f:"Liberty"}, 66, 0, 65, 1, 0, 0],[{v:"Limestone", f:"Limestone"}, 15, 0, 14, 1, 0, 0],[{v:"Llano", f:"Llano"}, 3, 0, 3, 0, 0, 0],[{v:"Lubbock", f:"Lubbock"}, 598, 6, 399, 50, 1, 149],[{v:"Floyd", f:"Floyd"}, 4, 0, 4, 0, 0, 0],[{v:"Lynn", f:"Lynn"}, 5, 0, 4, 1, 0, 0],[{v:"Martin", f:"Martin"}, 3, 0, 2, 1, 0, 0],[{v:"Matagorda", f:"Matagorda"}, 64, 0, 48, 5, 0, 11],[{v:"Maverick", f:"Maverick"}, 31, 0, 27, 0, 0, 4],[{v:"Freestone", f:"Freestone"}, 7, 0, 7, 0, 0, 0],[{v:"McLennan", f:"McLennan"}, 94, 0, 88, 4, 0, 2],[{v:"Frio", f:"Frio"}, 34, 0, 33, 0, 0, 1],[{v:"Medina", f:"Medina"}, 32, 0, 28, 2, 0, 2],[{v:"Midland", f:"Midland"}, 101, 0, 70, 11, 0, 20],[{v:"Milam", f:"Milam"}, 20, 0, 19, 1, 0, 0],[{v:"Garza", f:"Garza"}, 3, 0, 3, 0, 0, 0],[{v:"Montague", f:"Montague"}, 9, 0, 8, 1, 0, 0],[{v:"Gillespie", f:"Gillespie"}, 4, 0, 3, 0, 0, 1],[{v:"Montgomery", f:"Montgomery"}, 724, 0, 573, 17, 0, 134],[{v:"Glasscock", f:"Glasscock"}, 1, 0, 1, 0, 0, 0],[{v:"Moore", f:"Moore"}, 527, 0, 497, 9, 1, 21],[{v:"Goliad", f:"Goliad"}, 7, 0, 6, 0, 0, 1],[{v:"Morris", f:"Morris"}, 9, 0, 9, 0, 0, 0],[{v:"Gonzales", f:"Gonzales"}, 59, 0, 56, 2, 0, 1],[{v:"Nacogdoches", f:"Nacogdoches"}, 211, 0, 182, 9, 0, 20],[{v:"Gray", f:"Gray"}, 75, 0, 74, 0, 0, 1],[{v:"Navarro", f:"Navarro"}, 36, 0, 34, 2, 0, 0],[{v:"Nueces", f:"Nueces"}, 147, 15, 144, 3, 0, 0],[{v:"Oldham", f:"Oldham"}, 3, 0, 2, 1, 0, 0],[{v:"Orange", f:"Orange"}, 85, 0, 55, 2, 0, 28],[{v:"Parker", f:"Parker"}, 45, 0, 45, 0, 0, 0],[{v:"Polk", f:"Polk"}, 35, 0, 35, 0, 0, 0],[{v:"Potter", f:"Potter"}, 1179, 55, 1142, 17, 2, 20],[{v:"Hamilton", f:"Hamilton"}, 7, 0, 7, 0, 0, 0],[{v:"Randall", f:"Randall"}, 379, 21, 354, 3, 0, 22],[{v:"Hansford", f:"Hansford"}, 12, 0, 10, 2, 0, 0],[{v:"Reeves", f:"Reeves"}, 7, 0, 7, 0, 0, 0],[{v:"Robertson", f:"Robertson"}, 5, 0, 5, 0, 0, 0],[{v:"Rockwall", f:"Rockwall"}, 104, 0, 99, 5, 0, 0],[{v:"Rusk", f:"Rusk"}, 40, 0, 39, 1, 0, 0],[{v:"San Jacinto", f:"San Jacinto"}, 11, 0, 11, 0, 0, 0],[{v:"Hartley", f:"Hartley"}, 8, 0, 6, 2, 0, 0],[{v:"San Patricio", f:"San Patricio"}, 22, 0, 22, 0, 0, 0],[{v:"Shelby", f:"Shelby"}, 152, 0, 141, 5, 0, 6],[{v:"Smith", f:"Smith"}, 178, 4, 115, 4, 0, 59],[{v:"Hemphill", f:"Hemphill"}, 1, 0, 1, 0, 0, 0],[{v:"Starr", f:"Starr"}, 14, 0, 14, 0, 0, 0],[{v:"Swisher", f:"Swisher"}, 12, 0, 11, 0, 0, 1],[{v:"Tarrant", f:"Tarrant"}, 3745, 50, 3376, 104, 1, 265],[{v:"Taylor", f:"Taylor"}, 386, 2, 377, 6, 0, 3],[{v:"Terry", f:"Terry"}, 12, 0, 9, 0, 0, 3],[{v:"Tom Green", f:"Tom Green"}, 84, 0, 63, 1, 0, 20],[{v:"Travis", f:"Travis"}, 2171, 0, 1839, 65, 0, 267],[{v:"Howard", f:"Howard"}, 6, 0, 5, 1, 0, 0],[{v:"Upshur", f:"Upshur"}, 17, 0, 17, 0, 0, 0],[{v:"Uvalde", f:"Uvalde"}, 7, 0, 1, 0, 0, 6],[{v:"Val Verde", f:"Val Verde"}, 13, 0, 2, 0, 0, 11],[{v:"Hutchinson", f:"Hutchinson"}, 21, 0, 20, 0, 0, 1],[{v:"Van Zandt", f:"Van Zandt"}, 18, 0, 17, 1, 0, 0],[{v:"Victoria", f:"Victoria"}, 150, 0, 132, 5, 0, 13],[{v:"Jack", f:"Jack"}, 4, 0, 4, 0, 0, 0],[{v:"Walker", f:"Walker"}, 342, 0, 326, 2, 0, 14],[{v:"Waller", f:"Waller"}, 39, 0, 39, 0, 0, 0],[{v:"Washington", f:"Washington"}, 164, 0, 132, 18, 0, 14],[{v:"Webb", f:"Webb"}, 437, 2, 332, 17, 0, 88],[{v:"Wharton", f:"Wharton"}, 41, 0, 27, 0, 0, 14],[{v:"Jim Hogg", f:"Jim Hogg"}, 3, 0, 3, 0, 0, 0],[{v:"Wichita", f:"Wichita"}, 75, 0, 58, 2, 0, 15],[{v:"Jim Wells", f:"Jim Wells"}, 7, 0, 7, 0, 0, 0],[{v:"Willacy", f:"Willacy"}, 14, 0, 13, 1, 0, 0],[{v:"Williamson", f:"Williamson"}, 380, 0, 283, 14, 0, 83],[{v:"Jones", f:"Jones"}, 95, 0, 95, 0, 0, 0],[{v:"Wilson", f:"Wilson"}, 36, 0, 28, 4, 0, 4],[{v:"Wise", f:"Wise"}, 30, 0, 28, 2, 0, 0],[{v:"Yoakum", f:"Yoakum"}, 2, 0, 2, 0, 0, 0],[{v:"Young", f:"Young"}, 4, 0, 3, 1, 0, 0],[{v:"Newton", f:"Newton"}, 4, 0, 3, 0, 0, 1],[{v:"Tyler", f:"Tyler"}, 7, 0, 7, 0, 0, 0],[{v:"Kerr", f:"Kerr"}, 9, 0, 7, 0, 0, 2],[{v:"Kimble", f:"Kimble"}, 1, 0, 1, 0, 0, 0],[{v:"Live Oak", f:"Live Oak"}, 5, 0, 5, 0, 0, 0],[{v:"Knox", f:"Knox"}, 1, 0, 1, 0, 0, 0],[{v:"La Salle", f:"La Salle"}, 2, 0, 2, 0, 0, 0],[{v:"San Augustine", f:"San Augustine"}, 21, 0, 20, 1, 0, 0],[{v:"Wood", f:"Wood"}, 14, 0, 14, 0, 0, 0],[{v:"Panola", f:"Panola"}, 168, 0, 155, 8, 0, 5],[{v:"Lampasas", f:"Lampasas"}, 8, 0, 8, 0, 0, 0],[{v:"Lee", f:"Lee"}, 5, 0, 5, 0, 0, 0],[{v:"Lipscomb", f:"Lipscomb"}, 2, 0, 2, 0, 0, 0],[{v:"Palo Pinto", f:"Palo Pinto"}, 9, 0, 7, 2, 0, 0],[{v:"Titus", f:"Titus"}, 35, 0, 35, 0, 0, 0],[{v:"Trinity", f:"Trinity"}, 11, 0, 11, 0, 0, 0],[{v:"Madison", f:"Madison"}, 3, 0, 3, 0, 0, 0],[{v:"Marion", f:"Marion"}, 16, 0, 16, 0, 0, 0],[{v:"Mason", f:"Mason"}, 28, 0, 28, 0, 0, 0],[{v:"Pecos", f:"Pecos"}, 15, 0, 15, 0, 0, 0],[{v:"McCulloch", f:"McCulloch"}, 3, 0, 3, 0, 0, 0],[{v:"Zapata", f:"Zapata"}, 7, 0, 7, 0, 0, 0],[{v:"Mitchell", f:"Mitchell"}, 1, 0, 1, 0, 0, 0],[{v:"Motley", f:"Motley"}, 1, 0, 1, 0, 0, 0],[{v:"Rains", f:"Rains"}, 2, 0, 2, 0, 0, 0],[{v:"Nolan", f:"Nolan"}, 2, 0, 2, 0, 0, 0],[{v:"Scurry", f:"Scurry"}, 2, 0, 2, 0, 0, 0],[{v:"Ochiltree", f:"Ochiltree"}, 29, 0, 28, 1, 0, 0],[{v:"Stephens", f:"Stephens"}, 1, 0, 1, 0, 0, 0],[{v:"Winkler", f:"Winkler"}, 3, 0, 3, 0, 0, 0],[{v:"Parmer", f:"Parmer"}, 19, 0, 19, 0, 0, 0],[{v:"Wilbarger", f:"Wilbarger"}, 2, 0, 2, 0, 0, 0],[{v:"Red River", f:"Red River"}, 9, 0, 9, 0, 0, 0],[{v:"Roberts", f:"Roberts"}, 2, 0, 2, 0, 0, 0],[{v:"Sabine", f:"Sabine"}, 2, 0, 2, 0, 0, 0],[{v:"Sherman", f:"Sherman"}, 23, 0, 23, 0, 0, 0],[{v:"Zavala", f:"Zavala"}, 2, 0, 2, 0, 0, 0],[{v:"Refugio", f:"Refugio"}, 1, 0, 1, 0, 0, 0],[{v:"Runnels", f:"Runnels"}, 2, 0, 2, 0, 0, 0],[{v:"Wheeler", f:"Wheeler"}, 14, 0, 14, 0, 0, 0],[{v:"Shackelford", f:"Shackelford"}, 1, 0, 1, 0, 0, 0],
    ]);
    data.setProperty(0, 0, 'style', 'min-width:100px');
    var table = new google.visualization.Table(document.getElementById('geo_table'));
    table.draw(data, {allowHtml: true, sortColumn: 2, sortAscending: false, width: '660px', height: '100%'});
  }
</script>

<span style="font-size: 13px">All COVID-19 data displayed on the page is available through our FREE <a href="https://developer.smartable.ai">API program</a>. This US - Texas State Coronavirus (COVID-19) Live Stats is refreshed every hour using credible data sources, including the country/state's official government website, <a href="https://en.wikipedia.org/wiki/2019%E2%80%9320_coronavirus_pandemic" target="_blank">data available on wikipedia pages</a>, latest news reports, <a href="https://systems.jhu.edu/research/public-health/ncov/" target="_blank">Johns Hopkins University CSSE 2019-nCoV Dashboard</a>, <a href="https://www.who.int/emergencies/diseases/novel-coronavirus-2019/situation-reports" target="_blank">WHO Situation Reports</a>, <a href="https://www.cdc.gov/coronavirus/2019-ncov/index.html" target="_blank">CDC Situation Updates</a>, and <a href="https://ncov.dxy.cn/ncovh5/view/pneumonia" target="_blank">DXY.cn</a>.</span>

<h2 id="news" class="center" style="margin-top: 60px; font-size: 25px;">Local Government Help Information</h2>
<div class="info center">
<a href="https://www.dshs.state.tx.us/coronavirus/" target="_blank">Texas Department of State Health Services</a> 877-570-9779<br /><a href="https://www.dshs.state.tx.us/regions/2019-nCoV-Local-Health-Entities/" target="_blank">Local Health Entities</a>
</div>
<h2 id="news" class="center" style="margin-top: 60px; font-size: 25px;">Trending Coronavirus News in US-Texas</h2>
<div class="row">
<div class="col-md-6 col-sm-12">
  <div class="content-card">
	<a href="https://www.kxan.com/news/texas/texans-have-received-over-10-7-million-economic-impact-payments/"><div class="card-image" style="background-image: url(https://www.kxan.com/wp-content/uploads/sites/40/2020/05/d00c3ff529654f51b7a8ef955791d1d0.jpg?w=1280&h=720&crop=1)"></div></a>
	<div class="content">
		<div class="card-title"><a href="https://www.kxan.com/news/texas/texans-have-received-over-10-7-million-economic-impact-payments/">Texans have received over 10.7 million Economic Impact Payments</a></div>
		<div class="card-excerpt">Texans have received over 10.7 million Economic Impact Payments totaling more than $18.7 billion, according to the U.S. Treasury Department.</div>
		<div class="card-meta">
			<span class="card-provider">KXAN</span> • <span class="card-date">5/9/2020</span>
		</div>
	</div>
  </div>
</div>
<div class="col-md-6 col-sm-12">
  <div class="content-card">
	<a href="https://www.fox4news.com/news/city-of-dallas-to-furlough-nearly-500-employees"><div class="card-image" style="background-image: url(https://images.foxtv.com/static.fox4news.com/www.fox4news.com/content/uploads/2020/05/932/470/city-hall.jpg?ve=1&tl=1)"></div></a>
	<div class="content">
		<div class="card-title"><a href="https://www.fox4news.com/news/city-of-dallas-to-furlough-nearly-500-employees">City of Dallas to furlough nearly 500 employees</a></div>
		<div class="card-excerpt">The city of Dallas announced it is furloughing nearly 500 of its employees as part of phase one of cuts to offset a $25 million budget shortfall. Workers in 10 different departments got a notification about their job on Friday.</div>
		<div class="card-meta">
			<span class="card-provider">KDFW</span> • <span class="card-date">5/8/2020</span>
		</div>
	</div>
  </div>
</div>
<div class="col-md-6 col-sm-12">
  <div class="content-card">
	<a href="https://www.foxnews.com/auto/indycar-season-restarting-in-texas-june-6"><div class="card-image" style="background-image: url(https://a57.foxnews.com/static.foxnews.com/foxnews.com/content/uploads/2020/05/640/320/texas1.jpg?ve=1&tl=1)"></div></a>
	<div class="content">
		<div class="card-title"><a href="https://www.foxnews.com/auto/indycar-season-restarting-in-texas-june-6">IndyCar season restarting in Texas June 6</a></div>
		<div class="card-excerpt">IndyCar has gotten the green flag to finally start its season in Texas next month with a nighttime race June 6 without spectators. The race at Texas Motor Speedway was the next one on the series schedule that hadn't been postponed or canceled because of the coronavirus pandemic.</div>
		<div class="card-meta">
			<span class="card-provider">Fox News</span> • <span class="card-date">5/8/2020</span>
		</div>
	</div>
  </div>
</div>
<div class="col-md-6 col-sm-12">
  <div class="content-card">
	<a href="https://www.nbcdfw.com/news/coronavirus/walmart-opens-additional-covid-19-testing-locations-in-dallas-county/2366078/"><div class="card-image" style="background-image: url(https://media.nbcdfw.com/2019/09/GettyImages-1219427564.jpg?resize=850%2C478)"></div></a>
	<div class="content">
		<div class="card-title"><a href="https://www.nbcdfw.com/news/coronavirus/walmart-opens-additional-covid-19-testing-locations-in-dallas-county/2366078/">Walmart Opens Additional COVID-19 Testing Locations in Dallas County</a></div>
		<div class="card-excerpt">Walmart is opening a new COVID-19 testing site in Dallas County on Friday. The new site will be located the Walmart parking lot at 9410 Webb Chapel Road. This site will test anyone who meets the CDC,</div>
		<div class="card-meta">
			<span class="card-provider">NBC DFW</span> • <span class="card-date">5/8/2020</span>
		</div>
	</div>
  </div>
</div>
<div class="col-md-6 col-sm-12">
  <div class="content-card">
	<a href="https://detroit.cbslocal.com/2020/05/08/indycar-to-open-season-in-texas/"><div class="card-image" style="background-image: url(https://detroit.cbslocal.com/wp-content/uploads/sites/15909782/2020/05/GettyImages-970660826-e1588943489927.jpg)"></div></a>
	<div class="content">
		<div class="card-title"><a href="https://detroit.cbslocal.com/2020/05/08/indycar-to-open-season-in-texas/">IndyCar To Open Season In Texas</a></div>
		<div class="card-excerpt">IndyCar has gotten the green flag to finally start its season in Texas next month with a nighttime race on June 6 without spectators.</div>
		<div class="card-meta">
			<span class="card-provider">CBS Boston / WBZ</span> • <span class="card-date">5/8/2020</span>
		</div>
	</div>
  </div>
</div>
<div class="col-md-6 col-sm-12">
  <div class="content-card">
	<a href="https://www.cbsnews.com/news/shelley-luther-dallas-salon-owner-released-jail-greg-abbott-texas/"><div class="card-image" style="background-image: url(https://cbsnews3.cbsistatic.com/hub/i/r/2020/05/07/d25dd82c-772c-44ba-865d-acc05d4b3988/thumbnail/1200x630g2/9f324a3de52d1a29f340126d955a70c0/ap-20128708740033.jpg)"></div></a>
	<div class="content">
		<div class="card-title"><a href="https://www.cbsnews.com/news/shelley-luther-dallas-salon-owner-released-jail-greg-abbott-texas/">Salon owner released from jail after Texas governor changes coronavirus orders</a></div>
		<div class="card-excerpt">Shelley Luther, the Dallas salon owner who was arrested earlier this week for violating a stay-at-home order by reopening her business, was released from jail on Thursday. Texas Governor Greg Abbott modified his COVID-19 executive orders earlier in the day,</div>
		<div class="card-meta">
			<span class="card-provider">CBS News</span> • <span class="card-date">5/8/2020</span>
		</div>
	</div>
  </div>
</div>
<div class="col-md-6 col-sm-12">
  <div class="content-card">
	<a href="https://www.nbcdfw.com/news/coronavirus/reopening-texas-salons-barbershops-open-doors-again/2365690/"><div class="card-image" style="background-image: url(https://media.nbcdfw.com/2019/09/hair-salon-4.jpg?resize=1024%2C675)"></div></a>
	<div class="content">
		<div class="card-title"><a href="https://www.nbcdfw.com/news/coronavirus/reopening-texas-salons-barbershops-open-doors-again/2365690/">Reopening Texas: Salons, Barbershops Open Doors Again</a></div>
		<div class="card-excerpt">The reopening of Texas continues Friday as salons, barbershops, nail salons and tanning facilities are allowed to open their doors for the first time in well over a month.</div>
		<div class="card-meta">
			<span class="card-provider">NBC DFW</span> • <span class="card-date">5/8/2020</span>
		</div>
	</div>
  </div>
</div>
<div class="col-md-6 col-sm-12">
  <div class="content-card">
	<a href="https://www.cnn.com/us/live-news/us-coronavirus-update-04-22-20/h_9b9ce03bb565039f9908182f5995d0b1"><div class="card-image" style="background-image: url(https://cdn.cnn.com/cnnnext/dam/assets/200213175739-03-coronavirus-0213-super-tease.jpg)"></div></a>
	<div class="content">
		<div class="card-title"><a href="https://www.cnn.com/us/live-news/us-coronavirus-update-04-22-20/h_9b9ce03bb565039f9908182f5995d0b1">Masks to become part of life in California, but rules vary</a></div>
		<div class="card-excerpt">For Californians venturing outside, donning a mask will be as common as putting on a cap or sunglasses when the state begins gradually easing stay-at-home orders on Friday. But rules about face coverings vary from county to county,</div>
		<div class="card-meta">
			<span class="card-provider">Houston Chronicle</span> • <span class="card-date">5/7/2020</span>
		</div>
	</div>
  </div>
</div>
<div class="col-md-6 col-sm-12">
  <div class="content-card">
	<a href="https://www.cnn.com/us/live-news/us-coronavirus-update-04-22-20/h_9b9ce03bb565039f9908182f5995d0b1"><div class="card-image" style="background-image: url(https://cdn.cnn.com/cnnnext/dam/assets/200213175739-03-coronavirus-0213-super-tease.jpg)"></div></a>
	<div class="content">
		<div class="card-title"><a href="https://www.cnn.com/us/live-news/us-coronavirus-update-04-22-20/h_9b9ce03bb565039f9908182f5995d0b1">Coronavirus updates: Beyonce's BEYGood Foundation, mom Tina offer free COVID-19 testing in Houston this weekend</a></div>
		<div class="card-excerpt">We are continuing to track the latest headlines and updates regarding the global coronavirus (COVID-19) pandemic. LIVE @ 3 p.m. - Mayor Sylvester Turner and Recovery Czar Marvin Odum will announce the city's expanded program to contain the spread of COVID-19.</div>
		<div class="card-meta">
			<span class="card-provider">KHOU 11</span> • <span class="card-date">5/7/2020</span>
		</div>
	</div>
  </div>
</div>
<div class="col-md-6 col-sm-12">
  <div class="content-card">
	<a href="https://www.cnn.com/us/live-news/us-coronavirus-update-04-30-20/h_8951e72d2aa107da53f04d14d68ae727"><div class="card-image" style="background-image: url(https://dynaimage.cdn.cnn.com/cnn/digital-images/w_900,h_617/97277ac5-2172-4f92-9518-e8e955d7857c.jpg)"></div></a>
	<div class="content">
		<div class="card-title"><a href="https://www.cnn.com/us/live-news/us-coronavirus-update-04-30-20/h_8951e72d2aa107da53f04d14d68ae727">Golf courses, parks and marinas packed in Harford after Gov. Larry Hogan lightens coronavirus restrictions</a></div>
		<div class="card-excerpt">Thursday was like Christmas came early for those anxious to get back on the golf course and on the water, as Maryland Gov. Larry Hogan peeled back coronavirus restrictions on certain outdoor recreational activities.</div>
		<div class="card-meta">
			<span class="card-provider">The Baltimore Sun</span> • <span class="card-date">5/7/2020</span>
		</div>
	</div>
  </div>
</div>

</div>

