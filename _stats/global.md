---
category: stats
title: "Global Coronavirus (COVID-19) Live Stats"
excerpt: "Live stats of COVID-19 in the World. Total Cases: 4097208 (+86559), Deaths: 280274 (+4256), Recoveries: 1411928(+53500)."
publishedDateTime: 2020-05-10T05:45:40Z
updatedDateTime: 2020-05-10T05:45:40Z
webUrl: "https://smartable.ai/apps/coronavirus/stats/global/"
type: article
heat: 1000

provider:
  name: Smartable AI
  domain: smartable.ai
  images:
    - url: "https://smartable.azureedge.net/media/2020/02/logo.png"
      width: 50
      height: 50

topics:
  - Coronavirus

images:
  - url: "https://smartable.azureedge.net/coronavirus/sites/2/2020/global.jpg"
    width: 900
    height: 564
    title: "Global Coronavirus (COVID-19) Live Stats"

---
<div class="total-stats" style="text-align: center;">
    <h3>
	    <div style="font-size: 18px; font-weight: 400;">Total Confirmed Cases:</div>
	    4097208 (<span class='red'>+86559</span>)
    </h3>
    <h3>
	    <div style="font-size: 18px; font-weight: 400;">Total Deaths:</div>
	    280274 (<span class='red'>+4256</span>)
    </h3>
    <h3>
	    <div style="font-size: 18px; font-weight: 400;">Total Recovered:</div>
	    1411928 (<span class='green'>+53500</span>)
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
      ['1/22/2020', 554, 17, 28],['1/23/2020', 653, 18, 30],['1/24/2020', 941, 26, 36],['1/25/2020', 1434, 42, 39],['1/26/2020', 2118, 56, 52],['1/27/2020', 2927, 82, 61],['1/28/2020', 5578, 131, 107],['1/29/2020', 6166, 133, 126],['1/30/2020', 8233, 171, 143],['1/31/2020', 9927, 213, 222],['2/1/2020', 12037, 259, 284],['2/2/2020', 16787, 362, 471],['2/3/2020', 19881, 426, 623],['2/4/2020', 23892, 492, 852],['2/5/2020', 27635, 564, 1121],['2/6/2020', 30794, 634, 1487],['2/7/2020', 34391, 719, 2011],['2/8/2020', 37120, 806, 2614],['2/9/2020', 40150, 906, 3244],['2/10/2020', 42762, 1013, 3944],['2/11/2020', 44802, 1113, 4683],['2/12/2020', 45221, 1118, 5151],['2/13/2020', 60368, 1371, 6295],['2/14/2020', 66885, 1523, 8054],['2/15/2020', 69030, 1666, 9395],['2/16/2020', 71224, 1770, 10865],['2/17/2020', 73258, 1868, 12583],['2/18/2020', 75136, 2007, 14352],['2/19/2020', 75639, 2122, 16121],['2/20/2020', 76197, 2247, 18178],['2/21/2020', 76819, 2251, 18890],['2/22/2020', 78572, 2458, 22886],['2/23/2020', 78958, 2469, 23394],['2/24/2020', 79561, 2629, 25228],['2/25/2020', 80406, 2708, 27906],['2/26/2020', 81379, 2770, 30387],['2/27/2020', 82736, 2814, 33280],['2/28/2020', 84102, 2872, 36714],['2/29/2020', 85999, 2941, 39785],['3/1/2020', 88356, 2996, 42719],['3/2/2020', 90293, 3085, 45605],['3/3/2020', 92824, 3160, 48231],['3/4/2020', 95097, 3254, 51173],['3/5/2020', 97859, 3348, 53799],['3/6/2020', 101759, 3460, 55867],['3/7/2020', 105796, 3558, 58361],['3/8/2020', 109758, 3802, 60714],['3/9/2020', 113471, 3988, 62514],['3/10/2020', 118139, 4262, 64406],['3/11/2020', 125774, 4611, 67010],['3/12/2020', 134155, 4976, 69079],['3/13/2020', 145731, 5436, 72505],['3/14/2020', 156873, 5839, 75893],['3/15/2020', 168668, 6516, 77708],['3/16/2020', 182807, 7171, 79832],['3/17/2020', 198674, 7989, 82706],['3/18/2020', 219190, 8966, 85729],['3/19/2020', 245687, 10047, 88425],['3/20/2020', 276386, 11419, 91929],['3/21/2020', 308268, 13073, 95621],['3/22/2020', 339251, 14721, 99048],['3/23/2020', 381628, 16555, 101556],['3/24/2020', 423197, 18924, 108468],['3/25/2020', 472164, 21316, 114588],['3/26/2020', 533644, 24090, 122334],['3/27/2020', 597501, 27375, 131107],['3/28/2020', 665002, 30854, 139541],['3/29/2020', 737292, 34525, 148096],['3/30/2020', 798302, 38268, 160899],['3/31/2020', 869454, 42725, 172531],['4/1/2020', 952771, 47787, 194713],['4/2/2020', 1031327, 53664, 211805],['4/3/2020', 1113671, 59390, 226513],['4/4/2020', 1194673, 65238, 246752],['4/5/2020', 1267735, 69973, 262634],['4/6/2020', 1338712, 75318, 284387],['4/7/2020', 1414326, 82609, 300646],['4/8/2020', 1500008, 88960, 328788],['4/9/2020', 1585405, 96185, 355165],['4/10/2020', 1680140, 103299, 377401],['4/11/2020', 1756993, 109372, 404474],['4/12/2020', 1854028, 114771, 435166],['4/13/2020', 1924537, 120225, 457636],['4/14/2020', 1999887, 127273, 493610],['4/15/2020', 2080939, 135079, 510922],['4/16/2020', 2176752, 143552, 548174],['4/17/2020', 2266531, 154821, 566644],['4/18/2020', 2343146, 161474, 593739],['4/19/2020', 2421344, 165969, 620803],['4/20/2020', 2495422, 171256, 647153],['4/21/2020', 2568640, 178042, 681610],['4/22/2020', 2646686, 184795, 708870],['4/23/2020', 2734566, 191441, 737543],['4/24/2020', 2832547, 197889, 786066],['4/25/2020', 2926221, 203740, 833231],['4/26/2020', 2999132, 207389, 877022],['4/27/2020', 3069410, 212101, 916866],['4/28/2020', 3144395, 218224, 952107],['4/29/2020', 3223810, 228560, 995771],['4/30/2020', 3309963, 234269, 1033606],['5/1/2020', 3393481, 239302, 1070466],['5/2/2020', 3483205, 244858, 1110695],['5/3/2020', 3564075, 248556, 1142380],['5/4/2020', 3640979, 252726, 1183660],['5/5/2020', 3721548, 258245, 1218567],['5/6/2020', 3816803, 264918, 1277832],['5/7/2020', 3913723, 270537, 1317352],['5/8/2020', 4010649, 276018, 1358428],['5/9/2020', 4097208, 280274, 1411928],
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
      ["Afghanistan", 4033, 115],["Albania", 856, 31],["Algeria", 5558, 494],["Andorra", 754, 48],["Angola", 43, 2],["Anguilla", 3, 0],["Antigua and Barbuda", 25, 3],["Argentina", 5776, 300],["Armenia", 3175, 44],["Aruba", 101, 3],["Australia", 6939, 97],["Austria", 15833, 615],["Azerbaijan", 2422, 31],["Bahamas", 92, 11],["Bahrain", 4774, 8],["Bangladesh", 13770, 214],["Barbados", 84, 7],["Belarus", 22052, 126],["Belgium", 52596, 8581],["Belize", 18, 2],["Benin", 284, 2],["Bermuda", 118, 7],["Bhutan", 7, 0],["Bolivia", 2437, 114],["Bosnia and Herzegovina", 2090, 102],["Botswana", 23, 1],["Brazil", 156061, 10656],["British Virgin Islands", 7, 1],["Brunei", 141, 1],["Bulgaria", 1921, 90],["Burkina Faso", 748, 48],["Burma", 178, 6],["Cabo Verde", 236, 2],["Cambodia", 122, 0],["Cameroon", 2274, 108],["Canada", 68920, 4823],["Cape Verde", 1, 0],["CAR", 1, 0],["Cayman Islands", 81, 1],["Central African Republic", 143, 0],["Chad", 322, 31],["Channel Islands", 545, 41],["Chile", 27219, 304],["China", 83992, 4637],["Colombia", 10495, 445],["Costa Rica", 780, 6],["Cote d'Ivoire", 1667, 21],["Croatia", 2176, 87],["Cruise Ship: Diamond Princess", 712, 13],["Cuba", 1754, 74],["Curacao", 16, 1],["Cyprus", 892, 15],["Czechia", 8095, 276],["Democratic Republic of the Congo", 937, 39],["Denmark", 10319, 526],["Djibouti", 1189, 3],["Dominica", 16, 0],["Dominican Republic", 9882, 385],["East Timor", 1, 0],["Ecuador", 30298, 1717],["Egypt", 8964, 514],["El Salvador", 889, 17],["Equatorial Guinea", 439, 4],["Eritrea", 39, 0],["Estonia", 1733, 60],["Eswatini", 163, 2],["Ethiopia", 210, 5],["Faeroe Islands", 187, 0],["Faroe Islands", 187, 0],["Fench Guiana", 5, 0],["Fiji", 18, 0],["Finland", 5880, 265],["France", 176658, 26310],["French Guiana", 144, 1],["French Polynesia", 60, 0],["Gabon", 661, 8],["Gambia", 20, 1],["Georgia", 626, 10],["Germany", 171324, 7549],["Ghana", 4263, 22],["Gibraltar", 146, 0],["Greece", 2710, 151],["Greenland", 11, 0],["Grenada", 21, 0],["Guadeloupe", 154, 13],["United States", 1337621, 79660],["Guatemala", 967, 24],["Guernsey", 1, 0],["Guinea", 2042, 11],["Guinea-Bissau", 641, 3],["Guyana", 97, 10],["Haiti", 151, 12],["Holy See", 12, 0],["Honduras", 1830, 108],["Hungary", 3213, 405],["Iceland", 1801, 10],["India", 62939, 2109],["Indonesia", 13645, 959],["Iran", 106220, 6589],["Iraq", 2679, 107],["Ireland", 22760, 1446],["Isle of Man", 329, 23],["Israel", 16454, 247],["Italy", 218268, 30395],["Jamaica", 498, 9],["Japan", 15663, 607],["Jersey", 2, 0],["Jordan", 522, 9],["Kazakhstan", 4975, 31],["Kenya", 649, 30],["Kosovo", 862, 28],["Kuwait", 7623, 49],["Kyrgyzstan", 1002, 12],["Laos", 19, 0],["Latvia", 930, 18],["Lebanon", 809, 26],["Liberia", 199, 20],["Libya", 64, 3],["Liechtenstein", 82, 1],["Lithuania", 1444, 49],["Luxembourg", 3877, 101],["Madagascar", 193, 0],["Malaysia", 6589, 108],["Maldives", 790, 3],["Mali", 692, 37],["Malta", 490, 5],["Martinique", 186, 14],["Mauritania", 8, 1],["Mauritius", 334, 10],["Mayotte", 988, 11],["Mexico", 33460, 3353],["Moldova", 4867, 161],["Monaco", 96, 4],["Mongolia", 42, 0],["Montenegro", 324, 8],["Montserrat", 11, 1],["Morocco", 5910, 186],["Mozambique", 87, 0],["MS Zaandam", 9, 2],["Myanmar", 178, 6],["Namibia", 16, 0],["Nepal", 110, 0],["Netherlands", 42382, 5422],["New Caledonia", 18, 0],["New Zealand", 1494, 21],["Nicaragua", 16, 5],["Niger", 815, 45],["Nigeria", 4151, 128],["North Macedonia", 1622, 91],["Norway", 8099, 219],["Oman", 3224, 17],["Pakistan", 29465, 639],["Palestine", 375, 4],["Panama", 8282, 237],["Papua New Guinea", 8, 0],["Paraguay", 689, 10],["Peru", 65015, 1814],["Philippines", 10610, 704],["Poland", 15651, 785],["Portugal", 27406, 1126],["Qatar", 21331, 13],["Republic of the Congo", 274, 10],["Reunion", 431, 0],["Romania", 15131, 939],["Russia", 198676, 1827],["Rwanda", 280, 0],["Saint Barthelemy", 6, 0],["Saint Kitts and Nevis", 15, 0],["Saint Lucia", 18, 0],["Saint Martin", 39, 3],["Saint Vincent and the Grenadines", 17, 0],["San Marino", 637, 41],["Saudi Arabia", 37136, 239],["Senegal", 1634, 17],["Serbia", 10032, 215],["Seychelles", 11, 0],["Singapore", 22460, 20],["Sint Maarten", 76, 15],["Slovakia", 1455, 26],["Slovenia", 1454, 101],["Somalia", 997, 48],["South Africa", 9420, 186],["South Korea", 10874, 256],["Spain", 262783, 26478],["Sri Lanka", 847, 9],["Sudan", 1164, 64],["Suriname", 10, 1],["Sweden", 25921, 3220],["Switzerland", 30251, 1830],["Syria", 47, 5],["Taiwan", 440, 6],["Tanzania", 509, 21],["Thailand", 3009, 56],["The Bahamas", 92, 11],["The Gambia", 20, 1],["Timor-Leste", 24, 0],["Togo", 153, 10],["Trinidad and Tobago", 116, 8],["Tunisia", 1032, 45],["Turkey", 137115, 3739],["Turks and Caicos", 12, 1],["Turks and Caicos Islands", 12, 1],["Uganda", 116, 0],["Ukraine", 14710, 376],["United Arab Emirates", 17417, 185],["United Kingdom", 215260, 31587],["Uruguay", 702, 18],["Uzbekistan", 2349, 10],["Venezuela", 402, 16],["Vietnam", 288, 0],["West Bank and Gaza", 495, 4],["Zambia", 252, 7],["Zimbabwe", 40, 4],["Sierra Leone", 291, 18],["Burundi", 15, 1],["Caribbean Netherlands", 6, 0],["Malawi", 56, 3],["Falkland Islands", 13, 0],["Western Sahara", 6, 0],["Saint Pierre Miquelon", 1, 0],["South Sudan", 120, 0],["Sao Tome and Principe", 208, 5],["Yemen", 34, 7],["Falkland Islands (Malvinas)", 13, 0],["Saint Pierre and Miquelon", 1, 0],["Tajikistan", 612, 20],["Comoros", 11, 1],
    ]);
    var options = {
      backgroundColor: {fill:'transparent',stroke:'#FFF' ,strokeWidth:0 }, 
      region: 'world', 
      resolution: 'countries',
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
      [{v:"Afghanistan", f:"Afghanistan"}, 4033, 255, 3416, 115, 6, 502],[{v:"Albania", f:"Albania"}, 856, 6, 198, 31, 0, 627],[{v:"Algeria", f:"Algeria"}, 5558, 189, 2518, 494, 6, 2546],[{v:"Andorra", f:"Andorra"}, 754, 2, 161, 48, 1, 545],[{v:"Angola", f:"Angola"}, 43, 0, 28, 2, 0, 13],[{v:"Anguilla", f:"Anguilla"}, 3, 0, 0, 0, 0, 3],[{v:"Antigua and Barbuda", f:"Antigua and Barbuda"}, 25, 0, 3, 3, 0, 19],[{v:"Argentina", f:"Argentina"}, 5776, 165, 3748, 300, 7, 1728],[{v:"Armenia", f:"Armenia"}, 3175, 146, 1864, 44, 1, 1267],[{v:"Aruba", f:"Aruba"}, 101, 0, 9, 3, 0, 89],[{v:"Australia", f:"<a href='https://smartable.ai/apps/coronavirus/stats/australia/'>Australia</a>"}, 6939, 12, 680, 97, 0, 6162],[{v:"Austria", f:"Austria"}, 15833, 59, 1290, 615, 1, 13928],[{v:"Azerbaijan", f:"Azerbaijan"}, 2422, 143, 771, 31, 3, 1620],[{v:"Bahamas", f:"Bahamas"}, 92, 0, 44, 11, 0, 37],[{v:"Bahrain", f:"Bahrain"}, 4774, 330, 2711, 8, 0, 2055],[{v:"Bangladesh", f:"Bangladesh"}, 13770, 636, 11142, 214, 8, 2414],[{v:"Barbados", f:"Barbados"}, 84, 1, 20, 7, 0, 57],[{v:"Belarus", f:"Belarus"}, 22052, 951, 15876, 126, 5, 6050],[{v:"Belgium", f:"Belgium"}, 52596, 585, 30604, 8581, 60, 13411],[{v:"Belize", f:"Belize"}, 18, 0, 0, 2, 0, 16],[{v:"Benin", f:"Benin"}, 284, 42, 220, 2, 0, 62],[{v:"Bermuda", f:"Bermuda"}, 118, 0, 47, 7, 0, 64],[{v:"Bhutan", f:"Bhutan"}, 7, 0, 2, 0, 0, 5],[{v:"Bolivia", f:"Bolivia"}, 2437, 171, 2065, 114, 8, 258],[{v:"Bosnia and Herzegovina", f:"Bosnia and Herzegovina"}, 2090, 20, 929, 102, 4, 1059],[{v:"Botswana", f:"Botswana"}, 23, 0, 10, 1, 0, 12],[{v:"Brazil", f:"Brazil"}, 156061, 9167, 83720, 10656, 639, 61685],[{v:"British Virgin Islands", f:"British Virgin Islands"}, 7, 0, 2, 1, 0, 4],[{v:"Brunei", f:"Brunei"}, 141, 0, 8, 1, 0, 132],[{v:"Bulgaria", f:"Bulgaria"}, 1921, 10, 1409, 90, 2, 422],[{v:"Burkina Faso", f:"Burkina Faso"}, 748, 4, 131, 48, 0, 569],[{v:"Burma", f:"Burma"}, 178, 1, 104, 6, 0, 68],[{v:"Cabo Verde", f:"Cabo Verde"}, 236, 6, 178, 2, 0, 56],[{v:"Cambodia", f:"Cambodia"}, 122, 0, 2, 0, 0, 120],[{v:"Cameroon", f:"Cameroon"}, 2274, 7, 934, 108, 0, 1232],[{v:"Canada", f:"<a href='https://smartable.ai/apps/coronavirus/stats/canada/'>Canada</a>"}, 68920, 1244, 55887, 4823, 126, 8210],[{v:"Cape Verde", f:"Cape Verde"}, 1, 0, 1, 0, 0, 0],[{v:"CAR", f:"CAR"}, 1, 0, 1, 0, 0, 0],[{v:"Cayman Islands", f:"Cayman Islands"}, 81, 0, 39, 1, 0, 41],[{v:"Central African Republic", f:"Central African Republic"}, 143, 0, 133, 0, 0, 10],[{v:"Chad", f:"Chad"}, 322, 62, 238, 31, 3, 53],[{v:"Channel Islands", f:"Channel Islands"}, 545, 0, 57, 41, 0, 447],[{v:"Chile", f:"Chile"}, 27219, 1247, 14248, 304, 10, 12667],[{v:"China", f:"<a href='https://smartable.ai/apps/coronavirus/stats/china/'>China</a>"}, 83992, 15, 0, 4637, 0, 79970],[{v:"Colombia", f:"Colombia"}, 10495, 444, 7481, 445, 17, 2569],[{v:"Costa Rica", f:"Costa Rica"}, 780, 7, 294, 6, 0, 480],[{v:"Cote d'Ivoire", f:"Cote d'Ivoire"}, 1667, 65, 877, 21, 1, 769],[{v:"Croatia", f:"Croatia"}, 2176, 15, 363, 87, 1, 1726],[{v:"Cruise Ship: Diamond Princess", f:"Cruise Ship: Diamond Princess"}, 712, 0, 54, 13, 0, 645],[{v:"Cuba", f:"Cuba"}, 1754, 13, 540, 74, 0, 1140],[{v:"Curacao", f:"Curacao"}, 16, 0, 1, 1, 0, 14],[{v:"Cyprus", f:"Cyprus"}, 892, 1, 476, 15, 0, 401],[{v:"Czechia", f:"Czechia"}, 8095, 18, 3372, 276, 3, 4447],[{v:"Democratic Republic of the Congo", f:"Democratic Republic of the Congo"}, 937, 0, 768, 39, 0, 130],[{v:"Denmark", f:"Denmark"}, 10319, 101, 1700, 526, 4, 8093],[{v:"Djibouti", f:"Djibouti"}, 1189, 54, 352, 3, 0, 834],[{v:"Dominica", f:"Dominica"}, 16, 0, 2, 0, 0, 14],[{v:"Dominican Republic", f:"Dominican Republic"}, 9882, 506, 6913, 385, 5, 2584],[{v:"East Timor", f:"East Timor"}, 1, 0, 1, 0, 0, 0],[{v:"Ecuador", f:"Ecuador"}, 30298, 0, 25148, 1717, 13, 3433],[{v:"Egypt", f:"Egypt"}, 8964, 488, 6448, 514, 11, 2002],[{v:"El Salvador", f:"El Salvador"}, 889, 105, 579, 17, 1, 293],[{v:"Equatorial Guinea", f:"Equatorial Guinea"}, 439, 0, 422, 4, 0, 13],[{v:"Eritrea", f:"Eritrea"}, 39, 0, 2, 0, 0, 37],[{v:"Estonia", f:"Estonia"}, 1733, 8, 926, 60, 4, 747],[{v:"Eswatini", f:"Eswatini"}, 163, 4, 147, 2, 0, 14],[{v:"Ethiopia", f:"Ethiopia"}, 210, 16, 108, 5, 1, 97],[{v:"Faeroe Islands", f:"Faeroe Islands"}, 187, 0, 0, 0, 0, 187],[{v:"Faroe Islands", f:"Faroe Islands"}, 187, 0, 0, 0, 0, 187],[{v:"Fench Guiana", f:"Fench Guiana"}, 5, 0, 5, 0, 0, 0],[{v:"Fiji", f:"Fiji"}, 18, 0, 4, 0, 0, 14],[{v:"Finland", f:"Finland"}, 5880, 142, 1615, 265, 5, 4000],[{v:"France", f:"<a href='https://smartable.ai/apps/coronavirus/stats/france/'>France</a>"}, 176658, 579, 94310, 26310, 80, 56038],[{v:"French Guiana", f:"French Guiana"}, 144, 3, 21, 1, 0, 122],[{v:"French Polynesia", f:"French Polynesia"}, 60, 0, 4, 0, 0, 56],[{v:"Gabon", f:"Gabon"}, 661, 41, 543, 8, 0, 110],[{v:"Gambia", f:"Gambia"}, 20, 0, 10, 1, 0, 9],[{v:"Georgia", f:"<a href='https://smartable.ai/apps/coronavirus/stats/us-ga/'>Georgia</a>"}, 626, 3, 319, 10, 0, 297],[{v:"Germany", f:"<a href='https://smartable.ai/apps/coronavirus/stats/germany/'>Germany</a>"}, 171324, 736, 20475, 7549, 39, 143300],[{v:"Ghana", f:"Ghana"}, 4263, 251, 3863, 22, 4, 378],[{v:"Gibraltar", f:"Gibraltar"}, 146, 0, 4, 0, 0, 142],[{v:"Greece", f:"Greece"}, 2710, 19, 1185, 151, 1, 1374],[{v:"Greenland", f:"Greenland"}, 11, 0, 0, 0, 0, 11],[{v:"Grenada", f:"Grenada"}, 21, 0, 8, 0, 0, 13],[{v:"Guadeloupe", f:"Guadeloupe"}, 154, 0, 37, 13, 0, 104],[{v:"United States", f:"<a href='https://smartable.ai/apps/coronavirus/stats/us/'>United States</a>"}, 1337621, 24630, 1029412, 79660, 1482, 228549],[{v:"Guatemala", f:"Guatemala"}, 967, 67, 839, 24, 0, 104],[{v:"Guernsey", f:"Guernsey"}, 1, 0, 1, 0, 0, 0],[{v:"Guinea", f:"Guinea"}, 2042, 33, 1333, 11, 0, 698],[{v:"Guinea-Bissau", f:"Guinea-Bissau"}, 641, 47, 613, 3, 1, 25],[{v:"Guyana", f:"Guyana"}, 97, 3, 52, 10, 0, 35],[{v:"Haiti", f:"Haiti"}, 151, 5, 122, 12, 0, 17],[{v:"Holy See", f:"Holy See"}, 12, 0, 10, 0, 0, 2],[{v:"Honduras", f:"Honduras"}, 1830, 59, 1527, 108, 1, 195],[{v:"Hungary", f:"Hungary"}, 3213, 0, 1904, 405, 0, 904],[{v:"Iceland", f:"Iceland"}, 1801, 0, 18, 10, 0, 1773],[{v:"India", f:"<a href='https://smartable.ai/apps/coronavirus/stats/india/'>India</a>"}, 62939, 3174, 41472, 2109, 123, 19358],[{v:"Indonesia", f:"Indonesia"}, 13645, 533, 10079, 959, 16, 2607],[{v:"Iran", f:"<a href='https://smartable.ai/apps/coronavirus/stats/iran/'>Iran</a>"}, 106220, 1529, 14567, 6589, 48, 85064],[{v:"Iraq", f:"Iraq"}, 2679, 76, 870, 107, 3, 1702],[{v:"Ireland", f:"Ireland"}, 22760, 219, 4204, 1446, 17, 17110],[{v:"Isle of Man", f:"Isle of Man"}, 329, 0, 35, 23, 0, 271],[{v:"Israel", f:"Israel"}, 16454, 18, 4831, 247, 2, 11376],[{v:"Italy", f:"<a href='https://smartable.ai/apps/coronavirus/stats/italy/'>Italy</a>"}, 218268, 1083, 84842, 30395, 194, 103031],[{v:"Jamaica", f:"Jamaica"}, 498, 8, 411, 9, 0, 78],[{v:"Japan", f:"<a href='https://smartable.ai/apps/coronavirus/stats/japan/'>Japan</a>"}, 15663, 88, 9150, 607, 17, 5906],[{v:"Jersey", f:"Jersey"}, 2, 0, 2, 0, 0, 0],[{v:"Jordan", f:"Jordan"}, 522, 14, 126, 9, 0, 387],[{v:"Kazakhstan", f:"Kazakhstan"}, 4975, 141, 3168, 31, 0, 1776],[{v:"Kenya", f:"Kenya"}, 649, 28, 412, 30, 1, 207],[{v:"Kosovo", f:"Kosovo"}, 862, 1, 212, 28, 1, 622],[{v:"Kuwait", f:"Kuwait"}, 7623, 415, 4952, 49, 2, 2622],[{v:"Kyrgyzstan", f:"Kyrgyzstan"}, 1002, 71, 315, 12, 0, 675],[{v:"Laos", f:"Laos"}, 19, 0, 6, 0, 0, 13],[{v:"Latvia", f:"Latvia"}, 930, 2, 448, 18, 0, 464],[{v:"Lebanon", f:"Lebanon"}, 809, 13, 549, 26, 0, 234],[{v:"Liberia", f:"Liberia"}, 199, 0, 100, 20, 0, 79],[{v:"Libya", f:"Libya"}, 64, 0, 37, 3, 0, 24],[{v:"Liechtenstein", f:"Liechtenstein"}, 82, 0, 26, 1, 0, 55],[{v:"Lithuania", f:"Lithuania"}, 1444, 8, 567, 49, 0, 828],[{v:"Luxembourg", f:"Luxembourg"}, 3877, 6, 226, 101, 1, 3550],[{v:"Madagascar", f:"Madagascar"}, 193, 0, 92, 0, 0, 101],[{v:"Malaysia", f:"Malaysia"}, 6589, 54, 1552, 108, 1, 4929],[{v:"Maldives", f:"Maldives"}, 790, 46, 758, 3, 0, 29],[{v:"Mali", f:"Mali"}, 692, 24, 357, 37, 2, 298],[{v:"Malta", f:"Malta"}, 490, 1, 58, 5, 0, 427],[{v:"Martinique", f:"Martinique"}, 186, 0, 89, 14, 0, 83],[{v:"Mauritania", f:"Mauritania"}, 8, 0, 1, 1, 0, 6],[{v:"Mauritius", f:"Mauritius"}, 334, 0, 4, 10, 0, 320],[{v:"Mayotte", f:"Mayotte"}, 988, 134, 485, 11, 1, 492],[{v:"Mexico", f:"Mexico"}, 33460, 1938, 8283, 3353, 193, 21824],[{v:"Moldova", f:"Moldova"}, 4867, 139, 2781, 161, 11, 1925],[{v:"Monaco", f:"Monaco"}, 96, 1, 10, 4, 0, 82],[{v:"Mongolia", f:"Mongolia"}, 42, 0, 28, 0, 0, 14],[{v:"Montenegro", f:"Montenegro"}, 324, 0, 42, 8, 0, 274],[{v:"Montserrat", f:"Montserrat"}, 11, 0, 2, 1, 0, 8],[{v:"Morocco", f:"Morocco"}, 5910, 199, 3263, 186, 0, 2461],[{v:"Mozambique", f:"Mozambique"}, 87, 5, 53, 0, 0, 34],[{v:"MS Zaandam", f:"MS Zaandam"}, 9, 0, 7, 2, 0, 0],[{v:"Myanmar", f:"Myanmar"}, 178, 1, 104, 6, 0, 68],[{v:"Namibia", f:"Namibia"}, 16, 0, 6, 0, 0, 10],[{v:"Nepal", f:"Nepal"}, 110, 1, 79, 0, 0, 31],[{v:"Netherlands", f:"<a href='https://smartable.ai/apps/coronavirus/stats/netherlands/'>Netherlands</a>"}, 42382, 289, 36710, 5422, 63, 250],[{v:"New Caledonia", f:"New Caledonia"}, 18, 0, 0, 0, 0, 18],[{v:"New Zealand", f:"New Zealand"}, 1494, 2, 102, 21, 0, 1371],[{v:"Nicaragua", f:"Nicaragua"}, 16, 0, 4, 5, 0, 7],[{v:"Niger", f:"Niger"}, 815, 20, 153, 45, 1, 617],[{v:"Nigeria", f:"Nigeria"}, 4151, 239, 3278, 128, 11, 745],[{v:"North Macedonia", f:"North Macedonia"}, 1622, 36, 419, 91, 1, 1112],[{v:"Norway", f:"Norway"}, 8099, 29, 7848, 219, 1, 32],[{v:"Oman", f:"Oman"}, 3224, 112, 2139, 17, 1, 1068],[{v:"Pakistan", f:"Pakistan"}, 29465, 1991, 20803, 639, 21, 8023],[{v:"Palestine", f:"Palestine"}, 375, 0, 143, 4, 0, 228],[{v:"Panama", f:"Panama"}, 8282, 212, 3544, 237, 6, 4501],[{v:"Papua New Guinea", f:"Papua New Guinea"}, 8, 0, 0, 0, 0, 8],[{v:"Paraguay", f:"Paraguay"}, 689, 126, 524, 10, 0, 155],[{v:"Peru", f:"Peru"}, 65015, 3168, 42955, 1814, 100, 20246],[{v:"Philippines", f:"Philippines"}, 10610, 147, 8064, 704, 8, 1842],[{v:"Poland", f:"Poland"}, 15651, 285, 9429, 785, 9, 5437],[{v:"Portugal", f:"Portugal"}, 27406, 138, 23781, 1126, 12, 2499],[{v:"Qatar", f:"Qatar"}, 21331, 1130, 18869, 13, 1, 2449],[{v:"Republic of the Congo", f:"Republic of the Congo"}, 274, 0, 231, 10, 0, 33],[{v:"Reunion", f:"Reunion"}, 431, 4, 77, 0, 0, 354],[{v:"Romania", f:"Romania"}, 15131, 320, 7280, 939, 16, 6912],[{v:"Russia", f:"Russia"}, 198676, 10817, 164933, 1827, 104, 31916],[{v:"Rwanda", f:"Rwanda"}, 280, 7, 140, 0, 0, 140],[{v:"Saint Barthelemy", f:"Saint Barthelemy"}, 6, 0, 0, 0, 0, 6],[{v:"Saint Kitts and Nevis", f:"Saint Kitts and Nevis"}, 15, 0, 1, 0, 0, 14],[{v:"Saint Lucia", f:"Saint Lucia"}, 18, 0, 1, 0, 0, 17],[{v:"Saint Martin", f:"Saint Martin"}, 39, 1, 6, 3, 0, 30],[{v:"Saint Vincent and the Grenadines", f:"Saint Vincent and the Grenadines"}, 17, 0, 8, 0, 0, 9],[{v:"San Marino", f:"San Marino"}, 637, 14, 470, 41, 0, 126],[{v:"Saudi Arabia", f:"Saudi Arabia"}, 37136, 1704, 26753, 239, 10, 10144],[{v:"Senegal", f:"Senegal"}, 1634, 83, 974, 17, 4, 643],[{v:"Serbia", f:"Serbia"}, 10032, 89, 7085, 215, 6, 2732],[{v:"Seychelles", f:"Seychelles"}, 11, 0, 3, 0, 0, 8],[{v:"Singapore", f:"<a href='https://smartable.ai/apps/coronavirus/stats/singapore/'>Singapore</a>"}, 22460, 753, 20144, 20, 0, 2296],[{v:"Sint Maarten", f:"Sint Maarten"}, 76, 0, 15, 15, 1, 46],[{v:"Slovakia", f:"Slovakia"}, 1455, 0, 510, 26, 0, 919],[{v:"Slovenia", f:"Slovenia"}, 1454, 4, 1098, 101, 1, 255],[{v:"Somalia", f:"Somalia"}, 997, 69, 839, 48, 4, 110],[{v:"South Africa", f:"South Africa"}, 9420, 525, 5251, 186, 8, 3983],[{v:"South Korea", f:"<a href='https://smartable.ai/apps/coronavirus/stats/south-korea/'>South Korea</a>"}, 10874, 34, 1008, 256, 0, 9610],[{v:"Spain", f:"<a href='https://smartable.ai/apps/coronavirus/stats/spain/'>Spain</a>"}, 262783, 2666, 63148, 26478, 179, 173157],[{v:"Sri Lanka", f:"Sri Lanka"}, 847, 12, 578, 9, 0, 260],[{v:"Sudan", f:"Sudan"}, 1164, 53, 981, 64, 5, 119],[{v:"Suriname", f:"Suriname"}, 10, 0, 0, 1, 0, 9],[{v:"Sweden", f:"<a href='https://smartable.ai/apps/coronavirus/stats/sweden/'>Sweden</a>"}, 25921, 656, 17730, 3220, 45, 4971],[{v:"Switzerland", f:"<a href='https://smartable.ai/apps/coronavirus/stats/switzerland/'>Switzerland</a>"}, 30251, 44, 2021, 1830, 7, 26400],[{v:"Syria", f:"Syria"}, 47, 0, 13, 5, 0, 29],[{v:"Taiwan", f:"Taiwan"}, 440, 0, 73, 6, 0, 361],[{v:"Tanzania", f:"Tanzania"}, 509, 0, 305, 21, 0, 183],[{v:"Thailand", f:"Thailand"}, 3009, 5, 159, 56, 0, 2794],[{v:"The Bahamas", f:"The Bahamas"}, 92, 0, 44, 11, 0, 37],[{v:"The Gambia", f:"The Gambia"}, 20, 0, 10, 1, 0, 9],[{v:"Timor-Leste", f:"Timor-Leste"}, 24, 0, 3, 0, 0, 21],[{v:"Togo", f:"Togo"}, 153, 8, 56, 10, 0, 87],[{v:"Trinidad and Tobago", f:"Trinidad and Tobago"}, 116, 0, 4, 8, 0, 104],[{v:"Tunisia", f:"Tunisia"}, 1032, 2, 327, 45, 0, 660],[{v:"Turkey", f:"Turkey"}, 137115, 1546, 43896, 3739, 50, 89480],[{v:"Turks and Caicos", f:"Turks and Caicos"}, 12, 0, 3, 1, 0, 8],[{v:"Turks and Caicos Islands", f:"Turks and Caicos Islands"}, 12, 0, 3, 1, 0, 8],[{v:"Uganda", f:"Uganda"}, 116, 15, 61, 0, 0, 55],[{v:"Ukraine", f:"Ukraine"}, 14710, 515, 11425, 376, 15, 2909],[{v:"United Arab Emirates", f:"United Arab Emirates"}, 17417, 624, 12937, 185, 11, 4295],[{v:"United Kingdom", f:"<a href='https://smartable.ai/apps/coronavirus/stats/uk/'>United Kingdom</a>"}, 215260, 3896, 183329, 31587, 346, 344],[{v:"Uruguay", f:"Uruguay"}, 702, 8, 171, 18, 0, 513],[{v:"Uzbekistan", f:"Uzbekistan"}, 2349, 13, 493, 10, 0, 1846],[{v:"Venezuela", f:"Venezuela"}, 402, 14, 196, 16, 0, 190],[{v:"Vietnam", f:"Vietnam"}, 288, 0, 47, 0, 0, 241],[{v:"West Bank and Gaza", f:"West Bank and Gaza"}, 495, 0, 263, 4, 0, 228],[{v:"Zambia", f:"Zambia"}, 252, 85, 133, 7, 3, 112],[{v:"Zimbabwe", f:"Zimbabwe"}, 40, 0, 27, 4, 0, 9],[{v:"Sierra Leone", f:"Sierra Leone"}, 291, 34, 215, 18, 1, 58],[{v:"Burundi", f:"Burundi"}, 15, 0, 7, 1, 0, 7],[{v:"Caribbean Netherlands", f:"Caribbean Netherlands"}, 6, 0, 6, 0, 0, 0],[{v:"Malawi", f:"Malawi"}, 56, 13, 39, 3, 0, 14],[{v:"Falkland Islands", f:"Falkland Islands"}, 13, 0, 0, 0, 0, 13],[{v:"Western Sahara", f:"Western Sahara"}, 6, 0, 1, 0, 0, 5],[{v:"Saint Pierre Miquelon", f:"Saint Pierre Miquelon"}, 1, 0, 1, 0, 0, 0],[{v:"South Sudan", f:"South Sudan"}, 120, 0, 118, 0, 0, 2],[{v:"Sao Tome and Principe", f:"Sao Tome and Principe"}, 208, 0, 199, 5, 0, 4],[{v:"Yemen", f:"Yemen"}, 34, 0, 26, 7, 0, 1],[{v:"Falkland Islands (Malvinas)", f:"Falkland Islands (Malvinas)"}, 13, 0, 0, 0, 0, 13],[{v:"Saint Pierre and Miquelon", f:"Saint Pierre and Miquelon"}, 1, 0, 1, 0, 0, 0],[{v:"Tajikistan", f:"Tajikistan"}, 612, 90, 592, 20, 8, 0],[{v:"Comoros", f:"Comoros"}, 11, 3, 10, 1, 0, 0],
    ]);
    data.setProperty(0, 0, 'style', 'min-width:100px');
    var table = new google.visualization.Table(document.getElementById('geo_table'));
    table.draw(data, {allowHtml: true, sortColumn: 2, sortAscending: false, width: '660px', height: '100%'});
  }
