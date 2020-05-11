---
category: stats
title: "US - Utah State Coronavirus (COVID-19) Live Stats"
excerpt: "Live stats of COVID-19 in US-Utah. Total Cases: 6298 (+201), Deaths: 69 (+5), Recoveries: 2185(-)."
publishedDateTime: 2020-05-10T05:45:41Z
updatedDateTime: 2020-05-10T05:45:41Z
webUrl: "https://smartable.ai/apps/coronavirus/stats/us-ut/"
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
  - url: "https://smartable.azureedge.net/coronavirus/sites/2/2020/us-ut.jpg"
    width: 900
    height: 564
    title: "US - Utah State Coronavirus (COVID-19) Live Stats"

---
<div class="total-stats" style="text-align: center;">
    <h3>
	    <div style="font-size: 18px; font-weight: 400;">Total Confirmed Cases:</div>
	    6298 (<span class='red'>+201</span>)
    </h3>
    <h3>
	    <div style="font-size: 18px; font-weight: 400;">Total Deaths:</div>
	    69 (<span class='red'>+5</span>)
    </h3>
    <h3>
	    <div style="font-size: 18px; font-weight: 400;">Total Recovered:</div>
	    2185 (-)
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
      ['1/22/2020', 0, 0, 0],['1/23/2020', 0, 0, 0],['1/24/2020', 0, 0, 0],['1/25/2020', 0, 0, 0],['1/26/2020', 0, 0, 0],['1/27/2020', 0, 0, 0],['1/28/2020', 0, 0, 0],['1/29/2020', 0, 0, 0],['1/30/2020', 0, 0, 0],['1/31/2020', 0, 0, 0],['2/1/2020', 0, 0, 0],['2/2/2020', 0, 0, 0],['2/3/2020', 0, 0, 0],['2/4/2020', 0, 0, 0],['2/5/2020', 0, 0, 0],['2/6/2020', 0, 0, 0],['2/7/2020', 0, 0, 0],['2/8/2020', 0, 0, 0],['2/9/2020', 0, 0, 0],['2/10/2020', 0, 0, 0],['2/11/2020', 0, 0, 0],['2/12/2020', 0, 0, 0],['2/13/2020', 0, 0, 0],['2/14/2020', 0, 0, 0],['2/15/2020', 0, 0, 0],['2/16/2020', 0, 0, 0],['2/17/2020', 0, 0, 0],['2/18/2020', 0, 0, 0],['2/19/2020', 0, 0, 0],['2/20/2020', 0, 0, 0],['2/21/2020', 0, 0, 0],['2/22/2020', 0, 0, 0],['2/23/2020', 0, 0, 0],['2/24/2020', 0, 0, 0],['2/25/2020', 0, 0, 0],['2/26/2020', 0, 0, 0],['2/27/2020', 0, 0, 0],['2/28/2020', 0, 0, 0],['2/29/2020', 0, 0, 0],['3/1/2020', 0, 0, 0],['3/2/2020', 0, 0, 0],['3/3/2020', 0, 0, 0],['3/4/2020', 0, 0, 0],['3/5/2020', 0, 0, 0],['3/6/2020', 0, 0, 0],['3/7/2020', 1, 0, 0],['3/8/2020', 1, 0, 0],['3/9/2020', 1, 0, 0],['3/10/2020', 1, 0, 0],['3/11/2020', 2, 0, 0],['3/12/2020', 2, 0, 0],['3/13/2020', 6, 0, 0],['3/14/2020', 19, 0, 0],['3/15/2020', 28, 0, 0],['3/16/2020', 39, 0, 0],['3/17/2020', 51, 0, 0],['3/18/2020', 64, 0, 0],['3/19/2020', 78, 0, 0],['3/20/2020', 112, 0, 0],['3/21/2020', 136, 0, 0],['3/22/2020', 181, 1, 0],['3/23/2020', 256, 1, 0],['3/24/2020', 297, 1, 0],['3/25/2020', 346, 1, 0],['3/26/2020', 402, 1, 0],['3/27/2020', 480, 2, 0],['3/28/2020', 601, 2, 0],['3/29/2020', 709, 3, 0],['3/30/2020', 793, 3, 0],['3/31/2020', 867, 4, 0],['4/1/2020', 986, 6, 0],['4/2/2020', 1062, 6, 0],['4/3/2020', 1205, 6, 0],['4/4/2020', 1382, 7, 11],['4/5/2020', 1555, 7, 11],['4/6/2020', 1620, 12, 26],['4/7/2020', 1675, 12, 26],['4/8/2020', 1778, 12, 26],['4/9/2020', 1901, 12, 26],['4/10/2020', 2022, 16, 15],['4/11/2020', 2121, 17, 15],['4/12/2020', 2216, 17, 15],['4/13/2020', 2270, 17, 207],['4/14/2020', 2322, 18, 183],['4/15/2020', 2450, 19, 183],['4/16/2020', 2587, 20, 183],['4/17/2020', 2821, 24, 187],['4/18/2020', 2944, 26, 187],['4/19/2020', 3080, 28, 175],['4/20/2020', 3224, 29, 175],['4/21/2020', 3308, 33, 175],['4/22/2020', 3456, 35, 175],['4/23/2020', 3623, 36, 175],['4/24/2020', 3967, 37, 175],['4/25/2020', 4009, 41, 888],['4/26/2020', 4185, 42, 888],['4/27/2020', 4297, 42, 888],['4/28/2020', 4413, 45, 888],['4/29/2020', 4552, 46, 888],['4/30/2020', 4736, 47, 1939],['5/1/2020', 4855, 48, 2062],['5/2/2020', 5144, 52, 2185],['5/3/2020', 5337, 53, 2185],['5/4/2020', 5491, 53, 2185],['5/5/2020', 5631, 59, 2185],['5/6/2020', 5778, 61, 2185],['5/7/2020', 5915, 64, 2185],['5/8/2020', 6097, 64, 2185],['5/9/2020', 6298, 69, 2185],
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
      [41.6139765, -112.12478, "Bear River", 59, 1],[38.3945, -113.0123, "Beaver", 1, 0],[40.9629, -112.0953, "Davis", 327, 2],[37.8234, -112.4351, "Garfield", 3, 0],[38.6325, -109.3966, "Grand", 4, 0],[40.4743, -111.9383, "Salt Lake", 3206, 43],[37.205, -109.1623, "San Juan", 145, 3],[40.8298, -110.9984, "Summit", 385, 0],[40.4496, -112.3672, "Tooele", 76, 0],[40.0054, -111.7474, "Utah", 1318, 11],[40.4733, -111.2533, "Wasatch", 176, 1],[41.2603, -111.9522, "Weber", 175, 2],[37.0262, -112.5219, "Kane", 3, 0],[40.4344, -110.0308, "Duchesne", 8, 0],[39.3301, -110.9628, "Emery", 5, 0],[39.6561, -110.8461, "Carbon", 7, 0],[40.3695, -109.3556, "Uintah", 7, 0],[41.6124, -112.125, "Box Elder", 19, 1],[41.9116, -111.9356, "Cache", 51, 0],[37.7663, -113.0431, "Iron", 29, 1],[37.2373, -113.3471, "Washington", 103, 1],[41.0576176, -111.6183755, "Morgan", 9, 0],[39.3090085, -111.5706786, "Sanpete", 6, 0],[39.7108104, -112.7152125, "Juab", 7, 0],[39.0611744, -113.1918021, "Millard", 5, 0],[38.7333524, -111.6660725, "Sevier", 8, 0],[40.0966287, -111.5706786, "Southwest Utah", 155, 3],[38.3997408, -112.1430215, "Piute", 1, 0],
    ]);
    var options = {
      backgroundColor: {fill:'transparent',stroke:'#FFF' ,strokeWidth:0 }, 
      displayMode: 'markers',
      region: 'US-UT', 
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
      [{v:"Bear River", f:"Bear River"}, 59, 0, 58, 1, 0, 0],[{v:"Beaver", f:"Beaver"}, 1, 0, 1, 0, 0, 0],[{v:"Davis", f:"Davis"}, 327, 6, 325, 2, 0, 0],[{v:"Garfield", f:"Garfield"}, 3, 0, 3, 0, 0, 0],[{v:"Grand", f:"Grand"}, 4, 0, 3, 0, 0, 1],[{v:"Salt Lake", f:"Salt Lake"}, 3206, 102, 3163, 43, 4, 0],[{v:"San Juan", f:"San Juan"}, 145, 10, 142, 3, 1, 0],[{v:"Summit", f:"Summit"}, 385, 1, 385, 0, 0, 0],[{v:"Tooele", f:"Tooele"}, 76, 4, 76, 0, 0, 0],[{v:"Utah", f:"Utah"}, 1318, 30, 1307, 11, 0, 0],[{v:"Wasatch", f:"Wasatch"}, 176, 3, 175, 1, 0, 0],[{v:"Weber", f:"Weber"}, 175, 11, 137, 2, 0, 36],[{v:"Kane", f:"Kane"}, 3, 0, 3, 0, 0, 0],[{v:"Duchesne", f:"Duchesne"}, 8, 0, 8, 0, 0, 0],[{v:"Emery", f:"Emery"}, 5, 0, 5, 0, 0, 0],[{v:"Carbon", f:"Carbon"}, 7, 0, 5, 0, 0, 2],[{v:"Uintah", f:"Uintah"}, 7, 1, 7, 0, 0, 0],[{v:"Box Elder", f:"Box Elder"}, 19, 0, 18, 1, 0, 0],[{v:"Cache", f:"Cache"}, 51, 6, 51, 0, 0, 0],[{v:"Iron", f:"Iron"}, 29, 1, 28, 1, 0, 0],[{v:"Washington", f:"Washington"}, 103, 8, 102, 1, 0, 0],[{v:"Morgan", f:"Morgan"}, 9, 0, 9, 0, 0, 0],[{v:"Sanpete", f:"Sanpete"}, 6, 0, 6, 0, 0, 0],[{v:"Juab", f:"Juab"}, 7, 0, 7, 0, 0, 0],[{v:"Millard", f:"Millard"}, 5, 0, 5, 0, 0, 0],[{v:"Sevier", f:"Sevier"}, 8, 1, 8, 0, 0, 0],[{v:"Southwest Utah", f:"Southwest Utah"}, 155, 17, 152, 3, 0, 0],[{v:"Piute", f:"Piute"}, 1, 0, 1, 0, 0, 0],
    ]);
    data.setProperty(0, 0, 'style', 'min-width:100px');
    var table = new google.visualization.Table(document.getElementById('geo_table'));
    table.draw(data, {allowHtml: true, sortColumn: 2, sortAscending: false, width: '660px', height: '100%'});
  }
