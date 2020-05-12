---
category: stats
title: "US Coronavirus (COVID-19) Live Stats"
excerpt: "Live stats of COVID-19 in US. Total Cases: 1376229 (-), Deaths: 81535 (-), Recoveries: 252193(-)."
publishedDateTime: 2020-05-12T08:45:09Z
updatedDateTime: 2020-05-12T08:45:09Z
webUrl: "https://smartable.ai/apps/coronavirus/stats/us/"
type: article
heat: 900

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
  - url: "https://smartable.azureedge.net/coronavirus/sites/2/2020/us.jpg"
    width: 900
    height: 564
    title: "US Coronavirus (COVID-19) Live Stats"

---
<div class="total-stats" style="text-align: center;">
    <h3>
	    <div style="font-size: 18px; font-weight: 400;">Total Confirmed Cases:</div>
	    1376229 (-)
    </h3>
    <h3>
	    <div style="font-size: 18px; font-weight: 400;">Total Deaths:</div>
	    81535 (-)
    </h3>
    <h3>
	    <div style="font-size: 18px; font-weight: 400;">Total Recovered:</div>
	    252193 (-)
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
      ['1/22/2020', 1, 0, 0],['1/23/2020', 1, 0, 0],['1/24/2020', 2, 0, 0],['1/25/2020', 2, 0, 0],['1/26/2020', 5, 0, 0],['1/27/2020', 5, 0, 0],['1/28/2020', 5, 0, 0],['1/29/2020', 5, 0, 0],['1/30/2020', 5, 0, 0],['1/31/2020', 7, 0, 0],['2/1/2020', 8, 0, 0],['2/2/2020', 8, 0, 0],['2/3/2020', 11, 0, 0],['2/4/2020', 11, 0, 0],['2/5/2020', 11, 0, 0],['2/6/2020', 11, 0, 0],['2/7/2020', 11, 0, 0],['2/8/2020', 11, 0, 0],['2/9/2020', 11, 0, 3],['2/10/2020', 11, 0, 3],['2/11/2020', 12, 0, 3],['2/12/2020', 12, 0, 3],['2/13/2020', 13, 0, 3],['2/14/2020', 13, 0, 3],['2/15/2020', 13, 0, 3],['2/16/2020', 13, 0, 3],['2/17/2020', 13, 0, 3],['2/18/2020', 13, 0, 3],['2/19/2020', 13, 0, 3],['2/20/2020', 13, 0, 3],['2/21/2020', 15, 0, 5],['2/22/2020', 15, 0, 5],['2/23/2020', 15, 0, 5],['2/24/2020', 51, 0, 5],['2/25/2020', 51, 0, 6],['2/26/2020', 57, 0, 6],['2/27/2020', 58, 0, 6],['2/28/2020', 60, 0, 7],['2/29/2020', 68, 1, 7],['3/1/2020', 74, 1, 7],['3/2/2020', 98, 6, 7],['3/3/2020', 118, 7, 7],['3/4/2020', 149, 11, 7],['3/5/2020', 217, 12, 7],['3/6/2020', 262, 14, 7],['3/7/2020', 402, 17, 7],['3/8/2020', 518, 21, 7],['3/9/2020', 583, 22, 7],['3/10/2020', 768, 28, 7],['3/11/2020', 1165, 32, 11],['3/12/2020', 1758, 41, 12],['3/13/2020', 2354, 50, 13],['3/14/2020', 3068, 60, 16],['3/15/2020', 3773, 69, 17],['3/16/2020', 4760, 92, 17],['3/17/2020', 6579, 114, 18],['3/18/2020', 9385, 147, 108],['3/19/2020', 14298, 208, 108],['3/20/2020', 19853, 270, 147],['3/21/2020', 26880, 345, 147],['3/22/2020', 35171, 470, 178],['3/23/2020', 46343, 583, 179],['3/24/2020', 55095, 798, 181],['3/25/2020', 69007, 1050, 303],['3/26/2020', 85947, 1297, 303],['3/27/2020', 104518, 1712, 302],['3/28/2020', 124285, 2186, 302],['3/29/2020', 156449, 3026, 809],['3/30/2020', 175674, 3616, 1182],['3/31/2020', 198298, 4446, 1182],['4/1/2020', 231159, 5655, 9163],['4/2/2020', 260025, 6565, 9639],['4/3/2020', 291998, 7658, 10231],['4/4/2020', 326023, 8990, 15461],['4/5/2020', 351842, 10144, 17991],['4/6/2020', 382157, 11481, 20269],['4/7/2020', 413259, 13380, 22699],['4/8/2020', 445523, 15280, 24247],['4/9/2020', 479633, 17144, 26270],['4/10/2020', 515558, 19258, 28820],['4/11/2020', 543839, 21083, 31305],['4/12/2020', 571269, 22579, 40755],['4/13/2020', 596325, 24105, 42597],['4/14/2020', 625192, 26537, 48186],['4/15/2020', 654411, 28950, 50605],['4/16/2020', 686640, 31206, 53452],['4/17/2020', 722123, 37593, 56444],['4/18/2020', 750284, 39603, 62973],['4/19/2020', 774985, 41173, 68179],['4/20/2020', 802871, 42928, 70051],['4/21/2020', 829231, 45490, 73056],['4/22/2020', 857382, 48066, 75521],['4/23/2020', 891855, 50469, 79419],['4/24/2020', 922630, 52626, 95892],['4/25/2020', 960905, 54549, 120798],['4/26/2020', 987385, 55611, 121414],['4/27/2020', 1010116, 57051, 141126],['4/28/2020', 1034937, 59286, 144114],['4/29/2020', 1062258, 61763, 149133],['4/30/2020', 1091918, 63817, 157459],['5/1/2020', 1122366, 65415, 165445],['5/2/2020', 1155469, 67326, 173518],['5/3/2020', 1182766, 68661, 178402],['5/4/2020', 1207029, 69996, 186956],['5/5/2020', 1230649, 71938, 193112],['5/6/2020', 1255747, 74407, 205023],['5/7/2020', 1284704, 76526, 208570],['5/8/2020', 1312991, 78178, 214564],['5/9/2020', 1337621, 79660, 228549],['5/10/2020', 1358460, 80441, 246732],['5/11/2020', 1376229, 81535, 252193],['5/12/2020', 1376229, 81535, 252193],
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
      ["Guam", 32, 1],["Puerto Rico", 1307, 83],["U.S. Virgin Islands", 17, 0],["Alabama", 10164, 406],["Alaska", 381, 10],["Arizona", 11383, 542],["Arkansas", 4043, 94],["California", 69386, 2812],["Colorado", 19879, 987],["Connecticut", 33765, 3008],["Cruise Ship: Diamond Princess", 46, 0],["Cruise Ship: Grand Princess", 21, 0],["Delaware", 6565, 225],["District of Columbia", 6389, 328],["Florida", 40982, 1738],["Georgia", 34002, 1444],["Hawaii", 634, 17],["Idaho", 2263, 70],["Illinois", 79007, 3463],["Indiana", 24924, 1540],["Iowa", 12382, 271],["Kansas", 7242, 181],["Kentucky", 6709, 312],["Louisiana", 31815, 2308],["Maine", 1462, 65],["Maryland", 33373, 1683],["Massachusetts", 78462, 5108],["Michigan", 47552, 4584],["Minnesota", 11800, 591],["Mississippi", 9686, 438],["Missouri", 10149, 507],["Montana", 464, 16],["Nebraska", 8572, 104],["Nevada", 6172, 312],["New Hampshire", 3160, 134],["New Jersey", 141137, 9341],["New Mexico", 5490, 211],["New York", 347151, 27225],["North Carolina", 15357, 575],["North Dakota", 1518, 36],["Northern Mariana Islands", 14, 2],["Ohio", 24787, 1362],["Oklahoma", 4620, 274],["Oregon", 3286, 130],["Pennsylvania", 60576, 3845],["Rhode Island", 11450, 430],["South Carolina", 7842, 346],["South Dakota", 3618, 35],["Tennessee", 15773, 264],["Texas", 40855, 1153],["Utah", 6574, 71],["Vermont", 927, 54],["Virginia", 25070, 850],["Washington", 18029, 953],["West Virginia", 1377, 57],["Wisconsin", 10421, 409],["Wyoming", 672, 7],["Veteran Affairs", 6692, 413],["US Military", 6213, 26],["Navajo Nation", 1540, 58],["Federal Prisons", 1047, 26],["Wuhan Repatriated", 3, 0],
    ]);
    var options = {
      backgroundColor: {fill:'transparent',stroke:'#FFF' ,strokeWidth:0 }, 
      region: 'US', 
      resolution: 'provinces',
      colorAxis: {
          colors: ['#ED9CA1', '#f60109', '#7A0109']
      }
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
      [{v:"Guam", f:"Guam"}, 32, 0, 31, 1, 0, 0],[{v:"Puerto Rico", f:"Puerto Rico"}, 1307, 0, 833, 83, 0, 391],[{v:"U.S. Virgin Islands", f:"U.S. Virgin Islands"}, 17, 0, 17, 0, 0, 0],[{v:"Alabama", f:"<a href='https://smartable.ai/apps/coronavirus/stats/us-al/'>Alabama</a>"}, 10164, 0, 9738, 406, 0, 20],[{v:"Alaska", f:"Alaska"}, 381, 0, 43, 10, 0, 328],[{v:"Arizona", f:"<a href='https://smartable.ai/apps/coronavirus/stats/us-az/'>Arizona</a>"}, 11383, 0, 10771, 542, 0, 70],[{v:"Arkansas", f:"Arkansas"}, 4043, 0, 800, 94, 0, 3149],[{v:"California", f:"<a href='https://smartable.ai/apps/coronavirus/stats/us-ca/'>California</a>"}, 69386, 0, 55446, 2812, 0, 11128],[{v:"Colorado", f:"<a href='https://smartable.ai/apps/coronavirus/stats/us-co/'>Colorado</a>"}, 19879, 0, 18280, 987, 0, 612],[{v:"Connecticut", f:"<a href='https://smartable.ai/apps/coronavirus/stats/us-ct/'>Connecticut</a>"}, 33765, 0, 30692, 3008, 0, 65],[{v:"Cruise Ship: Diamond Princess", f:"Cruise Ship: Diamond Princess"}, 46, 0, 46, 0, 0, 0],[{v:"Cruise Ship: Grand Princess", f:"Cruise Ship: Grand Princess"}, 21, 0, 21, 0, 0, 0],[{v:"Delaware", f:"Delaware"}, 6565, 0, 3721, 225, 0, 2619],[{v:"District of Columbia", f:"<a href='https://smartable.ai/apps/coronavirus/stats/us-dc/'>District of Columbia</a>"}, 6389, 0, 5180, 328, 0, 881],[{v:"Florida", f:"<a href='https://smartable.ai/apps/coronavirus/stats/us-fl/'>Florida</a>"}, 40982, 0, 38198, 1738, 0, 1046],[{v:"Georgia", f:"<a href='https://smartable.ai/apps/coronavirus/stats/us-ga/'>Georgia</a>"}, 34002, 0, 32218, 1444, 0, 340],[{v:"Hawaii", f:"<a href='https://smartable.ai/apps/coronavirus/stats/us-hi/'>Hawaii</a>"}, 634, 0, 56, 17, 0, 561],[{v:"Idaho", f:"Idaho"}, 2263, 0, 814, 70, 0, 1379],[{v:"Illinois", f:"<a href='https://smartable.ai/apps/coronavirus/stats/us-il/'>Illinois</a>"}, 79007, 0, 74899, 3463, 0, 645],[{v:"Indiana", f:"<a href='https://smartable.ai/apps/coronavirus/stats/us-in/'>Indiana</a>"}, 24924, 0, 21693, 1540, 0, 1691],[{v:"Iowa", f:"<a href='https://smartable.ai/apps/coronavirus/stats/us-ia/'>Iowa</a>"}, 12382, 0, 6862, 271, 0, 5249],[{v:"Kansas", f:"<a href='https://smartable.ai/apps/coronavirus/stats/us-ks/'>Kansas</a>"}, 7242, 0, 5386, 181, 0, 1675],[{v:"Kentucky", f:"<a href='https://smartable.ai/apps/coronavirus/stats/us-ky/'>Kentucky</a>"}, 6709, 0, 4062, 312, 0, 2335],[{v:"Louisiana", f:"<a href='https://smartable.ai/apps/coronavirus/stats/us-la/'>Louisiana</a>"}, 31815, 0, 9191, 2308, 0, 20316],[{v:"Maine", f:"Maine"}, 1462, 0, 525, 65, 0, 872],[{v:"Maryland", f:"<a href='https://smartable.ai/apps/coronavirus/stats/us-md/'>Maryland</a>"}, 33373, 0, 29392, 1683, 0, 2298],[{v:"Massachusetts", f:"<a href='https://smartable.ai/apps/coronavirus/stats/us-ma/'>Massachusetts</a>"}, 78462, 0, 51206, 5108, 0, 22148],[{v:"Michigan", f:"<a href='https://smartable.ai/apps/coronavirus/stats/us-mi/'>Michigan</a>"}, 47552, 0, 20282, 4584, 0, 22686],[{v:"Minnesota", f:"<a href='https://smartable.ai/apps/coronavirus/stats/us-mn/'>Minnesota</a>"}, 11800, 0, 3673, 591, 0, 7536],[{v:"Mississippi", f:"Mississippi"}, 9686, 0, 4827, 438, 0, 4421],[{v:"Missouri", f:"<a href='https://smartable.ai/apps/coronavirus/stats/us-mo/'>Missouri</a>"}, 10149, 0, 7113, 507, 0, 2529],[{v:"Montana", f:"Montana"}, 464, 0, 25, 16, 0, 423],[{v:"Nebraska", f:"<a href='https://smartable.ai/apps/coronavirus/stats/us-ne/'>Nebraska</a>"}, 8572, 0, 8446, 104, 0, 22],[{v:"Nevada", f:"<a href='https://smartable.ai/apps/coronavirus/stats/us-nv/'>Nevada</a>"}, 6172, 0, 1663, 312, 0, 4197],[{v:"New Hampshire", f:"<a href='https://smartable.ai/apps/coronavirus/stats/us-nh/'>New Hampshire</a>"}, 3160, 0, 1795, 134, 0, 1231],[{v:"New Jersey", f:"<a href='https://smartable.ai/apps/coronavirus/stats/us-nj/'>New Jersey</a>"}, 141137, 0, 130247, 9341, 0, 1549],[{v:"New Mexico", f:"New Mexico"}, 5490, 0, 3979, 211, 0, 1300],[{v:"New York", f:"<a href='https://smartable.ai/apps/coronavirus/stats/us-ny/'>New York</a>"}, 347151, 0, 261563, 27225, 0, 58363],[{v:"North Carolina", f:"<a href='https://smartable.ai/apps/coronavirus/stats/us-nc/'>North Carolina</a>"}, 15357, 0, 12356, 575, 0, 2426],[{v:"North Dakota", f:"North Dakota"}, 1518, 0, 636, 36, 0, 846],[{v:"Northern Mariana Islands", f:"Northern Mariana Islands"}, 14, 0, 1, 2, 0, 11],[{v:"Ohio", f:"<a href='https://smartable.ai/apps/coronavirus/stats/us-oh/'>Ohio</a>"}, 24787, 0, 22977, 1362, 0, 448],[{v:"Oklahoma", f:"<a href='https://smartable.ai/apps/coronavirus/stats/us-ok/'>Oklahoma</a>"}, 4620, 0, 1142, 274, 0, 3204],[{v:"Oregon", f:"<a href='https://smartable.ai/apps/coronavirus/stats/us-or/'>Oregon</a>"}, 3286, 0, 2031, 130, 0, 1125],[{v:"Pennsylvania", f:"<a href='https://smartable.ai/apps/coronavirus/stats/us-pa/'>Pennsylvania</a>"}, 60576, 0, 55631, 3845, 0, 1100],[{v:"Rhode Island", f:"<a href='https://smartable.ai/apps/coronavirus/stats/us-ri/'>Rhode Island</a>"}, 11450, 0, 10290, 430, 0, 730],[{v:"South Carolina", f:"<a href='https://smartable.ai/apps/coronavirus/stats/us-sc/'>South Carolina</a>"}, 7842, 0, 2615, 346, 0, 4881],[{v:"South Dakota", f:"South Dakota"}, 3618, 0, 1396, 35, 0, 2187],[{v:"Tennessee", f:"<a href='https://smartable.ai/apps/coronavirus/stats/us-tn/'>Tennessee</a>"}, 15773, 0, 7471, 264, 0, 8038],[{v:"Texas", f:"<a href='https://smartable.ai/apps/coronavirus/stats/us-tx/'>Texas</a>"}, 40855, 0, 16110, 1153, 0, 23592],[{v:"Utah", f:"<a href='https://smartable.ai/apps/coronavirus/stats/us-ut/'>Utah</a>"}, 6574, 0, 3322, 71, 0, 3181],[{v:"Vermont", f:"<a href='https://smartable.ai/apps/coronavirus/stats/us-vt/'>Vermont</a>"}, 927, 0, 88, 54, 0, 785],[{v:"Virginia", f:"<a href='https://smartable.ai/apps/coronavirus/stats/us-va/'>Virginia</a>"}, 25070, 0, 21096, 850, 0, 3124],[{v:"Washington", f:"<a href='https://smartable.ai/apps/coronavirus/stats/us-wa/'>Washington</a>"}, 18029, 0, 13358, 953, 0, 3718],[{v:"West Virginia", f:"West Virginia"}, 1377, 0, 517, 57, 0, 803],[{v:"Wisconsin", f:"<a href='https://smartable.ai/apps/coronavirus/stats/us-wi/'>Wisconsin</a>"}, 10421, 0, 4998, 409, 0, 5014],[{v:"Wyoming", f:"Wyoming"}, 672, 0, 214, 7, 0, 451],[{v:"Veteran Affairs", f:"Veteran Affairs"}, 6692, 0, 6279, 413, 0, 0],[{v:"US Military", f:"US Military"}, 6213, 0, 4240, 26, 0, 1947],[{v:"Navajo Nation", f:"Navajo Nation"}, 1540, 0, 1482, 58, 0, 0],[{v:"Federal Prisons", f:"Federal Prisons"}, 1047, 0, 514, 26, 0, 507],[{v:"Wuhan Repatriated", f:"Wuhan Repatriated"}, 3, 0, 3, 0, 0, 0],
    ]);
    data.setProperty(0, 0, 'style', 'min-width:100px');
    var table = new google.visualization.Table(document.getElementById('geo_table'));
    table.draw(data, {allowHtml: true, sortColumn: 2, sortAscending: false, width: '660px', height: '100%'});
  }
