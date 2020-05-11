---
category: stats
title: "China Coronavirus (COVID-19) Live Stats"
excerpt: "Live stats of COVID-19 in China. Total Cases: 84011 (-), Deaths: 4637 (-), Recoveries: 80012(+4)."
publishedDateTime: 2020-05-11T23:45:10Z
updatedDateTime: 2020-05-11T23:45:10Z
webUrl: "https://smartable.ai/apps/coronavirus/stats/china/"
type: article
heat: 800

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
  - Coronavirus in China

images:
  - url: "https://smartable.azureedge.net/coronavirus/sites/2/2020/china.jpg"
    width: 900
    height: 564
    title: "China Coronavirus (COVID-19) Live Stats"

---
<div class="total-stats" style="text-align: center;">
    <h3>
	    <div style="font-size: 18px; font-weight: 400;">Total Confirmed Cases:</div>
	    84011 (-)
    </h3>
    <h3>
	    <div style="font-size: 18px; font-weight: 400;">Total Deaths:</div>
	    4637 (-)
    </h3>
    <h3>
	    <div style="font-size: 18px; font-weight: 400;">Total Recovered:</div>
	    80012 (<span class='green'>+4</span>)
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
      ['1/22/2020', 548, 17, 28],['1/23/2020', 643, 18, 30],['1/24/2020', 920, 26, 36],['1/25/2020', 1406, 42, 39],['1/26/2020', 2075, 56, 49],['1/27/2020', 2877, 82, 58],['1/28/2020', 5509, 131, 101],['1/29/2020', 6087, 133, 120],['1/30/2020', 8141, 171, 135],['1/31/2020', 9802, 213, 214],['2/1/2020', 11891, 259, 275],['2/2/2020', 16630, 361, 462],['2/3/2020', 19716, 425, 614],['2/4/2020', 23707, 491, 843],['2/5/2020', 27440, 563, 1112],['2/6/2020', 30587, 633, 1477],['2/7/2020', 34110, 718, 1999],['2/8/2020', 36814, 805, 2594],['2/9/2020', 39829, 905, 3219],['2/10/2020', 42354, 1012, 3916],['2/11/2020', 44386, 1112, 4636],['2/12/2020', 44759, 1117, 5083],['2/13/2020', 59895, 1369, 6217],['2/14/2020', 66358, 1521, 7973],['2/15/2020', 68413, 1663, 9298],['2/16/2020', 70513, 1766, 10755],['2/17/2020', 72434, 1864, 12462],['2/18/2020', 74211, 2003, 14206],['2/19/2020', 74619, 2116, 15962],['2/20/2020', 75077, 2238, 18013],['2/21/2020', 75550, 2238, 18704],['2/22/2020', 77001, 2443, 22699],['2/23/2020', 77022, 2445, 23187],['2/24/2020', 77241, 2595, 25015],['2/25/2020', 77754, 2665, 27676],['2/26/2020', 78166, 2717, 30084],['2/27/2020', 78600, 2746, 32930],['2/28/2020', 78928, 2790, 36329],['2/29/2020', 79356, 2837, 39320],['3/1/2020', 79932, 2872, 42162],['3/2/2020', 80136, 2914, 44854],['3/3/2020', 80261, 2947, 47450],['3/4/2020', 80386, 2983, 50001],['3/5/2020', 80537, 3015, 52292],['3/6/2020', 80690, 3044, 53944],['3/7/2020', 80770, 3072, 55539],['3/8/2020', 80823, 3100, 57388],['3/9/2020', 80860, 3123, 58804],['3/10/2020', 80887, 3139, 60181],['3/11/2020', 80921, 3161, 61644],['3/12/2020', 80935, 3173, 62911],['3/13/2020', 80972, 3193, 65634],['3/14/2020', 80996, 3203, 67004],['3/15/2020', 81020, 3217, 67843],['3/16/2020', 81051, 3230, 68777],['3/17/2020', 81088, 3241, 69717],['3/18/2020', 81140, 3249, 70529],['3/19/2020', 81200, 3252, 71262],['3/20/2020', 81287, 3259, 71854],['3/21/2020', 81349, 3265, 72360],['3/22/2020', 81440, 3274, 72815],['3/23/2020', 81515, 3274, 72822],['3/24/2020', 81596, 3281, 73275],['3/25/2020', 81728, 3291, 74167],['3/26/2020', 81785, 3291, 74175],['3/27/2020', 81947, 3299, 75092],['3/28/2020', 82057, 3304, 75570],['3/29/2020', 82153, 3308, 75898],['3/30/2020', 82241, 3309, 76188],['3/31/2020', 82295, 3310, 76200],['4/1/2020', 82395, 3316, 76420],['4/2/2020', 82431, 3316, 76427],['4/3/2020', 82475, 3316, 76446],['4/4/2020', 82494, 3316, 76446],['4/5/2020', 82523, 3316, 76479],['4/6/2020', 82547, 3316, 76489],['4/7/2020', 82568, 3316, 76509],['4/8/2020', 82594, 3316, 76537],['4/9/2020', 82607, 3316, 76566],['4/10/2020', 83004, 3343, 77844],['4/11/2020', 83097, 3343, 77921],['4/12/2020', 83136, 3343, 77956],['4/13/2020', 83303, 3345, 78148],['4/14/2020', 83352, 3346, 78265],['4/15/2020', 83402, 3346, 78370],['4/16/2020', 83754, 4636, 78472],['4/17/2020', 83785, 4636, 78540],['4/18/2020', 83804, 4636, 78594],['4/19/2020', 83818, 4636, 78647],['4/20/2020', 83850, 4636, 78715],['4/21/2020', 83865, 4636, 78758],['4/22/2020', 83877, 4636, 78818],['4/23/2020', 83885, 4636, 78869],['4/24/2020', 83886, 4636, 78909],['4/25/2020', 83910, 4636, 79023],['4/26/2020', 83913, 4637, 79113],['4/27/2020', 83939, 4637, 79223],['4/28/2020', 83941, 4637, 79271],['4/29/2020', 83945, 4637, 79310],['4/30/2020', 83957, 4637, 79359],['5/1/2020', 83958, 4637, 79388],['5/2/2020', 83960, 4637, 79423],['5/3/2020', 83965, 4637, 79520],['5/4/2020', 83967, 4637, 79628],['5/5/2020', 83969, 4637, 79706],['5/6/2020', 83971, 4637, 79770],['5/7/2020', 83977, 4637, 79818],['5/8/2020', 83977, 4637, 79834],['5/9/2020', 83992, 4637, 79970],['5/10/2020', 84011, 4637, 80008],['5/11/2020', 84011, 4637, 80012],
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
      ["Anhui Sheng", 991, 6],["Beijing Shi", 593, 9],["Chongqing Shi", 579, 6],["Fujian Sheng", 356, 1],["Gansu Sheng", 139, 2],["Guangdong Sheng", 1589, 8],["Guangxi", 254, 2],["Guizhou Sheng", 147, 2],["Hainan Sheng", 168, 6],["Hebei Sheng", 328, 6],["Heilongjiang Sheng", 945, 13],["Henan Sheng", 1276, 22],["Hong Kong SAR", 1048, 4],["Hubei Sheng", 68134, 4512],["Hunan Sheng", 1019, 4],["Jiangsu Sheng", 653, 0],["Jiangxi Sheng", 937, 1],["Jilin Sheng", 127, 1],["Liaoning Sheng", 147, 2],["Macao SAR", 45, 0],["Nei Mongol", 208, 1],["Ningxia", 75, 0],["Qinghai Sheng", 18, 0],["Shaanxi Sheng", 308, 3],["Shandong Sheng", 788, 7],["Shanghai Shi", 659, 7],["Shanxi Sheng", 198, 0],["Sichuan Sheng", 561, 3],["Tianjin Shi", 191, 3],["Xinjiang", 76, 3],["Xizang", 1, 0],["Yunnan Sheng", 185, 2],["Zhejiang Sheng", 1268, 1],
    ]);
    var options = {
      backgroundColor: {fill:'transparent',stroke:'#FFF' ,strokeWidth:0 }, 
      region: 'CN', 
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
      [{v:"Anhui Sheng", f:"Anhui Sheng"}, 991, 0, 0, 6, 0, 985],[{v:"Beijing Shi", f:"<a href='https://smartable.ai/apps/coronavirus/stats/china-beijing/'>Beijing Shi</a>"}, 593, 0, 16, 9, 0, 568],[{v:"Chongqing Shi", f:"Chongqing Shi"}, 579, 0, 0, 6, 0, 573],[{v:"Fujian Sheng", f:"Fujian Sheng"}, 356, 0, 1, 1, 0, 354],[{v:"Gansu Sheng", f:"Gansu Sheng"}, 139, 0, 0, 2, 0, 137],[{v:"Guangdong Sheng", f:"<a href='https://smartable.ai/apps/coronavirus/stats/china-guangdong/'>Guangdong Sheng</a>"}, 1589, 0, 1, 8, 0, 1580],[{v:"Guangxi", f:"Guangxi"}, 254, 0, 0, 2, 0, 252],[{v:"Guizhou Sheng", f:"Guizhou Sheng"}, 147, 0, 0, 2, 0, 145],[{v:"Hainan Sheng", f:"Hainan Sheng"}, 168, 0, 0, 6, 0, 162],[{v:"Hebei Sheng", f:"Hebei Sheng"}, 328, 0, 1, 6, 0, 321],[{v:"Heilongjiang Sheng", f:"Heilongjiang Sheng"}, 945, 0, 28, 13, 0, 904],[{v:"Henan Sheng", f:"Henan Sheng"}, 1276, 0, 0, 22, 0, 1254],[{v:"Hong Kong SAR", f:"<a href='https://smartable.ai/apps/coronavirus/stats/china-hongkong/'>Hong Kong SAR</a>"}, 1048, 0, 59, 4, 0, 985],[{v:"Hubei Sheng", f:"<a href='https://smartable.ai/apps/coronavirus/stats/china-hubei/'>Hubei Sheng</a>"}, 68134, 0, 0, 4512, 0, 64452],[{v:"Hunan Sheng", f:"Hunan Sheng"}, 1019, 0, 0, 4, 0, 1015],[{v:"Jiangsu Sheng", f:"Jiangsu Sheng"}, 653, 0, 0, 0, 0, 653],[{v:"Jiangxi Sheng", f:"Jiangxi Sheng"}, 937, 0, 0, 1, 0, 936],[{v:"Jilin Sheng", f:"Jilin Sheng"}, 127, 0, 21, 1, 0, 105],[{v:"Liaoning Sheng", f:"Liaoning Sheng"}, 147, 0, 1, 2, 0, 144],[{v:"Macao SAR", f:"Macao SAR"}, 45, 0, 3, 0, 0, 42],[{v:"Nei Mongol", f:"Nei Mongol"}, 208, 0, 20, 1, 0, 187],[{v:"Ningxia", f:"Ningxia"}, 75, 0, 0, 0, 0, 75],[{v:"Qinghai Sheng", f:"Qinghai Sheng"}, 18, 0, 0, 0, 0, 18],[{v:"Shaanxi Sheng", f:"Shaanxi Sheng"}, 308, 0, 11, 3, 0, 294],[{v:"Shandong Sheng", f:"Shandong Sheng"}, 788, 0, 4, 7, 0, 777],[{v:"Shanghai Shi", f:"<a href='https://smartable.ai/apps/coronavirus/stats/china-shanghai/'>Shanghai Shi</a>"}, 659, 0, 23, 7, 0, 629],[{v:"Shanxi Sheng", f:"Shanxi Sheng"}, 198, 0, 1, 0, 0, 197],[{v:"Sichuan Sheng", f:"Sichuan Sheng"}, 561, 0, 0, 3, 0, 558],[{v:"Tianjin Shi", f:"Tianjin Shi"}, 191, 0, 2, 3, 0, 186],[{v:"Xinjiang", f:"Xinjiang"}, 76, 0, 0, 3, 0, 73],[{v:"Xizang", f:"Xizang"}, 1, 0, 0, 0, 0, 1],[{v:"Yunnan Sheng", f:"Yunnan Sheng"}, 185, 0, 0, 2, 0, 183],[{v:"Zhejiang Sheng", f:"Zhejiang Sheng"}, 1268, 0, 0, 1, 0, 1267],
    ]);
    data.setProperty(0, 0, 'style', 'min-width:100px');
    var table = new google.visualization.Table(document.getElementById('geo_table'));
    table.draw(data, {allowHtml: true, sortColumn: 2, sortAscending: false, width: '660px', height: '100%'});
  }
