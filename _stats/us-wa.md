---
category: stats
title: "US - Washington State Coronavirus (COVID-19) Live Stats"
excerpt: "Live stats of COVID-19 in US-Washington. Total Cases: 18302 (+273), Deaths: 958 (+5), Recoveries: 3718(-)."
publishedDateTime: 2020-05-12T18:45:13Z
updatedDateTime: 2020-05-12T18:45:13Z
webUrl: "https://smartable.ai/apps/coronavirus/stats/us-wa/"
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
  - url: "https://smartable.azureedge.net/coronavirus/sites/2/2020/us-wa.jpg"
    width: 900
    height: 564
    title: "US - Washington State Coronavirus (COVID-19) Live Stats"

---
<div class="total-stats" style="text-align: center;">
    <h3>
	    <div style="font-size: 18px; font-weight: 400;">Total Confirmed Cases:</div>
	    18302 (<span class='red'>+273</span>)
    </h3>
    <h3>
	    <div style="font-size: 18px; font-weight: 400;">Total Deaths:</div>
	    958 (<span class='red'>+5</span>)
    </h3>
    <h3>
	    <div style="font-size: 18px; font-weight: 400;">Total Recovered:</div>
	    3718 (-)
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
      ['1/22/2020', 1, 0, 0],['1/23/2020', 1, 0, 0],['1/24/2020', 1, 0, 0],['1/25/2020', 1, 0, 0],['1/26/2020', 1, 0, 0],['1/27/2020', 1, 0, 0],['1/28/2020', 1, 0, 0],['1/29/2020', 1, 0, 0],['1/30/2020', 1, 0, 0],['1/31/2020', 1, 0, 0],['2/1/2020', 1, 0, 0],['2/2/2020', 1, 0, 0],['2/3/2020', 1, 0, 0],['2/4/2020', 1, 0, 0],['2/5/2020', 1, 0, 0],['2/6/2020', 1, 0, 0],['2/7/2020', 1, 0, 0],['2/8/2020', 1, 0, 0],['2/9/2020', 1, 0, 1],['2/10/2020', 1, 0, 1],['2/11/2020', 1, 0, 1],['2/12/2020', 1, 0, 1],['2/13/2020', 1, 0, 1],['2/14/2020', 1, 0, 1],['2/15/2020', 1, 0, 1],['2/16/2020', 1, 0, 1],['2/17/2020', 1, 0, 1],['2/18/2020', 1, 0, 1],['2/19/2020', 1, 0, 1],['2/20/2020', 1, 0, 1],['2/21/2020', 1, 0, 1],['2/22/2020', 1, 0, 1],['2/23/2020', 1, 0, 1],['2/24/2020', 1, 0, 1],['2/25/2020', 1, 0, 1],['2/26/2020', 1, 0, 1],['2/27/2020', 1, 0, 1],['2/28/2020', 1, 0, 1],['2/29/2020', 7, 1, 1],['3/1/2020', 11, 1, 1],['3/2/2020', 18, 6, 1],['3/3/2020', 27, 7, 1],['3/4/2020', 39, 10, 1],['3/5/2020', 70, 11, 1],['3/6/2020', 78, 13, 1],['3/7/2020', 102, 16, 1],['3/8/2020', 122, 18, 1],['3/9/2020', 122, 19, 1],['3/10/2020', 162, 23, 1],['3/11/2020', 282, 24, 1],['3/12/2020', 457, 31, 1],['3/13/2020', 569, 37, 1],['3/14/2020', 642, 40, 1],['3/15/2020', 769, 42, 1],['3/16/2020', 904, 48, 1],['3/17/2020', 1005, 55, 1],['3/18/2020', 1187, 68, 89],['3/19/2020', 1377, 74, 89],['3/20/2020', 1524, 83, 124],['3/21/2020', 1793, 94, 124],['3/22/2020', 1996, 95, 124],['3/23/2020', 2221, 111, 124],['3/24/2020', 2460, 125, 124],['3/25/2020', 2600, 133, 124],['3/26/2020', 3207, 150, 124],['3/27/2020', 3726, 175, 124],['3/28/2020', 4311, 189, 124],['3/29/2020', 4874, 204, 124],['3/30/2020', 5164, 219, 124],['3/31/2020', 5453, 225, 124],['4/1/2020', 5984, 254, 563],['4/2/2020', 6595, 272, 568],['4/3/2020', 6967, 295, 582],['4/4/2020', 7632, 318, 622],['4/5/2020', 7984, 343, 667],['4/6/2020', 8384, 383, 839],['4/7/2020', 8982, 408, 891],['4/8/2020', 9277, 432, 925],['4/9/2020', 9753, 457, 1076],['4/10/2020', 10221, 484, 1146],['4/11/2020', 10416, 496, 1287],['4/12/2020', 10529, 510, 1325],['4/13/2020', 10723, 522, 1410],['4/14/2020', 10928, 546, 1424],['4/15/2020', 10969, 562, 1507],['4/16/2020', 11278, 587, 1719],['4/17/2020', 11688, 610, 1757],['4/18/2020', 11792, 630, 1765],['4/19/2020', 11904, 634, 1778],['4/20/2020', 12486, 658, 1782],['4/21/2020', 12527, 720, 1790],['4/22/2020', 12655, 733, 1798],['4/23/2020', 12940, 752, 1803],['4/24/2020', 13067, 766, 1805],['4/25/2020', 13332, 741, 1807],['4/26/2020', 13609, 752, 1807],['4/27/2020', 13763, 765, 1807],['4/28/2020', 13914, 788, 1851],['4/29/2020', 14170, 806, 1851],['4/30/2020', 14466, 819, 1851],['5/1/2020', 14810, 825, 1851],['5/2/2020', 15512, 836, 1851],['5/3/2020', 15776, 837, 2033],['5/4/2020', 16136, 846, 2432],['5/5/2020', 16360, 870, 2545],['5/6/2020', 16694, 880, 2632],['5/7/2020', 16943, 904, 2686],['5/8/2020', 17351, 914, 2747],['5/9/2020', 17561, 922, 3626],['5/10/2020', 17806, 932, 3646],['5/11/2020', 18029, 953, 3718],['5/12/2020', 18302, 958, 3718],
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
      [46.7735, -118.8277, "Adams", 49, 0],[46.2826, -119.2937, "Benton", 719, 54],[47.5175, -120.4671, "Chelan", 153, 6],[48.1229, -123.0911, "Clallam", 19, 0],[45.7466, -122.5194, "Clark", 386, 24],[46.3168, -117.9769, "Columbia", 1, 0],[46.1796, -122.9577, "Cowlitz", 66, 0],[47.648, -120.0707, "Douglas", 117, 2],[48.7311, -118.6663, "Ferry", 1, 0],[46.5737, -119.0013, "Franklin", 525, 16],[47.1981, -119.3732, "Grant", 219, 3],[46.8304, -124.0898, "Grays Harbor", 14, 0],[48.1976, -122.5795, "Island", 179, 9],[47.7425, -123.304, "Jefferson", 29, 0],[47.6062, -122.3321, "King", 7434, 507],[47.6477, -122.6413, "Kitsap", 156, 2],[47.175, -120.9319, "Kittitas", 40, 0],[45.6599, -120.9698, "Klickitat", 20, 3],[46.7225, -122.9695, "Lewis", 30, 3],[47.3048, -117.9713, "Lincoln", 2, 0],[47.3475, -123.0952, "Mason", 28, 1],[48.0536, -119.8994, "Okanogan", 27, 2],[47.0676, -122.1295, "Pierce", 1718, 62],[48.5324, -123.0655, "San Juan", 15, 0],[48.4242, -121.7114, "Skagit", 402, 14],[45.6425, -121.9689, "Skamania", 3, 0],[48.033, -121.8339, "Snohomish", 2970, 118],[47.4513, -117.1307, "Spokane", 390, 29],[48.2929, -117.7336, "Stevens", 10, 1],[46.8646, -122.7696, "Thurston", 123, 1],[46.1991, -118.9728, "Walla Walla", 104, 2],[48.8787, -121.9719, "Whatcom", 338, 34],[47.0887, -117.0464, "Whitman", 16, 0],[46.7026, -120.756, "Yakima", 1966, 63],[46.3076, -123.6344, "Wahkiakum", 4, 0],[48.1788, -117.0545, "Pend Oreille", 2, 0],[46.4152, -117.0502, "Asotin", 18, 2],[46.6755, -123.6648, "Pacific", 9, 0],
    ]);
    var options = {
      backgroundColor: {fill:'transparent',stroke:'#FFF' ,strokeWidth:0 }, 
      displayMode: 'markers',
      region: 'US-WA', 
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
      [{v:"Adams", f:"Adams"}, 49, 0, 49, 0, 0, 0],[{v:"Benton", f:"Benton"}, 719, 14, 665, 54, 3, 0],[{v:"Chelan", f:"Chelan"}, 153, 1, 147, 6, 0, 0],[{v:"Clallam", f:"Clallam"}, 19, 0, 9, 0, 0, 10],[{v:"Clark", f:"Clark"}, 386, 11, 362, 24, 1, 0],[{v:"Columbia", f:"Columbia"}, 1, 0, 0, 0, 0, 1],[{v:"Cowlitz", f:"Cowlitz"}, 66, 0, 66, 0, 0, 0],[{v:"Douglas", f:"Douglas"}, 117, 0, 115, 2, 0, 0],[{v:"Ferry", f:"Ferry"}, 1, 0, 1, 0, 0, 0],[{v:"Franklin", f:"Franklin"}, 525, 9, 509, 16, 0, 0],[{v:"Grant", f:"Grant"}, 219, 0, 164, 3, 0, 52],[{v:"Grays Harbor", f:"Grays Harbor"}, 14, 0, 14, 0, 0, 0],[{v:"Island", f:"Island"}, 179, 0, 170, 9, 0, 0],[{v:"Jefferson", f:"Jefferson"}, 29, 0, 29, 0, 0, 0],[{v:"King", f:"King"}, 7434, 69, 6927, 507, 5, 0],[{v:"Kitsap", f:"Kitsap"}, 156, 0, 154, 2, 0, 0],[{v:"Kittitas", f:"Kittitas"}, 40, 0, 28, 0, 0, 12],[{v:"Klickitat", f:"Klickitat"}, 20, 0, 7, 3, 0, 10],[{v:"Lewis", f:"Lewis"}, 30, 0, 27, 3, 0, 0],[{v:"Lincoln", f:"Lincoln"}, 2, 0, 1, 0, 0, 1],[{v:"Mason", f:"Mason"}, 28, 0, 27, 1, 0, 0],[{v:"Okanogan", f:"Okanogan"}, 27, 0, 12, 2, 0, 13],[{v:"Pierce", f:"Pierce"}, 1718, 24, 1656, 62, 2, 0],[{v:"San Juan", f:"San Juan"}, 15, 0, 15, 0, 0, 0],[{v:"Skagit", f:"Skagit"}, 402, 0, 307, 14, 0, 81],[{v:"Skamania", f:"Skamania"}, 3, 0, 3, 0, 0, 0],[{v:"Snohomish", f:"Snohomish"}, 2970, 38, 1324, 118, 2, 1528],[{v:"Spokane", f:"Spokane"}, 390, 4, 361, 29, 1, 0],[{v:"Stevens", f:"Stevens"}, 10, 0, 9, 1, 0, 0],[{v:"Thurston", f:"Thurston"}, 123, 0, 40, 1, 0, 82],[{v:"Walla Walla", f:"Walla Walla"}, 104, 1, 87, 2, 0, 15],[{v:"Whatcom", f:"Whatcom"}, 338, 0, 304, 34, 0, 0],[{v:"Whitman", f:"Whitman"}, 16, 0, 16, 0, 0, 0],[{v:"Yakima", f:"Yakima"}, 1966, 102, 1903, 63, 1, 0],[{v:"Wahkiakum", f:"Wahkiakum"}, 4, 0, 4, 0, 0, 0],[{v:"Pend Oreille", f:"Pend Oreille"}, 2, 0, 2, 0, 0, 0],[{v:"Asotin", f:"Asotin"}, 18, 0, 16, 2, 0, 0],[{v:"Pacific", f:"Pacific"}, 9, 0, 9, 0, 0, 0],
    ]);
    data.setProperty(0, 0, 'style', 'min-width:100px');
    var table = new google.visualization.Table(document.getElementById('geo_table'));
    table.draw(data, {allowHtml: true, sortColumn: 2, sortAscending: false, width: '660px', height: '100%'});
  }
