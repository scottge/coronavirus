---
category: stats
title: "US - Washington, D.C. Coronavirus (COVID-19) Live Stats"
excerpt: "Live stats of COVID-19 in US-Washington D.C.. Total Cases: 6485 (+96), Deaths: 336 (+8), Recoveries: 886(+5)."
publishedDateTime: 2020-05-12T18:45:13Z
updatedDateTime: 2020-05-12T18:45:13Z
webUrl: "https://smartable.ai/apps/coronavirus/stats/us-dc/"
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
  - Coronavirus in US

images:
  - url: "https://smartable.azureedge.net/coronavirus/sites/2/2020/us-dc.jpg"
    width: 900
    height: 564
    title: "US - Washington, D.C. Coronavirus (COVID-19) Live Stats"

---
<div class="total-stats" style="text-align: center;">
    <h3>
	    <div style="font-size: 18px; font-weight: 400;">Total Confirmed Cases:</div>
	    6485 (<span class='red'>+96</span>)
    </h3>
    <h3>
	    <div style="font-size: 18px; font-weight: 400;">Total Deaths:</div>
	    336 (<span class='red'>+8</span>)
    </h3>
    <h3>
	    <div style="font-size: 18px; font-weight: 400;">Total Recovered:</div>
	    886 (<span class='green'>+5</span>)
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
      ['1/22/2020', 0, 0, 0],['1/23/2020', 0, 0, 0],['1/24/2020', 0, 0, 0],['1/25/2020', 0, 0, 0],['1/26/2020', 0, 0, 0],['1/27/2020', 0, 0, 0],['1/28/2020', 0, 0, 0],['1/29/2020', 0, 0, 0],['1/30/2020', 0, 0, 0],['1/31/2020', 0, 0, 0],['2/1/2020', 0, 0, 0],['2/2/2020', 0, 0, 0],['2/3/2020', 0, 0, 0],['2/4/2020', 0, 0, 0],['2/5/2020', 0, 0, 0],['2/6/2020', 0, 0, 0],['2/7/2020', 0, 0, 0],['2/8/2020', 0, 0, 0],['2/9/2020', 0, 0, 0],['2/10/2020', 0, 0, 0],['2/11/2020', 0, 0, 0],['2/12/2020', 0, 0, 0],['2/13/2020', 0, 0, 0],['2/14/2020', 0, 0, 0],['2/15/2020', 0, 0, 0],['2/16/2020', 0, 0, 0],['2/17/2020', 0, 0, 0],['2/18/2020', 0, 0, 0],['2/19/2020', 0, 0, 0],['2/20/2020', 0, 0, 0],['2/21/2020', 0, 0, 0],['2/22/2020', 0, 0, 0],['2/23/2020', 0, 0, 0],['2/24/2020', 0, 0, 0],['2/25/2020', 0, 0, 0],['2/26/2020', 0, 0, 0],['2/27/2020', 0, 0, 0],['2/28/2020', 0, 0, 0],['2/29/2020', 0, 0, 0],['3/1/2020', 0, 0, 0],['3/2/2020', 0, 0, 0],['3/3/2020', 0, 0, 0],['3/4/2020', 0, 0, 0],['3/5/2020', 0, 0, 0],['3/6/2020', 0, 0, 0],['3/7/2020', 0, 0, 0],['3/8/2020', 2, 0, 0],['3/9/2020', 2, 0, 0],['3/10/2020', 4, 0, 0],['3/11/2020', 4, 0, 0],['3/12/2020', 10, 0, 0],['3/13/2020', 10, 0, 0],['3/14/2020', 16, 0, 0],['3/15/2020', 17, 0, 0],['3/16/2020', 22, 0, 0],['3/17/2020', 31, 0, 0],['3/18/2020', 40, 0, 0],['3/19/2020', 71, 0, 0],['3/20/2020', 77, 1, 0],['3/21/2020', 98, 1, 0],['3/22/2020', 120, 2, 0],['3/23/2020', 141, 2, 0],['3/24/2020', 187, 2, 0],['3/25/2020', 231, 3, 0],['3/26/2020', 267, 3, 0],['3/27/2020', 304, 4, 0],['3/28/2020', 342, 4, 0],['3/29/2020', 401, 9, 0],['3/30/2020', 495, 9, 66],['3/31/2020', 507, 9, 66],['4/1/2020', 586, 11, 121],['4/2/2020', 653, 12, 173],['4/3/2020', 757, 15, 173],['4/4/2020', 902, 21, 235],['4/5/2020', 1002, 22, 258],['4/6/2020', 1097, 24, 287],['4/7/2020', 1211, 22, 318],['4/8/2020', 1440, 27, 361],['4/9/2020', 1523, 32, 393],['4/10/2020', 1660, 38, 426],['4/11/2020', 1778, 47, 447],['4/12/2020', 1875, 50, 493],['4/13/2020', 1955, 52, 507],['4/14/2020', 2058, 67, 518],['4/15/2020', 2197, 72, 530],['4/16/2020', 2350, 81, 552],['4/17/2020', 2476, 86, 573],['4/18/2020', 2666, 91, 608],['4/19/2020', 2793, 96, 622],['4/20/2020', 2927, 105, 630],['4/21/2020', 3098, 112, 636],['4/22/2020', 3206, 127, 645],['4/23/2020', 3361, 139, 648],['4/24/2020', 3528, 153, 651],['4/25/2020', 3699, 165, 652],['4/26/2020', 3841, 178, 657],['4/27/2020', 3892, 185, 659],['4/28/2020', 3994, 190, 660],['4/29/2020', 4106, 205, 660],['4/30/2020', 4323, 224, 660],['5/1/2020', 4560, 232, 663],['5/2/2020', 4797, 240, 666],['5/3/2020', 5016, 251, 666],['5/4/2020', 5170, 258, 666],['5/5/2020', 5322, 264, 667],['5/6/2020', 5461, 277, 808],['5/7/2020', 5654, 285, 825],['5/8/2020', 5899, 304, 825],['5/9/2020', 6102, 311, 879],['5/10/2020', 6272, 323, 880],['5/11/2020', 6389, 328, 881],['5/12/2020', 6485, 336, 886],
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





