---
category: stats
title: "US - Arizona State Coronavirus (COVID-19) Live Stats"
excerpt: "Live stats of COVID-19 in US-Arizona. Total Cases: 10960 (+433), Deaths: 532 (+15), Recoveries: 70(-)."
publishedDateTime: 2020-05-10T05:45:41Z
updatedDateTime: 2020-05-10T05:45:41Z
webUrl: "https://smartable.ai/apps/coronavirus/stats/us-az/"
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
  - url: "https://smartable.azureedge.net/coronavirus/sites/2/2020/us-az.jpg"
    width: 900
    height: 564
    title: "US - Arizona State Coronavirus (COVID-19) Live Stats"

---
<div class="total-stats" style="text-align: center;">
    <h3>
	    <div style="font-size: 18px; font-weight: 400;">Total Confirmed Cases:</div>
	    10960 (<span class='red'>+433</span>)
    </h3>
    <h3>
	    <div style="font-size: 18px; font-weight: 400;">Total Deaths:</div>
	    532 (<span class='red'>+15</span>)
    </h3>
    <h3>
	    <div style="font-size: 18px; font-weight: 400;">Total Recovered:</div>
	    70 (-)
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
      ['1/22/2020', 0, 0, 0],['1/23/2020', 0, 0, 0],['1/24/2020', 0, 0, 0],['1/25/2020', 0, 0, 0],['1/26/2020', 1, 0, 0],['1/27/2020', 1, 0, 0],['1/28/2020', 1, 0, 0],['1/29/2020', 1, 0, 0],['1/30/2020', 1, 0, 0],['1/31/2020', 1, 0, 0],['2/1/2020', 1, 0, 0],['2/2/2020', 1, 0, 0],['2/3/2020', 1, 0, 0],['2/4/2020', 1, 0, 0],['2/5/2020', 1, 0, 0],['2/6/2020', 1, 0, 0],['2/7/2020', 1, 0, 0],['2/8/2020', 1, 0, 0],['2/9/2020', 1, 0, 0],['2/10/2020', 1, 0, 0],['2/11/2020', 1, 0, 0],['2/12/2020', 1, 0, 0],['2/13/2020', 1, 0, 0],['2/14/2020', 1, 0, 0],['2/15/2020', 1, 0, 0],['2/16/2020', 1, 0, 0],['2/17/2020', 1, 0, 0],['2/18/2020', 1, 0, 0],['2/19/2020', 1, 0, 0],['2/20/2020', 1, 0, 0],['2/21/2020', 1, 0, 0],['2/22/2020', 1, 0, 0],['2/23/2020', 1, 0, 0],['2/24/2020', 1, 0, 0],['2/25/2020', 1, 0, 1],['2/26/2020', 1, 0, 1],['2/27/2020', 1, 0, 1],['2/28/2020', 1, 0, 1],['2/29/2020', 1, 0, 1],['3/1/2020', 1, 0, 1],['3/2/2020', 1, 0, 1],['3/3/2020', 1, 0, 1],['3/4/2020', 1, 0, 1],['3/5/2020', 1, 0, 1],['3/6/2020', 2, 0, 1],['3/7/2020', 4, 0, 1],['3/8/2020', 4, 0, 1],['3/9/2020', 4, 0, 1],['3/10/2020', 6, 0, 1],['3/11/2020', 9, 0, 1],['3/12/2020', 9, 0, 1],['3/13/2020', 10, 0, 1],['3/14/2020', 12, 0, 1],['3/15/2020', 13, 0, 1],['3/16/2020', 18, 0, 1],['3/17/2020', 22, 0, 2],['3/18/2020', 29, 0, 2],['3/19/2020', 53, 0, 2],['3/20/2020', 79, 1, 2],['3/21/2020', 104, 1, 2],['3/22/2020', 152, 2, 2],['3/23/2020', 235, 2, 2],['3/24/2020', 326, 5, 4],['3/25/2020', 401, 6, 4],['3/26/2020', 508, 8, 4],['3/27/2020', 665, 13, 4],['3/28/2020', 773, 15, 4],['3/29/2020', 919, 17, 4],['3/30/2020', 1158, 20, 4],['3/31/2020', 1289, 24, 4],['4/1/2020', 1413, 29, 3],['4/2/2020', 1598, 32, 3],['4/3/2020', 1769, 41, 3],['4/4/2020', 2019, 52, 3],['4/5/2020', 2269, 64, 3],['4/6/2020', 2456, 65, 3],['4/7/2020', 2575, 73, 3],['4/8/2020', 2726, 80, 3],['4/9/2020', 3018, 89, 3],['4/10/2020', 3112, 97, 3],['4/11/2020', 3393, 108, 3],['4/12/2020', 3542, 115, 3],['4/13/2020', 3705, 122, 3],['4/14/2020', 3809, 131, 6],['4/15/2020', 3968, 143, 6],['4/16/2020', 4241, 150, 6],['4/17/2020', 4511, 169, 6],['4/18/2020', 4724, 180, 6],['4/19/2020', 4933, 184, 6],['4/20/2020', 5068, 191, 6],['4/21/2020', 5256, 208, 6],['4/22/2020', 5473, 231, 6],['4/23/2020', 5772, 249, 6],['4/24/2020', 6046, 266, 6],['4/25/2020', 6289, 273, 70],['4/26/2020', 6536, 275, 70],['4/27/2020', 6727, 275, 70],['4/28/2020', 6957, 293, 70],['4/29/2020', 7209, 306, 70],['4/30/2020', 7655, 320, 70],['5/1/2020', 8006, 332, 70],['5/2/2020', 8365, 348, 70],['5/3/2020', 8641, 362, 70],['5/4/2020', 8925, 362, 70],['5/5/2020', 9305, 395, 70],['5/6/2020', 9707, 426, 70],['5/7/2020', 9945, 450, 70],['5/8/2020', 10527, 517, 70],['5/9/2020', 10960, 532, 70],
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
      [36.9221, -109.0753, "Apache", 710, 10],[31.6858, -109.6896, "Cochise", 41, 1],[36.592, -111.1071, "Coconino", 679, 55],[34.3199, -111.3051, "Gila", 19, 1],[32.8138, -109.6291, "Graham", 19, 0],[33.0531, -109.3307, "Greenlee", 2, 0],[33.9921, -114.4046, "La Paz", 22, 2],[33.2918, -112.4291, "Maricopa", 5779, 245],[35.4227, -113.6486, "Mohave", 178, 23],[33.9965, -109.9593, "Navajo", 981, 36],[32.0575, -111.6661, "Pima", 1554, 133],[32.8162, -111.2845, "Pinal", 585, 19],[31.6645, -110.6426, "Santa Cruz", 40, 0],[35.2171, -112.4913, "Yavapai", 175, 4],[32.6452, -114.7067, "Yuma", 176, 3],
    ]);
    var options = {
      backgroundColor: {fill:'transparent',stroke:'#FFF' ,strokeWidth:0 }, 
      displayMode: 'markers',
      region: 'US-AZ', 
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
      [{v:"Apache", f:"Apache"}, 710, 39, 700, 10, 0, 0],[{v:"Cochise", f:"Cochise"}, 41, 0, 40, 1, 0, 0],[{v:"Coconino", f:"Coconino"}, 679, 20, 624, 55, 0, 0],[{v:"Gila", f:"Gila"}, 19, 0, 18, 1, 0, 0],[{v:"Graham", f:"Graham"}, 19, 0, 19, 0, 0, 0],[{v:"Greenlee", f:"Greenlee"}, 2, 0, 2, 0, 0, 0],[{v:"La Paz", f:"La Paz"}, 22, 0, 20, 2, 0, 0],[{v:"Maricopa", f:"Maricopa"}, 5779, 254, 5533, 245, 7, 1],[{v:"Mohave", f:"Mohave"}, 178, 7, 155, 23, 3, 0],[{v:"Navajo", f:"Navajo"}, 981, 36, 945, 36, 1, 0],[{v:"Pima", f:"Pima"}, 1554, 34, 1420, 133, 2, 1],[{v:"Pinal", f:"Pinal"}, 585, 19, 565, 19, 0, 1],[{v:"Santa Cruz", f:"Santa Cruz"}, 40, 2, 40, 0, 0, 0],[{v:"Yavapai", f:"Yavapai"}, 175, 5, 168, 4, 0, 3],[{v:"Yuma", f:"Yuma"}, 176, 17, 173, 3, 2, 0],
    ]);
    data.setProperty(0, 0, 'style', 'min-width:100px');
    var table = new google.visualization.Table(document.getElementById('geo_table'));
    table.draw(data, {allowHtml: true, sortColumn: 2, sortAscending: false, width: '660px', height: '100%'});
  }
