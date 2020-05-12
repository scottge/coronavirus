---
category: stats
title: "Sweden Coronavirus (COVID-19) Live Stats"
excerpt: "Live stats of COVID-19 in Sweden. Total Cases: 26670 (+348), Deaths: 3256 (+31), Recoveries: 4971(-)."
publishedDateTime: 2020-05-12T01:45:10Z
updatedDateTime: 2020-05-12T01:45:10Z
webUrl: "https://smartable.ai/apps/coronavirus/stats/sweden/"
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
  - Coronavirus in Europe

images:
  - url: "https://smartable.azureedge.net/coronavirus/sites/2/2020/sweden.jpg"
    width: 900
    height: 564
    title: "Sweden Coronavirus (COVID-19) Live Stats"

---
<div class="total-stats" style="text-align: center;">
    <h3>
	    <div style="font-size: 18px; font-weight: 400;">Total Confirmed Cases:</div>
	    26670 (<span class='red'>+348</span>)
    </h3>
    <h3>
	    <div style="font-size: 18px; font-weight: 400;">Total Deaths:</div>
	    3256 (<span class='red'>+31</span>)
    </h3>
    <h3>
	    <div style="font-size: 18px; font-weight: 400;">Total Recovered:</div>
	    4971 (-)
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
      ['1/22/2020', 0, 0, 0],['1/23/2020', 0, 0, 0],['1/24/2020', 0, 0, 0],['1/25/2020', 0, 0, 0],['1/26/2020', 0, 0, 0],['1/27/2020', 0, 0, 0],['1/28/2020', 0, 0, 0],['1/29/2020', 0, 0, 0],['1/30/2020', 0, 0, 0],['1/31/2020', 1, 0, 0],['2/1/2020', 1, 0, 0],['2/2/2020', 1, 0, 0],['2/3/2020', 1, 0, 0],['2/4/2020', 1, 0, 0],['2/5/2020', 1, 0, 0],['2/6/2020', 1, 0, 0],['2/7/2020', 1, 0, 0],['2/8/2020', 1, 0, 0],['2/9/2020', 1, 0, 0],['2/10/2020', 1, 0, 0],['2/11/2020', 1, 0, 0],['2/12/2020', 1, 0, 0],['2/13/2020', 1, 0, 0],['2/14/2020', 1, 0, 0],['2/15/2020', 1, 0, 0],['2/16/2020', 1, 0, 0],['2/17/2020', 1, 0, 0],['2/18/2020', 1, 0, 0],['2/19/2020', 1, 0, 0],['2/20/2020', 1, 0, 0],['2/21/2020', 1, 0, 0],['2/22/2020', 1, 0, 0],['2/23/2020', 1, 0, 0],['2/24/2020', 1, 0, 0],['2/25/2020', 1, 0, 0],['2/26/2020', 2, 0, 0],['2/27/2020', 7, 0, 0],['2/28/2020', 7, 0, 0],['2/29/2020', 12, 0, 0],['3/1/2020', 14, 0, 0],['3/2/2020', 15, 0, 0],['3/3/2020', 21, 0, 0],['3/4/2020', 35, 0, 0],['3/5/2020', 94, 0, 0],['3/6/2020', 101, 0, 0],['3/7/2020', 161, 0, 0],['3/8/2020', 203, 0, 0],['3/9/2020', 248, 0, 1],['3/10/2020', 355, 0, 1],['3/11/2020', 500, 1, 1],['3/12/2020', 687, 1, 1],['3/13/2020', 814, 1, 1],['3/14/2020', 961, 2, 1],['3/15/2020', 1040, 3, 1],['3/16/2020', 1121, 7, 1],['3/17/2020', 1196, 8, 1],['3/18/2020', 1301, 10, 16],['3/19/2020', 1439, 11, 16],['3/20/2020', 1639, 16, 16],['3/21/2020', 1770, 20, 16],['3/22/2020', 1934, 21, 16],['3/23/2020', 2046, 27, 16],['3/24/2020', 2299, 40, 16],['3/25/2020', 2526, 62, 16],['3/26/2020', 2840, 77, 16],['3/27/2020', 3069, 105, 16],['3/28/2020', 3447, 105, 16],['3/29/2020', 3700, 110, 16],['3/30/2020', 4028, 146, 16],['3/31/2020', 4435, 180, 16],['4/1/2020', 4947, 239, 103],['4/2/2020', 5568, 308, 103],['4/3/2020', 6131, 358, 205],['4/4/2020', 6443, 373, 205],['4/5/2020', 6830, 401, 205],['4/6/2020', 7206, 477, 205],['4/7/2020', 7693, 591, 205],['4/8/2020', 8419, 687, 205],['4/9/2020', 9141, 793, 205],['4/10/2020', 9685, 870, 381],['4/11/2020', 10151, 887, 381],['4/12/2020', 10483, 899, 381],['4/13/2020', 10948, 919, 381],['4/14/2020', 11445, 1033, 381],['4/15/2020', 11927, 1203, 381],['4/16/2020', 12540, 1333, 550],['4/17/2020', 13216, 1400, 550],['4/18/2020', 13822, 1511, 550],['4/19/2020', 14385, 1540, 550],['4/20/2020', 14777, 1580, 550],['4/21/2020', 15322, 1765, 550],['4/22/2020', 16004, 1937, 550],['4/23/2020', 16755, 2021, 550],['4/24/2020', 17567, 2152, 1005],['4/25/2020', 18177, 2192, 1005],['4/26/2020', 18640, 2194, 1005],['4/27/2020', 18926, 2274, 1005],['4/28/2020', 19621, 2355, 1005],['4/29/2020', 20302, 2462, 1005],['4/30/2020', 21092, 2586, 1005],['5/1/2020', 21587, 2627, 1005],['5/2/2020', 22082, 2669, 1005],['5/3/2020', 22317, 2679, 1005],['5/4/2020', 22721, 2769, 4074],['5/5/2020', 23216, 2854, 4074],['5/6/2020', 23918, 2941, 4074],['5/7/2020', 24623, 3040, 4971],['5/8/2020', 25265, 3175, 4971],['5/9/2020', 25921, 3220, 4971],['5/10/2020', 26322, 3225, 4971],['5/11/2020', 26670, 3256, 4971],
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
      ["Sweden", 26670, 3256]
    ]);
    var options = {
      backgroundColor: {fill:'transparent',stroke:'#FFF' ,strokeWidth:0 }, 
      region: 'SE',
      resolution: 'countries', 
      legend: 'none',
      colorAxis: {
          colors: ['#FFE2E2', '#f60109']
      }
    };
    var chart = new google.visualization.GeoChart(document.getElementById('geo_chart'));
    chart.draw(data, options);
  };
