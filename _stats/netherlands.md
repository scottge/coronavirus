---
category: stats
title: "Netherlands Coronavirus (COVID-19) Live Stats"
excerpt: "Live stats of COVID-19 in Netherlands. Total Cases: 42788 (+161), Deaths: 5456 (+16), Recoveries: 250(-)."
publishedDateTime: 2020-05-12T05:45:11Z
updatedDateTime: 2020-05-12T05:45:11Z
webUrl: "https://smartable.ai/apps/coronavirus/stats/netherlands/"
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
  - url: "https://smartable.azureedge.net/coronavirus/sites/2/2020/netherlands.jpg"
    width: 900
    height: 564
    title: "Netherlands Coronavirus (COVID-19) Live Stats"

---
<div class="total-stats" style="text-align: center;">
    <h3>
	    <div style="font-size: 18px; font-weight: 400;">Total Confirmed Cases:</div>
	    42788 (<span class='red'>+161</span>)
    </h3>
    <h3>
	    <div style="font-size: 18px; font-weight: 400;">Total Deaths:</div>
	    5456 (<span class='red'>+16</span>)
    </h3>
    <h3>
	    <div style="font-size: 18px; font-weight: 400;">Total Recovered:</div>
	    250 (-)
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
      ['1/22/2020', 0, 0, 0],['1/23/2020', 0, 0, 0],['1/24/2020', 0, 0, 0],['1/25/2020', 0, 0, 0],['1/26/2020', 0, 0, 0],['1/27/2020', 0, 0, 0],['1/28/2020', 0, 0, 0],['1/29/2020', 0, 0, 0],['1/30/2020', 0, 0, 0],['1/31/2020', 0, 0, 0],['2/1/2020', 0, 0, 0],['2/2/2020', 0, 0, 0],['2/3/2020', 0, 0, 0],['2/4/2020', 0, 0, 0],['2/5/2020', 0, 0, 0],['2/6/2020', 0, 0, 0],['2/7/2020', 0, 0, 0],['2/8/2020', 0, 0, 0],['2/9/2020', 0, 0, 0],['2/10/2020', 0, 0, 0],['2/11/2020', 0, 0, 0],['2/12/2020', 0, 0, 0],['2/13/2020', 0, 0, 0],['2/14/2020', 0, 0, 0],['2/15/2020', 0, 0, 0],['2/16/2020', 0, 0, 0],['2/17/2020', 0, 0, 0],['2/18/2020', 0, 0, 0],['2/19/2020', 0, 0, 0],['2/20/2020', 0, 0, 0],['2/21/2020', 0, 0, 0],['2/22/2020', 0, 0, 0],['2/23/2020', 0, 0, 0],['2/24/2020', 0, 0, 0],['2/25/2020', 0, 0, 0],['2/26/2020', 0, 0, 0],['2/27/2020', 1, 0, 0],['2/28/2020', 1, 0, 0],['2/29/2020', 6, 0, 0],['3/1/2020', 10, 0, 0],['3/2/2020', 18, 0, 0],['3/3/2020', 24, 0, 0],['3/4/2020', 38, 0, 0],['3/5/2020', 82, 0, 0],['3/6/2020', 128, 1, 0],['3/7/2020', 188, 1, 0],['3/8/2020', 265, 3, 0],['3/9/2020', 321, 3, 0],['3/10/2020', 382, 4, 0],['3/11/2020', 503, 5, 0],['3/12/2020', 614, 5, 2],['3/13/2020', 804, 10, 2],['3/14/2020', 959, 12, 2],['3/15/2020', 1135, 20, 2],['3/16/2020', 1413, 24, 2],['3/17/2020', 1705, 43, 2],['3/18/2020', 2051, 58, 2],['3/19/2020', 2460, 76, 2],['3/20/2020', 2994, 106, 2],['3/21/2020', 3631, 136, 2],['3/22/2020', 4204, 179, 2],['3/23/2020', 4749, 213, 2],['3/24/2020', 5560, 276, 2],['3/25/2020', 6412, 356, 3],['3/26/2020', 7431, 434, 3],['3/27/2020', 8603, 546, 3],['3/28/2020', 9762, 639, 3],['3/29/2020', 10866, 771, 250],['3/30/2020', 11750, 864, 250],['3/31/2020', 12595, 1039, 250],['4/1/2020', 13614, 1173, 250],['4/2/2020', 14697, 1339, 250],['4/3/2020', 15723, 1487, 250],['4/4/2020', 16627, 1651, 250],['4/5/2020', 17851, 1766, 250],['4/6/2020', 18803, 1867, 250],['4/7/2020', 19580, 2101, 250],['4/8/2020', 20549, 2248, 250],['4/9/2020', 21762, 2396, 250],['4/10/2020', 23097, 2511, 250],['4/11/2020', 24413, 2643, 250],['4/12/2020', 25587, 2737, 250],['4/13/2020', 26551, 2823, 250],['4/14/2020', 27419, 2945, 250],['4/15/2020', 28153, 3134, 250],['4/16/2020', 29214, 3315, 250],['4/17/2020', 30449, 3459, 250],['4/18/2020', 31589, 3601, 250],['4/19/2020', 32655, 3684, 250],['4/20/2020', 33405, 3751, 250],['4/21/2020', 34134, 3916, 250],['4/22/2020', 34842, 4054, 250],['4/23/2020', 35729, 4177, 250],['4/24/2020', 36535, 4289, 250],['4/25/2020', 37190, 4409, 250],['4/26/2020', 37845, 4475, 250],['4/27/2020', 38245, 4518, 250],['4/28/2020', 38416, 4566, 250],['4/29/2020', 38802, 4711, 250],['4/30/2020', 39316, 4795, 250],['5/1/2020', 39776, 4891, 250],['5/2/2020', 40236, 4987, 250],['5/3/2020', 40571, 5056, 250],['5/4/2020', 40770, 5082, 250],['5/5/2020', 41087, 5168, 250],['5/6/2020', 41319, 5204, 250],['5/7/2020', 41774, 5288, 250],['5/8/2020', 42093, 5359, 250],['5/9/2020', 42382, 5422, 250],['5/10/2020', 42627, 5440, 250],['5/11/2020', 42788, 5456, 250],
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
      ["Netherlands", 42788, 5456]
    ]);
    var options = {
      backgroundColor: {fill:'transparent',stroke:'#FFF' ,strokeWidth:0 }, 
      region: 'NL',
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



<span style="font-size: 13px">All COVID-19 data displayed on the page is available through our FREE <a href="https://developer.smartable.ai">API program</a>. This Netherlands Coronavirus (COVID-19) Live Stats is refreshed every hour using credible data sources, including the country/state's official government website, <a href="https://en.wikipedia.org/wiki/2019%E2%80%9320_coronavirus_pandemic" target="_blank">data available on wikipedia pages</a>, latest news reports, <a href="https://systems.jhu.edu/research/public-health/ncov/" target="_blank">Johns Hopkins University CSSE 2019-nCoV Dashboard</a>, <a href="https://www.who.int/emergencies/diseases/novel-coronavirus-2019/situation-reports" target="_blank">WHO Situation Reports</a>, <a href="https://www.cdc.gov/coronavirus/2019-ncov/index.html" target="_blank">CDC Situation Updates</a>, and <a href="https://ncov.dxy.cn/ncovh5/view/pneumonia" target="_blank">DXY.cn</a>.</span>


<h2 id="news" class="center" style="margin-top: 60px; font-size: 25px;">Trending Coronavirus News in Netherlands</h2>
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