</script>

<span style="font-size: 13px">All COVID-19 data displayed on the page is available through our FREE <a href="https://developer.smartable.ai">API program</a>. This US - Utah State Coronavirus (COVID-19) Live Stats is refreshed every hour using credible data sources, including the country/state's official government website, <a href="https://en.wikipedia.org/wiki/2019%E2%80%9320_coronavirus_pandemic" target="_blank">data available on wikipedia pages</a>, latest news reports, <a href="https://systems.jhu.edu/research/public-health/ncov/" target="_blank">Johns Hopkins University CSSE 2019-nCoV Dashboard</a>, <a href="https://www.who.int/emergencies/diseases/novel-coronavirus-2019/situation-reports" target="_blank">WHO Situation Reports</a>, <a href="https://www.cdc.gov/coronavirus/2019-ncov/index.html" target="_blank">CDC Situation Updates</a>, and <a href="https://ncov.dxy.cn/ncovh5/view/pneumonia" target="_blank">DXY.cn</a>.</span>

<h2 id="news" class="center" style="margin-top: 60px; font-size: 25px;">Local Government Help Information</h2>
<div class="info center">
<a href="https://coronavirus.utah.gov/" target="_blank">Utah Department of Health</a> 800-456-7707
</div>
<h2 id="news" class="center" style="margin-top: 60px; font-size: 25px;">Trending Coronavirus News in US-Utah</h2>
<div class="row">
<div class="col-md-6 col-sm-12">
  <div class="content-card">
	<a href="https://gephardtdaily.com/breaking/utah-covid-19-update-195-new-cases-no-deaths-since-thursday/"><div class="card-image" style="background-image: url(https://gephardtdaily.com/wp-content/uploads/2020/04/COVID-19-black.jpg)"></div></a>
	<div class="content">
		<div class="card-title"><a href="https://gephardtdaily.com/breaking/utah-covid-19-update-195-new-cases-no-deaths-since-thursday/">Utah COVID-19 update: 195 new cases, no deaths since Thursday</a></div>
		<div class="card-excerpt">The Utah Department of Health on Friday released new COVID-19 numbers, revealing 195 new lab-confirmed cases, 12 more hospitalizations, and no new deaths.</div>
		<div class="card-meta">
			<span class="card-provider">Gephardt Daily</span> • <span class="card-date">5/8/2020</span>
		</div>
	</div>
  </div>
