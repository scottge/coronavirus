---
category: stats
title: "US - Pennsylvania State Coronavirus (COVID-19) Live Stats"
excerpt: "Live stats of COVID-19 in US-Pennsylvania. Total Cases: 58686 (+1215), Deaths: 3798 (+78), Recoveries: 1080(-)."
publishedDateTime: 2020-05-10T05:45:41Z
updatedDateTime: 2020-05-10T05:45:41Z
webUrl: "https://smartable.ai/apps/coronavirus/stats/us-pa/"
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
  - url: "https://smartable.azureedge.net/coronavirus/sites/2/2020/us-pa.jpg"
    width: 900
    height: 564
    title: "US - Pennsylvania State Coronavirus (COVID-19) Live Stats"

---
<div class="total-stats" style="text-align: center;">
    <h3>
	    <div style="font-size: 18px; font-weight: 400;">Total Confirmed Cases:</div>
	    58686 (<span class='red'>+1215</span>)
    </h3>
    <h3>
	    <div style="font-size: 18px; font-weight: 400;">Total Deaths:</div>
	    3798 (<span class='red'>+78</span>)
    </h3>
    <h3>
	    <div style="font-size: 18px; font-weight: 400;">Total Recovered:</div>
	    1080 (-)
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
      ['1/22/2020', 0, 0, 0],['1/23/2020', 0, 0, 0],['1/24/2020', 0, 0, 0],['1/25/2020', 0, 0, 0],['1/26/2020', 0, 0, 0],['1/27/2020', 0, 0, 0],['1/28/2020', 0, 0, 0],['1/29/2020', 0, 0, 0],['1/30/2020', 0, 0, 0],['1/31/2020', 0, 0, 0],['2/1/2020', 0, 0, 0],['2/2/2020', 0, 0, 0],['2/3/2020', 0, 0, 0],['2/4/2020', 0, 0, 0],['2/5/2020', 0, 0, 0],['2/6/2020', 0, 0, 0],['2/7/2020', 0, 0, 0],['2/8/2020', 0, 0, 0],['2/9/2020', 0, 0, 0],['2/10/2020', 0, 0, 0],['2/11/2020', 0, 0, 0],['2/12/2020', 0, 0, 0],['2/13/2020', 0, 0, 0],['2/14/2020', 0, 0, 0],['2/15/2020', 0, 0, 0],['2/16/2020', 0, 0, 0],['2/17/2020', 0, 0, 0],['2/18/2020', 0, 0, 0],['2/19/2020', 0, 0, 0],['2/20/2020', 0, 0, 0],['2/21/2020', 0, 0, 0],['2/22/2020', 0, 0, 0],['2/23/2020', 0, 0, 0],['2/24/2020', 0, 0, 0],['2/25/2020', 0, 0, 0],['2/26/2020', 0, 0, 0],['2/27/2020', 0, 0, 0],['2/28/2020', 0, 0, 0],['2/29/2020', 0, 0, 0],['3/1/2020', 0, 0, 0],['3/2/2020', 0, 0, 0],['3/3/2020', 0, 0, 0],['3/4/2020', 0, 0, 0],['3/5/2020', 0, 0, 0],['3/6/2020', 2, 0, 0],['3/7/2020', 2, 0, 0],['3/8/2020', 6, 0, 0],['3/9/2020', 7, 0, 0],['3/10/2020', 12, 0, 0],['3/11/2020', 15, 0, 0],['3/12/2020', 22, 0, 0],['3/13/2020', 41, 0, 0],['3/14/2020', 47, 0, 0],['3/15/2020', 66, 0, 0],['3/16/2020', 82, 0, 0],['3/17/2020', 115, 0, 0],['3/18/2020', 157, 1, 0],['3/19/2020', 206, 1, 0],['3/20/2020', 311, 1, 0],['3/21/2020', 399, 2, 0],['3/22/2020', 516, 5, 0],['3/23/2020', 698, 6, 0],['3/24/2020', 946, 8, 0],['3/25/2020', 1284, 15, 0],['3/26/2020', 1813, 18, 0],['3/27/2020', 2345, 23, 0],['3/28/2020', 2910, 35, 0],['3/29/2020', 3466, 43, 0],['3/30/2020', 4155, 51, 0],['3/31/2020', 4994, 67, 0],['4/1/2020', 6063, 74, 58],['4/2/2020', 7345, 92, 67],['4/3/2020', 8570, 102, 67],['4/4/2020', 10444, 136, 76],['4/5/2020', 11589, 151, 76],['4/6/2020', 13206, 179, 76],['4/7/2020', 14956, 250, 134],['4/8/2020', 16746, 319, 134],['4/9/2020', 18633, 365, 170],['4/10/2020', 20408, 449, 170],['4/11/2020', 21942, 530, 179],['4/12/2020', 22997, 557, 179],['4/13/2020', 24336, 592, 264],['4/14/2020', 25591, 679, 264],['4/15/2020', 26804, 751, 264],['4/16/2020', 28314, 848, 317],['4/17/2020', 30031, 921, 340],['4/18/2020', 31795, 1105, 373],['4/19/2020', 32902, 1276, 466],['4/20/2020', 34005, 1357, 466],['4/21/2020', 35339, 1599, 466],['4/22/2020', 36212, 1651, 586],['4/23/2020', 38379, 1702, 603],['4/24/2020', 39410, 1734, 603],['4/25/2020', 41697, 1818, 650],['4/26/2020', 42708, 1849, 692],['4/27/2020', 43561, 1919, 692],['4/28/2020', 45139, 2068, 765],['4/29/2020', 46330, 2385, 765],['4/30/2020', 47999, 2541, 765],['5/1/2020', 49446, 2654, 801],['5/2/2020', 50915, 2776, 916],['5/3/2020', 52048, 2832, 916],['5/4/2020', 52922, 2852, 983],['5/5/2020', 53907, 3196, 983],['5/6/2020', 54898, 3349, 1044],['5/7/2020', 56002, 3592, 1080],['5/8/2020', 57471, 3720, 1080],['5/9/2020', 58686, 3798, 1080],
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
      [39.9813, -77.2493, "Adams", 156, 5],[40.417, -80.0544, "Allegheny", 1486, 120],[40.5938, -79.5564, "Armstrong", 55, 3],[40.7355, -80.3091, "Beaver", 482, 78],[40.3711, -75.6306, "Berks", 3257, 169],[40.5082, -78.4007, "Blair", 28, 0],[41.6704, -76.2623, "Bradford", 38, 5],[40.4108, -75.2479, "Bucks", 3852, 336],[40.9104, -79.9157, "Butler", 194, 6],[40.6048, -78.7072, "Cambria", 42, 2],[41.3448, -78.134, "Cameron", 2, 0],[40.916, -75.9657, "Carbon", 195, 16],[40.8266, -77.8226, "Centre", 117, 2],[39.9343, -75.5306, "Chester", 1774, 183],[41.021, -79.2782, "Clarion", 23, 1],[40.8745, -78.7274, "Clearfield", 24, 0],[41.0026, -76.4561, "Columbia", 323, 28],[41.562, -80.2261, "Crawford", 20, 0],[40.2311, -77.0727, "Cumberland", 425, 33],[40.2657, -76.7126, "Dauphin", 797, 37],[39.9078, -75.3879, "Delaware", 4836, 394],[42.0469, -80.2765, "Erie", 120, 2],[40.0188, -79.891, "Fayette", 85, 4],[39.7329, -77.7247, "Franklin", 478, 12],[39.9111, -80.432, "Greene", 27, 1],[40.6472, -78.1957, "Huntingdon", 119, 0],[40.8197, -78.8297, "Indiana", 76, 5],[40.5686, -77.4047, "Juniata", 93, 1],[41.4846, -75.666, "Lackawanna", 1134, 115],[40.2141, -76.1605, "Lancaster", 2185, 222],[41.0955, -80.4953, "Lawrence", 69, 7],[40.3412, -76.4228, "Lebanon", 805, 16],[40.5165, -75.5545, "Lehigh", 3169, 120],[41.2867, -75.8967, "Luzerne", 2356, 120],[41.2472, -76.9184, "Lycoming", 127, 4],[41.3502, -80.0837, "Mercer", 73, 2],[40.5549, -77.6168, "Mifflin", 50, 0],[41.0458, -75.2479, "Monroe", 1206, 63],[40.229, -75.3879, "Montgomery", 5116, 523],[40.9615, -76.612, "Montour", 50, 0],[40.8811, -75.1861, "Northampton", 2429, 158],[41.085, -76.8646, "Northumberland", 119, 0],[40.3952, -77.0277, "Perry", 34, 1],[39.9526, -75.1652, "Philadelphia", 17881, 891],[41.3666, -74.6997, "Pike", 427, 21],[41.7768, -78.1552, "Potter", 4, 0],[40.6302, -76.3912, "Schuylkill", 437, 13],[40.7625, -76.9408, "Snyder", 33, 1],[40.2027, -78.9293, "Somerset", 32, 1],[41.9506, -75.6095, "Susquehanna", 87, 13],[41.9868, -76.9396, "Tioga", 16, 2],[40.8805, -76.9842, "Union", 40, 1],[41.4716, -79.9311, "Venango", 7, 0],[41.701, -79.0298, "Warren", 1, 1],[40.332, -80.256, "Washington", 124, 4],[41.6739, -75.2479, "Wayne", 116, 5],[40.4145, -79.5729, "Westmoreland", 415, 30],[40.1542, -76.7515, "York", 767, 14],[40.1599, -78.232, "Bedford", 29, 1],[41.4937, -79.448, "Forest", 7, 0],[41.6119, -76.0458, "Wyoming", 30, 2],[41.0094, -77.5306, "Clinton", 41, 0],[41.418, -76.492, "Sullivan", 1, 0],[39.932, -77.9958, "Fulton", 8, 1],[41.357, -78.6101, "Elk", 5, 1],[41.1615, -79.0827, "Jefferson", 7, 0],[41.9604, -78.6413, "McKean", 6, 1],
    ]);
    var options = {
      backgroundColor: {fill:'transparent',stroke:'#FFF' ,strokeWidth:0 }, 
      displayMode: 'markers',
      region: 'US-PA', 
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
      [{v:"Adams", f:"Adams"}, 156, 2, 151, 5, 0, 0],[{v:"Allegheny", f:"Allegheny"}, 1486, 31, 1366, 120, 1, 0],[{v:"Armstrong", f:"Armstrong"}, 55, 0, 52, 3, 0, 0],[{v:"Beaver", f:"Beaver"}, 482, 3, 404, 78, 0, 0],[{v:"Berks", f:"Berks"}, 3257, 67, 3059, 169, 1, 29],[{v:"Blair", f:"Blair"}, 28, 0, 28, 0, 0, 0],[{v:"Bradford", f:"Bradford"}, 38, 1, 33, 5, 0, 0],[{v:"Bucks", f:"Bucks"}, 3852, 102, 3023, 336, 5, 493],[{v:"Butler", f:"Butler"}, 194, 2, 188, 6, 0, 0],[{v:"Cambria", f:"Cambria"}, 42, 2, 40, 2, 0, 0],[{v:"Cameron", f:"Cameron"}, 2, 0, 2, 0, 0, 0],[{v:"Carbon", f:"Carbon"}, 195, 3, 179, 16, 0, 0],[{v:"Centre", f:"Centre"}, 117, 0, 115, 2, 0, 0],[{v:"Chester", f:"Chester"}, 1774, 46, 1591, 183, 7, 0],[{v:"Clarion", f:"Clarion"}, 23, 0, 22, 1, 0, 0],[{v:"Clearfield", f:"Clearfield"}, 24, 0, 24, 0, 0, 0],[{v:"Columbia", f:"Columbia"}, 323, 16, 295, 28, 7, 0],[{v:"Crawford", f:"Crawford"}, 20, 0, 20, 0, 0, 0],[{v:"Cumberland", f:"Cumberland"}, 425, 11, 392, 33, 2, 0],[{v:"Dauphin", f:"Dauphin"}, 797, 33, 718, 37, 0, 42],[{v:"Delaware", f:"Delaware"}, 4836, 156, 4442, 394, 12, 0],[{v:"Erie", f:"Erie"}, 120, 7, 79, 2, 0, 39],[{v:"Fayette", f:"Fayette"}, 85, 1, 81, 4, 0, 0],[{v:"Franklin", f:"Franklin"}, 478, 26, 466, 12, 1, 0],[{v:"Greene", f:"Greene"}, 27, 0, 26, 1, 0, 0],[{v:"Huntingdon", f:"Huntingdon"}, 119, 2, 119, 0, 0, 0],[{v:"Indiana", f:"Indiana"}, 76, 1, 71, 5, 0, 0],[{v:"Juniata", f:"Juniata"}, 93, 0, 92, 1, 0, 0],[{v:"Lackawanna", f:"Lackawanna"}, 1134, 20, 1019, 115, 2, 0],[{v:"Lancaster", f:"Lancaster"}, 2185, 63, 1963, 222, 0, 0],[{v:"Lawrence", f:"Lawrence"}, 69, 0, 62, 7, 0, 0],[{v:"Lebanon", f:"Lebanon"}, 805, 8, 789, 16, 0, 0],[{v:"Lehigh", f:"Lehigh"}, 3169, 29, 3049, 120, 6, 0],[{v:"Luzerne", f:"Luzerne"}, 2356, 9, 2236, 120, 0, 0],[{v:"Lycoming", f:"Lycoming"}, 127, 18, 123, 4, 0, 0],[{v:"Mercer", f:"Mercer"}, 73, 3, 71, 2, 1, 0],[{v:"Mifflin", f:"Mifflin"}, 50, 0, 50, 0, 0, 0],[{v:"Monroe", f:"Monroe"}, 1206, 8, 1143, 63, 0, 0],[{v:"Montgomery", f:"Montgomery"}, 5116, 79, 4593, 523, 8, 0],[{v:"Montour", f:"Montour"}, 50, 0, 50, 0, 0, 0],[{v:"Northampton", f:"Northampton"}, 2429, 39, 2271, 158, 5, 0],[{v:"Northumberland", f:"Northumberland"}, 119, 1, 119, 0, 0, 0],[{v:"Perry", f:"Perry"}, 34, 0, 33, 1, 0, 0],[{v:"Philadelphia", f:"Philadelphia"}, 17881, 364, 16990, 891, 16, 0],[{v:"Pike", f:"Pike"}, 427, 5, 406, 21, 0, 0],[{v:"Potter", f:"Potter"}, 4, 0, 4, 0, 0, 0],[{v:"Schuylkill", f:"Schuylkill"}, 437, 7, 424, 13, 0, 0],[{v:"Snyder", f:"Snyder"}, 33, 0, 32, 1, 0, 0],[{v:"Somerset", f:"Somerset"}, 32, 0, 31, 1, 0, 0],[{v:"Susquehanna", f:"Susquehanna"}, 87, 0, 74, 13, 2, 0],[{v:"Tioga", f:"Tioga"}, 16, 0, 14, 2, 0, 0],[{v:"Union", f:"Union"}, 40, 0, 39, 1, 0, 0],[{v:"Venango", f:"Venango"}, 7, 0, 7, 0, 0, 0],[{v:"Warren", f:"Warren"}, 1, 0, 0, 1, 0, 0],[{v:"Washington", f:"Washington"}, 124, 3, 120, 4, 0, 0],[{v:"Wayne", f:"Wayne"}, 116, 3, 111, 5, 0, 0],[{v:"Westmoreland", f:"Westmoreland"}, 415, 2, 385, 30, 0, 0],[{v:"York", f:"York"}, 767, 14, 753, 14, 0, 0],[{v:"Bedford", f:"Bedford"}, 29, 1, 28, 1, 0, 0],[{v:"Forest", f:"Forest"}, 7, 0, 7, 0, 0, 0],[{v:"Wyoming", f:"Wyoming"}, 30, 2, 28, 2, 0, 0],[{v:"Clinton", f:"Clinton"}, 41, 4, 41, 0, 0, 0],[{v:"Sullivan", f:"Sullivan"}, 1, 0, 1, 0, 0, 0],[{v:"Fulton", f:"Fulton"}, 8, 1, 7, 1, 1, 0],[{v:"Elk", f:"Elk"}, 5, 0, 4, 1, 0, 0],[{v:"Jefferson", f:"Jefferson"}, 7, 0, 7, 0, 0, 0],[{v:"McKean", f:"McKean"}, 6, 0, 5, 1, 0, 0],
    ]);
    data.setProperty(0, 0, 'style', 'min-width:100px');
    var table = new google.visualization.Table(document.getElementById('geo_table'));
    table.draw(data, {allowHtml: true, sortColumn: 2, sortAscending: false, width: '660px', height: '100%'});
  }