</script>



<span style="font-size: 13px">All COVID-19 data displayed on the page is available through our FREE <a href="https://developer.smartable.ai">API program</a>. This Sweden Coronavirus (COVID-19) Live Stats is refreshed every hour using credible data sources, including the country/state's official government website, <a href="https://en.wikipedia.org/wiki/2019%E2%80%9320_coronavirus_pandemic" target="_blank">data available on wikipedia pages</a>, latest news reports, <a href="https://systems.jhu.edu/research/public-health/ncov/" target="_blank">Johns Hopkins University CSSE 2019-nCoV Dashboard</a>, <a href="https://www.who.int/emergencies/diseases/novel-coronavirus-2019/situation-reports" target="_blank">WHO Situation Reports</a>, <a href="https://www.cdc.gov/coronavirus/2019-ncov/index.html" target="_blank">CDC Situation Updates</a>, and <a href="https://ncov.dxy.cn/ncovh5/view/pneumonia" target="_blank">DXY.cn</a>.</span>


<h2 id="news" class="center" style="margin-top: 60px; font-size: 25px;">Trending Coronavirus News in Sweden</h2>
<div class="row">
<div class="col-md-6 col-sm-12">
  <div class="content-card">
	<a href="https://apnews.com/1d7916cf6e48b7a231b894ef9cda1a19"><div class="card-image" style="background-image: url(https://storage.googleapis.com/afs-prod/media/7fa2d715e4bb461580da9fc8cb96895d/3000.jpeg)"></div></a>
	<div class="content">
		<div class="card-title"><a href="https://apnews.com/1d7916cf6e48b7a231b894ef9cda1a19">Coronavirus takes a toll in Sweden’s immigrant community</a></div>
		<div class="card-excerpt">The flight from Italy was one of the last arrivals that day at the Stockholm airport. A Swedish couple in their 50s walked up and loaded their skis into Razzak</div>
		<div class="card-meta">
			<span class="card-provider">Associated Press</span> • <span class="card-date">5/8/2020</span>
		</div>
	</div>
  </div>