</div>
<div class="col-md-6 col-sm-12">
  <div class="content-card">
	<a href="https://www.deseret.com/utah/2020/5/6/21249626/68-got-covid-19-after-utah-county-businesses-told-sick-employees-to-work"><div class="card-image" style="background-image: url(https://cdn.vox-cdn.com/thumbor/xe7KD3GW5e7ssoRRKBHUIYyV2Fg=/0x0:3000x2000/1400x1050/filters:focal(1260x760:1740x1240):no_upscale()/cdn.vox-cdn.com/uploads/chorus_image/image/66761297/merlin_2588361.0.jpg)"></div></a>
	<div class="content">
		<div class="card-title"><a href="https://www.deseret.com/utah/2020/5/6/21249626/68-got-covid-19-after-utah-county-businesses-told-sick-employees-to-work">68 got COVID-19 after Utah County businesses told sick employees to work</a></div>
		<div class="card-excerpt">Utah County officials aren’t disclosing the name of two businesses found in violation of COVID-19 prevention guidelines — including telling employees confirmed to be diagnosed with COVID-19 to still report to work before the required quarantine period ended.</div>
		<div class="card-meta">
			<span class="card-provider">deseret</span> • <span class="card-date">5/6/2020</span>
		</div>
	</div>
  </div>
