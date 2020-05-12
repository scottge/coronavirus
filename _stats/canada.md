---
category: stats
title: "Canada Coronavirus (COVID-19) Live Stats"
excerpt: "Live stats of COVID-19 in Canada. Total Cases: 71264 (-), Deaths: 5116 (-), Recoveries: 8210(-)."
publishedDateTime: 2020-05-12T09:45:10Z
updatedDateTime: 2020-05-12T09:45:10Z
webUrl: "https://smartable.ai/apps/coronavirus/stats/canada/"
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
  - Coronavirus in Canada

images:
  - url: "https://smartable.azureedge.net/coronavirus/sites/2/2020/canada.jpg"
    width: 900
    height: 564
    title: "Canada Coronavirus (COVID-19) Live Stats"

---
<div class="total-stats" style="text-align: center;">
    <h3>
	    <div style="font-size: 18px; font-weight: 400;">Total Confirmed Cases:</div>
	    71264 (-)
    </h3>
    <h3>
	    <div style="font-size: 18px; font-weight: 400;">Total Deaths:</div>
	    5116 (-)
    </h3>
    <h3>
	    <div style="font-size: 18px; font-weight: 400;">Total Recovered:</div>
	    8210 (-)
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
      ['1/22/2020', 0, 0, 0],['1/23/2020', 0, 0, 0],['1/24/2020', 0, 0, 0],['1/25/2020', 0, 0, 0],['1/26/2020', 1, 0, 0],['1/27/2020', 1, 0, 0],['1/28/2020', 2, 0, 0],['1/29/2020', 2, 0, 0],['1/30/2020', 2, 0, 0],['1/31/2020', 4, 0, 0],['2/1/2020', 4, 0, 0],['2/2/2020', 4, 0, 0],['2/3/2020', 4, 0, 0],['2/4/2020', 4, 0, 0],['2/5/2020', 5, 0, 0],['2/6/2020', 5, 0, 0],['2/7/2020', 7, 0, 0],['2/8/2020', 7, 0, 0],['2/9/2020', 7, 0, 0],['2/10/2020', 7, 0, 0],['2/11/2020', 7, 0, 0],['2/12/2020', 7, 0, 1],['2/13/2020', 7, 0, 1],['2/14/2020', 7, 0, 1],['2/15/2020', 7, 0, 1],['2/16/2020', 7, 0, 1],['2/17/2020', 8, 0, 1],['2/18/2020', 8, 0, 1],['2/19/2020', 8, 0, 1],['2/20/2020', 8, 0, 3],['2/21/2020', 9, 0, 3],['2/22/2020', 9, 0, 3],['2/23/2020', 9, 0, 3],['2/24/2020', 10, 0, 3],['2/25/2020', 11, 0, 3],['2/26/2020', 11, 0, 6],['2/27/2020', 13, 0, 9],['2/28/2020', 14, 0, 9],['2/29/2020', 20, 0, 9],['3/1/2020', 24, 0, 9],['3/2/2020', 27, 0, 9],['3/3/2020', 30, 0, 9],['3/4/2020', 33, 0, 9],['3/5/2020', 37, 0, 9],['3/6/2020', 49, 0, 9],['3/7/2020', 54, 0, 12],['3/8/2020', 64, 0, 12],['3/9/2020', 77, 1, 12],['3/10/2020', 79, 1, 12],['3/11/2020', 108, 1, 12],['3/12/2020', 117, 1, 12],['3/13/2020', 196, 1, 12],['3/14/2020', 250, 1, 12],['3/15/2020', 339, 1, 12],['3/16/2020', 439, 4, 13],['3/17/2020', 589, 8, 13],['3/18/2020', 732, 9, 13],['3/19/2020', 872, 12, 13],['3/20/2020', 1085, 12, 13],['3/21/2020', 1309, 19, 14],['3/22/2020', 1470, 21, 14],['3/23/2020', 2089, 25, 14],['3/24/2020', 2791, 28, 114],['3/25/2020', 3316, 34, 187],['3/26/2020', 4046, 39, 188],['3/27/2020', 4684, 55, 256],['3/28/2020', 5576, 60, 466],['3/29/2020', 6280, 63, 466],['3/30/2020', 7398, 79, 466],['3/31/2020', 8527, 100, 1592],['4/1/2020', 9560, 108, 1324],['4/2/2020', 11284, 138, 1735],['4/3/2020', 12437, 178, 2175],['4/4/2020', 12978, 217, 2577],['4/5/2020', 15749, 258, 3012],['4/6/2020', 16563, 338, 3256],['4/7/2020', 17872, 374, 3791],['4/8/2020', 19141, 405, 4154],['4/9/2020', 20654, 502, 5162],['4/10/2020', 22148, 569, 5855],['4/11/2020', 23316, 653, 6589],['4/12/2020', 24381, 717, 7123],['4/13/2020', 25680, 780, 7758],['4/14/2020', 27063, 903, 8210],['4/15/2020', 28253, 1010, 8210],['4/16/2020', 30987, 1235, 8210],['4/17/2020', 32857, 1357, 8210],['4/18/2020', 34386, 1520, 8210],['4/19/2020', 36040, 1625, 8210],['4/20/2020', 37933, 1753, 8210],['4/21/2020', 39489, 1915, 8210],['4/22/2020', 41664, 2080, 8210],['4/23/2020', 43300, 2240, 8210],['4/24/2020', 44540, 2385, 8210],['4/25/2020', 46363, 2564, 8210],['4/26/2020', 48010, 2678, 8210],['4/27/2020', 49616, 2840, 8210],['4/28/2020', 51150, 2982, 8210],['4/29/2020', 52865, 3154, 8210],['4/30/2020', 54457, 3309, 8210],['5/1/2020', 56189, 3494, 8210],['5/2/2020', 57927, 3684, 8210],['5/3/2020', 60504, 3795, 8210],['5/4/2020', 61957, 4006, 8210],['5/5/2020', 63216, 4190, 8210],['5/6/2020', 64694, 4366, 8210],['5/7/2020', 66204, 4541, 8210],['5/8/2020', 67676, 4697, 8210],['5/9/2020', 68920, 4823, 8210],['5/10/2020', 70091, 4991, 8210],['5/11/2020', 71264, 5116, 8210],['5/12/2020', 71264, 5116, 8210],
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
      ['Location', 'Total Cases', 'Total Deaths'],
      ["Alberta", 6300, 117],["British Columbia", 2353, 131],["Cruise Ship: Grand Princess", 13, 0],["Manitoba", 289, 7],["New Brunswick", 120, 0],["Newfoundland and Labrador", 261, 3],["Northwest Territories", 5, 0],["Nova Scotia", 1019, 48],["Ontario", 21817, 1788],["Prince Edward Island", 27, 0],["Quebec", 38480, 3014],["Saskatchewan", 568, 7],["Yukon", 11, 0],["Diamond Princess", 1, 1],
    ]);
    var options = {
      backgroundColor: {fill:'transparent',stroke:'#FFF' ,strokeWidth:0 }, 
      region: 'CA', 
      resolution: 'provinces',
      colorAxis: {
          colors: ['#ED9CA1', '#f60109', '#7A0109']
      }
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
      [{v:"Alberta", f:"<a href='https://smartable.ai/apps/coronavirus/stats/canada-ab/'>Alberta</a>"}, 6300, 0, 6183, 117, 0, 0],[{v:"British Columbia", f:"<a href='https://smartable.ai/apps/coronavirus/stats/canada-bc/'>British Columbia</a>"}, 2353, 0, 2222, 131, 0, 0],[{v:"Cruise Ship: Grand Princess", f:"Cruise Ship: Grand Princess"}, 13, 0, 13, 0, 0, 0],[{v:"Manitoba", f:"Manitoba"}, 289, 0, 282, 7, 0, 0],[{v:"New Brunswick", f:"New Brunswick"}, 120, 0, 120, 0, 0, 0],[{v:"Newfoundland and Labrador", f:"Newfoundland and Labrador"}, 261, 0, 258, 3, 0, 0],[{v:"Northwest Territories", f:"Northwest Territories"}, 5, 0, 5, 0, 0, 0],[{v:"Nova Scotia", f:"Nova Scotia"}, 1019, 0, 971, 48, 0, 0],[{v:"Ontario", f:"<a href='https://smartable.ai/apps/coronavirus/stats/canada-on/'>Ontario</a>"}, 21817, 0, 20029, 1788, 0, 0],[{v:"Prince Edward Island", f:"Prince Edward Island"}, 27, 0, 27, 0, 0, 0],[{v:"Quebec", f:"<a href='https://smartable.ai/apps/coronavirus/stats/canada-qc/'>Quebec</a>"}, 38480, 0, 35466, 3014, 0, 0],[{v:"Saskatchewan", f:"Saskatchewan"}, 568, 0, 561, 7, 0, 0],[{v:"Yukon", f:"Yukon"}, 11, 0, 11, 0, 0, 0],[{v:"Diamond Princess", f:"Diamond Princess"}, 1, 0, 0, 1, 0, 0],
    ]);
    data.setProperty(0, 0, 'style', 'min-width:100px');
    var table = new google.visualization.Table(document.getElementById('geo_table'));
    table.draw(data, {allowHtml: true, sortColumn: 2, sortAscending: false, width: '660px', height: '100%'});
  }
