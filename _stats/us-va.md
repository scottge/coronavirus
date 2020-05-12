---
category: stats
title: "US - Virginia State Coronavirus (COVID-19) Live Stats"
excerpt: "Live stats of COVID-19 in US-Virginia. Total Cases: 25070 (+989), Deaths: 850 (+11), Recoveries: 3124(-)."
publishedDateTime: 2020-05-12T05:45:11Z
updatedDateTime: 2020-05-12T05:45:11Z
webUrl: "https://smartable.ai/apps/coronavirus/stats/us-va/"
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
  - url: "https://smartable.azureedge.net/coronavirus/sites/2/2020/us-va.jpg"
    width: 900
    height: 564
    title: "US - Virginia State Coronavirus (COVID-19) Live Stats"

---
<div class="total-stats" style="text-align: center;">
    <h3>
	    <div style="font-size: 18px; font-weight: 400;">Total Confirmed Cases:</div>
	    25070 (<span class='red'>+989</span>)
    </h3>
    <h3>
	    <div style="font-size: 18px; font-weight: 400;">Total Deaths:</div>
	    850 (<span class='red'>+11</span>)
    </h3>
    <h3>
	    <div style="font-size: 18px; font-weight: 400;">Total Recovered:</div>
	    3124 (-)
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
      ['1/22/2020', 0, 0, 0],['1/23/2020', 0, 0, 0],['1/24/2020', 0, 0, 0],['1/25/2020', 0, 0, 0],['1/26/2020', 0, 0, 0],['1/27/2020', 0, 0, 0],['1/28/2020', 0, 0, 0],['1/29/2020', 0, 0, 0],['1/30/2020', 0, 0, 0],['1/31/2020', 0, 0, 0],['2/1/2020', 0, 0, 0],['2/2/2020', 0, 0, 0],['2/3/2020', 0, 0, 0],['2/4/2020', 0, 0, 0],['2/5/2020', 0, 0, 0],['2/6/2020', 0, 0, 0],['2/7/2020', 0, 0, 0],['2/8/2020', 0, 0, 0],['2/9/2020', 0, 0, 0],['2/10/2020', 0, 0, 0],['2/11/2020', 0, 0, 0],['2/12/2020', 0, 0, 0],['2/13/2020', 0, 0, 0],['2/14/2020', 0, 0, 0],['2/15/2020', 0, 0, 0],['2/16/2020', 0, 0, 0],['2/17/2020', 0, 0, 0],['2/18/2020', 0, 0, 0],['2/19/2020', 0, 0, 0],['2/20/2020', 0, 0, 0],['2/21/2020', 0, 0, 0],['2/22/2020', 0, 0, 0],['2/23/2020', 0, 0, 0],['2/24/2020', 0, 0, 0],['2/25/2020', 0, 0, 0],['2/26/2020', 0, 0, 0],['2/27/2020', 0, 0, 0],['2/28/2020', 0, 0, 0],['2/29/2020', 0, 0, 0],['3/1/2020', 0, 0, 0],['3/2/2020', 0, 0, 0],['3/3/2020', 0, 0, 0],['3/4/2020', 0, 0, 0],['3/5/2020', 0, 0, 0],['3/6/2020', 0, 0, 0],['3/7/2020', 0, 0, 0],['3/8/2020', 2, 0, 0],['3/9/2020', 2, 0, 0],['3/10/2020', 8, 0, 0],['3/11/2020', 9, 0, 0],['3/12/2020', 20, 0, 0],['3/13/2020', 37, 0, 0],['3/14/2020', 48, 1, 0],['3/15/2020', 47, 1, 0],['3/16/2020', 55, 2, 0],['3/17/2020', 70, 2, 0],['3/18/2020', 76, 2, 1],['3/19/2020', 103, 2, 1],['3/20/2020', 123, 2, 1],['3/21/2020', 155, 3, 1],['3/22/2020', 241, 6, 1],['3/23/2020', 281, 7, 1],['3/24/2020', 327, 9, 1],['3/25/2020', 421, 13, 1],['3/26/2020', 491, 14, 1],['3/27/2020', 627, 16, 1],['3/28/2020', 754, 17, 1],['3/29/2020', 899, 24, 1],['3/30/2020', 1029, 25, 1],['3/31/2020', 1258, 27, 1],['4/1/2020', 1487, 35, 2],['4/2/2020', 1688, 41, 2],['4/3/2020', 1964, 47, 2],['4/4/2020', 2341, 52, 2],['4/5/2020', 2569, 52, 2],['4/6/2020', 2801, 66, 2],['4/7/2020', 3253, 66, 2],['4/8/2020', 3554, 75, 2],['4/9/2020', 3944, 109, 2],['4/10/2020', 4398, 121, 2],['4/11/2020', 4957, 130, 2],['4/12/2020', 5148, 141, 2],['4/13/2020', 5608, 149, 2],['4/14/2020', 6035, 157, 721],['4/15/2020', 6351, 195, 721],['4/16/2020', 6729, 208, 721],['4/17/2020', 7318, 231, 721],['4/18/2020', 7870, 258, 721],['4/19/2020', 8339, 277, 721],['4/20/2020', 8782, 300, 721],['4/21/2020', 9412, 324, 721],['4/22/2020', 10044, 349, 721],['4/23/2020', 10767, 373, 721],['4/24/2020', 11546, 436, 721],['4/25/2020', 12366, 438, 1672],['4/26/2020', 12970, 448, 1815],['4/27/2020', 13535, 460, 1815],['4/28/2020', 14339, 493, 1815],['4/29/2020', 14961, 523, 2042],['4/30/2020', 15846, 554, 2104],['5/1/2020', 16770, 580, 2208],['5/2/2020', 17731, 619, 2312],['5/3/2020', 18671, 662, 2497],['5/4/2020', 19492, 687, 2497],['5/5/2020', 20256, 713, 2497],['5/6/2020', 20256, 715, 2734],['5/7/2020', 21570, 769, 2734],['5/8/2020', 22342, 812, 2997],['5/9/2020', 23196, 827, 3124],['5/10/2020', 24081, 839, 3124],['5/11/2020', 25070, 850, 3124],
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
      [37.9299, -75.662, "Accomack", 524, 7],[38.9085, -77.2405, "Fairfax", 6200, 243],[38.1266, -78.4386, "Albemarle", 123, 4],[38.6473, -77.3459, "Prince William", 2991, 53],[38.8185, -77.0861, "Alexandria", 1224, 30],[38.8816, -77.091, "Arlington", 1399, 61],[37.7985, -79.7903, "Alleghany", 6, 0],[37.6133, -77.4768, "Henrico", 1083, 110],[37.3366, -77.9882, "Amelia", 18, 1],[37.4487, -79.1057, "Amherst", 16, 1],[39.0768, -77.6536, "Loudoun", 1195, 30],[37.3273, -77.3194, "Chesterfield", 789, 26],[37.3591, -78.8269, "Appomattox", 22, 0],[38.4362, -78.8735, "Harrisonburg", 583, 21],[36.7335, -76.0435, "Virginia Beach", 505, 17],[38.1618, -78.8413, "Augusta", 64, 1],[37.9603, -76.761, "Richmond", 546, 18],[37.3866, -79.7253, "Bedford", 38, 1],[36.6778, -76.3024, "Chesapeake", 340, 9],[38.4597, -77.3806, "Stafford", 384, 2],[37.3783, -79.8206, "Botetourt", 30, 3],[38.4465, -78.9228, "Rockingham", 360, 2],[36.6179, -82.1607, "Bristol", 3, 0],[36.8508, -76.2859, "Norfolk", 308, 5],[38.7479, -77.4838, "Manassas", 428, 3],[36.5759, -77.9839, "Brunswick", 19, 0],[37.2679, -76.7052, "James", 173, 15],[37.2754, -82.0988, "Buchanan", 16, 0],[37.5541, -78.5514, "Buckingham", 246, 1],[36.6953, -76.6398, "Suffolk", 216, 19],[37.7343004, -79.3539238, "Buena Vista", 8, 0],[37.1051, -76.5185, "Newport News", 164, 10],[37.3426, -78.9863, "Campbell", 13, 0],[37.7772, -77.5161, "Hanover", 171, 16],[37.9856, -77.5244, "Caroline", 38, 2],[36.5815, -80.6688, "Carroll", 34, 0],[36.8468, -76.354, "Portsmouth", 208, 8],[37.3441, -77.0687, "Charles", 21, 1],[37.0551, -76.3629, "Hampton", 146, 3],[38.2042, -77.6078, "Spotsylvania", 257, 4],[36.9933, -78.6009, "Charlotte", 12, 0],[38.0375, -78.4855, "Charlottesville", 68, 2],[38.4705, -78.0001, "Culpeper", 276, 5],[39.0902, -78.223, "Frederick", 166, 2],[37.0836, -76.6747, "Isle of Wight", 112, 3],[36.5762, -78.1107, "Mecklenburg", 134, 10],[39.0933, -78.0601, "Clarke", 16, 0],[38.5769, -78.5027, "Page", 129, 12],[37.265, -77.3969, "Colonial Heights", 66, 6],[37.7785, -79.9868, "Covington", 1, 0],[38.654, -77.637, "Fauquier", 180, 4],[36.5778, -77.1989, "Southampton", 131, 1],[37.5013, -80.1119, "Craig", 4, 0],[37.8652, -78.2627, "Fluvanna", 79, 6],[37.4914, -78.2577, "Cumberland", 13, 0],[36.5831, -79.4088, "Danville", 39, 1],[38.7394, -78.6513, "Shenandoah", 250, 6],[37.6973, -77.8944, "Goochland", 81, 5],[37.0676, -80.4405, "Montgomery", 66, 1],[36.9853, -77.7219, "Dinwiddie", 28, 0],[36.6953, -77.5356, "Emporia", 49, 3],[37.4003, -79.1909, "Lynchburg", 69, 1],[37.9187, -76.8667, "Essex", 24, 0],[38.7718, -77.445, "Manassas Park", 135, 2],[37.2352, -76.5146, "York", 57, 2],[38.8847, -77.1751, "Falls Church", 37, 4],[36.9118, -80.3184, "Floyd", 3, 0],[38.9231, -78.1033, "Warren", 86, 1],[38.0212, -77.9985, "Louisa", 56, 0],[37.1233, -79.6971, "Franklin", 28, 1],[37.2746, -79.8888, "Roanoke", 106, 1],[37.2959, -78.4002, "Prince Edward", 66, 2],[38.2992, -77.4872, "Fredericksburg", 61, 0],[36.666, -80.9176, "Galax", 55, 0],[39.1735, -78.1746, "Winchester", 66, 0],[37.3315, -80.8083, "Giles", 8, 0],[37.2766, -76.5043, "Gloucester", 27, 1],[36.816, -77.4689, "Greensville", 47, 7],[36.7022, -81.4413, "Grayson", 15, 0],[37.2357, -77.3325, "Prince George", 45, 0],[38.2991, -78.4367, "Greene", 15, 1],[36.6326, -81.7891, "Washington", 49, 3],[37.034, -77.0956, "Sussex", 34, 1],[36.839, -78.7284, "Halifax", 22, 0],[37.2043, -77.3913, "Petersburg", 48, 2],[38.3282, -77.2423, "King George", 42, 4],[38.136, -78.1879, "Orange", 47, 0],[36.7009, -79.9424, "Henry", 25, 1],[38.4116, -79.5809, "Highland", 2, 0],[37.2915, -77.2985, "Hopewell", 39, 0],[37.6683, -76.8782, "King and Queen", 5, 0],[37.5095, -76.9862, "New Kent", 26, 2],[37.7458, -77.1315, "King William", 12, 1],[37.257, -76.0093, "Northampton", 170, 5],[37.6621, -76.4205, "Lancaster", 6, 0],[37.2692, -76.7076, "Williamsburg", 42, 3],[36.7764, -82.9433, "Lee", 10, 0],[37.126, -82.6071, "Wise", 22, 1],[37.7825, -79.444, "Lexington", 6, 0],[38.2565, -76.9784, "Westmoreland", 38, 0],[36.9608, -78.1283, "Lunenburg", 6, 0],[38.3792, -78.2586, "Madison", 21, 1],[36.6827, -79.8636, "Martinsville", 2, 0],[37.4984, -76.2883, "Mathews", 5, 0],[36.8009, -81.6832, "Smyth", 13, 0],[37.3912302, -76.317414, "Matthews", 5, 0],[37.6395, -76.5747, "Middlesex", 10, 0],[37.9161, -78.9382, "Nelson", 10, 0],[37.1812, -78.1307, "Nottoway", 14, 0],[37.0954, -79.3029, "Pittsylvania", 17, 1],[37.5427, -77.9267, "Powhatan", 18, 0],[36.953, -81.0881, "Wythe", 13, 2],[37.92, -76.4785, "Northumberland", 10, 1],[36.9314, -82.6262, "Norton", 2, 0],[36.9342, -80.7255, "Pulaski", 10, 0],[38.1593, -79.0611, "Staunton", 18, 0],[38.0674, -78.9014, "Waynesboro", 21, 0],[36.6344, -80.1985, "Patrick", 4, 0],[37.1318, -76.3569, "Poquoson", 7, 0],[37.2864, -80.0555, "Salem", 32, 0],[37.1229, -80.5587, "Radford", 3, 0],[37.9901, -79.5067, "Rockbridge", 9, 0],[38.6562, -78.2322, "Rappahannock", 10, 0],[36.6401, -82.5782, "Scott", 7, 2],[36.9792, -82.296, "Russell", 6, 0],[37.1371, -76.8333, "Surry", 5, 1],[37.0879, -81.808, "Tazewell", 7, 0],
    ]);
    var options = {
      backgroundColor: {fill:'transparent',stroke:'#FFF' ,strokeWidth:0 }, 
      displayMode: 'markers',
      region: 'US-VA', 
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
      [{v:"Accomack", f:"Accomack"}, 524, 16, 517, 7, 0, 0],[{v:"Fairfax", f:"Fairfax"}, 6200, 308, 5957, 243, 4, 0],[{v:"Albemarle", f:"Albemarle"}, 123, 3, 119, 4, 0, 0],[{v:"Prince William", f:"Prince William"}, 2991, 251, 2938, 53, 5, 0],[{v:"Alexandria", f:"Alexandria"}, 1224, 31, 1194, 30, 0, 0],[{v:"Arlington", f:"Arlington"}, 1399, 31, 1338, 61, 0, 0],[{v:"Alleghany", f:"Alleghany"}, 6, 0, 6, 0, 0, 0],[{v:"Henrico", f:"Henrico"}, 1083, 16, 973, 110, 0, 0],[{v:"Amelia", f:"Amelia"}, 18, 0, 17, 1, 0, 0],[{v:"Amherst", f:"Amherst"}, 16, 1, 15, 1, 0, 0],[{v:"Loudoun", f:"Loudoun"}, 1195, 36, 1165, 30, 0, 0],[{v:"Chesterfield", f:"Chesterfield"}, 789, 2, 763, 26, 0, 0],[{v:"Appomattox", f:"Appomattox"}, 22, 0, 22, 0, 0, 0],[{v:"Harrisonburg", f:"Harrisonburg"}, 583, 4, 562, 21, 0, 0],[{v:"Virginia Beach", f:"Virginia Beach"}, 505, 14, 488, 17, 0, 0],[{v:"Augusta", f:"Augusta"}, 64, 0, 63, 1, 0, 0],[{v:"Richmond", f:"Richmond"}, 546, 16, 528, 18, 0, 0],[{v:"Bedford", f:"Bedford"}, 38, 0, 37, 1, 0, 0],[{v:"Chesapeake", f:"Chesapeake"}, 340, 12, 331, 9, 0, 0],[{v:"Stafford", f:"Stafford"}, 384, 10, 382, 2, 0, 0],[{v:"Botetourt", f:"Botetourt"}, 30, 0, 27, 3, 0, 0],[{v:"Rockingham", f:"Rockingham"}, 360, 16, 358, 2, 0, 0],[{v:"Bristol", f:"Bristol"}, 3, 0, 3, 0, 0, 0],[{v:"Norfolk", f:"Norfolk"}, 308, 4, 303, 5, 0, 0],[{v:"Manassas", f:"Manassas"}, 428, 47, 425, 3, 0, 0],[{v:"Brunswick", f:"Brunswick"}, 19, 1, 19, 0, 0, 0],[{v:"James", f:"James"}, 173, 0, 158, 15, 0, 0],[{v:"Buchanan", f:"Buchanan"}, 16, 0, 16, 0, 0, 0],[{v:"Buckingham", f:"Buckingham"}, 246, 0, 245, 1, 0, 0],[{v:"Suffolk", f:"Suffolk"}, 216, 1, 197, 19, 0, 0],[{v:"Buena Vista", f:"Buena Vista"}, 8, 0, 8, 0, 0, 0],[{v:"Newport News", f:"Newport News"}, 164, 5, 154, 10, 0, 0],[{v:"Campbell", f:"Campbell"}, 13, 0, 13, 0, 0, 0],[{v:"Hanover", f:"Hanover"}, 171, 1, 155, 16, 0, 0],[{v:"Caroline", f:"Caroline"}, 38, 0, 36, 2, 0, 0],[{v:"Carroll", f:"Carroll"}, 34, 1, 34, 0, 0, 0],[{v:"Portsmouth", f:"Portsmouth"}, 208, 6, 200, 8, 0, 0],[{v:"Charles", f:"Charles"}, 21, 0, 20, 1, 0, 0],[{v:"Hampton", f:"Hampton"}, 146, 2, 143, 3, 0, 0],[{v:"Spotsylvania", f:"Spotsylvania"}, 257, 9, 253, 4, 0, 0],[{v:"Charlotte", f:"Charlotte"}, 12, 0, 12, 0, 0, 0],[{v:"Charlottesville", f:"Charlottesville"}, 68, 2, 66, 2, 0, 0],[{v:"Culpeper", f:"Culpeper"}, 276, 12, 271, 5, 0, 0],[{v:"Frederick", f:"Frederick"}, 166, 2, 164, 2, 0, 0],[{v:"Isle of Wight", f:"Isle of Wight"}, 112, 2, 109, 3, 0, 0],[{v:"Mecklenburg", f:"Mecklenburg"}, 134, 12, 124, 10, 0, 0],[{v:"Clarke", f:"Clarke"}, 16, 0, 16, 0, 0, 0],[{v:"Page", f:"Page"}, 129, 1, 117, 12, 0, 0],[{v:"Colonial Heights", f:"Colonial Heights"}, 66, 0, 60, 6, 0, 0],[{v:"Covington", f:"Covington"}, 1, 0, 1, 0, 0, 0],[{v:"Fauquier", f:"Fauquier"}, 180, 8, 176, 4, 0, 0],[{v:"Southampton", f:"Southampton"}, 131, 0, 130, 1, 0, 0],[{v:"Craig", f:"Craig"}, 4, 0, 4, 0, 0, 0],[{v:"Fluvanna", f:"Fluvanna"}, 79, 0, 73, 6, 0, 0],[{v:"Cumberland", f:"Cumberland"}, 13, 0, 13, 0, 0, 0],[{v:"Danville", f:"Danville"}, 39, 0, 38, 1, 0, 0],[{v:"Shenandoah", f:"Shenandoah"}, 250, 5, 244, 6, 0, 0],[{v:"Goochland", f:"Goochland"}, 81, 0, 76, 5, 0, 0],[{v:"Montgomery", f:"Montgomery"}, 66, 1, 65, 1, 0, 0],[{v:"Dinwiddie", f:"Dinwiddie"}, 28, 1, 28, 0, 0, 0],[{v:"Emporia", f:"Emporia"}, 49, 1, 46, 3, 0, 0],[{v:"Lynchburg", f:"Lynchburg"}, 69, 1, 68, 1, 0, 0],[{v:"Essex", f:"Essex"}, 24, 1, 24, 0, 0, 0],[{v:"Manassas Park", f:"Manassas Park"}, 135, 15, 133, 2, 0, 0],[{v:"York", f:"York"}, 57, 1, 55, 2, 0, 0],[{v:"Falls Church", f:"Falls Church"}, 37, 0, 33, 4, 0, 0],[{v:"Floyd", f:"Floyd"}, 3, 0, 3, 0, 0, 0],[{v:"Warren", f:"Warren"}, 86, 1, 85, 1, 0, 0],[{v:"Louisa", f:"Louisa"}, 56, 1, 56, 0, 0, 0],[{v:"Franklin", f:"Franklin"}, 28, 1, 27, 1, 0, 0],[{v:"Roanoke", f:"Roanoke"}, 106, 13, 105, 1, 0, 0],[{v:"Prince Edward", f:"Prince Edward"}, 66, 0, 64, 2, 0, 0],[{v:"Fredericksburg", f:"Fredericksburg"}, 61, 0, 61, 0, 0, 0],[{v:"Galax", f:"Galax"}, 55, 10, 55, 0, 0, 0],[{v:"Winchester", f:"Winchester"}, 66, 0, 66, 0, 0, 0],[{v:"Giles", f:"Giles"}, 8, 0, 8, 0, 0, 0],[{v:"Gloucester", f:"Gloucester"}, 27, 0, 26, 1, 0, 0],[{v:"Greensville", f:"Greensville"}, 47, 1, 40, 7, 0, 0],[{v:"Grayson", f:"Grayson"}, 15, 3, 15, 0, 0, 0],[{v:"Prince George", f:"Prince George"}, 45, 1, 45, 0, 0, 0],[{v:"Greene", f:"Greene"}, 15, 0, 14, 1, 0, 0],[{v:"Washington", f:"Washington"}, 49, 0, 46, 3, 0, 0],[{v:"Sussex", f:"Sussex"}, 34, 1, 33, 1, 0, 0],[{v:"Halifax", f:"Halifax"}, 22, 0, 22, 0, 0, 0],[{v:"Petersburg", f:"Petersburg"}, 48, 3, 46, 2, 0, 0],[{v:"King George", f:"King George"}, 42, 1, 38, 4, 0, 0],[{v:"Orange", f:"Orange"}, 47, 1, 47, 0, 0, 0],[{v:"Henry", f:"Henry"}, 25, 3, 24, 1, 0, 0],[{v:"Highland", f:"Highland"}, 2, 0, 2, 0, 0, 0],[{v:"Hopewell", f:"Hopewell"}, 39, 2, 39, 0, 0, 0],[{v:"King and Queen", f:"King and Queen"}, 5, 0, 5, 0, 0, 0],[{v:"New Kent", f:"New Kent"}, 26, 0, 24, 2, 0, 0],[{v:"King William", f:"King William"}, 12, 1, 11, 1, 0, 0],[{v:"Northampton", f:"Northampton"}, 170, 7, 165, 5, 0, 0],[{v:"Lancaster", f:"Lancaster"}, 6, 0, 6, 0, 0, 0],[{v:"Williamsburg", f:"Williamsburg"}, 42, 3, 39, 3, 1, 0],[{v:"Lee", f:"Lee"}, 10, 0, 10, 0, 0, 0],[{v:"Wise", f:"Wise"}, 22, 0, 21, 1, 0, 0],[{v:"Lexington", f:"Lexington"}, 6, 0, 6, 0, 0, 0],[{v:"Westmoreland", f:"Westmoreland"}, 38, 0, 38, 0, 0, 0],[{v:"Lunenburg", f:"Lunenburg"}, 6, 0, 6, 0, 0, 0],[{v:"Madison", f:"Madison"}, 21, 0, 20, 1, 0, 0],[{v:"Martinsville", f:"Martinsville"}, 2, 0, 2, 0, 0, 0],[{v:"Mathews", f:"Mathews"}, 5, 0, 5, 0, 0, 0],[{v:"Smyth", f:"Smyth"}, 13, 0, 13, 0, 0, 0],[{v:"Matthews", f:"Matthews"}, 5, 0, 5, 0, 0, 0],[{v:"Middlesex", f:"Middlesex"}, 10, 0, 10, 0, 0, 0],[{v:"Nelson", f:"Nelson"}, 10, 0, 10, 0, 0, 0],[{v:"Nottoway", f:"Nottoway"}, 14, 0, 14, 0, 0, 0],[{v:"Pittsylvania", f:"Pittsylvania"}, 17, 0, 16, 1, 0, 0],[{v:"Powhatan", f:"Powhatan"}, 18, 0, 18, 0, 0, 0],[{v:"Wythe", f:"Wythe"}, 13, 0, 11, 2, 0, 0],[{v:"Northumberland", f:"Northumberland"}, 10, 0, 9, 1, 0, 0],[{v:"Norton", f:"Norton"}, 2, 0, 2, 0, 0, 0],[{v:"Pulaski", f:"Pulaski"}, 10, 0, 10, 0, 0, 0],[{v:"Staunton", f:"Staunton"}, 18, 3, 18, 0, 0, 0],[{v:"Waynesboro", f:"Waynesboro"}, 21, 0, 21, 0, 0, 0],[{v:"Patrick", f:"Patrick"}, 4, 0, 4, 0, 0, 0],[{v:"Poquoson", f:"Poquoson"}, 7, 0, 7, 0, 0, 0],[{v:"Salem", f:"Salem"}, 32, 1, 32, 0, 0, 0],[{v:"Radford", f:"Radford"}, 3, 0, 3, 0, 0, 0],[{v:"Rockbridge", f:"Rockbridge"}, 9, 0, 9, 0, 0, 0],[{v:"Rappahannock", f:"Rappahannock"}, 10, 2, 10, 0, 0, 0],[{v:"Scott", f:"Scott"}, 7, 0, 5, 2, 0, 0],[{v:"Russell", f:"Russell"}, 6, 0, 6, 0, 0, 0],[{v:"Surry", f:"Surry"}, 5, 0, 4, 1, 0, 0],[{v:"Tazewell", f:"Tazewell"}, 7, 0, 7, 0, 0, 0],
    ]);
    data.setProperty(0, 0, 'style', 'min-width:100px');
    var table = new google.visualization.Table(document.getElementById('geo_table'));
    table.draw(data, {allowHtml: true, sortColumn: 2, sortAscending: false, width: '660px', height: '100%'});
  }
