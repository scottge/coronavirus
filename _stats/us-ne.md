---
category: stats
title: "US - Nebraska State Coronavirus (COVID-19) Live Stats"
excerpt: "Live stats of COVID-19 in US-Nebraska. Total Cases: 8234 (+403), Deaths: 98 (+1), Recoveries: 22(-)."
publishedDateTime: 2020-05-10T05:45:41Z
updatedDateTime: 2020-05-10T05:45:41Z
webUrl: "https://smartable.ai/apps/coronavirus/stats/us-ne/"
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
  - url: "https://smartable.azureedge.net/coronavirus/sites/2/2020/us-ne.jpg"
    width: 900
    height: 564
    title: "US - Nebraska State Coronavirus (COVID-19) Live Stats"

---
<div class="total-stats" style="text-align: center;">
    <h3>
	    <div style="font-size: 18px; font-weight: 400;">Total Confirmed Cases:</div>
	    8234 (<span class='red'>+403</span>)
    </h3>
    <h3>
	    <div style="font-size: 18px; font-weight: 400;">Total Deaths:</div>
	    98 (<span class='red'>+1</span>)
    </h3>
    <h3>
	    <div style="font-size: 18px; font-weight: 400;">Total Recovered:</div>
	    22 (-)
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
      ['1/22/2020', 0, 0, 0],['1/23/2020', 0, 0, 0],['1/24/2020', 0, 0, 0],['1/25/2020', 0, 0, 0],['1/26/2020', 0, 0, 0],['1/27/2020', 0, 0, 0],['1/28/2020', 0, 0, 0],['1/29/2020', 0, 0, 0],['1/30/2020', 0, 0, 0],['1/31/2020', 0, 0, 0],['2/1/2020', 0, 0, 0],['2/2/2020', 0, 0, 0],['2/3/2020', 0, 0, 0],['2/4/2020', 0, 0, 0],['2/5/2020', 0, 0, 0],['2/6/2020', 0, 0, 0],['2/7/2020', 0, 0, 0],['2/8/2020', 0, 0, 0],['2/9/2020', 0, 0, 0],['2/10/2020', 0, 0, 0],['2/11/2020', 0, 0, 0],['2/12/2020', 0, 0, 0],['2/13/2020', 0, 0, 0],['2/14/2020', 0, 0, 0],['2/15/2020', 0, 0, 0],['2/16/2020', 0, 0, 0],['2/17/2020', 0, 0, 0],['2/18/2020', 0, 0, 0],['2/19/2020', 0, 0, 0],['2/20/2020', 0, 0, 0],['2/21/2020', 0, 0, 0],['2/22/2020', 0, 0, 0],['2/23/2020', 0, 0, 0],['2/24/2020', 0, 0, 0],['2/25/2020', 0, 0, 0],['2/26/2020', 0, 0, 0],['2/27/2020', 0, 0, 0],['2/28/2020', 0, 0, 0],['2/29/2020', 0, 0, 0],['3/1/2020', 0, 0, 0],['3/2/2020', 0, 0, 0],['3/3/2020', 0, 0, 0],['3/4/2020', 0, 0, 0],['3/5/2020', 0, 0, 0],['3/6/2020', 1, 0, 0],['3/7/2020', 1, 0, 0],['3/8/2020', 1, 0, 0],['3/9/2020', 3, 0, 0],['3/10/2020', 3, 0, 0],['3/11/2020', 5, 0, 0],['3/12/2020', 11, 0, 0],['3/13/2020', 14, 0, 0],['3/14/2020', 17, 0, 0],['3/15/2020', 18, 0, 0],['3/16/2020', 18, 0, 0],['3/17/2020', 24, 0, 0],['3/18/2020', 29, 0, 0],['3/19/2020', 32, 0, 0],['3/20/2020', 38, 0, 0],['3/21/2020', 51, 0, 0],['3/22/2020', 51, 0, 0],['3/23/2020', 66, 0, 0],['3/24/2020', 71, 0, 0],['3/25/2020', 74, 0, 0],['3/26/2020', 82, 0, 0],['3/27/2020', 90, 2, 0],['3/28/2020', 108, 2, 0],['3/29/2020', 120, 2, 0],['3/30/2020', 154, 3, 0],['3/31/2020', 178, 4, 0],['4/1/2020', 215, 4, 0],['4/2/2020', 255, 6, 0],['4/3/2020', 280, 6, 0],['4/4/2020', 323, 8, 0],['4/5/2020', 364, 8, 0],['4/6/2020', 418, 9, 0],['4/7/2020', 478, 10, 0],['4/8/2020', 519, 12, 0],['4/9/2020', 577, 15, 0],['4/10/2020', 647, 17, 0],['4/11/2020', 704, 17, 0],['4/12/2020', 814, 17, 0],['4/13/2020', 853, 18, 0],['4/14/2020', 901, 20, 0],['4/15/2020', 952, 21, 0],['4/16/2020', 1066, 24, 0],['4/17/2020', 1138, 24, 0],['4/18/2020', 1287, 28, 0],['4/19/2020', 1474, 28, 0],['4/20/2020', 1648, 33, 0],['4/21/2020', 1722, 33, 0],['4/22/2020', 1813, 38, 0],['4/23/2020', 2202, 47, 0],['4/24/2020', 2271, 56, 0],['4/25/2020', 2732, 53, 22],['4/26/2020', 3095, 56, 22],['4/27/2020', 3358, 57, 22],['4/28/2020', 3515, 57, 22],['4/29/2020', 3865, 68, 22],['4/30/2020', 4281, 75, 22],['5/1/2020', 4793, 75, 22],['5/2/2020', 5330, 78, 22],['5/3/2020', 5679, 81, 22],['5/4/2020', 6107, 86, 22],['5/5/2020', 6438, 84, 22],['5/6/2020', 6771, 88, 22],['5/7/2020', 7190, 92, 22],['5/8/2020', 7831, 97, 22],['5/9/2020', 8234, 98, 22],
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
      [40.4377, -98.4409, "Adams", 223, 6],[40.9276, -99.3901, "Buffalo", 121, 1],[40.8691, -96.14, "Cass", 11, 0],[40.7065, -100.2155, "Dawson", 705, 4],[41.416, -96.5021, "Dodge", 147, 0],[41.3148, -96.1951, "Douglas", 1501, 19],[40.2849, -96.534, "Gage", 40, 3],[40.5733, -99.7409, "Gosper", 12, 0],[41.0046, -98.6007, "Hall", 1325, 34],[40.4981, -98.9671, "Kearney", 7, 0],[42.6712, -97.8722, "Knox", 5, 0],[40.6818, -96.5039, "Lancaster", 595, 2],[40.7539, -100.7319, "Lincoln", 39, 2],[42.0328, -97.4209, "Madison", 249, 4],[40.4787, -95.7313, "Nemaha", 1, 0],[41.7004, -97.6938, "Platte", 353, 0],[41.0718, -95.9255, "Sarpy", 234, 1],[41.2665, -96.7209, "Saunders", 11, 1],[41.9641, -103.9247, "Scotts Bluff", 42, 0],[41.4747, -96.2037, "Washington", 23, 1],[40.7795, -97.8114, "York", 17, 0],[42.3377, -97.9718, "Antelope", 6, 0],[41.2342, -103.4867, "Kimball", 10, 0],[41.8378, -96.7062, "Cuming", 12, 0],[40.8812, -97.8875, "Hamilton", 52, 9],[40.6762, -95.8613, "Otoe", 3, 0],[41.4367, -97.2152, "Colfax", 413, 0],[41.1667, -98.1389, "Merrick", 21, 0],[42.923, -101.6997, "Cherry", 1, 0],[40.5104, -96.1617, "Johnson", 5, 0],[40.7782, -97.2825, "Seward", 17, 1],[40.5263, -99.6324, "Phelps", 10, 0],[41.4082, -102.9708, "Cheyenne", 8, 0],[41.2863, -99.3824, "Custer", 33, 4],[41.9471, -97.2172, "Stanton", 11, 0],[41.936, -96.4717, "Burt", 6, 0],[41.116, -97.5911, "Polk", 10, 0],[40.0864, -98.5222, "Webster", 5, 0],[40.0966, -98.9514, "Franklin", 6, 0],[42.4555, -97.4698, "Cedar", 5, 0],[40.3548, -98.1392, "Clay", 13, 0],[42.2758, -97.1909, "Wayne", 2, 0],[42.2747, -97.6651, "Pierce", 2, 0],[42.4507, -96.579, "Dakota", 1407, 5],[40.4809, -96.9646, "Saline", 349, 0],[41.6639, -103.0962, "Morrill", 9, 0],[42.3213, -103.0753, "Box Butte", 1, 0],[41.2156, -98.628, "Howard", 22, 0],[41.4709, -98.0677, "Nance", 4, 0],[41.1983, -97.2974, "Butler", 16, 0],[40.2046, -100.6213, "Red Willow", 5, 0],[40.2776, -99.7763, "Furnas", 4, 0],[42.0574, -96.5128, "Thurston", 12, 0],[42.2665, -96.8632, "Dixon", 24, 0],[40.4149, -97.5871, "Fillmore", 3, 1],[41.5484, -98.5305, "Greeley", 2, 0],[41.1562, -99.1532, "Sherman", 2, 0],[41.9251335, -99.456155, "Loup", 1, 0],[41.5680276, -101.6157773, "Arthur", 1, 0],[42.6551733, -103.0817903, "Dawes", 2, 0],[40.1680732, -97.179026, "Jefferson", 4, 0],[41.4936253, -98.9245343, "Valley", 1, 0],[40.5744778, -100.3497895, "Frontier", 1, 0],[40.1844599, -101.0711758, "Hitchcock", 1, 0],[41.9368476, -101.0711758, "Hooker", 1, 0],[41.1815863, -101.5248055, "Keith", 2, 0],[42.3803308, -98.6600586, "Holt", 1, 0],[41.7172326, -98.0465185, "Boone", 2, 0],[41.6222686, -101.0711758, "McPherson", 10, 0],[41.9882143, -100.5296115, "Thomas", 1, 0],
    ]);
    var options = {
      backgroundColor: {fill:'transparent',stroke:'#FFF' ,strokeWidth:0 }, 
      displayMode: 'markers',
      region: 'US-NE', 
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
      [{v:"Adams", f:"Adams"}, 223, 5, 217, 6, 0, 0],[{v:"Buffalo", f:"Buffalo"}, 121, 2, 120, 1, 0, 0],[{v:"Cass", f:"Cass"}, 11, 2, 11, 0, 0, 0],[{v:"Dawson", f:"Dawson"}, 705, 25, 701, 4, 0, 0],[{v:"Dodge", f:"Dodge"}, 147, 8, 147, 0, 0, 0],[{v:"Douglas", f:"Douglas"}, 1501, 159, 1482, 19, 0, 0],[{v:"Gage", f:"Gage"}, 40, 0, 37, 3, 0, 0],[{v:"Gosper", f:"Gosper"}, 12, 0, 12, 0, 0, 0],[{v:"Hall", f:"Hall"}, 1325, 14, 1291, 34, 0, 0],[{v:"Kearney", f:"Kearney"}, 7, 0, 7, 0, 0, 0],[{v:"Knox", f:"Knox"}, 5, 0, 5, 0, 0, 0],[{v:"Lancaster", f:"Lancaster"}, 595, 48, 593, 2, 0, 0],[{v:"Lincoln", f:"Lincoln"}, 39, 0, 37, 2, 0, 0],[{v:"Madison", f:"Madison"}, 249, 6, 245, 4, 0, 0],[{v:"Nemaha", f:"Nemaha"}, 1, 0, 1, 0, 0, 0],[{v:"Platte", f:"Platte"}, 353, 29, 353, 0, 0, 0],[{v:"Sarpy", f:"Sarpy"}, 234, 16, 233, 1, 0, 0],[{v:"Saunders", f:"Saunders"}, 11, 0, 10, 1, 1, 0],[{v:"Scotts Bluff", f:"Scotts Bluff"}, 42, 3, 42, 0, 0, 0],[{v:"Washington", f:"Washington"}, 23, 0, 22, 1, 0, 0],[{v:"York", f:"York"}, 17, 2, 17, 0, 0, 0],[{v:"Antelope", f:"Antelope"}, 6, 0, 6, 0, 0, 0],[{v:"Kimball", f:"Kimball"}, 10, 0, 10, 0, 0, 0],[{v:"Cuming", f:"Cuming"}, 12, 1, 12, 0, 0, 0],[{v:"Hamilton", f:"Hamilton"}, 52, 0, 43, 9, 0, 0],[{v:"Otoe", f:"Otoe"}, 3, 0, 3, 0, 0, 0],[{v:"Colfax", f:"Colfax"}, 413, 22, 413, 0, 0, 0],[{v:"Merrick", f:"Merrick"}, 21, 0, 21, 0, 0, 0],[{v:"Cherry", f:"Cherry"}, 1, 0, 1, 0, 0, 0],[{v:"Johnson", f:"Johnson"}, 5, 0, 5, 0, 0, 0],[{v:"Seward", f:"Seward"}, 17, 1, 16, 1, 0, 0],[{v:"Phelps", f:"Phelps"}, 10, 1, 10, 0, 0, 0],[{v:"Cheyenne", f:"Cheyenne"}, 8, 0, 8, 0, 0, 0],[{v:"Custer", f:"Custer"}, 33, 0, 29, 4, 0, 0],[{v:"Stanton", f:"Stanton"}, 11, 0, 11, 0, 0, 0],[{v:"Burt", f:"Burt"}, 6, 1, 6, 0, 0, 0],[{v:"Polk", f:"Polk"}, 10, 0, 10, 0, 0, 0],[{v:"Webster", f:"Webster"}, 5, 0, 5, 0, 0, 0],[{v:"Franklin", f:"Franklin"}, 6, 1, 6, 0, 0, 0],[{v:"Cedar", f:"Cedar"}, 5, 0, 5, 0, 0, 0],[{v:"Clay", f:"Clay"}, 13, 0, 13, 0, 0, 0],[{v:"Wayne", f:"Wayne"}, 2, 1, 2, 0, 0, 0],[{v:"Pierce", f:"Pierce"}, 2, 0, 2, 0, 0, 0],[{v:"Dakota", f:"Dakota"}, 1407, 84, 1402, 5, 0, 0],[{v:"Saline", f:"Saline"}, 349, 29, 349, 0, 0, 0],[{v:"Morrill", f:"Morrill"}, 9, 1, 9, 0, 0, 0],[{v:"Box Butte", f:"Box Butte"}, 1, 0, 1, 0, 0, 0],[{v:"Howard", f:"Howard"}, 22, 1, 22, 0, 0, 0],[{v:"Nance", f:"Nance"}, 4, 0, 4, 0, 0, 0],[{v:"Butler", f:"Butler"}, 16, 1, 16, 0, 0, 0],[{v:"Red Willow", f:"Red Willow"}, 5, 0, 5, 0, 0, 0],[{v:"Furnas", f:"Furnas"}, 4, 0, 4, 0, 0, 0],[{v:"Thurston", f:"Thurston"}, 12, 0, 12, 0, 0, 0],[{v:"Dixon", f:"Dixon"}, 24, 1, 24, 0, 0, 0],[{v:"Fillmore", f:"Fillmore"}, 3, 0, 2, 1, 0, 0],[{v:"Greeley", f:"Greeley"}, 2, 0, 2, 0, 0, 0],[{v:"Sherman", f:"Sherman"}, 2, 0, 2, 0, 0, 0],[{v:"Loup", f:"Loup"}, 1, 0, 1, 0, 0, 0],[{v:"Arthur", f:"Arthur"}, 1, 0, 1, 0, 0, 0],[{v:"Dawes", f:"Dawes"}, 2, 0, 2, 0, 0, 0],[{v:"Jefferson", f:"Jefferson"}, 4, 0, 4, 0, 0, 0],[{v:"Valley", f:"Valley"}, 1, 0, 1, 0, 0, 0],[{v:"Frontier", f:"Frontier"}, 1, 0, 1, 0, 0, 0],[{v:"Hitchcock", f:"Hitchcock"}, 1, 0, 1, 0, 0, 0],[{v:"Hooker", f:"Hooker"}, 1, 0, 1, 0, 0, 0],[{v:"Keith", f:"Keith"}, 2, 0, 2, 0, 0, 0],[{v:"Holt", f:"Holt"}, 1, 0, 1, 0, 0, 0],[{v:"Boone", f:"Boone"}, 2, 0, 2, 0, 0, 0],[{v:"McPherson", f:"McPherson"}, 10, 0, 10, 0, 0, 0],[{v:"Thomas", f:"Thomas"}, 1, 0, 1, 0, 0, 0],
    ]);
    data.setProperty(0, 0, 'style', 'min-width:100px');
    var table = new google.visualization.Table(document.getElementById('geo_table'));
    table.draw(data, {allowHtml: true, sortColumn: 2, sortAscending: false, width: '660px', height: '100%'});
  }
