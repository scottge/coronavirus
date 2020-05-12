---
category: stats
title: "US - Georgia State Coronavirus (COVID-19) Live Stats"
excerpt: "Live stats of COVID-19 in US-Georgia. Total Cases: 34737 (+735), Deaths: 1469 (+25), Recoveries: 340(-)."
publishedDateTime: 2020-05-12T21:45:15Z
updatedDateTime: 2020-05-12T21:45:15Z
webUrl: "https://smartable.ai/apps/coronavirus/stats/us-ga/"
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
  - url: "https://smartable.azureedge.net/coronavirus/sites/2/2020/us-ga.jpg"
    width: 900
    height: 564
    title: "US - Georgia State Coronavirus (COVID-19) Live Stats"

---
<div class="total-stats" style="text-align: center;">
    <h3>
	    <div style="font-size: 18px; font-weight: 400;">Total Confirmed Cases:</div>
	    34737 (<span class='red'>+735</span>)
    </h3>
    <h3>
	    <div style="font-size: 18px; font-weight: 400;">Total Deaths:</div>
	    1469 (<span class='red'>+25</span>)
    </h3>
    <h3>
	    <div style="font-size: 18px; font-weight: 400;">Total Recovered:</div>
	    340 (-)
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
      ['1/22/2020', 0, 0, 0],['1/23/2020', 0, 0, 0],['1/24/2020', 0, 0, 0],['1/25/2020', 0, 0, 0],['1/26/2020', 0, 0, 0],['1/27/2020', 0, 0, 0],['1/28/2020', 0, 0, 0],['1/29/2020', 0, 0, 0],['1/30/2020', 0, 0, 0],['1/31/2020', 0, 0, 0],['2/1/2020', 0, 0, 0],['2/2/2020', 0, 0, 0],['2/3/2020', 0, 0, 0],['2/4/2020', 0, 0, 0],['2/5/2020', 0, 0, 0],['2/6/2020', 0, 0, 0],['2/7/2020', 0, 0, 0],['2/8/2020', 0, 0, 0],['2/9/2020', 0, 0, 0],['2/10/2020', 0, 0, 0],['2/11/2020', 0, 0, 0],['2/12/2020', 0, 0, 0],['2/13/2020', 0, 0, 0],['2/14/2020', 0, 0, 0],['2/15/2020', 0, 0, 0],['2/16/2020', 0, 0, 0],['2/17/2020', 0, 0, 0],['2/18/2020', 0, 0, 0],['2/19/2020', 0, 0, 0],['2/20/2020', 0, 0, 0],['2/21/2020', 0, 0, 0],['2/22/2020', 0, 0, 0],['2/23/2020', 0, 0, 0],['2/24/2020', 0, 0, 0],['2/25/2020', 0, 0, 0],['2/26/2020', 0, 0, 0],['2/27/2020', 0, 0, 0],['2/28/2020', 0, 0, 0],['2/29/2020', 0, 0, 0],['3/1/2020', 0, 0, 0],['3/2/2020', 0, 0, 0],['3/3/2020', 2, 0, 0],['3/4/2020', 2, 0, 0],['3/5/2020', 2, 0, 0],['3/6/2020', 3, 0, 0],['3/7/2020', 5, 0, 0],['3/8/2020', 5, 0, 0],['3/9/2020', 10, 0, 0],['3/10/2020', 17, 0, 0],['3/11/2020', 23, 0, 0],['3/12/2020', 37, 1, 0],['3/13/2020', 42, 1, 0],['3/14/2020', 96, 1, 0],['3/15/2020', 112, 1, 0],['3/16/2020', 129, 1, 0],['3/17/2020', 169, 1, 0],['3/18/2020', 200, 3, 0],['3/19/2020', 291, 10, 0],['3/20/2020', 487, 14, 0],['3/21/2020', 557, 20, 0],['3/22/2020', 623, 25, 0],['3/23/2020', 805, 26, 0],['3/24/2020', 1099, 38, 0],['3/25/2020', 1381, 47, 0],['3/26/2020', 1777, 56, 0],['3/27/2020', 2204, 65, 0],['3/28/2020', 2450, 79, 0],['3/29/2020', 2687, 84, 0],['3/30/2020', 3035, 102, 0],['3/31/2020', 4119, 125, 0],['4/1/2020', 4750, 154, 0],['4/2/2020', 5445, 176, 0],['4/3/2020', 5968, 198, 0],['4/4/2020', 6384, 208, 0],['4/5/2020', 6743, 219, 0],['4/6/2020', 7559, 294, 0],['4/7/2020', 9157, 348, 0],['4/8/2020', 10190, 370, 0],['4/9/2020', 10886, 412, 0],['4/10/2020', 11860, 425, 0],['4/11/2020', 12262, 433, 340],['4/12/2020', 12551, 442, 340],['4/13/2020', 13622, 480, 340],['4/14/2020', 14571, 525, 340],['4/15/2020', 15260, 576, 340],['4/16/2020', 16367, 617, 340],['4/17/2020', 17428, 668, 340],['4/18/2020', 17834, 677, 340],['4/19/2020', 18287, 687, 340],['4/20/2020', 19391, 774, 340],['4/21/2020', 20158, 818, 340],['4/22/2020', 21103, 846, 340],['4/23/2020', 21884, 881, 340],['4/24/2020', 23197, 909, 340],['4/25/2020', 23216, 907, 340],['4/26/2020', 23481, 920, 340],['4/27/2020', 24225, 994, 340],['4/28/2020', 24854, 1036, 340],['4/29/2020', 25690, 1100, 340],['4/30/2020', 26264, 1135, 340],['5/1/2020', 27268, 1148, 340],['5/2/2020', 28332, 1180, 340],['5/3/2020', 28671, 1187, 340],['5/4/2020', 29493, 1253, 340],['5/5/2020', 29892, 1302, 340],['5/6/2020', 30740, 1335, 340],['5/7/2020', 31580, 1362, 340],['5/8/2020', 32178, 1406, 340],['5/9/2020', 32582, 1414, 340],['5/10/2020', 33508, 1415, 340],['5/11/2020', 34002, 1444, 340],['5/12/2020', 34737, 1469, 340],
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
      [31.7642, -82.3508, "Appling", 94, 10],[31.5441, -82.4145, "Bacon", 45, 1],[31.3172, -84.3376, "Baker", 33, 2],[33.0523, -83.244, "Baldwin", 275, 13],[34.3095, -83.6381, "Banks", 38, 0],[33.9917, -83.7218, "Barrow", 197, 6],[34.266, 84.8151, "Bartow", 366, 33],[31.7135, -83.2515, "Ben Hill", 40, 0],[31.0729, -83.196, "Berrien", 19, 0],[32.8065, -83.6974, "Bibb", 384, 15],[30.9433, -83.5003, "Brooks", 64, 7],[31.9012, -81.3126, "Bryan", 60, 4],[32.5383, -81.9297, "Bulloch", 44, 2],[33.0909, -82.0146, "Burke", 110, 4],[33.2524, -83.903, "Butts", 189, 17],[31.4847, -84.5133, "Calhoun", 117, 5],[30.7985, -81.5628, "Camden", 37, 1],[32.3958, -82.0621, "Candler", 10, 0],[33.7305, -84.917, "Carroll", 397, 19],[34.9318, -85.246, "Catoosa", 58, 0],[30.7917, -82.0843, "Charlton", 17, 1],[32.1043, -81.2568, "Chatham", 319, 13],[32.347, -84.787, "Chattahoochee", 15, 0],[34.4835, -85.4776, "Chattooga", 16, 2],[34.2515, -84.4803, "Cherokee", 624, 18],[33.9666, -83.2815, "Clarke", 188, 13],[33.4773, -84.36, "Clayton", 946, 35],[30.6881, -82.5721, "Clinch", 30, 0],[33.8999, -84.5641, "Cobb", 2220, 121],[31.6248, -82.8877, "Coffee", 182, 10],[31.0683, -83.6236, "Colquitt", 213, 10],[33.4262, -82.3127, "Columbia", 185, 5],[31.0466, -83.3906, "Cook", 33, 3],[33.326, -84.6371, "Coweta", 279, 4],[31.9563, -83.7695, "Crisp", 186, 7],[34.4362, -84.1252, "Dawson", 81, 1],[30.8756, -84.4312, "Decatur", 109, 3],[33.7956, -84.2279, "DeKalb", 2561, 72],[32.1973, -83.1712, "Dodge", 34, 1],[32.1956, -83.7596, "Dooly", 147, 13],[31.4756, -84.101, "Dougherty", 1609, 128],[33.7811, -84.6486, "Douglas", 417, 12],[31.2988, -84.717, "Early", 227, 27],[32.3641, -81.3078, "Effingham", 39, 1],[34.8749, -84.2442, "Fannin", 34, 1],[33.4502, -84.4803, "Fayette", 201, 12],[37.5455, -82.7779, "Floyd", 159, 12],[34.2829, 85.2308, "Floyed", 1, 0],[34.2064, -84.1337, "Forsyth", 397, 10],[34.4953, -83.0975, "Franklin", 28, 1],[33.8034, -84.3963, "Fulton", 3525, 147],[34.6911, -84.484, "Gilmer", 100, 0],[31.145, -81.474, "Glynn", 74, 1],[34.4379, -84.6999, "Gordon", 124, 16],[33.6177, -83.0756, "Greene", 57, 5],[33.9191, -84.0167, "Gwinnett", 2487, 96],[34.5648, -83.5424, "Habersham", 386, 16],[34.3956, -83.6655, "Hall", 2050, 29],[33.7335, -85.2859, "Haralson", 33, 2],[32.7647, -84.8752, "Harris", 68, 2],[34.2859, -83.1097, "Hart", 18, 0],[33.3689, -85.1037, "Heard", 16, 1],[33.4399, -84.1508, "Henry", 614, 15],[32.6341, -83.6854, "Houston", 286, 15],[31.5987, -83.2499, "Irwin", 22, 1],[34.0933, -83.7617, "Jackson", 124, 3],[33.4007, -83.5884, "Jasper", 26, 0],[32.9149, -81.949, "Jenkins", 18, 1],[33.002, -83.5374, "Jones", 31, 0],[33.0508, -84.1527, "Lamar", 40, 2],[32.3835, -82.9917, "Laurens", 82, 1],[31.8128, 84.1435, "Lee", 340, 22],[31.7715, -81.6216, "Liberty", 44, 0],[33.7931, -82.4776, "Lincoln", 12, 0],[31.7096, -81.7457, "Long", 5, 0],[30.86, 83.2934, "Lowndes", 188, 4],[34.5302, -83.9796, "Lumpkin", 76, 2],[32.2997, -84.0246, "Macon", 85, 5],[34.1727, -83.293, "Madison", 29, 1],[32.887, -84.6781, "Meriwether", 66, 1],[31.1017, -84.6848, "Miller", 34, 0],[31.3804, -84.1592, "Mitchell", 353, 33],[33.0347, -83.938, "Monroe", 37, 4],[33.7378, -83.5149, "Morgan", 33, 0],[34.8282, -84.7657, "Murray", 50, 1],[32.51, -84.8771, "Muscogee", 384, 15],[33.5739, -83.894, "Newton", 260, 8],[33.9474, -83.5334, "Oconee", 67, 0],[33.8771, -84.771, "Paulding", 228, 10],[32.5522, -83.8817, "Peach", 64, 2],[34.5279, -84.4939, "Pickens", 35, 2],[31.4088, -82.1132, "Pierce", 67, 4],[33.0918, -84.4385, "Pike", 45, 2],[34.0132, -85.1479, "Polk", 66, 0],[32.2964, -83.4814, "Pulaski", 35, 1],[31.6717, -84.8903, "Randolph", 169, 21],[33.2906, -82.0994, "Richmond", 456, 16],[33.6645, -83.9967, "Rockdale", 244, 7],[32.238, -84.3089, "Schley", 16, 1],[31.0404, -84.8792, "Seminole", 36, 2],[33.2418, -84.2747, "Spalding", 237, 12],[34.5027, -83.1967, "Stephens", 92, 1],[32.0736, -84.2249, "Sumter", 401, 33],[32.2806, -82.1387, "Tattnall", 10, 0],[32.5982, -84.3786, "Taylor", 21, 2],[32.0635, -82.8968, "Telfair", 28, 0],[31.7199, -84.3477, "Terrell", 198, 23],[30.8394, -83.9783, "Thomas", 253, 26],[31.3389, -83.5949, "Tift", 159, 6],[32.1713, -82.3298, "Toombs", 41, 4],[33.1674, -84.9027, "Troup", 192, 5],[31.671, -83.6354, "Turner", 78, 12],[32.606, -83.246, "Twiggs", 8, 0],[32.9369, -84.3405, "Upson", 251, 24],[33.7455, -83.8502, "Walton", 152, 7],[31.2406, -82.3411, "Ware", 165, 13],[33.4626, -82.7055, "Warren", 15, 0],[32.9827, -82.8089, "Washington", 63, 2],[32.1469, -82.7798, "Wheeler", 5, 0],[34.6437, -83.7411, "White", 88, 2],[34.8497, -85.0395, "Whitfield", 165, 6],[33.8674, -82.742, "Wilkes", 27, 0],[31.5103, -83.7368, "Worth", 184, 13],[32.3875, -83.3523, "Bleckley", 29, 0],[31.5198, -84.8691, "Clay", 27, 3],[31.7221, -82.6967, "Jeff Davis", 24, 1],[33.1934, -82.5287, "Jefferson", 17, 1],[32.7265, -82.7197, "Johnson", 67, 2],[32.5789, -84.5516, "Talbot", 27, 1],[34.8741, -85.5096, "Dade", 17, 1],[34.9196, -83.3854, "Rabun", 14, 1],[30.8845, -84.3247, "Grady", 87, 4],[33.9103, -83.218, "Oglethorpe", 56, 4],[32.5214, -81.5331, "Screven", 17, 1],[32.0487, -84.798, "Stewart", 34, 0],[32.1084, -83.5029, "Wilcox", 95, 12],[32.8866, -83.3349, "Wilkinson", 41, 3],[32.5306, -82.592, "Emanuel", 24, 1],[34.9296, -85.294, "Walker", 67, 0],[33.2616, -83.2679, "Putnam", 59, 6],[34.8761, -83.9548, "Union", 35, 2],[31.041, -83.0748, "Lanier", 11, 2],[34.2051, -83.0309, "Elbert", 42, 0],[32.3188, -84.5177, "Marion", 42, 1],[34.9789, -83.554, "Towns", 22, 1],[31.6666, -82.0269, "Wayne", 13, 0],[32.7232, -83.996, "Crawford", 19, 0],[31.2065, -81.9814, "Brantley", 26, 2],[32.3782, -82.5945, "Treutlen", 5, 0],[31.3358, -83.0446, "Atkinson", 20, 1],[33.2767, -82.9704, "Hancock", 132, 4],[32.1882, -82.5699, "Montgomery", 5, 0],[32.1613, -81.9093, "Evans", 5, 0],[31.8485969, -84.981754, "Quitman", 8, 1],[33.7956441, -84.2278796, "Out of GA", 1554, 24],[30.7503289, -82.9501558, "Echols", 7, 0],[32.0129889, -84.564147, "Webster", 11, 2],[33.5258626, -82.5185837, "McDuffie", 51, 4],[31.4748147, -81.3839326, "McIntosh", 7, 0],[33.5697878, -82.8855961, "Taliaferro", 1, 0],[33.2422994, -82.6267345, "Glascock", 1, 1],
    ]);
    var options = {
      backgroundColor: {fill:'transparent',stroke:'#FFF' ,strokeWidth:0 }, 
      displayMode: 'markers',
      region: 'US-GA', 
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
      [{v:"Appling", f:"Appling"}, 94, 1, 84, 10, 0, 0],[{v:"Bacon", f:"Bacon"}, 45, 2, 44, 1, 0, 0],[{v:"Baker", f:"Baker"}, 33, 0, 31, 2, 0, 0],[{v:"Baldwin", f:"Baldwin"}, 275, 0, 262, 13, 0, 0],[{v:"Banks", f:"Banks"}, 38, 2, 38, 0, 0, 0],[{v:"Barrow", f:"Barrow"}, 197, 0, 191, 6, 0, 0],[{v:"Bartow", f:"Bartow"}, 366, 2, 333, 33, 0, 0],[{v:"Ben Hill", f:"Ben Hill"}, 40, 0, 40, 0, 0, 0],[{v:"Berrien", f:"Berrien"}, 19, 0, 19, 0, 0, 0],[{v:"Bibb", f:"Bibb"}, 384, 0, 369, 15, 0, 0],[{v:"Brooks", f:"Brooks"}, 64, 0, 57, 7, 0, 0],[{v:"Bryan", f:"Bryan"}, 60, 0, 56, 4, 0, 0],[{v:"Bulloch", f:"Bulloch"}, 44, 0, 42, 2, 0, 0],[{v:"Burke", f:"Burke"}, 110, 1, 106, 4, 0, 0],[{v:"Butts", f:"Butts"}, 189, 0, 172, 17, 0, 0],[{v:"Calhoun", f:"Calhoun"}, 117, 0, 112, 5, 0, 0],[{v:"Camden", f:"Camden"}, 37, 0, 36, 1, 0, 0],[{v:"Candler", f:"Candler"}, 10, 1, 10, 0, 0, 0],[{v:"Carroll", f:"Carroll"}, 397, 2, 378, 19, 2, 0],[{v:"Catoosa", f:"Catoosa"}, 58, 3, 58, 0, 0, 0],[{v:"Charlton", f:"Charlton"}, 17, 0, 16, 1, 1, 0],[{v:"Chatham", f:"Chatham"}, 319, 8, 306, 13, 0, 0],[{v:"Chattahoochee", f:"Chattahoochee"}, 15, 1, 15, 0, 0, 0],[{v:"Chattooga", f:"Chattooga"}, 16, 0, 14, 2, 0, 0],[{v:"Cherokee", f:"Cherokee"}, 624, 3, 606, 18, 0, 0],[{v:"Clarke", f:"Clarke"}, 188, 0, 175, 13, 0, 0],[{v:"Clayton", f:"Clayton"}, 946, 2, 911, 35, 1, 0],[{v:"Clinch", f:"Clinch"}, 30, 1, 30, 0, 0, 0],[{v:"Cobb", f:"Cobb"}, 2220, 34, 2099, 121, 3, 0],[{v:"Coffee", f:"Coffee"}, 182, 5, 172, 10, 0, 0],[{v:"Colquitt", f:"Colquitt"}, 213, 3, 203, 10, 0, 0],[{v:"Columbia", f:"Columbia"}, 185, 2, 180, 5, 0, 0],[{v:"Cook", f:"Cook"}, 33, 1, 30, 3, 2, 0],[{v:"Coweta", f:"Coweta"}, 279, 1, 275, 4, 0, 0],[{v:"Crisp", f:"Crisp"}, 186, 1, 179, 7, 1, 0],[{v:"Dawson", f:"Dawson"}, 81, 0, 80, 1, 0, 0],[{v:"Decatur", f:"Decatur"}, 109, 0, 106, 3, 1, 0],[{v:"DeKalb", f:"DeKalb"}, 2561, 6, 2489, 72, 1, 0],[{v:"Dodge", f:"Dodge"}, 34, 0, 33, 1, 0, 0],[{v:"Dooly", f:"Dooly"}, 147, 1, 134, 13, 0, 0],[{v:"Dougherty", f:"Dougherty"}, 1609, 0, 1141, 128, 0, 340],[{v:"Douglas", f:"Douglas"}, 417, 0, 405, 12, 0, 0],[{v:"Early", f:"Early"}, 227, 1, 200, 27, 0, 0],[{v:"Effingham", f:"Effingham"}, 39, 1, 38, 1, 0, 0],[{v:"Fannin", f:"Fannin"}, 34, 0, 33, 1, 0, 0],[{v:"Fayette", f:"Fayette"}, 201, 0, 189, 12, 0, 0],[{v:"Floyd", f:"Floyd"}, 159, 1, 147, 12, 0, 0],[{v:"Floyed", f:"Floyed"}, 1, 0, 1, 0, 0, 0],[{v:"Forsyth", f:"Forsyth"}, 397, 6, 387, 10, 0, 0],[{v:"Franklin", f:"Franklin"}, 28, 2, 27, 1, 0, 0],[{v:"Fulton", f:"Fulton"}, 3525, 9, 3378, 147, 2, 0],[{v:"Gilmer", f:"Gilmer"}, 100, 2, 100, 0, 0, 0],[{v:"Glynn", f:"Glynn"}, 74, 1, 73, 1, 0, 0],[{v:"Gordon", f:"Gordon"}, 124, 0, 108, 16, 0, 0],[{v:"Greene", f:"Greene"}, 57, 0, 52, 5, 0, 0],[{v:"Gwinnett", f:"Gwinnett"}, 2487, 12, 2391, 96, 4, 0],[{v:"Habersham", f:"Habersham"}, 386, 0, 370, 16, 0, 0],[{v:"Hall", f:"Hall"}, 2050, 11, 2021, 29, 0, 0],[{v:"Haralson", f:"Haralson"}, 33, 1, 31, 2, 0, 0],[{v:"Harris", f:"Harris"}, 68, 1, 66, 2, 0, 0],[{v:"Hart", f:"Hart"}, 18, 0, 18, 0, 0, 0],[{v:"Heard", f:"Heard"}, 16, 1, 15, 1, 0, 0],[{v:"Henry", f:"Henry"}, 614, 4, 599, 15, 1, 0],[{v:"Houston", f:"Houston"}, 286, 0, 271, 15, 0, 0],[{v:"Irwin", f:"Irwin"}, 22, 0, 21, 1, 0, 0],[{v:"Jackson", f:"Jackson"}, 124, 0, 121, 3, 0, 0],[{v:"Jasper", f:"Jasper"}, 26, 0, 26, 0, 0, 0],[{v:"Jenkins", f:"Jenkins"}, 18, 1, 17, 1, 0, 0],[{v:"Jones", f:"Jones"}, 31, 0, 31, 0, 0, 0],[{v:"Lamar", f:"Lamar"}, 40, 0, 38, 2, 0, 0],[{v:"Laurens", f:"Laurens"}, 82, 0, 81, 1, 0, 0],[{v:"Lee", f:"Lee"}, 340, 0, 318, 22, 0, 0],[{v:"Liberty", f:"Liberty"}, 44, 0, 44, 0, 0, 0],[{v:"Lincoln", f:"Lincoln"}, 12, 0, 12, 0, 0, 0],[{v:"Long", f:"Long"}, 5, 0, 5, 0, 0, 0],[{v:"Lowndes", f:"Lowndes"}, 188, 3, 184, 4, 0, 0],[{v:"Lumpkin", f:"Lumpkin"}, 76, 0, 74, 2, 0, 0],[{v:"Macon", f:"Macon"}, 85, 0, 80, 5, 1, 0],[{v:"Madison", f:"Madison"}, 29, 0, 28, 1, 0, 0],[{v:"Meriwether", f:"Meriwether"}, 66, 0, 65, 1, 0, 0],[{v:"Miller", f:"Miller"}, 34, 0, 34, 0, 0, 0],[{v:"Mitchell", f:"Mitchell"}, 353, 1, 320, 33, 0, 0],[{v:"Monroe", f:"Monroe"}, 37, 2, 33, 4, 0, 0],[{v:"Morgan", f:"Morgan"}, 33, 0, 33, 0, 0, 0],[{v:"Murray", f:"Murray"}, 50, 3, 49, 1, 0, 0],[{v:"Muscogee", f:"Muscogee"}, 384, 7, 369, 15, 1, 0],[{v:"Newton", f:"Newton"}, 260, 0, 252, 8, 0, 0],[{v:"Oconee", f:"Oconee"}, 67, 0, 67, 0, 0, 0],[{v:"Paulding", f:"Paulding"}, 228, 2, 218, 10, 0, 0],[{v:"Peach", f:"Peach"}, 64, 1, 62, 2, 0, 0],[{v:"Pickens", f:"Pickens"}, 35, 2, 33, 2, 0, 0],[{v:"Pierce", f:"Pierce"}, 67, 0, 63, 4, 1, 0],[{v:"Pike", f:"Pike"}, 45, 1, 43, 2, 0, 0],[{v:"Polk", f:"Polk"}, 66, 0, 66, 0, 0, 0],[{v:"Pulaski", f:"Pulaski"}, 35, 0, 34, 1, 0, 0],[{v:"Randolph", f:"Randolph"}, 169, 1, 148, 21, 0, 0],[{v:"Richmond", f:"Richmond"}, 456, 7, 440, 16, 0, 0],[{v:"Rockdale", f:"Rockdale"}, 244, 1, 237, 7, 0, 0],[{v:"Schley", f:"Schley"}, 16, 0, 15, 1, 0, 0],[{v:"Seminole", f:"Seminole"}, 36, 2, 34, 2, 0, 0],[{v:"Spalding", f:"Spalding"}, 237, 0, 225, 12, 1, 0],[{v:"Stephens", f:"Stephens"}, 92, 0, 91, 1, 0, 0],[{v:"Sumter", f:"Sumter"}, 401, 1, 368, 33, 1, 0],[{v:"Tattnall", f:"Tattnall"}, 10, 0, 10, 0, 0, 0],[{v:"Taylor", f:"Taylor"}, 21, 0, 19, 2, 0, 0],[{v:"Telfair", f:"Telfair"}, 28, 0, 28, 0, 0, 0],[{v:"Terrell", f:"Terrell"}, 198, 0, 175, 23, 2, 0],[{v:"Thomas", f:"Thomas"}, 253, 4, 227, 26, 0, 0],[{v:"Tift", f:"Tift"}, 159, 2, 153, 6, 0, 0],[{v:"Toombs", f:"Toombs"}, 41, 1, 37, 4, 1, 0],[{v:"Troup", f:"Troup"}, 192, 2, 187, 5, 0, 0],[{v:"Turner", f:"Turner"}, 78, 0, 66, 12, 0, 0],[{v:"Twiggs", f:"Twiggs"}, 8, 0, 8, 0, 0, 0],[{v:"Upson", f:"Upson"}, 251, 1, 227, 24, 0, 0],[{v:"Walton", f:"Walton"}, 152, 0, 145, 7, 1, 0],[{v:"Ware", f:"Ware"}, 165, 0, 152, 13, 0, 0],[{v:"Warren", f:"Warren"}, 15, 0, 15, 0, 0, 0],[{v:"Washington", f:"Washington"}, 63, 6, 61, 2, 0, 0],[{v:"Wheeler", f:"Wheeler"}, 5, 0, 5, 0, 0, 0],[{v:"White", f:"White"}, 88, 0, 86, 2, 0, 0],[{v:"Whitfield", f:"Whitfield"}, 165, 8, 159, 6, 0, 0],[{v:"Wilkes", f:"Wilkes"}, 27, 0, 27, 0, 0, 0],[{v:"Worth", f:"Worth"}, 184, 1, 171, 13, 0, 0],[{v:"Bleckley", f:"Bleckley"}, 29, 0, 29, 0, 0, 0],[{v:"Clay", f:"Clay"}, 27, 0, 24, 3, 0, 0],[{v:"Jeff Davis", f:"Jeff Davis"}, 24, 0, 23, 1, 0, 0],[{v:"Jefferson", f:"Jefferson"}, 17, 0, 16, 1, 0, 0],[{v:"Johnson", f:"Johnson"}, 67, 0, 65, 2, 0, 0],[{v:"Talbot", f:"Talbot"}, 27, 0, 26, 1, 0, 0],[{v:"Dade", f:"Dade"}, 17, 0, 16, 1, 0, 0],[{v:"Rabun", f:"Rabun"}, 14, 0, 13, 1, 0, 0],[{v:"Grady", f:"Grady"}, 87, 4, 83, 4, 0, 0],[{v:"Oglethorpe", f:"Oglethorpe"}, 56, 0, 52, 4, 0, 0],[{v:"Screven", f:"Screven"}, 17, 0, 16, 1, 0, 0],[{v:"Stewart", f:"Stewart"}, 34, 0, 34, 0, 0, 0],[{v:"Wilcox", f:"Wilcox"}, 95, 0, 83, 12, 0, 0],[{v:"Wilkinson", f:"Wilkinson"}, 41, 0, 38, 3, 1, 0],[{v:"Emanuel", f:"Emanuel"}, 24, 0, 23, 1, 0, 0],[{v:"Walker", f:"Walker"}, 67, 2, 67, 0, 0, 0],[{v:"Putnam", f:"Putnam"}, 59, 1, 53, 6, 0, 0],[{v:"Union", f:"Union"}, 35, 0, 33, 2, 0, 0],[{v:"Lanier", f:"Lanier"}, 11, 0, 9, 2, 0, 0],[{v:"Elbert", f:"Elbert"}, 42, 0, 42, 0, 0, 0],[{v:"Marion", f:"Marion"}, 42, 0, 41, 1, 0, 0],[{v:"Towns", f:"Towns"}, 22, 0, 21, 1, 0, 0],[{v:"Wayne", f:"Wayne"}, 13, 0, 13, 0, 0, 0],[{v:"Crawford", f:"Crawford"}, 19, 0, 19, 0, 0, 0],[{v:"Brantley", f:"Brantley"}, 26, 0, 24, 2, 0, 0],[{v:"Treutlen", f:"Treutlen"}, 5, 0, 5, 0, 0, 0],[{v:"Atkinson", f:"Atkinson"}, 20, 0, 19, 1, 0, 0],[{v:"Hancock", f:"Hancock"}, 132, 4, 128, 4, 1, 0],[{v:"Montgomery", f:"Montgomery"}, 5, 1, 5, 0, 0, 0],[{v:"Evans", f:"Evans"}, 5, 0, 5, 0, 0, 0],[{v:"Quitman", f:"Quitman"}, 8, 0, 7, 1, 0, 0],[{v:"Out of GA", f:"Out of GA"}, 1554, 0, 1530, 24, 0, 0],[{v:"Echols", f:"Echols"}, 7, 0, 7, 0, 0, 0],[{v:"Webster", f:"Webster"}, 11, 1, 9, 2, 0, 0],[{v:"McDuffie", f:"McDuffie"}, 51, 0, 47, 4, 0, 0],[{v:"McIntosh", f:"McIntosh"}, 7, 0, 7, 0, 0, 0],[{v:"Taliaferro", f:"Taliaferro"}, 1, 0, 1, 0, 0, 0],[{v:"Glascock", f:"Glascock"}, 1, 0, 0, 1, 0, 0],
    ]);
    data.setProperty(0, 0, 'style', 'min-width:100px');
    var table = new google.visualization.Table(document.getElementById('geo_table'));
    table.draw(data, {allowHtml: true, sortColumn: 2, sortAscending: false, width: '660px', height: '100%'});
  }