</div>
<div class="col-md-6 col-sm-12">
  <div class="content-card">
	<a href="https://www.ksl.com/article/46749664/utah-reports-highest-single-day-covid-19-death-total-of-6"><div class="card-image" style="background-image: url(https://img.ksl.com/slc/2778/277888/27788806.jpg?filter=ksl/responsive_story_lg)"></div></a>
	<div class="content">
		<div class="card-title"><a href="https://www.ksl.com/article/46749664/utah-reports-highest-single-day-covid-19-death-total-of-6">Utah reports highest single-day COVID-19 death total of 6</a></div>
		<div class="card-excerpt">Utah’s total number of COVID-19 cases has increased by 132 from Monday, with six new reported deaths, according to the Utah Department of Health.</div>
		<div class="card-meta">
			<span class="card-provider">KSL</span> • <span class="card-date">5/5/2020</span>
		</div>
	</div>
  </div>
</div>
<div class="col-md-6 col-sm-12">
  <div class="content-card">
	<a href="https://www.ksl.com/article/46749664/utah-sees-132-new-cases-of-covid-19-6-new-deaths-in-states-deadliest-day-so-far"><div class="card-image" style="background-image: url(https://img.ksl.com/slc/2778/277888/27788806.jpg?filter=ksl/responsive_story_lg)"></div></a>
	<div class="content">
		<div class="card-title"><a href="https://www.ksl.com/article/46749664/utah-sees-132-new-cases-of-covid-19-6-new-deaths-in-states-deadliest-day-so-far">Utah sees 132 new cases of COVID-19, 6 new deaths in state's deadliest day so far</a></div>
		<div class="card-excerpt">Utah’s total number of COVID-19 cases has increased by 132 from Monday, with six new reported deaths, according to the Utah Department of Health.</div>
		<div class="card-meta">
			<span class="card-provider">KSL</span> • <span class="card-date">5/5/2020</span>
		</div>
	</div>
  </div>
</div>
<div class="col-md-6 col-sm-12">
  <div class="content-card">
	<a href="https://www.foxnews.com/us/utah-gives-coronavirus-mask-everyone-state"><div class="card-image" style="background-image: url(https://static.foxnews.com/foxnews.com/content/uploads/2020/04/masks-1.jpg)"></div></a>
	<div class="content">
		<div class="card-title"><a href="https://www.foxnews.com/us/utah-gives-coronavirus-mask-everyone-state">Utah aims to give coronavirus mask to every resident in state</a></div>
		<div class="card-excerpt">Utah will enter into a public-private partnership to provide a free mask for every resident in the state who doesn't have one, Gov. Gary Herbert’s office said Wednesday.</div>
		<div class="card-meta">
			<span class="card-provider">Fox News</span> • <span class="card-date">4/29/2020</span>
		</div>
	</div>
  </div>
</div>

</div>

