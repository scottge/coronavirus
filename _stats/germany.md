---
category: stats
title: "Germany Coronavirus (COVID-19) Live Stats"
excerpt: "Live stats of COVID-19 in Germany. Total Cases: 172576 (+697), Deaths: 7661 (+92), Recoveries: 145600(-)."
publishedDateTime: 2020-05-11T22:45:10Z
updatedDateTime: 2020-05-11T22:45:10Z
webUrl: "https://smartable.ai/apps/coronavirus/stats/germany/"
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
  - url: "https://smartable.azureedge.net/coronavirus/sites/2/2020/germany.jpg"
    width: 900
    height: 564
    title: "Germany Coronavirus (COVID-19) Live Stats"

---
<div class="total-stats" style="text-align: center;">
    <h3>
	    <div style="font-size: 18px; font-weight: 400;">Total Confirmed Cases:</div>
	    172576 (<span class='red'>+697</span>)
    </h3>
    <h3>
	    <div style="font-size: 18px; font-weight: 400;">Total Deaths:</div>
	    7661 (<span class='red'>+92</span>)
    </h3>
    <h3>
	    <div style="font-size: 18px; font-weight: 400;">Total Recovered:</div>
	    145600 (-)
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
      ['1/22/2020', 0, 0, 0],['1/23/2020', 0, 0, 0],['1/24/2020', 0, 0, 0],['1/25/2020', 0, 0, 0],['1/26/2020', 0, 0, 0],['1/27/2020', 1, 0, 0],['1/28/2020', 4, 0, 0],['1/29/2020', 4, 0, 0],['1/30/2020', 4, 0, 0],['1/31/2020', 5, 0, 0],['2/1/2020', 8, 0, 0],['2/2/2020', 10, 0, 0],['2/3/2020', 12, 0, 0],['2/4/2020', 12, 0, 0],['2/5/2020', 12, 0, 0],['2/6/2020', 12, 0, 0],['2/7/2020', 13, 0, 0],['2/8/2020', 13, 0, 0],['2/9/2020', 14, 0, 0],['2/10/2020', 14, 0, 0],['2/11/2020', 16, 0, 0],['2/12/2020', 16, 0, 0],['2/13/2020', 16, 0, 1],['2/14/2020', 16, 0, 1],['2/15/2020', 16, 0, 1],['2/16/2020', 16, 0, 1],['2/17/2020', 16, 0, 1],['2/18/2020', 16, 0, 12],['2/19/2020', 16, 0, 12],['2/20/2020', 16, 0, 12],['2/21/2020', 16, 0, 14],['2/22/2020', 16, 0, 14],['2/23/2020', 16, 0, 14],['2/24/2020', 16, 0, 14],['2/25/2020', 17, 0, 14],['2/26/2020', 27, 0, 15],['2/27/2020', 46, 0, 16],['2/28/2020', 48, 0, 16],['2/29/2020', 79, 0, 16],['3/1/2020', 130, 0, 16],['3/2/2020', 159, 0, 16],['3/3/2020', 196, 0, 16],['3/4/2020', 262, 0, 16],['3/5/2020', 482, 0, 16],['3/6/2020', 670, 0, 17],['3/7/2020', 799, 0, 18],['3/8/2020', 1040, 0, 18],['3/9/2020', 1176, 2, 18],['3/10/2020', 1457, 2, 18],['3/11/2020', 1908, 3, 25],['3/12/2020', 2745, 6, 25],['3/13/2020', 3675, 8, 46],['3/14/2020', 4599, 9, 46],['3/15/2020', 5813, 13, 46],['3/16/2020', 7272, 17, 67],['3/17/2020', 9367, 26, 71],['3/18/2020', 12327, 28, 105],['3/19/2020', 15320, 44, 115],['3/20/2020', 19848, 68, 180],['3/21/2020', 22364, 84, 239],['3/22/2020', 24873, 94, 266],['3/23/2020', 29056, 123, 453],['3/24/2020', 32991, 159, 3290],['3/25/2020', 37323, 206, 3547],['3/26/2020', 43938, 267, 5673],['3/27/2020', 50871, 351, 6658],['3/28/2020', 57695, 433, 8481],['3/29/2020', 62435, 541, 9211],['3/30/2020', 66885, 645, 13500],['3/31/2020', 71808, 775, 16100],['4/1/2020', 77981, 931, 18700],['4/2/2020', 84794, 1107, 22440],['4/3/2020', 91159, 1275, 24575],['4/4/2020', 96092, 1444, 26400],['4/5/2020', 100123, 1584, 28700],['4/6/2020', 103375, 1810, 36081],['4/7/2020', 107663, 2016, 36081],['4/8/2020', 113296, 2349, 46300],['4/9/2020', 118235, 2607, 52407],['4/10/2020', 122171, 2736, 53913],['4/11/2020', 125452, 2871, 57400],['4/12/2020', 127854, 3022, 64300],['4/13/2020', 130072, 3194, 68200],['4/14/2020', 132210, 3495, 72600],['4/15/2020', 134753, 3804, 72600],['4/16/2020', 137698, 4052, 81800],['4/17/2020', 141397, 4352, 83114],['4/18/2020', 143724, 4538, 88000],['4/19/2020', 145742, 4642, 88000],['4/20/2020', 147065, 4862, 95200],['4/21/2020', 148453, 5086, 99400],['4/22/2020', 150648, 5315, 103300],['4/23/2020', 153129, 5575, 106800],['4/24/2020', 154999, 5760, 109800],['4/25/2020', 156513, 5877, 109800],['4/26/2020', 157770, 5976, 114500],['4/27/2020', 158758, 6126, 114500],['4/28/2020', 159912, 6314, 120400],['4/29/2020', 161539, 6467, 123500],['4/30/2020', 163009, 6623, 123500],['5/1/2020', 163988, 6717, 126250],['5/2/2020', 164967, 6812, 130600],['5/3/2020', 165664, 6866, 132700],['5/4/2020', 166152, 6993, 135100],['5/5/2020', 167007, 6993, 135100],['5/6/2020', 168162, 7275, 139900],['5/7/2020', 169430, 7392, 141700],['5/8/2020', 170588, 7510, 143300],['5/9/2020', 171324, 7549, 143300],['5/10/2020', 171879, 7569, 145600],['5/11/2020', 172576, 7661, 145600],
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
      ["Germany", 172576, 7661]
    ]);
    var options = {
      backgroundColor: {fill:'transparent',stroke:'#FFF' ,strokeWidth:0 }, 
      region: 'DE',
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



<span style="font-size: 13px">All COVID-19 data displayed on the page is available through our FREE <a href="https://developer.smartable.ai">API program</a>. This Germany Coronavirus (COVID-19) Live Stats is refreshed every hour using credible data sources, including the country/state's official government website, <a href="https://en.wikipedia.org/wiki/2019%E2%80%9320_coronavirus_pandemic" target="_blank">data available on wikipedia pages</a>, latest news reports, <a href="https://systems.jhu.edu/research/public-health/ncov/" target="_blank">Johns Hopkins University CSSE 2019-nCoV Dashboard</a>, <a href="https://www.who.int/emergencies/diseases/novel-coronavirus-2019/situation-reports" target="_blank">WHO Situation Reports</a>, <a href="https://www.cdc.gov/coronavirus/2019-ncov/index.html" target="_blank">CDC Situation Updates</a>, and <a href="https://ncov.dxy.cn/ncovh5/view/pneumonia" target="_blank">DXY.cn</a>.</span>


<h2 id="news" class="center" style="margin-top: 60px; font-size: 25px;">Trending Coronavirus News in Germany</h2>
<div class="row">
<div class="col-md-6 col-sm-12">
  <div class="content-card">
	<a href="https://www.reuters.com/article/us-health-coronavirus-germany-cases-idUSKBN22M019"><div class="card-image" style="background-image: url(https://s1.reutersmedia.net/resources/r/?m=02&d=20200510&t=2&i=1518071601&w=&fh=545px&fw=&ll=&pl=&sq=&r=LYNXMPEG4901A)"></div></a>
	<div class="content">
		<div class="card-title"><a href="https://www.reuters.com/article/us-health-coronavirus-germany-cases-idUSKBN22M019">Germany's confirmed coronavirus cases rise by 667 to 169,218: RKI</a></div>
		<div class="card-excerpt">The number of confirmed coronavirus cases in Germany increased by 667 to 169,218, data from the Robert Koch Institute (RKI) for infectious diseases showed on Sunday.</div>
		<div class="card-meta">
			<span class="card-provider">Reuters</span> • <span class="card-date">5/9/2020</span>
		</div>
	</div>
  </div>
</div>
<div class="col-md-6 col-sm-12">
  <div class="content-card">
	<a href="https://www.latimes.com/world-nation/story/2020-05-09/outbreaks-in-germany-s-korea-show-the-risks-in-easing-up"><div class="card-image" style="background-image: url(https://ca-times.brightspotcdn.com/dims4/default/554396d/2147483647/strip/true/crop/3060x1999+0+196/resize/320x209!/quality/90/?url=https%3A%2F%2Fcalifornia-times-brightspot.s3.amazonaws.com%2F28%2F3c%2F8f91ad034b1e8b1e2c0589f0a3cf%2F49534865371-05ecf26c90-o.jpg)"></div></a>
	<div class="content">
		<div class="card-title"><a href="https://www.latimes.com/world-nation/story/2020-05-09/outbreaks-in-germany-s-korea-show-the-risks-in-easing-up">Coronavirus flare-ups in Germany, South Korea show the risks in easing restrictions</a></div>
		<div class="card-excerpt">South Korea and Germany scramble to contain fresh coronavirus outbreaks while Italians rediscover la dolce vita as countries begin to reopen.</div>
		<div class="card-meta">
			<span class="card-provider">Los Angeles Times</span> • <span class="card-date">5/9/2020</span>
		</div>
	</div>
  </div>
</div>
<div class="col-md-6 col-sm-12">
  <div class="content-card">
	<a href="https://www.ibtimes.com/coronavirus-cases-death-toll-parts-germany-postpone-reopening-after-rise-infections-2973363"><div class="card-image" style="background-image: url(https://s1.ibtimes.com/sites/www.ibtimes.com/files/styles/full/public/2020/05/07/germany-europes-largest-economy-has-started-reopening-schools.jpg)"></div></a>
	<div class="content">
		<div class="card-title"><a href="https://www.ibtimes.com/coronavirus-cases-death-toll-parts-germany-postpone-reopening-after-rise-infections-2973363">Coronavirus Cases, Death Toll: Parts of Germany Postpone Reopening After Rise In Infections</a></div>
		<div class="card-excerpt">An outbreak at a meatpacking plant in one German district has forced authorities to delay the reopening process.</div>
		<div class="card-meta">
			<span class="card-provider">International Business Times</span> • <span class="card-date">5/9/2020</span>
		</div>
	</div>
  </div>
</div>
<div class="col-md-6 col-sm-12">
  <div class="content-card">
	<a href="https://www.reuters.com/article/us-health-coronavirus-germany-cases-idUSKBN22L03L"><div class="card-image" style="background-image: url(https://s1.reutersmedia.net/resources/r/?m=02&d=20200509&t=2&i=1518010706&w=&fh=545px&fw=&ll=&pl=&sq=&r=LYNXMPEG4802A)"></div></a>
	<div class="content">
		<div class="card-title"><a href="https://www.reuters.com/article/us-health-coronavirus-germany-cases-idUSKBN22L03L">Germany's confirmed coronavirus cases rise by 1,251 to 168,551: RKI</a></div>
		<div class="card-excerpt">The number of confirmed coronavirus cases in Germany increased by 1,251 to 168,551, data from the Robert Koch Institute (RKI) for infectious diseases showed on Saturday.</div>
		<div class="card-meta">
			<span class="card-provider">Reuters</span> • <span class="card-date">5/8/2020</span>
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
	<a href="https://www.reuters.com/article/us-health-coronavirus-germany-reproducti-idUSKBN22J12E"><div class="card-image" style="background-image: url(https://s4.reutersmedia.net/resources/r/?m=02&d=20200507&t=2&i=1517770753&w=&fh=545px&fw=&ll=&pl=&sq=&r=LYNXMPEG460IV)"></div></a>
	<div class="content">
		<div class="card-title"><a href="https://www.reuters.com/article/us-health-coronavirus-germany-reproducti-idUSKBN22J12E">Coronavirus reproduction rate at 0.65 in Germany: RKI</a></div>
		<div class="card-excerpt">The reproduction rate of the novel coronavirus in Germany is currently estimated at 0.65, the Robert Koch Institute for infectious diseases said on Thursday.</div>
		<div class="card-meta">
			<span class="card-provider">Reuters</span> • <span class="card-date">5/7/2020</span>
		</div>
	</div>
  </div>
</div>
<div class="col-md-6 col-sm-12">
  <div class="content-card">
	<a href="https://www.reuters.com/article/us-health-coronavirus-germany-cases-idUSKBN22J09L"><div class="card-image" style="background-image: url(https://s2.reutersmedia.net/resources/r/?m=02&d=20200507&t=2&i=1517744540&w=&fh=545px&fw=&ll=&pl=&sq=&r=LYNXMPEG4604H)"></div></a>
	<div class="content">
		<div class="card-title"><a href="https://www.reuters.com/article/us-health-coronavirus-germany-cases-idUSKBN22J09L">Germany's confirmed coronavirus cases rise by 1,284 to 166,091: RKI</a></div>
		<div class="card-excerpt">The number of confirmed coronavirus cases in Germany increased by 1,284 to 166,091, data from the Robert Koch Institute (RKI) for infectious diseases showed on Thursday.</div>
		<div class="card-meta">
			<span class="card-provider">Reuters</span> • <span class="card-date">5/6/2020</span>
		</div>
	</div>
  </div>
</div>

</div>

