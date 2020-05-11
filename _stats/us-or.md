---
category: stats
title: "US - Oregon State Coronavirus (COVID-19) Live Stats"
excerpt: "Live stats of COVID-19 in US-Oregon. Total Cases: 3160 (+91), Deaths: 127 (+3), Recoveries: 1125(-)."
publishedDateTime: 2020-05-10T05:45:41Z
updatedDateTime: 2020-05-10T05:45:41Z
webUrl: "https://smartable.ai/apps/coronavirus/stats/us-or/"
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
  - url: "https://smartable.azureedge.net/coronavirus/sites/2/2020/us-or.jpg"
    width: 900
    height: 564
    title: "US - Oregon State Coronavirus (COVID-19) Live Stats"

---
<div class="total-stats" style="text-align: center;">
    <h3>
	    <div style="font-size: 18px; font-weight: 400;">Total Confirmed Cases:</div>
	    3160 (<span class='red'>+91</span>)
    </h3>
    <h3>
	    <div style="font-size: 18px; font-weight: 400;">Total Deaths:</div>
	    127 (<span class='red'>+3</span>)
    </h3>
    <h3>
	    <div style="font-size: 18px; font-weight: 400;">Total Recovered:</div>
	    1125 (-)
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
      ['1/22/2020', 0, 0, 0],['1/23/2020', 0, 0, 0],['1/24/2020', 0, 0, 0],['1/25/2020', 0, 0, 0],['1/26/2020', 0, 0, 0],['1/27/2020', 0, 0, 0],['1/28/2020', 0, 0, 0],['1/29/2020', 0, 0, 0],['1/30/2020', 0, 0, 0],['1/31/2020', 0, 0, 0],['2/1/2020', 0, 0, 0],['2/2/2020', 0, 0, 0],['2/3/2020', 0, 0, 0],['2/4/2020', 0, 0, 0],['2/5/2020', 0, 0, 0],['2/6/2020', 0, 0, 0],['2/7/2020', 0, 0, 0],['2/8/2020', 0, 0, 0],['2/9/2020', 0, 0, 0],['2/10/2020', 0, 0, 0],['2/11/2020', 0, 0, 0],['2/12/2020', 0, 0, 0],['2/13/2020', 0, 0, 0],['2/14/2020', 0, 0, 0],['2/15/2020', 0, 0, 0],['2/16/2020', 0, 0, 0],['2/17/2020', 0, 0, 0],['2/18/2020', 0, 0, 0],['2/19/2020', 0, 0, 0],['2/20/2020', 0, 0, 0],['2/21/2020', 0, 0, 0],['2/22/2020', 0, 0, 0],['2/23/2020', 0, 0, 0],['2/24/2020', 0, 0, 0],['2/25/2020', 0, 0, 0],['2/26/2020', 0, 0, 0],['2/27/2020', 0, 0, 0],['2/28/2020', 0, 0, 0],['2/29/2020', 1, 0, 0],['3/1/2020', 1, 0, 0],['3/2/2020', 3, 0, 0],['3/3/2020', 3, 0, 0],['3/4/2020', 3, 0, 0],['3/5/2020', 3, 0, 0],['3/6/2020', 3, 0, 0],['3/7/2020', 6, 0, 0],['3/8/2020', 14, 0, 0],['3/9/2020', 14, 0, 0],['3/10/2020', 14, 0, 0],['3/11/2020', 19, 0, 0],['3/12/2020', 24, 0, 0],['3/13/2020', 32, 0, 0],['3/14/2020', 36, 1, 0],['3/15/2020', 39, 1, 0],['3/16/2020', 45, 1, 0],['3/17/2020', 68, 2, 0],['3/18/2020', 75, 3, 0],['3/19/2020', 88, 3, 0],['3/20/2020', 114, 4, 0],['3/21/2020', 137, 4, 0],['3/22/2020', 161, 5, 0],['3/23/2020', 191, 5, 0],['3/24/2020', 210, 8, 0],['3/25/2020', 266, 10, 0],['3/26/2020', 317, 11, 0],['3/27/2020', 414, 12, 0],['3/28/2020', 479, 13, 0],['3/29/2020', 549, 13, 0],['3/30/2020', 606, 16, 0],['3/31/2020', 690, 18, 0],['4/1/2020', 736, 19, 0],['4/2/2020', 826, 21, 0],['4/3/2020', 899, 22, 0],['4/4/2020', 999, 26, 0],['4/5/2020', 1068, 27, 0],['4/6/2020', 1132, 29, 0],['4/7/2020', 1181, 33, 0],['4/8/2020', 1239, 37, 0],['4/9/2020', 1321, 44, 0],['4/10/2020', 1371, 48, 0],['4/11/2020', 1447, 51, 0],['4/12/2020', 1527, 52, 0],['4/13/2020', 1584, 53, 0],['4/14/2020', 1633, 55, 38],['4/15/2020', 1663, 58, 42],['4/16/2020', 1736, 64, 42],['4/17/2020', 1785, 70, 42],['4/18/2020', 1844, 72, 42],['4/19/2020', 1910, 74, 42],['4/20/2020', 1956, 75, 42],['4/21/2020', 2002, 78, 42],['4/22/2020', 2059, 78, 595],['4/23/2020', 2127, 83, 595],['4/24/2020', 2178, 86, 595],['4/25/2020', 2254, 87, 42],['4/26/2020', 2312, 91, 42],['4/27/2020', 2355, 92, 42],['4/28/2020', 2387, 99, 42],['4/29/2020', 2447, 101, 860],['4/30/2020', 2511, 103, 860],['5/1/2020', 2568, 105, 860],['5/2/2020', 2636, 109, 860],['5/3/2020', 2681, 109, 860],['5/4/2020', 2759, 109, 860],['5/5/2020', 2839, 113, 860],['5/6/2020', 2916, 115, 1125],['5/7/2020', 2989, 121, 1125],['5/8/2020', 3069, 124, 1125],['5/9/2020', 3160, 127, 1125],
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
      [44.3307, -123.3625, "Benton", 44, 5],[45.4239, -122.447, "Clackamas", 256, 9],[46.1303, -123.3715, "Clatsop", 28, 0],[46.0768, -122.9405, "Columbia", 15, 0],[43.8325, -121.2617, "Deschutes", 85, 0],[43.1261, -123.2492, "Douglas", 24, 0],[44.4667, -119.5322, "Grant", 1, 0],[45.6354, -121.5522, "Hood River", 12, 0],[42.3345, -122.7647, "Jackson", 49, 0],[42.2797, -123.6151, "Josephine", 24, 1],[42.6953, -121.6142, "Klamath", 39, 0],[44.0563, -123.1173, "Lane", 60, 2],[44.6231, -124.0524, "Lincoln", 6, 0],[44.3561, -122.865, "Linn", 102, 8],[44.8446, -122.5927, "Marion", 663, 23],[45.8959, -119.4883, "Morrow", 12, 0],[45.5146, -122.5863, "Multnomah", 863, 53],[44.9267, -123.4919, "Polk", 82, 5],[45.1208, -123.9766, "Tillamook", 6, 0],[45.775, -118.7606, "Umatilla", 84, 1],[45.3358, -118.0492, "Union", 4, 0],[45.685, -121.3952, "Wasco", 15, 1],[45.547, -123.1386, "Washington", 562, 12],[45.211, -123.1918, "Yamhill", 47, 7],[44.2476, -117.5187, "Malheur", 14, 0],[45.5704, -117.5286, "Wallowa", 1, 0],[44.298, -120.8616, "Crook", 1, 0],[45.5916, -120.6975, "Sherman", 1, 0],[42.3974, -124.4171, "Curry", 4, 0],[42.886, -124.0735, "Coos", 30, 0],[44.5232, -121.211, "Jefferson", 24, 0],[43.1423225, -119.0116305, "Harney", 1, 0],[44.7652304, -117.67692, "Baker", 1, 0],
    ]);
    var options = {
      backgroundColor: {fill:'transparent',stroke:'#FFF' ,strokeWidth:0 }, 
      displayMode: 'markers',
      region: 'US-OR', 
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
      [{v:"Benton", f:"Benton"}, 44, 0, 39, 5, 0, 0],[{v:"Clackamas", f:"Clackamas"}, 256, 6, 247, 9, 1, 0],[{v:"Clatsop", f:"Clatsop"}, 28, 1, 28, 0, 0, 0],[{v:"Columbia", f:"Columbia"}, 15, 0, 15, 0, 0, 0],[{v:"Deschutes", f:"Deschutes"}, 85, 1, 85, 0, 0, 0],[{v:"Douglas", f:"Douglas"}, 24, 0, 16, 0, 0, 8],[{v:"Grant", f:"Grant"}, 1, 0, 1, 0, 0, 0],[{v:"Hood River", f:"Hood River"}, 12, 1, 12, 0, 0, 0],[{v:"Jackson", f:"Jackson"}, 49, 0, 49, 0, 0, 0],[{v:"Josephine", f:"Josephine"}, 24, 0, 19, 1, 0, 4],[{v:"Klamath", f:"Klamath"}, 39, 0, 24, 0, 0, 15],[{v:"Lane", f:"Lane"}, 60, 1, 43, 2, 0, 15],[{v:"Lincoln", f:"Lincoln"}, 6, 0, 6, 0, 0, 0],[{v:"Linn", f:"Linn"}, 102, 2, 94, 8, 1, 0],[{v:"Marion", f:"Marion"}, 663, 37, 640, 23, 0, 0],[{v:"Morrow", f:"Morrow"}, 12, 0, 12, 0, 0, 0],[{v:"Multnomah", f:"Multnomah"}, 863, 24, 810, 53, 1, 0],[{v:"Polk", f:"Polk"}, 82, 2, 77, 5, 0, 0],[{v:"Tillamook", f:"Tillamook"}, 6, 0, 6, 0, 0, 0],[{v:"Umatilla", f:"Umatilla"}, 84, 4, 83, 1, 0, 0],[{v:"Union", f:"Union"}, 4, 0, 4, 0, 0, 0],[{v:"Wasco", f:"Wasco"}, 15, 0, 14, 1, 0, 0],[{v:"Washington", f:"Washington"}, 562, 6, 550, 12, 0, 0],[{v:"Yamhill", f:"Yamhill"}, 47, 2, 40, 7, 0, 0],[{v:"Malheur", f:"Malheur"}, 14, 1, 14, 0, 0, 0],[{v:"Wallowa", f:"Wallowa"}, 1, 0, 1, 0, 0, 0],[{v:"Crook", f:"Crook"}, 1, 0, 1, 0, 0, 0],[{v:"Sherman", f:"Sherman"}, 1, 0, 1, 0, 0, 0],[{v:"Curry", f:"Curry"}, 4, 0, 4, 0, 0, 0],[{v:"Coos", f:"Coos"}, 30, 1, 30, 0, 0, 0],[{v:"Jefferson", f:"Jefferson"}, 24, 2, 24, 0, 0, 0],[{v:"Harney", f:"Harney"}, 1, 0, 1, 0, 0, 0],[{v:"Baker", f:"Baker"}, 1, 0, 1, 0, 0, 0],
    ]);
    data.setProperty(0, 0, 'style', 'min-width:100px');
    var table = new google.visualization.Table(document.getElementById('geo_table'));
    table.draw(data, {allowHtml: true, sortColumn: 2, sortAscending: false, width: '660px', height: '100%'});
  }