</script>

<span style="font-size: 13px">All COVID-19 data displayed on the page is available through our FREE <a href="https://developer.smartable.ai">API program</a>. This US - Nebraska State Coronavirus (COVID-19) Live Stats is refreshed every hour using credible data sources, including the country/state's official government website, <a href="https://en.wikipedia.org/wiki/2019%E2%80%9320_coronavirus_pandemic" target="_blank">data available on wikipedia pages</a>, latest news reports, <a href="https://systems.jhu.edu/research/public-health/ncov/" target="_blank">Johns Hopkins University CSSE 2019-nCoV Dashboard</a>, <a href="https://www.who.int/emergencies/diseases/novel-coronavirus-2019/situation-reports" target="_blank">WHO Situation Reports</a>, <a href="https://www.cdc.gov/coronavirus/2019-ncov/index.html" target="_blank">CDC Situation Updates</a>, and <a href="https://ncov.dxy.cn/ncovh5/view/pneumonia" target="_blank">DXY.cn</a>.</span>

<h2 id="news" class="center" style="margin-top: 60px; font-size: 25px;">Local Government Help Information</h2>
<div class="info center">
<a href="http://dhhs.ne.gov/Pages/Coronavirus.aspx" target="_blank">Nebraska Department of Health & Human Services</a>
</div>
<h2 id="news" class="center" style="margin-top: 60px; font-size: 25px;">Trending Coronavirus News in US-Nebraska</h2>
<div class="row">
<div class="col-md-6 col-sm-12">
  <div class="content-card">
	<a href="https://apnews.com/44536be6032fc220a0857b82c714073c"><div class="card-image" style="background-image: url(https://apnews.com/images/ShareLogo2.png)"></div></a>
	<div class="content">
		<div class="card-title"><a href="https://apnews.com/44536be6032fc220a0857b82c714073c">Another Nebraska prisons staffer tests positive for COVID-19</a></div>
		<div class="card-excerpt">Another staffer at Lincoln’s Nebraska State Penitentiary has tested positive for the new coronavirus, state prisons officials said Tuesday. The Nebraska Department</div>
		<div class="card-meta">
			<span class="card-provider">Associated Press</span> • <span class="card-date">5/5/2020</span>
		</div>
	</div>
  </div>