</script>

<span style="font-size: 13px">All COVID-19 data displayed on the page is available through our FREE <a href="https://developer.smartable.ai">API program</a>. This US Coronavirus (COVID-19) Live Stats is refreshed every hour using credible data sources, including the country/state's official government website, <a href="https://en.wikipedia.org/wiki/2019%E2%80%9320_coronavirus_pandemic" target="_blank">data available on wikipedia pages</a>, latest news reports, <a href="https://systems.jhu.edu/research/public-health/ncov/" target="_blank">Johns Hopkins University CSSE 2019-nCoV Dashboard</a>, <a href="https://www.who.int/emergencies/diseases/novel-coronavirus-2019/situation-reports" target="_blank">WHO Situation Reports</a>, <a href="https://www.cdc.gov/coronavirus/2019-ncov/index.html" target="_blank">CDC Situation Updates</a>, and <a href="https://ncov.dxy.cn/ncovh5/view/pneumonia" target="_blank">DXY.cn</a>.</span>


<h2 id="news" class="center" style="margin-top: 60px; font-size: 25px;">Trending Coronavirus News in US</h2>
<div class="row">
<div class="col-md-6 col-sm-12">
  <div class="content-card">
	<a href="https://www.dailynews.com/2020/05/09/la-county-announces-44-more-coronavirus-deaths-more-than-1000-new-cases/"><div class="card-image" style="background-image: url(https://www.dailynews.com/wp-content/uploads/2020/05/LDN-L-VIRUS-LA-0313-01-SR-1.jpg?w=1024&h=682)"></div></a>
	<div class="content">
		<div class="card-title"><a href="https://www.dailynews.com/2020/05/09/la-county-announces-44-more-coronavirus-deaths-more-than-1000-new-cases/">LA County announces 44 more coronavirus deaths, more than 1,000 new cases</a></div>
		<div class="card-excerpt">Another 44 Los Angeles County residents have died after testing positive for the coronavirus, officials announced Saturday, May 9, bringing the county’s death toll to 1,512. The county’s Public Health Department also reported 1,</div>
		<div class="card-meta">
			<span class="card-provider">Los Angeles Daily News</span> • <span class="card-date">5/9/2020</span>
		</div>
	</div>
  </div>
