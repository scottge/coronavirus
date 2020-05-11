---
category: stats
title: "Canada - British Columbia Coronavirus (COVID-19) Live Stats"
excerpt: "Live stats of COVID-19 in Canada-British Columbia. Total Cases: 2353 (+23), Deaths: 130 (+1), Recoveries: 0(-)."
publishedDateTime: 2020-05-11T22:45:10Z
updatedDateTime: 2020-05-11T22:45:10Z
webUrl: "https://smartable.ai/apps/coronavirus/stats/canada-bc/"
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
  - Coronavirus in Canada

images:
  - url: "https://smartable.azureedge.net/coronavirus/sites/2/2020/canada-bc.jpg"
    width: 900
    height: 564
    title: "Canada - British Columbia Coronavirus (COVID-19) Live Stats"

---
<div class="total-stats" style="text-align: center;">
    <h3>
	    <div style="font-size: 18px; font-weight: 400;">Total Confirmed Cases:</div>
	    2353 (<span class='red'>+23</span>)
    </h3>
    <h3>
	    <div style="font-size: 18px; font-weight: 400;">Total Deaths:</div>
	    130 (<span class='red'>+1</span>)
    </h3>
    <h3>
	    <div style="font-size: 18px; font-weight: 400;">Total Recovered:</div>
	    0 (-)
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
      ['1/22/2020', 0, 0, 0],['1/23/2020', 0, 0, 0],['1/24/2020', 0, 0, 0],['1/25/2020', 0, 0, 0],['1/26/2020', 0, 0, 0],['1/27/2020', 0, 0, 0],['1/28/2020', 1, 0, 0],['1/29/2020', 1, 0, 0],['1/30/2020', 1, 0, 0],['1/31/2020', 1, 0, 0],['2/1/2020', 1, 0, 0],['2/2/2020', 1, 0, 0],['2/3/2020', 1, 0, 0],['2/4/2020', 1, 0, 0],['2/5/2020', 2, 0, 0],['2/6/2020', 2, 0, 0],['2/7/2020', 4, 0, 0],['2/8/2020', 4, 0, 0],['2/9/2020', 4, 0, 0],['2/10/2020', 4, 0, 0],['2/11/2020', 4, 0, 0],['2/12/2020', 4, 0, 0],['2/13/2020', 4, 0, 0],['2/14/2020', 4, 0, 0],['2/15/2020', 4, 0, 0],['2/16/2020', 4, 0, 0],['2/17/2020', 5, 0, 0],['2/18/2020', 5, 0, 0],['2/19/2020', 5, 0, 0],['2/20/2020', 5, 0, 0],['2/21/2020', 6, 0, 0],['2/22/2020', 6, 0, 0],['2/23/2020', 6, 0, 0],['2/24/2020', 6, 0, 0],['2/25/2020', 7, 0, 0],['2/26/2020', 7, 0, 0],['2/27/2020', 7, 0, 3],['2/28/2020', 7, 0, 3],['2/29/2020', 8, 0, 3],['3/1/2020', 8, 0, 3],['3/2/2020', 8, 0, 3],['3/3/2020', 9, 0, 3],['3/4/2020', 12, 0, 3],['3/5/2020', 13, 0, 3],['3/6/2020', 21, 0, 3],['3/7/2020', 21, 0, 4],['3/8/2020', 27, 0, 4],['3/9/2020', 32, 1, 4],['3/10/2020', 32, 1, 4],['3/11/2020', 39, 1, 4],['3/12/2020', 46, 1, 4],['3/13/2020', 64, 1, 4],['3/14/2020', 73, 1, 4],['3/15/2020', 73, 1, 4],['3/16/2020', 103, 4, 4],['3/17/2020', 186, 7, 4],['3/18/2020', 231, 7, 4],['3/19/2020', 271, 8, 4],['3/20/2020', 348, 8, 4],['3/21/2020', 424, 10, 4],['3/22/2020', 424, 10, 4],['3/23/2020', 472, 13, 4],['3/24/2020', 617, 13, 4],['3/25/2020', 617, 14, 4],['3/26/2020', 725, 14, 4],['3/27/2020', 725, 16, 0],['3/28/2020', 884, 17, 0],['3/29/2020', 884, 17, 0],['3/30/2020', 970, 19, 0],['3/31/2020', 1013, 24, 0],['4/1/2020', 1013, 24, 0],['4/2/2020', 1121, 31, 0],['4/3/2020', 1174, 31, 0],['4/4/2020', 1203, 38, 0],['4/5/2020', 1203, 38, 0],['4/6/2020', 1266, 38, 0],['4/7/2020', 1266, 39, 0],['4/8/2020', 1291, 43, 0],['4/9/2020', 1336, 48, 0],['4/10/2020', 1410, 55, 0],['4/11/2020', 1445, 58, 0],['4/12/2020', 1445, 58, 0],['4/13/2020', 1490, 69, 0],['4/14/2020', 1517, 72, 0],['4/15/2020', 1561, 75, 0],['4/16/2020', 1589, 79, 0],['4/17/2020', 1618, 79, 0],['4/18/2020', 1647, 81, 0],['4/19/2020', 1647, 81, 0],['4/20/2020', 1699, 86, 0],['4/21/2020', 1724, 87, 0],['4/22/2020', 1795, 93, 0],['4/23/2020', 1824, 94, 0],['4/24/2020', 1824, 94, 0],['4/25/2020', 1948, 100, 0],['4/26/2020', 1948, 100, 0],['4/27/2020', 1998, 104, 0],['4/28/2020', 2053, 106, 0],['4/29/2020', 2087, 109, 0],['4/30/2020', 2112, 111, 0],['5/1/2020', 2141, 112, 0],['5/2/2020', 2171, 114, 0],['5/3/2020', 2171, 114, 0],['5/4/2020', 2224, 120, 0],['5/5/2020', 2232, 121, 0],['5/6/2020', 2255, 124, 0],['5/7/2020', 2288, 126, 0],['5/8/2020', 2315, 127, 0],['5/9/2020', 2330, 129, 0],['5/10/2020', 2330, 129, 0],['5/11/2020', 2353, 130, 0],
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





