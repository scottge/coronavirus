---
category: stats
title: "US - New York Coronavirus (COVID-19) Live Stats"
excerpt: "Live stats of COVID-19 in US-New York. Total Cases: 347151 (+1745), Deaths: 27225 (+309), Recoveries: 58363(+263)."
publishedDateTime: 2020-05-12T06:45:10Z
updatedDateTime: 2020-05-12T06:45:10Z
webUrl: "https://smartable.ai/apps/coronavirus/stats/us-ny/"
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
  - url: "https://smartable.azureedge.net/coronavirus/sites/2/2020/us-ny.jpg"
    width: 900
    height: 564
    title: "US - New York Coronavirus (COVID-19) Live Stats"

---
<div class="total-stats" style="text-align: center;">
    <h3>
	    <div style="font-size: 18px; font-weight: 400;">Total Confirmed Cases:</div>
	    347151 (<span class='red'>+1745</span>)
    </h3>
    <h3>
	    <div style="font-size: 18px; font-weight: 400;">Total Deaths:</div>
	    27225 (<span class='red'>+309</span>)
    </h3>
    <h3>
	    <div style="font-size: 18px; font-weight: 400;">Total Recovered:</div>
	    58363 (<span class='green'>+263</span>)
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
      ['1/22/2020', 0, 0, 0],['1/23/2020', 0, 0, 0],['1/24/2020', 0, 0, 0],['1/25/2020', 0, 0, 0],['1/26/2020', 0, 0, 0],['1/27/2020', 0, 0, 0],['1/28/2020', 0, 0, 0],['1/29/2020', 0, 0, 0],['1/30/2020', 0, 0, 0],['1/31/2020', 0, 0, 0],['2/1/2020', 0, 0, 0],['2/2/2020', 0, 0, 0],['2/3/2020', 0, 0, 0],['2/4/2020', 0, 0, 0],['2/5/2020', 0, 0, 0],['2/6/2020', 0, 0, 0],['2/7/2020', 0, 0, 0],['2/8/2020', 0, 0, 0],['2/9/2020', 0, 0, 0],['2/10/2020', 0, 0, 0],['2/11/2020', 0, 0, 0],['2/12/2020', 0, 0, 0],['2/13/2020', 0, 0, 0],['2/14/2020', 0, 0, 0],['2/15/2020', 0, 0, 0],['2/16/2020', 0, 0, 0],['2/17/2020', 0, 0, 0],['2/18/2020', 0, 0, 0],['2/19/2020', 0, 0, 0],['2/20/2020', 0, 0, 0],['2/21/2020', 0, 0, 0],['2/22/2020', 0, 0, 0],['2/23/2020', 0, 0, 0],['2/24/2020', 0, 0, 0],['2/25/2020', 0, 0, 0],['2/26/2020', 0, 0, 0],['2/27/2020', 0, 0, 0],['2/28/2020', 0, 0, 0],['2/29/2020', 0, 0, 0],['3/1/2020', 0, 0, 0],['3/2/2020', 1, 0, 0],['3/3/2020', 2, 0, 0],['3/4/2020', 11, 0, 0],['3/5/2020', 23, 0, 0],['3/6/2020', 31, 0, 0],['3/7/2020', 76, 0, 0],['3/8/2020', 106, 0, 0],['3/9/2020', 142, 0, 0],['3/10/2020', 150, 0, 0],['3/11/2020', 218, 0, 0],['3/12/2020', 326, 0, 0],['3/13/2020', 439, 0, 0],['3/14/2020', 613, 2, 0],['3/15/2020', 746, 6, 0],['3/16/2020', 974, 10, 0],['3/17/2020', 1708, 16, 0],['3/18/2020', 3086, 17, 1],['3/19/2020', 5712, 38, 1],['3/20/2020', 8515, 56, 1],['3/21/2020', 12322, 76, 1],['3/22/2020', 16916, 153, 1],['3/23/2020', 23230, 183, 1],['3/24/2020', 26376, 271, 1],['3/25/2020', 33033, 366, 1],['3/26/2020', 39140, 461, 1],['3/27/2020', 46094, 605, 1],['3/28/2020', 53520, 834, 1],['3/29/2020', 59746, 966, 1],['3/30/2020', 67384, 1342, 1],['3/31/2020', 76049, 1714, 1],['4/1/2020', 84046, 2220, 6409],['4/2/2020', 92743, 2468, 6440],['4/3/2020', 103060, 2935, 6555],['4/4/2020', 114174, 3565, 11163],['4/5/2020', 123160, 4159, 12924],['4/6/2020', 131830, 4758, 14183],['4/7/2020', 140386, 5489, 15592],['4/8/2020', 151079, 6269, 15927],['4/9/2020', 161807, 7067, 16234],['4/10/2020', 174489, 7887, 16517],['4/11/2020', 181825, 8650, 16957],['4/12/2020', 190288, 9385, 25582],['4/13/2020', 196146, 10058, 26068],['4/14/2020', 203377, 10842, 26611],['4/15/2020', 214698, 11620, 27188],['4/16/2020', 223691, 12248, 27712],['4/17/2020', 235395, 17131, 27850],['4/18/2020', 242570, 17627, 28431],['4/19/2020', 248417, 18298, 28822],['4/20/2020', 253311, 18822, 29311],['4/21/2020', 258589, 19470, 29506],['4/22/2020', 263744, 20248, 29511],['4/23/2020', 271162, 20982, 30817],['4/24/2020', 277165, 21454, 30817],['4/25/2020', 288313, 22109, 31218],['4/26/2020', 293991, 22371, 31218],['4/27/2020', 298004, 22764, 45557],['4/28/2020', 301450, 23144, 46963],['4/29/2020', 306158, 23577, 48173],['4/30/2020', 310839, 23780, 49405],['5/1/2020', 315015, 24072, 49986],['5/2/2020', 319213, 24368, 50567],['5/3/2020', 323883, 24824, 52791],['5/4/2020', 327374, 25105, 53345],['5/5/2020', 330139, 25241, 53731],['5/6/2020', 333491, 25956, 54597],['5/7/2020', 337421, 26365, 55547],['5/8/2020', 340705, 26585, 56412],['5/9/2020', 343409, 26848, 56566],['5/10/2020', 345406, 26916, 58100],['5/11/2020', 347151, 27225, 58363],
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
      [42.65258, -73.756233, "Albany", 1456, 74],[42.3193, -77.7386, "Allegany", 38, 2],[42.1716, -75.8586, "Broome", 378, 27],[42.0368, -78.3373, "Cattaraugus", 61, 2],[42.7511, -76.6994, "Cayuga", 60, 2],[42.0747, -79.485, "Chautauqua", 41, 4],[42.0127, -76.7298, "Chemung", 131, 3],[42.624, -75.3353, "Chenango", 111, 3],[44.6951, -73.4563, "Clinton", 76, 4],[42.4134, -73.6778, "Columbia", 314, 25],[42.6004, -76.1784, "Cortland", 32, 1],[42.4459, -74.9088, "Delaware", 65, 4],[41.6191, -73.7944, "Dutchess", 3378, 103],[43.0085, -78.6308, "Erie", 4483, 359],[43.8345, -73.7647, "Essex", 40, 0],[44.2326, -74.4621, "Franklin", 17, 0],[43.1028, -74.2661, "Fulton", 109, 9],[42.978, -77.9899, "Genesee", 173, 3],[42.1773, -74.0229, "Greene", 206, 10],[43.5944, -74.3822, "Hamilton", 5, 1],[43.1859, -75.0151, "Herkimer", 81, 3],[43.7351, -76.1344, "Jefferson", 68, 0],[42.5838, -77.7915, "Livingston", 102, 6],[42.7401, -75.5436, "Madison", 251, 7],[41.3046, 74.1827, "Monroe", 1850, 147],[42.942, -74.1907, "Montgomery", 67, 4],[40.6546, -73.5594, "Nassau", 38337, 1973],[40.7128, -74.006, "New York", 185357, 20056],[43.1451, -78.8777, "Niagara", 655, 46],[43.0479, -75.2811, "Oneida", 669, 25],[43.0409, -76.1438, "Onondaga", 1287, 69],[42.8095, -77.2582, "Ontario", 107, 9],[41.3782, -74.6909, "Orange", 9584, 388],[43.3213, -78.3891, "Orleans", 130, 20],[43.3194, -76.5778, "Oswego", 75, 3],[42.7978, -74.7506, "Otsego", 67, 4],[41.4228, -73.6069, "Putnam", 1098, 56],[42.5332, -73.7493, "Rensselaer", 411, 23],[41.1489, -73.983, "Rockland", 12484, 576],[43.0324, -73.936, "Saratoga", 403, 13],[42.8614, -73.9206, "Schenectady", 575, 28],[42.7068, -74.3473, "Schoharie", 46, 1],[42.335, -76.7881, "Schuyler", 8, 0],[44.7481, -74.997, "St. Lawrence", 190, 2],[42.1634, -77.0925, "Steuben", 228, 39],[40.9849, -72.6151, "Suffolk", 36911, 1639],[41.7962, -74.7429, "Sullivan", 1109, 25],[42.2149, -76.496, "Tioga", 107, 14],[42.4113, -76.4883, "Tompkins", 132, 0],[41.8586, -74.3118, "Ulster", 1454, 58],[43.5614, -73.6588, "Warren", 217, 21],[43.4082, -73.2617, "Washington", 210, 12],[43.2371, -77.0628, "Wayne", 81, 2],[41.122, -73.7949, "Westchester", 31384, 1305],[42.6312, -78.0525, "Wyoming", 77, 5],[43.8947, -75.3914, "Lewis", 11, 5],[42.6135, -76.8225, "Seneca", 49, 2],[42.6123, -77.0916, "Yates", 21, 3],
    ]);
    var options = {
      backgroundColor: {fill:'transparent',stroke:'#FFF' ,strokeWidth:0 }, 
      displayMode: 'markers',
      region: 'US-NY', 
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
      [{v:"Albany", f:"Albany"}, 1456, 24, 1382, 74, 0, 0],[{v:"Allegany", f:"Allegany"}, 38, 2, 9, 2, 0, 27],[{v:"Broome", f:"Broome"}, 378, 5, 265, 27, 0, 86],[{v:"Cattaraugus", f:"Cattaraugus"}, 61, 1, 59, 2, 0, 0],[{v:"Cayuga", f:"Cayuga"}, 60, 2, 16, 2, 0, 42],[{v:"Chautauqua", f:"Chautauqua"}, 41, 0, 13, 4, 0, 24],[{v:"Chemung", f:"Chemung"}, 131, 0, 118, 3, 0, 10],[{v:"Chenango", f:"Chenango"}, 111, 2, 108, 3, 0, 0],[{v:"Clinton", f:"Clinton"}, 76, 0, 28, 4, 0, 44],[{v:"Columbia", f:"Columbia"}, 314, 2, 223, 25, 0, 66],[{v:"Cortland", f:"Cortland"}, 32, 0, 3, 1, 0, 28],[{v:"Delaware", f:"Delaware"}, 65, 0, 29, 4, 0, 32],[{v:"Dutchess", f:"Dutchess"}, 3378, 19, 2902, 103, 0, 373],[{v:"Erie", f:"Erie"}, 4483, 30, 3645, 359, 0, 479],[{v:"Essex", f:"Essex"}, 40, 1, 32, 0, 0, 8],[{v:"Franklin", f:"Franklin"}, 17, 0, 13, 0, 0, 4],[{v:"Fulton", f:"Fulton"}, 109, 2, 100, 9, 0, 0],[{v:"Genesee", f:"Genesee"}, 173, 1, 106, 3, 0, 64],[{v:"Greene", f:"Greene"}, 206, 0, 136, 10, 0, 60],[{v:"Hamilton", f:"Hamilton"}, 5, 0, 4, 1, 0, 0],[{v:"Herkimer", f:"Herkimer"}, 81, 2, 78, 3, 0, 0],[{v:"Jefferson", f:"Jefferson"}, 68, 0, 59, 0, 0, 9],[{v:"Livingston", f:"Livingston"}, 102, 0, 67, 6, 0, 29],[{v:"Madison", f:"Madison"}, 251, 0, 138, 7, 0, 106],[{v:"Monroe", f:"Monroe"}, 1850, 29, 1178, 147, 0, 525],[{v:"Montgomery", f:"Montgomery"}, 67, 0, 38, 4, 0, 25],[{v:"Nassau", f:"Nassau"}, 38337, 120, 34211, 1973, 10, 2153],[{v:"New York", f:"New York"}, 185357, 940, 165301, 20056, 238, 0],[{v:"Niagara", f:"Niagara"}, 655, 12, 455, 46, 0, 154],[{v:"Oneida", f:"Oneida"}, 669, 9, 531, 25, 0, 113],[{v:"Onondaga", f:"Onondaga"}, 1287, 22, 796, 69, 0, 422],[{v:"Ontario", f:"Ontario"}, 107, 1, 51, 9, 0, 47],[{v:"Orange", f:"Orange"}, 9584, 41, 9196, 388, 21, 0],[{v:"Orleans", f:"Orleans"}, 130, 4, 88, 20, 0, 22],[{v:"Oswego", f:"Oswego"}, 75, 0, 26, 3, 0, 46],[{v:"Otsego", f:"Otsego"}, 67, 0, 32, 4, 0, 31],[{v:"Putnam", f:"Putnam"}, 1098, 9, 1042, 56, 0, 0],[{v:"Rensselaer", f:"Rensselaer"}, 411, 2, 283, 23, 0, 105],[{v:"Rockland", f:"Rockland"}, 12484, 33, 11908, 576, 14, 0],[{v:"Saratoga", f:"Saratoga"}, 403, 1, 269, 13, 0, 121],[{v:"Schenectady", f:"Schenectady"}, 575, 4, 349, 28, 0, 198],[{v:"Schoharie", f:"Schoharie"}, 46, 0, 45, 1, 0, 0],[{v:"Schuyler", f:"Schuyler"}, 8, 0, 2, 0, 0, 6],[{v:"St. Lawrence", f:"St. Lawrence"}, 190, 3, 188, 2, 0, 0],[{v:"Steuben", f:"Steuben"}, 228, 1, 85, 39, 0, 104],[{v:"Suffolk", f:"Suffolk"}, 36911, 209, 33160, 1639, 22, 2112],[{v:"Sullivan", f:"Sullivan"}, 1109, 16, 738, 25, 0, 346],[{v:"Tioga", f:"Tioga"}, 107, 2, 73, 14, 0, 20],[{v:"Tompkins", f:"Tompkins"}, 132, 0, 38, 0, 0, 94],[{v:"Ulster", f:"Ulster"}, 1454, 4, 1235, 58, 4, 161],[{v:"Warren", f:"Warren"}, 217, 10, 196, 21, 0, 0],[{v:"Washington", f:"Washington"}, 210, 4, 159, 12, 0, 39],[{v:"Wayne", f:"Wayne"}, 81, 1, 44, 2, 0, 35],[{v:"Westchester", f:"Westchester"}, 31384, 90, 20708, 1305, 0, 9371],[{v:"Wyoming", f:"Wyoming"}, 77, 0, 41, 5, 0, 31],[{v:"Lewis", f:"Lewis"}, 11, 0, 1, 5, 0, 5],[{v:"Seneca", f:"Seneca"}, 49, 0, 47, 2, 0, 0],[{v:"Yates", f:"Yates"}, 21, 0, 16, 3, 0, 2],
    ]);
    data.setProperty(0, 0, 'style', 'min-width:100px');
    var table = new google.visualization.Table(document.getElementById('geo_table'));
    table.draw(data, {allowHtml: true, sortColumn: 2, sortAscending: false, width: '660px', height: '100%'});
  }