</script>

<span style="font-size: 13px">All COVID-19 data displayed on the page is available through our FREE <a href="https://developer.smartable.ai">API program</a>. This China Coronavirus (COVID-19) Live Stats is refreshed every hour using credible data sources, including the country/state's official government website, <a href="https://en.wikipedia.org/wiki/2019%E2%80%9320_coronavirus_pandemic" target="_blank">data available on wikipedia pages</a>, latest news reports, <a href="https://systems.jhu.edu/research/public-health/ncov/" target="_blank">Johns Hopkins University CSSE 2019-nCoV Dashboard</a>, <a href="https://www.who.int/emergencies/diseases/novel-coronavirus-2019/situation-reports" target="_blank">WHO Situation Reports</a>, <a href="https://www.cdc.gov/coronavirus/2019-ncov/index.html" target="_blank">CDC Situation Updates</a>, and <a href="https://ncov.dxy.cn/ncovh5/view/pneumonia" target="_blank">DXY.cn</a>.</span>


<h2 id="news" class="center" style="margin-top: 60px; font-size: 25px;">Trending Coronavirus News in China</h2>
<div class="row">
<div class="col-md-6 col-sm-12">
  <div class="content-card">
	<a href="https://abcnews.go.com/Health/wireStory/asia-today-south-korea-china-report-rise-infections-70601425"><div class="card-image" style="background-image: url(https://s.abcnews.com/images/Health/WireAP_f55b8e15c6aa41649bd791bbb67ce260_16x9_992.jpg)"></div></a>
	<div class="content">
		<div class="card-title"><a href="https://abcnews.go.com/Health/wireStory/asia-today-south-korea-china-report-rise-infections-70601425">Asia Today: South Korea, China report rise in infections</a></div>
		<div class="card-excerpt">South Korea has reported 34 additional cases of the coronavirus amid a spate of infections linked to clubgoers</div>
		<div class="card-meta">
			<span class="card-provider">ABC</span> • <span class="card-date">5/9/2020</span>
		</div>
	</div>
  </div>
