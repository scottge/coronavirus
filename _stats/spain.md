---
category: stats
title: "Spain Coronavirus (COVID-19) Live Stats"
excerpt: "Live stats of COVID-19 in Spain. Total Cases: 268143 (+3480), Deaths: 26744 (+123), Recoveries: 177846(+1407)."
publishedDateTime: 2020-05-12T00:45:10Z
updatedDateTime: 2020-05-12T00:45:10Z
webUrl: "https://smartable.ai/apps/coronavirus/stats/spain/"
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
  - url: "https://smartable.azureedge.net/coronavirus/sites/2/2020/spain.jpg"
    width: 900
    height: 564
    title: "Spain Coronavirus (COVID-19) Live Stats"

---
<div class="total-stats" style="text-align: center;">
    <h3>
	    <div style="font-size: 18px; font-weight: 400;">Total Confirmed Cases:</div>
	    268143 (<span class='red'>+3480</span>)
    </h3>
    <h3>
	    <div style="font-size: 18px; font-weight: 400;">Total Deaths:</div>
	    26744 (<span class='red'>+123</span>)
    </h3>
    <h3>
	    <div style="font-size: 18px; font-weight: 400;">Total Recovered:</div>
	    177846 (<span class='green'>+1407</span>)
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
      ['1/22/2020', 0, 0, 0],['1/23/2020', 0, 0, 0],['1/24/2020', 0, 0, 0],['1/25/2020', 0, 0, 0],['1/26/2020', 0, 0, 0],['1/27/2020', 0, 0, 0],['1/28/2020', 0, 0, 0],['1/29/2020', 0, 0, 0],['1/30/2020', 0, 0, 0],['1/31/2020', 0, 0, 0],['2/1/2020', 1, 0, 0],['2/2/2020', 1, 0, 0],['2/3/2020', 1, 0, 0],['2/4/2020', 1, 0, 0],['2/5/2020', 1, 0, 0],['2/6/2020', 1, 0, 0],['2/7/2020', 1, 0, 0],['2/8/2020', 1, 0, 0],['2/9/2020', 2, 0, 0],['2/10/2020', 2, 0, 0],['2/11/2020', 2, 0, 0],['2/12/2020', 2, 0, 0],['2/13/2020', 2, 0, 0],['2/14/2020', 2, 0, 0],['2/15/2020', 2, 0, 2],['2/16/2020', 2, 0, 2],['2/17/2020', 2, 0, 2],['2/18/2020', 2, 0, 2],['2/19/2020', 2, 0, 2],['2/20/2020', 2, 0, 2],['2/21/2020', 2, 0, 2],['2/22/2020', 2, 0, 2],['2/23/2020', 2, 0, 2],['2/24/2020', 2, 0, 2],['2/25/2020', 6, 0, 2],['2/26/2020', 13, 0, 2],['2/27/2020', 15, 0, 2],['2/28/2020', 32, 0, 2],['2/29/2020', 45, 0, 2],['3/1/2020', 84, 0, 2],['3/2/2020', 120, 0, 2],['3/3/2020', 165, 1, 2],['3/4/2020', 222, 2, 2],['3/5/2020', 259, 3, 2],['3/6/2020', 400, 5, 2],['3/7/2020', 500, 10, 30],['3/8/2020', 673, 17, 30],['3/9/2020', 1073, 28, 32],['3/10/2020', 1695, 35, 32],['3/11/2020', 2277, 54, 183],['3/12/2020', 3146, 86, 189],['3/13/2020', 5232, 133, 193],['3/14/2020', 6391, 196, 517],['3/15/2020', 7845, 292, 517],['3/16/2020', 9942, 342, 530],['3/17/2020', 11826, 533, 1028],['3/18/2020', 14769, 638, 1081],['3/19/2020', 18077, 833, 1107],['3/20/2020', 21571, 1093, 1588],['3/21/2020', 25496, 1381, 2125],['3/22/2020', 28768, 1772, 2575],['3/23/2020', 35136, 2311, 3355],['3/24/2020', 42058, 2991, 3794],['3/25/2020', 49515, 3647, 5367],['3/26/2020', 57786, 4365, 7015],['3/27/2020', 65719, 5138, 9357],['3/28/2020', 73235, 5982, 12285],['3/29/2020', 80110, 6803, 14709],['3/30/2020', 87956, 7716, 16780],['3/31/2020', 95923, 8464, 19259],['4/1/2020', 104118, 9387, 22647],['4/2/2020', 112065, 10348, 26743],['4/3/2020', 119199, 11198, 30513],['4/4/2020', 126168, 11947, 34219],['4/5/2020', 131646, 12641, 38080],['4/6/2020', 136675, 13341, 40437],['4/7/2020', 141942, 14045, 43208],['4/8/2020', 148220, 14792, 48021],['4/9/2020', 153222, 15447, 52165],['4/10/2020', 158273, 16081, 55668],['4/11/2020', 163027, 16606, 59109],['4/12/2020', 166831, 17209, 62391],['4/13/2020', 170099, 17756, 64727],['4/14/2020', 174060, 18255, 67504],['4/15/2020', 180659, 18812, 70853],['4/16/2020', 184948, 19315, 74797],['4/17/2020', 190839, 20002, 74797],['4/18/2020', 194416, 20639, 74797],['4/19/2020', 198674, 20639, 77357],['4/20/2020', 200210, 20852, 80587],['4/21/2020', 204178, 21282, 82514],['4/22/2020', 208389, 21717, 85915],['4/23/2020', 213024, 22157, 89250],['4/24/2020', 219764, 22524, 92355],['4/25/2020', 223759, 22902, 95708],['4/26/2020', 226629, 23190, 117727],['4/27/2020', 229422, 23521, 120832],['4/28/2020', 232128, 23822, 123903],['4/29/2020', 236899, 24275, 132929],['4/30/2020', 239639, 24543, 137984],['5/1/2020', 242603, 24821, 142108],['5/2/2020', 245567, 25100, 146233],['5/3/2020', 247122, 25264, 148558],['5/4/2020', 248301, 25428, 151633],['5/5/2020', 250561, 25613, 154718],['5/6/2020', 253682, 25857, 159359],['5/7/2020', 256855, 26070, 163919],['5/8/2020', 260117, 26299, 168408],['5/9/2020', 262783, 26478, 173157],['5/10/2020', 264663, 26621, 176439],['5/11/2020', 268143, 26744, 177846],
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
      ["Spain", 268143, 26744]
    ]);
    var options = {
      backgroundColor: {fill:'transparent',stroke:'#FFF' ,strokeWidth:0 }, 
      region: 'ES',
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



<span style="font-size: 13px">All COVID-19 data displayed on the page is available through our FREE <a href="https://developer.smartable.ai">API program</a>. This Spain Coronavirus (COVID-19) Live Stats is refreshed every hour using credible data sources, including the country/state's official government website, <a href="https://en.wikipedia.org/wiki/2019%E2%80%9320_coronavirus_pandemic" target="_blank">data available on wikipedia pages</a>, latest news reports, <a href="https://systems.jhu.edu/research/public-health/ncov/" target="_blank">Johns Hopkins University CSSE 2019-nCoV Dashboard</a>, <a href="https://www.who.int/emergencies/diseases/novel-coronavirus-2019/situation-reports" target="_blank">WHO Situation Reports</a>, <a href="https://www.cdc.gov/coronavirus/2019-ncov/index.html" target="_blank">CDC Situation Updates</a>, and <a href="https://ncov.dxy.cn/ncovh5/view/pneumonia" target="_blank">DXY.cn</a>.</span>


<h2 id="news" class="center" style="margin-top: 60px; font-size: 25px;">Trending Coronavirus News in Spain</h2>
<div class="row">
<div class="col-md-6 col-sm-12">
  <div class="content-card">
	<a href="https://www.theguardian.com/politics/2020/may/09/poll-shows-people-think-uk-handled-coronavirus-worse-than-italy-spain"><div class="card-image" style="background-image: url(https://i.guim.co.uk/img/media/cab69bab69587412a0ce2762f15ad2fe4d149728/0_0_6192_3715/master/6192.jpg?width=300&quality=45&auto=format&fit=max&dpr=2&s=c5dcb01f51c212272f1aeb6fdb11fe0c)"></div></a>
	<div class="content">
		<div class="card-title"><a href="https://www.theguardian.com/politics/2020/may/09/poll-shows-people-think-uk-handled-coronavirus-worse-than-italy-spain">More people think UK has handled coronavirus worse than Spain and Italy, poll shows</a></div>
		<div class="card-excerpt">Only US is judged to have dealt with it worse, after it was reported the UK has the highest death toll of any country in Europe</div>
		<div class="card-meta">
			<span class="card-provider">The Guardian</span> • <span class="card-date">5/9/2020</span>
		</div>
	</div>
  </div>
</div>
<div class="col-md-6 col-sm-12">
  <div class="content-card">
	<a href="https://www.ft.com/content/2ac243b2-657f-481d-ac38-8b4254b797d3"><div class="card-image" style="background-image: url(https://www.ft.com/__origami/service/image/v2/images/raw/https%3A%2F%2Fd1e00ek4ebabms.cloudfront.net%2Fproduction%2F4cddba02-2314-42ed-b52c-2f7286e42147.jpg?source=google-amp&fit=scale-down&width=500)"></div></a>
	<div class="content">
		<div class="card-title"><a href="https://www.ft.com/content/2ac243b2-657f-481d-ac38-8b4254b797d3">Spain to begin limited loosening of coronavirus lockdown</a></div>
		<div class="card-excerpt">Pedro Sánchez has pleaded with Spain’s citizens to take maximum precautions when the country’s harsh coronavirus lockdown is relaxed on Monday, as political and economic tensions increase over his government’s plans to loosen controls.</div>
		<div class="card-meta">
			<span class="card-provider">The Financial Times</span> • <span class="card-date">5/9/2020</span>
		</div>
	</div>
  </div>
</div>
<div class="col-md-6 col-sm-12">
  <div class="content-card">
	<a href="https://www.nytimes.com/reuters/2020/05/09/world/europe/09reuters-health-coronavirus-spain.html"><div class="card-image" style="background-image: url(https://static01.nyt.com/newsgraphics/images/icons/defaultPromoCrop.png)"></div></a>
	<div class="content">
		<div class="card-title"><a href="https://www.nytimes.com/reuters/2020/05/09/world/europe/09reuters-health-coronavirus-spain.html">Spain's Coronavirus Daily Death Tolls Falls to 179 on Saturday</a></div>
		<div class="card-excerpt">Spain's daily death toll from the coronavirus fell to 179 on Saturday, down from 229 on the previous day, the health ministry reported.</div>
		<div class="card-meta">
			<span class="card-provider">New York Times</span> • <span class="card-date">5/9/2020</span>
		</div>
	</div>
  </div>
</div>
<div class="col-md-6 col-sm-12">
  <div class="content-card">
	<a href="https://www.cnbc.com/2020/05/09/coronavirus-live-updates-us-lawmakers-urge-support-for-taiwans-who-bid.html"><div class="card-image" style="background-image: url(https://image.cnbcfm.com/api/v1/image/106529511-1589005300082gettyimages-1211709360.jpeg?v=1589005489)"></div></a>
	<div class="content">
		<div class="card-title"><a href="https://www.cnbc.com/2020/05/09/coronavirus-live-updates-us-lawmakers-urge-support-for-taiwans-who-bid.html">Coronavirus live updates: China offers North Korea help; Russia's Victory Day celebrations pared back</a></div>
		<div class="card-excerpt">Russia marks the 75th anniversary of Soviet victory over Nazi Germany in World War Two on Saturday, but the coronavirus outbreak means that celebrations have been pared back massively.</div>
		<div class="card-meta">
			<span class="card-provider">CNBC</span> • <span class="card-date">5/9/2020</span>
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
	<a href="https://www.reuters.com/article/us-health-coronavirus-spain-idUSKBN22J1C6"><div class="card-image" style="background-image: url(https://s2.reutersmedia.net/resources/r/?m=02&d=20200507&t=2&i=1517780165&w=&fh=545px&fw=&ll=&pl=&sq=&r=LYNXMPEG460QB)"></div></a>
	<div class="content">
		<div class="card-title"><a href="https://www.reuters.com/article/us-health-coronavirus-spain-idUSKBN22J1C6">Spain's daily coronavirus death toll falls again on Thursday: health ministry</a></div>
		<div class="card-excerpt">Spain's coronavirus daily death toll fell on Thursday to 213 down from 244 the day before, the health ministry reported.</div>
		<div class="card-meta">
			<span class="card-provider">Reuters</span> • <span class="card-date">5/7/2020</span>
		</div>
	</div>
  </div>
</div>
<div class="col-md-6 col-sm-12">
  <div class="content-card">
	<a href="https://www.reuters.com/article/health-coronavirus-soccer-spain-women-idUSL4N2CO34B"><div class="card-image" style="background-image: url(https://s4.reutersmedia.net/resources_v3/images/rcom-default.png)"></div></a>
	<div class="content">
		<div class="card-title"><a href="https://www.reuters.com/article/health-coronavirus-soccer-spain-women-idUSL4N2CO34B">Soccer-Spain to end women's soccer season due to COVID-19 pandemic</a></div>
		<div class="card-excerpt">Spain's women's soccer season is on the verge of being cut short due to the COVID-19 pandemic, with champions in each tier being declared based on the standings before the campaign was halted, the country's football federation (RFEF) has said.</div>
		<div class="card-meta">
			<span class="card-provider">Reuters</span> • <span class="card-date">5/6/2020</span>
		</div>
	</div>
  </div>
</div>

</div>