</script>

<span style="font-size: 13px">All COVID-19 data displayed on the page is available through our FREE <a href="https://developer.smartable.ai">API program</a>. This US - New York Coronavirus (COVID-19) Live Stats is refreshed every hour using credible data sources, including the country/state's official government website, <a href="https://en.wikipedia.org/wiki/2019%E2%80%9320_coronavirus_pandemic" target="_blank">data available on wikipedia pages</a>, latest news reports, <a href="https://systems.jhu.edu/research/public-health/ncov/" target="_blank">Johns Hopkins University CSSE 2019-nCoV Dashboard</a>, <a href="https://www.who.int/emergencies/diseases/novel-coronavirus-2019/situation-reports" target="_blank">WHO Situation Reports</a>, <a href="https://www.cdc.gov/coronavirus/2019-ncov/index.html" target="_blank">CDC Situation Updates</a>, and <a href="https://ncov.dxy.cn/ncovh5/view/pneumonia" target="_blank">DXY.cn</a>.</span>

<h2 id="news" class="center" style="margin-top: 60px; font-size: 25px;">Local Government Help Information</h2>
<div class="info center">
<a href="https://www.health.ny.gov/" target="_blank" rel="noopener noreferrer">New York State Department of Health</a> 888-364-3065<br /><a href="https://www1.nyc.gov/site/doh/health/health-topics/coronavirus.page" target="_blank" rel="noopener noreferrer">NYC Health</a> 347-396-7990
</div>
<h2 id="news" class="center" style="margin-top: 60px; font-size: 25px;">Trending Coronavirus News in US-New York</h2>
<div class="row">
<div class="col-md-6 col-sm-12">
  <div class="content-card">
	<a href="https://www.nytimes.com/2020/05/09/health/mysterious-coronavirus-illness-claims-3-children-in-new-york.html"><div class="card-image" style="background-image: url(https://static01.nyt.com/images/2020/05/09/us/politics/09virus-kids/merlin_171615855_3fcf73e0-bb43-4f50-85ee-4542d445b500-facebookJumbo.jpg)"></div></a>
	<div class="content">
		<div class="card-title"><a href="https://www.nytimes.com/2020/05/09/health/mysterious-coronavirus-illness-claims-3-children-in-new-york.html">Mysterious Coronavirus Illness Claims 3 Children in New York</a></div>
		<div class="card-excerpt">A baffling ailment linked to Covid-19 has killed three young children and sickened 73 others across the state.</div>
		<div class="card-meta">
			<span class="card-provider">New York Times</span> • <span class="card-date">5/9/2020</span>
		</div>
	</div>
  </div>
