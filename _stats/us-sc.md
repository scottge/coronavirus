---
category: stats
title: "US - South Carolina State Coronavirus (COVID-19) Live Stats"
excerpt: "Live stats of COVID-19 in US-South Carolina. Total Cases: 7533 (+163), Deaths: 330 (+10), Recoveries: 4881(-)."
publishedDateTime: 2020-05-10T05:45:41Z
updatedDateTime: 2020-05-10T05:45:41Z
webUrl: "https://smartable.ai/apps/coronavirus/stats/us-sc/"
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
  - url: "https://smartable.azureedge.net/coronavirus/sites/2/2020/us-sc.jpg"
    width: 900
    height: 564
    title: "US - South Carolina State Coronavirus (COVID-19) Live Stats"

---
<div class="total-stats" style="text-align: center;">
    <h3>
	    <div style="font-size: 18px; font-weight: 400;">Total Confirmed Cases:</div>
	    7533 (<span class='red'>+163</span>)
    </h3>
    <h3>
	    <div style="font-size: 18px; font-weight: 400;">Total Deaths:</div>
	    330 (<span class='red'>+10</span>)
    </h3>
    <h3>
	    <div style="font-size: 18px; font-weight: 400;">Total Recovered:</div>
	    4881 (-)
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
      ['1/22/2020', 0, 0, 0],['1/23/2020', 0, 0, 0],['1/24/2020', 0, 0, 0],['1/25/2020', 0, 0, 0],['1/26/2020', 0, 0, 0],['1/27/2020', 0, 0, 0],['1/28/2020', 0, 0, 0],['1/29/2020', 0, 0, 0],['1/30/2020', 0, 0, 0],['1/31/2020', 0, 0, 0],['2/1/2020', 0, 0, 0],['2/2/2020', 0, 0, 0],['2/3/2020', 0, 0, 0],['2/4/2020', 0, 0, 0],['2/5/2020', 0, 0, 0],['2/6/2020', 0, 0, 0],['2/7/2020', 0, 0, 0],['2/8/2020', 0, 0, 0],['2/9/2020', 0, 0, 0],['2/10/2020', 0, 0, 0],['2/11/2020', 0, 0, 0],['2/12/2020', 0, 0, 0],['2/13/2020', 0, 0, 0],['2/14/2020', 0, 0, 0],['2/15/2020', 0, 0, 0],['2/16/2020', 0, 0, 0],['2/17/2020', 0, 0, 0],['2/18/2020', 0, 0, 0],['2/19/2020', 0, 0, 0],['2/20/2020', 0, 0, 0],['2/21/2020', 0, 0, 0],['2/22/2020', 0, 0, 0],['2/23/2020', 0, 0, 0],['2/24/2020', 0, 0, 0],['2/25/2020', 0, 0, 0],['2/26/2020', 0, 0, 0],['2/27/2020', 0, 0, 0],['2/28/2020', 0, 0, 0],['2/29/2020', 0, 0, 0],['3/1/2020', 0, 0, 0],['3/2/2020', 0, 0, 0],['3/3/2020', 0, 0, 0],['3/4/2020', 0, 0, 0],['3/5/2020', 0, 0, 0],['3/6/2020', 0, 0, 0],['3/7/2020', 2, 0, 0],['3/8/2020', 2, 0, 0],['3/9/2020', 3, 0, 0],['3/10/2020', 3, 0, 0],['3/11/2020', 6, 0, 0],['3/12/2020', 7, 0, 0],['3/13/2020', 8, 0, 0],['3/14/2020', 19, 0, 0],['3/15/2020', 28, 0, 0],['3/16/2020', 33, 1, 0],['3/17/2020', 50, 1, 0],['3/18/2020', 61, 1, 0],['3/19/2020', 79, 1, 0],['3/20/2020', 126, 3, 0],['3/21/2020', 174, 3, 0],['3/22/2020', 197, 4, 0],['3/23/2020', 300, 5, 0],['3/24/2020', 343, 7, 0],['3/25/2020', 425, 7, 0],['3/26/2020', 457, 9, 0],['3/27/2020', 543, 13, 0],['3/28/2020', 662, 15, 0],['3/29/2020', 775, 16, 0],['3/30/2020', 926, 18, 0],['3/31/2020', 1084, 22, 0],['4/1/2020', 1294, 26, 0],['4/2/2020', 1554, 31, 0],['4/3/2020', 1700, 34, 0],['4/4/2020', 1917, 40, 0],['4/5/2020', 2049, 44, 0],['4/6/2020', 2232, 48, 0],['4/7/2020', 2417, 51, 0],['4/8/2020', 2552, 63, 0],['4/9/2020', 2793, 67, 0],['4/10/2020', 3067, 72, 0],['4/11/2020', 3211, 80, 0],['4/12/2020', 3314, 82, 0],['4/13/2020', 3439, 87, 0],['4/14/2020', 3553, 97, 0],['4/15/2020', 3656, 106, 0],['4/16/2020', 3918, 109, 0],['4/17/2020', 4086, 116, 0],['4/18/2020', 4248, 119, 0],['4/19/2020', 4377, 120, 0],['4/20/2020', 4439, 124, 0],['4/21/2020', 4608, 135, 0],['4/22/2020', 4761, 140, 0],['4/23/2020', 4917, 150, 0],['4/24/2020', 5071, 158, 0],['4/25/2020', 5255, 166, 3701],['4/26/2020', 5498, 174, 3701],['4/27/2020', 5626, 177, 3701],['4/28/2020', 5744, 192, 3701],['4/29/2020', 5890, 232, 3701],['4/30/2020', 6096, 244, 3701],['5/1/2020', 6284, 252, 4291],['5/2/2020', 6490, 267, 4881],['5/3/2020', 6627, 275, 4881],['5/4/2020', 6762, 283, 4881],['5/5/2020', 6853, 296, 4881],['5/6/2020', 6944, 305, 4881],['5/7/2020', 7145, 316, 4881],['5/8/2020', 7370, 320, 4881],['5/9/2020', 7533, 330, 4881],
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
      ['LATITUDE', 'LONGITUDE', 'DESCRIPTION', 'Total Cases', 'Total Deaths'],
      [34.3766, -82.3467, "Abbeville", 34, 0],[33.8497, -81.6097, "Aiken", 116, 6],[34.6433, -82.4588, "Anderson", 184, 8],[32.4599, -80.7869, "Beaufort", 273, 12],[32.9922, -80.0052, "Berkeley", 192, 15],[33.5579, -80.715, "Calhoun", 8, 1],[32.7957, -79.7848, "Charleston", 482, 10],[34.5753, -80.9048, "Chester", 39, 0],[34.7697, -80.2264, "Chesterfield", 75, 1],[33.6013, -80.3527, "Clarendon", 262, 26],[32.7718, -80.477, "Colleton", 33, 4],[34.401, -80.071, "Darlington", 173, 3],[34.3406, -79.1663, "Dillon", 88, 0],[33.186, -80.5794, "Dorchester", 105, 3],[33.7401, -81.8404, "Edgefield", 39, 2],[34.3718, -81.0907, "Fairfield", 80, 4],[33.8149, -79.4444, "Florence", 412, 20],[33.5567, -79.0591, "Georgetown", 50, 3],[34.8821, -82.3336, "Greenville", 912, 45],[34.1696, -82.024, "Greenwood", 62, 0],[32.6812, -81.1877, "Hampton", 27, 0],[33.6092, -78.9772, "Horry", 256, 18],[32.4681, -80.9178, "Jasper", 23, 1],[34.3672, -80.5883, "Kershaw", 253, 12],[34.7253, -80.6771, "Lancaster", 104, 4],[34.4912, -82.2957, "Laurens", 46, 2],[34.2202, -80.2483, "Lee", 99, 8],[33.9458, -81.0433, "Lexington", 472, 21],[34.2823, -79.4723, "Marion", 47, 2],[34.6438, -79.5867, "Marlboro", 57, 1],[34.2681, -81.4196, "Newberry", 32, 1],[34.7704, -83.0615, "Oconee", 37, 0],[33.5301, -80.5712, "Orangeburg", 99, 2],[34.819, -82.5828, "Pickens", 68, 1],[34.0324, -80.9717, "Richland", 1082, 54],[33.8573, -81.7313, "Saluda", 86, 0],[34.8606, -81.9535, "Spartanburg", 336, 12],[33.9753, -80.5264, "Sumter", 286, 12],[34.7922, -81.4614, "Union", 30, 0],[33.6665, -79.8293, "Williamsburg", 136, 6],[34.952, -81.3436, "York", 237, 5],[33.2419, -81.3659, "Barnwell", 33, 0],[33.0985, -81.0138, "Bamberg", 15, 0],[32.9593, -81.2363, "Allendale", 24, 3],[35.0742, -81.6558, "Cherokee", 22, 0],[33.7192, -82.2173, "McCormick", 7, 1],
    ]);
    var options = {
      backgroundColor: {fill:'transparent',stroke:'#FFF' ,strokeWidth:0 }, 
      displayMode: 'markers',
      region: 'US-SC', 
      resolution: 'metros',
      colorAxis: {colors: ['#F27D81', '#f60109']},
      sizeAxis: {minSize:3,  maxSize:12},
    };
    var chart = new google.visualization.GeoChart(document.getElementById('geo_chart'));
    chart.draw(data, options);
  };