</script>

<span style="font-size: 13px">All COVID-19 data displayed on the page is available through our FREE <a href="https://developer.smartable.ai">API program</a>. This US - Oregon State Coronavirus (COVID-19) Live Stats is refreshed every hour using credible data sources, including the country/state's official government website, <a href="https://en.wikipedia.org/wiki/2019%E2%80%9320_coronavirus_pandemic" target="_blank">data available on wikipedia pages</a>, latest news reports, <a href="https://systems.jhu.edu/research/public-health/ncov/" target="_blank">Johns Hopkins University CSSE 2019-nCoV Dashboard</a>, <a href="https://www.who.int/emergencies/diseases/novel-coronavirus-2019/situation-reports" target="_blank">WHO Situation Reports</a>, <a href="https://www.cdc.gov/coronavirus/2019-ncov/index.html" target="_blank">CDC Situation Updates</a>, and <a href="https://ncov.dxy.cn/ncovh5/view/pneumonia" target="_blank">DXY.cn</a>.</span>

<h2 id="news" class="center" style="margin-top: 60px; font-size: 25px;">Local Government Help Information</h2>
<div class="info center">
<a href="https://www.oregon.gov/oha/PH/DISEASESCONDITIONS/DISEASESAZ/Pages/emerging-respiratory-infections.aspx" target="_blank">Novel Coronavirus Updates on oregon.gov</a> Call 211
</div>
<h2 id="news" class="center" style="margin-top: 60px; font-size: 25px;">Trending Coronavirus News in US-Oregon</h2>
<div class="row">
<div class="col-md-6 col-sm-12">
  <div class="content-card">
	<a href="https://www.sfgate.com/news/article/Oregon-reports-2-new-deaths-70-new-cases-of-15251575.php"><div class="card-image" style="background-image: url(https://d29xw9s9x32j3w.cloudfront.net/players/library/placeholder.png)"></div></a>
	<div class="content">
		<div class="card-title"><a href="https://www.sfgate.com/news/article/Oregon-reports-2-new-deaths-70-new-cases-of-15251575.php">Oregon reports 2 new deaths, 70 new cases of coronavirus</a></div>
		<div class="card-excerpt">Oregon health officials said Wednesday that two more people have died from the new coronavirus and there are 70 new confirmed cases. The numbers bring the statewide death toll to 115 and the number of confirmed cases statewide to 2,</div>
		<div class="card-meta">
			<span class="card-provider">SFGate</span> • <span class="card-date">5/6/2020</span>
		</div>
	</div>
  </div>