<span style="font-size: 13px">All COVID-19 data displayed on the page is available through our FREE <a href="https://developer.smartable.ai">API program</a>. This Canada - British Columbia Coronavirus (COVID-19) Live Stats is refreshed every hour using credible data sources, including the country/state's official government website, <a href="https://en.wikipedia.org/wiki/2019%E2%80%9320_coronavirus_pandemic" target="_blank">data available on wikipedia pages</a>, latest news reports, <a href="https://systems.jhu.edu/research/public-health/ncov/" target="_blank">Johns Hopkins University CSSE 2019-nCoV Dashboard</a>, <a href="https://www.who.int/emergencies/diseases/novel-coronavirus-2019/situation-reports" target="_blank">WHO Situation Reports</a>, <a href="https://www.cdc.gov/coronavirus/2019-ncov/index.html" target="_blank">CDC Situation Updates</a>, and <a href="https://ncov.dxy.cn/ncovh5/view/pneumonia" target="_blank">DXY.cn</a>.</span>


<h2 id="news" class="center" style="margin-top: 60px; font-size: 25px;">Trending Coronavirus News in Canada-British Columbia</h2>
<div class="row">
<div class="col-md-6 col-sm-12">
  <div class="content-card">
	<a href="https://www.reuters.com/article/us-health-coronavirus-canada-idUSKBN22I2C2"><div class="card-image" style="background-image: url(https://s3.reutersmedia.net/resources/r/?m=02&d=20200506&t=2&i=1517677509&w=&fh=545px&fw=&ll=&pl=&sq=&r=LYNXMPEG451H7)"></div></a>
	<div class="content">
		<div class="card-title"><a href="https://www.reuters.com/article/us-health-coronavirus-canada-idUSKBN22I2C2">Canada's British Columbia the latest province to unveil restart plan</a></div>
		<div class="card-excerpt">The Canadian province of British Columbia will begin reopening its economy as early as mid-May, the premier said on Wednesday, as new coronavirus cases dwindle and other parts of the country, including Quebec and Manitoba,</div>
		<div class="card-meta">
			<span class="card-provider">Reuters</span> • <span class="card-date">5/6/2020</span>
		</div>
	</div>
  </div>
</div>
<div class="col-md-6 col-sm-12">
  <div class="content-card">
	<a href="https://www.washingtontimes.com/news/2020/may/6/the-latest-german-soccer-could-be-cleared-to-resum/"><div class="card-image" style="background-image: url(https://twt-thumbs.washtimes.com/media/image/2020/04/20/virus_outbreak_sports_poll_10233_c0-140-3359-2099_s1200x700.jpg?c9ed18d226ea968fb467046bcea6f29c38ba16e5)"></div></a>
	<div class="content">
		<div class="card-title"><a href="https://www.washingtontimes.com/news/2020/may/6/the-latest-german-soccer-could-be-cleared-to-resum/">The Latest: NHL offered place to play in British Columbia</a></div>
		<div class="card-excerpt">British Columbia Premier John Horgan has offered the NHL a place to play if the league can find a way to resume the season. TOP STORIES Texas governor demands release of salon owner jailed for violating his executive order Coronavirus hype biggest political hoax in history Donald Trump Jr.</div>
		<div class="card-meta">
			<span class="card-provider">Washington Times</span> • <span class="card-date">5/6/2020</span>
		</div>
	</div>
  </div>
</div>

</div>