</script>

<span style="font-size: 13px">All COVID-19 data displayed on the page is available through our FREE <a href="https://developer.smartable.ai">API program</a>. This US - Arizona State Coronavirus (COVID-19) Live Stats is refreshed every hour using credible data sources, including the country/state's official government website, <a href="https://en.wikipedia.org/wiki/2019%E2%80%9320_coronavirus_pandemic" target="_blank">data available on wikipedia pages</a>, latest news reports, <a href="https://systems.jhu.edu/research/public-health/ncov/" target="_blank">Johns Hopkins University CSSE 2019-nCoV Dashboard</a>, <a href="https://www.who.int/emergencies/diseases/novel-coronavirus-2019/situation-reports" target="_blank">WHO Situation Reports</a>, <a href="https://www.cdc.gov/coronavirus/2019-ncov/index.html" target="_blank">CDC Situation Updates</a>, and <a href="https://ncov.dxy.cn/ncovh5/view/pneumonia" target="_blank">DXY.cn</a>.</span>

<h2 id="news" class="center" style="margin-top: 60px; font-size: 25px;">Local Government Help Information</h2>
<div class="info center">
<a href="https://www.azdhs.gov/preparedness/epidemiology-disease-control/infectious-disease-epidemiology/index.php#novel-coronavirus-home" target="_blank">Arizona Department of Health Services</a> 415-655-0003
</div>
<h2 id="news" class="center" style="margin-top: 60px; font-size: 25px;">Trending Coronavirus News in US-Arizona</h2>
<div class="row">
<div class="col-md-6 col-sm-12">
  <div class="content-card">
	<a href="http://news.aa.com/coronavirus/"><div class="card-image" style="background-image: url(http://s21.q4cdn.com/616071541/files/images/newsroom/PR_2019/NEWSROOM-Livery-1200x628.jpg	)"></div></a>
	<div class="content">
		<div class="card-title"><a href="http://news.aa.com/coronavirus/">Coronavirus live updates: Trump staff to be tested daily; TSA to require facial protection; WH reportedly shelved CDC reopening plans;</a></div>
		<div class="card-excerpt">President Trump's staff to be tested daily. TSA requires facial protection. The White House reportedly shelved CDC's reopening plan. Thursday's news.</div>
		<div class="card-meta">
			<span class="card-provider">USA Today</span> • <span class="card-date">5/7/2020</span>
		</div>
	</div>
  </div>
