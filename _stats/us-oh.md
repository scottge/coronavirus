---
category: stats
title: "US - Ohio State Coronavirus (COVID-19) Live Stats"
excerpt: "Live stats of COVID-19 in US-Ohio. Total Cases: 25250 (+463), Deaths: 1436 (+74), Recoveries: 448(-)."
publishedDateTime: 2020-05-12T19:45:10Z
updatedDateTime: 2020-05-12T19:45:10Z
webUrl: "https://smartable.ai/apps/coronavirus/stats/us-oh/"
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
  - url: "https://smartable.azureedge.net/coronavirus/sites/2/2020/us-oh.jpg"
    width: 900
    height: 564
    title: "US - Ohio State Coronavirus (COVID-19) Live Stats"

---
<div class="total-stats" style="text-align: center;">
    <h3>
	    <div style="font-size: 18px; font-weight: 400;">Total Confirmed Cases:</div>
	    25250 (<span class='red'>+463</span>)
    </h3>
    <h3>
	    <div style="font-size: 18px; font-weight: 400;">Total Deaths:</div>
	    1436 (<span class='red'>+74</span>)
    </h3>
    <h3>
	    <div style="font-size: 18px; font-weight: 400;">Total Recovered:</div>
	    448 (-)
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
      ['1/22/2020', 0, 0, 0],['1/23/2020', 0, 0, 0],['1/24/2020', 0, 0, 0],['1/25/2020', 0, 0, 0],['1/26/2020', 0, 0, 0],['1/27/2020', 0, 0, 0],['1/28/2020', 0, 0, 0],['1/29/2020', 0, 0, 0],['1/30/2020', 0, 0, 0],['1/31/2020', 0, 0, 0],['2/1/2020', 0, 0, 0],['2/2/2020', 0, 0, 0],['2/3/2020', 0, 0, 0],['2/4/2020', 0, 0, 0],['2/5/2020', 0, 0, 0],['2/6/2020', 0, 0, 0],['2/7/2020', 0, 0, 0],['2/8/2020', 0, 0, 0],['2/9/2020', 0, 0, 0],['2/10/2020', 0, 0, 0],['2/11/2020', 0, 0, 0],['2/12/2020', 0, 0, 0],['2/13/2020', 0, 0, 0],['2/14/2020', 0, 0, 0],['2/15/2020', 0, 0, 0],['2/16/2020', 0, 0, 0],['2/17/2020', 0, 0, 0],['2/18/2020', 0, 0, 0],['2/19/2020', 0, 0, 0],['2/20/2020', 0, 0, 0],['2/21/2020', 0, 0, 0],['2/22/2020', 0, 0, 0],['2/23/2020', 0, 0, 0],['2/24/2020', 0, 0, 0],['2/25/2020', 0, 0, 0],['2/26/2020', 0, 0, 0],['2/27/2020', 0, 0, 0],['2/28/2020', 0, 0, 0],['2/29/2020', 0, 0, 0],['3/1/2020', 0, 0, 0],['3/2/2020', 0, 0, 0],['3/3/2020', 0, 0, 0],['3/4/2020', 0, 0, 0],['3/5/2020', 0, 0, 0],['3/6/2020', 0, 0, 0],['3/7/2020', 0, 0, 0],['3/8/2020', 0, 0, 0],['3/9/2020', 0, 0, 0],['3/10/2020', 3, 0, 0],['3/11/2020', 4, 0, 0],['3/12/2020', 5, 0, 0],['3/13/2020', 18, 0, 0],['3/14/2020', 38, 0, 0],['3/15/2020', 37, 0, 0],['3/16/2020', 50, 0, 0],['3/17/2020', 67, 0, 0],['3/18/2020', 89, 0, 0],['3/19/2020', 120, 1, 0],['3/20/2020', 174, 3, 0],['3/21/2020', 248, 3, 0],['3/22/2020', 356, 3, 0],['3/23/2020', 443, 6, 0],['3/24/2020', 567, 8, 0],['3/25/2020', 704, 11, 0],['3/26/2020', 870, 15, 0],['3/27/2020', 1139, 19, 0],['3/28/2020', 1406, 25, 0],['3/29/2020', 1653, 29, 0],['3/30/2020', 1933, 40, 0],['3/31/2020', 2199, 55, 0],['4/1/2020', 2547, 65, 0],['4/2/2020', 2902, 81, 0],['4/3/2020', 3312, 91, 0],['4/4/2020', 3739, 102, 0],['4/5/2020', 4043, 119, 0],['4/6/2020', 4453, 142, 0],['4/7/2020', 4782, 167, 0],['4/8/2020', 5148, 193, 0],['4/9/2020', 5512, 213, 0],['4/10/2020', 5878, 231, 12],['4/11/2020', 6250, 247, 12],['4/12/2020', 6604, 253, 12],['4/13/2020', 6975, 274, 12],['4/14/2020', 7285, 324, 305],['4/15/2020', 7794, 362, 367],['4/16/2020', 8414, 391, 367],['4/17/2020', 9107, 418, 448],['4/18/2020', 10218, 451, 448],['4/19/2020', 11595, 471, 448],['4/20/2020', 12919, 509, 448],['4/21/2020', 13725, 557, 448],['4/22/2020', 14117, 610, 448],['4/23/2020', 14694, 656, 448],['4/24/2020', 15173, 693, 448],['4/25/2020', 15590, 712, 448],['4/26/2020', 15974, 732, 448],['4/27/2020', 16349, 759, 448],['4/28/2020', 16781, 804, 448],['4/29/2020', 17309, 940, 448],['4/30/2020', 18032, 981, 448],['5/1/2020', 18670, 996, 448],['5/2/2020', 19345, 1026, 448],['5/3/2020', 19920, 1042, 448],['5/4/2020', 20477, 1060, 448],['5/5/2020', 20972, 1136, 448],['5/6/2020', 21579, 1227, 448],['5/7/2020', 22134, 1276, 448],['5/8/2020', 23020, 1311, 448],['5/9/2020', 23701, 1338, 448],['5/10/2020', 24088, 1347, 448],['5/11/2020', 24787, 1362, 448],['5/12/2020', 25250, 1436, 448],
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
      [40.8307, -84.0846, "Allen", 146, 29],[40.6584, -82.3144, "Ashland", 15, 0],[41.5364, -80.8597, "Ashtabula", 193, 19],[39.4016, -81.9549, "Athens", 6, 1],[40.5558, -84.0796, "Auglaize", 43, 3],[40.0105, -80.8814, "Belmont", 258, 7],[39.0293, -83.9267, "Brown", 17, 1],[39.4791, -84.462, "Butler", 479, 13],[40.555, -81.1992, "Carroll", 24, 1],[40.127, -83.9644, "Champaign", 19, 1],[39.9295, -83.6139, "Clark", 98, 3],[39.2123, -84.3001, "Clermont", 125, 3],[39.5523, -83.7856, "Clinton", 35, 0],[40.8871, -80.6749, "Columbiana", 336, 37],[40.2618, -81.848, "Coshocton", 19, 0],[40.7924, -82.8568, "Crawford", 77, 1],[41.4339, -81.6758, "Cuyahoga", 2861, 147],[40.1157, -84.4966, "Darke", 89, 14],[41.2944, -84.7648, "Defiance", 26, 1],[40.2219, -82.8802, "Delaware", 222, 4],[41.2883, -82.5995, "Erie", 83, 3],[39.6049, -82.8235, "Fairfield", 178, 3],[39.6079, -83.3953, "Fayette", 27, 0],[40.0251, -82.8637, "Franklin", 3881, 124],[41.7113, -83.9057, "Fulton", 31, 0],[38.9776, -82.3374, "Gallia", 6, 1],[41.4318, -81.3351, "Geauga", 191, 19],[39.731, -84.0624, "Greene", 63, 5],[39.1063, -84.3703, "Hamilton", 1823, 101],[40.8995, -83.7271, "Hancock", 39, 1],[39.2123, -83.6113, "Highland", 12, 1],[40.5628, -81.8011, "Holmes", 8, 1],[41.0796, -82.4066, "Huron", 38, 1],[40.2701, -80.6318, "Jefferson", 56, 2],[40.4784, -82.5485, "Knox", 20, 1],[41.6581, -81.4323, "Lake", 199, 8],[38.4375, -82.3818, "Lawrence", 25, 0],[39.95, -82.5985, "Licking", 164, 7],[40.516, -83.8875, "Logan", 23, 0],[41.2665, -82.304, "Lorain", 554, 45],[41.4906, -83.8747, "Lucas", 1806, 165],[39.733, -83.4765, "Madison", 84, 3],[40.9042, -80.9524, "Mahoning", 1144, 123],[40.4598, -83.0848, "Marion", 2404, 14],[41.0349, -82.0123, "Medina", 195, 17],[40.6915, -84.6502, "Mercer", 84, 1],[40.1504, -84.2438, "Miami", 313, 28],[39.8393, -84.4176, "Montgomery", 422, 12],[40.1376, -82.0119, "Muskingum", 27, 0],[41.5094, -82.9383, "Ottawa", 47, 2],[39.5705, -82.9471, "Pickaway", 1933, 23],[39.1256, -82.9836, "Pike", 5, 0],[41.3118, -81.345, "Portage", 280, 46],[39.8564, -84.7922, "Preble", 28, 2],[40.68, -82.5793, "Richland", 121, 2],[39.4647, -82.7456, "Ross", 53, 2],[41.4216, -83.221, "Sandusky", 52, 8],[41.2355, -82.8592, "Seneca", 14, 1],[40.2891, -84.1667, "Shelby", 32, 1],[40.8685, -81.2519, "Stark", 511, 67],[41.1386, -81.4344, "Summit", 915, 78],[41.3421, -80.5277, "Trumbull", 408, 36],[40.2761, -81.5949, "Tuscarawas", 216, 1],[40.3534, -83.2628, "Union", 28, 0],[40.7852, -84.4559, "Van Wert", 3, 0],[39.5022, -83.9984, "Warren", 209, 13],[39.4739, -81.468, "Washington", 114, 17],[40.9764, -81.9, "Wayne", 188, 42],[41.2846, -83.8438, "Wood", 225, 31],[40.9517, -83.1709, "Wyandot", 27, 2],[39.6063, -82.2046, "Perry", 14, 1],[40.5533, -82.8279, "Morrow", 87, 1],[40.1508, -81.5758, "Guernsey", 21, 0],[40.788, -83.643, "Hardin", 28, 0],[41.5026, -84.4183, "Williams", 44, 1],[39.7631, -81.1168, "Monroe", 19, 0],[38.8618, -82.8552, "Scioto", 15, 0],[40.9205, -84.0597, "Putnam", 76, 13],[41.019, -84.4775, "Paulding", 9, 0],[39.5489, -81.7944, "Morgan", 5, 0],[38.9984, -81.9686, "Meigs", 3, 0],[39.1172, -82.5375, "Jackson", 8, 0],[41.4387, -84.2554, "Henry", 9, 0],[39.7888, -81.5565, "Noble", 6, 0],[38.9463, -83.4094, "Adams", 6, 0],[39.4719, -82.7374, "Hocking", 22, 1],[40.3265, -80.8954, "Harrison", 6, 0],[39.2875595, -82.5185837, "Vinton", 12, 0],
    ]);
    var options = {
      backgroundColor: {fill:'transparent',stroke:'#FFF' ,strokeWidth:0 }, 
      displayMode: 'markers',
      region: 'US-OH', 
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
      [{v:"Allen", f:"Allen"}, 146, 0, 117, 29, 0, 0],[{v:"Ashland", f:"Ashland"}, 15, 0, 15, 0, 0, 0],[{v:"Ashtabula", f:"Ashtabula"}, 193, 0, 174, 19, 0, 0],[{v:"Athens", f:"Athens"}, 6, 0, 5, 1, 0, 0],[{v:"Auglaize", f:"Auglaize"}, 43, 0, 40, 3, 0, 0],[{v:"Belmont", f:"Belmont"}, 258, 0, 239, 7, 0, 12],[{v:"Brown", f:"Brown"}, 17, 0, 16, 1, 0, 0],[{v:"Butler", f:"Butler"}, 479, 0, 466, 13, 0, 0],[{v:"Carroll", f:"Carroll"}, 24, 0, 23, 1, 0, 0],[{v:"Champaign", f:"Champaign"}, 19, 0, 18, 1, 0, 0],[{v:"Clark", f:"Clark"}, 98, 0, 95, 3, 0, 0],[{v:"Clermont", f:"Clermont"}, 125, 0, 122, 3, 0, 0],[{v:"Clinton", f:"Clinton"}, 35, 0, 35, 0, 0, 0],[{v:"Columbiana", f:"Columbiana"}, 336, 0, 299, 37, 0, 0],[{v:"Coshocton", f:"Coshocton"}, 19, 0, 10, 0, 0, 9],[{v:"Crawford", f:"Crawford"}, 77, 0, 65, 1, 0, 11],[{v:"Cuyahoga", f:"Cuyahoga"}, 2861, 0, 2490, 147, 0, 224],[{v:"Darke", f:"Darke"}, 89, 0, 75, 14, 0, 0],[{v:"Defiance", f:"Defiance"}, 26, 0, 25, 1, 0, 0],[{v:"Delaware", f:"Delaware"}, 222, 0, 218, 4, 0, 0],[{v:"Erie", f:"Erie"}, 83, 0, 80, 3, 0, 0],[{v:"Fairfield", f:"Fairfield"}, 178, 0, 150, 3, 0, 25],[{v:"Fayette", f:"Fayette"}, 27, 0, 27, 0, 0, 0],[{v:"Franklin", f:"Franklin"}, 3881, 0, 3757, 124, 0, 0],[{v:"Fulton", f:"Fulton"}, 31, 0, 31, 0, 0, 0],[{v:"Gallia", f:"Gallia"}, 6, 0, 5, 1, 0, 0],[{v:"Geauga", f:"Geauga"}, 191, 0, 172, 19, 0, 0],[{v:"Greene", f:"Greene"}, 63, 0, 58, 5, 0, 0],[{v:"Hamilton", f:"Hamilton"}, 1823, 0, 1722, 101, 0, 0],[{v:"Hancock", f:"Hancock"}, 39, 0, 38, 1, 0, 0],[{v:"Highland", f:"Highland"}, 12, 0, 7, 1, 0, 4],[{v:"Holmes", f:"Holmes"}, 8, 0, 7, 1, 0, 0],[{v:"Huron", f:"Huron"}, 38, 0, 29, 1, 0, 8],[{v:"Jefferson", f:"Jefferson"}, 56, 0, 48, 2, 0, 6],[{v:"Knox", f:"Knox"}, 20, 0, 19, 1, 0, 0],[{v:"Lake", f:"Lake"}, 199, 0, 191, 8, 0, 0],[{v:"Lawrence", f:"Lawrence"}, 25, 0, 25, 0, 0, 0],[{v:"Licking", f:"Licking"}, 164, 0, 126, 7, 0, 31],[{v:"Logan", f:"Logan"}, 23, 0, 23, 0, 0, 0],[{v:"Lorain", f:"Lorain"}, 554, 0, 469, 45, 0, 40],[{v:"Lucas", f:"Lucas"}, 1806, 0, 1641, 165, 0, 0],[{v:"Madison", f:"Madison"}, 84, 0, 81, 3, 0, 0],[{v:"Mahoning", f:"Mahoning"}, 1144, 0, 1021, 123, 0, 0],[{v:"Marion", f:"Marion"}, 2404, 0, 2390, 14, 0, 0],[{v:"Medina", f:"Medina"}, 195, 0, 178, 17, 0, 0],[{v:"Mercer", f:"Mercer"}, 84, 0, 79, 1, 0, 4],[{v:"Miami", f:"Miami"}, 313, 0, 285, 28, 0, 0],[{v:"Montgomery", f:"Montgomery"}, 422, 0, 410, 12, 0, 0],[{v:"Muskingum", f:"Muskingum"}, 27, 0, 27, 0, 0, 0],[{v:"Ottawa", f:"Ottawa"}, 47, 0, 45, 2, 0, 0],[{v:"Pickaway", f:"Pickaway"}, 1933, 0, 1892, 23, 0, 18],[{v:"Pike", f:"Pike"}, 5, 0, 5, 0, 0, 0],[{v:"Portage", f:"Portage"}, 280, 0, 234, 46, 0, 0],[{v:"Preble", f:"Preble"}, 28, 0, 26, 2, 0, 0],[{v:"Richland", f:"Richland"}, 121, 0, 105, 2, 0, 14],[{v:"Ross", f:"Ross"}, 53, 0, 51, 2, 0, 0],[{v:"Sandusky", f:"Sandusky"}, 52, 0, 44, 8, 0, 0],[{v:"Seneca", f:"Seneca"}, 14, 0, 8, 1, 0, 5],[{v:"Shelby", f:"Shelby"}, 32, 0, 19, 1, 0, 12],[{v:"Stark", f:"Stark"}, 511, 0, 444, 67, 0, 0],[{v:"Summit", f:"Summit"}, 915, 0, 837, 78, 0, 0],[{v:"Trumbull", f:"Trumbull"}, 408, 0, 372, 36, 0, 0],[{v:"Tuscarawas", f:"Tuscarawas"}, 216, 0, 198, 1, 0, 17],[{v:"Union", f:"Union"}, 28, 0, 28, 0, 0, 0],[{v:"Van Wert", f:"Van Wert"}, 3, 0, 1, 0, 0, 2],[{v:"Warren", f:"Warren"}, 209, 0, 196, 13, 0, 0],[{v:"Washington", f:"Washington"}, 114, 0, 97, 17, 0, 0],[{v:"Wayne", f:"Wayne"}, 188, 0, 146, 42, 0, 0],[{v:"Wood", f:"Wood"}, 225, 0, 194, 31, 0, 0],[{v:"Wyandot", f:"Wyandot"}, 27, 0, 25, 2, 0, 0],[{v:"Perry", f:"Perry"}, 14, 0, 10, 1, 0, 3],[{v:"Morrow", f:"Morrow"}, 87, 0, 86, 1, 0, 0],[{v:"Guernsey", f:"Guernsey"}, 21, 0, 21, 0, 0, 0],[{v:"Hardin", f:"Hardin"}, 28, 0, 28, 0, 0, 0],[{v:"Williams", f:"Williams"}, 44, 0, 43, 1, 0, 0],[{v:"Monroe", f:"Monroe"}, 19, 0, 19, 0, 0, 0],[{v:"Scioto", f:"Scioto"}, 15, 0, 15, 0, 0, 0],[{v:"Putnam", f:"Putnam"}, 76, 0, 63, 13, 0, 0],[{v:"Paulding", f:"Paulding"}, 9, 0, 9, 0, 0, 0],[{v:"Morgan", f:"Morgan"}, 5, 0, 5, 0, 0, 0],[{v:"Meigs", f:"Meigs"}, 3, 0, 3, 0, 0, 0],[{v:"Jackson", f:"Jackson"}, 8, 0, 8, 0, 0, 0],[{v:"Henry", f:"Henry"}, 9, 0, 9, 0, 0, 0],[{v:"Noble", f:"Noble"}, 6, 0, 6, 0, 0, 0],[{v:"Adams", f:"Adams"}, 6, 0, 3, 0, 0, 3],[{v:"Hocking", f:"Hocking"}, 22, 0, 21, 1, 0, 0],[{v:"Harrison", f:"Harrison"}, 6, 0, 6, 0, 0, 0],[{v:"Vinton", f:"Vinton"}, 12, 0, 12, 0, 0, 0],
    ]);
    data.setProperty(0, 0, 'style', 'min-width:100px');
    var table = new google.visualization.Table(document.getElementById('geo_table'));
    table.draw(data, {allowHtml: true, sortColumn: 2, sortAscending: false, width: '660px', height: '100%'});
  }
