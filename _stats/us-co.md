---
category: stats
title: "US - Colorado State Coronavirus (COVID-19) Live Stats"
excerpt: "Live stats of COVID-19 in US-Colorado. Total Cases: 19879 (-), Deaths: 987 (-), Recoveries: 612(-)."
publishedDateTime: 2020-05-12T12:45:10Z
updatedDateTime: 2020-05-12T12:45:10Z
webUrl: "https://smartable.ai/apps/coronavirus/stats/us-co/"
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
  - url: "https://smartable.azureedge.net/coronavirus/sites/2/2020/us-co.jpg"
    width: 900
    height: 564
    title: "US - Colorado State Coronavirus (COVID-19) Live Stats"

---
<div class="total-stats" style="text-align: center;">
    <h3>
	    <div style="font-size: 18px; font-weight: 400;">Total Confirmed Cases:</div>
	    19879 (-)
    </h3>
    <h3>
	    <div style="font-size: 18px; font-weight: 400;">Total Deaths:</div>
	    987 (-)
    </h3>
    <h3>
	    <div style="font-size: 18px; font-weight: 400;">Total Recovered:</div>
	    612 (-)
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
      ['1/22/2020', 0, 0, 0],['1/23/2020', 0, 0, 0],['1/24/2020', 0, 0, 0],['1/25/2020', 0, 0, 0],['1/26/2020', 0, 0, 0],['1/27/2020', 0, 0, 0],['1/28/2020', 0, 0, 0],['1/29/2020', 0, 0, 0],['1/30/2020', 0, 0, 0],['1/31/2020', 0, 0, 0],['2/1/2020', 0, 0, 0],['2/2/2020', 0, 0, 0],['2/3/2020', 0, 0, 0],['2/4/2020', 0, 0, 0],['2/5/2020', 0, 0, 0],['2/6/2020', 0, 0, 0],['2/7/2020', 0, 0, 0],['2/8/2020', 0, 0, 0],['2/9/2020', 0, 0, 0],['2/10/2020', 0, 0, 0],['2/11/2020', 0, 0, 0],['2/12/2020', 0, 0, 0],['2/13/2020', 0, 0, 0],['2/14/2020', 0, 0, 0],['2/15/2020', 0, 0, 0],['2/16/2020', 0, 0, 0],['2/17/2020', 0, 0, 0],['2/18/2020', 0, 0, 0],['2/19/2020', 0, 0, 0],['2/20/2020', 0, 0, 0],['2/21/2020', 0, 0, 0],['2/22/2020', 0, 0, 0],['2/23/2020', 0, 0, 0],['2/24/2020', 0, 0, 0],['2/25/2020', 0, 0, 0],['2/26/2020', 0, 0, 0],['2/27/2020', 0, 0, 0],['2/28/2020', 0, 0, 0],['2/29/2020', 0, 0, 0],['3/1/2020', 0, 0, 0],['3/2/2020', 0, 0, 0],['3/3/2020', 0, 0, 0],['3/4/2020', 0, 0, 0],['3/5/2020', 0, 0, 0],['3/6/2020', 3, 0, 0],['3/7/2020', 7, 0, 0],['3/8/2020', 7, 0, 0],['3/9/2020', 7, 0, 0],['3/10/2020', 14, 0, 0],['3/11/2020', 27, 0, 0],['3/12/2020', 50, 0, 0],['3/13/2020', 76, 1, 0],['3/14/2020', 100, 1, 0],['3/15/2020', 133, 1, 0],['3/16/2020', 133, 1, 0],['3/17/2020', 185, 2, 0],['3/18/2020', 221, 2, 0],['3/19/2020', 277, 4, 0],['3/20/2020', 363, 4, 0],['3/21/2020', 476, 6, 0],['3/22/2020', 595, 7, 0],['3/23/2020', 723, 7, 0],['3/24/2020', 912, 11, 0],['3/25/2020', 1087, 20, 0],['3/26/2020', 1430, 19, 0],['3/27/2020', 1740, 31, 0],['3/28/2020', 2063, 44, 0],['3/29/2020', 2308, 47, 0],['3/30/2020', 2627, 51, 0],['3/31/2020', 2968, 69, 0],['4/1/2020', 3330, 80, 0],['4/2/2020', 3728, 97, 0],['4/3/2020', 4173, 111, 0],['4/4/2020', 4565, 126, 0],['4/5/2020', 4950, 140, 0],['4/6/2020', 5183, 150, 0],['4/7/2020', 5429, 179, 0],['4/8/2020', 5655, 193, 0],['4/9/2020', 6202, 226, 0],['4/10/2020', 6513, 250, 0],['4/11/2020', 6893, 274, 108],['4/12/2020', 7307, 289, 112],['4/13/2020', 7696, 306, 116],['4/14/2020', 7954, 327, 498],['4/15/2020', 8284, 354, 510],['4/16/2020', 8679, 372, 510],['4/17/2020', 9051, 389, 510],['4/18/2020', 9444, 411, 529],['4/19/2020', 9734, 420, 559],['4/20/2020', 10116, 447, 559],['4/21/2020', 10460, 484, 559],['4/22/2020', 10891, 506, 559],['4/23/2020', 11274, 550, 559],['4/24/2020', 12082, 550, 559],['4/25/2020', 12968, 680, 559],['4/26/2020', 13441, 684, 559],['4/27/2020', 13879, 708, 559],['4/28/2020', 14316, 737, 559],['4/29/2020', 14758, 767, 559],['4/30/2020', 15284, 777, 559],['5/1/2020', 15748, 800, 559],['5/2/2020', 16225, 832, 559],['5/3/2020', 16635, 842, 559],['5/4/2020', 16936, 854, 559],['5/5/2020', 17364, 903, 559],['5/6/2020', 17830, 921, 559],['5/7/2020', 18371, 944, 559],['5/8/2020', 18827, 960, 559],['5/9/2020', 19375, 967, 559],['5/10/2020', 19703, 971, 559],['5/11/2020', 19879, 987, 612],['5/12/2020', 19879, 987, 612],
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
      [39.7392, -104.9903, "Denver", 4118, 212],[39.7084, -104.7274, "Adams", 2278, 81],[39.6203, -104.3326, "Arapahoe", 3313, 179],[37.4767, -105.8396, "Alamosa", 32, 2],[40.8691, -104.2259, "Weld", 2159, 114],[37.3861, -102.2801, "Baca", 12, 0],[39.58, -105.2663, "Jefferson", 1658, 94],[40.0726, -105.5136, "Boulder", 777, 55],[38.9108, -104.4723, "El Paso", 1137, 79],[39.9541, -105.0527, "Broomfield", 200, 17],[39.6553, -106.8287, "Eagle", 559, 8],[38.5524, -106.0085, "Chaffee", 68, 16],[39.7241, -105.4306, "Clear Creek", 14, 1],[39.2587, -104.9389, "Douglas", 604, 29],[37.2086, -105.5667, "Costilla", 3, 0],[40.6956, -105.5943, "Larimer", 452, 19],[38.2209, -103.7567, "Crowley", 39, 1],[40.3134, -103.8023, "Morgan", 517, 22],[38.7053, -107.61, "Delta", 55, 1],[40.6818, -102.8395, "Logan", 432, 2],[38.5458, -106.9253, "Gunnison", 173, 6],[38.2351, -104.3434, "Pueblo", 185, 12],[39.2189, -104.5403, "Elbert", 39, 1],[39.5912, -106.064, "Summit", 169, 1],[38.362, -105.1417, "Fremont", 23, 0],[38.6084, -107.9827, "Montrose", 127, 11],[39.4667, -107.2599, "Garfield", 104, 2],[40.0565, -106.3782, "Grand", 5, 0],[37.0749, -107.5933, "La Plata", 65, 1],[38.0836, -107.0306, "Hinsdale", 3, 0],[38.6092, 106.5167, "Pitkin", 65, 3],[37.6307, -104.7818, "Huerfano", 3, 0],[40.2738, -106.9574, "Routt", 58, 6],[39.0877, -108.5673, "Mesa", 51, 0],[39.3038, -102.4234, "Kit Carson", 26, 2],[38.945, -105.1619, "Teller", 31, 2],[39.1361, -103.4735, "Lincoln", 4, 0],[38.1286, -108.2918, "San Miguel", 20, 0],[37.8488, -106.9252, "Mineral", 2, 0],[39.2467, -106.2935, "Lake", 23, 0],[40.5191, -108.0889, "Moffat", 6, 0],[37.5017, -108.66, "Montezuma", 24, 3],[38.0014, -103.5549, "Otero", 10, 1],[37.2675, -107.0301, "Archuleta", 8, 0],[38.7591, -105.5024, "Park", 16, 0],[37.6877, -106.586, "Rio Grande", 8, 0],[40.1644, -103.2206, "Washington", 9, 0],[39.7029, -102.2938, "Yuma", 11, 0],[38.0276, -107.6734, "Ouray", 6, 1],[40.6831, -102.1725, "Phillips", 9, 0],[37.1225, -104.7396, "Las Animas", 4, 0],[38.0862, -106.1407, "Saguache", 5, 0],[38.134, -105.4654, "Custer", 2, 0],[40.0498, -107.8953, "Rio Blanco", 1, 0],[39.7963, -105.5151, "Gilpin", 3, 0],[38.074, -102.6155, "Prowers", 9, 0],[37.7573704, -107.71625, "San Juan", 1, 0],[38.8002562, -102.6216211, "Cheyenne", 5, 0],[37.2689711, -106.2522143, "Conejos", 1, 0],[38.0036339, -103.0817903, "Bent", 1, 0],
    ]);
    var options = {
      backgroundColor: {fill:'transparent',stroke:'#FFF' ,strokeWidth:0 }, 
      displayMode: 'markers',
      region: 'US-CO', 
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
      [{v:"Denver", f:"Denver"}, 4118, 0, 3536, 212, 0, 370],[{v:"Adams", f:"Adams"}, 2278, 0, 2197, 81, 0, 0],[{v:"Arapahoe", f:"Arapahoe"}, 3313, 0, 3134, 179, 0, 0],[{v:"Alamosa", f:"Alamosa"}, 32, 0, 30, 2, 0, 0],[{v:"Weld", f:"Weld"}, 2159, 0, 2045, 114, 0, 0],[{v:"Baca", f:"Baca"}, 12, 0, 12, 0, 0, 0],[{v:"Jefferson", f:"Jefferson"}, 1658, 0, 1564, 94, 0, 0],[{v:"Boulder", f:"Boulder"}, 777, 0, 565, 55, 0, 157],[{v:"El Paso", f:"El Paso"}, 1137, 0, 1058, 79, 0, 0],[{v:"Broomfield", f:"Broomfield"}, 200, 0, 183, 17, 0, 0],[{v:"Eagle", f:"Eagle"}, 559, 0, 551, 8, 0, 0],[{v:"Chaffee", f:"Chaffee"}, 68, 0, 52, 16, 0, 0],[{v:"Clear Creek", f:"Clear Creek"}, 14, 0, 13, 1, 0, 0],[{v:"Douglas", f:"Douglas"}, 604, 0, 575, 29, 0, 0],[{v:"Costilla", f:"Costilla"}, 3, 0, 3, 0, 0, 0],[{v:"Larimer", f:"Larimer"}, 452, 0, 433, 19, 0, 0],[{v:"Crowley", f:"Crowley"}, 39, 0, 38, 1, 0, 0],[{v:"Morgan", f:"Morgan"}, 517, 0, 495, 22, 0, 0],[{v:"Delta", f:"Delta"}, 55, 0, 54, 1, 0, 0],[{v:"Logan", f:"Logan"}, 432, 0, 430, 2, 0, 0],[{v:"Gunnison", f:"Gunnison"}, 173, 0, 167, 6, 0, 0],[{v:"Pueblo", f:"Pueblo"}, 185, 0, 173, 12, 0, 0],[{v:"Elbert", f:"Elbert"}, 39, 0, 38, 1, 0, 0],[{v:"Summit", f:"Summit"}, 169, 0, 168, 1, 0, 0],[{v:"Fremont", f:"Fremont"}, 23, 0, 23, 0, 0, 0],[{v:"Montrose", f:"Montrose"}, 127, 0, 116, 11, 0, 0],[{v:"Garfield", f:"Garfield"}, 104, 0, 102, 2, 0, 0],[{v:"Grand", f:"Grand"}, 5, 0, 5, 0, 0, 0],[{v:"La Plata", f:"La Plata"}, 65, 0, 64, 1, 0, 0],[{v:"Hinsdale", f:"Hinsdale"}, 3, 0, 3, 0, 0, 0],[{v:"Pitkin", f:"Pitkin"}, 65, 0, 62, 3, 0, 0],[{v:"Huerfano", f:"Huerfano"}, 3, 0, 3, 0, 0, 0],[{v:"Routt", f:"Routt"}, 58, 0, 52, 6, 0, 0],[{v:"Mesa", f:"Mesa"}, 51, 0, 19, 0, 0, 32],[{v:"Kit Carson", f:"Kit Carson"}, 26, 0, 24, 2, 0, 0],[{v:"Teller", f:"Teller"}, 31, 0, 29, 2, 0, 0],[{v:"Lincoln", f:"Lincoln"}, 4, 0, 4, 0, 0, 0],[{v:"San Miguel", f:"San Miguel"}, 20, 0, 20, 0, 0, 0],[{v:"Mineral", f:"Mineral"}, 2, 0, 2, 0, 0, 0],[{v:"Lake", f:"Lake"}, 23, 0, 23, 0, 0, 0],[{v:"Moffat", f:"Moffat"}, 6, 0, 6, 0, 0, 0],[{v:"Montezuma", f:"Montezuma"}, 24, 0, 21, 3, 0, 0],[{v:"Otero", f:"Otero"}, 10, 0, 9, 1, 0, 0],[{v:"Archuleta", f:"Archuleta"}, 8, 0, 8, 0, 0, 0],[{v:"Park", f:"Park"}, 16, 0, 16, 0, 0, 0],[{v:"Rio Grande", f:"Rio Grande"}, 8, 0, 8, 0, 0, 0],[{v:"Washington", f:"Washington"}, 9, 0, 9, 0, 0, 0],[{v:"Yuma", f:"Yuma"}, 11, 0, 11, 0, 0, 0],[{v:"Ouray", f:"Ouray"}, 6, 0, 5, 1, 0, 0],[{v:"Phillips", f:"Phillips"}, 9, 0, 9, 0, 0, 0],[{v:"Las Animas", f:"Las Animas"}, 4, 0, 4, 0, 0, 0],[{v:"Saguache", f:"Saguache"}, 5, 0, 5, 0, 0, 0],[{v:"Custer", f:"Custer"}, 2, 0, 2, 0, 0, 0],[{v:"Rio Blanco", f:"Rio Blanco"}, 1, 0, 1, 0, 0, 0],[{v:"Gilpin", f:"Gilpin"}, 3, 0, 3, 0, 0, 0],[{v:"Prowers", f:"Prowers"}, 9, 0, 9, 0, 0, 0],[{v:"San Juan", f:"San Juan"}, 1, 0, 1, 0, 0, 0],[{v:"Cheyenne", f:"Cheyenne"}, 5, 0, 5, 0, 0, 0],[{v:"Conejos", f:"Conejos"}, 1, 0, 1, 0, 0, 0],[{v:"Bent", f:"Bent"}, 1, 0, 1, 0, 0, 0],
    ]);
    data.setProperty(0, 0, 'style', 'min-width:100px');
    var table = new google.visualization.Table(document.getElementById('geo_table'));
    table.draw(data, {allowHtml: true, sortColumn: 2, sortAscending: false, width: '660px', height: '100%'});
  }