</script>

<span style="font-size: 13px">All COVID-19 data displayed on the page is available through our FREE <a href="https://developer.smartable.ai">API program</a>. This US - Pennsylvania State Coronavirus (COVID-19) Live Stats is refreshed every hour using credible data sources, including the country/state's official government website, <a href="https://en.wikipedia.org/wiki/2019%E2%80%9320_coronavirus_pandemic" target="_blank">data available on wikipedia pages</a>, latest news reports, <a href="https://systems.jhu.edu/research/public-health/ncov/" target="_blank">Johns Hopkins University CSSE 2019-nCoV Dashboard</a>, <a href="https://www.who.int/emergencies/diseases/novel-coronavirus-2019/situation-reports" target="_blank">WHO Situation Reports</a>, <a href="https://www.cdc.gov/coronavirus/2019-ncov/index.html" target="_blank">CDC Situation Updates</a>, and <a href="https://ncov.dxy.cn/ncovh5/view/pneumonia" target="_blank">DXY.cn</a>.</span>

<h2 id="news" class="center" style="margin-top: 60px; font-size: 25px;">Local Government Help Information</h2>
<div class="info center">
<a href="https://www.health.pa.gov/topics/disease/Pages/Coronavirus.aspx" target="_blank">Pennsylvania Department of Health</a>
</div>
<h2 id="news" class="center" style="margin-top: 60px; font-size: 25px;">Trending Coronavirus News in US-Pennsylvania</h2>
<div class="row">
<div class="col-md-6 col-sm-12">
  <div class="content-card">
	<a href="https://www.pennlive.com/coronavirus/2020/05/coronavirus-cases-in-pennsylvania-55316-diagnosed-3688-deaths.html"><div class="card-image" style="background-image: url(https://arc-anglerfish-arc2-prod-advancelocal.s3.amazonaws.com/public/XWE3GCAUCNE43HHJYTRSH62TNQ.jpg)"></div></a>
	<div class="content">
		<div class="card-title"><a href="https://www.pennlive.com/coronavirus/2020/05/coronavirus-cases-in-pennsylvania-55316-diagnosed-3688-deaths.html">Coronavirus cases in Pennsylvania: 55,316 diagnoses, 3,688 deaths</a></div>
		<div class="card-excerpt">The Department of Health reported 1,078 new coronavirus cases Saturday, raising the statewide total to 55,316 infected in about two months. Across the state, 3,688 pe</div>
		<div class="card-meta">
			<span class="card-provider">Penn Live</span> • <span class="card-date">5/9/2020</span>
		</div>
	</div>
  </div>