</div>
<div class="col-md-6 col-sm-12">
  <div class="content-card">
	<a href="https://www.thestar.com.my/news/regional/2020/05/10/china039s-hubei-reports-one-case-of-covid-19"><div class="card-image" style="background-image: url(https://apicms.thestar.com.my/uploads/images/2020/05/10/675838.jpg)"></div></a>
	<div class="content">
		<div class="card-title"><a href="https://www.thestar.com.my/news/regional/2020/05/10/china039s-hubei-reports-one-case-of-covid-19">China's Hubei reports one case of Covid-19</a></div>
		<div class="card-excerpt">WUHAN: One new confirmed case of the Covid-19 (coronavirus) disease was reported in central China's Hubei Province on late Saturday, the provincial health commission said Sunday morning (May 10).</div>
		<div class="card-meta">
			<span class="card-provider">The Star</span> • <span class="card-date">5/9/2020</span>
		</div>
	</div>
  </div>
</div>
<div class="col-md-6 col-sm-12">
  <div class="content-card">
	<a href="https://www.reuters.com/article/us-nintendo-china-idUSKBN22M01G"><div class="card-image" style="background-image: url(https://s2.reutersmedia.net/resources/r/?m=02&d=20200510&t=2&i=1518071878&w=&fh=545px&fw=&ll=&pl=&sq=&r=LYNXMPEG4901F)"></div></a>
	<div class="content">
		<div class="card-title"><a href="https://www.reuters.com/article/us-nintendo-china-idUSKBN22M01G">China's Animal Crossing gamers use code words, middlemen to enter virtual world</a></div>
		<div class="card-excerpt">New Horizons are paying a premium on foreign consoles and finding ways to skirt limits imposed by local regulators on a game that has become both a breakout worldwide hit and political flashpoint.</div>
		<div class="card-meta">
			<span class="card-provider">Reuters</span> • <span class="card-date">5/9/2020</span>
		</div>
	</div>
  </div>