</script>

<span style="font-size: 13px">All COVID-19 data displayed on the page is available through our FREE <a href="https://developer.smartable.ai">API program</a>. This US - Washington State Coronavirus (COVID-19) Live Stats is refreshed every hour using credible data sources, including the country/state's official government website, <a href="https://en.wikipedia.org/wiki/2019%E2%80%9320_coronavirus_pandemic" target="_blank">data available on wikipedia pages</a>, latest news reports, <a href="https://systems.jhu.edu/research/public-health/ncov/" target="_blank">Johns Hopkins University CSSE 2019-nCoV Dashboard</a>, <a href="https://www.who.int/emergencies/diseases/novel-coronavirus-2019/situation-reports" target="_blank">WHO Situation Reports</a>, <a href="https://www.cdc.gov/coronavirus/2019-ncov/index.html" target="_blank">CDC Situation Updates</a>, and <a href="https://ncov.dxy.cn/ncovh5/view/pneumonia" target="_blank">DXY.cn</a>.</span>

<h2 id="news" class="center" style="margin-top: 60px; font-size: 25px;">Local Government Help Information</h2>
<div class="info center">
<a href="https://www.doh.wa.gov/Emergencies/Coronavirus" target="_blank">Washington State Department of Health</a> 800-525-0127<br /><a href="https://www.kingcounty.gov/depts/health/communicable-diseases/disease-control/novel-coronavirus.aspx" target="_blank">Seattle & King County Public Health</a> 206-477-3977<br /><a href="https://www.snohd.org/484/Novel-Coronavirus-2019" target="_blank">Snohomish Health District</a> 800-525-0127
</div>
<h2 id="news" class="center" style="margin-top: 60px; font-size: 25px;">Trending Coronavirus News in US-Washington</h2>
<div class="row">
<div class="col-md-6 col-sm-12">
  <div class="content-card">
	<a href="https://www.thenewstribune.com/news/coronavirus/article242628041.html"><div class="card-image" style="background-image: url(https://cf-images.us-east-1.prod.boltdns.net/v1/static/5615998020001/7d919262-3f57-45df-9021-1a921d5d3055/0174afbf-2175-48f0-9f8d-cafdb9b2bdbc/1280x720/match/image.jpg)"></div></a>
	<div class="content">
		<div class="card-title"><a href="https://www.thenewstribune.com/news/coronavirus/article242628041.html">Washington state reports 16,674 COVID-19 cases, 921 deaths</a></div>
		<div class="card-excerpt">The Washington State Department of Health reported 286 new COVID-19 cases and 16 additional deaths Saturday. Statewide case totals have reached 16,674, while the state’s death toll is now at 921, up from 16,</div>
		<div class="card-meta">
			<span class="card-provider">News Tribune</span> • <span class="card-date">5/9/2020</span>
		</div>
	</div>
  </div>