</div>
<div class="col-md-6 col-sm-12">
  <div class="content-card">
	<a href="https://www.wpxi.com/news/top-stories/live-updates-coronavirus-pennsylvania-what-you-need-know-wednesday/W6C5SQYXAVBKREVLJDLXQN5VTY/"><div class="card-image" style="background-image: url(https://d1hfln2sfez66z.cloudfront.net/04-01-2020/t_96eaf797ad874d2bb16470ccf163c8c7_name_451D86B54B454A58B5F2731A29F7E7EB.jpg)"></div></a>
	<div class="content">
		<div class="card-title"><a href="https://www.wpxi.com/news/top-stories/live-updates-coronavirus-pennsylvania-what-you-need-know-wednesday/W6C5SQYXAVBKREVLJDLXQN5VTY/">TIMELINE: Pennsylvania coronavirus updates May 7</a></div>
		<div class="card-excerpt">During Gov. Tom Wolf’s press conference about relief for renters and homeowners, he said he’s making an announcement tomorrow about more openings in Pennsylvania.</div>
		<div class="card-meta">
			<span class="card-provider">WPXI</span> • <span class="card-date">5/8/2020</span>
		</div>
	</div>
  </div>
</div>
<div class="col-md-6 col-sm-12">
  <div class="content-card">
	<a href="https://www.newsweek.com/wrongful-death-lawsuit-filed-against-pennsylvania-meat-plant-over-coronavirus-deaths-1502662"><div class="card-image" style="background-image: url(https://d.newsweek.com/en/full/1588201/jbs-greenley-colorado.jpg)"></div></a>
	<div class="content">
		<div class="card-title"><a href="https://www.newsweek.com/wrongful-death-lawsuit-filed-against-pennsylvania-meat-plant-over-coronavirus-deaths-1502662">Wrongful Death Lawsuit Filed Against Pennsylvania Meat Plant Over Coronavirus Deaths</a></div>
		<div class="card-excerpt">The lawsuit against JBS claimed the company did not implement adequate safety measures at its Souderton, Pennsylvania, facility to protect against coronavirus transmission.</div>
		<div class="card-meta">
			<span class="card-provider">Newsweek</span> • <span class="card-date">5/7/2020</span>
		</div>
	</div>
  </div>