</script>

<span style="font-size: 13px">All COVID-19 data displayed on the page is available through our FREE <a href="https://developer.smartable.ai">API program</a>. This US - Virginia State Coronavirus (COVID-19) Live Stats is refreshed every hour using credible data sources, including the country/state's official government website, <a href="https://en.wikipedia.org/wiki/2019%E2%80%9320_coronavirus_pandemic" target="_blank">data available on wikipedia pages</a>, latest news reports, <a href="https://systems.jhu.edu/research/public-health/ncov/" target="_blank">Johns Hopkins University CSSE 2019-nCoV Dashboard</a>, <a href="https://www.who.int/emergencies/diseases/novel-coronavirus-2019/situation-reports" target="_blank">WHO Situation Reports</a>, <a href="https://www.cdc.gov/coronavirus/2019-ncov/index.html" target="_blank">CDC Situation Updates</a>, and <a href="https://ncov.dxy.cn/ncovh5/view/pneumonia" target="_blank">DXY.cn</a>.</span>

<h2 id="news" class="center" style="margin-top: 60px; font-size: 25px;">Local Government Help Information</h2>
<div class="info center">
<a href="http://www.vdh.virginia.gov/surveillance-and-investigation/novel-coronavirus/" target="_blank">Virginia Department of Health</a>
</div>
<h2 id="news" class="center" style="margin-top: 60px; font-size: 25px;">Trending Coronavirus News in US-Virginia</h2>
<div class="row">
<div class="col-md-6 col-sm-12">
  <div class="content-card">
	<a href="https://www.dailypress.com/news/health/vp-nw-may-9-coronavirus-numbers-20200509-4utdi5dntzhutghwh7rt57mg7e-story.html"><div class="card-image" style="background-image: url(https://www.dailypress.com/resizer/P_GoRahJ00EBJv2HZlOL6Wk9M5I=/1200x0/top/arc-anglerfish-arc2-prod-tronc.s3.amazonaws.com/public/2ZS7YFYMG5BPNNWCI5IYJC6Z6U.jpg)"></div></a>
	<div class="content">
		<div class="card-title"><a href="https://www.dailypress.com/news/health/vp-nw-may-9-coronavirus-numbers-20200509-4utdi5dntzhutghwh7rt57mg7e-story.html">15 more deaths, 854 new coronavirus cases reported in Virginia</a></div>
		<div class="card-excerpt">The state’s latest data shows Accomack County on the Eastern Shore now has the highest number of cases in region with 496, surpassing Virginia Beach, which has 478.</div>
		<div class="card-meta">
			<span class="card-provider">Daily Press</span> • <span class="card-date">5/9/2020</span>
		</div>
	</div>
  </div>