</div>
<div class="col-md-6 col-sm-12">
  <div class="content-card">
	<a href="http://news.aa.com/coronavirus/"><div class="card-image" style="background-image: url(http://s21.q4cdn.com/616071541/files/images/newsroom/PR_2019/NEWSROOM-Livery-1200x628.jpg	)"></div></a>
	<div class="content">
		<div class="card-title"><a href="http://news.aa.com/coronavirus/">Coronavirus update: U.S. death toll tops 73,000, as Trump administration shelves ‘too cautious’ CDC guide to reopening</a></div>
		<div class="card-excerpt">The number of U.S. fatalities from the coronavirus that causes COVID-19 climbed above 73,000 on Thursday, as President Donald Trump’s administration said</div>
		<div class="card-meta">
			<span class="card-provider">MarketWatch</span> • <span class="card-date">5/7/2020</span>
		</div>
	</div>
  </div>
</div>
<div class="col-md-6 col-sm-12">
  <div class="content-card">
	<a href="http://news.aa.com/coronavirus/"><div class="card-image" style="background-image: url(http://s21.q4cdn.com/616071541/files/images/newsroom/PR_Thumbs/General/social-American-Airlines-generic-07.png)"></div></a>
	<div class="content">
		<div class="card-title"><a href="http://news.aa.com/coronavirus/">Live updates: Trump admits reopening the U.S. economy may cost American lives</a></div>
		<div class="card-excerpt">Trump said it's “possible” there will be more deaths as coronavirus restrictions are lifted across the U.S. "But we have to get our country open,” he said.</div>
		<div class="card-meta">
			<span class="card-provider">Washington Post</span> • <span class="card-date">5/6/2020</span>
		</div>
	</div>
  </div>
