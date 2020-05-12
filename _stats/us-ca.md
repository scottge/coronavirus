---
category: stats
title: "US - California State Coronavirus (COVID-19) Live Stats"
excerpt: "Live stats of COVID-19 in US-California. Total Cases: 69203 (+1203), Deaths: 2778 (+35), Recoveries: 11128(+148)."
publishedDateTime: 2020-05-12T00:45:10Z
updatedDateTime: 2020-05-12T00:45:10Z
webUrl: "https://smartable.ai/apps/coronavirus/stats/us-ca/"
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
  - url: "https://smartable.azureedge.net/coronavirus/sites/2/2020/us-ca.jpg"
    width: 900
    height: 564
    title: "US - California State Coronavirus (COVID-19) Live Stats"

---
<div class="total-stats" style="text-align: center;">
    <h3>
	    <div style="font-size: 18px; font-weight: 400;">Total Confirmed Cases:</div>
	    69203 (<span class='red'>+1203</span>)
    </h3>
    <h3>
	    <div style="font-size: 18px; font-weight: 400;">Total Deaths:</div>
	    2778 (<span class='red'>+35</span>)
    </h3>
    <h3>
	    <div style="font-size: 18px; font-weight: 400;">Total Recovered:</div>
	    11128 (<span class='green'>+148</span>)
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
      ['1/22/2020', 0, 0, 0],['1/23/2020', 0, 0, 0],['1/24/2020', 0, 0, 0],['1/25/2020', 0, 0, 0],['1/26/2020', 2, 0, 0],['1/27/2020', 2, 0, 0],['1/28/2020', 2, 0, 0],['1/29/2020', 2, 0, 0],['1/30/2020', 2, 0, 0],['1/31/2020', 3, 0, 0],['2/1/2020', 3, 0, 0],['2/2/2020', 3, 0, 0],['2/3/2020', 6, 0, 0],['2/4/2020', 6, 0, 0],['2/5/2020', 6, 0, 0],['2/6/2020', 6, 0, 0],['2/7/2020', 6, 0, 0],['2/8/2020', 6, 0, 0],['2/9/2020', 6, 0, 0],['2/10/2020', 6, 0, 0],['2/11/2020', 7, 0, 0],['2/12/2020', 7, 0, 0],['2/13/2020', 8, 0, 0],['2/14/2020', 8, 0, 0],['2/15/2020', 8, 0, 0],['2/16/2020', 8, 0, 0],['2/17/2020', 8, 0, 0],['2/18/2020', 8, 0, 0],['2/19/2020', 8, 0, 0],['2/20/2020', 8, 0, 0],['2/21/2020', 10, 0, 2],['2/22/2020', 10, 0, 2],['2/23/2020', 10, 0, 2],['2/24/2020', 10, 0, 2],['2/25/2020', 10, 0, 2],['2/26/2020', 10, 0, 2],['2/27/2020', 11, 0, 2],['2/28/2020', 11, 0, 2],['2/29/2020', 12, 0, 2],['3/1/2020', 12, 0, 2],['3/2/2020', 21, 0, 2],['3/3/2020', 25, 0, 2],['3/4/2020', 35, 1, 2],['3/5/2020', 51, 1, 2],['3/6/2020', 59, 1, 2],['3/7/2020', 81, 1, 2],['3/8/2020', 95, 1, 2],['3/9/2020', 101, 1, 2],['3/10/2020', 143, 2, 2],['3/11/2020', 174, 4, 5],['3/12/2020', 243, 4, 6],['3/13/2020', 301, 5, 6],['3/14/2020', 371, 5, 6],['3/15/2020', 454, 6, 6],['3/16/2020', 564, 11, 6],['3/17/2020', 718, 13, 6],['3/18/2020', 861, 16, 6],['3/19/2020', 1047, 19, 6],['3/20/2020', 1249, 24, 6],['3/21/2020', 1515, 28, 6],['3/22/2020', 1811, 35, 6],['3/23/2020', 2212, 43, 6],['3/24/2020', 2628, 54, 6],['3/25/2020', 3169, 67, 6],['3/26/2020', 4040, 82, 6],['3/27/2020', 4885, 102, 6],['3/28/2020', 5636, 120, 6],['3/29/2020', 6319, 132, 6],['3/30/2020', 7394, 149, 33],['3/31/2020', 8558, 182, 33],['4/1/2020', 9907, 216, 111],['4/2/2020', 11126, 244, 164],['4/3/2020', 12507, 279, 212],['4/4/2020', 13878, 322, 257],['4/5/2020', 15158, 349, 278],['4/6/2020', 16349, 388, 285],['4/7/2020', 17625, 452, 341],['4/8/2020', 19031, 507, 430],['4/9/2020', 20169, 547, 705],['4/10/2020', 21393, 599, 779],['4/11/2020', 22416, 634, 873],['4/12/2020', 23296, 682, 913],['4/13/2020', 24372, 732, 1051],['4/14/2020', 25779, 790, 1256],['4/15/2020', 26940, 880, 1258],['4/16/2020', 28157, 973, 1473],['4/17/2020', 29425, 1057, 2560],['4/18/2020', 30812, 1148, 2740],['4/19/2020', 31531, 1180, 3053],['4/20/2020', 33866, 1229, 3337],['4/21/2020', 35845, 1326, 3345],['4/22/2020', 37701, 1439, 3580],['4/23/2020', 39561, 1533, 3582],['4/24/2020', 40834, 1597, 3614],['4/25/2020', 42596, 1695, 3614],['4/26/2020', 43700, 1723, 3614],['4/27/2020', 45178, 1787, 3614],['4/28/2020', 46433, 1877, 3614],['4/29/2020', 48764, 1958, 3614],['4/30/2020', 50410, 2044, 3614],['5/1/2020', 51865, 2105, 3761],['5/2/2020', 53670, 2192, 3908],['5/3/2020', 54941, 2228, 4057],['5/4/2020', 56112, 2292, 7564],['5/5/2020', 58625, 2386, 8110],['5/6/2020', 60653, 2470, 9332],['5/7/2020', 62477, 2554, 9728],['5/8/2020', 64475, 2635, 10134],['5/9/2020', 66687, 2710, 10352],['5/10/2020', 68000, 2743, 10980],['5/11/2020', 69203, 2778, 11128],
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
      [37.6017, -121.7195, "Alameda", 2085, 75],[38.419, -120.8232, "Amador", 16, 0],[39.4261, -121.3542, "Butte", 19, 0],[38.196, -120.6805, "Calaveras", 13, 0],[39.0742, -121.8988, "Colusa", 3, 0],[37.8534, -121.9018, "Contra Costa", 1048, 32],[38.675, -121.049, "El Dorado", 54, 0],[36.9859, -119.2321, "Fresno", 885, 9],[39.5149, -122.1995, "Glenn", 6, 0],[40.745, -123.8695, "Humboldt", 57, 0],[33.3548, -115.7306, "Imperial", 512, 12],[37.4189, -118.5424, "Inyo", 20, 1],[35.6411, -118.4047, "Kern", 1264, 16],[36.303, -119.637, "Kings", 287, 1],[34.0522, -118.2437, "Los Angeles", 31703, 1531],[37.2519, -119.6963, "Madera", 67, 2],[38.0834, -122.7633, "Marin", 261, 14],[39.4429, -123.3963, "Mendocino", 40, 0],[37.4306, -120.7759, "Merced", 163, 3],[38.5834, -119.516, "Mono", 29, 1],[36.6247, -121.6465, "Monterey", 279, 6],[38.5063, -122.4682, "Napa", 79, 2],[39.3718, -121.106, "Nevada", 41, 1],[33.7879, -117.8531, "Orange", 3506, 76],[39.0916, -120.8039, "Placer", 169, 8],[33.9533, -117.3961, "Riverside", 5039, 205],[38.4747, -121.3542, "Sacramento", 1167, 50],[36.5761, -120.9876, "San Benito", 55, 2],[34.0714, -117.6981, "San Bernardino", 2964, 114],[32.7157, -117.1611, "San Diego", 4989, 194],[37.7749, -122.4194, "San Francisco", 1946, 34],[36.6066, -120.189, "San Joaquin", 612, 29],[35.7309, -120.8702, "San Luis Obispo", 220, 1],[37.563, -122.3255, "San Mateo", 1453, 65],[34.4382, -119.6286, "Santa Barbara", 1308, 11],[37.3541, -121.9552, "Santa Clara", 2339, 129],[37.0454, -121.958, "Santa Cruz", 141, 2],[40.7909, -121.8474, "Shasta", 31, 4],[41.6086, -122.8409, "Siskiyou", 5, 0],[38.3105, -121.9018, "Solano", 356, 7],[38.578, -122.9888, "Sonoma", 309, 4],[37.5091, -120.9876, "Stanislaus", 501, 21],[39.2788, -121.6624, "Sutter", 45, 3],[36.379, -119.0312, "Tulare", 1140, 48],[34.3705, -119.1391, "Ventura", 679, 19],[38.7646, -121.9018, "Yolo", 173, 20],[39.3204, -121.4038, "Yuba", 20, 1],[37.8703, -120.4443, "Tuolumne", 4, 0],[38.8103, -119.8033, "Alpine", 8, 0],[40.0059, -120.9525, "Plumas", 4, 0],[41.5322, -124.0063, "Del Norte", 3, 0],[40.027, -122.0981, "Tehama", 1, 1],[38.8356, -122.723, "Lake", 8, 0],[37.4893626, -119.9679294, "Mariposa", 15, 0],[40.6329485, -123.0622553, "Trinity", 1, 0],
    ]);
    var options = {
      backgroundColor: {fill:'transparent',stroke:'#FFF' ,strokeWidth:0 }, 
      displayMode: 'markers',
      region: 'US-CA', 
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
      [{v:"Alameda", f:"Alameda"}, 2085, 21, 2010, 75, 3, 0],[{v:"Amador", f:"Amador"}, 16, 0, 13, 0, 0, 3],[{v:"Butte", f:"Butte"}, 19, 0, 19, 0, 0, 0],[{v:"Calaveras", f:"Calaveras"}, 13, 0, 11, 0, 0, 2],[{v:"Colusa", f:"Colusa"}, 3, 0, 3, 0, 0, 0],[{v:"Contra Costa", f:"Contra Costa"}, 1048, 0, 1016, 32, 0, 0],[{v:"El Dorado", f:"El Dorado"}, 54, 0, 38, 0, 0, 16],[{v:"Fresno", f:"Fresno"}, 885, 0, 791, 9, 0, 85],[{v:"Glenn", f:"Glenn"}, 6, 0, 4, 0, 0, 2],[{v:"Humboldt", f:"Humboldt"}, 57, 0, 7, 0, 0, 50],[{v:"Imperial", f:"Imperial"}, 512, 0, 439, 12, 0, 61],[{v:"Inyo", f:"Inyo"}, 20, 0, 19, 1, 0, 0],[{v:"Kern", f:"Kern"}, 1264, 10, 1014, 16, 0, 234],[{v:"Kings", f:"Kings"}, 287, 0, 286, 1, 0, 0],[{v:"Los Angeles", f:"Los Angeles"}, 31703, 0, 29940, 1531, 0, 232],[{v:"Madera", f:"Madera"}, 67, 0, 54, 2, 0, 11],[{v:"Marin", f:"Marin"}, 261, 0, 247, 14, 0, 0],[{v:"Mendocino", f:"Mendocino"}, 40, 0, 36, 0, 0, 4],[{v:"Merced", f:"Merced"}, 163, 0, 144, 3, 0, 16],[{v:"Mono", f:"Mono"}, 29, 0, 28, 1, 0, 0],[{v:"Monterey", f:"Monterey"}, 279, 0, 249, 6, 0, 24],[{v:"Napa", f:"Napa"}, 79, 0, 77, 2, 0, 0],[{v:"Nevada", f:"Nevada"}, 41, 0, 40, 1, 0, 0],[{v:"Orange", f:"Orange"}, 3506, 4, 3430, 76, 0, 0],[{v:"Placer", f:"Placer"}, 169, 0, 161, 8, 0, 0],[{v:"Riverside", f:"Riverside"}, 5039, 0, 4134, 205, 0, 700],[{v:"Sacramento", f:"Sacramento"}, 1167, 0, 1117, 50, 0, 0],[{v:"San Benito", f:"San Benito"}, 55, 0, 13, 2, 0, 40],[{v:"San Bernardino", f:"San Bernardino"}, 2964, 0, 2850, 114, 0, 0],[{v:"San Diego", f:"San Diego"}, 4989, 63, 3657, 194, 0, 1138],[{v:"San Francisco", f:"San Francisco"}, 1946, 3, 1912, 34, 0, 0],[{v:"San Joaquin", f:"San Joaquin"}, 612, 0, 583, 29, 0, 0],[{v:"San Luis Obispo", f:"San Luis Obispo"}, 220, 0, 108, 1, 0, 111],[{v:"San Mateo", f:"San Mateo"}, 1453, 28, 1388, 65, 8, 0],[{v:"Santa Barbara", f:"Santa Barbara"}, 1308, 0, 1128, 11, 0, 169],[{v:"Santa Clara", f:"Santa Clara"}, 2339, 0, 2209, 129, 0, 1],[{v:"Santa Cruz", f:"Santa Cruz"}, 141, 0, 91, 2, 0, 48],[{v:"Shasta", f:"Shasta"}, 31, 0, 21, 4, 0, 6],[{v:"Siskiyou", f:"Siskiyou"}, 5, 0, 2, 0, 0, 3],[{v:"Solano", f:"Solano"}, 356, 0, 206, 7, 0, 143],[{v:"Sonoma", f:"Sonoma"}, 309, 0, 196, 4, 0, 109],[{v:"Stanislaus", f:"Stanislaus"}, 501, 0, 386, 21, 0, 94],[{v:"Sutter", f:"Sutter"}, 45, 0, 10, 3, 0, 32],[{v:"Tulare", f:"Tulare"}, 1140, 0, 1037, 48, 0, 55],[{v:"Ventura", f:"Ventura"}, 679, 13, 438, 19, 0, 222],[{v:"Yolo", f:"Yolo"}, 173, 0, 153, 20, 0, 0],[{v:"Yuba", f:"Yuba"}, 20, 0, 19, 1, 0, 0],[{v:"Tuolumne", f:"Tuolumne"}, 4, 0, 4, 0, 0, 0],[{v:"Alpine", f:"Alpine"}, 8, 0, 7, 0, 0, 1],[{v:"Plumas", f:"Plumas"}, 4, 0, 4, 0, 0, 0],[{v:"Del Norte", f:"Del Norte"}, 3, 0, 1, 0, 0, 2],[{v:"Tehama", f:"Tehama"}, 1, 0, 0, 1, 0, 0],[{v:"Lake", f:"Lake"}, 8, 0, 8, 0, 0, 0],[{v:"Mariposa", f:"Mariposa"}, 15, 0, 15, 0, 0, 0],[{v:"Trinity", f:"Trinity"}, 1, 0, 1, 0, 0, 0],
    ]);
    data.setProperty(0, 0, 'style', 'min-width:100px');
    var table = new google.visualization.Table(document.getElementById('geo_table'));
    table.draw(data, {allowHtml: true, sortColumn: 2, sortAscending: false, width: '660px', height: '100%'});
  }