</div>
<div class="col-md-6 col-sm-12">
  <div class="content-card">
	<a href="https://www.wsj.com/articles/sweden-has-avoided-a-coronavirus-lockdown-its-economy-is-hurting-anyway-11588870062"><div class="card-image" style="background-image: url(https://images.wsj.net/im-183866/social)"></div></a>
	<div class="content">
		<div class="card-title"><a href="https://www.wsj.com/articles/sweden-has-avoided-a-coronavirus-lockdown-its-economy-is-hurting-anyway-11588870062">Sweden has Avoided a Coronavirus Lockdown. Its Economy Is Hurting Anyway.</a></div>
		<div class="card-excerpt">Sweden’s decision not to impose a mandatory national lockdown has drawn global attention. But it turns out the situation here is not as different as it might first appear.</div>
		<div class="card-meta">
			<span class="card-provider">Wall Street Journal</span> • <span class="card-date">5/7/2020</span>
		</div>
	</div>
  </div>
</div>
<div class="col-md-6 col-sm-12">
  <div class="content-card">
	<a href="https://www.newsweek.com/sweden-coronavirus-deaths-children-lockdown-1502548"><div class="card-image" style="background-image: url(https://d.newsweek.com/en/full/1588051/cafe-stockholm-sweden-march-2020-coronavirus.jpg)"></div></a>
	<div class="content">
		<div class="card-title"><a href="https://www.newsweek.com/sweden-coronavirus-deaths-children-lockdown-1502548">Sweden's Coronavirus Death Toll 'Horrifying' Says Scientist Behind Country's Anti-Lockdown Strategy</a></div>
		<div class="card-excerpt">Sweden's death rate is reported to be more than double that of the U.S., nearly six times that of Norway and nearly triple the death rates of Finland and Denmark, as of Thursday.</div>
		<div class="card-meta">
			<span class="card-provider">Newsweek</span> • <span class="card-date">5/7/2020</span>
		</div>
	</div>
  </div>
</div>
<div class="col-md-6 col-sm-12">
  <div class="content-card">
	<a href="https://www.reuters.com/article/us-health-coronavirus-sweden-casualties-idUSKBN22J1UV"><div class="card-image" style="background-image: url(https://s4.reutersmedia.net/resources_v3/images/rcom-default.png)"></div></a>
	<div class="content">
		<div class="card-title"><a href="https://www.reuters.com/article/us-health-coronavirus-sweden-casualties-idUSKBN22J1UV">COVID-19 deaths in Sweden pass 3,000: Public Health Agency</a></div>
		<div class="card-excerpt">Deaths in Sweden from COVID-19 passed 3,000 on Thursday, the Public Health Agency said, far more than in neighbouring Nordic countries.</div>
		<div class="card-meta">
			<span class="card-provider">Reuters</span> • <span class="card-date">5/7/2020</span>
		</div>
	</div>
  </div>
</div>
<div class="col-md-6 col-sm-12">
  <div class="content-card">
	<a href="https://www.businessinsider.com/coronavirus-sweden-lockdown-chief-says-high-death-toll-was-surprise-2020-5"><div class="card-image" style="background-image: url(https://i.insider.com/5eb2806c48d92c48774169b5?width=1200&format=jpeg)"></div></a>
	<div class="content">
		<div class="card-title"><a href="https://www.businessinsider.com/coronavirus-sweden-lockdown-chief-says-high-death-toll-was-surprise-2020-5">The head of Sweden's no-lockdown coronavirus plan said its heavy death toll 'came as a surprise'</a></div>
		<div class="card-excerpt">Or a tip on how your town or community is handling the pandemic? Please email covidtips@businessinsider.com and tell us your story. Get the latest coronavirus business & economic impact analysis from Business Insider Intelligence on how COVID-19 is affecting industries.</div>
		<div class="card-meta">
			<span class="card-provider">Business Insider</span> • <span class="card-date">5/6/2020</span>
		</div>
	</div>
  </div>
</div>

</div>