</div>
<div class="col-md-6 col-sm-12">
  <div class="content-card">
	<a href="https://www.nbcnews.com/health/health-news/live-blog/2020-05-08-coronavirus-news-n1202636/ncrd1203556"><div class="card-image" style="background-image: url(https://media2.s-nbcnews.com/i/newscms/2020_19/3341911/200508-auburn-washington-al-0802_10738abed84caac74f36558c3b30e360.jpg)"></div></a>
	<div class="content">
		<div class="card-title"><a href="https://www.nbcnews.com/health/health-news/live-blog/2020-05-08-coronavirus-news-n1202636/ncrd1203556">Washington state saw coronavirus infection rate creep back up in April</a></div>
		<div class="card-excerpt">The rate at which infected people infect others with coronavirus in Washington state dropped from around three in March to at or below one, but the rate is estimated to have risen slightly. The governor said it shows social distancing must be maintained.</div>
		<div class="card-meta">
			<span class="card-provider">NBC News</span> • <span class="card-date">5/8/2020</span>
		</div>
	</div>
  </div>
</div>
<div class="col-md-6 col-sm-12">
  <div class="content-card">
	<a href="https://www.kiro7.com/news/local/wa-supreme-court-rejects-plea-release-thousands-inmates-immediately/NELJN77TXBBCLKRFK6ARZFL24Y/"><div class="card-image" style="background-image: url(https://arc-anglerfish-arc2-prod-cmg.s3.amazonaws.com/public/V2IFTWIJ5ZB7LAKX3NWXT5C4AI.jpg)"></div></a>
	<div class="content">
		<div class="card-title"><a href="https://www.kiro7.com/news/local/wa-supreme-court-rejects-plea-release-thousands-inmates-immediately/NELJN77TXBBCLKRFK6ARZFL24Y/">Documents raised questions about FBI handling of Michael Flynn case</a></div>
		<div class="card-excerpt">The Justice Department is filing an emergency request with the U.S. Supreme Court, asking justices to temporarily block the enforcement of an order requiring in the release of secret grand jury materials ... BAIER: Finally tonight, some good news. Students in Washington state still got a chance to celebrate their graduation from their cars.</div>
		<div class="card-meta">
			<span class="card-provider">Fox News</span> • <span class="card-date">5/8/2020</span>
		</div>
	</div>
  </div>