</script>

<span style="font-size: 13px">All COVID-19 data displayed on the page is available through our FREE <a href="https://developer.smartable.ai">API program</a>. This US - California State Coronavirus (COVID-19) Live Stats is refreshed every hour using credible data sources, including the country/state's official government website, <a href="https://en.wikipedia.org/wiki/2019%E2%80%9320_coronavirus_pandemic" target="_blank">data available on wikipedia pages</a>, latest news reports, <a href="https://systems.jhu.edu/research/public-health/ncov/" target="_blank">Johns Hopkins University CSSE 2019-nCoV Dashboard</a>, <a href="https://www.who.int/emergencies/diseases/novel-coronavirus-2019/situation-reports" target="_blank">WHO Situation Reports</a>, <a href="https://www.cdc.gov/coronavirus/2019-ncov/index.html" target="_blank">CDC Situation Updates</a>, and <a href="https://ncov.dxy.cn/ncovh5/view/pneumonia" target="_blank">DXY.cn</a>.</span>

<h2 id="news" class="center" style="margin-top: 60px; font-size: 25px;">Local Government Help Information</h2>
<div class="info center">
<a href="https://www.cdph.ca.gov/Programs/CID/DCDC/Pages/Immunization/ncov2019.aspx" target="_blank" rel="noopener noreferrer">California Department of Public Health</a><br /><a href="http://www.ochealthinfo.com/phs/about/epidasmt/epi/dip/prevention/novel_coronavirus" target="_blank" rel="noopener noreferrer">Orange County Coronavirus Information</a> (800) 564-8448<br /><a href="https://www.sccgov.org/sites/phd/DiseaseInformation/novel-coronavirus/Pages/home.aspx" target="_blank" rel="noopener noreferrer">Santa Clara County Coronavirus Information</a> 408- 885-3980
</div>
<h2 id="news" class="center" style="margin-top: 60px; font-size: 25px;">Trending Coronavirus News in US-California</h2>
<div class="row">
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
	<a href="https://www.usatoday.com/story/news/politics/elections/2020/05/08/coronavirus-california-send-mail-ballots-every-voter/3101522001/"><div class="card-image" style="background-image: url(https://www.gannett-cdn.com/presto/2020/05/08/PPAS/6dd28a9b-e07b-4b54-9a20-a33ffd8cd4a5-AP20129791254453.jpg?auto=webp&crop=5471,3078,x0,y182&format=pjpg&width=1200)"></div></a>
	<div class="content">
		<div class="card-title"><a href="https://www.usatoday.com/story/news/politics/elections/2020/05/08/coronavirus-california-send-mail-ballots-every-voter/3101522001/">Locked-down California to send mail-in ballots to every voter</a></div>
		<div class="card-excerpt">California Gov. Gavin Newsom on Friday announced the state will send every voter a mail-in ballot for the November elections.</div>
		<div class="card-meta">
			<span class="card-provider">USA Today</span> • <span class="card-date">5/8/2020</span>
		</div>
	</div>
  </div>