</script>

<span style="font-size: 13px">All COVID-19 data displayed on the page is available through our FREE <a href="https://developer.smartable.ai">API program</a>. This US - Ohio State Coronavirus (COVID-19) Live Stats is refreshed every hour using credible data sources, including the country/state's official government website, <a href="https://en.wikipedia.org/wiki/2019%E2%80%9320_coronavirus_pandemic" target="_blank">data available on wikipedia pages</a>, latest news reports, <a href="https://systems.jhu.edu/research/public-health/ncov/" target="_blank">Johns Hopkins University CSSE 2019-nCoV Dashboard</a>, <a href="https://www.who.int/emergencies/diseases/novel-coronavirus-2019/situation-reports" target="_blank">WHO Situation Reports</a>, <a href="https://www.cdc.gov/coronavirus/2019-ncov/index.html" target="_blank">CDC Situation Updates</a>, and <a href="https://ncov.dxy.cn/ncovh5/view/pneumonia" target="_blank">DXY.cn</a>.</span>

<h2 id="news" class="center" style="margin-top: 60px; font-size: 25px;">Local Government Help Information</h2>
<div class="info center">
<a href="https://odh.ohio.gov/wps/portal/gov/odh/media-center/ODH-News-Releases/COVID-19-ODH-Call-center" target="_blank">Ohio Department of Health</a> 1-833-4-ASK-ODH
</div>
<h2 id="news" class="center" style="margin-top: 60px; font-size: 25px;">Trending Coronavirus News in US-Ohio</h2>
<div class="row">
<div class="col-md-6 col-sm-12">
  <div class="content-card">
	<a href="https://www.foxnews.com/politics/ohio-prison-reform-system-covid-19"><div class="card-image" style="background-image: url(https://a57.foxnews.com/static.foxnews.com/foxnews.com/content/uploads/2020/05/640/320/Rep.-Diane-Grendell-.jpg?ve=1&tl=1)"></div></a>
	<div class="content">
		<div class="card-title"><a href="https://www.foxnews.com/politics/ohio-prison-reform-system-covid-19">Ohio lawmakers hope for bipartisan reform of prison system stressed by COVID-19</a></div>
		<div class="card-excerpt">Ohio lawmakers, lobbyists and researchers of various political stripes are finding a common cause in prison reform.</div>
		<div class="card-meta">
			<span class="card-provider">Fox News</span> • <span class="card-date">5/8/2020</span>
		</div>
	</div>
  </div>
