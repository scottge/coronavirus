---
category: stats
title: "Singapore Coronavirus (COVID-19) Live Stats"
excerpt: "Live stats of COVID-19 in Singapore. Total Cases: 23822 (+486), Deaths: 21 (+1), Recoveries: 3225(+504)."
publishedDateTime: 2020-05-12T04:45:11Z
updatedDateTime: 2020-05-12T04:45:11Z
webUrl: "https://smartable.ai/apps/coronavirus/stats/singapore/"
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
  - Coronavirus in Asia

images:
  - url: "https://smartable.azureedge.net/coronavirus/sites/2/2020/singapore.jpg"
    width: 900
    height: 564
    title: "Singapore Coronavirus (COVID-19) Live Stats"

---
<div class="total-stats" style="text-align: center;">
    <h3>
	    <div style="font-size: 18px; font-weight: 400;">Total Confirmed Cases:</div>
	    23822 (<span class='red'>+486</span>)
    </h3>
    <h3>
	    <div style="font-size: 18px; font-weight: 400;">Total Deaths:</div>
	    21 (<span class='red'>+1</span>)
    </h3>
    <h3>
	    <div style="font-size: 18px; font-weight: 400;">Total Recovered:</div>
	    3225 (<span class='green'>+504</span>)
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
      ['1/22/2020', 0, 0, 0],['1/23/2020', 1, 0, 0],['1/24/2020', 3, 0, 0],['1/25/2020', 3, 0, 0],['1/26/2020', 4, 0, 0],['1/27/2020', 5, 0, 0],['1/28/2020', 7, 0, 0],['1/29/2020', 7, 0, 0],['1/30/2020', 10, 0, 0],['1/31/2020', 13, 0, 0],['2/1/2020', 16, 0, 0],['2/2/2020', 18, 0, 0],['2/3/2020', 18, 0, 0],['2/4/2020', 24, 0, 0],['2/5/2020', 28, 0, 0],['2/6/2020', 28, 0, 0],['2/7/2020', 30, 0, 0],['2/8/2020', 33, 0, 2],['2/9/2020', 40, 0, 2],['2/10/2020', 45, 0, 2],['2/11/2020', 47, 0, 9],['2/12/2020', 50, 0, 15],['2/13/2020', 58, 0, 15],['2/14/2020', 67, 0, 17],['2/15/2020', 72, 0, 18],['2/16/2020', 75, 0, 18],['2/17/2020', 77, 0, 24],['2/18/2020', 81, 0, 29],['2/19/2020', 84, 0, 34],['2/20/2020', 84, 0, 34],['2/21/2020', 85, 0, 37],['2/22/2020', 85, 0, 37],['2/23/2020', 89, 0, 51],['2/24/2020', 89, 0, 51],['2/25/2020', 91, 0, 53],['2/26/2020', 93, 0, 62],['2/27/2020', 93, 0, 62],['2/28/2020', 93, 0, 62],['2/29/2020', 102, 0, 72],['3/1/2020', 106, 0, 72],['3/2/2020', 108, 0, 78],['3/3/2020', 110, 0, 78],['3/4/2020', 110, 0, 78],['3/5/2020', 117, 0, 78],['3/6/2020', 130, 0, 78],['3/7/2020', 138, 0, 78],['3/8/2020', 150, 0, 78],['3/9/2020', 150, 0, 78],['3/10/2020', 160, 0, 78],['3/11/2020', 178, 0, 96],['3/12/2020', 187, 0, 96],['3/13/2020', 200, 0, 97],['3/14/2020', 212, 0, 105],['3/15/2020', 226, 0, 105],['3/16/2020', 243, 0, 109],['3/17/2020', 266, 0, 114],['3/18/2020', 313, 0, 117],['3/19/2020', 345, 0, 124],['3/20/2020', 385, 2, 131],['3/21/2020', 432, 2, 140],['3/22/2020', 455, 2, 144],['3/23/2020', 509, 2, 152],['3/24/2020', 558, 2, 156],['3/25/2020', 631, 2, 160],['3/26/2020', 683, 2, 172],['3/27/2020', 732, 2, 183],['3/28/2020', 802, 3, 198],['3/29/2020', 844, 3, 212],['3/30/2020', 879, 3, 228],['3/31/2020', 926, 3, 240],['4/1/2020', 1000, 4, 245],['4/2/2020', 1049, 5, 266],['4/3/2020', 1114, 5, 282],['4/4/2020', 1189, 6, 297],['4/5/2020', 1309, 6, 320],['4/6/2020', 1375, 6, 344],['4/7/2020', 1481, 6, 377],['4/8/2020', 1623, 6, 406],['4/9/2020', 1910, 7, 460],['4/10/2020', 2108, 7, 492],['4/11/2020', 2299, 8, 528],['4/12/2020', 2532, 8, 560],['4/13/2020', 2918, 9, 586],['4/14/2020', 3252, 10, 611],['4/15/2020', 3699, 10, 652],['4/16/2020', 4427, 10, 683],['4/17/2020', 5050, 11, 708],['4/18/2020', 5992, 11, 740],['4/19/2020', 6588, 11, 768],['4/20/2020', 8014, 11, 801],['4/21/2020', 9125, 11, 839],['4/22/2020', 10141, 12, 896],['4/23/2020', 11178, 12, 924],['4/24/2020', 12075, 12, 956],['4/25/2020', 13624, 12, 1002],['4/26/2020', 13624, 12, 1060],['4/27/2020', 14423, 14, 1095],['4/28/2020', 14951, 14, 1128],['4/29/2020', 15641, 14, 1188],['4/30/2020', 16169, 15, 1244],['5/1/2020', 16858, 16, 1295],['5/2/2020', 17548, 17, 1347],['5/3/2020', 18205, 18, 1408],['5/4/2020', 18778, 18, 1457],['5/5/2020', 19410, 18, 1519],['5/6/2020', 20198, 20, 1634],['5/7/2020', 20939, 20, 1712],['5/8/2020', 21707, 20, 2040],['5/9/2020', 22460, 20, 2296],['5/10/2020', 23336, 20, 2721],['5/11/2020', 23822, 21, 3225],
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
      ["Singapore", 23822, 21]
    ]);
    var options = {
      backgroundColor: {fill:'transparent',stroke:'#FFF' ,strokeWidth:0 }, 
      region: 'SG',
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



<span style="font-size: 13px">All COVID-19 data displayed on the page is available through our FREE <a href="https://developer.smartable.ai">API program</a>. This Singapore Coronavirus (COVID-19) Live Stats is refreshed every hour using credible data sources, including the country/state's official government website, <a href="https://en.wikipedia.org/wiki/2019%E2%80%9320_coronavirus_pandemic" target="_blank">data available on wikipedia pages</a>, latest news reports, <a href="https://systems.jhu.edu/research/public-health/ncov/" target="_blank">Johns Hopkins University CSSE 2019-nCoV Dashboard</a>, <a href="https://www.who.int/emergencies/diseases/novel-coronavirus-2019/situation-reports" target="_blank">WHO Situation Reports</a>, <a href="https://www.cdc.gov/coronavirus/2019-ncov/index.html" target="_blank">CDC Situation Updates</a>, and <a href="https://ncov.dxy.cn/ncovh5/view/pneumonia" target="_blank">DXY.cn</a>.</span>


<h2 id="news" class="center" style="margin-top: 60px; font-size: 25px;">Trending Coronavirus News in Singapore</h2>
<div class="row">
<div class="col-md-6 col-sm-12">
  <div class="content-card">
	<a href="https://www.nytimes.com/reuters/2020/05/09/world/asia/09reuters-health-coronavirus-singapore.html"><div class="card-image" style="background-image: url(https://static01.nyt.com/newsgraphics/images/icons/defaultPromoCrop.png)"></div></a>
	<div class="content">
		<div class="card-title"><a href="https://www.nytimes.com/reuters/2020/05/09/world/asia/09reuters-health-coronavirus-singapore.html">Singapore Reports 753 New Coronavirus Cases, Taking Total to 22,460</a></div>
		<div class="card-excerpt">Singapore registered 753 new coronavirus infections, its health ministry said on Saturday, taking the city-state's total to 22,460 cases.</div>
		<div class="card-meta">
			<span class="card-provider">New York Times</span> • <span class="card-date">5/9/2020</span>
		</div>
	</div>
  </div>
</div>
<div class="col-md-6 col-sm-12">
  <div class="content-card">
	<a href="https://www.newindianexpress.com/world/2020/may/09/singapore-coronavirus-infections-touch-21707-with-20-deaths-health-ministry-2140989.html"><div class="card-image" style="background-image: url(https://images.newindianexpress.com/uploads/user/imagelibrary/2020/5/6/w600X390/000_1QH6CK.jpg)"></div></a>
	<div class="content">
		<div class="card-title"><a href="https://www.newindianexpress.com/world/2020/may/09/singapore-coronavirus-infections-touch-21707-with-20-deaths-health-ministry-2140989.html">Singapore coronavirus infections touch 21,707 with 20 deaths: Health Ministry</a></div>
		<div class="card-excerpt">The Ministry of Health (MoH) said the foreign workers living in dormitories form the bulk of the cases of the new 768 new infections.</div>
		<div class="card-meta">
			<span class="card-provider">The New Indian Express</span> • <span class="card-date">5/8/2020</span>
		</div>
	</div>
  </div>
</div>
<div class="col-md-6 col-sm-12">
  <div class="content-card">
	<a href="https://www.cnn.com/2020/05/08/tech/singapore-coronavirus-social-distancing-robot-intl-hnk/index.html"><div class="card-image" style="background-image: url(https://cdn.cnn.com/cnnnext/dam/assets/200508144808-spot-singapore-govtech-super-tease.jpeg)"></div></a>
	<div class="content">
		<div class="card-title"><a href="https://www.cnn.com/2020/05/08/tech/singapore-coronavirus-social-distancing-robot-intl-hnk/index.html">Singapore deploys robot 'dog' to encourage social distancing</a></div>
		<div class="card-excerpt">The four-legged robot "dog" will patrol the area starting this weekend and broadcast a pre-recorded message to visitors to remind them of the importance of social distancing, authorities said. The device will also be equipped with cameras that will scan the surroundings and help officials estimate the number of people gathering in parks,</div>
		<div class="card-meta">
			<span class="card-provider">CNN</span> • <span class="card-date">5/8/2020</span>
		</div>
	</div>
  </div>
</div>
<div class="col-md-6 col-sm-12">
  <div class="content-card">
	<a href="https://www.reuters.com/article/us-health-coronavirus-singapore-idUSKBN22K0UU"><div class="card-image" style="background-image: url(https://s3.reutersmedia.net/resources/r/?m=02&d=20200508&t=2&i=1517911874&w=&fh=545px&fw=&ll=&pl=&sq=&r=LYNXMPEG470GK)"></div></a>
	<div class="content">
		<div class="card-title"><a href="https://www.reuters.com/article/us-health-coronavirus-singapore-idUSKBN22K0UU">Singapore records 768 new COVID-19 cases, total now 21,707</a></div>
		<div class="card-excerpt">Singapore recorded 768 new coronavirus cases on Friday, its health ministry said, taking the city-state's tally to 21,707.</div>
		<div class="card-meta">
			<span class="card-provider">Reuters</span> • <span class="card-date">5/8/2020</span>
		</div>
	</div>
  </div>
</div>
<div class="col-md-6 col-sm-12">
  <div class="content-card">
	<a href="https://www.reuters.com/article/us-ocbc-results-idUSKBN22J3MI"><div class="card-image" style="background-image: url(https://s4.reutersmedia.net/resources_v3/images/rcom-default.png)"></div></a>
	<div class="content">
		<div class="card-title"><a href="https://www.reuters.com/article/us-ocbc-results-idUSKBN22J3MI">Singapore lender OCBC's first-quarter profit slumps 43% on coronavirus charges</a></div>
		<div class="card-excerpt">Oversea-Chinese Banking Corp reported a 43% fall in first-quarter net profit, worse than market estimates, as Singapore's second-largest lender set aside higher credit allowances to cover the impact of the coronavirus pandemic.</div>
		<div class="card-meta">
			<span class="card-provider">Reuters</span> • <span class="card-date">5/7/2020</span>
		</div>
	</div>
  </div>
</div>
<div class="col-md-6 col-sm-12">
  <div class="content-card">
	<a href="https://www.reuters.com/article/us-health-coronavirus-singapore-idUSKBN22J0UO"><div class="card-image" style="background-image: url(https://s2.reutersmedia.net/resources/r/?m=02&d=20200507&t=2&i=1517764387&w=&fh=545px&fw=&ll=&pl=&sq=&r=LYNXMPEG460FC)"></div></a>
	<div class="content">
		<div class="card-title"><a href="https://www.reuters.com/article/us-health-coronavirus-singapore-idUSKBN22J0UO">Singapore reports 741 new coronavirus cases, taking total to 20,939</a></div>
		<div class="card-excerpt">Singapore has registered 741 new coronavirus infections, its health ministry said on Thursday, taking the city-state's total number of COVID-19 cases to 20,939.</div>
		<div class="card-meta">
			<span class="card-provider">Reuters</span> • <span class="card-date">5/7/2020</span>
		</div>
	</div>
  </div>
</div>
<div class="col-md-6 col-sm-12">
  <div class="content-card">
	<a href="https://www.zdnet.com/article/singapore-scrapes-fraudulent-covid-19-healthcare-products-from-online-stores/"><div class="card-image" style="background-image: url(https://zdnet4.cbsistatic.com/hub/i/r/2016/02/22/e4a9fab1-0023-465b-8a12-250f05e47a88/thumbnail/1200x675/a4d848327d28808fd777ede97292dfce/5g-connectivity.jpg)"></div></a>
	<div class="content">
		<div class="card-title"><a href="https://www.zdnet.com/article/singapore-scrapes-fraudulent-covid-19-healthcare-products-from-online-stores/">Singapore scrapes fraudulent COVID-19 healthcare products from online stores</a></div>
		<div class="card-excerpt">Since February, more than 1,700 product listings that contain fraudulent COVID-19 claims have been removed from local e-commerce sites and retail shops.</div>
		<div class="card-meta">
			<span class="card-provider">ZDNet</span> • <span class="card-date">5/6/2020</span>
		</div>
	</div>
  </div>
</div>
<div class="col-md-6 col-sm-12">
  <div class="content-card">
	<a href="https://www.reuters.com/article/us-health-coronavirus-singapore-idUSKBN22I0SG"><div class="card-image" style="background-image: url(https://s3.reutersmedia.net/resources/r/?m=02&d=20200506&t=2&i=1517622084&w=&fh=545px&fw=&ll=&pl=&sq=&r=LYNXMPEG450FO)"></div></a>
	<div class="content">
		<div class="card-title"><a href="https://www.reuters.com/article/us-health-coronavirus-singapore-idUSKBN22I0SG">Singapore's health ministry confirms 788 new coronavirus cases</a></div>
		<div class="card-excerpt">Singapore's health ministry on Wednesday confirmed 788 new coronavirus cases, taking the city-state's tally to 20,198.</div>
		<div class="card-meta">
			<span class="card-provider">Reuters</span> • <span class="card-date">5/6/2020</span>
		</div>
	</div>
  </div>
</div>
<div class="col-md-6 col-sm-12">
  <div class="content-card">
	<a href="https://www.cnbc.com/2020/05/06/coronavirus-singapore-is-not-halfway-through-outbreak-says-minister.html"><div class="card-image" style="background-image: url(https://image.cnbcfm.com/api/v1/image/106486812-1586821456671gettyimages-1209215531.jpeg?v=1588738000)"></div></a>
	<div class="content">
		<div class="card-title"><a href="https://www.cnbc.com/2020/05/06/coronavirus-singapore-is-not-halfway-through-outbreak-says-minister.html">Singapore is not yet halfway through its coronavirus outbreak, says minister</a></div>
		<div class="card-excerpt">Migrant workers living dormitories have accounted for around 87.6% of Singapore's total 19,410 confirmed cases as of Tuesday, according to the health ministry.</div>
		<div class="card-meta">
			<span class="card-provider">CNBC</span> • <span class="card-date">5/5/2020</span>
		</div>
	</div>
  </div>
</div>
<div class="col-md-6 col-sm-12">
  <div class="content-card">
	<a href="https://www.reuters.com/article/southeast-asia-stocks-idUSL4N2CO0GB"><div class="card-image" style="background-image: url(https://s4.reutersmedia.net/resources_v3/images/rcom-default.png)"></div></a>
	<div class="content">
		<div class="card-title"><a href="https://www.reuters.com/article/southeast-asia-stocks-idUSL4N2CO0GB">SE Asia Stocks-Singapore gains; Philippines falls on profit-taking, poor exports</a></div>
		<div class="card-excerpt">Singapore shares gained the most in Southeast Asia on Wednesday, supported by the industrial sector, while Philippine stocks dropped more than 1% on profit-taking and dismal exports data. Financial markets around the world have been caught this month between grim economic figures and worries about worsening U.</div>
		<div class="card-meta">
			<span class="card-provider">Reuters</span> • <span class="card-date">5/5/2020</span>
		</div>
	</div>
  </div>
</div>

</div>