</div>
<div class="col-md-6 col-sm-12">
  <div class="content-card">
	<a href="https://www.oregonlive.com/pacific-northwest-news/2020/05/cycle-oregon-cancels-all-2020-events-due-to-ongoing-coronavirus-pandemic.html"><div class="card-image" style="background-image: url(https://arc-anglerfish-arc2-prod-advancelocal.s3.amazonaws.com/public/OKINOQDDPVG2PK4BYMYTINY5FU.JPG)"></div></a>
	<div class="content">
		<div class="card-title"><a href="https://www.oregonlive.com/pacific-northwest-news/2020/05/cycle-oregon-cancels-all-2020-events-due-to-ongoing-coronavirus-pandemic.html">Cycle Oregon cancels all 2020 events due to ongoing coronavirus pandemic</a></div>
		<div class="card-excerpt">Registered riders will receive a 70 percent refund of their registration fee and a total refund of their add-on purchases.</div>
		<div class="card-meta">
			<span class="card-provider">Oregonian</span> • <span class="card-date">5/6/2020</span>
		</div>
	</div>
  </div>
</div>
<div class="col-md-6 col-sm-12">
  <div class="content-card">
	<a href="https://www.foxnews.com/health/oregons-first-known-coronavirus-patient-released-from-hospital-after-2-months"><div class="card-image" style="background-image: url(https://a57.foxnews.com/static.foxnews.com/foxnews.com/content/uploads/2020/05/640/320/Hector-Calderon-AP.jpg?ve=1&tl=1)"></div></a>
	<div class="content">
		<div class="card-title"><a href="https://www.foxnews.com/health/oregons-first-known-coronavirus-patient-released-from-hospital-after-2-months">Oregon’s first known coronavirus patient released from hospital after 2 months</a></div>
		<div class="card-excerpt">The first known coronavirus patient in Oregon to test positive for the novel coronavirus has officially been released from the hospital following a more than two-month-long battle with COVID-19.</div>
		<div class="card-meta">
			<span class="card-provider">Fox News</span> • <span class="card-date">5/6/2020</span>
		</div>
	</div>
  </div>