</script>

<span style="font-size: 13px">All COVID-19 data displayed on the page is available through our FREE <a href="https://developer.smartable.ai">API program</a>. This Canada Coronavirus (COVID-19) Live Stats is refreshed every hour using credible data sources, including the country/state's official government website, <a href="https://en.wikipedia.org/wiki/2019%E2%80%9320_coronavirus_pandemic" target="_blank">data available on wikipedia pages</a>, latest news reports, <a href="https://systems.jhu.edu/research/public-health/ncov/" target="_blank">Johns Hopkins University CSSE 2019-nCoV Dashboard</a>, <a href="https://www.who.int/emergencies/diseases/novel-coronavirus-2019/situation-reports" target="_blank">WHO Situation Reports</a>, <a href="https://www.cdc.gov/coronavirus/2019-ncov/index.html" target="_blank">CDC Situation Updates</a>, and <a href="https://ncov.dxy.cn/ncovh5/view/pneumonia" target="_blank">DXY.cn</a>.</span>


<h2 id="news" class="center" style="margin-top: 60px; font-size: 25px;">Trending Coronavirus News in Canada</h2>
<div class="row">
<div class="col-md-6 col-sm-12">
  <div class="content-card">
	<a href="https://www.cbc.ca/news/canada/nova-scotia/nova-scotia-covid-19-update-saturday-may-9-1.5563119"><div class="card-image" style="background-image: url(https://i.cbc.ca/1.5545103.1587826736!/fileImage/httpImage/image.JPG_gen/derivatives/16x9_620/kendra-macdonald-covid-19-qeii-microbiology-lab-halifax.JPG)"></div></a>
	<div class="content">
		<div class="card-title"><a href="https://www.cbc.ca/news/canada/nova-scotia/nova-scotia-covid-19-update-saturday-may-9-1.5563119">1 more death, 3 new cases of COVID-19 in Nova Scotia</a></div>
		<div class="card-excerpt">Nova Scotia reported one more death, bringing the province's total to 47, and three new cases of COVID-19 on Saturday. The latest death was reported at the Northwood long-term care home in Hailfax, where 41 people have died from the virus.</div>
		<div class="card-meta">
			<span class="card-provider">CBC.ca</span> • <span class="card-date">5/9/2020</span>
		</div>
	</div>
  </div>