</div>
<div class="col-md-6 col-sm-12">
  <div class="content-card">
	<a href="https://www.reuters.com/article/us-health-coronavirus-usa-california-idUSKBN22K2T3"><div class="card-image" style="background-image: url(https://s2.reutersmedia.net/resources/r/?m=02&d=20200508&t=2&i=1517990669&w=&fh=545px&fw=&ll=&pl=&sq=&r=LYNXMPEG471UH)"></div></a>
	<div class="content">
		<div class="card-title"><a href="https://www.reuters.com/article/us-health-coronavirus-usa-california-idUSKBN22K2T3">California first state to promise mail-in ballots to all 2020 voters</a></div>
		<div class="card-excerpt">California on Friday became the first state to commit to sending mail-in ballots to all registered voters for the November election as a result of the coronavirus pandemic to safeguard voter access and public safety.</div>
		<div class="card-meta">
			<span class="card-provider">Reuters</span> • <span class="card-date">5/8/2020</span>
		</div>
	</div>
  </div>
</div>
<div class="col-md-6 col-sm-12">
  <div class="content-card">
	<a href="https://www.cbsnews.com/news/ice-death-immigrant-custody-dies-california/"><div class="card-image" style="background-image: url(https://cbsnews3.cbsistatic.com/hub/i/r/2020/04/30/fd9980db-a48b-4092-89b6-4661a00dcb6a/thumbnail/1200x630/146478ecb90a7ae8c564bd006f910953/ap-19243607890380.jpg)"></div></a>
	<div class="content">
		<div class="card-title"><a href="https://www.cbsnews.com/news/ice-death-immigrant-custody-dies-california/">Immigrant in ICE custody dies from coronavirus complications in California</a></div>
		<div class="card-excerpt">The 57-year-old immigrant died Wednesday morning in a San Diego-area hospital after being transferred in April from the privately operated Otay Mesa detention center, the epicenter of coronavirus cases inside the nation's immigration detention system,</div>
		<div class="card-meta">
			<span class="card-provider">CBS News</span> • <span class="card-date">5/8/2020</span>
		</div>
	</div>
  </div>
