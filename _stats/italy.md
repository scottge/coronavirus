---
category: stats
title: "Italy Coronavirus (COVID-19) Live Stats"
excerpt: "Live stats of COVID-19 in Italy. Total Cases: 219814 (+744), Deaths: 30739 (+179), Recoveries: 106587(+1401)."
publishedDateTime: 2020-05-12T00:45:10Z
updatedDateTime: 2020-05-12T00:45:10Z
webUrl: "https://smartable.ai/apps/coronavirus/stats/italy/"
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
  - url: "https://smartable.azureedge.net/coronavirus/sites/2/2020/italy.jpg"
    width: 900
    height: 564
    title: "Italy Coronavirus (COVID-19) Live Stats"

---
<div class="total-stats" style="text-align: center;">
    <h3>
	    <div style="font-size: 18px; font-weight: 400;">Total Confirmed Cases:</div>
	    219814 (<span class='red'>+744</span>)
    </h3>
    <h3>
	    <div style="font-size: 18px; font-weight: 400;">Total Deaths:</div>
	    30739 (<span class='red'>+179</span>)
    </h3>
    <h3>
	    <div style="font-size: 18px; font-weight: 400;">Total Recovered:</div>
	    106587 (<span class='green'>+1401</span>)
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
      ['1/22/2020', 0, 0, 0],['1/23/2020', 0, 0, 0],['1/24/2020', 0, 0, 0],['1/25/2020', 0, 0, 0],['1/26/2020', 0, 0, 0],['1/27/2020', 0, 0, 0],['1/28/2020', 0, 0, 0],['1/29/2020', 0, 0, 0],['1/30/2020', 0, 0, 0],['1/31/2020', 2, 0, 0],['2/1/2020', 2, 0, 0],['2/2/2020', 2, 0, 0],['2/3/2020', 2, 0, 0],['2/4/2020', 2, 0, 0],['2/5/2020', 2, 0, 0],['2/6/2020', 2, 0, 0],['2/7/2020', 3, 0, 0],['2/8/2020', 3, 0, 0],['2/9/2020', 3, 0, 0],['2/10/2020', 3, 0, 0],['2/11/2020', 3, 0, 0],['2/12/2020', 3, 0, 0],['2/13/2020', 3, 0, 0],['2/14/2020', 3, 0, 0],['2/15/2020', 3, 0, 0],['2/16/2020', 3, 0, 0],['2/17/2020', 3, 0, 0],['2/18/2020', 3, 0, 0],['2/19/2020', 3, 0, 0],['2/20/2020', 3, 0, 0],['2/21/2020', 20, 1, 0],['2/22/2020', 62, 2, 1],['2/23/2020', 155, 3, 1],['2/24/2020', 229, 7, 1],['2/25/2020', 322, 10, 1],['2/26/2020', 453, 12, 3],['2/27/2020', 655, 17, 45],['2/28/2020', 888, 21, 46],['2/29/2020', 1128, 29, 46],['3/1/2020', 1694, 34, 83],['3/2/2020', 2036, 52, 149],['3/3/2020', 2502, 79, 160],['3/4/2020', 3089, 107, 276],['3/5/2020', 3858, 148, 414],['3/6/2020', 4636, 197, 523],['3/7/2020', 5883, 233, 589],['3/8/2020', 7375, 366, 622],['3/9/2020', 9172, 463, 724],['3/10/2020', 10149, 631, 724],['3/11/2020', 12462, 827, 1045],['3/12/2020', 15113, 1016, 1258],['3/13/2020', 17660, 1266, 1439],['3/14/2020', 21157, 1441, 1966],['3/15/2020', 24747, 1809, 2335],['3/16/2020', 27980, 2158, 2749],['3/17/2020', 31506, 2503, 2941],['3/18/2020', 35713, 2978, 4025],['3/19/2020', 41035, 3405, 4440],['3/20/2020', 47021, 4032, 5129],['3/21/2020', 53578, 4825, 6072],['3/22/2020', 59138, 5476, 7024],['3/23/2020', 63927, 6077, 7432],['3/24/2020', 69176, 6820, 8326],['3/25/2020', 74386, 7503, 9362],['3/26/2020', 80589, 8215, 10361],['3/27/2020', 86498, 9134, 10950],['3/28/2020', 92472, 10023, 12384],['3/29/2020', 97689, 10779, 13030],['3/30/2020', 101739, 11591, 14620],['3/31/2020', 105792, 12428, 15729],['4/1/2020', 110574, 13155, 16847],['4/2/2020', 115242, 13915, 18278],['4/3/2020', 119827, 14681, 19758],['4/4/2020', 124632, 15362, 20996],['4/5/2020', 128948, 15887, 21815],['4/6/2020', 132547, 16523, 22837],['4/7/2020', 135586, 17127, 24392],['4/8/2020', 139422, 17669, 26491],['4/9/2020', 143626, 18279, 28470],['4/10/2020', 147577, 18849, 30455],['4/11/2020', 152271, 19468, 32534],['4/12/2020', 156363, 19899, 34211],['4/13/2020', 159516, 20465, 35435],['4/14/2020', 162488, 21067, 37130],['4/15/2020', 165155, 21645, 38092],['4/16/2020', 168941, 22170, 40164],['4/17/2020', 172434, 22745, 42727],['4/18/2020', 175925, 23227, 44927],['4/19/2020', 178972, 23660, 47055],['4/20/2020', 181228, 24114, 48877],['4/21/2020', 183957, 24648, 51600],['4/22/2020', 187327, 25085, 54543],['4/23/2020', 189973, 25549, 57576],['4/24/2020', 192994, 25969, 60498],['4/25/2020', 195351, 26384, 63120],['4/26/2020', 197675, 26644, 64928],['4/27/2020', 199414, 26977, 66624],['4/28/2020', 201505, 27359, 68941],['4/29/2020', 203591, 27682, 71252],['4/30/2020', 205463, 27967, 75945],['5/1/2020', 207395, 28338, 77929],['5/2/2020', 209328, 28710, 79914],['5/3/2020', 210717, 28884, 81654],['5/4/2020', 211938, 29079, 82879],['5/5/2020', 213013, 29315, 85231],['5/6/2020', 214457, 29684, 93245],['5/7/2020', 215858, 29958, 96276],['5/8/2020', 217185, 30201, 99023],['5/9/2020', 218268, 30395, 103031],['5/10/2020', 219070, 30560, 105186],['5/11/2020', 219814, 30739, 106587],
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
      ["Italy", 219814, 30739]
    ]);
    var options = {
      backgroundColor: {fill:'transparent',stroke:'#FFF' ,strokeWidth:0 }, 
      region: 'IT',
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



<span style="font-size: 13px">All COVID-19 data displayed on the page is available through our FREE <a href="https://developer.smartable.ai">API program</a>. This Italy Coronavirus (COVID-19) Live Stats is refreshed every hour using credible data sources, including the country/state's official government website, <a href="https://en.wikipedia.org/wiki/2019%E2%80%9320_coronavirus_pandemic" target="_blank">data available on wikipedia pages</a>, latest news reports, <a href="https://systems.jhu.edu/research/public-health/ncov/" target="_blank">Johns Hopkins University CSSE 2019-nCoV Dashboard</a>, <a href="https://www.who.int/emergencies/diseases/novel-coronavirus-2019/situation-reports" target="_blank">WHO Situation Reports</a>, <a href="https://www.cdc.gov/coronavirus/2019-ncov/index.html" target="_blank">CDC Situation Updates</a>, and <a href="https://ncov.dxy.cn/ncovh5/view/pneumonia" target="_blank">DXY.cn</a>.</span>


<h2 id="news" class="center" style="margin-top: 60px; font-size: 25px;">Trending Coronavirus News in Italy</h2>
<div class="row">
<div class="col-md-6 col-sm-12">
  <div class="content-card">
	<a href="https://www.ft.com/content/6c2ad256-9452-4480-9d98-2444b07675d4"><div class="card-image" style="background-image: url(https://www.ft.com/__origami/service/image/v2/images/raw/https%3A%2F%2Fd1e00ek4ebabms.cloudfront.net%2Fproduction%2F8e4ceb41-68fe-4f0b-b74b-87500afd027b.jpg?source=google-amp&fit=scale-down&width=500)"></div></a>
	<div class="content">
		<div class="card-title"><a href="https://www.ft.com/content/6c2ad256-9452-4480-9d98-2444b07675d4">Coronavirus deepens north-south divide in Italy and Spain</a></div>
		<div class="card-excerpt">While the rest of Italy started returning to work this week as restrictions aimed at stopping the spread of coronavirus were lifted, employees at the Rummo pasta plant could be forgiven for wanting a holiday.</div>
		<div class="card-meta">
			<span class="card-provider">The Financial Times</span> • <span class="card-date">5/9/2020</span>
		</div>
	</div>
  </div>
</div>
<div class="col-md-6 col-sm-12">
  <div class="content-card">
	<a href="https://www.foxnews.com/world/italy-to-resume-church-services-earlier-than-expected-after-bishops-sitdown-with-government"><div class="card-image" style="background-image: url(https://cf-images.us-east-1.prod.boltdns.net/v1/static/694940094001/596938e4-c35c-4df2-bf37-f143c7f1b7b8/dd68ea5d-8089-4c94-8ee9-8559b9d96f09/1280x720/match/image.jpg)"></div></a>
	<div class="content">
		<div class="card-title"><a href="https://www.foxnews.com/world/italy-to-resume-church-services-earlier-than-expected-after-bishops-sitdown-with-government">Italy gives go-ahead for Roman Catholic Masses to resume May 18</a></div>
		<div class="card-excerpt">Italy is set to lift its ban on religious services due to COVID-19, weeks earlier than expected, following a Thursday meeting between the nation's bishops and Prime Minister Giuseppe Conte.</div>
		<div class="card-meta">
			<span class="card-provider">Fox News</span> • <span class="card-date">5/9/2020</span>
		</div>
	</div>
  </div>
</div>
<div class="col-md-6 col-sm-12">
  <div class="content-card">
	<a href="https://apnews.com/fce9ea63c7c4199e4ff39ddd54d3944e"><div class="card-image" style="background-image: url(https://storage.googleapis.com/afs-prod/media/8544eabdc5b0428da95282955d2c6aae/3000.jpeg)"></div></a>
	<div class="content">
		<div class="card-title"><a href="https://apnews.com/fce9ea63c7c4199e4ff39ddd54d3944e">Reopenings bring new cases in S. Korea, virus fears in Italy</a></div>
		<div class="card-excerpt">South Korea's capital closed down more than 2,100 bars and other nightspots Saturday because of a new cluster of coronavirus infections, Germany scrambled to contain fresh outbreaks</div>
		<div class="card-meta">
			<span class="card-provider">Associated Press</span> • <span class="card-date">5/9/2020</span>
		</div>
	</div>
  </div>
</div>
<div class="col-md-6 col-sm-12">
  <div class="content-card">
	<a href="https://www.usatoday.com/story/travel/news/2020/05/09/coronavirus-italys-la-scala-opera-house-unveils-virtual-tours/3103172001/"><div class="card-image" style="background-image: url(https://www.gannett-cdn.com/presto/2020/05/09/USAT/96c4c7c8-26cd-47a6-846d-8961d6df9507-AP_Virus_Outbreak_Italy_La_Scala.JPG?auto=webp&crop=4791,2695,x0,y332&format=pjpg&width=1200)"></div></a>
	<div class="content">
		<div class="card-title"><a href="https://www.usatoday.com/story/travel/news/2020/05/09/coronavirus-italys-la-scala-opera-house-unveils-virtual-tours/3103172001/">Italy's La Scala opera house unveils virtual tours amid coronavirus pandemic</a></div>
		<div class="card-excerpt">La Scala has been closed since Feb. 23, within days of the first positive case of domestically transmitted coronavirus in Italy.</div>
		<div class="card-meta">
			<span class="card-provider">USA Today</span> • <span class="card-date">5/9/2020</span>
		</div>
	</div>
  </div>
</div>
<div class="col-md-6 col-sm-12">
  <div class="content-card">
	<a href="https://www.reuters.com/article/us-health-coronavirus-italy-tally-idUSKBN22L0Q4"><div class="card-image" style="background-image: url(https://s3.reutersmedia.net/resources/r/?m=02&d=20200509&t=2&i=1518047864&w=&fh=545px&fw=&ll=&pl=&sq=&r=LYNXMPEG480LN)"></div></a>
	<div class="content">
		<div class="card-title"><a href="https://www.reuters.com/article/us-health-coronavirus-italy-tally-idUSKBN22L0Q4">Italy's daily coronavirus death toll and new cases fall</a></div>
		<div class="card-excerpt">Deaths from the COVID-19 epidemic in Italy climbed by 194 on Saturday, against 243 the day before, the Civil Protection Agency said, while the daily tally of new cases fell to 1,083 from 1,327 on Friday.</div>
		<div class="card-meta">
			<span class="card-provider">Reuters</span> • <span class="card-date">5/9/2020</span>
		</div>
	</div>
  </div>
</div>
<div class="col-md-6 col-sm-12">
  <div class="content-card">
	<a href="https://www.washingtonpost.com/world/europe/coronavirus-italy-deaths-recession-euroskepticism/2020/05/08/c28c496e-8a5a-11ea-80df-d24b35a568ae_story.html"><div class="card-image" style="background-image: url(https://www.washingtonpost.com/resizer/9HcJLrARuLBeNKta7hkdfXMyHpk=/1440x0/smart/arc-anglerfish-washpost-prod-washpost.s3.amazonaws.com/public/BJCEPXUQVII6VKOAOO4TIIWWSE.jpg)"></div></a>
	<div class="content">
		<div class="card-title"><a href="https://www.washingtonpost.com/world/europe/coronavirus-italy-deaths-recession-euroskepticism/2020/05/08/c28c496e-8a5a-11ea-80df-d24b35a568ae_story.html">Italy has long been Europe’s wild card. The coronavirus has upped the risk.</a></div>
		<div class="card-excerpt">The novel coronavirus death toll has surpassed 30,000. The country is hurtling into its steepest recession in modern times. Tourism has gone bust. Many restaurants and shops lack the cash to ever reopen.</div>
		<div class="card-meta">
			<span class="card-provider">Washington Post</span> • <span class="card-date">5/9/2020</span>
		</div>
	</div>
  </div>
</div>
<div class="col-md-6 col-sm-12">
  <div class="content-card">
	<a href="https://www.bbc.co.uk/news/world-europe-52594570"><div class="card-image" style="background-image: url(https://ichef.bbci.co.uk/news/1024/cpsprodpb/F92E/production/_112209736_061392753.jpg)"></div></a>
	<div class="content">
		<div class="card-title"><a href="https://www.bbc.co.uk/news/world-europe-52594570">Coronavirus: Italy death toll tops 30,000, highest in EU</a></div>
		<div class="card-excerpt">Italy has the third highest number of officially recorded coronavirus deaths in the world, after the United States and the UK - which is no longer a member of the EU. Britain passed the 30,000 mark on Wednesday.</div>
		<div class="card-meta">
			<span class="card-provider">BBC</span> • <span class="card-date">5/8/2020</span>
		</div>
	</div>
  </div>
</div>
<div class="col-md-6 col-sm-12">
  <div class="content-card">
	<a href="https://www.theguardian.com/world/2020/may/08/global-report-spain-and-italy-grapple-with-how-to-end-covid-19-lockdown"><div class="card-image" style="background-image: url(https://i.guim.co.uk/img/media/bbfcace64208b917f64ba608224aa88dd03bd0eb/0_0_3500_2101/master/3500.jpg?width=300&quality=45&auto=format&fit=max&dpr=2&s=ec92ffada431751f8593ad2eda732d57)"></div></a>
	<div class="content">
		<div class="card-title"><a href="https://www.theguardian.com/world/2020/may/08/global-report-spain-and-italy-grapple-with-how-to-end-covid-19-lockdown">Global report: Spain and Italy grapple with how to end Covid-19 lockdown</a></div>
		<div class="card-excerpt">Spanish government refuses permission for Madrid region to loosen physical distancing rules</div>
		<div class="card-meta">
			<span class="card-provider">The Guardian</span> • <span class="card-date">5/8/2020</span>
		</div>
	</div>
  </div>
</div>
<div class="col-md-6 col-sm-12">
  <div class="content-card">
	<a href="https://www.cnbc.com/2020/05/08/coronavirus-latest-updates.html"><div class="card-image" style="background-image: url(https://image.cnbcfm.com/api/v1/image/106490962-1587013284970gettyimages-1210084517.jpeg?v=1587886531)"></div></a>
	<div class="content">
		<div class="card-title"><a href="https://www.cnbc.com/2020/05/08/coronavirus-latest-updates.html">Coronavirus live updates: WHO calls for research into Wuhan market, Indonesia eases travel restrictions</a></div>
		<div class="card-excerpt">Covid-19 has infected more than 3,862,174 people around the world as of Friday, killing at least 269,881 people.</div>
		<div class="card-meta">
			<span class="card-provider">CNBC</span> • <span class="card-date">5/8/2020</span>
		</div>
	</div>
  </div>
</div>
<div class="col-md-6 col-sm-12">
  <div class="content-card">
	<a href="https://www.nbcnews.com/health/health-news/live-blog/2020-05-07-coronavirus-news-n1201801/ncrd1202511"><div class="card-image" style="background-image: url(https://nodeassets.nbcnews.com/cdnassets/projects/socialshareimages-bento/og-nbcnews1200x630.png)"></div></a>
	<div class="content">
		<div class="card-title"><a href="https://www.nbcnews.com/health/health-news/live-blog/2020-05-07-coronavirus-news-n1201801/ncrd1202511">House probe finds U.S. efforts to screen travelers from Italy and South Korea were lax</a></div>
		<div class="card-excerpt">As of Thursday evening, the death toll in the U.S. is over 76,000 and there are more than 1.2 million confirmed cases, according to NBC News' count. Here's what to know about the coronavirus, plus a timeline of the most critical moments: Reopening America: See what states across the U.</div>
		<div class="card-meta">
			<span class="card-provider">NBC News</span> • <span class="card-date">5/7/2020</span>
		</div>
	</div>
  </div>
</div>

</div>