</div>
<div class="col-md-6 col-sm-12">
  <div class="content-card">
	<a href="https://www.reuters.com/article/brief-canadas-coronavirus-death-toll-ris-idUSL1N2CR074"><div class="card-image" style="background-image: url(https://s4.reutersmedia.net/resources_v3/images/rcom-default.png)"></div></a>
	<div class="content">
		<div class="card-title"><a href="https://www.reuters.com/article/brief-canadas-coronavirus-death-toll-ris-idUSL1N2CR074">BRIEF-Canada's coronavirus death toll rises 3.5% to 4,628</a></div>
		<div class="card-excerpt">CANADA’S TOTAL CORONAVIRUS CASES RISE TO 66,780 FROM TO 65,399 ON MAY 8; 4,628 DEATHS, UP FROM 4,471 - PUBLIC HEALTH AGENCY DATA (Reporting by Rod Nickel) Our Standards:The Thomson Reuters Trust Principles.</div>
		<div class="card-meta">
			<span class="card-provider">Reuters</span> • <span class="card-date">5/9/2020</span>
		</div>
	</div>
  </div>
</div>
<div class="col-md-6 col-sm-12">
  <div class="content-card">
	<a href="https://www.cbc.ca/news/canada/montreal/covid-19-quebec-may-8-1.5560951"><div class="card-image" style="background-image: url(https://i.cbc.ca/1.5560771.1588902843!/fileImage/httpImage/image.jpg_gen/derivatives/16x9_620/mask.jpg)"></div></a>
	<div class="content">
		<div class="card-title"><a href="https://www.cbc.ca/news/canada/montreal/covid-19-quebec-may-8-1.5560951">COVID-19 in Quebec: What you need to know on Friday</a></div>
		<div class="card-excerpt">Quebec's director of public health, Dr. Horacio Arruda, offered more details on the province's testing for COVID-19, which has faced criticism from experts as the province opens up.</div>
		<div class="card-meta">
			<span class="card-provider">CBC.ca</span> • <span class="card-date">5/9/2020</span>
		</div>
	</div>
  </div>