</div>
<div class="col-md-6 col-sm-12">
  <div class="content-card">
	<a href="https://www.nbcnews.com/news/us-news/southern-california-birthday-party-blamed-covid-19-cluster-n1203821"><div class="card-image" style="background-image: url(https://media3.s-nbcnews.com/i/newscms/2020_19/3343826/200509-pasadena-al-1700_11d43d196d0261a8dea45051909d77e1.jpg)"></div></a>
	<div class="content">
		<div class="card-title"><a href="https://www.nbcnews.com/news/us-news/southern-california-birthday-party-blamed-covid-19-cluster-n1203821">Southern California birthday party blamed for COVID-19 cluster</a></div>
		<div class="card-excerpt">One attendee joked that, because she was coughing, she probably had the virus, a city of Pasadena spokeswoman said.</div>
		<div class="card-meta">
			<span class="card-provider">NBC News</span> • <span class="card-date">5/9/2020</span>
		</div>
	</div>
  </div>
</div>
<div class="col-md-6 col-sm-12">
  <div class="content-card">
	<a href="https://www.cbsnews.com/news/sioux-tribe-rejects-south-dakota-governors-request-to-remove-coronavirus-checkpoints/"><div class="card-image" style="background-image: url(https://cbsnews1.cbsistatic.com/hub/i/r/2020/05/10/3310b480-c405-4866-971f-519f4f976a0a/thumbnail/1200x630/4bc8e2e6a5ce5c09e00c4e47979600e9/gettyimages-1189041682.jpg)"></div></a>
	<div class="content">
		<div class="card-title"><a href="https://www.cbsnews.com/news/sioux-tribe-rejects-south-dakota-governors-request-to-remove-coronavirus-checkpoints/">Sioux tribe rejects South Dakota governor's request to remove coronavirus travel checkpoints</a></div>
		<div class="card-excerpt">"I absolutely agree that we need to work together during this time of crisis, however you continuing to interfere in our efforts to do what science and facts dictate seriously undermine our ability to protect everyone on the reservation,</div>
		<div class="card-meta">
			<span class="card-provider">CBS News</span> • <span class="card-date">5/9/2020</span>
		</div>
	</div>
  </div>
