---
category: stats
title: "India Coronavirus (COVID-19) Live Stats"
excerpt: "Live stats of COVID-19 in India. Total Cases: 74243 (+3416), Deaths: 2415 (+121), Recoveries: 24420(+1871)."
publishedDateTime: 2020-05-12T20:45:10Z
updatedDateTime: 2020-05-12T20:45:10Z
webUrl: "https://smartable.ai/apps/coronavirus/stats/india/"
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
  - url: "https://smartable.azureedge.net/coronavirus/sites/2/2020/india.jpg"
    width: 900
    height: 564
    title: "India Coronavirus (COVID-19) Live Stats"

---
<div class="total-stats" style="text-align: center;">
    <h3>
	    <div style="font-size: 18px; font-weight: 400;">Total Confirmed Cases:</div>
	    74243 (<span class='red'>+3416</span>)
    </h3>
    <h3>
	    <div style="font-size: 18px; font-weight: 400;">Total Deaths:</div>
	    2415 (<span class='red'>+121</span>)
    </h3>
    <h3>
	    <div style="font-size: 18px; font-weight: 400;">Total Recovered:</div>
	    24420 (<span class='green'>+1871</span>)
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
      ['1/22/2020', 0, 0, 0],['1/23/2020', 0, 0, 0],['1/24/2020', 0, 0, 0],['1/25/2020', 0, 0, 0],['1/26/2020', 0, 0, 0],['1/27/2020', 0, 0, 0],['1/28/2020', 0, 0, 0],['1/29/2020', 0, 0, 0],['1/30/2020', 1, 0, 0],['1/31/2020', 1, 0, 0],['2/1/2020', 1, 0, 0],['2/2/2020', 2, 0, 0],['2/3/2020', 3, 0, 0],['2/4/2020', 3, 0, 0],['2/5/2020', 3, 0, 0],['2/6/2020', 3, 0, 0],['2/7/2020', 3, 0, 0],['2/8/2020', 3, 0, 0],['2/9/2020', 3, 0, 0],['2/10/2020', 3, 0, 0],['2/11/2020', 3, 0, 0],['2/12/2020', 3, 0, 0],['2/13/2020', 3, 0, 0],['2/14/2020', 3, 0, 0],['2/15/2020', 3, 0, 0],['2/16/2020', 3, 0, 3],['2/17/2020', 3, 0, 3],['2/18/2020', 3, 0, 3],['2/19/2020', 3, 0, 3],['2/20/2020', 3, 0, 3],['2/21/2020', 3, 0, 3],['2/22/2020', 3, 0, 3],['2/23/2020', 3, 0, 3],['2/24/2020', 3, 0, 3],['2/25/2020', 3, 0, 3],['2/26/2020', 3, 0, 3],['2/27/2020', 3, 0, 3],['2/28/2020', 3, 0, 3],['2/29/2020', 3, 0, 3],['3/1/2020', 3, 0, 3],['3/2/2020', 5, 0, 3],['3/3/2020', 5, 0, 3],['3/4/2020', 28, 0, 3],['3/5/2020', 30, 0, 3],['3/6/2020', 31, 0, 3],['3/7/2020', 34, 0, 3],['3/8/2020', 39, 0, 3],['3/9/2020', 43, 0, 3],['3/10/2020', 56, 0, 4],['3/11/2020', 62, 1, 4],['3/12/2020', 75, 1, 4],['3/13/2020', 83, 2, 10],['3/14/2020', 105, 2, 10],['3/15/2020', 114, 2, 13],['3/16/2020', 129, 3, 13],['3/17/2020', 148, 3, 14],['3/18/2020', 171, 3, 15],['3/19/2020', 201, 5, 20],['3/20/2020', 275, 5, 23],['3/21/2020', 332, 5, 27],['3/22/2020', 425, 8, 27],['3/23/2020', 499, 10, 37],['3/24/2020', 562, 11, 40],['3/25/2020', 673, 13, 43],['3/26/2020', 747, 20, 66],['3/27/2020', 902, 20, 83],['3/28/2020', 987, 25, 87],['3/29/2020', 1024, 27, 95],['3/30/2020', 1251, 32, 102],['3/31/2020', 1590, 45, 148],['4/1/2020', 2032, 58, 148],['4/2/2020', 2567, 72, 192],['4/3/2020', 2567, 72, 192],['4/4/2020', 3588, 99, 229],['4/5/2020', 4314, 118, 328],['4/6/2020', 4778, 136, 382],['4/7/2020', 5356, 160, 468],['4/8/2020', 5916, 178, 506],['4/9/2020', 6771, 228, 635],['4/10/2020', 7600, 249, 774],['4/11/2020', 8446, 288, 969],['4/12/2020', 9240, 331, 1096],['4/13/2020', 10541, 358, 1205],['4/14/2020', 11555, 396, 1362],['4/15/2020', 12370, 422, 1508],['4/16/2020', 13495, 448, 1777],['4/17/2020', 14425, 488, 2045],['4/18/2020', 16365, 521, 2466],['4/19/2020', 17615, 559, 2854],['4/20/2020', 18658, 592, 3273],['4/21/2020', 20178, 645, 3976],['4/22/2020', 21797, 681, 4376],['4/23/2020', 23502, 722, 5012],['4/24/2020', 24530, 780, 5498],['4/25/2020', 26496, 825, 5939],['4/26/2020', 27977, 884, 6523],['4/27/2020', 29451, 939, 7137],['4/28/2020', 31360, 1008, 7747],['4/29/2020', 33062, 1079, 8437],['4/30/2020', 35043, 1154, 9068],['5/1/2020', 37371, 1238, 9943],['5/2/2020', 39980, 1323, 10819],['5/3/2020', 42670, 1395, 11782],['5/4/2020', 46476, 1571, 12849],['5/5/2020', 49436, 1695, 14183],['5/6/2020', 53045, 1787, 15331],['5/7/2020', 56409, 1890, 16790],['5/8/2020', 59765, 1986, 17897],['5/9/2020', 62939, 2109, 19358],['5/10/2020', 67259, 2212, 20969],['5/11/2020', 70827, 2294, 22549],['5/12/2020', 74243, 2415, 24420],
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
      ["India", 74243, 2415]
    ]);
    var options = {
      backgroundColor: {fill:'transparent',stroke:'#FFF' ,strokeWidth:0 }, 
      region: 'IN',
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



<span style="font-size: 13px">All COVID-19 data displayed on the page is available through our FREE <a href="https://developer.smartable.ai">API program</a>. This India Coronavirus (COVID-19) Live Stats is refreshed every hour using credible data sources, including the country/state's official government website, <a href="https://en.wikipedia.org/wiki/2019%E2%80%9320_coronavirus_pandemic" target="_blank">data available on wikipedia pages</a>, latest news reports, <a href="https://systems.jhu.edu/research/public-health/ncov/" target="_blank">Johns Hopkins University CSSE 2019-nCoV Dashboard</a>, <a href="https://www.who.int/emergencies/diseases/novel-coronavirus-2019/situation-reports" target="_blank">WHO Situation Reports</a>, <a href="https://www.cdc.gov/coronavirus/2019-ncov/index.html" target="_blank">CDC Situation Updates</a>, and <a href="https://ncov.dxy.cn/ncovh5/view/pneumonia" target="_blank">DXY.cn</a>.</span>


<h2 id="news" class="center" style="margin-top: 60px; font-size: 25px;">Trending Coronavirus News in India</h2>
<div class="row">
<div class="col-md-6 col-sm-12">
  <div class="content-card">
	<a href="https://www.reuters.com/article/us-health-coronavirus-india-idUSKBN22K0DK"><div class="card-image" style="background-image: url(https://s4.reutersmedia.net/resources_v3/images/rcom-default.png)"></div></a>
	<div class="content">
		<div class="card-title"><a href="https://www.reuters.com/article/us-health-coronavirus-india-idUSKBN22K0DK">India train crushes over migrant workers killing 14</a></div>
		<div class="card-excerpt">An Indian train ran over migrant workers sleeping on the track on Friday, killing at least 14 of the group, who were apparently on their way to their home villages, the railway ministry and media said.</div>
		<div class="card-meta">
			<span class="card-provider">Reuters</span> • <span class="card-date">5/7/2020</span>
		</div>
	</div>
  </div>
</div>
<div class="col-md-6 col-sm-12">
  <div class="content-card">
	<a href="https://www.nytimes.com/2020/05/07/briefing/coronavirus-president-trump-india-your-thursday-briefing.html"><div class="card-image" style="background-image: url(https://static01.nyt.com/images/2018/12/05/climate/07ambriefing-promo3/05CLI-COAL-facebookJumbo.jpg)"></div></a>
	<div class="content">
		<div class="card-title"><a href="https://www.nytimes.com/2020/05/07/briefing/coronavirus-president-trump-india-your-thursday-briefing.html">Coronavirus, President Trump, India: Your Thursday Briefing</a></div>
		<div class="card-excerpt">Shortly after taking office, President Trump and congressional Republicans found an innovative way to reduce business regulations, one of their top policy priorities. They began using a 1996 law — called the Congressional Review Act,</div>
		<div class="card-meta">
			<span class="card-provider">New York Times</span> • <span class="card-date">5/7/2020</span>
		</div>
	</div>
  </div>
</div>
<div class="col-md-6 col-sm-12">
  <div class="content-card">
	<a href="https://www.reuters.com/article/us-india-disaster-idUSKBN22J092"><div class="card-image" style="background-image: url(https://s2.reutersmedia.net/resources/r/?m=02&d=20200507&t=2&i=1517776583&w=&fh=545px&fw=&ll=&pl=&sq=&r=LYNXMPEG460NE)"></div></a>
	<div class="content">
		<div class="card-title"><a href="https://www.reuters.com/article/us-india-disaster-idUSKBN22J092">Gas leak at South Korea-owned factory in India kills nine, hundreds hospitalised</a></div>
		<div class="card-excerpt">At least 9 people were killed in southern India by a gas leak at a South Korean-owned factory making polystyrene products, with emergency services rushing over 300 people to hospitals and evacuating 1,</div>
		<div class="card-meta">
			<span class="card-provider">Reuters</span> • <span class="card-date">5/7/2020</span>
		</div>
	</div>
  </div>
</div>
<div class="col-md-6 col-sm-12">
  <div class="content-card">
	<a href="https://www.washingtonpost.com/world/asia_pacific/hundreds-sickened-in-india-and-7-dead-by-gas-leak-in-reopened-factory/2020/05/07/2fe3000e-902b-11ea-9322-a29e75effc93_story.html"><div class="card-image" style="background-image: url(https://www.washingtonpost.com/resizer/Rsj0FdRI9eldzKrUbczsg---2gU=/1440x0/smart/arc-anglerfish-washpost-prod-washpost.s3.amazonaws.com/public/JMPEKPUQGII6VKOAOO4TIIWWSE.jpg)"></div></a>
	<div class="content">
		<div class="card-title"><a href="https://www.washingtonpost.com/world/asia_pacific/hundreds-sickened-in-india-and-7-dead-by-gas-leak-in-reopened-factory/2020/05/07/2fe3000e-902b-11ea-9322-a29e75effc93_story.html">Hundreds sickened in India and 7 dead by gas leak in reopened factory</a></div>
		<div class="card-excerpt">A gas leak at a chemical plant in the port city of Visakhapatnam in southern India killed at least seven people and left over 200 hospitalized early Thursday, according to local authorities. Two of the dead are children under the age of 10.</div>
		<div class="card-meta">
			<span class="card-provider">Washington Post</span> • <span class="card-date">5/7/2020</span>
		</div>
	</div>
  </div>
</div>
<div class="col-md-6 col-sm-12">
  <div class="content-card">
	<a href="https://www.reuters.com/article/us-health-coronavirus-india-cases-idUSKBN22J0BN"><div class="card-image" style="background-image: url(https://s4.reutersmedia.net/resources/r/?m=02&d=20200507&t=2&i=1517746630&w=&fh=545px&fw=&ll=&pl=&sq=&r=LYNXMPEG4605W)"></div></a>
	<div class="content">
		<div class="card-title"><a href="https://www.reuters.com/article/us-health-coronavirus-india-cases-idUSKBN22J0BN">India now has 52,952 cases of coronavirus, death toll 1783: health ministry</a></div>
		<div class="card-excerpt">The number of coronavirus infections rose to 52,952 in India, up by 3,561 over the previous day, the health ministry said on Thursday, with no signs of abating despite a strict weeks-long lockdown in the world's second most populous country.</div>
		<div class="card-meta">
			<span class="card-provider">Reuters</span> • <span class="card-date">5/6/2020</span>
		</div>
	</div>
  </div>
</div>

</div>