</script>

<div id="geo_table"></div>
<script type="text/javascript">
  google.charts.load('current', {'packages':['table']});
  google.charts.setOnLoadCallback(drawTable);
  function drawTable() {
    var data = new google.visualization.DataTable();
    data.addColumn('string', 'Location');
    data.addColumn('number', 'Total Cases');
    data.addColumn('number', 'New Cases');
    data.addColumn('number', 'Active Cases');
    data.addColumn('number', 'Total Deaths');
    data.addColumn('number', 'New Deaths');
    data.addColumn('number', 'Total Recovered');
    data.addRows([
      [{v:"Abbeville", f:"Abbeville"}, 34, 0, 34, 0, 0, 0],[{v:"Aiken", f:"Aiken"}, 116, 4, 110, 6, 0, 0],[{v:"Anderson", f:"Anderson"}, 184, 2, 176, 8, 0, 0],[{v:"Beaufort", f:"Beaufort"}, 273, 0, 261, 12, 0, 0],[{v:"Berkeley", f:"Berkeley"}, 192, 1, 177, 15, 1, 0],[{v:"Calhoun", f:"Calhoun"}, 8, 1, 7, 1, 0, 0],[{v:"Charleston", f:"Charleston"}, 482, 1, 472, 10, 1, 0],[{v:"Chester", f:"Chester"}, 39, 0, 39, 0, 0, 0],[{v:"Chesterfield", f:"Chesterfield"}, 75, 3, 74, 1, 0, 0],[{v:"Clarendon", f:"Clarendon"}, 262, 4, 236, 26, 1, 0],[{v:"Colleton", f:"Colleton"}, 33, 0, 29, 4, 0, 0],[{v:"Darlington", f:"Darlington"}, 173, 2, 170, 3, 0, 0],[{v:"Dillon", f:"Dillon"}, 88, 4, 88, 0, 0, 0],[{v:"Dorchester", f:"Dorchester"}, 105, 0, 102, 3, 0, 0],[{v:"Edgefield", f:"Edgefield"}, 39, 3, 37, 2, 0, 0],[{v:"Fairfield", f:"Fairfield"}, 80, 4, 76, 4, 1, 0],[{v:"Florence", f:"Florence"}, 412, 13, 392, 20, 0, 0],[{v:"Georgetown", f:"Georgetown"}, 50, 0, 47, 3, 0, 0],[{v:"Greenville", f:"Greenville"}, 912, 43, 867, 45, 1, 0],[{v:"Greenwood", f:"Greenwood"}, 62, 0, 62, 0, 0, 0],[{v:"Hampton", f:"Hampton"}, 27, 0, 27, 0, 0, 0],[{v:"Horry", f:"Horry"}, 256, 5, 238, 18, 0, 0],[{v:"Jasper", f:"Jasper"}, 23, 2, 22, 1, 0, 0],[{v:"Kershaw", f:"Kershaw"}, 253, 3, 241, 12, 0, 0],[{v:"Lancaster", f:"Lancaster"}, 104, 1, 100, 4, 0, 0],[{v:"Laurens", f:"Laurens"}, 46, 0, 44, 2, 0, 0],[{v:"Lee", f:"Lee"}, 99, 7, 91, 8, 0, 0],[{v:"Lexington", f:"Lexington"}, 472, 7, 451, 21, 2, 0],[{v:"Marion", f:"Marion"}, 47, 3, 45, 2, 0, 0],[{v:"Marlboro", f:"Marlboro"}, 57, 0, 56, 1, 0, 0],[{v:"Newberry", f:"Newberry"}, 32, 0, 31, 1, 0, 0],[{v:"Oconee", f:"Oconee"}, 37, 1, 37, 0, 0, 0],[{v:"Orangeburg", f:"Orangeburg"}, 99, 0, 97, 2, 0, 0],[{v:"Pickens", f:"Pickens"}, 68, 5, 67, 1, 0, 0],[{v:"Richland", f:"Richland"}, 1082, 25, 1028, 54, 2, 0],[{v:"Saluda", f:"Saluda"}, 86, 2, 86, 0, 0, 0],[{v:"Spartanburg", f:"Spartanburg"}, 336, 3, 324, 12, 0, 0],[{v:"Sumter", f:"Sumter"}, 286, 5, 274, 12, 0, 0],[{v:"Union", f:"Union"}, 30, 1, 30, 0, 0, 0],[{v:"Williamsburg", f:"Williamsburg"}, 136, 0, 130, 6, 0, 0],[{v:"York", f:"York"}, 237, 4, 232, 5, 0, 0],[{v:"Barnwell", f:"Barnwell"}, 33, 1, 33, 0, 0, 0],[{v:"Bamberg", f:"Bamberg"}, 15, 1, 15, 0, 0, 0],[{v:"Allendale", f:"Allendale"}, 24, 1, 21, 3, 0, 0],[{v:"Cherokee", f:"Cherokee"}, 22, 1, 22, 0, 0, 0],[{v:"McCormick", f:"McCormick"}, 7, 0, 6, 1, 0, 0],
    ]);
    data.setProperty(0, 0, 'style', 'min-width:100px');
    var table = new google.visualization.Table(document.getElementById('geo_table'));
    table.draw(data, {allowHtml: true, sortColumn: 2, sortAscending: false, width: '660px', height: '100%'});
  }