</div>
<div class="col-md-6 col-sm-12">
  <div class="content-card">
	<a href="https://www.wpxi.com/news/top-stories/live-updates-coronavirus-pennsylvania-what-you-need-know-wednesday/W6C5SQYXAVBKREVLJDLXQN5VTY/"><div class="card-image" style="background-image: url(https://d1hfln2sfez66z.cloudfront.net/04-01-2020/t_96eaf797ad874d2bb16470ccf163c8c7_name_451D86B54B454A58B5F2731A29F7E7EB.jpg)"></div></a>
	<div class="content">
		<div class="card-title"><a href="https://www.wpxi.com/news/top-stories/live-updates-coronavirus-pennsylvania-what-you-need-know-wednesday/W6C5SQYXAVBKREVLJDLXQN5VTY/">TIMELINE: Pennsylvania coronavirus updates May 6</a></div>
		<div class="card-excerpt">Channel 11 News is committed to keeping you informed about the coronavirus, the impact on our community and your lives. Below you’ll find all of today’s updates, including the latest numbers and information from local and state officials.</div>
		<div class="card-meta">
			<span class="card-provider">WPXI</span> • <span class="card-date">5/7/2020</span>
		</div>
	</div>
  </div>
</div>
<div class="col-md-6 col-sm-12">
  <div class="content-card">
	<a href="https://www.inquirer.com/news/philadelphia-police-lt-james-walker-coronavirus-death-20200406.html"><div class="card-image" style="background-image: url(https://www.inquirer.com/resizer/pVsL9AkUrCstOxQSP67jW5a-JpI=/1200x0/center/middle/www.inquirer.com/resizer/_-pOWL2fu4mK0waFufjhT9yEXPo=/1200x0/center/middle/arc-anglerfish-arc2-prod-pmn.s3.amazonaws.com/public/FE4ENZIWDRC3BGVZ5M6YPZAX2M.jpg)"></div></a>
	<div class="content">
		<div class="card-title"><a href="https://www.inquirer.com/news/philadelphia-police-lt-james-walker-coronavirus-death-20200406.html">Coronavirus Latest: Widow Of Philadelphia Police Lt. James Walker, Who Died Of COVID-19, Has Message As Talk About Reopening Ramps Up</a></div>
		<div class="card-excerpt">Lt. James Walker was one of the early casualties of the coronavirus pandemic in Philadelphia. Now, his widow has a message she wants everyone to hear. Walker died a month ago this week and with so much talk about reopening,</div>
		<div class="card-meta">
			<span class="card-provider">CBS Boston / WBZ</span> • <span class="card-date">5/6/2020</span>
		</div>
	</div>
  </div>
