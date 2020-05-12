---
category: stats
title: "UK Coronavirus (COVID-19) Live Stats"
excerpt: "Live stats of COVID-19 in UK. Total Cases: 226463 (+3403), Deaths: 32692 (+627), Recoveries: 344(-)."
publishedDateTime: 2020-05-12T18:45:13Z
updatedDateTime: 2020-05-12T18:45:13Z
webUrl: "https://smartable.ai/apps/coronavirus/stats/uk/"
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
  - url: "https://smartable.azureedge.net/coronavirus/sites/2/2020/uk.jpg"
    width: 900
    height: 564
    title: "UK Coronavirus (COVID-19) Live Stats"

---
<div class="total-stats" style="text-align: center;">
    <h3>
	    <div style="font-size: 18px; font-weight: 400;">Total Confirmed Cases:</div>
	    226463 (<span class='red'>+3403</span>)
    </h3>
    <h3>
	    <div style="font-size: 18px; font-weight: 400;">Total Deaths:</div>
	    32692 (<span class='red'>+627</span>)
    </h3>
    <h3>
	    <div style="font-size: 18px; font-weight: 400;">Total Recovered:</div>
	    344 (-)
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
      ['1/22/2020', 0, 0, 0],['1/23/2020', 0, 0, 0],['1/24/2020', 0, 0, 0],['1/25/2020', 0, 0, 0],['1/26/2020', 0, 0, 0],['1/27/2020', 0, 0, 0],['1/28/2020', 0, 0, 0],['1/29/2020', 0, 0, 0],['1/30/2020', 0, 0, 0],['1/31/2020', 2, 0, 0],['2/1/2020', 2, 0, 0],['2/2/2020', 2, 0, 0],['2/3/2020', 2, 0, 0],['2/4/2020', 2, 0, 0],['2/5/2020', 2, 0, 0],['2/6/2020', 2, 0, 0],['2/7/2020', 3, 0, 0],['2/8/2020', 3, 0, 0],['2/9/2020', 3, 0, 0],['2/10/2020', 8, 0, 0],['2/11/2020', 8, 0, 0],['2/12/2020', 9, 0, 1],['2/13/2020', 9, 0, 1],['2/14/2020', 9, 0, 1],['2/15/2020', 9, 0, 1],['2/16/2020', 9, 0, 8],['2/17/2020', 9, 0, 8],['2/18/2020', 9, 0, 8],['2/19/2020', 9, 0, 8],['2/20/2020', 9, 0, 8],['2/21/2020', 9, 0, 8],['2/22/2020', 9, 0, 8],['2/23/2020', 9, 0, 8],['2/24/2020', 13, 0, 8],['2/25/2020', 13, 0, 8],['2/26/2020', 13, 0, 8],['2/27/2020', 15, 0, 8],['2/28/2020', 20, 0, 8],['2/29/2020', 23, 0, 8],['3/1/2020', 36, 0, 8],['3/2/2020', 40, 0, 8],['3/3/2020', 51, 0, 8],['3/4/2020', 85, 0, 8],['3/5/2020', 115, 1, 8],['3/6/2020', 163, 2, 8],['3/7/2020', 206, 2, 18],['3/8/2020', 273, 3, 18],['3/9/2020', 321, 4, 18],['3/10/2020', 382, 6, 18],['3/11/2020', 456, 8, 18],['3/12/2020', 590, 10, 18],['3/13/2020', 798, 11, 18],['3/14/2020', 1140, 21, 18],['3/15/2020', 1391, 35, 20],['3/16/2020', 1543, 55, 52],['3/17/2020', 1950, 71, 65],['3/18/2020', 2626, 104, 65],['3/19/2020', 3269, 144, 65],['3/20/2020', 3983, 177, 65],['3/21/2020', 5018, 233, 93],['3/22/2020', 5683, 281, 135],['3/23/2020', 6650, 335, 135],['3/24/2020', 8077, 422, 135],['3/25/2020', 9529, 465, 135],['3/26/2020', 11658, 578, 135],['3/27/2020', 14543, 759, 135],['3/28/2020', 17089, 1019, 135],['3/29/2020', 19522, 1228, 135],['3/30/2020', 22141, 1408, 135],['3/31/2020', 25150, 1789, 135],['4/1/2020', 29474, 2352, 135],['4/2/2020', 33718, 2921, 135],['4/3/2020', 38168, 3605, 135],['4/4/2020', 41903, 4313, 135],['4/5/2020', 47806, 4934, 135],['4/6/2020', 51608, 5373, 135],['4/7/2020', 55242, 6159, 135],['4/8/2020', 60733, 7097, 135],['4/9/2020', 65077, 7978, 135],['4/10/2020', 73758, 8958, 344],['4/11/2020', 78991, 9875, 344],['4/12/2020', 84279, 10612, 344],['4/13/2020', 88621, 11329, 344],['4/14/2020', 93873, 12107, 344],['4/15/2020', 98476, 12868, 344],['4/16/2020', 103093, 13729, 344],['4/17/2020', 108692, 14576, 344],['4/18/2020', 114217, 15464, 344],['4/19/2020', 120067, 16060, 344],['4/20/2020', 124743, 16509, 344],['4/21/2020', 129044, 17337, 344],['4/22/2020', 133495, 18100, 344],['4/23/2020', 138078, 18738, 344],['4/24/2020', 143464, 19506, 344],['4/25/2020', 148377, 20319, 344],['4/26/2020', 152840, 20732, 344],['4/27/2020', 157149, 21092, 344],['4/28/2020', 161145, 21678, 344],['4/29/2020', 165221, 26097, 344],['4/30/2020', 171253, 26771, 344],['5/1/2020', 176756, 27451, 344],['5/2/2020', 182260, 28131, 344],['5/3/2020', 186599, 28446, 344],['5/4/2020', 190584, 28734, 344],['5/5/2020', 194990, 29427, 344],['5/6/2020', 201101, 30076, 344],['5/7/2020', 206715, 30615, 344],['5/8/2020', 211364, 31241, 344],['5/9/2020', 215260, 31587, 344],['5/10/2020', 219183, 31855, 344],['5/11/2020', 223060, 32065, 344],['5/12/2020', 226463, 32692, 344],
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
      ["United Kingdom", 226463, 32692]
    ]);
    var options = {
      backgroundColor: {fill:'transparent',stroke:'#FFF' ,strokeWidth:0 }, 
      region: 'GB',
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



<span style="font-size: 13px">All COVID-19 data displayed on the page is available through our FREE <a href="https://developer.smartable.ai">API program</a>. This UK Coronavirus (COVID-19) Live Stats is refreshed every hour using credible data sources, including the country/state's official government website, <a href="https://en.wikipedia.org/wiki/2019%E2%80%9320_coronavirus_pandemic" target="_blank">data available on wikipedia pages</a>, latest news reports, <a href="https://systems.jhu.edu/research/public-health/ncov/" target="_blank">Johns Hopkins University CSSE 2019-nCoV Dashboard</a>, <a href="https://www.who.int/emergencies/diseases/novel-coronavirus-2019/situation-reports" target="_blank">WHO Situation Reports</a>, <a href="https://www.cdc.gov/coronavirus/2019-ncov/index.html" target="_blank">CDC Situation Updates</a>, and <a href="https://ncov.dxy.cn/ncovh5/view/pneumonia" target="_blank">DXY.cn</a>.</span>


<h2 id="news" class="center" style="margin-top: 60px; font-size: 25px;">Trending Coronavirus News in UK</h2>
<div class="row">
<div class="col-md-6 col-sm-12">
  <div class="content-card">
	<a href="https://www.bbc.com/news/uk-52603566"><div class="card-image" style="background-image: url(https://ichef.bbci.co.uk/news/1024/cpsprodpb/F6CD/production/_112218136_gettyimages-1210981020.jpg)"></div></a>
	<div class="content">
		<div class="card-title"><a href="https://www.bbc.com/news/uk-52603566">Coronavirus: UK sent 50,000 Covid-19 samples to US for testing</a></div>
		<div class="card-excerpt">The government has admitted sending about 50,000 coronavirus tests to the US last week for processing after "operational issues" in UK labs. The Department of Health said sending swabs abroad are among the contingencies to deal with "teething problems".</div>
		<div class="card-meta">
			<span class="card-provider">BBC</span> • <span class="card-date">5/9/2020</span>
		</div>
	</div>
  </div>
</div>
<div class="col-md-6 col-sm-12">
  <div class="content-card">
	<a href="https://www.reuters.com/article/uk-britain-stocks-idUKKBN22D4Q0"><div class="card-image" style="background-image: url(https://s4.reutersmedia.net/resources/r/?m=02&d=20200501&t=2&i=1517125064&w=&fh=545px&fw=&ll=&pl=&sq=&r=LYNXMPEG402VZ)"></div></a>
	<div class="content">
		<div class="card-title"><a href="https://www.reuters.com/article/uk-britain-stocks-idUKKBN22D4Q0">London stocks slide as Trump threatens China over pandemic</a></div>
		<div class="card-excerpt">A slump in energy firms led London-listed stocks lower on Friday, with sentiment also dented by U.S. President Donald Trump's threat to impose new tariffs on China over the coronavirus crisis.</div>
		<div class="card-meta">
			<span class="card-provider">Reuters</span> • <span class="card-date">5/9/2020</span>
		</div>
	</div>
  </div>
</div>
<div class="col-md-6 col-sm-12">
  <div class="content-card">
	<a href="https://www.reuters.com/article/us-health-coronavirus-britain-toll-idUSKBN22L0NT"><div class="card-image" style="background-image: url(https://s2.reutersmedia.net/resources/r/?m=02&d=20200509&t=2&i=1518044322&w=&fh=545px&fw=&ll=&pl=&sq=&r=LYNXMPEG480KD)"></div></a>
	<div class="content">
		<div class="card-title"><a href="https://www.reuters.com/article/us-health-coronavirus-britain-toll-idUSKBN22L0NT">UK coronavirus death toll rises to 31,587</a></div>
		<div class="card-excerpt">The death toll from coronavirus in Britain has risen to 31,587, an increase of 346 in a 24-hour period, Transport Minister Grant Shapps said at the government's daily news briefing.</div>
		<div class="card-meta">
			<span class="card-provider">Reuters</span> • <span class="card-date">5/9/2020</span>
		</div>
	</div>
  </div>
</div>
<div class="col-md-6 col-sm-12">
  <div class="content-card">
	<a href="https://www.theguardian.com/uk-news/2020/may/09/huge-rise-in-fake-goods-and-scams-amid-coronavirus-lockdown-say-uk-councils"><div class="card-image" style="background-image: url(https://i.guim.co.uk/img/media/b75470060cb502048806ed43cba11e9b4336569f/0_0_7000_4200/master/7000.jpg?width=300&quality=45&auto=format&fit=max&dpr=2&s=618e044018b7cb497107ccd50833c0d3)"></div></a>
	<div class="content">
		<div class="card-title"><a href="https://www.theguardian.com/uk-news/2020/may/09/huge-rise-in-fake-goods-and-scams-amid-coronavirus-lockdown-say-uk-councils">Huge rise in fake goods and scams amid coronavirus lockdown, say UK councils</a></div>
		<div class="card-excerpt">Complaints soar over useless face masks, handmade sanitisers and school meal scams</div>
		<div class="card-meta">
			<span class="card-provider">The Guardian</span> • <span class="card-date">5/8/2020</span>
		</div>
	</div>
  </div>
</div>
<div class="col-md-6 col-sm-12">
  <div class="content-card">
	<a href="https://www.reuters.com/news/picture/uk-has-europes-highest-official-coronavi-idUSRTX7HGFD"><div class="card-image" style="background-image: url(https://s3.reutersmedia.net/resources/r/?m=02&d=20200508&t=2&i=1517945063&w=&fh=545&fw=810&ll=&pl=&sq=&r=2020-05-08T132716Z_35495_MRPRC2JIG9SOI2K_RTRMADP_0_HEALTH-CORONAVIRUS-BRITAIN)"></div></a>
	<div class="content">
		<div class="card-title"><a href="https://www.reuters.com/news/picture/uk-has-europes-highest-official-coronavi-idUSRTX7HGFD">UK has Europe's highest official coronavirus death toll</a></div>
		<div class="card-excerpt">Clinical staff wear Personal Protective Equipment (PPE) as they care for a patent at the Intensive Care unit at Royal Papworth Hospital, during the coronavirus disease (COVID-19) outbreak, in Cambridg</div>
		<div class="card-meta">
			<span class="card-provider">Reuters</span> • <span class="card-date">5/8/2020</span>
		</div>
	</div>
  </div>
</div>
<div class="col-md-6 col-sm-12">
  <div class="content-card">
	<a href="https://www.theguardian.com/education/2020/may/08/not-yet-safe-for-schools-to-reopen-in-uk-coronavirus-crisis-unions-warn"><div class="card-image" style="background-image: url(https://i.guim.co.uk/img/media/f7723c22767e0f7adb0ac00497a6e39023669828/0_508_4032_2419/master/4032.jpg?width=300&quality=45&auto=format&fit=max&dpr=2&s=0f419bcdc2217716ce04c96023d7ce56)"></div></a>
	<div class="content">
		<div class="card-title"><a href="https://www.theguardian.com/education/2020/may/08/not-yet-safe-for-schools-to-reopen-in-uk-coronavirus-crisis-unions-warn">Not yet safe for schools to reopen in UK coronavirus crisis, unions warn</a></div>
		<div class="card-excerpt">TUC demands ‘no increase in pupil numbers until full rollout of national test and trace scheme’</div>
		<div class="card-meta">
			<span class="card-provider">The Guardian</span> • <span class="card-date">5/8/2020</span>
		</div>
	</div>
  </div>
</div>
<div class="col-md-6 col-sm-12">
  <div class="content-card">
	<a href="https://www.theguardian.com/politics/live/2020/may/08/uk-coronavirus-live-britain-ve-day-anniversary-lockdown-covid-19-latest-updates"><div class="card-image" style="background-image: url(https://i.guim.co.uk/img/media/ab7b65b6a2b7c2e371b8095e1cc7bdd9b1618a34/0_53_5370_3222/master/5370.jpg?width=300&quality=45&auto=format&fit=max&dpr=2&s=1c831aa7e0fb50d14fc22165455ecf2c)"></div></a>
	<div class="content">
		<div class="card-title"><a href="https://www.theguardian.com/politics/live/2020/may/08/uk-coronavirus-live-britain-ve-day-anniversary-lockdown-covid-19-latest-updates">UK coronavirus live: Britain marks VE Day anniversary under lockdown</a></div>
		<div class="card-excerpt">Boris Johnson’s ‘roadmap’ to ease lockdown restrictions</div>
		<div class="card-meta">
			<span class="card-provider">The Guardian</span> • <span class="card-date">5/8/2020</span>
		</div>
	</div>
  </div>
</div>
<div class="col-md-6 col-sm-12">
  <div class="content-card">
	<a href="https://www.theguardian.com/us-news/2020/may/08/democrats-demand-details-of-trump-organization-requests-for-uk-coronavirus-aid"><div class="card-image" style="background-image: url(https://i.guim.co.uk/img/media/d68a652611ef3bc45365c60dcf9340d9aecd8628/0_0_5395_3239/master/5395.jpg?width=300&quality=45&auto=format&fit=max&dpr=2&s=ab105b8b86afc9d63b6a341cec0b37ab)"></div></a>
	<div class="content">
		<div class="card-title"><a href="https://www.theguardian.com/us-news/2020/may/08/democrats-demand-details-of-trump-organization-requests-for-uk-coronavirus-aid">Democrats demand details of Trump Organization requests for UK coronavirus aid</a></div>
		<div class="card-excerpt">Head of oversight and reform committee suggests move to seek overseas funding was potentially a violation of the US constitution</div>
		<div class="card-meta">
			<span class="card-provider">The Guardian</span> • <span class="card-date">5/7/2020</span>
		</div>
	</div>
  </div>
</div>
<div class="col-md-6 col-sm-12">
  <div class="content-card">
	<a href="https://www.reuters.com/article/us-health-coronavirus-britain-johnson-ca-idUSKBN22J2JA"><div class="card-image" style="background-image: url(https://s3.reutersmedia.net/resources/r/?m=02&d=20200507&t=2&i=1517828082&w=&fh=545px&fw=&ll=&pl=&sq=&r=LYNXMPEG461J5)"></div></a>
	<div class="content">
		<div class="card-title"><a href="https://www.reuters.com/article/us-health-coronavirus-britain-johnson-ca-idUSKBN22J2JA">UK PM Johnson to proceed with 'maximum caution' in coronavirus response</a></div>
		<div class="card-excerpt">British Prime Minister Boris Johnson will proceed with maximum caution as he looks to the next phase of the government's response to the coronavirus, a spokesman from his office said on Thursday.</div>
		<div class="card-meta">
			<span class="card-provider">Reuters</span> • <span class="card-date">5/7/2020</span>
		</div>
	</div>
  </div>
</div>
<div class="col-md-6 col-sm-12">
  <div class="content-card">
	<a href="https://www.theguardian.com/music/2020/may/07/ty-mercury-prize-nominated-uk-rapper-dies-aged-47-of-coronavirus"><div class="card-image" style="background-image: url(https://i.guim.co.uk/img/media/5af12b11d308ee33610a9dc614cecd43dd2b87b3/1174_242_3976_2388/master/3976.jpg?width=300&quality=45&auto=format&fit=max&dpr=2&s=4ddb0973e0978c2d47ad6c6e137c41d2)"></div></a>
	<div class="content">
		<div class="card-title"><a href="https://www.theguardian.com/music/2020/may/07/ty-mercury-prize-nominated-uk-rapper-dies-aged-47-of-coronavirus">Ty, Mercury prize-nominated UK rapper, dies aged 47 of coronavirus</a></div>
		<div class="card-excerpt">Rapper who recorded acclaimed albums including Upward and Awkward had been put in medically induced coma</div>
		<div class="card-meta">
			<span class="card-provider">The Guardian</span> • <span class="card-date">5/7/2020</span>
		</div>
	</div>
  </div>
</div>

</div>

