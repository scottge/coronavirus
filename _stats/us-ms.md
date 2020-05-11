---
category: stats
title: "US - Mississippi State Coronavirus (COVID-19) Live Stats"
excerpt: "Live stats of COVID-19 in US-Mississippi. Total Cases: 9674 (+153), Deaths: 435 (+4), Recoveries: 4421(-)."
publishedDateTime: 2020-05-11T17:42:25Z
updatedDateTime: 2020-05-11T17:42:25Z
webUrl: "https://smartable.ai/apps/coronavirus/stats/us-ms/"
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
  - url: "https://smartable.azureedge.net/coronavirus/sites/2/2020/us-ms.jpg"
    width: 900
    height: 564
    title: "US - Mississippi State Coronavirus (COVID-19) Live Stats"

---
<div class="total-stats" style="text-align: center;">
    <h3>
	    <div style="font-size: 18px; font-weight: 400;">Total Confirmed Cases:</div>
	    9674 (<span class='red'>+153</span>)
    </h3>
    <h3>
	    <div style="font-size: 18px; font-weight: 400;">Total Deaths:</div>
	    435 (<span class='red'>+4</span>)
    </h3>
    <h3>
	    <div style="font-size: 18px; font-weight: 400;">Total Recovered:</div>
	    4421 (-)
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
      ['1/22/2020', 0, 0, 0],['1/23/2020', 0, 0, 0],['1/24/2020', 0, 0, 0],['1/25/2020', 0, 0, 0],['1/26/2020', 0, 0, 0],['1/27/2020', 0, 0, 0],['1/28/2020', 0, 0, 0],['1/29/2020', 0, 0, 0],['1/30/2020', 0, 0, 0],['1/31/2020', 0, 0, 0],['2/1/2020', 0, 0, 0],['2/2/2020', 0, 0, 0],['2/3/2020', 0, 0, 0],['2/4/2020', 0, 0, 0],['2/5/2020', 0, 0, 0],['2/6/2020', 0, 0, 0],['2/7/2020', 0, 0, 0],['2/8/2020', 0, 0, 0],['2/9/2020', 0, 0, 0],['2/10/2020', 0, 0, 0],['2/11/2020', 0, 0, 0],['2/12/2020', 0, 0, 0],['2/13/2020', 0, 0, 0],['2/14/2020', 0, 0, 0],['2/15/2020', 0, 0, 0],['2/16/2020', 0, 0, 0],['2/17/2020', 0, 0, 0],['2/18/2020', 0, 0, 0],['2/19/2020', 0, 0, 0],['2/20/2020', 0, 0, 0],['2/21/2020', 0, 0, 0],['2/22/2020', 0, 0, 0],['2/23/2020', 0, 0, 0],['2/24/2020', 0, 0, 0],['2/25/2020', 0, 0, 0],['2/26/2020', 0, 0, 0],['2/27/2020', 0, 0, 0],['2/28/2020', 0, 0, 0],['2/29/2020', 0, 0, 0],['3/1/2020', 0, 0, 0],['3/2/2020', 0, 0, 0],['3/3/2020', 0, 0, 0],['3/4/2020', 0, 0, 0],['3/5/2020', 0, 0, 0],['3/6/2020', 0, 0, 0],['3/7/2020', 0, 0, 0],['3/8/2020', 0, 0, 0],['3/9/2020', 0, 0, 0],['3/10/2020', 0, 0, 0],['3/11/2020', 0, 0, 0],['3/12/2020', 1, 0, 0],['3/13/2020', 8, 0, 0],['3/14/2020', 8, 0, 0],['3/15/2020', 10, 0, 0],['3/16/2020', 16, 0, 0],['3/17/2020', 25, 0, 0],['3/18/2020', 34, 0, 0],['3/19/2020', 52, 1, 0],['3/20/2020', 80, 1, 0],['3/21/2020', 140, 1, 0],['3/22/2020', 207, 1, 0],['3/23/2020', 249, 1, 0],['3/24/2020', 320, 1, 0],['3/25/2020', 377, 5, 0],['3/26/2020', 485, 6, 0],['3/27/2020', 579, 8, 0],['3/28/2020', 663, 13, 0],['3/29/2020', 759, 14, 0],['3/30/2020', 847, 16, 0],['3/31/2020', 937, 20, 0],['4/1/2020', 1073, 22, 0],['4/2/2020', 1177, 26, 0],['4/3/2020', 1358, 29, 0],['4/4/2020', 1455, 35, 0],['4/5/2020', 1638, 43, 0],['4/6/2020', 1738, 51, 0],['4/7/2020', 1915, 60, 0],['4/8/2020', 2003, 67, 0],['4/9/2020', 2260, 76, 0],['4/10/2020', 2469, 82, 0],['4/11/2020', 2642, 93, 0],['4/12/2020', 2781, 96, 0],['4/13/2020', 2942, 98, 0],['4/14/2020', 3087, 111, 0],['4/15/2020', 3360, 122, 0],['4/16/2020', 3624, 129, 0],['4/17/2020', 3793, 140, 0],['4/18/2020', 3974, 152, 0],['4/19/2020', 4274, 159, 0],['4/20/2020', 4512, 169, 0],['4/21/2020', 4716, 183, 0],['4/22/2020', 4894, 193, 0],['4/23/2020', 5153, 201, 0],['4/24/2020', 5437, 210, 0],['4/25/2020', 5723, 221, 0],['4/26/2020', 5919, 228, 0],['4/27/2020', 6100, 231, 0],['4/28/2020', 6347, 241, 0],['4/29/2020', 6574, 252, 0],['4/30/2020', 6828, 263, 3413],['5/1/2020', 7120, 272, 3413],['5/2/2020', 7448, 293, 3413],['5/3/2020', 7557, 303, 3413],['5/4/2020', 7878, 312, 3413],['5/5/2020', 8208, 342, 3413],['5/6/2020', 8441, 374, 4421],['5/7/2020', 8704, 398, 4421],['5/8/2020', 9108, 410, 4421],['5/9/2020', 9391, 424, 4421],['5/10/2020', 9521, 431, 4421],['5/11/2020', 9674, 435, 4421],
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
      [31.496, -91.4152, "Adams", 159, 12],[34.9224, -88.4432, "Alcorn", 10, 1],[31.1611, -90.8006, "Amite", 38, 1],[33.122, -89.465, "Attala", 191, 4],[34.8239, -89.2385, "Benton", 13, 0],[34.09, -90.7206, "Bolivar", 119, 9],[33.9909, -89.3454, "Calhoun", 58, 4],[33.5186, -89.9193, "Carroll", 111, 4],[34.0053, -88.7479, "Chickasaw", 92, 10],[33.2931, -89.3993, "Choctaw", 16, 2],[31.8804, -91.1407, "Claiborne", 41, 0],[32.0441, -88.8844, "Clarke", 81, 8],[33.6064, -88.6571, "Clay", 66, 3],[34.3222, -90.4542, "Coahoma", 71, 3],[31.9903, -90.354, "Copiah", 162, 2],[31.5581, -89.4987, "Covington", 90, 1],[34.85, -89.9921, "DeSoto", 333, 5],[31.3074, -89.317, "Forrest", 314, 21],[31.4721, -90.8929, "Franklin", 19, 1],[30.9312, -88.5959, "George", 15, 1],[33.7816, -89.813, "Grenada", 51, 2],[30.3791, -89.3707, "Hancock", 74, 10],[30.4422, -88.9512, "Harrison", 198, 6],[32.3163, -90.2124, "Hinds", 670, 15],[33.323, -90.2355, "Holmes", 213, 19],[33.0952, -90.4967, "Humphreys", 30, 4],[34.2327, -88.2507, "Itawamba", 68, 6],[30.5905, -88.4846, "Jackson", 275, 11],[31.7123, -91.062, "Jefferson", 30, 0],[31.7879, -89.0362, "Jones", 247, 5],[32.8302, -88.4771, "Kemper", 92, 6],[34.5034, -89.5025, "Lafayette", 98, 3],[31.3114, -89.374, "Lamar", 152, 4],[32.5104, -88.5264, "Lauderdale", 482, 43],[31.6048, -90.0023, "Lawrence", 66, 0],[32.6749, -89.4529, "Leake", 299, 3],[34.2649, -88.5768, "Lee", 78, 5],[33.5173, -90.3444, "Leflore", 185, 18],[31.5803, -90.4432, "Lincoln", 186, 14],[33.6276, -88.4454, "Lowndes", 83, 3],[32.5434, -90.3142, "Madison", 431, 12],[31.2386, -89.8829, "Marion", 83, 7],[34.6492, -89.3065, "Marshall", 55, 2],[33.746, -88.4095, "Monroe", 200, 21],[33.4404, -89.5673, "Montgomery", 69, 1],[32.7889, -89.2384, "Neshoba", 315, 14],[32.5711, -89.1152, "Newton", 138, 1],[33.2367, -88.5781, "Noxubee", 102, 2],[33.3451, -89.0458, "Oktibbeha", 89, 4],[34.2409, -89.9433, "Panola", 43, 2],[30.574, -89.6419, "Pearl River", 190, 24],[31.2036, -89.0272, "Perry", 34, 1],[31.0072, -90.4719, "Pike", 168, 10],[34.3611, -88.8388, "Pontotoc", 24, 2],[34.708, -88.662, "Prentiss", 36, 2],[34.2006, -90.2845, "Quitman", 17, 0],[32.2778, -89.9896, "Rankin", 250, 6],[32.4491, -89.4889, "Scott", 457, 6],[32.9719, -90.8284, "Sharkey", 5, 0],[31.873, -89.734, "Simpson", 61, 0],[32.0144, -89.3818, "Smith", 100, 6],[33.8101, -90.5304, "Sunflower", 63, 3],[34.0075, -90.0552, "Tallahatchie", 12, 1],[34.6902, -89.9757, "Tate", 50, 0],[34.638, -88.8431, "Tippah", 65, 11],[34.7032, -90.3796, "Tunica", 39, 2],[34.4909, -89.0201, "Union", 48, 3],[31.1173, -90.1444, "Walthall", 39, 0],[32.3173, -90.8868, "Warren", 117, 2],[33.385, -91.0514, "Washington", 82, 3],[33.539, -89.1278, "Webster", 22, 1],[31.087, -91.0654, "Wilkinson", 77, 9],[33.1224, -89.0553, "Winston", 63, 0],[33.9765, -89.6845, "Yalobusha", 31, 0],[32.672, -90.5445, "Yazoo", 164, 2],[34.4866, -88.1863, "Tishomingo", 10, 0],[32.0722, -89.2626, "Jasper", 86, 2],[31.6773, -88.6353, "Wayne", 27, 0],[30.8557, -89.1385, "Stone", 24, 0],[31.1037, -88.8239, "Greene", 6, 1],[31.4961, -89.745, "Jefferson Davis", 53, 1],
    ]);
    var options = {
      backgroundColor: {fill:'transparent',stroke:'#FFF' ,strokeWidth:0 }, 
      displayMode: 'markers',
      region: 'US-MS', 
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
      [{v:"Adams", f:"Adams"}, 159, 0, 147, 12, 0, 0],[{v:"Alcorn", f:"Alcorn"}, 10, 0, 9, 1, 0, 0],[{v:"Amite", f:"Amite"}, 38, 0, 37, 1, 0, 0],[{v:"Attala", f:"Attala"}, 191, 0, 187, 4, 0, 0],[{v:"Benton", f:"Benton"}, 13, 0, 13, 0, 0, 0],[{v:"Bolivar", f:"Bolivar"}, 119, 0, 110, 9, 1, 0],[{v:"Calhoun", f:"Calhoun"}, 58, 0, 54, 4, 0, 0],[{v:"Carroll", f:"Carroll"}, 111, 0, 107, 4, 0, 0],[{v:"Chickasaw", f:"Chickasaw"}, 92, 0, 82, 10, 0, 0],[{v:"Choctaw", f:"Choctaw"}, 16, 0, 14, 2, 0, 0],[{v:"Claiborne", f:"Claiborne"}, 41, 0, 41, 0, 0, 0],[{v:"Clarke", f:"Clarke"}, 81, 0, 73, 8, 0, 0],[{v:"Clay", f:"Clay"}, 66, 0, 63, 3, 0, 0],[{v:"Coahoma", f:"Coahoma"}, 71, 0, 68, 3, 0, 0],[{v:"Copiah", f:"Copiah"}, 162, 0, 160, 2, 0, 0],[{v:"Covington", f:"Covington"}, 90, 0, 89, 1, 0, 0],[{v:"DeSoto", f:"DeSoto"}, 333, 0, 328, 5, 0, 0],[{v:"Forrest", f:"Forrest"}, 314, 0, 293, 21, 0, 0],[{v:"Franklin", f:"Franklin"}, 19, 0, 18, 1, 0, 0],[{v:"George", f:"George"}, 15, 0, 14, 1, 0, 0],[{v:"Grenada", f:"Grenada"}, 51, 0, 49, 2, 0, 0],[{v:"Hancock", f:"Hancock"}, 74, 0, 64, 10, 0, 0],[{v:"Harrison", f:"Harrison"}, 198, 0, 192, 6, 0, 0],[{v:"Hinds", f:"Hinds"}, 670, 0, 655, 15, 0, 0],[{v:"Holmes", f:"Holmes"}, 213, 0, 194, 19, 0, 0],[{v:"Humphreys", f:"Humphreys"}, 30, 0, 26, 4, 0, 0],[{v:"Itawamba", f:"Itawamba"}, 68, 0, 62, 6, 0, 0],[{v:"Jackson", f:"Jackson"}, 275, 0, 264, 11, 0, 0],[{v:"Jefferson", f:"Jefferson"}, 30, 0, 30, 0, 0, 0],[{v:"Jones", f:"Jones"}, 247, 0, 242, 5, 0, 0],[{v:"Kemper", f:"Kemper"}, 92, 0, 86, 6, 0, 0],[{v:"Lafayette", f:"Lafayette"}, 98, 0, 95, 3, 0, 0],[{v:"Lamar", f:"Lamar"}, 152, 0, 148, 4, 0, 0],[{v:"Lauderdale", f:"Lauderdale"}, 482, 0, 439, 43, 0, 0],[{v:"Lawrence", f:"Lawrence"}, 66, 0, 66, 0, 0, 0],[{v:"Leake", f:"Leake"}, 299, 0, 296, 3, 0, 0],[{v:"Lee", f:"Lee"}, 78, 0, 73, 5, 0, 0],[{v:"Leflore", f:"Leflore"}, 185, 0, 167, 18, 0, 0],[{v:"Lincoln", f:"Lincoln"}, 186, 0, 172, 14, 0, 0],[{v:"Lowndes", f:"Lowndes"}, 83, 0, 80, 3, 0, 0],[{v:"Madison", f:"Madison"}, 431, 0, 419, 12, 0, 0],[{v:"Marion", f:"Marion"}, 83, 0, 76, 7, 0, 0],[{v:"Marshall", f:"Marshall"}, 55, 0, 53, 2, 0, 0],[{v:"Monroe", f:"Monroe"}, 200, 0, 179, 21, 1, 0],[{v:"Montgomery", f:"Montgomery"}, 69, 0, 68, 1, 0, 0],[{v:"Neshoba", f:"Neshoba"}, 315, 0, 301, 14, 0, 0],[{v:"Newton", f:"Newton"}, 138, 0, 137, 1, 0, 0],[{v:"Noxubee", f:"Noxubee"}, 102, 0, 100, 2, 0, 0],[{v:"Oktibbeha", f:"Oktibbeha"}, 89, 0, 85, 4, 0, 0],[{v:"Panola", f:"Panola"}, 43, 0, 41, 2, 0, 0],[{v:"Pearl River", f:"Pearl River"}, 190, 0, 166, 24, 0, 0],[{v:"Perry", f:"Perry"}, 34, 0, 33, 1, 0, 0],[{v:"Pike", f:"Pike"}, 168, 0, 158, 10, 0, 0],[{v:"Pontotoc", f:"Pontotoc"}, 24, 0, 22, 2, 0, 0],[{v:"Prentiss", f:"Prentiss"}, 36, 0, 34, 2, 0, 0],[{v:"Quitman", f:"Quitman"}, 17, 0, 17, 0, 0, 0],[{v:"Rankin", f:"Rankin"}, 250, 0, 244, 6, 0, 0],[{v:"Scott", f:"Scott"}, 457, 0, 451, 6, 0, 0],[{v:"Sharkey", f:"Sharkey"}, 5, 0, 5, 0, 0, 0],[{v:"Simpson", f:"Simpson"}, 61, 0, 61, 0, 0, 0],[{v:"Smith", f:"Smith"}, 100, 0, 94, 6, 0, 0],[{v:"Sunflower", f:"Sunflower"}, 63, 0, 60, 3, 0, 0],[{v:"Tallahatchie", f:"Tallahatchie"}, 12, 0, 11, 1, 0, 0],[{v:"Tate", f:"Tate"}, 50, 0, 50, 0, 0, 0],[{v:"Tippah", f:"Tippah"}, 65, 0, 54, 11, 0, 0],[{v:"Tunica", f:"Tunica"}, 39, 0, 37, 2, 0, 0],[{v:"Union", f:"Union"}, 48, 0, 45, 3, 0, 0],[{v:"Walthall", f:"Walthall"}, 39, 0, 39, 0, 0, 0],[{v:"Warren", f:"Warren"}, 117, 0, 115, 2, 0, 0],[{v:"Washington", f:"Washington"}, 82, 0, 79, 3, 0, 0],[{v:"Webster", f:"Webster"}, 22, 0, 21, 1, 0, 0],[{v:"Wilkinson", f:"Wilkinson"}, 77, 0, 68, 9, 0, 0],[{v:"Winston", f:"Winston"}, 63, 0, 63, 0, 0, 0],[{v:"Yalobusha", f:"Yalobusha"}, 31, 0, 31, 0, 0, 0],[{v:"Yazoo", f:"Yazoo"}, 164, 0, 162, 2, 0, 0],[{v:"Tishomingo", f:"Tishomingo"}, 10, 0, 10, 0, 0, 0],[{v:"Jasper", f:"Jasper"}, 86, 0, 84, 2, 0, 0],[{v:"Wayne", f:"Wayne"}, 27, 0, 27, 0, 0, 0],[{v:"Stone", f:"Stone"}, 24, 0, 24, 0, 0, 0],[{v:"Greene", f:"Greene"}, 6, 0, 5, 1, 0, 0],[{v:"Jefferson Davis", f:"Jefferson Davis"}, 53, 0, 52, 1, 0, 0],
    ]);
    data.setProperty(0, 0, 'style', 'min-width:100px');
    var table = new google.visualization.Table(document.getElementById('geo_table'));
    table.draw(data, {allowHtml: true, sortColumn: 2, sortAscending: false, width: '660px', height: '100%'});
  }