</div>
<div class="col-md-6 col-sm-12">
  <div class="content-card">
	<a href="https://www.newsweek.com/pennsylvania-chris-dush-tom-wolf-nazi-coronavirus-1501960"><div class="card-image" style="background-image: url(https://d.newsweek.com/en/full/1587298/wolf.jpg)"></div></a>
	<div class="content">
		<div class="card-title"><a href="https://www.newsweek.com/pennsylvania-chris-dush-tom-wolf-nazi-coronavirus-1501960">GOP Pennsylvania Lawmaker Compares Governor Tom Wolf's Handling of Coronavirus to the Nazi Party</a></div>
		<div class="card-excerpt">Rep. Cris Dush accused Wolf's withholding of information to the press as resembling a page out of a "socialist playbook."</div>
		<div class="card-meta">
			<span class="card-provider">Newsweek</span> • <span class="card-date">5/5/2020</span>
		</div>
	</div>
  </div>
</div>
<div class="col-md-6 col-sm-12">
  <div class="content-card">
	<a href="https://triblive.com/news/pennsylvania/pennsylvania-reports-14-new-coronavirus-deaths-825-new-cases/"><div class="card-image" style="background-image: url(https://triblive.com/wp-content/uploads/2020/05/2612548_web1_2591634-629d5c09437b455bb8f8548847932300.jpg)"></div></a>
	<div class="content">
		<div class="card-title"><a href="https://triblive.com/news/pennsylvania/pennsylvania-reports-14-new-coronavirus-deaths-825-new-cases/">Pennsylvania reports 825 new coronavirus cases, eclipses 50,000</a></div>
		<div class="card-excerpt">Pennsylvania health officials will decide this week whether to share coronavirus-related data from nursing and personal care homes with the public, which is where the majority of covid-19 deaths are occuring.</div>
		<div class="card-meta">
			<span class="card-provider">TribLIVE.com</span> • <span class="card-date">5/4/2020</span>
		</div>
	</div>
  </div>