</div>
<div class="col-md-6 col-sm-12">
  <div class="content-card">
	<a href="https://www.kiro7.com/news/local/coronavirus-phase-one-inslees-reopening-plan-begins-tuesday/XIDPHMLVOJAAREQ5YCL75367PU/"><div class="card-image" style="background-image: url(https://www.kiro7.com/resizer/yesUsFg5BBVtPcg1GGa83b98vSs=/1200x628/d1hfln2sfez66z.cloudfront.net/05-08-2020/t_a851c68d0b0f4747bf0b01b94575ba08_name_Crowded_Sign_1152x1536.jpg)"></div></a>
	<div class="content">
		<div class="card-title"><a href="https://www.kiro7.com/news/local/coronavirus-phase-one-inslees-reopening-plan-begins-tuesday/XIDPHMLVOJAAREQ5YCL75367PU/">Coronavirus: ‘Social distancing ambassadors’ will monitor Seattle parks over warm weekend</a></div>
		<div class="card-excerpt">Though officials won't close parks like they did over Easter weekend, there will be measures in place to cut down on crowding during the coronavirus pandemic. About 60 “social distancing ambassadors” will be out to keep people moving at Seattle parks this weekend.</div>
		<div class="card-meta">
			<span class="card-provider">KIRO-TV</span> • <span class="card-date">5/8/2020</span>
		</div>
	</div>
  </div>
