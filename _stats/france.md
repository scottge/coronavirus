---
category: stats
title: "France Coronavirus (COVID-19) Live Stats"
excerpt: "Live stats of COVID-19 in France. Total Cases: 177423 (+453), Deaths: 26643 (+263), Recoveries: 56724(+507)."
publishedDateTime: 2020-05-12T00:45:10Z
updatedDateTime: 2020-05-12T00:45:10Z
webUrl: "https://smartable.ai/apps/coronavirus/stats/france/"
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
  - url: "https://smartable.azureedge.net/coronavirus/sites/2/2020/france.jpg"
    width: 900
    height: 564
    title: "France Coronavirus (COVID-19) Live Stats"

---
<div class="total-stats" style="text-align: center;">
    <h3>
	    <div style="font-size: 18px; font-weight: 400;">Total Confirmed Cases:</div>
	    177423 (<span class='red'>+453</span>)
    </h3>
    <h3>
	    <div style="font-size: 18px; font-weight: 400;">Total Deaths:</div>
	    26643 (<span class='red'>+263</span>)
    </h3>
    <h3>
	    <div style="font-size: 18px; font-weight: 400;">Total Recovered:</div>
	    56724 (<span class='green'>+507</span>)
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
      ['1/22/2020', 0, 0, 0],['1/23/2020', 0, 0, 0],['1/24/2020', 2, 0, 0],['1/25/2020', 3, 0, 0],['1/26/2020', 3, 0, 0],['1/27/2020', 3, 0, 0],['1/28/2020', 4, 0, 0],['1/29/2020', 5, 0, 0],['1/30/2020', 5, 0, 0],['1/31/2020', 5, 0, 0],['2/1/2020', 6, 0, 0],['2/2/2020', 6, 0, 0],['2/3/2020', 6, 0, 0],['2/4/2020', 6, 0, 0],['2/5/2020', 6, 0, 0],['2/6/2020', 6, 0, 0],['2/7/2020', 6, 0, 0],['2/8/2020', 11, 0, 0],['2/9/2020', 11, 0, 0],['2/10/2020', 11, 0, 0],['2/11/2020', 11, 0, 0],['2/12/2020', 11, 0, 2],['2/13/2020', 11, 0, 2],['2/14/2020', 11, 0, 2],['2/15/2020', 12, 1, 4],['2/16/2020', 12, 1, 4],['2/17/2020', 12, 1, 4],['2/18/2020', 12, 1, 4],['2/19/2020', 12, 1, 4],['2/20/2020', 12, 1, 4],['2/21/2020', 12, 1, 4],['2/22/2020', 12, 1, 4],['2/23/2020', 12, 1, 4],['2/24/2020', 12, 1, 4],['2/25/2020', 14, 1, 11],['2/26/2020', 18, 2, 11],['2/27/2020', 38, 2, 11],['2/28/2020', 57, 2, 11],['2/29/2020', 100, 2, 12],['3/1/2020', 130, 2, 12],['3/2/2020', 191, 3, 12],['3/3/2020', 204, 4, 12],['3/4/2020', 285, 4, 12],['3/5/2020', 377, 6, 12],['3/6/2020', 653, 9, 12],['3/7/2020', 949, 11, 12],['3/8/2020', 1126, 19, 12],['3/9/2020', 1209, 19, 12],['3/10/2020', 1784, 33, 12],['3/11/2020', 2281, 48, 12],['3/12/2020', 2281, 61, 12],['3/13/2020', 3661, 79, 12],['3/14/2020', 4469, 91, 12],['3/15/2020', 4499, 127, 12],['3/16/2020', 6633, 148, 12],['3/17/2020', 7652, 175, 602],['3/18/2020', 9043, 264, 602],['3/19/2020', 10871, 372, 1295],['3/20/2020', 12612, 450, 1587],['3/21/2020', 14282, 562, 1587],['3/22/2020', 16018, 674, 2200],['3/23/2020', 19856, 860, 2200],['3/24/2020', 22304, 1100, 3281],['3/25/2020', 25233, 1331, 3900],['3/26/2020', 29155, 1696, 4948],['3/27/2020', 32964, 1995, 5700],['3/28/2020', 37575, 2314, 5700],['3/29/2020', 40174, 2606, 7202],['3/30/2020', 44550, 3024, 7927],['3/31/2020', 52128, 3523, 9444],['4/1/2020', 56989, 4032, 10935],['4/2/2020', 59105, 5387, 12428],['4/3/2020', 64338, 6507, 14008],['4/4/2020', 68605, 7560, 15438],['4/5/2020', 70478, 8078, 16183],['4/6/2020', 74390, 8911, 17250],['4/7/2020', 78167, 10328, 19337],['4/8/2020', 82048, 10869, 21254],['4/9/2020', 86334, 12210, 23206],['4/10/2020', 90676, 13197, 24932],['4/11/2020', 93790, 13832, 26391],['4/12/2020', 120633, 14393, 27186],['4/13/2020', 124298, 14967, 27718],['4/14/2020', 130253, 15729, 28805],['4/15/2020', 133470, 17167, 30955],['4/16/2020', 145960, 17920, 32812],['4/17/2020', 147969, 18681, 34420],['4/18/2020', 147969, 19323, 35983],['4/19/2020', 152894, 19718, 36578],['4/20/2020', 155275, 20265, 37409],['4/21/2020', 155650, 20796, 39181],['4/22/2020', 155860, 21340, 40657],['4/23/2020', 158183, 21856, 42088],['4/24/2020', 159828, 22245, 43493],['4/25/2020', 161488, 22614, 44594],['4/26/2020', 162100, 22856, 44903],['4/27/2020', 165842, 23293, 45513],['4/28/2020', 167605, 23660, 46886],['4/29/2020', 167605, 24087, 48228],['4/30/2020', 167605, 24376, 49476],['5/1/2020', 168000, 24568, 50019],['5/2/2020', 168396, 24760, 50562],['5/3/2020', 168693, 24895, 50784],['5/4/2020', 169462, 25201, 51371],['5/5/2020', 170551, 25531, 52736],['5/6/2020', 174191, 25809, 53972],['5/7/2020', 174791, 25987, 55027],['5/8/2020', 176079, 26230, 55782],['5/9/2020', 176658, 26310, 56038],['5/10/2020', 176970, 26380, 56217],['5/11/2020', 177423, 26643, 56724],
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
      ["France", 177423, 26643]
    ]);
    var options = {
      backgroundColor: {fill:'transparent',stroke:'#FFF' ,strokeWidth:0 }, 
      region: 'FR',
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



<span style="font-size: 13px">All COVID-19 data displayed on the page is available through our FREE <a href="https://developer.smartable.ai">API program</a>. This France Coronavirus (COVID-19) Live Stats is refreshed every hour using credible data sources, including the country/state's official government website, <a href="https://en.wikipedia.org/wiki/2019%E2%80%9320_coronavirus_pandemic" target="_blank">data available on wikipedia pages</a>, latest news reports, <a href="https://systems.jhu.edu/research/public-health/ncov/" target="_blank">Johns Hopkins University CSSE 2019-nCoV Dashboard</a>, <a href="https://www.who.int/emergencies/diseases/novel-coronavirus-2019/situation-reports" target="_blank">WHO Situation Reports</a>, <a href="https://www.cdc.gov/coronavirus/2019-ncov/index.html" target="_blank">CDC Situation Updates</a>, and <a href="https://ncov.dxy.cn/ncovh5/view/pneumonia" target="_blank">DXY.cn</a>.</span>


<h2 id="news" class="center" style="margin-top: 60px; font-size: 25px;">Trending Coronavirus News in France</h2>
<div class="row">
<div class="col-md-6 col-sm-12">
  <div class="content-card">
	<a href="https://www.reuters.com/article/us-health-coronavirus-france-idUSKBN22L0RR"><div class="card-image" style="background-image: url(https://s3.reutersmedia.net/resources/r/?m=02&d=20200509&t=2&i=1518050729&w=&fh=545px&fw=&ll=&pl=&sq=&r=LYNXMPEG480MO)"></div></a>
	<div class="content">
		<div class="card-title"><a href="https://www.reuters.com/article/us-health-coronavirus-france-idUSKBN22L0RR">France says total death toll from coronavirus rises by 80 to 26,310</a></div>
		<div class="card-excerpt">The number of people who have died from coronavirus infections in France rose by 80 to 26,310 on Saturday, the health ministry said, a much smaller daily increase than the previous day when it was 243.</div>
		<div class="card-meta">
			<span class="card-provider">Reuters</span> • <span class="card-date">5/9/2020</span>
		</div>
	</div>
  </div>
</div>
<div class="col-md-6 col-sm-12">
  <div class="content-card">
	<a href="https://www.reuters.com/article/us-health-coronavirus-france-casualties-idUSKBN22K2J9"><div class="card-image" style="background-image: url(https://s4.reutersmedia.net/resources_v3/images/rcom-default.png)"></div></a>
	<div class="content">
		<div class="card-title"><a href="https://www.reuters.com/article/us-health-coronavirus-france-casualties-idUSKBN22K2J9">France's coronavirus daily death toll rises again</a></div>
		<div class="card-excerpt">The number of people who have died from coronavirus infection in France rose 243 to 26,230 on Friday, a higher daily death toll than the previous day when it stood at 178.</div>
		<div class="card-meta">
			<span class="card-provider">Reuters</span> • <span class="card-date">5/8/2020</span>
		</div>
	</div>
  </div>
</div>
<div class="col-md-6 col-sm-12">
  <div class="content-card">
	<a href="https://www.reuters.com/article/us-health-coronavirus-france-casualties/frances-coronavirus-death-toll-close-to-26000-lockdown-to-be-lifted-idUSKBN22J2X0"><div class="card-image" style="background-image: url(https://s1.reutersmedia.net/resources/r/?m=02&d=20200507&t=2&i=1517843971&w=&fh=545px&fw=&ll=&pl=&sq=&r=LYNXMPEG461SA)"></div></a>
	<div class="content">
		<div class="card-title"><a href="https://www.reuters.com/article/us-health-coronavirus-france-casualties/frances-coronavirus-death-toll-close-to-26000-lockdown-to-be-lifted-idUSKBN22J2X0">France's coronavirus death toll close to 26,000, lockdown to be lifted</a></div>
		<div class="card-excerpt">France's coronavirus-linked death toll reached almost 26,000 on Thursday but rose less sharply than in previous days as the government confirmed it would start lifting an almost two-month-old national lockdown from Monday.</div>
		<div class="card-meta">
			<span class="card-provider">Reuters</span> • <span class="card-date">5/7/2020</span>
		</div>
	</div>
  </div>
</div>
<div class="col-md-6 col-sm-12">
  <div class="content-card">
	<a href="https://www.bbc.com/news/world-europe-52557722?intlink_from_url=&link_location=live-reporting-story"><div class="card-image" style="background-image: url(https://ichef.bbci.co.uk/news/1024/cpsprodpb/D9AF/production/_112172755_f10792f4-45e6-498c-bf6f-95cb2a3b0287.jpg)"></div></a>
	<div class="content">
		<div class="card-title"><a href="https://www.bbc.com/news/world-europe-52557722?intlink_from_url=&link_location=live-reporting-story">Coronavirus: Lockdown bites poor as France eases grip</a></div>
		<div class="card-excerpt">Image caption The French economy has been battered by the lockdown and may take some time to recover I meet a young woman waiting in the queue, who introduces herself as Madame Ouattara. Even behind her mask,</div>
		<div class="card-meta">
			<span class="card-provider">BBC</span> • <span class="card-date">5/7/2020</span>
		</div>
	</div>
  </div>
</div>
<div class="col-md-6 col-sm-12">
  <div class="content-card">
	<a href="https://www.reuters.com/article/us-health-coronavirus-russia-cases-idUSKBN22J0ZR"><div class="card-image" style="background-image: url(https://s2.reutersmedia.net/resources/r/?m=02&d=20200507&t=2&i=1517768397&w=&fh=545px&fw=&ll=&pl=&sq=&r=LYNXMPEG460HF)"></div></a>
	<div class="content">
		<div class="card-title"><a href="https://www.reuters.com/article/us-health-coronavirus-russia-cases-idUSKBN22J0ZR">Russia overtakes Germany, France after record rise in coronavirus cases</a></div>
		<div class="card-excerpt">Russia's coronavirus cases overtook France and Germany on Thursday to become the fifth highest number in the world after a record daily rise, and Moscow's mayor said the real figure, not captured by official statistics,</div>
		<div class="card-meta">
			<span class="card-provider">Reuters</span> • <span class="card-date">5/7/2020</span>
		</div>
	</div>
  </div>
</div>
<div class="col-md-6 col-sm-12">
  <div class="content-card">
	<a href="https://www.theguardian.com/world/2020/may/07/global-report-france-to-ease-lockdown-as-russia-becomes-coronavirus-hotspot"><div class="card-image" style="background-image: url(https://i.guim.co.uk/img/media/2de55396a46ae2ac821b3491c2f59a128eb47f55/0_199_4000_2399/master/4000.jpg?width=300&quality=45&auto=format&fit=max&dpr=2&s=02c8d396058e98cf999125969e127dd5)"></div></a>
	<div class="content">
		<div class="card-title"><a href="https://www.theguardian.com/world/2020/may/07/global-report-france-to-ease-lockdown-as-russia-becomes-coronavirus-hotspot">Global report: France to ease lockdown as Russia becomes coronavirus hotspot</a></div>
		<div class="card-excerpt">Also, Germans ‘will have to get used to living with virus’ as WHO warns on domestic violence</div>
		<div class="card-meta">
			<span class="card-provider">The Guardian</span> • <span class="card-date">5/7/2020</span>
		</div>
	</div>
  </div>
</div>
<div class="col-md-6 col-sm-12">
  <div class="content-card">
	<a href="https://www.bbc.com/news/world-europe-52579482"><div class="card-image" style="background-image: url(https://ichef.bbci.co.uk/news/1024/cpsprodpb/144B8/production/_112182138_mediaitem112182137.jpg)"></div></a>
	<div class="content">
		<div class="card-title"><a href="https://www.bbc.com/news/world-europe-52579482">Coronavirus: Paris restrictions to stay as France reopens</a></div>
		<div class="card-excerpt">Restrictions will remain in the capital and north-eastern regions. It comes as France prepares to relax its lockdown on Monday, with shops and some schools allowed to reopen. The country has suffered one of the highest Covid-19 death rates in Europe.</div>
		<div class="card-meta">
			<span class="card-provider">BBC</span> • <span class="card-date">5/7/2020</span>
		</div>
	</div>
  </div>
</div>
<div class="col-md-6 col-sm-12">
  <div class="content-card">
	<a href="https://www.nbcnews.com/health/health-news/live-blog/2020-05-07-coronavirus-news-n1201801/ncrd1201841"><div class="card-image" style="background-image: url(https://nodeassets.nbcnews.com/cdnassets/projects/socialshareimages-bento/og-nbcnews1200x630.png)"></div></a>
	<div class="content">
		<div class="card-title"><a href="https://www.nbcnews.com/health/health-news/live-blog/2020-05-07-coronavirus-news-n1201801/ncrd1201841">Russia surpasses France and Germany in total number of coronavirus cases</a></div>
		<div class="card-excerpt">Scientists meanwhile, are carefully watching for signs that the transmission of coronavirus could slow in warm weather. The consensus seems to be that the virus will be seasonal and endemic, meaning that,</div>
		<div class="card-meta">
			<span class="card-provider">NBC News</span> • <span class="card-date">5/7/2020</span>
		</div>
	</div>
  </div>
</div>
<div class="col-md-6 col-sm-12">
  <div class="content-card">
	<a href="https://www.foxnews.com/science/coronavirus-was-circulating-in-france-in-december-case-report-suggests"><div class="card-image" style="background-image: url(https://a57.foxnews.com/static.foxnews.com/foxnews.com/content/uploads/2018/09/640/320/istock-492070598.jpg?ve=1&tl=1)"></div></a>
	<div class="content">
		<div class="card-title"><a href="https://www.foxnews.com/science/coronavirus-was-circulating-in-france-in-december-case-report-suggests">Coronavirus was circulating in France in December, case report suggests</a></div>
		<div class="card-excerpt">The coronavirus was circulating in France as early as December, new evidence suggests. Doctors in France discovered that a patient who went to the hospital in late December with respiratory symptoms was positive for COVID-19,</div>
		<div class="card-meta">
			<span class="card-provider">Fox News</span> • <span class="card-date">5/7/2020</span>
		</div>
	</div>
  </div>
</div>
<div class="col-md-6 col-sm-12">
  <div class="content-card">
	<a href="https://www.nytimes.com/2020/05/05/world/europe/france-coronavirus-timeline.html"><div class="card-image" style="background-image: url(https://static01.nyt.com/images/2020/05/05/world/05virus-france-copy/05virus-france-copy-facebookJumbo-v2.jpg)"></div></a>
	<div class="content">
		<div class="card-title"><a href="https://www.nytimes.com/2020/05/05/world/europe/france-coronavirus-timeline.html">New Report Says Coronavirus May Have Made Early Appearance in France</a></div>
		<div class="card-excerpt">A sample taken on Dec. 27 from a French patient with pneumonia has tested positive for coronavirus, nearly a month before the disease was first officially acknowledged to have emerged in France.</div>
		<div class="card-meta">
			<span class="card-provider">New York Times</span> • <span class="card-date">5/5/2020</span>
		</div>
	</div>
  </div>
</div>

</div>