</div>
<div class="col-md-6 col-sm-12">
  <div class="content-card">
	<a href="https://www.dispatch.com/news/20200508/ohiorsquos-schools-face-another-challenge-during-coronavirus-pandemic-balancing-budget"><div class="card-image" style="background-image: url(https://www.dispatch.com/apps/pbcsi.dll/bilde?Site=OH&Date=20200508&Category=NEWS&ArtNo=200508866&Ref=AR)"></div></a>
	<div class="content">
		<div class="card-title"><a href="https://www.dispatch.com/news/20200508/ohiorsquos-schools-face-another-challenge-during-coronavirus-pandemic-balancing-budget">Ohio’s schools face another challenge during coronavirus pandemic: balancing the budget</a></div>
		<div class="card-excerpt">Though the cuts in state aid Gov. Mike DeWine announced this week — $300 million, or about 4% of overall state funding — are the most-</div>
		<div class="card-meta">
			<span class="card-provider">Columbus Dispatch</span> • <span class="card-date">5/8/2020</span>
		</div>
	</div>
  </div>
</div>
<div class="col-md-6 col-sm-12">
  <div class="content-card">
	<a href="https://www.cleveland.com/metro/2020/05/gov-mike-dewine-on-reopening-ohio-coronavirus-cases-will-increase.html"><div class="card-image" style="background-image: url(https://arc-anglerfish-arc2-prod-advancelocal.s3.amazonaws.com/public/P4R7CCUJ5JD2PIZNMLCNTLL74M.jpg)"></div></a>
	<div class="content">
		<div class="card-title"><a href="https://www.cleveland.com/metro/2020/05/gov-mike-dewine-on-reopening-ohio-coronavirus-cases-will-increase.html">Gov. Mike DeWine on reopening Ohio: Coronavirus cases will increase</a></div>
		<div class="card-excerpt">Gov. Mike DeWine in announcing steps to reopen restaurants, bars and salons urged Ohioans to accept a new normal due to coronavirus.</div>
		<div class="card-meta">
			<span class="card-provider">Cleveland.com</span> • <span class="card-date">5/7/2020</span>
		</div>
	</div>
  </div>
</div>
<div class="col-md-6 col-sm-12">
  <div class="content-card">
	<a href="https://www.foxnews.com/health/ohio-health-officials-hiring-coronavirus-contact-tracers-stop-spread-covid-19"><div class="card-image" style="background-image: url(https://a57.foxnews.com/static.foxnews.com/foxnews.com/content/uploads/2020/05/640/320/iStock-1179336021.jpg?ve=1&tl=1)"></div></a>
	<div class="content">
		<div class="card-title"><a href="https://www.foxnews.com/health/ohio-health-officials-hiring-coronavirus-contact-tracers-stop-spread-covid-19">Ohio health officials hiring coronavirus 'contact tracers' to help stop spread of COVID-19</a></div>
		<div class="card-excerpt">Get the latest news on coronavirus and more delivered daily to your inbox.  Heads up, Ohioans: If you’re in need of a job, the state Department of Health may have one for you. The Ohio Department of Health on Wednesday announced its need for “disease detectives” — or contact tracers — to help stop the spread of the novel coronavirus.</div>
		<div class="card-meta">
			<span class="card-provider">Fox News</span> • <span class="card-date">5/7/2020</span>
		</div>
	</div>
  </div>
</div>

</div>

