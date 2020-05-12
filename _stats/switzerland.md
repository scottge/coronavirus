---
category: stats
title: "Switzerland Coronavirus (COVID-19) Live Stats"
excerpt: "Live stats of COVID-19 in Switzerland. Total Cases: 30380 (+36), Deaths: 1867 (+22), Recoveries: 26800(-)."
publishedDateTime: 2020-05-12T23:45:15Z
updatedDateTime: 2020-05-12T23:45:15Z
webUrl: "https://smartable.ai/apps/coronavirus/stats/switzerland/"
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
  - url: "https://smartable.azureedge.net/coronavirus/sites/2/2020/switzerland.jpg"
    width: 900
    height: 564
    title: "Switzerland Coronavirus (COVID-19) Live Stats"

---
<div class="total-stats" style="text-align: center;">
    <h3>
	    <div style="font-size: 18px; font-weight: 400;">Total Confirmed Cases:</div>
	    30380 (<span class='red'>+36</span>)
    </h3>
    <h3>
	    <div style="font-size: 18px; font-weight: 400;">Total Deaths:</div>
	    1867 (<span class='red'>+22</span>)
    </h3>
    <h3>
	    <div style="font-size: 18px; font-weight: 400;">Total Recovered:</div>
	    26800 (-)
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
      ['1/22/2020', 0, 0, 0],['1/23/2020', 0, 0, 0],['1/24/2020', 0, 0, 0],['1/25/2020', 0, 0, 0],['1/26/2020', 0, 0, 0],['1/27/2020', 0, 0, 0],['1/28/2020', 0, 0, 0],['1/29/2020', 0, 0, 0],['1/30/2020', 0, 0, 0],['1/31/2020', 0, 0, 0],['2/1/2020', 0, 0, 0],['2/2/2020', 0, 0, 0],['2/3/2020', 0, 0, 0],['2/4/2020', 0, 0, 0],['2/5/2020', 0, 0, 0],['2/6/2020', 0, 0, 0],['2/7/2020', 0, 0, 0],['2/8/2020', 0, 0, 0],['2/9/2020', 0, 0, 0],['2/10/2020', 0, 0, 0],['2/11/2020', 0, 0, 0],['2/12/2020', 0, 0, 0],['2/13/2020', 0, 0, 0],['2/14/2020', 0, 0, 0],['2/15/2020', 0, 0, 0],['2/16/2020', 0, 0, 0],['2/17/2020', 0, 0, 0],['2/18/2020', 0, 0, 0],['2/19/2020', 0, 0, 0],['2/20/2020', 0, 0, 0],['2/21/2020', 0, 0, 0],['2/22/2020', 0, 0, 0],['2/23/2020', 0, 0, 0],['2/24/2020', 0, 0, 0],['2/25/2020', 1, 0, 0],['2/26/2020', 1, 0, 0],['2/27/2020', 8, 0, 0],['2/28/2020', 8, 0, 0],['2/29/2020', 18, 0, 0],['3/1/2020', 27, 0, 0],['3/2/2020', 42, 0, 0],['3/3/2020', 56, 0, 2],['3/4/2020', 90, 0, 3],['3/5/2020', 114, 1, 3],['3/6/2020', 214, 1, 3],['3/7/2020', 268, 1, 3],['3/8/2020', 337, 2, 3],['3/9/2020', 374, 2, 3],['3/10/2020', 491, 3, 3],['3/11/2020', 652, 4, 4],['3/12/2020', 868, 7, 4],['3/13/2020', 1139, 11, 4],['3/14/2020', 1375, 13, 4],['3/15/2020', 2217, 14, 4],['3/16/2020', 2353, 19, 4],['3/17/2020', 2742, 27, 15],['3/18/2020', 3115, 33, 15],['3/19/2020', 4222, 43, 15],['3/20/2020', 5615, 56, 15],['3/21/2020', 6863, 80, 131],['3/22/2020', 7474, 98, 131],['3/23/2020', 8795, 120, 131],['3/24/2020', 9877, 122, 131],['3/25/2020', 10897, 153, 131],['3/26/2020', 11811, 192, 131],['3/27/2020', 12928, 231, 1530],['3/28/2020', 14076, 264, 1595],['3/29/2020', 14829, 300, 1595],['3/30/2020', 15922, 359, 1823],['3/31/2020', 16605, 433, 1823],['4/1/2020', 17768, 488, 2967],['4/2/2020', 18827, 536, 4013],['4/3/2020', 19606, 591, 4846],['4/4/2020', 20505, 666, 6415],['4/5/2020', 21100, 715, 6415],['4/6/2020', 21657, 765, 8056],['4/7/2020', 22253, 821, 8704],['4/8/2020', 23280, 895, 9800],['4/9/2020', 24051, 948, 10600],['4/10/2020', 24551, 1002, 11100],['4/11/2020', 25107, 1036, 12100],['4/12/2020', 25415, 1106, 12700],['4/13/2020', 25688, 1138, 13700],['4/14/2020', 25936, 1174, 14700],['4/15/2020', 26336, 1239, 15400],['4/16/2020', 26732, 1281, 15900],['4/17/2020', 27078, 1327, 16400],['4/18/2020', 27404, 1368, 17100],['4/19/2020', 27740, 1393, 17800],['4/20/2020', 27944, 1429, 18600],['4/21/2020', 28063, 1478, 19400],['4/22/2020', 28268, 1509, 19900],['4/23/2020', 28496, 1549, 20600],['4/24/2020', 28677, 1589, 21000],['4/25/2020', 28894, 1599, 21300],['4/26/2020', 29061, 1610, 21800],['4/27/2020', 29164, 1665, 22200],['4/28/2020', 29264, 1699, 22600],['4/29/2020', 29407, 1716, 22600],['4/30/2020', 29586, 1737, 23400],['5/1/2020', 29701, 1749, 23800],['5/2/2020', 29817, 1762, 24200],['5/3/2020', 29905, 1762, 24500],['5/4/2020', 29981, 1784, 25200],['5/5/2020', 30009, 1795, 25400],['5/6/2020', 30060, 1805, 25700],['5/7/2020', 30126, 1810, 25900],['5/8/2020', 30207, 1823, 26100],['5/9/2020', 30251, 1830, 26400],['5/10/2020', 30305, 1833, 26600],['5/11/2020', 30344, 1845, 26800],['5/12/2020', 30380, 1867, 26800],
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
      ["Switzerland", 30380, 1867]
    ]);
    var options = {
      backgroundColor: {fill:'transparent',stroke:'#FFF' ,strokeWidth:0 }, 
      region: 'CH',
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



<span style="font-size: 13px">All COVID-19 data displayed on the page is available through our FREE <a href="https://developer.smartable.ai">API program</a>. This Switzerland Coronavirus (COVID-19) Live Stats is refreshed every hour using credible data sources, including the country/state's official government website, <a href="https://en.wikipedia.org/wiki/2019%E2%80%9320_coronavirus_pandemic" target="_blank">data available on wikipedia pages</a>, latest news reports, <a href="https://systems.jhu.edu/research/public-health/ncov/" target="_blank">Johns Hopkins University CSSE 2019-nCoV Dashboard</a>, <a href="https://www.who.int/emergencies/diseases/novel-coronavirus-2019/situation-reports" target="_blank">WHO Situation Reports</a>, <a href="https://www.cdc.gov/coronavirus/2019-ncov/index.html" target="_blank">CDC Situation Updates</a>, and <a href="https://ncov.dxy.cn/ncovh5/view/pneumonia" target="_blank">DXY.cn</a>.</span>