</script>

<span style="font-size: 13px">All COVID-19 data displayed on the page is available through our FREE <a href="https://developer.smartable.ai">API program</a>. This US - Georgia State Coronavirus (COVID-19) Live Stats is refreshed every hour using credible data sources, including the country/state's official government website, <a href="https://en.wikipedia.org/wiki/2019%E2%80%9320_coronavirus_pandemic" target="_blank">data available on wikipedia pages</a>, latest news reports, <a href="https://systems.jhu.edu/research/public-health/ncov/" target="_blank">Johns Hopkins University CSSE 2019-nCoV Dashboard</a>, <a href="https://www.who.int/emergencies/diseases/novel-coronavirus-2019/situation-reports" target="_blank">WHO Situation Reports</a>, <a href="https://www.cdc.gov/coronavirus/2019-ncov/index.html" target="_blank">CDC Situation Updates</a>, and <a href="https://ncov.dxy.cn/ncovh5/view/pneumonia" target="_blank">DXY.cn</a>.</span>

<h2 id="news" class="center" style="margin-top: 60px; font-size: 25px;">Local Government Help Information</h2>
<div class="info center">
<a href="https://dph.georgia.gov/" target="_blank">Georgia Department of Health</a> 866-782-4584
</div>
<h2 id="news" class="center" style="margin-top: 60px; font-size: 25px;">Trending Coronavirus News in US-Georgia</h2>
<div class="row">
<div class="col-md-6 col-sm-12">
  <div class="content-card">
	<a href="https://www.ajc.com/news/latest-atlanta-coronavirus-news-georgia-deaths-close-500/3uKLG9K7aYKCDN0LwwQKKP/"><div class="card-image" style="background-image: url(https://www.ajc.com/rf/image_medium/Pub/p11/AJC/2020/04/11/Videos/4883122.vpx)"></div></a>
	<div class="content">
		<div class="card-title"><a href="https://www.ajc.com/news/latest-atlanta-coronavirus-news-georgia-deaths-close-500/3uKLG9K7aYKCDN0LwwQKKP/">Latest Atlanta coronavirus news: Georgia’s COVID-19 deaths hit 1,400</a></div>
		<div class="card-excerpt">Constitution is committed to providing our readers with the most comprehensive coverage of the deadly coronavirus. This blog will be updated throughout Saturday, May 9, with news and details of COVID-19 in Georgia.</div>
		<div class="card-meta">
			<span class="card-provider">Atlanta Journal-Constitution</span> • <span class="card-date">5/9/2020</span>
		</div>
	</div>
  </div>
</div>
<div class="col-md-6 col-sm-12">
  <div class="content-card">
	<a href="https://www.ajc.com/news/latest-atlanta-coronavirus-news-georgia-deaths-close-500/3uKLG9K7aYKCDN0LwwQKKP/"><div class="card-image" style="background-image: url(https://www.ajc.com/rf/image_medium/Pub/p11/AJC/2020/04/11/Videos/4883122.vpx)"></div></a>
	<div class="content">
		<div class="card-title"><a href="https://www.ajc.com/news/latest-atlanta-coronavirus-news-georgia-deaths-close-500/3uKLG9K7aYKCDN0LwwQKKP/">Latest Atlanta coronavirus news: Georgia’s COVID-19 cases pass 31K</a></div>
		<div class="card-excerpt">Constitution is committed to providing our readers with the most comprehensive coverage of the deadly coronavirus. This blog will be updated throughout Thursday, May 7, with news and details of COVID-19 in Georgia.</div>
		<div class="card-meta">
			<span class="card-provider">Atlanta Journal-Constitution</span> • <span class="card-date">5/7/2020</span>
		</div>
	</div>
  </div>
</div>

</div>