</script>

<span style="font-size: 13px">All COVID-19 data displayed on the page is available through our FREE <a href="https://developer.smartable.ai">API program</a>. This Global Coronavirus (COVID-19) Live Stats is refreshed every hour using credible data sources, including the country/state's official government website, <a href="https://en.wikipedia.org/wiki/2019%E2%80%9320_coronavirus_pandemic" target="_blank">data available on wikipedia pages</a>, latest news reports, <a href="https://systems.jhu.edu/research/public-health/ncov/" target="_blank">Johns Hopkins University CSSE 2019-nCoV Dashboard</a>, <a href="https://www.who.int/emergencies/diseases/novel-coronavirus-2019/situation-reports" target="_blank">WHO Situation Reports</a>, <a href="https://www.cdc.gov/coronavirus/2019-ncov/index.html" target="_blank">CDC Situation Updates</a>, and <a href="https://ncov.dxy.cn/ncovh5/view/pneumonia" target="_blank">DXY.cn</a>.</span>


<h2 id="news" class="center" style="margin-top: 60px; font-size: 25px;">Trending Coronavirus News in the World</h2>
<div class="row">
<div class="col-md-6 col-sm-12">
  <div class="content-card">
	<a href="https://www.reviewjournal.com/opinion/opinion-columns/debra-saunders/debra-j-saunders-public-school-closures-may-be-a-big-mistake-2024988/"><div class="card-image" style="background-image: url(https://www.reviewjournal.com/wp-content/uploads/2020/05/13720800_web1_cmyk_13622881-f3b139580d224e70912de143d76901f4.jpg?w=600)"></div></a>
	<div class="content">
		<div class="card-title"><a href="https://www.reviewjournal.com/opinion/opinion-columns/debra-saunders/debra-j-saunders-public-school-closures-may-be-a-big-mistake-2024988/">DEBRA J. SAUNDERS: Public school closures may be a big mistake</a></div>
		<div class="card-excerpt">In this March 13, 2020  students at New York City's Stuyvesant High School leave after classes end for the week. Public schools in New York City's 1.1 million-stu</div>
		<div class="card-meta">
			<span class="card-provider">Las Vegas Review-Journal</span> • <span class="card-date">5/9/2020</span>
		</div>
	</div>
  </div>