</div>
<div class="col-md-6 col-sm-12">
  <div class="content-card">
	<a href="https://www.reuters.com/article/us-health-coronavirus-china-idUSKBN22M00V"><div class="card-image" style="background-image: url(https://s1.reutersmedia.net/resources/r/?m=02&d=20200510&t=2&i=1518071163&w=&fh=545px&fw=&ll=&pl=&sq=&r=LYNXMPEG49011)"></div></a>
	<div class="content">
		<div class="card-title"><a href="https://www.reuters.com/article/us-health-coronavirus-china-idUSKBN22M00V">China reports 14 new coronavirus cases, high-risk area resurfaces</a></div>
		<div class="card-excerpt">China's National Health Commission reported 14 new confirmed coronavirus cases on May 9, the highest number since April 28 and up from only one case a day earlier, according to data published on Sunday.</div>
		<div class="card-meta">
			<span class="card-provider">Reuters</span> • <span class="card-date">5/9/2020</span>
		</div>
	</div>
  </div>
</div>
<div class="col-md-6 col-sm-12">
  <div class="content-card">
	<a href="https://www.nbcnews.com/video/jenna-bush-hager-finds-out-how-kids-in-china-are-doing-as-coronavirus-lockdown-lifts-83259461686"><div class="card-image" style="background-image: url(https://media11.s-nbcnews.com/j/MSNBC/Components/Video/202005/f_unicef_jenna_bush_hager_200509_1920x1080.nbcnews-fp-1200-630.jpg)"></div></a>
	<div class="content">
		<div class="card-title"><a href="https://www.nbcnews.com/video/jenna-bush-hager-finds-out-how-kids-in-china-are-doing-as-coronavirus-lockdown-lifts-83259461686">Jenna Bush Hager finds out how kids in China are doing as coronavirus lockdown lifts</a></div>
		<div class="card-excerpt">TODAY co-host Jenna Bush Hager talks to UNICEF representative from China Cynthia McCaffrey about how the organization rushed supplies to children when the coronavirus lockdown was happening and how kids are doing now that circumstances have improved.May 10, 2020 © 2020 NBC UNIVERSAL</div>
		<div class="card-meta">
			<span class="card-provider">NBC News</span> • <span class="card-date">5/9/2020</span>
		</div>
	</div>
  </div>