</script>

<span style="font-size: 13px">All COVID-19 data displayed on the page is available through our FREE <a href="https://developer.smartable.ai">API program</a>. This US - South Carolina State Coronavirus (COVID-19) Live Stats is refreshed every hour using credible data sources, including the country/state's official government website, <a href="https://en.wikipedia.org/wiki/2019%E2%80%9320_coronavirus_pandemic" target="_blank">data available on wikipedia pages</a>, latest news reports, <a href="https://systems.jhu.edu/research/public-health/ncov/" target="_blank">Johns Hopkins University CSSE 2019-nCoV Dashboard</a>, <a href="https://www.who.int/emergencies/diseases/novel-coronavirus-2019/situation-reports" target="_blank">WHO Situation Reports</a>, <a href="https://www.cdc.gov/coronavirus/2019-ncov/index.html" target="_blank">CDC Situation Updates</a>, and <a href="https://ncov.dxy.cn/ncovh5/view/pneumonia" target="_blank">DXY.cn</a>.</span>

<h2 id="news" class="center" style="margin-top: 60px; font-size: 25px;">Local Government Help Information</h2>
<div class="info center">
<a href="https://www.scdhec.gov/health/infectious-diseases/viruses/coronavirus-disease-2019-covid-19" target="_blank">South Carolina Department of Health and Environmental</a> 855-472-3432
</div>
<h2 id="news" class="center" style="margin-top: 60px; font-size: 25px;">Trending Coronavirus News in US-South Carolina</h2>
<div class="row">
<div class="col-md-6 col-sm-12">
  <div class="content-card">
	<a href="https://www.upi.com/News_Photos/view/upi/a01c0429493082fa35af960e0b28f58b/Beaches-Open-in-South-Carolina-After-Coronavirus-Closure/"><div class="card-image" style="background-image: url(https://cdnph.upi.com/pv/upi/a01c0429493082fa35af960e0b28f58b/BEACHES-CHARLESTON.jpg)"></div></a>
	<div class="content">
		<div class="card-title"><a href="https://www.upi.com/News_Photos/view/upi/a01c0429493082fa35af960e0b28f58b/Beaches-Open-in-South-Carolina-After-Coronavirus-Closure/">Beaches Open in South Carolina After Coronavirus Closure</a></div>
		<div class="card-excerpt">Crowds of people enjoy the beach after the the city relaxed restrictions to prevent the spread of COVID-19, coronavirus, re-opening for the first time since March on Wednesday, May 6, 2020, in Isle of Palms,</div>
		<div class="card-meta">
			<span class="card-provider">UPI.com</span> • <span class="card-date">5/6/2020</span>
		</div>
	</div>
  </div>