</div>
<div class="col-md-6 col-sm-12">
  <div class="content-card">
	<a href="https://apnews.com/e8e3e00f7017adef8eee9a8a68127a87"><div class="card-image" style="background-image: url(https://storage.googleapis.com/afs-prod/media/989d7cc476ab4e5a83081031e8a2710e/3000.jpeg)"></div></a>
	<div class="content">
		<div class="card-title"><a href="https://apnews.com/e8e3e00f7017adef8eee9a8a68127a87">Virginia defends coronavirus restrictions in church lawsuit</a></div>
		<div class="card-excerpt">An attempt by a Virginia church to prevent the state from barring gatherings of more than 10 people “would seriously undermine” the state's efforts to deter the spread of</div>
		<div class="card-meta">
			<span class="card-provider">Associated Press</span> • <span class="card-date">5/8/2020</span>
		</div>
	</div>
  </div>
</div>
<div class="col-md-6 col-sm-12">
  <div class="content-card">
	<a href="https://www.washingtonpost.com/local/amid-coronavirus-pandemic-fewer-maryland-residents-seek-er-treatment/2020/05/07/acc42a20-9068-11ea-9e23-6914ee410a5f_story.html"><div class="card-image" style="background-image: url(https://www.washingtonpost.com/resizer/u2cCzVmH0dqN2bpZW8A7bZ9yLUg=/1440x0/smart/arc-anglerfish-washpost-prod-washpost.s3.amazonaws.com/public/JNXIRXUQR4I6VEZCUKPHL374SM.jpg)"></div></a>
	<div class="content">
		<div class="card-title"><a href="https://www.washingtonpost.com/local/amid-coronavirus-pandemic-fewer-maryland-residents-seek-er-treatment/2020/05/07/acc42a20-9068-11ea-9e23-6914ee410a5f_story.html">Amid coronavirus pandemic, fewer Maryland, Virginia residents seek ER treatment</a></div>
		<div class="card-excerpt">The Washington Post is providing this important information about the coronavirus for free. For more free coverage of the coronavirus pandemic, sign up for our daily Coronavirus Updates newsletter where all stories are free to read.</div>
		<div class="card-meta">
			<span class="card-provider">Washington Post</span> • <span class="card-date">5/7/2020</span>
		</div>
	</div>
  </div>
</div>
<div class="col-md-6 col-sm-12">
  <div class="content-card">
	<a href="https://www.wavy.com/sports/local-sports/virginia-spring-high-school-sports-officially-canceled-due-to-coronavirus/"><div class="card-image" style="background-image: url(https://www.wavy.com/wp-content/uploads/sites/3/2020/05/thumbnail_Coronavirus-Update-3.png?w=1280&h=720&crop=1)"></div></a>
	<div class="content">
		<div class="card-title"><a href="https://www.wavy.com/sports/local-sports/virginia-spring-high-school-sports-officially-canceled-due-to-coronavirus/">Virginia spring high school sports officially canceled due to coronavirus</a></div>
		<div class="card-excerpt">Any hope of a high school spring sports season was officially squashed Thursday as the Virginia High School Sports League voted at its May meeting to cancel all</div>
		<div class="card-meta">
			<span class="card-provider">WAVY</span> • <span class="card-date">5/7/2020</span>
		</div>
	</div>
  </div>
</div>

</div>