</div>
<div class="col-md-6 col-sm-12">
  <div class="content-card">
	<a href="https://www.azfamily.com/news/continuing_coverage/coronavirus_coverage/"><div class="card-image" style="background-image: url(https://bloximages.newyork1.vip.townnews.com/azfamily.com/content/tncms/custom/image/96272750-6998-11ea-9c94-b772d12eb4e6.jpg)"></div></a>
	<div class="content">
		<div class="card-title"><a href="https://www.azfamily.com/news/continuing_coverage/coronavirus_coverage/">Arizona's Family sues state health department to get long-term health care facilities information</a></div>
		<div class="card-excerpt">Arizona’s Family has teamed up with several other Phoenix news organizations in suing the Arizona Department of Health Services to get information about COVID-19 in our long-term health care facilities.</div>
		<div class="card-meta">
			<span class="card-provider">AZFamily</span> • <span class="card-date">5/5/2020</span>
		</div>
	</div>
  </div>
</div>
<div class="col-md-6 col-sm-12">
  <div class="content-card">
	<a href="http://news.aa.com/coronavirus/"><div class="card-image" style="background-image: url(http://s21.q4cdn.com/616071541/files/images/newsroom/PR_2019/NEWSROOM-Livery-1200x628.jpg	)"></div></a>
	<div class="content">
		<div class="card-title"><a href="http://news.aa.com/coronavirus/">Coronavirus Live Updates: Infection Rates Show the Threat Is Not Fading</a></div>
		<div class="card-excerpt">Cases are growing by 2 to 4 percent daily, and more than 1,000 people have died each day for over a month. At least 15 children in New York were hospitalized with an illness scientists worry might be linked to Covid-19.</div>
		<div class="card-meta">
			<span class="card-provider">New York Times</span> • <span class="card-date">5/5/2020</span>
		</div>
	</div>
  </div>
</div>
<div class="col-md-6 col-sm-12">
  <div class="content-card">
	<a href="https://www.abc15.com/news/state/pinal-county-reports-two-new-cases-of-coronavirus-bringing-total-in-county-to-five?_amp=true&__twitter_impression=true"><div class="card-image" style="background-image: url(https://x-default-stgec.uplynk.com/ausw/slices/fcd/5c3d34b8b29a45469a86c02775b7a2cf/fcd9612540ec4beebbc80c0ae588d1b0/poster_e1a6edad9cb0498d9c9e3e3a47bec7a8.jpg)"></div></a>
	<div class="content">
		<div class="card-title"><a href="https://www.abc15.com/news/state/pinal-county-reports-two-new-cases-of-coronavirus-bringing-total-in-county-to-five?_amp=true&__twitter_impression=true">The Latest: New Zealand reports no new coronavirus cases</a></div>
		<div class="card-excerpt">New Zealand reported no new coronavirus cases Monday, marking a significant moment that indicated the country’s bold strategy of trying to eliminate the virus was working.</div>
		<div class="card-meta">
			<span class="card-provider">The State</span> • <span class="card-date">5/3/2020</span>
		</div>
	</div>
  </div>