</div>
<div class="col-md-6 col-sm-12">
  <div class="content-card">
	<a href="https://www.statesmanjournal.com/story/news/2020/05/05/salem-coronavirus-updates-fred-meyer-offers-testing-frontline-workers/3083665001/"><div class="card-image" style="background-image: url(https://www.gannett-cdn.com/presto/2020/04/15/USAT/c117f675-982e-410b-a279-aeb9c700aec2-61618JF001_STIMULUS.JPG?auto=webp&crop=2999,1687,x0,y240&format=pjpg&width=1200)"></div></a>
	<div class="content">
		<div class="card-title"><a href="https://www.statesmanjournal.com/story/news/2020/05/05/salem-coronavirus-updates-fred-meyer-offers-testing-frontline-workers/3083665001/">Oregon coronavirus updates, May 5: 4 new COVID-19 deaths; 72 new cases</a></div>
		<div class="card-excerpt">Check back on this story throughout the day for the latest news about coronavirus and its effects in Salem and around Oregon</div>
		<div class="card-meta">
			<span class="card-provider">Statesman Journal</span> • <span class="card-date">5/6/2020</span>
		</div>
	</div>
  </div>
</div>
<div class="col-md-6 col-sm-12">
  <div class="content-card">
	<a href="https://www.sfgate.com/news/article/Oregon-s-1st-COVID-19-patient-out-of-hospital-15249249.php"><div class="card-image" style="background-image: url(https://d29xw9s9x32j3w.cloudfront.net/players/library/placeholder.png)"></div></a>
	<div class="content">
		<div class="card-title"><a href="https://www.sfgate.com/news/article/Oregon-s-1st-COVID-19-patient-out-of-hospital-15249249.php">Oregon's 1st COVID-19 patient out of hospital after 2 months</a></div>
		<div class="card-excerpt">The first person in Oregon to be diagnosed with the new coronavirus has been discharged from the hospital more than two months after being admitted, the hospital said Tuesday. Hector Calderon spent many days in the intensive care unit,</div>
		<div class="card-meta">
			<span class="card-provider">SFGate</span> • <span class="card-date">5/5/2020</span>
		</div>
	</div>
  </div>