</div>
<div class="col-md-6 col-sm-12">
  <div class="content-card">
	<a href="https://www.reuters.com/article/us-health-coronavirus-usa-ny-idUSKBN22L0OF"><div class="card-image" style="background-image: url(https://s4.reutersmedia.net/resources/r/?m=02&d=20200509&t=2&i=1518049053&w=&fh=545px&fw=&ll=&pl=&sq=&r=LYNXMPEG480M9)"></div></a>
	<div class="content">
		<div class="card-title"><a href="https://www.reuters.com/article/us-health-coronavirus-usa-ny-idUSKBN22L0OF">Rare syndrome tied to COVID-19 kills three children in New York, Cuomo says</a></div>
		<div class="card-excerpt">Three children in New York have died from a rare inflammatory syndrome believed to be linked to the novel coronavirus, Governor Andrew Cuomo said on Saturday, a development that may augur a pandemic risk for children.</div>
		<div class="card-meta">
			<span class="card-provider">Reuters</span> • <span class="card-date">5/9/2020</span>
		</div>
	</div>
  </div>
</div>
<div class="col-md-6 col-sm-12">
  <div class="content-card">
	<a href="https://www.forbes.com/sites/sergeiklebnikov/2020/05/08/cuomo-says-new-york-is-finally-ahead-of-this-virus/"><div class="card-image" style="background-image: url(https://thumbor.forbes.com/thumbor/fit-in/1200x0/filters%3Aformat%28jpg%29/https%3A%2F%2Fspecials-images.forbesimg.com%2Fimageserve%2F5eb58ade170c940006485cd8%2F0x0.jpg)"></div></a>
	<div class="content">
		<div class="card-title"><a href="https://www.forbes.com/sites/sergeiklebnikov/2020/05/08/cuomo-says-new-york-is-finally-ahead-of-this-virus/">Cuomo Says New York Is ‘Finally Ahead Of This Virus’</a></div>
		<div class="card-excerpt">The good news, Cuomo said, is that he feels that for the first time, “we’re finally ahead of this virus.” “Our numbers are coming down in New York—in most states in this country, you still see the numbers going up,</div>
		<div class="card-meta">
			<span class="card-provider">Forbes</span> • <span class="card-date">5/8/2020</span>
		</div>
	</div>
  </div>
