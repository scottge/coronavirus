---
category: stats
title: "US - Pennsylvania State Coronavirus (COVID-19) Live Stats"
excerpt: "Live stats of COVID-19 in US-Pennsylvania. Total Cases: 61346 (+770), Deaths: 3917 (+72), Recoveries: 6313(+5213)."
publishedDateTime: 2020-05-12T19:45:10Z
updatedDateTime: 2020-05-12T19:45:10Z
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
	    61346 (<span class='red'>+770</span>)
    </h3>
    <h3>
	    <div style="font-size: 18px; font-weight: 400;">Total Deaths:</div>
	    3917 (<span class='red'>+72</span>)
    </h3>
    <h3>
	    <div style="font-size: 18px; font-weight: 400;">Total Recovered:</div>
	    6313 (<span class='green'>+5213</span>)
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
      ['1/22/2020', 0, 0, 0],['1/23/2020', 0, 0, 0],['1/24/2020', 0, 0, 0],['1/25/2020', 0, 0, 0],['1/26/2020', 0, 0, 0],['1/27/2020', 0, 0, 0],['1/28/2020', 0, 0, 0],['1/29/2020', 0, 0, 0],['1/30/2020', 0, 0, 0],['1/31/2020', 0, 0, 0],['2/1/2020', 0, 0, 0],['2/2/2020', 0, 0, 0],['2/3/2020', 0, 0, 0],['2/4/2020', 0, 0, 0],['2/5/2020', 0, 0, 0],['2/6/2020', 0, 0, 0],['2/7/2020', 0, 0, 0],['2/8/2020', 0, 0, 0],['2/9/2020', 0, 0, 0],['2/10/2020', 0, 0, 0],['2/11/2020', 0, 0, 0],['2/12/2020', 0, 0, 0],['2/13/2020', 0, 0, 0],['2/14/2020', 0, 0, 0],['2/15/2020', 0, 0, 0],['2/16/2020', 0, 0, 0],['2/17/2020', 0, 0, 0],['2/18/2020', 0, 0, 0],['2/19/2020', 0, 0, 0],['2/20/2020', 0, 0, 0],['2/21/2020', 0, 0, 0],['2/22/2020', 0, 0, 0],['2/23/2020', 0, 0, 0],['2/24/2020', 0, 0, 0],['2/25/2020', 0, 0, 0],['2/26/2020', 0, 0, 0],['2/27/2020', 0, 0, 0],['2/28/2020', 0, 0, 0],['2/29/2020', 0, 0, 0],['3/1/2020', 0, 0, 0],['3/2/2020', 0, 0, 0],['3/3/2020', 0, 0, 0],['3/4/2020', 0, 0, 0],['3/5/2020', 0, 0, 0],['3/6/2020', 2, 0, 0],['3/7/2020', 2, 0, 0],['3/8/2020', 6, 0, 0],['3/9/2020', 7, 0, 0],['3/10/2020', 12, 0, 0],['3/11/2020', 15, 0, 0],['3/12/2020', 22, 0, 0],['3/13/2020', 41, 0, 0],['3/14/2020', 47, 0, 0],['3/15/2020', 66, 0, 0],['3/16/2020', 82, 0, 0],['3/17/2020', 115, 0, 0],['3/18/2020', 157, 1, 0],['3/19/2020', 206, 1, 0],['3/20/2020', 311, 1, 0],['3/21/2020', 399, 2, 0],['3/22/2020', 516, 5, 0],['3/23/2020', 698, 6, 0],['3/24/2020', 946, 8, 0],['3/25/2020', 1284, 15, 0],['3/26/2020', 1813, 18, 0],['3/27/2020', 2345, 23, 0],['3/28/2020', 2910, 35, 0],['3/29/2020', 3466, 43, 0],['3/30/2020', 4155, 51, 0],['3/31/2020', 4994, 67, 0],['4/1/2020', 6063, 74, 58],['4/2/2020', 7345, 92, 67],['4/3/2020', 8570, 102, 67],['4/4/2020', 10444, 136, 76],['4/5/2020', 11589, 151, 76],['4/6/2020', 13206, 179, 76],['4/7/2020', 14956, 250, 134],['4/8/2020', 16746, 319, 134],['4/9/2020', 18633, 365, 170],['4/10/2020', 20408, 449, 170],['4/11/2020', 21942, 530, 179],['4/12/2020', 22997, 557, 179],['4/13/2020', 24336, 592, 264],['4/14/2020', 25591, 679, 264],['4/15/2020', 26804, 751, 264],['4/16/2020', 28314, 848, 317],['4/17/2020', 30031, 921, 340],['4/18/2020', 31795, 1105, 373],['4/19/2020', 32902, 1276, 466],['4/20/2020', 34005, 1357, 466],['4/21/2020', 35339, 1599, 466],['4/22/2020', 36212, 1651, 586],['4/23/2020', 38379, 1702, 603],['4/24/2020', 39410, 1734, 603],['4/25/2020', 41697, 1818, 650],['4/26/2020', 42708, 1849, 692],['4/27/2020', 43561, 1919, 692],['4/28/2020', 45139, 2068, 765],['4/29/2020', 46330, 2385, 765],['4/30/2020', 47999, 2541, 765],['5/1/2020', 49446, 2654, 801],['5/2/2020', 50915, 2776, 916],['5/3/2020', 52048, 2832, 916],['5/4/2020', 52922, 2852, 983],['5/5/2020', 53907, 3196, 983],['5/6/2020', 54898, 3349, 1044],['5/7/2020', 56002, 3592, 1080],['5/8/2020', 57471, 3720, 1080],['5/9/2020', 58686, 3798, 1080],['5/10/2020', 60056, 3824, 1100],['5/11/2020', 60576, 3845, 1100],['5/12/2020', 61346, 3917, 6313],
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
      [39.9813, -77.2493, "Adams", 167, 5],[40.417, -80.0544, "Allegheny", 1511, 123],[40.5938, -79.5564, "Armstrong", 55, 5],[40.7355, -80.3091, "Beaver", 491, 78],[40.3711, -75.6306, "Berks", 3417, 171],[40.5082, -78.4007, "Blair", 29, 0],[41.6704, -76.2623, "Bradford", 38, 5],[40.4108, -75.2479, "Bucks", 4028, 349],[40.9104, -79.9157, "Butler", 195, 6],[40.6048, -78.7072, "Cambria", 44, 2],[41.3448, -78.134, "Cameron", 2, 0],[40.916, -75.9657, "Carbon", 198, 17],[40.8266, -77.8226, "Centre", 119, 2],[39.9343, -75.5306, "Chester", 1926, 187],[41.021, -79.2782, "Clarion", 23, 1],[40.8745, -78.7274, "Clearfield", 25, 0],[41.0026, -76.4561, "Columbia", 328, 28],[41.562, -80.2261, "Crawford", 21, 0],[40.2311, -77.0727, "Cumberland", 451, 33],[40.2657, -76.7126, "Dauphin", 830, 37],[39.9078, -75.3879, "Delaware", 5101, 399],[42.0469, -80.2765, "Erie", 124, 2],[40.0188, -79.891, "Fayette", 85, 4],[39.7329, -77.7247, "Franklin", 513, 12],[39.9111, -80.432, "Greene", 27, 1],[40.6472, -78.1957, "Huntingdon", 187, 0],[40.8197, -78.8297, "Indiana", 76, 5],[40.5686, -77.4047, "Juniata", 93, 1],[41.4846, -75.666, "Lackawanna", 1187, 117],[40.2141, -76.1605, "Lancaster", 2256, 233],[41.0955, -80.4953, "Lawrence", 70, 7],[40.3412, -76.4228, "Lebanon", 815, 16],[40.5165, -75.5545, "Lehigh", 3259, 121],[41.2867, -75.8967, "Luzerne", 2426, 120],[41.2472, -76.9184, "Lycoming", 132, 4],[41.3502, -80.0837, "Mercer", 75, 2],[40.5549, -77.6168, "Mifflin", 52, 0],[41.0458, -75.2479, "Monroe", 1224, 64],[40.229, -75.3879, "Montgomery", 5292, 525],[40.9615, -76.612, "Montour", 50, 0],[40.8811, -75.1861, "Northampton", 2465, 160],[41.085, -76.8646, "Northumberland", 125, 0],[40.3952, -77.0277, "Perry", 35, 1],[39.9526, -75.1652, "Philadelphia", 18313, 894],[41.3666, -74.6997, "Pike", 433, 21],[41.7768, -78.1552, "Potter", 4, 0],[40.6302, -76.3912, "Schuylkill", 453, 13],[40.7625, -76.9408, "Snyder", 33, 1],[40.2027, -78.9293, "Somerset", 32, 1],[41.9506, -75.6095, "Susquehanna", 87, 13],[41.9868, -76.9396, "Tioga", 16, 2],[40.8805, -76.9842, "Union", 41, 1],[41.4716, -79.9311, "Venango", 7, 0],[41.701, -79.0298, "Warren", 1, 1],[40.332, -80.256, "Washington", 124, 4],[41.6739, -75.2479, "Wayne", 117, 5],[40.4145, -79.5729, "Westmoreland", 418, 30],[40.1542, -76.7515, "York", 784, 14],[40.1599, -78.232, "Bedford", 29, 1],[41.4937, -79.448, "Forest", 7, 0],[41.6119, -76.0458, "Wyoming", 30, 3],[41.0094, -77.5306, "Clinton", 41, 0],[41.418, -76.492, "Sullivan", 1, 0],[39.932, -77.9958, "Fulton", 8, 1],[41.357, -78.6101, "Elk", 5, 1],[41.1615, -79.0827, "Jefferson", 7, 0],[41.9604, -78.6413, "McKean", 6, 1],
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
      [{v:"Adams", f:"Adams"}, 167, 0, 162, 5, 0, 0],[{v:"Allegheny", f:"Allegheny"}, 1511, 0, 1388, 123, 0, 0],[{v:"Armstrong", f:"Armstrong"}, 55, 0, 50, 5, 1, 0],[{v:"Beaver", f:"Beaver"}, 491, 0, 413, 78, 0, 0],[{v:"Berks", f:"Berks"}, 3417, 0, 3217, 171, 0, 29],[{v:"Blair", f:"Blair"}, 29, 0, 29, 0, 0, 0],[{v:"Bradford", f:"Bradford"}, 38, 0, 33, 5, 0, 0],[{v:"Bucks", f:"Bucks"}, 4028, 0, 3186, 349, 0, 493],[{v:"Butler", f:"Butler"}, 195, 0, 189, 6, 0, 0],[{v:"Cambria", f:"Cambria"}, 44, 0, 42, 2, 0, 0],[{v:"Cameron", f:"Cameron"}, 2, 0, 2, 0, 0, 0],[{v:"Carbon", f:"Carbon"}, 198, 0, 181, 17, 0, 0],[{v:"Centre", f:"Centre"}, 119, 0, 117, 2, 0, 0],[{v:"Chester", f:"Chester"}, 1926, 20, 1739, 187, 3, 0],[{v:"Clarion", f:"Clarion"}, 23, 0, 22, 1, 0, 0],[{v:"Clearfield", f:"Clearfield"}, 25, 0, 25, 0, 0, 0],[{v:"Columbia", f:"Columbia"}, 328, 0, 300, 28, 0, 0],[{v:"Crawford", f:"Crawford"}, 21, 0, 21, 0, 0, 0],[{v:"Cumberland", f:"Cumberland"}, 451, 0, 418, 33, 0, 0],[{v:"Dauphin", f:"Dauphin"}, 830, 0, 751, 37, 0, 42],[{v:"Delaware", f:"Delaware"}, 5101, 55, 4702, 399, 0, 0],[{v:"Erie", f:"Erie"}, 124, 0, 83, 2, 0, 39],[{v:"Fayette", f:"Fayette"}, 85, 0, 81, 4, 0, 0],[{v:"Franklin", f:"Franklin"}, 513, 0, 501, 12, 0, 0],[{v:"Greene", f:"Greene"}, 27, 0, 26, 1, 0, 0],[{v:"Huntingdon", f:"Huntingdon"}, 187, 0, 187, 0, 0, 0],[{v:"Indiana", f:"Indiana"}, 76, 0, 71, 5, 0, 0],[{v:"Juniata", f:"Juniata"}, 93, 0, 92, 1, 0, 0],[{v:"Lackawanna", f:"Lackawanna"}, 1187, 0, 1070, 117, 0, 0],[{v:"Lancaster", f:"Lancaster"}, 2256, 0, 2023, 233, 0, 0],[{v:"Lawrence", f:"Lawrence"}, 70, 0, 63, 7, 0, 0],[{v:"Lebanon", f:"Lebanon"}, 815, 0, 799, 16, 0, 0],[{v:"Lehigh", f:"Lehigh"}, 3259, 0, 3138, 121, 0, 0],[{v:"Luzerne", f:"Luzerne"}, 2426, 0, 2306, 120, 0, 0],[{v:"Lycoming", f:"Lycoming"}, 132, 0, 128, 4, 0, 0],[{v:"Mercer", f:"Mercer"}, 75, 0, 73, 2, 0, 0],[{v:"Mifflin", f:"Mifflin"}, 52, 0, 52, 0, 0, 0],[{v:"Monroe", f:"Monroe"}, 1224, 0, 1160, 64, 0, 0],[{v:"Montgomery", f:"Montgomery"}, 5292, 0, 4767, 525, 0, 0],[{v:"Montour", f:"Montour"}, 50, 0, 50, 0, 0, 0],[{v:"Northampton", f:"Northampton"}, 2465, 0, 2305, 160, 0, 0],[{v:"Northumberland", f:"Northumberland"}, 125, 0, 125, 0, 0, 0],[{v:"Perry", f:"Perry"}, 35, 0, 34, 1, 0, 0],[{v:"Philadelphia", f:"Philadelphia"}, 18313, 0, 17419, 894, 0, 0],[{v:"Pike", f:"Pike"}, 433, 0, 412, 21, 0, 0],[{v:"Potter", f:"Potter"}, 4, 0, 4, 0, 0, 0],[{v:"Schuylkill", f:"Schuylkill"}, 453, 0, 440, 13, 0, 0],[{v:"Snyder", f:"Snyder"}, 33, 0, 32, 1, 0, 0],[{v:"Somerset", f:"Somerset"}, 32, 0, 31, 1, 0, 0],[{v:"Susquehanna", f:"Susquehanna"}, 87, 0, 74, 13, 0, 0],[{v:"Tioga", f:"Tioga"}, 16, 0, 14, 2, 0, 0],[{v:"Union", f:"Union"}, 41, 0, 40, 1, 0, 0],[{v:"Venango", f:"Venango"}, 7, 0, 7, 0, 0, 0],[{v:"Warren", f:"Warren"}, 1, 0, 0, 1, 0, 0],[{v:"Washington", f:"Washington"}, 124, 0, 120, 4, 0, 0],[{v:"Wayne", f:"Wayne"}, 117, 0, 112, 5, 0, 0],[{v:"Westmoreland", f:"Westmoreland"}, 418, 0, 388, 30, 0, 0],[{v:"York", f:"York"}, 784, 0, 770, 14, 0, 0],[{v:"Bedford", f:"Bedford"}, 29, 0, 28, 1, 0, 0],[{v:"Forest", f:"Forest"}, 7, 0, 7, 0, 0, 0],[{v:"Wyoming", f:"Wyoming"}, 30, 0, 27, 3, 1, 0],[{v:"Clinton", f:"Clinton"}, 41, 0, 41, 0, 0, 0],[{v:"Sullivan", f:"Sullivan"}, 1, 0, 1, 0, 0, 0],[{v:"Fulton", f:"Fulton"}, 8, 0, 7, 1, 0, 0],[{v:"Elk", f:"Elk"}, 5, 0, 4, 1, 0, 0],[{v:"Jefferson", f:"Jefferson"}, 7, 0, 7, 0, 0, 0],[{v:"McKean", f:"McKean"}, 6, 0, 5, 1, 0, 0],
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

</div>