</div>
<div class="col-md-6 col-sm-12">
  <div class="content-card">
	<a href="https://www.latimes.com/world-nation/story/2020-04-13/coworkers-save-coronavirus-doctor"><div class="card-image" style="background-image: url(https://ca-times.brightspotcdn.com/dims4/default/38e96f3/2147483647/strip/true/crop/3900x2547+0+26/resize/320x209!/quality/90/?url=https%3A%2F%2Fcalifornia-times-brightspot.s3.amazonaws.com%2Fec%2Ff6%2Ff9bd47364827a36c3a8739541dbf%2Fla-photos-1staff-535886-la-me-longest-stay-covid-patient-5-ajs.jpg)"></div></a>
	<div class="content">
		<div class="card-title"><a href="https://www.latimes.com/world-nation/story/2020-04-13/coworkers-save-coronavirus-doctor">Opinion: Remdesivir helps beat COVID-19. But the search for a better drug goes on</a></div>
		<div class="card-excerpt">The FDA issued emergency authorization for the drug and attempts are being made to ramp up production after Dr. Anthony Fauci, who leads the National Institute of Allergy and Infectious Diseases, extolled the results,</div>
		<div class="card-meta">
			<span class="card-provider">Los Angeles Times</span> • <span class="card-date">5/8/2020</span>
		</div>
	</div>
  </div>
</div>
<div class="col-md-6 col-sm-12">
  <div class="content-card">
	<a href="https://www.kiro7.com/news/local/20-miles-stay-healthy-streets-close-permanently-seattle/EKK2NVSK4VAIRCY3D2C6NUJZKQ/"><div class="card-image" style="background-image: url(https://arc-anglerfish-arc2-prod-cmg.s3.amazonaws.com/public/ZNPGU5WYZJDAFG7UI3AY4HX5LQ.jpg)"></div></a>
	<div class="content">
		<div class="card-title"><a href="https://www.kiro7.com/news/local/20-miles-stay-healthy-streets-close-permanently-seattle/EKK2NVSK4VAIRCY3D2C6NUJZKQ/">Seattle to permanently close 20 miles of streets to traffic so residents can exercise and bike on them</a></div>
		<div class="card-excerpt">Seattle residents will have more space to exercise and bike on as the city plans to permanently close 20 miles of streets to most vehicular traffic, the mayor announced Thursday.</div>
		<div class="card-meta">
			<span class="card-provider">CNN</span> • <span class="card-date">5/7/2020</span>
		</div>
	</div>
  </div>