</script>

<span style="font-size: 13px">All COVID-19 data displayed on the page is available through our FREE <a href="https://developer.smartable.ai">API program</a>. This US - Mississippi State Coronavirus (COVID-19) Live Stats is refreshed every hour using credible data sources, including the country/state's official government website, <a href="https://en.wikipedia.org/wiki/2019%E2%80%9320_coronavirus_pandemic" target="_blank">data available on wikipedia pages</a>, latest news reports, <a href="https://systems.jhu.edu/research/public-health/ncov/" target="_blank">Johns Hopkins University CSSE 2019-nCoV Dashboard</a>, <a href="https://www.who.int/emergencies/diseases/novel-coronavirus-2019/situation-reports" target="_blank">WHO Situation Reports</a>, <a href="https://www.cdc.gov/coronavirus/2019-ncov/index.html" target="_blank">CDC Situation Updates</a>, and <a href="https://ncov.dxy.cn/ncovh5/view/pneumonia" target="_blank">DXY.cn</a>.</span>

<h2 id="news" class="center" style="margin-top: 60px; font-size: 25px;">Local Government Help Information</h2>
<div class="info center">
<a href="https://msdh.ms.gov/msdhsite/_static/14,0,420.html" target="_blank">Mississippi State Department of Health</a> 877-978-6453
</div>
<h2 id="news" class="center" style="margin-top: 60px; font-size: 25px;">Trending Coronavirus News in US-Mississippi</h2>
<div class="row">
<div class="col-md-6 col-sm-12">
  <div class="content-card">
	<a href="https://apnews.com/e7596d17d4022040794903fb2d7461a4"><div class="card-image" style="background-image: url(https://storage.googleapis.com/afs-prod/media/ab8aecc8b6224d7eaa71153da080b954/3000.jpeg)"></div></a>
	<div class="content">
		<div class="card-title"><a href="https://apnews.com/e7596d17d4022040794903fb2d7461a4">Mississippi: At least 9,378 cases of COVID-19, 421 deaths</a></div>
		<div class="card-excerpt">The state of Mississippi reported 288 new cases of COVID-19 on Saturday, bringing the total to at least 9,378. The state’s death toll from the virus rose to 421,</div>
		<div class="card-meta">
			<span class="card-provider">Associated Press</span> • <span class="card-date">5/9/2020</span>
		</div>
	</div>
  </div>
</div>
<div class="col-md-6 col-sm-12">
  <div class="content-card">
	<a href="https://www.wjtv.com/health/coronavirus/262-new-coronavirus-cases-in-mississippi-8696-total-cases-with-396-deaths/"><div class="card-image" style="background-image: url(https://www.wjtv.com/wp-content/uploads/sites/72/2020/04/thumbnail_Coronavirus-Update-1-2-2-2-3-2-1-5-1.jpg?w=1280&h=720&crop=1)"></div></a>
	<div class="content">
		<div class="card-title"><a href="https://www.wjtv.com/health/coronavirus/262-new-coronavirus-cases-in-mississippi-8696-total-cases-with-396-deaths/">262 new coronavirus cases in Mississippi; 8,696 total cases with 396 deaths</a></div>
		<div class="card-excerpt">The Mississippi State Department of Health is reporting 262 new cases of the coronavirus (COVID-19) in Mississippi. That brings the state’s total number of</div>
		<div class="card-meta">
			<span class="card-provider">WJTV</span> • <span class="card-date">5/7/2020</span>
		</div>
	</div>
  </div>
</div>

</div>