</div>
<div class="col-md-6 col-sm-12">
  <div class="content-card">
	<a href="https://www.energeticcity.ca/2020/05/coronavirus-how-long-will-pandemic-related-job-losses-last-in-canada/"><div class="card-image" style="background-image: url(https://149382914.v2.pressablecdn.com/wp-content/uploads/2020/05/182739/coronavirus-how-long-will-pandemic-related-job-losses-last-in-canada.jpg)"></div></a>
	<div class="content">
		<div class="card-title"><a href="https://www.energeticcity.ca/2020/05/coronavirus-how-long-will-pandemic-related-job-losses-last-in-canada/">Coronavirus: How long will pandemic-related job losses last in Canada?</a></div>
		<div class="card-excerpt">New figures are painting a grim picture of the coronavirus pandemic’s impact on Canadians: the economy shed nearly two million jobs in April, driving the tota</div>
		<div class="card-meta">
			<span class="card-provider">Energeticcity</span> • <span class="card-date">5/8/2020</span>
		</div>
	</div>
  </div>
</div>
<div class="col-md-6 col-sm-12">
  <div class="content-card">
	<a href="https://www.reuters.com/article/us-canada-fighterjets/canada-gives-bidders-more-time-to-submit-fighter-jet-bids-cites-coronavirus-idUSKBN22K2NR"><div class="card-image" style="background-image: url(https://s4.reutersmedia.net/resources_v3/images/rcom-default.png)"></div></a>
	<div class="content">
		<div class="card-title"><a href="https://www.reuters.com/article/us-canada-fighterjets/canada-gives-bidders-more-time-to-submit-fighter-jet-bids-cites-coronavirus-idUSKBN22K2NR">Canada gives bidders more time to submit fighter jet bids, cites coronavirus</a></div>
		<div class="card-excerpt">OTTAWA (Reuters) - Canada is giving potential bidders another month to submit proposals for a multibillion-dollar contract to supply 88 new fighter jets, time needed due to complications caused by the coronavirus outbreak. The move is the latest delay in a ...</div>
		<div class="card-meta">
			<span class="card-provider">Reuters</span> • <span class="card-date">5/8/2020</span>
		</div>
	</div>
  </div>
</div>
<div class="col-md-6 col-sm-12">
  <div class="content-card">
	<a href="https://www.cbc.ca/news/canada/calgary/canada-post-main-calgary-covid-outbreak-1.5562431"><div class="card-image" style="background-image: url(https://i.cbc.ca/1.2460240.1386789863!/fileImage/httpImage/image.jpg_gen/derivatives/16x9_620/canada-post-parcel-service.jpg)"></div></a>
	<div class="content">
		<div class="card-title"><a href="https://www.cbc.ca/news/canada/calgary/canada-post-main-calgary-covid-outbreak-1.5562431">COVID-19 outbreak confirmed at Canada Post main plant in Calgary</a></div>
		<div class="card-excerpt">There is now an outbreak of COVID-19 at Canada Post's main plant in Calgary, Alberta's chief medical officer of health, Dr. Deena Hinshaw, confirmed Friday.</div>
		<div class="card-meta">
			<span class="card-provider">CBC.ca</span> • <span class="card-date">5/8/2020</span>
		</div>
	</div>
  </div>