<span style="font-size: 13px">All COVID-19 data displayed on the page is available through our FREE <a href="https://developer.smartable.ai">API program</a>. This US - Washington, D.C. Coronavirus (COVID-19) Live Stats is refreshed every hour using credible data sources, including the country/state's official government website, <a href="https://en.wikipedia.org/wiki/2019%E2%80%9320_coronavirus_pandemic" target="_blank">data available on wikipedia pages</a>, latest news reports, <a href="https://systems.jhu.edu/research/public-health/ncov/" target="_blank">Johns Hopkins University CSSE 2019-nCoV Dashboard</a>, <a href="https://www.who.int/emergencies/diseases/novel-coronavirus-2019/situation-reports" target="_blank">WHO Situation Reports</a>, <a href="https://www.cdc.gov/coronavirus/2019-ncov/index.html" target="_blank">CDC Situation Updates</a>, and <a href="https://ncov.dxy.cn/ncovh5/view/pneumonia" target="_blank">DXY.cn</a>.</span>

<h2 id="news" class="center" style="margin-top: 60px; font-size: 25px;">Local Government Help Information</h2>
<div class="info center">
<a href="https://coronavirus.dc.gov/" target="_blank">Coronavirus Information on DC.gov</a>
</div>
<h2 id="news" class="center" style="margin-top: 60px; font-size: 25px;">Trending Coronavirus News in US-Washington D.C.</h2>
<div class="row">
<div class="col-md-6 col-sm-12">
  <div class="content-card">
	<a href="https://www.nytimes.com/2020/05/07/us/coronavirus-updates-cases-deaths.html"><div class="card-image" style="background-image: url(https://www.nytimes.com/newsgraphics/2020/04/09/corona-virus-social-images-by-section/assets/US_promo.jpg?u=1588880289804)"></div></a>
	<div class="content">
		<div class="card-title"><a href="https://www.nytimes.com/2020/05/07/us/coronavirus-updates-cases-deaths.html">Coronavirus Live Updates: White House Blocks C.D.C. Guidance Over Economic and Religious Concerns</a></div>
		<div class="card-excerpt">Another 3.2 million people filed for unemployment benefits. A new study found that nearly everyone who gets the disease eventually makes antibodies to the virus. The governor of Texas said people would not be jailed for defiantly reopening businesses.</div>
		<div class="card-meta">
			<span class="card-provider">New York Times</span> • <span class="card-date">5/7/2020</span>
		</div>
	</div>
  </div>
</div>
<div class="col-md-6 col-sm-12">
  <div class="content-card">
	<a href="https://www.forbes.com/sites/andrewsolender/2020/05/06/trump-senators-eschew-masks-as-dc-coronavirus-cases-continue-to-rise/"><div class="card-image" style="background-image: url(https://thumbor.forbes.com/thumbor/fit-in/1200x0/filters%3Aformat%28jpg%29/https%3A%2F%2Fspecials-images.forbesimg.com%2Fimageserve%2F1211995037%2F0x0.jpg%3FcropX1%3D0%26cropX2%3D4857%26cropY1%3D0%26cropY2%3D2487)"></div></a>
	<div class="content">
		<div class="card-title"><a href="https://www.forbes.com/sites/andrewsolender/2020/05/06/trump-senators-eschew-masks-as-dc-coronavirus-cases-continue-to-rise/">Trump, Senators Eschew Masks As D.C. Coronavirus Cases Continue To Rise</a></div>
		<div class="card-excerpt">This comes days after Vice President Mike Pence apologized for not wearing a mask at a recent visit to the Mayo Clinic.</div>
		<div class="card-meta">
			<span class="card-provider">Forbes</span> • <span class="card-date">5/6/2020</span>
		</div>
	</div>
  </div>
</div>

</div>