</div>
<div class="col-md-6 col-sm-12">
  <div class="content-card">
	<a href="https://www.kiro7.com/news/local/seattle-researchers-hope-llama-antibodies-lead-coronavirus-treatment/DZT7GXRGGFB4HMCXTC2B7DJK5I/"><div class="card-image" style="background-image: url(https://www.kiro7.com/resizer/6zXcRRUbqXAB0v-pPd_HIpUTut8=/1200x628/d1hfln2sfez66z.cloudfront.net/05-08-2020/t_f4d9a8c40a8243a1bd0f4fc696ecc78b_name_Llamas_transfer.jpg)"></div></a>
	<div class="content">
		<div class="card-title"><a href="https://www.kiro7.com/news/local/seattle-researchers-hope-llama-antibodies-lead-coronavirus-treatment/DZT7GXRGGFB4HMCXTC2B7DJK5I/">Seattle researchers hope llama antibodies lead to coronavirus treatment</a></div>
		<div class="card-excerpt">"This strange property of producing these small simple antibodies," said John Aitchison of Seattle Children's Research Institute. That means llamas hold great promise in the fight against the coronavirus.</div>
		<div class="card-meta">
			<span class="card-provider">KIRO-TV</span> • <span class="card-date">5/7/2020</span>
		</div>
	</div>
  </div>
</div>
<div class="col-md-6 col-sm-12">
  <div class="content-card">
	<a href="https://www.kiro7.com/news/local/coronavirus-phase-one-inslees-reopening-plan-begins-tuesday/XIDPHMLVOJAAREQ5YCL75367PU/"><div class="card-image" style="background-image: url(https://www.kiro7.com/resizer/FONKWleqIUN4Kg4Suw7COZuTnAc=/1200x628/d1hfln2sfez66z.cloudfront.net/05-07-2020/t_e3d78f8bf0ca4051916c462a8fa78bbe_name_brown_bear_car_wash.jpg)"></div></a>
	<div class="content">
		<div class="card-title"><a href="https://www.kiro7.com/news/local/coronavirus-phase-one-inslees-reopening-plan-begins-tuesday/XIDPHMLVOJAAREQ5YCL75367PU/">Coronavirus: Some businesses allowed to reopen; others still waiting on state</a></div>
		<div class="card-excerpt">Some car and boat sales will reopen Thursday after receiving guidance from Gov. Jay Inslee for vehicle and vessel sales under the Safe Start Phase 1 recovery plan. Businesses that meet the criteria in the guidance can reopen.</div>
		<div class="card-meta">
			<span class="card-provider">KIRO-TV</span> • <span class="card-date">5/7/2020</span>
		</div>
	</div>
  </div>
</div>
<div class="col-md-6 col-sm-12">
  <div class="content-card">
	<a href="https://www.cnn.com/2020/05/07/us/washington-retracts-walla-walla-covid-19-parties-trnd/index.html"><div class="card-image" style="background-image: url(https://cdn.cnn.com/cnnnext/dam/assets/200506184918-walla-walla-county-super-tease.jpg)"></div></a>
	<div class="content">
		<div class="card-title"><a href="https://www.cnn.com/2020/05/07/us/washington-retracts-walla-walla-covid-19-parties-trnd/index.html">Those partygoers in Washington state weren't trying to get Covid-19 after all</a></div>
		<div class="card-excerpt">Earlier this week, health officials in a Washington county warned about reports of people attending gatherings to purposely get infected with Covid-19. Now, they say partygoers weren't intentionally trying to contract the disease.</div>
		<div class="card-meta">
			<span class="card-provider">CNN</span> • <span class="card-date">5/7/2020</span>
		</div>
	</div>
  </div>
</div>
<div class="col-md-6 col-sm-12">
  <div class="content-card">
	<a href="https://www.seattletimes.com/education-lab/as-they-brace-for-budget-strain-washington-state-school-districts-will-receive-some-coronavirus-aid/"><div class="card-image" style="background-image: url(https://static.seattletimes.com/wp-content/uploads/2020/05/05062020_teaser_tzr_151340-780x501.jpg)"></div></a>
	<div class="content">
		<div class="card-title"><a href="https://www.seattletimes.com/education-lab/as-they-brace-for-budget-strain-washington-state-school-districts-will-receive-some-coronavirus-aid/">As they brace for budget strain, Washington state school districts will receive some coronavirus aid</a></div>
		<div class="card-excerpt">State officials are now deciding how best to spend the money this summer, which is part of a $2.2 trillion aid package approved by Congress through the Coronavirus Aid, Relief and Economic Security Act (CARES) last month.</div>
		<div class="card-meta">
			<span class="card-provider">Seattle Times</span> • <span class="card-date">5/7/2020</span>
		</div>
	</div>
  </div>
</div>

</div>

