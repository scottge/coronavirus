---
category: stats
title: "Australia Coronavirus (COVID-19) Live Stats"
excerpt: "Live stats of COVID-19 in Australia. Total Cases: 6971 (-), Deaths: 97 (-), Recoveries: 6231(+1)."
publishedDateTime: 2020-05-12T14:45:11Z
updatedDateTime: 2020-05-12T14:45:11Z
webUrl: "https://smartable.ai/apps/coronavirus/stats/australia/"
type: article
heat: 500

provider:
  name: Smartable AI
  domain: smartable.ai
  images:
    - url: "https://smartable.azureedge.net/media/2020/02/logo.png"
      width: 50
      height: 50

topics:
  - Coronavirus

images:
  - url: "https://smartable.azureedge.net/coronavirus/sites/2/2020/australia.jpg"
    width: 900
    height: 564
    title: "Australia Coronavirus (COVID-19) Live Stats"

---
<div class="total-stats" style="text-align: center;">
    <h3>
	    <div style="font-size: 18px; font-weight: 400;">Total Confirmed Cases:</div>
	    6971 (-)
    </h3>
    <h3>
	    <div style="font-size: 18px; font-weight: 400;">Total Deaths:</div>
	    97 (-)
    </h3>
    <h3>
	    <div style="font-size: 18px; font-weight: 400;">Total Recovered:</div>
	    6231 (<span class='green'>+1</span>)
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
      ['1/22/2020', 0, 0, 0],['1/23/2020', 0, 0, 0],['1/24/2020', 0, 0, 0],['1/25/2020', 0, 0, 0],['1/26/2020', 4, 0, 0],['1/27/2020', 5, 0, 0],['1/28/2020', 5, 0, 0],['1/29/2020', 6, 0, 0],['1/30/2020', 8, 0, 2],['1/31/2020', 9, 0, 2],['2/1/2020', 11, 0, 2],['2/2/2020', 12, 0, 2],['2/3/2020', 12, 0, 2],['2/4/2020', 13, 0, 2],['2/5/2020', 13, 0, 2],['2/6/2020', 14, 0, 2],['2/7/2020', 15, 0, 2],['2/8/2020', 15, 0, 2],['2/9/2020', 15, 0, 2],['2/10/2020', 15, 0, 2],['2/11/2020', 15, 0, 2],['2/12/2020', 15, 0, 2],['2/13/2020', 15, 0, 8],['2/14/2020', 15, 0, 8],['2/15/2020', 15, 0, 8],['2/16/2020', 15, 0, 8],['2/17/2020', 15, 0, 10],['2/18/2020', 15, 0, 10],['2/19/2020', 15, 0, 10],['2/20/2020', 15, 0, 10],['2/21/2020', 15, 0, 11],['2/22/2020', 15, 0, 11],['2/23/2020', 15, 0, 11],['2/24/2020', 15, 0, 11],['2/25/2020', 15, 0, 11],['2/26/2020', 15, 0, 11],['2/27/2020', 15, 0, 11],['2/28/2020', 15, 0, 11],['2/29/2020', 25, 0, 11],['3/1/2020', 27, 1, 11],['3/2/2020', 30, 1, 11],['3/3/2020', 39, 1, 11],['3/4/2020', 51, 2, 11],['3/5/2020', 54, 2, 21],['3/6/2020', 60, 2, 21],['3/7/2020', 63, 2, 21],['3/8/2020', 76, 3, 21],['3/9/2020', 91, 3, 21],['3/10/2020', 107, 3, 21],['3/11/2020', 128, 3, 21],['3/12/2020', 128, 3, 21],['3/13/2020', 200, 3, 23],['3/14/2020', 250, 3, 23],['3/15/2020', 297, 3, 23],['3/16/2020', 377, 3, 23],['3/17/2020', 452, 5, 23],['3/18/2020', 568, 6, 23],['3/19/2020', 681, 6, 26],['3/20/2020', 791, 7, 26],['3/21/2020', 1071, 7, 26],['3/22/2020', 1314, 7, 88],['3/23/2020', 1682, 7, 119],['3/24/2020', 2318, 8, 119],['3/25/2020', 2364, 8, 119],['3/26/2020', 3143, 13, 194],['3/27/2020', 3143, 13, 194],['3/28/2020', 3935, 21, 244],['3/29/2020', 4197, 17, 244],['3/30/2020', 4550, 18, 358],['3/31/2020', 4559, 18, 358],['4/1/2020', 4862, 20, 422],['4/2/2020', 5116, 24, 520],['4/3/2020', 5330, 28, 649],['4/4/2020', 5550, 30, 701],['4/5/2020', 5687, 35, 757],['4/6/2020', 5797, 40, 1080],['4/7/2020', 5895, 45, 1080],['4/8/2020', 6010, 50, 1080],['4/9/2020', 6108, 51, 1472],['4/10/2020', 6283, 56, 1793],['4/11/2020', 6303, 57, 1806],['4/12/2020', 6352, 61, 1806],['4/13/2020', 6397, 61, 2186],['4/14/2020', 6416, 62, 2186],['4/15/2020', 6441, 63, 2186],['4/16/2020', 6521, 66, 3786],['4/17/2020', 6539, 66, 3822],['4/18/2020', 6547, 67, 4124],['4/19/2020', 6547, 67, 4124],['4/20/2020', 6547, 67, 4124],['4/21/2020', 6547, 67, 4124],['4/22/2020', 6547, 67, 4124],['4/23/2020', 6662, 75, 4124],['4/24/2020', 6662, 75, 4124],['4/25/2020', 6694, 80, 5271],['4/26/2020', 6714, 83, 5541],['4/27/2020', 6721, 83, 5588],['4/28/2020', 6745, 91, 5670],['4/29/2020', 6753, 92, 5718],['4/30/2020', 6767, 93, 5748],['5/1/2020', 6773, 93, 5776],['5/2/2020', 6799, 95, 5818],['5/3/2020', 6825, 96, 5864],['5/4/2020', 6849, 96, 5891],['5/5/2020', 6875, 97, 5975],['5/6/2020', 6896, 97, 6034],['5/7/2020', 6913, 97, 6078],['5/8/2020', 6927, 97, 6134],['5/9/2020', 6939, 97, 6162],['5/10/2020', 6949, 97, 6181],['5/11/2020', 6971, 97, 6230],['5/12/2020', 6971, 97, 6231],
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
      ["Australia", 6971, 97]
    ]);
    var options = {
      backgroundColor: {fill:'transparent',stroke:'#FFF' ,strokeWidth:0 }, 
      region: 'AU',
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



<span style="font-size: 13px">All COVID-19 data displayed on the page is available through our FREE <a href="https://developer.smartable.ai">API program</a>. This Australia Coronavirus (COVID-19) Live Stats is refreshed every hour using credible data sources, including the country/state's official government website, <a href="https://en.wikipedia.org/wiki/2019%E2%80%9320_coronavirus_pandemic" target="_blank">data available on wikipedia pages</a>, latest news reports, <a href="https://systems.jhu.edu/research/public-health/ncov/" target="_blank">Johns Hopkins University CSSE 2019-nCoV Dashboard</a>, <a href="https://www.who.int/emergencies/diseases/novel-coronavirus-2019/situation-reports" target="_blank">WHO Situation Reports</a>, <a href="https://www.cdc.gov/coronavirus/2019-ncov/index.html" target="_blank">CDC Situation Updates</a>, and <a href="https://ncov.dxy.cn/ncovh5/view/pneumonia" target="_blank">DXY.cn</a>.</span>


<h2 id="news" class="center" style="margin-top: 60px; font-size: 25px;">Trending Coronavirus News in Australia</h2>
<div class="row">
<div class="col-md-6 col-sm-12">
  <div class="content-card">
	<a href="https://www.reuters.com/article/health-coronavirus-australia-idUSL4N2CR023"><div class="card-image" style="background-image: url(https://s4.reutersmedia.net/resources_v3/images/rcom-default.png)"></div></a>
	<div class="content">
		<div class="card-title"><a href="https://www.reuters.com/article/health-coronavirus-australia-idUSL4N2CR023">Australia's biggest states hold off relaxing COVID-19 lockdowns</a></div>
		<div class="card-excerpt">Australia's most populous states held back from easing COVID-19 restrictions on Saturday even as some states allowed small gatherings and got ready to open restaurants in line with the federal government's three-stage plan for reopening businesses.</div>
		<div class="card-meta">
			<span class="card-provider">Reuters</span> • <span class="card-date">5/9/2020</span>
		</div>
	</div>
  </div>
</div>
<div class="col-md-6 col-sm-12">
  <div class="content-card">
	<a href="https://www.reuters.com/video/watch/idOVCD2SSBV"><div class="card-image" style="background-image: url(https://static.reuters.com/resources/r/?d=20200508&i=OVCD2SSBV&r=OVCD2SSBV&t=2)"></div></a>
	<div class="content">
		<div class="card-title"><a href="https://www.reuters.com/video/watch/idOVCD2SSBV">Australia to end most COVID-19 restrictions by July</a></div>
		<div class="card-excerpt">World Australia to end most COVID-19 restrictions by July. Posted . Australia will ease social distancing restrictions implemented to slow the spread of the coronavirus in a three</div>
		<div class="card-meta">
			<span class="card-provider">Reuters</span> • <span class="card-date">5/8/2020</span>
		</div>
	</div>
  </div>
</div>
<div class="col-md-6 col-sm-12">
  <div class="content-card">
	<a href="https://www.cnbc.com/2020/05/08/coronavirus-live-updates-asia-europe.html"><div class="card-image" style="background-image: url(https://image.cnbcfm.com/api/v1/image/106524968-1588838965779gettyimages-1208218734.jpeg?v=1588924424)"></div></a>
	<div class="content">
		<div class="card-title"><a href="https://www.cnbc.com/2020/05/08/coronavirus-live-updates-asia-europe.html">Coronavirus live updates: Australia plans reopening in 3 stages; Germany reports over 1,200 cases</a></div>
		<div class="card-excerpt">Australia will ease nationwide restrictions in a process comprising three stages, its Prime Minister Scott Morrison said on Friday.</div>
		<div class="card-meta">
			<span class="card-provider">CNBC</span> • <span class="card-date">5/7/2020</span>
		</div>
	</div>
  </div>
</div>
<div class="col-md-6 col-sm-12">
  <div class="content-card">
	<a href="https://www.theguardian.com/australia-news/2020/may/07/covid-safe-app-downloads-ios-android-iphone-australian-government-covidsafe-tracking-how-to-download-install-works-working-problems-issues-battery-australia-coronavirus-contact-tracing"><div class="card-image" style="background-image: url(https://i.guim.co.uk/img/media/06456110e64b3cbbfcc1af6235942f45117c3e0e/439_307_3561_2138/master/3561.jpg?width=300&quality=45&auto=format&fit=max&dpr=2&s=0558f7ce36467a094a7739bc830adbaf)"></div></a>
	<div class="content">
		<div class="card-title"><a href="https://www.theguardian.com/australia-news/2020/may/07/covid-safe-app-downloads-ios-android-iphone-australian-government-covidsafe-tracking-how-to-download-install-works-working-problems-issues-battery-australia-coronavirus-contact-tracing">Covidsafe app: how Australia’s coronavirus contact tracing app works, what it does, downloads and problems</a></div>
		<div class="card-excerpt">The app will ask for your name (or pseudonym), age range, postcode and phone number. Scott Morrison says the Australian government’s covid safe tracking app won’t be mandatory to download and install,</div>
		<div class="card-meta">
			<span class="card-provider">The Guardian</span> • <span class="card-date">5/6/2020</span>
		</div>
	</div>
  </div>
</div>

</div>