</div>
<div class="col-md-6 col-sm-12">
  <div class="content-card">
	<a href="https://www.cbc.ca/news/business/housing-starts-april-1.5561214"><div class="card-image" style="background-image: url(https://i.cbc.ca/1.5358323.1573674927!/cumulusImage/httpImage/image.jpg_gen/derivatives/16x9_620/cranes-front-spadina.jpg)"></div></a>
	<div class="content">
		<div class="card-title"><a href="https://www.cbc.ca/news/business/housing-starts-april-1.5561214">Housing starts up in some parts of Canada despite COVID-19</a></div>
		<div class="card-excerpt">Canada Mortgage and Housing Corp. says construction of multi-unit housing projects remained strong in some provinces last month despite the fight against the COVID-19 pandemic.</div>
		<div class="card-meta">
			<span class="card-provider">CBC.ca</span> • <span class="card-date">5/8/2020</span>
		</div>
	</div>
  </div>
</div>
<div class="col-md-6 col-sm-12">
  <div class="content-card">
	<a href="https://atlantic.ctvnews.ca/new-brunswick-loosens-covid-19-restrictions-a-second-time-1.4931077"><div class="card-image" style="background-image: url(https://beta.ctvnews.ca/content/dam/ctvnews/images/2020/5/8/1_4931121.jpg?cache_timestamp=1588960549784)"></div></a>
	<div class="content">
		<div class="card-title"><a href="https://atlantic.ctvnews.ca/new-brunswick-loosens-covid-19-restrictions-a-second-time-1.4931077">New Brunswick loosens COVID-19 restrictions a second time</a></div>
		<div class="card-excerpt">Two weeks after taking the first step, New Brunswick is making a second larger step to try to get back to some semblance of normal. "Today, we announce a further loosening of restrictions," said Premier Blaine Higgs at a news conference in Fredericton to announce what businesses can open under its state of emergency.</div>
		<div class="card-meta">
			<span class="card-provider">CTV News</span> • <span class="card-date">5/8/2020</span>
		</div>
	</div>
  </div>
</div>
<div class="col-md-6 col-sm-12">
  <div class="content-card">
	<a href="https://globalnews.ca/news/6920177/canada-2-million-jobs-lost-april-covid-19-statcan/"><div class="card-image" style="background-image: url(https://thecanadianpress-a.akamaihd.net/graphics/2020/static/cp-unemployment-apr.png)"></div></a>
	<div class="content">
		<div class="card-title"><a href="https://globalnews.ca/news/6920177/canada-2-million-jobs-lost-april-covid-19-statcan/">Canada shed 2 million jobs in April amid COVID-19: StatCan</a></div>
		<div class="card-excerpt">Canada shed nearly two million jobs in April, as the novel coronavirus pandemic tore through the Canadian economy. [ Sign up for our Health IQ newsletter for the latest coronaviru</div>
		<div class="card-meta">
			<span class="card-provider">Global News</span> • <span class="card-date">5/8/2020</span>
		</div>
	</div>
  </div>
</div>
<div class="col-md-6 col-sm-12">
  <div class="content-card">
	<a href="https://www.thestar.com/news/canada/2020/05/08/coronavirus-updates-may-8-covid-19-canada.html"><div class="card-image" style="background-image: url(https://images.thestar.com/Q0UQsDUzXkeiJeo3zN3Amhi_l0E=/1200x800/smart/filters:cb(1588931414984)/https://www.thestar.com/content/dam/thestar/news/canada/2020/05/08/coronavirus-updates-may-8-covid-19-canada/rpjsecretblossoms02.jpg)"></div></a>
	<div class="content">
		<div class="card-title"><a href="https://www.thestar.com/news/canada/2020/05/08/coronavirus-updates-may-8-covid-19-canada.html">Coronavirus updates: May 8 COVID-19 Canada</a></div>
		<div class="card-excerpt">South Korea on Friday advised nightclubs and similar venues to close for a month and may delay the reopening of schools after linking more than a</div>
		<div class="card-meta">
			<span class="card-provider">The Star</span> • <span class="card-date">5/8/2020</span>
		</div>
	</div>
  </div>
</div>

</div>