</div>
<div class="col-md-6 col-sm-12">
  <div class="content-card">
	<a href="https://www.foxnews.com/health/coronavirus-infects-workers-at-oregon-seafood-processing-plant"><div class="card-image" style="background-image: url(https://a57.foxnews.com/static.foxnews.com/foxnews.com/content/uploads/2020/05/640/320/iStock-1153667868.jpg?ve=1&tl=1)"></div></a>
	<div class="content">
		<div class="card-title"><a href="https://www.foxnews.com/health/coronavirus-infects-workers-at-oregon-seafood-processing-plant">Coronavirus infects workers at Oregon seafood processing plant</a></div>
		<div class="card-excerpt">More than a dozen workers at a seafood processing plant in Oregon have contracted the novel coronavirus, forcing two of Bornstein Seafood's facilities in Astoria to temporarily close.</div>
		<div class="card-meta">
			<span class="card-provider">Fox News</span> • <span class="card-date">5/5/2020</span>
		</div>
	</div>
  </div>
</div>
<div class="col-md-6 col-sm-12">
  <div class="content-card">
	<a href="https://www.kdrv.com/content/news/Oregon-Health-Authority-no-new-deaths-65-new-cases-of-COVID-19-570180761.html"><div class="card-image" style="background-image: url(http://media.heartlandtv.com/images/Coronavirus+CDC.jpg)"></div></a>
	<div class="content">
		<div class="card-title"><a href="https://www.kdrv.com/content/news/Oregon-Health-Authority-no-new-deaths-65-new-cases-of-COVID-19-570180761.html">Oregon Health Authority no new deaths, 65 new cases of COVID-19</a></div>
		<div class="card-excerpt">The Oregon Health Authority reported 65 new confirmed cases in an update on Wednesday, bringing the state total to 2,745.</div>
		<div class="card-meta">
			<span class="card-provider">KDRV</span> • <span class="card-date">5/4/2020</span>
		</div>
	</div>
  </div>