</script>

<span style="font-size: 13px">All COVID-19 data displayed on the page is available through our FREE <a href="https://developer.smartable.ai">API program</a>. This US - Colorado State Coronavirus (COVID-19) Live Stats is refreshed every hour using credible data sources, including the country/state's official government website, <a href="https://en.wikipedia.org/wiki/2019%E2%80%9320_coronavirus_pandemic" target="_blank">data available on wikipedia pages</a>, latest news reports, <a href="https://systems.jhu.edu/research/public-health/ncov/" target="_blank">Johns Hopkins University CSSE 2019-nCoV Dashboard</a>, <a href="https://www.who.int/emergencies/diseases/novel-coronavirus-2019/situation-reports" target="_blank">WHO Situation Reports</a>, <a href="https://www.cdc.gov/coronavirus/2019-ncov/index.html" target="_blank">CDC Situation Updates</a>, and <a href="https://ncov.dxy.cn/ncovh5/view/pneumonia" target="_blank">DXY.cn</a>.</span>

<h2 id="news" class="center" style="margin-top: 60px; font-size: 25px;">Local Government Help Information</h2>
<div class="info center">
<a href="https://www.colorado.gov/pacific/cdphe/2019-novel-coronavirus" target="_blank">Colorado Department of Public Health & Environment</a> 303-389-1687 or 1-877-462-2911
</div>