</div>
<div class="col-md-6 col-sm-12">
  <div class="content-card">
	<a href="https://www.theguardian.com/world/2020/may/10/elon-musk-threatens-to-move-tesla-hq-out-of-california-over-covid-19-restrictions?CMP=twt_gu"><div class="card-image" style="background-image: url(https://i.guim.co.uk/img/media/0d0b568444ea1f2fc72d351f5fc1c56ebde4e8f7/0_300_4500_2700/master/4500.jpg?width=300&quality=45&auto=format&fit=max&dpr=2&s=5d64a4cb5c6ddfa6d3e0eb2d97422e52)"></div></a>
	<div class="content">
		<div class="card-title"><a href="https://www.theguardian.com/world/2020/may/10/elon-musk-threatens-to-move-tesla-hq-out-of-california-over-covid-19-restrictions?CMP=twt_gu">Elon Musk threatens to move Tesla HQ out of California over Covid-19 restrictions</a></div>
		<div class="card-excerpt">Tesla sues state authorities over lockdown after Fremont factory stopped from reopening</div>
		<div class="card-meta">
			<span class="card-provider">The Guardian</span> • <span class="card-date">5/9/2020</span>
		</div>
	</div>
  </div>
</div>
<div class="col-md-6 col-sm-12">
  <div class="content-card">
	<a href="https://www.theguardian.com/world/live/2020/may/10/coronavirus-live-news-obama-trumps-covid-19--chaotic-as-global-cases-pass-4-million-mexico-russia-germany-south-korea-deaths-"><div class="card-image" style="background-image: url(https://i.guim.co.uk/img/media/45a5994a2f94016349125d7531d0b731d4269e5d/0_250_5440_3263/master/5440.jpg?width=300&quality=45&auto=format&fit=max&dpr=2&s=2229c0c065451654592fea41c0efc9ea)"></div></a>
	<div class="content">
		<div class="card-title"><a href="https://www.theguardian.com/world/live/2020/may/10/coronavirus-live-news-obama-trumps-covid-19--chaotic-as-global-cases-pass-4-million-mexico-russia-germany-south-korea-deaths-">Coronavirus live news: Obama calls Trump's Covid-19 response 'chaotic', as global cases pass 4 million</a></div>
		<div class="card-excerpt">Mexican hospitals turn people away; Russia cases approach 200,000; German football league setback as Dynamo Dresden team quarantined</div>
		<div class="card-meta">
			<span class="card-provider">The Guardian</span> • <span class="card-date">5/9/2020</span>
		</div>
	</div>
  </div>