</div>
<div class="col-md-6 col-sm-12">
  <div class="content-card">
	<a href="http://news.aa.com/coronavirus/"><div class="card-image" style="background-image: url(http://s21.q4cdn.com/616071541/files/images/newsroom/PR_2019/NEWSROOM-Livery-1200x628.jpg	)"></div></a>
	<div class="content">
		<div class="card-title"><a href="http://news.aa.com/coronavirus/">American Airlines Group Reports First-Quarter 2020 Financial Results</a></div>
		<div class="card-excerpt">American Airlines Group Inc. (NASDAQ: AAL) today reported its first-quarter 2020 financial results, including: -- First-quarter net loss of $2.2 billion, or ($5.26) per share. Excluding net special items,</div>
		<div class="card-meta">
			<span class="card-provider">MarketWatch</span> • <span class="card-date">4/30/2020</span>
		</div>
	</div>
  </div>
</div>
<div class="col-md-6 col-sm-12">
  <div class="content-card">
	<a href="http://news.aa.com/coronavirus/"><div class="card-image" style="background-image: url(http://s21.q4cdn.com/616071541/files/images/newsroom/PR_2019/NEWSROOM-Livery-1200x628.jpg	)"></div></a>
	<div class="content">
		<div class="card-title"><a href="http://news.aa.com/coronavirus/">Coronavirus Live Updates: Most States Balk at Trump’s Suggestion to Reopen Schools</a></div>
		<div class="card-excerpt">School officials balk at calls for returning to classrooms this spring. The number of known U.S. cases passed 1 million. Vice President Mike Pence visited the Mayo Clinic without a face mask.</div>
		<div class="card-meta">
			<span class="card-provider">New York Times</span> • <span class="card-date">4/28/2020</span>
		</div>
	</div>
  </div>
</div>
<div class="col-md-6 col-sm-12">
  <div class="content-card">
	<a href="http://news.aa.com/coronavirus/"><div class="card-image" style="background-image: url(http://s21.q4cdn.com/616071541/files/images/newsroom/PR_2019/NEWSROOM-Livery-1200x628.jpg	)"></div></a>
	<div class="content">
		<div class="card-title"><a href="http://news.aa.com/coronavirus/">Live updates: States move to reopen as U.S. coronavirus cases near 1 million; White House issues testing guidance</a></div>
		<div class="card-excerpt">The number confirmed U.S. cases is nearing 1 million. Texas, Ohio, Michigan and several other states will slowly reopen. The CDC added six new symptoms of covid-19.</div>
		<div class="card-meta">
			<span class="card-provider">Washington Post</span> • <span class="card-date">4/28/2020</span>
		</div>
	</div>
  </div>
</div>
<div class="col-md-6 col-sm-12">
  <div class="content-card">
	<a href="http://news.aa.com/coronavirus/"><div class="card-image" style="background-image: url(http://s21.q4cdn.com/616071541/files/images/newsroom/PR_2019/NEWSROOM-Livery-1200x628.jpg	)"></div></a>
	<div class="content">
		<div class="card-title"><a href="http://news.aa.com/coronavirus/">Coronavirus economic updates: Crude oil prices plummet to below $1 a barrel</a></div>
		<div class="card-excerpt">The coronavirus pandemic has quickly evolved from a health care crisis to a financial one, shuttering businesses, upending industries and sending financial markets reeling. Here's the latest news on how the COVID-19 crisis is affecting the economy.</div>
		<div class="card-meta">
			<span class="card-provider">ABC</span> • <span class="card-date">4/20/2020</span>
		</div>
	</div>
  </div>
</div>

</div>