</div>
<div class="col-md-6 col-sm-12">
  <div class="content-card">
	<a href="https://www.foxnews.com/transcript/sen-cotton-china-made-conscious-decision-to-let-coronavirus-spread-after-they-knew-how-deadly-it-was"><div class="card-image" style="background-image: url(https://cf-images.us-east-1.prod.boltdns.net/v1/static/694940094001/f33c1360-73c1-4973-b722-e3ab9b105a85/a7aacdd9-9f68-438f-b8d7-63cdb0737d8e/1280x720/match/image.jpg)"></div></a>
	<div class="content">
		<div class="card-title"><a href="https://www.foxnews.com/transcript/sen-cotton-china-made-conscious-decision-to-let-coronavirus-spread-after-they-knew-how-deadly-it-was">Sen. Cotton: China made conscious decision to let coronavirus spread after they knew how deadly it was</a></div>
		<div class="card-excerpt">We knew it was coming, even if this is the highest unemployment rate since the Great Depression, and it's still a shock to the system. (BEGIN AUDIO CLIP)  TRUMP: It's fully expected. There's no surprise.</div>
		<div class="card-meta">
			<span class="card-provider">Fox News</span> • <span class="card-date">5/9/2020</span>
		</div>
	</div>
  </div>
</div>
<div class="col-md-6 col-sm-12">
  <div class="content-card">
	<a href="https://www.ibtimes.com/north-korea-news-kim-jong-un-praises-china-leader-clashes-south-korea-over-military-2973398"><div class="card-image" style="background-image: url(https://s1.ibtimes.com/sites/www.ibtimes.com/files/styles/full/public/2020/04/14/the-latest-test-comes-a-day-before-north.jpg)"></div></a>
	<div class="content">
		<div class="card-title"><a href="https://www.ibtimes.com/north-korea-news-kim-jong-un-praises-china-leader-clashes-south-korea-over-military-2973398">North Korea News: Kim Jong Un Praises China Leader, Clashes With South Korea Over Military Drills</a></div>
		<div class="card-excerpt">Kim Jong Un in his message extended his warm greetings to Xi Jinping and congratulated him, highly appreciating that he is seizing a chance of victory in the war against the unprecedented epidemic,” the state-run Korean Central News Agency (KCNA) said.</div>
		<div class="card-meta">
			<span class="card-provider">International Business Times</span> • <span class="card-date">5/9/2020</span>
		</div>
	</div>
  </div>