</div>
<div class="col-md-6 col-sm-12">
  <div class="content-card">
	<a href="https://www.foxnews.com/science/san-francisco-covid-19-testing-reveals-stark-burden-on-the-poor-and-marginalized"><div class="card-image" style="background-image: url(https://a57.foxnews.com/static.foxnews.com/foxnews.com/content/uploads/2018/11/640/320/iStock-900506258.jpg?ve=1&tl=1)"></div></a>
	<div class="content">
		<div class="card-title"><a href="https://www.foxnews.com/science/san-francisco-covid-19-testing-reveals-stark-burden-on-the-poor-and-marginalized">San Francisco COVID-19 testing reveals stark burden on the poor and marginalized</a></div>
		<div class="card-excerpt">A COVID-19 mass testing effort within San Francisco's Mission District  — which aimed to broadly test individuals regardless of symptoms  — found stark inequalities in how the virus is affecting different groups.</div>
		<div class="card-meta">
			<span class="card-provider">Fox News</span> • <span class="card-date">5/8/2020</span>
		</div>
	</div>
  </div>
</div>
<div class="col-md-6 col-sm-12">
  <div class="content-card">
	<a href="https://www.sfgate.com/news/article/138-employees-at-meat-plant-test-positive-for-15254451.php"><div class="card-image" style="background-image: url(https://s.hdnux.com/photos/01/11/75/43/19388648/3/375x250.jpg)"></div></a>
	<div class="content">
		<div class="card-title"><a href="https://www.sfgate.com/news/article/138-employees-at-meat-plant-test-positive-for-15254451.php">138 employees at California meat plant test positive for coronavirus</a></div>
		<div class="card-excerpt">At least 138 employees at a meat packing plant in central California have tested positive for the coronavirus, officials said. Kings County Supervisor Doug Verboon told the Fresno Bee that the outbreak at Central Valley Meat Company in Hanford now accounts for nearly two-thirds of the coronavirus cases in the rural county,</div>
		<div class="card-meta">
			<span class="card-provider">SFGate</span> • <span class="card-date">5/7/2020</span>
		</div>
	</div>
  </div>