</div>
<div class="col-md-6 col-sm-12">
  <div class="content-card">
	<a href="https://www.lubbockonline.com/news/20200509/lubbock-reports-6-new-coronavirus-cases-restaurant-as-possible-exposure-site"><div class="card-image" style="background-image: url(https://www.lubbockonline.com/apps/pbcsi.dll/bilde?Site=TX&Date=20200509&Category=NEWS&ArtNo=200508977&Ref=AR)"></div></a>
	<div class="content">
		<div class="card-title"><a href="https://www.lubbockonline.com/news/20200509/lubbock-reports-6-new-coronavirus-cases-restaurant-as-possible-exposure-site">Lubbock reports 6 new coronavirus cases, restaurant as possible exposure site</a></div>
		<div class="card-excerpt">Lubbock health officials on Saturday announced six new confirmed coronavirus cases in the county, with no new deaths linked to COVID-19 reported for the</div>
		<div class="card-meta">
			<span class="card-provider">Lubbock Avalanche-Journal</span> • <span class="card-date">5/9/2020</span>
		</div>
	</div>
  </div>
</div>
<div class="col-md-6 col-sm-12">
  <div class="content-card">
	<a href="https://apnews.com/065083df159ef7f85df41a0b6f3a4fea"><div class="card-image" style="background-image: url(https://storage.googleapis.com/afs-prod/media/6f4820446786468f83ebd4fb8715e2a0/3000.jpeg)"></div></a>
	<div class="content">
		<div class="card-title"><a href="https://apnews.com/065083df159ef7f85df41a0b6f3a4fea">Beshear: Infant among Kentucky’s new coronavirus cases</a></div>
		<div class="card-excerpt">FRANKFORT, Ky. (AP) — A 1-year-old child is among Kentucky's 158 new coronavirus cases, Gov. Andy Beshear said Saturday. The Democratic governor said the state's caseload continues</div>
		<div class="card-meta">
			<span class="card-provider">Associated Press</span> • <span class="card-date">5/9/2020</span>
		</div>
	</div>
  </div>