</div>
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
	<a href="https://www.ft.com/content/6c2ad256-9452-4480-9d98-2444b07675d4"><div class="card-image" style="background-image: url(https://www.ft.com/__origami/service/image/v2/images/raw/https%3A%2F%2Fd1e00ek4ebabms.cloudfront.net%2Fproduction%2F8e4ceb41-68fe-4f0b-b74b-87500afd027b.jpg?source=google-amp&fit=scale-down&width=500)"></div></a>
	<div class="content">
		<div class="card-title"><a href="https://www.ft.com/content/6c2ad256-9452-4480-9d98-2444b07675d4">Coronavirus deepens north-south divide in Italy and Spain</a></div>
		<div class="card-excerpt">While the rest of Italy started returning to work this week as restrictions aimed at stopping the spread of coronavirus were lifted, employees at the Rummo pasta plant could be forgiven for wanting a holiday.</div>
		<div class="card-meta">
			<span class="card-provider">The Financial Times</span> • <span class="card-date">5/9/2020</span>
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
	<a href="https://www.bbc.com/news/uk-52603566"><div class="card-image" style="background-image: url(https://ichef.bbci.co.uk/news/1024/cpsprodpb/F6CD/production/_112218136_gettyimages-1210981020.jpg)"></div></a>
	<div class="content">
		<div class="card-title"><a href="https://www.bbc.com/news/uk-52603566">Coronavirus: UK sent 50,000 Covid-19 samples to US for testing</a></div>
		<div class="card-excerpt">The government has admitted sending about 50,000 coronavirus tests to the US last week for processing after "operational issues" in UK labs. The Department of Health said sending swabs abroad are among the contingencies to deal with "teething problems".</div>
		<div class="card-meta">
			<span class="card-provider">BBC</span> • <span class="card-date">5/9/2020</span>
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
	<a href="https://www.reuters.com/article/us-health-coronavirus-southkorea-idUSKBN22M028"><div class="card-image" style="background-image: url(https://s2.reutersmedia.net/resources/r/?m=02&d=20200510&t=2&i=1518074993&w=&fh=545px&fw=&ll=&pl=&sq=&r=LYNXMPEG4902H)"></div></a>
	<div class="content">
		<div class="card-title"><a href="https://www.reuters.com/article/us-health-coronavirus-southkorea-idUSKBN22M028">South Korea reports 34 new coronavirus cases, highest in a month</a></div>
		<div class="card-excerpt">South Korea reported 34 new coronavirus cases on Sunday, the highest daily number in a month, after a small outbreak emerged around a slew of nightclubs that a confirmed patient had visited.</div>
		<div class="card-meta">
			<span class="card-provider">Reuters</span> • <span class="card-date">5/9/2020</span>
		</div>
	</div>
  </div>
</div>
<div class="col-md-6 col-sm-12">
  <div class="content-card">
	<a href="https://www.wfaa.com/article/news/health/coronavirus/community-welcomes-home-inspiring-texas-school-nurse-after-a-month-in-nyc-treating-covid-19-patients/287-8af704a8-348f-4f99-b7d5-d9a0af7dc965"><div class="card-image" style="background-image: url(https://media.wfaa.com/assets/WFAA/images/536b03f2-9f28-466f-9894-ed0db6acd342/536b03f2-9f28-466f-9894-ed0db6acd342_750x422.jpg)"></div></a>
	<div class="content">
		<div class="card-title"><a href="https://www.wfaa.com/article/news/health/coronavirus/community-welcomes-home-inspiring-texas-school-nurse-after-a-month-in-nyc-treating-covid-19-patients/287-8af704a8-348f-4f99-b7d5-d9a0af7dc965">Community welcomes home 'inspiring' Texas school nurse after a month in NYC treating COVID-19 patients</a></div>
		<div class="card-excerpt">Kristy Edney is a school nurse in Northwest ISD who felt the call to New York to help fellow health care workers</div>
		<div class="card-meta">
			<span class="card-provider">WFAA8</span> • <span class="card-date">5/9/2020</span>
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

</div>