</div>
<div class="col-md-6 col-sm-12">
  <div class="content-card">
	<a href="https://www.wjbf.com/news/south-carolina-news/south-carolina-dhec-to-test-all-staff-and-residents-at-nursing-homes-across-the-state-for-covid-19/"><div class="card-image" style="background-image: url(https://www.wjbf.com/wp-content/uploads/sites/47/2016/01/sc_36101647_ver1.0.png?w=1280&h=720&crop=1)"></div></a>
	<div class="content">
		<div class="card-title"><a href="https://www.wjbf.com/news/south-carolina-news/south-carolina-dhec-to-test-all-staff-and-residents-at-nursing-homes-across-the-state-for-covid-19/">South Carolina DHEC to test all staff and residents at nursing homes across the state for COVID-19</a></div>
		<div class="card-excerpt">South Carolina DHEC announced Wednesday all residents and staff members of every nursing home in South Carolina will be tested for COVID-19. “Many of us have</div>
		<div class="card-meta">
			<span class="card-provider">WJBF</span> • <span class="card-date">5/6/2020</span>
		</div>
	</div>
  </div>
</div>
<div class="col-md-6 col-sm-12">
  <div class="content-card">
	<a href="https://www.nbcnews.com/health/health-news/live-blog/2020-05-04-coronavirus-news-n1199156/ncrd1199186"><div class="card-image" style="background-image: url(https://media4.s-nbcnews.com/j/newscms/2020_19/3335361/screen_shot_2020-05-04_at_12-03-42_8dd03578ad9bfad9d06316a400c46f2d.fit-560w.png)"></div></a>
	<div class="content">
		<div class="card-title"><a href="https://www.nbcnews.com/health/health-news/live-blog/2020-05-04-coronavirus-news-n1199156/ncrd1199186">South Carolina woman charged on two counts after licking incident at grocery store</a></div>
		<div class="card-excerpt">A woman suspected of picking up goods in grocery stores after licking her hands has been arrested in Sumter, South Carolina.</div>
		<div class="card-meta">
			<span class="card-provider">NBC News</span> • <span class="card-date">5/4/2020</span>
		</div>
	</div>
  </div>
</div>
<div class="col-md-6 col-sm-12">
  <div class="content-card">
	<a href="https://apnews.com/985d545cd6a77ab067c2dcbd19c9f604"><div class="card-image" style="background-image: url(https://apnews.com/images/ShareLogo2.png)"></div></a>
	<div class="content">
		<div class="card-title"><a href="https://apnews.com/985d545cd6a77ab067c2dcbd19c9f604">South Carolina parks fill up as virus death toll climbs</a></div>
		<div class="card-excerpt">Several state parks in South Carolina quickly reached capacity Sunday on the first weekend they were open after a lengthy closure because of the coronavirus. Jones</div>
		<div class="card-meta">
			<span class="card-provider">Associated Press</span> • <span class="card-date">5/3/2020</span>
		</div>
	</div>
  </div>
</div>

</div>