</div>
<div class="col-md-6 col-sm-12">
  <div class="content-card">
	<a href="https://www.cbsnews.com/news/coronavirus-pennsylvania-doctor-state-covid-19-test-philadelphia/"><div class="card-image" style="background-image: url(https://cbsnews2.cbsistatic.com/hub/i/r/2020/04/30/1eb4cabf-a1ab-407b-8943-7abde1107a64/thumbnail/1200x630/07b35c79152d1f2ddf68a1650e8b4b5a/cbsn-fusion-philadelphia-doctor-takes-to-the-streets-to-provide-free-covid-19-testing-thumbnail-477573-640x360.jpg)"></div></a>
	<div class="content">
		<div class="card-title"><a href="https://www.cbsnews.com/news/coronavirus-pennsylvania-doctor-state-covid-19-test-philadelphia/">Pennsylvania doctor takes state's COVID-19 testing problem into her own hands</a></div>
		<div class="card-excerpt">In addition, the series will report on how states are responding to testing needs, whether they are developing testing plans, and what testing benchmarks they are looking for as these states make the decision to re-open.</div>
		<div class="card-meta">
			<span class="card-provider">CBS News</span> • <span class="card-date">4/30/2020</span>
		</div>
	</div>
  </div>
</div>
<div class="col-md-6 col-sm-12">
  <div class="content-card">
	<a href="https://www.wpxi.com/news/top-stories/live-updates-coronavirus-pennsylvania-what-you-need-know-wednesday/W6C5SQYXAVBKREVLJDLXQN5VTY/"><div class="card-image" style="background-image: url(https://d1hfln2sfez66z.cloudfront.net/04-01-2020/t_96eaf797ad874d2bb16470ccf163c8c7_name_451D86B54B454A58B5F2731A29F7E7EB.jpg)"></div></a>
	<div class="content">
		<div class="card-title"><a href="https://www.wpxi.com/news/top-stories/live-updates-coronavirus-pennsylvania-what-you-need-know-wednesday/W6C5SQYXAVBKREVLJDLXQN5VTY/">TIMELINE: Pennsylvania coronavirus updates April 29</a></div>
		<div class="card-excerpt">Channel 11 News is committed to keeping you informed about the coronavirus, the impact on our community and your lives. Below you’ll find all of today’s updates, including the latest numbers and information from local and state officials.</div>
		<div class="card-meta">
			<span class="card-provider">WPXI</span> • <span class="card-date">4/30/2020</span>
		</div>
	</div>
  </div>
</div>
<div class="col-md-6 col-sm-12">
  <div class="content-card">
	<a href="https://www.sfgate.com/news/article/Pennsylvania-adds-479-COVID-19-deaths-as-total-15234411.php"><div class="card-image" style="background-image: url(https://d29xw9s9x32j3w.cloudfront.net/players/library/placeholder.png)"></div></a>
	<div class="content">
		<div class="card-title"><a href="https://www.sfgate.com/news/article/Pennsylvania-adds-479-COVID-19-deaths-as-total-15234411.php">Pennsylvania adds 479 COVID-19 deaths as total tops 2,000</a></div>
		<div class="card-excerpt">The Pennsylvania Department of Health on Wednesday reported 479 new COVID-19 deaths, raising the state's overall death toll to more than 2,000. The newly reported deaths occurred over the past two weeks.</div>
		<div class="card-meta">
			<span class="card-provider">SFGate</span> • <span class="card-date">4/29/2020</span>
		</div>
	</div>
  </div>
</div>

</div>