</div>
<div class="col-md-6 col-sm-12">
  <div class="content-card">
	<a href="https://www.reuters.com/article/us-health-coronavirus-usa-detention-idUSKBN22J110"><div class="card-image" style="background-image: url(https://s2.reutersmedia.net/resources/r/?m=02&d=20200507&t=2&i=1517815021&w=&fh=545px&fw=&ll=&pl=&sq=&r=LYNXMPEG4619F)"></div></a>
	<div class="content">
		<div class="card-title"><a href="https://www.reuters.com/article/us-health-coronavirus-usa-detention-idUSKBN22J110">First immigrant detainee with COVID-19 dies in U.S. custody in California</a></div>
		<div class="card-excerpt">The first immigrant in U.S. detention with the novel coronavirus died this week, according to federal officials and local health authorities, as infections steadily climbed among the nearly 30,000 migrants in U.</div>
		<div class="card-meta">
			<span class="card-provider">Reuters</span> • <span class="card-date">5/7/2020</span>
		</div>
	</div>
  </div>
</div>
<div class="col-md-6 col-sm-12">
  <div class="content-card">
	<a href="https://www.reuters.com/article/us-health-coronavirus-california-budget-idUSKBN22J2EH"><div class="card-image" style="background-image: url(https://s2.reutersmedia.net/resources/r/?m=02&d=20200507&t=2&i=1517822254&w=&fh=545px&fw=&ll=&pl=&sq=&r=LYNXMPEG461DG)"></div></a>
	<div class="content">
		<div class="card-title"><a href="https://www.reuters.com/article/us-health-coronavirus-california-budget-idUSKBN22J2EH">California predicts $54.3 billion budget deficit due to coronavirus</a></div>
		<div class="card-excerpt">California will face a budget deficit of $54.3 billion due to a huge drop in revenue combined with increased expenses linked to the coronavirus pandemic, according to a projection released Thursday by financial advisers to Governor Gavin Newsom.</div>
		<div class="card-meta">
			<span class="card-provider">Reuters</span> • <span class="card-date">5/7/2020</span>
		</div>
	</div>
  </div>
</div>
<div class="col-md-6 col-sm-12">
  <div class="content-card">
	<a href="https://www.cnbc.com/2020/05/07/coronavirus-latest-updates.html"><div class="card-image" style="background-image: url(https://image.cnbcfm.com/api/v1/image/106526961-1588886277574gettyimages-1210439986.jpeg?v=1588886384)"></div></a>
	<div class="content">
		<div class="card-title"><a href="https://www.cnbc.com/2020/05/07/coronavirus-latest-updates.html">Coronavirus live updates: Moderna vaccine candidate takes 'crucial step,' Germany warns crisis is not over</a></div>
		<div class="card-excerpt">Covid-19 has infected a confirmed 3.7 million people globally, and killed at least 264,111 as of Thursday morning.</div>
		<div class="card-meta">
			<span class="card-provider">CNBC</span> • <span class="card-date">5/7/2020</span>
		</div>
	</div>
  </div>
</div>

</div>