</div>
<div class="col-md-6 col-sm-12">
  <div class="content-card">
	<a href="https://www.oregonlive.com/beer/2020/05/oregon-brewers-festival-the-states-largest-canceled-for-2020-because-of-coronavirus.html"><div class="card-image" style="background-image: url(https://arc-anglerfish-arc2-prod-advancelocal.s3.amazonaws.com/public/2AKMLSIWEJBERAL56DJRT4GUM4.jpg)"></div></a>
	<div class="content">
		<div class="card-title"><a href="https://www.oregonlive.com/beer/2020/05/oregon-brewers-festival-the-states-largest-canceled-for-2020-because-of-coronavirus.html">Oregon Brewers Festival, the state’s largest, canceled for 2020 because of coronavirus</a></div>
		<div class="card-excerpt">For the first time in over three decades, the Oregon Brewers Festival – the state’s biggest craft beer showcase – won’t be a summertime stop for tens of thousands of suds enthusiasts as organizers have called off the party, the latest cancellation ... to hold a successful event in a post-pandemic world.” Coronavirus in Oregon: Latest ...</div>
		<div class="card-meta">
			<span class="card-provider">Oregonian</span> • <span class="card-date">5/4/2020</span>
		</div>
	</div>
  </div>
</div>
<div class="col-md-6 col-sm-12">
  <div class="content-card">
	<a href="https://www.kgw.com/article/news/health/coronavirus/oregon-coronavirus-updates-live-blog-covid-19/283-cda6c929-68ae-499b-b438-0c924d0aa69b"><div class="card-image" style="background-image: url(https://media.kgw.com/assets/KGW/images/e06671c3-fd18-4a09-8360-f3c13efb6848/e06671c3-fd18-4a09-8360-f3c13efb6848_1140x641.jpg)"></div></a>
	<div class="content">
		<div class="card-title"><a href="https://www.kgw.com/article/news/health/coronavirus/oregon-coronavirus-updates-live-blog-covid-19/283-cda6c929-68ae-499b-b438-0c924d0aa69b">Oregon coronavirus updates May 2: Portland Whole Foods worker speaks out</a></div>
		<div class="card-excerpt">We post a new blog post every day that tracks the daily changes in Oregon and Southwest Washington as we get them. CLICK HERE TO SEE THE LATEST UPDATES</div>
		<div class="card-meta">
			<span class="card-provider">KGW8</span> • <span class="card-date">5/2/2020</span>
		</div>
	</div>
  </div>
</div>
<div class="col-md-6 col-sm-12">
  <div class="content-card">
	<a href="https://www.heraldandnews.com/news/local_news/oregon-reports-two-deaths-61-new-confirmed-covid-19-cases/article_3e1506b3-4d9b-512f-8630-b3d4c4470f4c.html"><div class="card-image" style="background-image: url(https://bloximages.chicago2.vip.townnews.com/heraldandnews.com/content/tncms/assets/v3/editorial/b/23/b23fbef0-b3e3-5a62-bfca-0047cef084b7/5e8d0fcb335a3.image.jpg)"></div></a>
	<div class="content">
		<div class="card-title"><a href="https://www.heraldandnews.com/news/local_news/oregon-reports-two-deaths-61-new-confirmed-covid-19-cases/article_3e1506b3-4d9b-512f-8630-b3d4c4470f4c.html">Oregon reports two deaths, 61 new confirmed COVID-19 cases</a></div>
		<div class="card-excerpt">COVID-19 has claimed two more lives in Oregon, raising the state’s death toll to 101, the Oregon Health Authority reported on Wednesday, April 29, according to a news release.</div>
		<div class="card-meta">
			<span class="card-provider">Herald and News</span> • <span class="card-date">4/29/2020</span>
		</div>
	</div>
  </div>
</div>

</div>