</div>
<div class="col-md-6 col-sm-12">
  <div class="content-card">
	<a href="https://www.cbsnews.com/live/video/20200510031952-hawaii-reports-no-new-covid19-cases/"><div class="card-image" style="background-image: url(https://images-cbsn.cbsnews.com/prod/2020/05/10/story_05019306_1589080815.jpg)"></div></a>
	<div class="content">
		<div class="card-title"><a href="https://www.cbsnews.com/live/video/20200510031952-hawaii-reports-no-new-covid19-cases/">Hawaii reports no new COVID19 cases</a></div>
		<div class="card-excerpt">Watch "Hawaii reports no new COVID19 cases", a CBSN video on CBSNews.com. View more CBSN videos and watch CBSN, a live news stream featuring original CBS News reporting.</div>
		<div class="card-meta">
			<span class="card-provider">CBS News</span> • <span class="card-date">5/9/2020</span>
		</div>
	</div>
  </div>
</div>
<div class="col-md-6 col-sm-12">
  <div class="content-card">
	<a href="https://www.eastbaytimes.com/2020/05/09/coronavirus-alameda-reports-more-new-cases-than-other-bay-area-counties/"><div class="card-image" style="background-image: url(https://www.eastbaytimes.com/wp-content/uploads/2020/05/TEASER_coronavirus_BAY_AREA-1-2-7.jpg?w=1024&h=688)"></div></a>
	<div class="content">
		<div class="card-title"><a href="https://www.eastbaytimes.com/2020/05/09/coronavirus-alameda-reports-more-new-cases-than-other-bay-area-counties/">Coronavirus: Alameda reports more new cases than other Bay Area counties</a></div>
		<div class="card-excerpt">Alameda County reported 62 new coronavirus cases on Saturday, more than anywhere else in the Bay Area. The county also recorded one of the region’s four deaths reported Saturday. The other three fatalities occurred in Contra Costa County.</div>
		<div class="card-meta">
			<span class="card-provider">East Bay Times</span> • <span class="card-date">5/9/2020</span>
		</div>
	</div>
  </div>
</div>
<div class="col-md-6 col-sm-12">
  <div class="content-card">
	<a href="https://www.statesmanjournal.com/story/news/2020/05/09/covid-19-oregon-coronavirus-updates-saturday-shakespeare-festival-cancels-season-salem/3102482001/"><div class="card-image" style="background-image: url(https://www.gannett-cdn.com/presto/2020/04/07/PSAL/151a66a0-494f-4e75-9cbf-4d938e6e3acd-GettyImages-1210366866.jpg?auto=webp&crop=2031,1143,x0,y163&format=pjpg&width=1200)"></div></a>
	<div class="content">
		<div class="card-title"><a href="https://www.statesmanjournal.com/story/news/2020/05/09/covid-19-oregon-coronavirus-updates-saturday-shakespeare-festival-cancels-season-salem/3102482001/">Oregon coronavirus updates, Saturday: Marion County sees spike in new cases</a></div>
		<div class="card-excerpt">Check back on this story throughout the day for the latest news about coronavirus and its effects in Salem and around Oregon</div>
		<div class="card-meta">
			<span class="card-provider">Statesman Journal</span> • <span class="card-date">5/9/2020</span>
		</div>
	</div>
  </div>
</div>

</div>