</div>
<div class="col-md-6 col-sm-12">
  <div class="content-card">
	<a href="https://www.foxnews.com/media/jeff-van-drew-china-coronavirus-democrats-house-politics"><div class="card-image" style="background-image: url(https://static.foxnews.com/foxnews.com/content/uploads/2020/05/JEFF.jpg)"></div></a>
	<div class="content">
		<div class="card-title"><a href="https://www.foxnews.com/media/jeff-van-drew-china-coronavirus-democrats-house-politics">Rep. Jeff Van Drew: Dems won't help Republicans hold China accountable on coronavirus because of politics</a></div>
		<div class="card-excerpt">It is "unbelievable" that there is not a united political front in terms of holding China accountable for their role in the coronavirus outbreak, Rep. Jeff Van Drew, R-N.J., stated Saturday.</div>
		<div class="card-meta">
			<span class="card-provider">Fox News</span> • <span class="card-date">5/9/2020</span>
		</div>
	</div>
  </div>
</div>
<div class="col-md-6 col-sm-12">
  <div class="content-card">
	<a href="https://www.foxnews.com/media/coronavirus-china-maria-bartiromo-fox-nation"><div class="card-image" style="background-image: url(https://cf-images.us-east-1.prod.boltdns.net/v1/static/694940094001/e2aca2ed-9139-4353-95fa-2cf689e07d85/39b2a7cc-7842-45eb-b509-ffaa09db1a3d/1280x720/match/image.jpg)"></div></a>
	<div class="content">
		<div class="card-title"><a href="https://www.foxnews.com/media/coronavirus-china-maria-bartiromo-fox-nation">Maria Bartiromo: Communist China's COVID-19 response 'brought us to a critical moment'</a></div>
		<div class="card-excerpt">Fox News and Fox Business host Maria Bartiromo looked into the origins of the world's deadliest pandemic in more than a century and examined how the Chinese communist dictatorship has responded to the crisis,</div>
		<div class="card-meta">
			<span class="card-provider">Fox News</span> • <span class="card-date">5/9/2020</span>
		</div>
	</div>
  </div>
</div>
<div class="col-md-6 col-sm-12">
  <div class="content-card">
	<a href="https://www.nytimes.com/2020/05/09/us/politics/china-journalists-us-visa-crackdown.html"><div class="card-image" style="background-image: url(https://static01.nyt.com/images/2020/05/09/world/09china-journalists01/09china-journalists01-facebookJumbo.jpg)"></div></a>
	<div class="content">
		<div class="card-title"><a href="https://www.nytimes.com/2020/05/09/us/politics/china-journalists-us-visa-crackdown.html">U.S. Hits Back at China With New Visa Restrictions on Journalists</a></div>
		<div class="card-excerpt">The Trump administration is imposing 90-day limits on work visas for Chinese journalists, raising the threat of further retaliation by the Chinese government.</div>
		<div class="card-meta">
			<span class="card-provider">New York Times</span> • <span class="card-date">5/9/2020</span>
		</div>
	</div>
  </div>
</div>

</div>