</div>
<div class="col-md-6 col-sm-12">
  <div class="content-card">
	<a href="https://www.reuters.com/article/us-health-coronavirus-usa-new-york-idUSKBN22K2C0"><div class="card-image" style="background-image: url(https://s3.reutersmedia.net/resources/r/?m=02&d=20200508&t=2&i=1517982487&w=&fh=545px&fw=&ll=&pl=&sq=&r=LYNXMPEG471GQ)"></div></a>
	<div class="content">
		<div class="card-title"><a href="https://www.reuters.com/article/us-health-coronavirus-usa-new-york-idUSKBN22K2C0">New York governor says 5-year old died from rare COVID-related complications</a></div>
		<div class="card-excerpt">A 5-year old boy has died in New York from a rare inflammatory syndrome believed to be linked to the novel coronavirus, highlighting a potential new risk for children in the pandemic, Governor Andrew Cuomo said on Friday.</div>
		<div class="card-meta">
			<span class="card-provider">Reuters</span> • <span class="card-date">5/8/2020</span>
		</div>
	</div>
  </div>
</div>
<div class="col-md-6 col-sm-12">
  <div class="content-card">
	<a href="https://www.reuters.com/article/us-health-coronavirus-sorrento-thera-idUSKBN22K1QX"><div class="card-image" style="background-image: url(https://s2.reutersmedia.net/resources/r/?m=02&d=20200508&t=2&i=1517941902&w=&fh=545px&fw=&ll=&pl=&sq=&r=LYNXMPEG4713H)"></div></a>
	<div class="content">
		<div class="card-title"><a href="https://www.reuters.com/article/us-health-coronavirus-sorrento-thera-idUSKBN22K1QX">Sorrento ties up with New York's Mount Sinai for COVID-19 antibody cocktail</a></div>
		<div class="card-excerpt">Sorrento Therapeutics Inc on Friday partnered with New York City's Mount Sinai Health System to develop an antibody cocktail to potentially treat or prevent COVID-19, with the aim of starting human trials in the third quarter.</div>
		<div class="card-meta">
			<span class="card-provider">Reuters</span> • <span class="card-date">5/8/2020</span>
		</div>
	</div>
  </div>