</div>
<div class="col-md-6 col-sm-12">
  <div class="content-card">
	<a href="https://www.staradvertiser.com/2020/05/03/breaking-news/nebraska-will-open-voting-sites-for-primary-despite-covid-19-concerns/"><div class="card-image" style="background-image: url(https://www.staradvertiser.com/wp-content/uploads/2020/05/web1_9939906-0c620346df17434c8575db27b21cda97.jpg)"></div></a>
	<div class="content">
		<div class="card-title"><a href="https://www.staradvertiser.com/2020/05/03/breaking-news/nebraska-will-open-voting-sites-for-primary-despite-covid-19-concerns/">Nebraska will open voting sites for primary despite COVID-19 concerns</a></div>
		<div class="card-excerpt">LINCOLN, Neb. >> Nebraska is forging ahead with plans to hold the nation’s first in-person election in more than a month, despite health concerns about the coronavirus pandemic and allegations that political motivations are fueling opposition to an all-mail approach.</div>
		<div class="card-meta">
			<span class="card-provider">Honolulu Star-Advertiser</span> • <span class="card-date">5/3/2020</span>
		</div>
	</div>
  </div>
</div>
<div class="col-md-6 col-sm-12">
  <div class="content-card">
	<a href="https://www.omaha.com/livewellnebraska/fourth-nebraska-prison-worker-tests-positive-for-coronavirus/article_d043dd03-8636-526a-afa3-596143d3cee5.html"><div class="card-image" style="background-image: url(https://bloximages.newyork1.vip.townnews.com/omaha.com/content/tncms/assets/v3/editorial/d/04/d043dd03-8636-526a-afa3-596143d3cee5/5eaaec5b001a4.preview.jpg?crop=1763%2C992%2C0%2C91&resize=1120%2C630&order=crop%2Cresize)"></div></a>
	<div class="content">
		<div class="card-title"><a href="https://www.omaha.com/livewellnebraska/fourth-nebraska-prison-worker-tests-positive-for-coronavirus/article_d043dd03-8636-526a-afa3-596143d3cee5.html">Fourth Nebraska prison worker tests positive for coronavirus</a></div>
		<div class="card-excerpt">This is the third worker at the State Penitentiary to test positive. The fourth employee worked at the Diagnostic & Evaluation Center in Lincoln.</div>
		<div class="card-meta">
			<span class="card-provider">Omaha.com</span> • <span class="card-date">4/30/2020</span>
		</div>
	</div>
  </div>
</div>

</div>

