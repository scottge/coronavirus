---
category: stats
title: "Iran Coronavirus (COVID-19) Live Stats"
excerpt: "Live stats of COVID-19 in Iran. Total Cases: 106220 (+1529), Deaths: 6589 (+48), Recoveries: 85064(+1227)."
publishedDateTime: 2020-05-10T05:45:41Z
updatedDateTime: 2020-05-10T05:45:41Z
webUrl: "https://smartable.ai/apps/coronavirus/stats/iran/"
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
  - Coronavirus in Asia

images:
  - url: "https://smartable.azureedge.net/coronavirus/sites/2/2020/iran.jpg"
    width: 900
    height: 564
    title: "Iran Coronavirus (COVID-19) Live Stats"

---
<div class="total-stats" style="text-align: center;">
    <h3>
	    <div style="font-size: 18px; font-weight: 400;">Total Confirmed Cases:</div>
	    106220 (<span class='red'>+1529</span>)
    </h3>
    <h3>
	    <div style="font-size: 18px; font-weight: 400;">Total Deaths:</div>
	    6589 (<span class='red'>+48</span>)
    </h3>
    <h3>
	    <div style="font-size: 18px; font-weight: 400;">Total Recovered:</div>
	    85064 (<span class='green'>+1227</span>)
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
      ['1/22/2020', 0, 0, 0],['1/23/2020', 0, 0, 0],['1/24/2020', 0, 0, 0],['1/25/2020', 0, 0, 0],['1/26/2020', 0, 0, 0],['1/27/2020', 0, 0, 0],['1/28/2020', 0, 0, 0],['1/29/2020', 0, 0, 0],['1/30/2020', 0, 0, 0],['1/31/2020', 0, 0, 0],['2/1/2020', 0, 0, 0],['2/2/2020', 0, 0, 0],['2/3/2020', 0, 0, 0],['2/4/2020', 0, 0, 0],['2/5/2020', 0, 0, 0],['2/6/2020', 0, 0, 0],['2/7/2020', 0, 0, 0],['2/8/2020', 0, 0, 0],['2/9/2020', 0, 0, 0],['2/10/2020', 0, 0, 0],['2/11/2020', 0, 0, 0],['2/12/2020', 0, 0, 0],['2/13/2020', 0, 0, 0],['2/14/2020', 0, 0, 0],['2/15/2020', 0, 0, 0],['2/16/2020', 0, 0, 0],['2/17/2020', 0, 0, 0],['2/18/2020', 0, 0, 0],['2/19/2020', 2, 2, 0],['2/20/2020', 5, 2, 0],['2/21/2020', 18, 4, 0],['2/22/2020', 28, 5, 0],['2/23/2020', 43, 8, 0],['2/24/2020', 61, 12, 0],['2/25/2020', 95, 16, 0],['2/26/2020', 139, 19, 49],['2/27/2020', 245, 26, 49],['2/28/2020', 388, 34, 73],['2/29/2020', 593, 43, 123],['3/1/2020', 978, 54, 175],['3/2/2020', 1501, 66, 291],['3/3/2020', 2336, 77, 291],['3/4/2020', 2922, 92, 552],['3/5/2020', 3513, 107, 739],['3/6/2020', 4747, 124, 913],['3/7/2020', 5823, 145, 1669],['3/8/2020', 6566, 194, 2134],['3/9/2020', 7161, 237, 2394],['3/10/2020', 8042, 291, 2731],['3/11/2020', 9000, 354, 2959],['3/12/2020', 10075, 429, 3276],['3/13/2020', 11364, 514, 3529],['3/14/2020', 12729, 611, 4339],['3/15/2020', 13938, 724, 4590],['3/16/2020', 14991, 853, 4996],['3/17/2020', 16169, 988, 5389],['3/18/2020', 17361, 1135, 5710],['3/19/2020', 18407, 1284, 5979],['3/20/2020', 19644, 1433, 6745],['3/21/2020', 20610, 1556, 7635],['3/22/2020', 21638, 1685, 7931],['3/23/2020', 23049, 1812, 8376],['3/24/2020', 24811, 1934, 8913],['3/25/2020', 27017, 2077, 9625],['3/26/2020', 29406, 2234, 10457],['3/27/2020', 32332, 2378, 11133],['3/28/2020', 35408, 2517, 11679],['3/29/2020', 38309, 2640, 12391],['3/30/2020', 41495, 2757, 13911],['3/31/2020', 44605, 2898, 14656],['4/1/2020', 47593, 3036, 15473],['4/2/2020', 50468, 3160, 16711],['4/3/2020', 53183, 3294, 17935],['4/4/2020', 55743, 3452, 19736],['4/5/2020', 58226, 3603, 22011],['4/6/2020', 60500, 3739, 24236],['4/7/2020', 62589, 3872, 27039],['4/8/2020', 66220, 4003, 29812],['4/9/2020', 66220, 4110, 32309],['4/10/2020', 68192, 4232, 35465],['4/11/2020', 70029, 4357, 41947],['4/12/2020', 71686, 4474, 43894],['4/13/2020', 73303, 4585, 45983],['4/14/2020', 74877, 4683, 48129],['4/15/2020', 76389, 4777, 49933],['4/16/2020', 77995, 4869, 52229],['4/17/2020', 79494, 4958, 54064],['4/18/2020', 80868, 5031, 55987],['4/19/2020', 82211, 5118, 57023],['4/20/2020', 83505, 5209, 59273],['4/21/2020', 84802, 5297, 60965],['4/22/2020', 85996, 5391, 63113],['4/23/2020', 87026, 5481, 64843],['4/24/2020', 88194, 5574, 66599],['4/25/2020', 89328, 5650, 68193],['4/26/2020', 90481, 5710, 69657],['4/27/2020', 91472, 5806, 70933],['4/28/2020', 92584, 5877, 72439],['4/29/2020', 93657, 5957, 73791],['4/30/2020', 94640, 6028, 75103],['5/1/2020', 95544, 6092, 76226],['5/2/2020', 96448, 6156, 77350],['5/3/2020', 97424, 6203, 78422],['5/4/2020', 98647, 6277, 79379],['5/5/2020', 99970, 6340, 80475],['5/6/2020', 101650, 6418, 81587],['5/7/2020', 103135, 6486, 82744],['5/8/2020', 104691, 6541, 83837],['5/9/2020', 106220, 6589, 85064],
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
      ["Iran", 106220, 6589]
    ]);
    var options = {
      backgroundColor: {fill:'transparent',stroke:'#FFF' ,strokeWidth:0 }, 
      region: 'IR',
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



<span style="font-size: 13px">All COVID-19 data displayed on the page is available through our FREE <a href="https://developer.smartable.ai">API program</a>. This Iran Coronavirus (COVID-19) Live Stats is refreshed every hour using credible data sources, including the country/state's official government website, <a href="https://en.wikipedia.org/wiki/2019%E2%80%9320_coronavirus_pandemic" target="_blank">data available on wikipedia pages</a>, latest news reports, <a href="https://systems.jhu.edu/research/public-health/ncov/" target="_blank">Johns Hopkins University CSSE 2019-nCoV Dashboard</a>, <a href="https://www.who.int/emergencies/diseases/novel-coronavirus-2019/situation-reports" target="_blank">WHO Situation Reports</a>, <a href="https://www.cdc.gov/coronavirus/2019-ncov/index.html" target="_blank">CDC Situation Updates</a>, and <a href="https://ncov.dxy.cn/ncovh5/view/pneumonia" target="_blank">DXY.cn</a>.</span>


<h2 id="news" class="center" style="margin-top: 60px; font-size: 25px;">Trending Coronavirus News in Iran</h2>
<div class="row">
<div class="col-md-6 col-sm-12">
  <div class="content-card">
	<a href="https://www.newsweek.com/report-accuses-iran-attack-drug-company-coronavirus-1502838"><div class="card-image" style="background-image: url(https://d.newsweek.com/en/full/1588511/gilead-cyber-attack-iran-remdesivir.jpg)"></div></a>
	<div class="content">
		<div class="card-title"><a href="https://www.newsweek.com/report-accuses-iran-attack-drug-company-coronavirus-1502838">Report Accuses Iran of Cyberattack on U.S. Company Trying to Find Treatment for Coronavirus</a></div>
		<div class="card-excerpt">"The Iranian government does not engage in cyber warfare," Iranian mission to the U.N. spokesperson Alireza Miryousefi told Newsweek following a Reuters report tying Tehran to an attack on Gilead.</div>
		<div class="card-meta">
			<span class="card-provider">Newsweek</span> • <span class="card-date">5/8/2020</span>
		</div>
	</div>
  </div>
</div>
<div class="col-md-6 col-sm-12">
  <div class="content-card">
	<a href="https://www.reuters.com/article/us-healthcare-coronavirus-gilead-iran-ex-idUSKBN22K2EV"><div class="card-image" style="background-image: url(https://s4.reutersmedia.net/resources/r/?m=02&d=20200508&t=2&i=1517969081&w=&fh=545px&fw=&ll=&pl=&sq=&r=LYNXMPEG471IY)"></div></a>
	<div class="content">
		<div class="card-title"><a href="https://www.reuters.com/article/us-healthcare-coronavirus-gilead-iran-ex-idUSKBN22K2EV">Exclusive: Iran-linked hackers recently targeted coronavirus drugmaker Gilead - sources</a></div>
		<div class="card-excerpt">Hackers linked to Iran have targeted staff at U.S. drugmaker Gilead Sciences Inc in recent weeks, according to publicly-available web archives reviewed by Reuters and three cybersecurity researchers,</div>
		<div class="card-meta">
			<span class="card-provider">Reuters</span> • <span class="card-date">5/8/2020</span>
		</div>
	</div>
  </div>
</div>
<div class="col-md-6 col-sm-12">
  <div class="content-card">
	<a href="https://www.wsj.com/articles/irans-coronavirus-cases-rise-anew-as-friday-prayers-are-set-to-resume-11588870093"><div class="card-image" style="background-image: url(https://images.wsj.net/im-184319/social)"></div></a>
	<div class="content">
		<div class="card-title"><a href="https://www.wsj.com/articles/irans-coronavirus-cases-rise-anew-as-friday-prayers-are-set-to-resume-11588870093">Iran’s Coronavirus Cases Rise Anew as Friday Prayers Are Set to Resume</a></div>
		<div class="card-excerpt">Two weeks after the country began lifting restrictions and a day before some mosques are set to reopen, cases of Covid-19 have surged afresh in Iran, where nearly 6,500 people have died from the disease.</div>
		<div class="card-meta">
			<span class="card-provider">Wall Street Journal</span> • <span class="card-date">5/7/2020</span>
		</div>
	</div>
  </div>
</div>
<div class="col-md-6 col-sm-12">
  <div class="content-card">
	<a href="https://www.reuters.com/article/us-health-coronavirus-iran-grains-exclus-idUSKBN22J233"><div class="card-image" style="background-image: url(https://s2.reutersmedia.net/resources/r/?m=02&d=20200507&t=2&i=1517812534&w=&fh=545px&fw=&ll=&pl=&sq=&r=LYNXMPEG4616D)"></div></a>
	<div class="content">
		<div class="card-title"><a href="https://www.reuters.com/article/us-health-coronavirus-iran-grains-exclus-idUSKBN22J233">Exclusive: Iran hunts for grains as coronavirus compounds economic woes</a></div>
		<div class="card-excerpt">Iran is scrambling to buy millions of tonnes of wheat, corn and soybeans to shore up its reserves, Iranian officials and traders said, despite President Hassan Rouhani's assertions that the coronavirus would not endanger food supplies to the Middle Eastern country worst hit by the pandemic.</div>
		<div class="card-meta">
			<span class="card-provider">Reuters</span> • <span class="card-date">5/7/2020</span>
		</div>
	</div>
  </div>
</div>
<div class="col-md-6 col-sm-12">
  <div class="content-card">
	<a href="https://www.reuters.com/article/us-health-coronavirus-iran-idUSKBN22I1CH"><div class="card-image" style="background-image: url(https://s1.reutersmedia.net/resources/r/?m=02&d=20200506&t=2&i=1517636961&w=&fh=545px&fw=&ll=&pl=&sq=&r=LYNXMPEG450S1)"></div></a>
	<div class="content">
		<div class="card-title"><a href="https://www.reuters.com/article/us-health-coronavirus-iran-idUSKBN22I1CH">Iran's coronavirus death toll rises by 78 to 6,418</a></div>
		<div class="card-excerpt">The death toll from the new coronavirus outbreak in Iran rose by 78 in the past 24 hours to 6,418 and the total number of infections to 101,650, the Health Ministry said in a tweet on Wednesday.</div>
		<div class="card-meta">
			<span class="card-provider">Reuters</span> • <span class="card-date">5/6/2020</span>
		</div>
	</div>
  </div>
</div>
<div class="col-md-6 col-sm-12">
  <div class="content-card">
	<a href="https://www.reuters.com/article/us-health-coronavirus-iran-idUSKBN22H13H"><div class="card-image" style="background-image: url(https://s4.reutersmedia.net/resources/r/?m=02&d=20200505&t=2&i=1517503627&w=&fh=545px&fw=&ll=&pl=&sq=&r=LYNXMPEG440LU)"></div></a>
	<div class="content">
		<div class="card-title"><a href="https://www.reuters.com/article/us-health-coronavirus-iran-idUSKBN22H13H">Iran death toll from new coronavirus outbreak rises by 63 to 6,340: health ministry official</a></div>
		<div class="card-excerpt">The death toll from the outbreak of new coronavirus in Iran rose by 63 in the past 24 hours to 6,340, Health Ministry spokesman Kianush Jahanpur said in a statement on state TV on Tuesday.</div>
		<div class="card-meta">
			<span class="card-provider">Reuters</span> • <span class="card-date">5/5/2020</span>
		</div>
	</div>
  </div>
</div>
<div class="col-md-6 col-sm-12">
  <div class="content-card">
	<a href="https://www.reuters.com/article/us-health-coronavirus-iran-idUSKBN22F090"><div class="card-image" style="background-image: url(https://s1.reutersmedia.net/resources/r/?m=02&d=20200503&t=2&i=1517295700&w=&fh=545px&fw=&ll=&pl=&sq=&r=LYNXMPEG42070)"></div></a>
	<div class="content">
		<div class="card-title"><a href="https://www.reuters.com/article/us-health-coronavirus-iran-idUSKBN22F090">Mosques and schools to reopen in Iran's low-risk areas</a></div>
		<div class="card-excerpt">Iran plans to reopen mosques and schools in areas that have been consistently free of the coronavirus as President Hassan Rouhani's government starts to ease restrictions that were aimed at containing the outbreak.</div>
		<div class="card-meta">
			<span class="card-provider">Reuters</span> • <span class="card-date">5/3/2020</span>
		</div>
	</div>
  </div>
</div>
<div class="col-md-6 col-sm-12">
  <div class="content-card">
	<a href="https://www.foxnews.com/politics/pompeo-warren-iran-deal-china-sending-tanks"><div class="card-image" style="background-image: url(https://cf-images.us-east-1.prod.boltdns.net/v1/static/694940094001/d86f2324-b516-4d77-bf02-ff7f493dd247/d56bddf3-f115-4cab-a01a-f8d042b06a3f/1280x720/match/image.jpg)"></div></a>
	<div class="content">
		<div class="card-title"><a href="https://www.foxnews.com/politics/pompeo-warren-iran-deal-china-sending-tanks">Pompeo clashes with Warren on Iran deal, asks if she's 'good' with China sending tanks to Tehran</a></div>
		<div class="card-excerpt">Secretary of State Mike Pompeo on Thursday clashed with Sen. Elizabeth Warren, D-Mass., over a Trump administration plan to block weapon sales to Iran by arguing that the U.S. is still part of the Iran nuclear deal because it remains part of a U.</div>
		<div class="card-meta">
			<span class="card-provider">Fox News</span> • <span class="card-date">4/30/2020</span>
		</div>
	</div>
  </div>
</div>
<div class="col-md-6 col-sm-12">
  <div class="content-card">
	<a href="https://www.reuters.com/article/us-health-coronavirus-iran-idUSKCN22A1CL"><div class="card-image" style="background-image: url(https://s4.reutersmedia.net/resources_v3/images/rcom-default.png)"></div></a>
	<div class="content">
		<div class="card-title"><a href="https://www.reuters.com/article/us-health-coronavirus-iran-idUSKCN22A1CL">Iran's coronavirus death toll rises by 71 to 5,877 -health ministry official</a></div>
		<div class="card-excerpt">The death toll in Iran from the coronavirus pandemic rose by 71 in the past 24 hours to 5,877, health ministry spokesman Kianush Jahanpur said on state TV on Tuesday.</div>
		<div class="card-meta">
			<span class="card-provider">Reuters</span> • <span class="card-date">4/28/2020</span>
		</div>
	</div>
  </div>
</div>

</div>