</div>
<div class="col-md-6 col-sm-12">
  <div class="content-card">
	<a href="https://www.usatoday.com/story/news/nation/2020/05/07/new-york-woman-beats-coronavirus-celebrates-100th-birthday/3090164001/"><div class="card-image" style="background-image: url(https://www.gannett-cdn.com/presto/2020/05/07/PROC/818d0811-1f2d-418b-9eda-2ff3a3882058-MaryJaneHastings.jpg?auto=webp&crop=610,344,x0,y133&format=pjpg&width=1200)"></div></a>
	<div class="content">
		<div class="card-title"><a href="https://www.usatoday.com/story/news/nation/2020/05/07/new-york-woman-beats-coronavirus-celebrates-100th-birthday/3090164001/">New York woman beats coronavirus, celebrates 100th birthday: 'She really is remarkable'</a></div>
		<div class="card-excerpt">A week prior, her brother died of the virus at 98. The family of Mary Jane Hastings worried “that would be it" after her diagnosis.</div>
		<div class="card-meta">
			<span class="card-provider">USA Today</span> • <span class="card-date">5/7/2020</span>
		</div>
	</div>
  </div>
</div>
<div class="col-md-6 col-sm-12">
  <div class="content-card">
	<a href="https://www.cnbc.com/video/2020/05/06/new-york-gov-andrew-cuomo-says-its-shocking-most-new-coronavirus-cases-were-people-who-stayed-at-home.html"><div class="card-image" style="background-image: url(https://image.cnbcfm.com/api/v1/image/106515969-1588339507418gettyimages-1211432279.jpeg?v=1588339543)"></div></a>
	<div class="content">
		<div class="card-title"><a href="https://www.cnbc.com/video/2020/05/06/new-york-gov-andrew-cuomo-says-its-shocking-most-new-coronavirus-cases-were-people-who-stayed-at-home.html">New York Gov. Andrew Cuomo says it's 'shocking' most new coronavirus cases were people who stayed at home</a></div>
		<div class="card-excerpt">New York Gov. Andrew Cuomo said that preliminary data from the state's hospitals indicates a majority of new hospitalizations related to Covid-19 were people who are at home and not frequently traveling.</div>
		<div class="card-meta">
			<span class="card-provider">CNBC</span> • <span class="card-date">5/6/2020</span>
		</div>
	</div>
  </div>
</div>
<div class="col-md-6 col-sm-12">
  <div class="content-card">
	<a href="https://www.wsj.com/articles/new-york-city-subway-begins-nightly-shutdowns-for-coronavirus-cleaning-11588767945"><div class="card-image" style="background-image: url(https://images.wsj.net/im-184067/social)"></div></a>
	<div class="content">
		<div class="card-title"><a href="https://www.wsj.com/articles/new-york-city-subway-begins-nightly-shutdowns-for-coronavirus-cleaning-11588767945">New York City Subway Begins Nightly Shutdowns for Coronavirus Cleaning</a></div>
		<div class="card-excerpt">Cleaning crews backed by swarms of police officers descended into New York City’s subway system early Wednesday to disinfect trains, in the first regularly scheduled shutdown of the subway system in over a century of operation.</div>
		<div class="card-meta">
			<span class="card-provider">Wall Street Journal</span> • <span class="card-date">5/6/2020</span>
		</div>
	</div>
  </div>
</div>

</div>

