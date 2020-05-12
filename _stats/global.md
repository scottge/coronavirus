---
category: stats
title: "Global Coronavirus (COVID-19) Live Stats"
excerpt: "Live stats of COVID-19 in the World. Total Cases: 4304574 (+52925), Deaths: 290333 (+3040), Recoveries: 1534031(+38258)."
publishedDateTime: 2020-05-12T17:45:09Z
updatedDateTime: 2020-05-12T17:45:09Z
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
	    4304574 (<span class='red'>+52925</span>)
    </h3>
    <h3>
	    <div style="font-size: 18px; font-weight: 400;">Total Deaths:</div>
	    290333 (<span class='red'>+3040</span>)
    </h3>
    <h3>
	    <div style="font-size: 18px; font-weight: 400;">Total Recovered:</div>
	    1534031 (<span class='green'>+38258</span>)
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
      ['1/22/2020', 554, 17, 28],['1/23/2020', 653, 18, 30],['1/24/2020', 941, 26, 36],['1/25/2020', 1434, 42, 39],['1/26/2020', 2118, 56, 52],['1/27/2020', 2927, 82, 61],['1/28/2020', 5578, 131, 107],['1/29/2020', 6166, 133, 126],['1/30/2020', 8233, 171, 143],['1/31/2020', 9927, 213, 222],['2/1/2020', 12037, 259, 284],['2/2/2020', 16787, 362, 471],['2/3/2020', 19881, 426, 623],['2/4/2020', 23892, 492, 852],['2/5/2020', 27635, 564, 1121],['2/6/2020', 30794, 634, 1487],['2/7/2020', 34391, 719, 2011],['2/8/2020', 37120, 806, 2614],['2/9/2020', 40150, 906, 3244],['2/10/2020', 42762, 1013, 3944],['2/11/2020', 44802, 1113, 4683],['2/12/2020', 45221, 1118, 5151],['2/13/2020', 60368, 1371, 6295],['2/14/2020', 66885, 1523, 8054],['2/15/2020', 69030, 1666, 9395],['2/16/2020', 71224, 1770, 10865],['2/17/2020', 73258, 1868, 12583],['2/18/2020', 75136, 2007, 14352],['2/19/2020', 75639, 2122, 16121],['2/20/2020', 76197, 2247, 18178],['2/21/2020', 76819, 2251, 18890],['2/22/2020', 78572, 2458, 22886],['2/23/2020', 78958, 2469, 23394],['2/24/2020', 79561, 2629, 25228],['2/25/2020', 80406, 2708, 27906],['2/26/2020', 81379, 2770, 30387],['2/27/2020', 82736, 2814, 33280],['2/28/2020', 84102, 2872, 36714],['2/29/2020', 85999, 2941, 39785],['3/1/2020', 88356, 2996, 42719],['3/2/2020', 90293, 3085, 45605],['3/3/2020', 92824, 3160, 48231],['3/4/2020', 95097, 3254, 51173],['3/5/2020', 97859, 3348, 53799],['3/6/2020', 101759, 3460, 55867],['3/7/2020', 105796, 3558, 58361],['3/8/2020', 109758, 3802, 60714],['3/9/2020', 113471, 3988, 62514],['3/10/2020', 118139, 4262, 64406],['3/11/2020', 125774, 4611, 67010],['3/12/2020', 134155, 4976, 69079],['3/13/2020', 145731, 5436, 72505],['3/14/2020', 156873, 5839, 75893],['3/15/2020', 168668, 6516, 77708],['3/16/2020', 182807, 7171, 79832],['3/17/2020', 198674, 7989, 82706],['3/18/2020', 219190, 8966, 85729],['3/19/2020', 245687, 10047, 88425],['3/20/2020', 276386, 11419, 91929],['3/21/2020', 308268, 13073, 95621],['3/22/2020', 339251, 14721, 99048],['3/23/2020', 381628, 16555, 101556],['3/24/2020', 423197, 18924, 108468],['3/25/2020', 472164, 21316, 114588],['3/26/2020', 533644, 24090, 122334],['3/27/2020', 597501, 27375, 131107],['3/28/2020', 665002, 30854, 139541],['3/29/2020', 737292, 34525, 148096],['3/30/2020', 798302, 38268, 160899],['3/31/2020', 869454, 42725, 172531],['4/1/2020', 952771, 47787, 194713],['4/2/2020', 1031327, 53664, 211805],['4/3/2020', 1113671, 59390, 226513],['4/4/2020', 1194673, 65238, 246752],['4/5/2020', 1267735, 69973, 262634],['4/6/2020', 1338712, 75318, 284387],['4/7/2020', 1414326, 82609, 300646],['4/8/2020', 1500008, 88960, 328788],['4/9/2020', 1585405, 96185, 355165],['4/10/2020', 1680140, 103299, 377401],['4/11/2020', 1756993, 109372, 404474],['4/12/2020', 1854028, 114771, 435166],['4/13/2020', 1924537, 120225, 457636],['4/14/2020', 1999887, 127273, 493610],['4/15/2020', 2080939, 135079, 510922],['4/16/2020', 2176752, 143552, 548174],['4/17/2020', 2266531, 154821, 566644],['4/18/2020', 2343146, 161474, 593739],['4/19/2020', 2421344, 165969, 620803],['4/20/2020', 2495422, 171256, 647153],['4/21/2020', 2568640, 178042, 681610],['4/22/2020', 2646686, 184795, 708870],['4/23/2020', 2734566, 191441, 737543],['4/24/2020', 2832547, 197889, 786066],['4/25/2020', 2926221, 203740, 833231],['4/26/2020', 2999132, 207389, 877022],['4/27/2020', 3069410, 212101, 916866],['4/28/2020', 3144395, 218224, 952107],['4/29/2020', 3223810, 228560, 995771],['4/30/2020', 3309963, 234269, 1033606],['5/1/2020', 3393481, 239302, 1070466],['5/2/2020', 3483205, 244858, 1110695],['5/3/2020', 3564075, 248556, 1142380],['5/4/2020', 3640979, 252726, 1183660],['5/5/2020', 3721548, 258245, 1218567],['5/6/2020', 3816803, 264918, 1277832],['5/7/2020', 3913723, 270537, 1317352],['5/8/2020', 4010649, 276018, 1358428],['5/9/2020', 4097330, 280282, 1411984],['5/10/2020', 4176646, 283728, 1462759],['5/11/2020', 4251649, 287293, 1495773],['5/12/2020', 4304574, 290333, 1534031],
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
      ["Afghanistan", 4963, 127],["Albania", 876, 31],["Algeria", 6067, 515],["Andorra", 755, 48],["Angola", 45, 2],["Anguilla", 3, 0],["Antigua and Barbuda", 25, 3],["Argentina", 6278, 317],["Armenia", 3538, 47],["Aruba", 101, 3],["Australia", 6971, 97],["Austria", 15961, 623],["Azerbaijan", 2693, 33],["Bahamas", 93, 11],["Bahrain", 5409, 9],["Bangladesh", 16660, 250],["Barbados", 84, 7],["Belarus", 24873, 142],["Belgium", 53779, 8761],["Belize", 18, 2],["Benin", 327, 2],["Bermuda", 119, 8],["Bhutan", 11, 0],["Bolivia", 2831, 122],["Bosnia and Herzegovina", 2158, 117],["Botswana", 24, 1],["Brazil", 172243, 11980],["British Virgin Islands", 7, 1],["Brunei", 141, 1],["Bulgaria", 2023, 95],["Burkina Faso", 760, 50],["Burma", 180, 6],["Cabo Verde", 267, 2],["Cambodia", 122, 0],["Cameroon", 2689, 125],["Canada", 71368, 5131],["Cape Verde", 1, 0],["CAR", 1, 0],["Cayman Islands", 84, 1],["Central African Republic", 143, 0],["Chad", 357, 40],["Channel Islands", 547, 42],["Chile", 31721, 335],["China", 84012, 4637],["Colombia", 11613, 479],["Costa Rica", 801, 7],["Cote d'Ivoire", 1730, 21],["Croatia", 2207, 91],["Cruise Ship: Diamond Princess", 712, 13],["Cuba", 1783, 77],["Curacao", 16, 1],["Cyprus", 903, 16],["Czechia", 8198, 283],["Democratic Republic of the Congo", 1102, 44],["Denmark", 10591, 533],["Djibouti", 1227, 3],["Dominica", 16, 0],["Dominican Republic", 10900, 402],["East Timor", 1, 0],["Ecuador", 30419, 2327],["Egypt", 9746, 533],["El Salvador", 998, 18],["Equatorial Guinea", 439, 4],["Eritrea", 39, 0],["Estonia", 1746, 61],["Eswatini", 175, 2],["Ethiopia", 261, 5],["Faeroe Islands", 187, 0],["Faroe Islands", 187, 0],["Fench Guiana", 5, 0],["Fiji", 18, 0],["Finland", 6003, 275],["France", 177423, 26643],["French Guiana", 144, 1],["French Polynesia", 60, 0],["Gabon", 802, 9],["Gambia", 22, 1],["Georgia", 642, 11],["Germany", 172812, 7676],["Ghana", 5127, 22],["Gibraltar", 147, 0],["Greece", 2744, 152],["Greenland", 11, 0],["Grenada", 21, 0],["Guadeloupe", 154, 13],["United States", 1385500, 82288],["Guatemala", 1114, 26],["Guernsey", 1, 0],["Guinea", 2213, 11],["Guinea-Bissau", 761, 3],["Guyana", 109, 10],["Haiti", 209, 16],["Holy See", 12, 0],["Honduras", 2100, 116],["Hungary", 3313, 425],["Iceland", 1801, 10],["India", 73981, 2408],["Indonesia", 14749, 1007],["Iran", 110767, 6733],["Iraq", 2913, 112],["Ireland", 23242, 1488],["Isle of Man", 330, 23],["Israel", 16526, 258],["Italy", 221216, 30911],["Jamaica", 505, 9],["Japan", 15847, 633],["Jersey", 2, 0],["Jordan", 576, 9],["Kazakhstan", 5279, 32],["Kenya", 715, 36],["Kosovo", 884, 28],["Kuwait", 10277, 75],["Kyrgyzstan", 1037, 12],["Laos", 19, 0],["Latvia", 950, 18],["Lebanon", 870, 26],["Liberia", 211, 20],["Libya", 64, 3],["Liechtenstein", 82, 1],["Lithuania", 1491, 50],["Luxembourg", 3894, 102],["Madagascar", 193, 0],["Malaysia", 6742, 109],["Maldives", 904, 3],["Mali", 712, 39],["Malta", 506, 5],["Martinique", 187, 14],["Mauritania", 8, 1],["Mauritius", 334, 10],["Mayotte", 1023, 11],["Mexico", 36327, 3573],["Moldova", 4995, 175],["Monaco", 96, 4],["Mongolia", 42, 0],["Montenegro", 324, 9],["Montserrat", 11, 1],["Morocco", 6418, 188],["Mozambique", 103, 0],["MS Zaandam", 9, 2],["Myanmar", 180, 6],["Namibia", 16, 0],["Nepal", 217, 0],["Netherlands", 42984, 5510],["New Caledonia", 18, 0],["New Zealand", 1497, 21],["Nicaragua", 16, 5],["Niger", 832, 46],["Nigeria", 4641, 150],["North Macedonia", 1674, 92],["Norway", 8132, 224],["Oman", 3721, 17],["Pakistan", 32674, 724],["Palestine", 375, 4],["Panama", 8616, 249],["Papua New Guinea", 8, 0],["Paraguay", 724, 10],["Peru", 68822, 1961],["Philippines", 11350, 751],["Poland", 16921, 839],["Portugal", 27913, 1163],["Qatar", 25149, 14],["Republic of the Congo", 333, 11],["Reunion", 436, 0],["Romania", 15778, 1002],["Russia", 232243, 2116],["Rwanda", 285, 0],["Saint Barthelemy", 6, 0],["Saint Kitts and Nevis", 15, 0],["Saint Lucia", 18, 0],["Saint Martin", 39, 3],["Saint Vincent and the Grenadines", 17, 0],["San Marino", 638, 41],["Saudi Arabia", 42925, 264],["Senegal", 1995, 19],["Serbia", 10243, 220],["Seychelles", 11, 0],["Singapore", 24671, 21],["Sint Maarten", 76, 15],["Slovakia", 1465, 27],["Slovenia", 1461, 102],["Somalia", 1170, 52],["South Africa", 11350, 206],["South Korea", 10936, 258],["Spain", 269520, 26920],["Sri Lanka", 884, 9],["Sudan", 1526, 74],["Suriname", 10, 1],["Sweden", 27272, 3313],["Switzerland", 30380, 1867],["Syria", 47, 5],["Taiwan", 440, 7],["Tanzania", 509, 21],["Thailand", 3017, 56],["The Bahamas", 93, 11],["The Gambia", 22, 1],["Timor-Leste", 24, 0],["Togo", 181, 11],["Trinidad and Tobago", 116, 8],["Tunisia", 1032, 45],["Turkey", 141475, 3894],["Turks and Caicos", 12, 1],["Turks and Caicos Islands", 12, 1],["Uganda", 122, 0],["Ukraine", 16023, 425],["United Arab Emirates", 19661, 203],["United Kingdom", 226463, 32692],["Uruguay", 711, 19],["Uzbekistan", 2519, 10],["Venezuela", 422, 16],["Vietnam", 288, 0],["West Bank and Gaza", 495, 4],["Zambia", 441, 7],["Zimbabwe", 40, 4],["Sierra Leone", 338, 19],["Burundi", 15, 1],["Caribbean Netherlands", 6, 0],["Malawi", 57, 3],["Falkland Islands", 13, 0],["Western Sahara", 6, 0],["Saint Pierre Miquelon", 1, 0],["South Sudan", 156, 0],["Sao Tome and Principe", 208, 5],["Yemen", 65, 10],["Falkland Islands (Malvinas)", 13, 0],["Saint Pierre and Miquelon", 1, 0],["Tajikistan", 661, 21],["Comoros", 11, 1],
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
      [{v:"Afghanistan", f:"Afghanistan"}, 4963, 276, 4226, 127, 5, 610],[{v:"Albania", f:"Albania"}, 876, 4, 163, 31, 0, 682],[{v:"Algeria", f:"Algeria"}, 6067, 176, 2554, 515, 8, 2998],[{v:"Andorra", f:"Andorra"}, 755, 0, 157, 48, 0, 550],[{v:"Angola", f:"Angola"}, 45, 0, 30, 2, 0, 13],[{v:"Anguilla", f:"Anguilla"}, 3, 0, 0, 0, 0, 3],[{v:"Antigua and Barbuda", f:"Antigua and Barbuda"}, 25, 0, 3, 3, 0, 19],[{v:"Argentina", f:"Argentina"}, 6278, 0, 4099, 317, 3, 1862],[{v:"Armenia", f:"Armenia"}, 3538, 146, 2061, 47, 1, 1430],[{v:"Aruba", f:"Aruba"}, 101, 0, 9, 3, 0, 89],[{v:"Australia", f:"<a href='https://smartable.ai/apps/coronavirus/stats/australia/'>Australia</a>"}, 6971, 0, 643, 97, 0, 6231],[{v:"Austria", f:"Austria"}, 15961, 79, 1190, 623, 3, 14148],[{v:"Azerbaijan", f:"Azerbaijan"}, 2693, 104, 980, 33, 1, 1680],[{v:"Bahamas", f:"Bahamas"}, 93, 0, 43, 11, 0, 39],[{v:"Bahrain", f:"Bahrain"}, 5409, 173, 3218, 9, 1, 2182],[{v:"Bangladesh", f:"Bangladesh"}, 16660, 969, 13263, 250, 11, 3147],[{v:"Barbados", f:"Barbados"}, 84, 0, 20, 7, 0, 57],[{v:"Belarus", f:"Belarus"}, 24873, 967, 17757, 142, 7, 6974],[{v:"Belgium", f:"Belgium"}, 53779, 330, 31286, 8761, 54, 13732],[{v:"Belize", f:"Belize"}, 18, 0, 0, 2, 0, 16],[{v:"Benin", f:"Benin"}, 327, 8, 249, 2, 0, 76],[{v:"Bermuda", f:"Bermuda"}, 119, 0, 45, 8, 0, 66],[{v:"Bhutan", f:"Bhutan"}, 11, 0, 6, 0, 0, 5],[{v:"Bolivia", f:"Bolivia"}, 2831, 0, 2410, 122, 0, 299],[{v:"Bosnia and Herzegovina", f:"Bosnia and Herzegovina"}, 2158, 17, 873, 117, 4, 1168],[{v:"Botswana", f:"Botswana"}, 24, 0, 11, 1, 0, 12],[{v:"Brazil", f:"Brazil"}, 172243, 2649, 92879, 11980, 327, 67384],[{v:"British Virgin Islands", f:"British Virgin Islands"}, 7, 0, 2, 1, 0, 4],[{v:"Brunei", f:"Brunei"}, 141, 0, 6, 1, 0, 134],[{v:"Bulgaria", f:"Bulgaria"}, 2023, 19, 1452, 95, 2, 476],[{v:"Burkina Faso", f:"Burkina Faso"}, 760, 0, 126, 50, 0, 584],[{v:"Burma", f:"Burma"}, 180, 0, 100, 6, 0, 74],[{v:"Cabo Verde", f:"Cabo Verde"}, 267, 7, 207, 2, 0, 58],[{v:"Cambodia", f:"Cambodia"}, 122, 0, 1, 0, 0, 121],[{v:"Cameroon", f:"Cameroon"}, 2689, 0, 1040, 125, 0, 1524],[{v:"Canada", f:"<a href='https://smartable.ai/apps/coronavirus/stats/canada/'>Canada</a>"}, 71368, 104, 58027, 5131, 15, 8210],[{v:"Cape Verde", f:"Cape Verde"}, 1, 0, 1, 0, 0, 0],[{v:"CAR", f:"CAR"}, 1, 0, 1, 0, 0, 0],[{v:"Cayman Islands", f:"Cayman Islands"}, 84, 0, 36, 1, 0, 47],[{v:"Central African Republic", f:"Central African Republic"}, 143, 0, 133, 0, 0, 10],[{v:"Chad", f:"Chad"}, 357, 35, 241, 40, 9, 76],[{v:"Channel Islands", f:"Channel Islands"}, 547, 1, 50, 42, 1, 455],[{v:"Chile", f:"Chile"}, 31721, 1658, 17261, 335, 12, 14125],[{v:"China", f:"<a href='https://smartable.ai/apps/coronavirus/stats/china/'>China</a>"}, 84012, 0, 0, 4637, 0, 80046],[{v:"Colombia", f:"Colombia"}, 11613, 0, 8309, 479, 0, 2825],[{v:"Costa Rica", f:"Costa Rica"}, 801, 0, 277, 7, 0, 517],[{v:"Cote d'Ivoire", f:"Cote d'Ivoire"}, 1730, 0, 891, 21, 0, 818],[{v:"Croatia", f:"Croatia"}, 2207, 11, 308, 91, 0, 1808],[{v:"Cruise Ship: Diamond Princess", f:"Cruise Ship: Diamond Princess"}, 712, 0, 48, 13, 0, 651],[{v:"Cuba", f:"Cuba"}, 1783, 0, 477, 77, 0, 1229],[{v:"Curacao", f:"Curacao"}, 16, 0, 1, 1, 0, 14],[{v:"Cyprus", f:"Cyprus"}, 903, 2, 438, 16, 0, 449],[{v:"Czechia", f:"Czechia"}, 8198, 21, 3050, 283, 0, 4865],[{v:"Democratic Republic of the Congo", f:"Democratic Republic of the Congo"}, 1102, 78, 912, 44, 3, 146],[{v:"Denmark", f:"Denmark"}, 10591, 78, 1730, 533, 0, 8328],[{v:"Djibouti", f:"Djibouti"}, 1227, 0, 352, 3, 0, 872],[{v:"Dominica", f:"Dominica"}, 16, 0, 1, 0, 0, 15],[{v:"Dominican Republic", f:"Dominican Republic"}, 10900, 266, 7277, 402, 9, 3221],[{v:"East Timor", f:"East Timor"}, 1, 0, 1, 0, 0, 0],[{v:"Ecuador", f:"Ecuador"}, 30419, 121, 24659, 2327, 182, 3433],[{v:"Egypt", f:"Egypt"}, 9746, 0, 7041, 533, 0, 2172],[{v:"El Salvador", f:"El Salvador"}, 998, 0, 631, 18, 0, 349],[{v:"Equatorial Guinea", f:"Equatorial Guinea"}, 439, 0, 422, 4, 0, 13],[{v:"Eritrea", f:"Eritrea"}, 39, 0, 1, 0, 0, 38],[{v:"Estonia", f:"Estonia"}, 1746, 5, 908, 61, 0, 777],[{v:"Eswatini", f:"Eswatini"}, 175, 0, 145, 2, 0, 28],[{v:"Ethiopia", f:"Ethiopia"}, 261, 11, 150, 5, 0, 106],[{v:"Faeroe Islands", f:"Faeroe Islands"}, 187, 0, 0, 0, 0, 187],[{v:"Faroe Islands", f:"Faroe Islands"}, 187, 0, 0, 0, 0, 187],[{v:"Fench Guiana", f:"Fench Guiana"}, 5, 0, 5, 0, 0, 0],[{v:"Fiji", f:"Fiji"}, 18, 0, 4, 0, 0, 14],[{v:"Finland", f:"Finland"}, 6003, 19, 1428, 275, 4, 4300],[{v:"France", f:"<a href='https://smartable.ai/apps/coronavirus/stats/france/'>France</a>"}, 177423, 0, 94056, 26643, 0, 56724],[{v:"French Guiana", f:"French Guiana"}, 144, 0, 21, 1, 0, 122],[{v:"French Polynesia", f:"French Polynesia"}, 60, 0, 4, 0, 0, 56],[{v:"Gabon", f:"Gabon"}, 802, 0, 666, 9, 0, 127],[{v:"Gambia", f:"Gambia"}, 22, 0, 11, 1, 0, 10],[{v:"Georgia", f:"<a href='https://smartable.ai/apps/coronavirus/stats/us-ga/'>Georgia</a>"}, 642, 3, 282, 11, 0, 349],[{v:"Germany", f:"<a href='https://smartable.ai/apps/coronavirus/stats/germany/'>Germany</a>"}, 172812, 236, 17936, 7676, 15, 147200],[{v:"Ghana", f:"Ghana"}, 5127, 427, 4611, 22, 0, 494],[{v:"Gibraltar", f:"Gibraltar"}, 147, 0, 4, 0, 0, 143],[{v:"Greece", f:"Greece"}, 2744, 18, 1218, 152, 1, 1374],[{v:"Greenland", f:"Greenland"}, 11, 0, 0, 0, 0, 11],[{v:"Grenada", f:"Grenada"}, 21, 0, 8, 0, 0, 13],[{v:"Guadeloupe", f:"Guadeloupe"}, 154, 0, 37, 13, 0, 104],[{v:"United States", f:"<a href='https://smartable.ai/apps/coronavirus/stats/us/'>United States</a>"}, 1385500, 9271, 1038343, 82288, 753, 264869],[{v:"Guatemala", f:"Guatemala"}, 1114, 0, 977, 26, 0, 111],[{v:"Guernsey", f:"Guernsey"}, 1, 0, 1, 0, 0, 0],[{v:"Guinea", f:"Guinea"}, 2213, 67, 1431, 11, 0, 771],[{v:"Guinea-Bissau", f:"Guinea-Bissau"}, 761, 0, 732, 3, 0, 26],[{v:"Guyana", f:"Guyana"}, 109, 0, 63, 10, 0, 36],[{v:"Haiti", f:"Haiti"}, 209, 0, 176, 16, 0, 17],[{v:"Holy See", f:"Holy See"}, 12, 0, 10, 0, 0, 2],[{v:"Honduras", f:"Honduras"}, 2100, 0, 1778, 116, 0, 206],[{v:"Hungary", f:"Hungary"}, 3313, 0, 1881, 425, 0, 1007],[{v:"Iceland", f:"Iceland"}, 1801, 0, 15, 10, 0, 1776],[{v:"India", f:"<a href='https://smartable.ai/apps/coronavirus/stats/india/'>India</a>"}, 73981, 3154, 47449, 2408, 114, 24124],[{v:"Indonesia", f:"Indonesia"}, 14749, 484, 10679, 1007, 16, 3063],[{v:"Iran", f:"<a href='https://smartable.ai/apps/coronavirus/stats/iran/'>Iran</a>"}, 110767, 1481, 15677, 6733, 48, 88357],[{v:"Iraq", f:"Iraq"}, 2913, 95, 898, 112, 2, 1903],[{v:"Ireland", f:"Ireland"}, 23242, 107, 4644, 1488, 21, 17110],[{v:"Isle of Man", f:"Isle of Man"}, 330, 0, 36, 23, 0, 271],[{v:"Israel", f:"Israel"}, 16526, 20, 4312, 258, 0, 11956],[{v:"Italy", f:"<a href='https://smartable.ai/apps/coronavirus/stats/italy/'>Italy</a>"}, 221216, 1402, 81266, 30911, 172, 109039],[{v:"Jamaica", f:"Jamaica"}, 505, 0, 406, 9, 0, 90],[{v:"Japan", f:"<a href='https://smartable.ai/apps/coronavirus/stats/japan/'>Japan</a>"}, 15847, 0, 6921, 633, 0, 8293],[{v:"Jersey", f:"Jersey"}, 2, 0, 2, 0, 0, 0],[{v:"Jordan", f:"Jordan"}, 576, 14, 177, 9, 0, 390],[{v:"Kazakhstan", f:"Kazakhstan"}, 5279, 39, 3139, 32, 0, 2108],[{v:"Kenya", f:"Kenya"}, 715, 15, 420, 36, 3, 259],[{v:"Kosovo", f:"Kosovo"}, 884, 0, 201, 28, 0, 655],[{v:"Kuwait", f:"Kuwait"}, 10277, 991, 7101, 75, 10, 3101],[{v:"Kyrgyzstan", f:"Kyrgyzstan"}, 1037, 0, 316, 12, 0, 709],[{v:"Laos", f:"Laos"}, 19, 0, 6, 0, 0, 13],[{v:"Latvia", f:"Latvia"}, 950, 4, 305, 18, 0, 627],[{v:"Lebanon", f:"Lebanon"}, 870, 11, 610, 26, 0, 234],[{v:"Liberia", f:"Liberia"}, 211, 0, 106, 20, 0, 85],[{v:"Libya", f:"Libya"}, 64, 0, 33, 3, 0, 28],[{v:"Liechtenstein", f:"Liechtenstein"}, 82, 0, 26, 1, 0, 55],[{v:"Lithuania", f:"Lithuania"}, 1491, 6, 591, 50, 0, 850],[{v:"Luxembourg", f:"Luxembourg"}, 3894, 6, 182, 102, 1, 3610],[{v:"Madagascar", f:"Madagascar"}, 193, 0, 92, 0, 0, 101],[{v:"Malaysia", f:"Malaysia"}, 6742, 16, 1410, 109, 0, 5223],[{v:"Maldives", f:"Maldives"}, 904, 7, 872, 3, 0, 29],[{v:"Mali", f:"Mali"}, 712, 0, 296, 39, 0, 377],[{v:"Malta", f:"Malta"}, 506, 3, 67, 5, 0, 434],[{v:"Martinique", f:"Martinique"}, 187, 0, 82, 14, 0, 91],[{v:"Mauritania", f:"Mauritania"}, 8, 0, 1, 1, 0, 6],[{v:"Mauritius", f:"Mauritius"}, 334, 0, 2, 10, 0, 322],[{v:"Mayotte", f:"Mayotte"}, 1023, 0, 520, 11, 0, 492],[{v:"Mexico", f:"Mexico"}, 36327, 0, 9654, 3573, 0, 23100],[{v:"Moldova", f:"Moldova"}, 4995, 0, 2840, 175, 0, 1980],[{v:"Monaco", f:"Monaco"}, 96, 0, 7, 4, 0, 85],[{v:"Mongolia", f:"Mongolia"}, 42, 0, 27, 0, 0, 15],[{v:"Montenegro", f:"Montenegro"}, 324, 0, 17, 9, 0, 298],[{v:"Montserrat", f:"Montserrat"}, 11, 0, 2, 1, 0, 8],[{v:"Morocco", f:"Morocco"}, 6418, 137, 3239, 188, 0, 2991],[{v:"Mozambique", f:"Mozambique"}, 103, 0, 69, 0, 0, 34],[{v:"MS Zaandam", f:"MS Zaandam"}, 9, 0, 7, 2, 0, 0],[{v:"Myanmar", f:"Myanmar"}, 180, 0, 100, 6, 0, 74],[{v:"Namibia", f:"Namibia"}, 16, 0, 5, 0, 0, 11],[{v:"Nepal", f:"Nepal"}, 217, 83, 184, 0, 0, 33],[{v:"Netherlands", f:"<a href='https://smartable.ai/apps/coronavirus/stats/netherlands/'>Netherlands</a>"}, 42984, 196, 37224, 5510, 54, 250],[{v:"New Caledonia", f:"New Caledonia"}, 18, 0, 0, 0, 0, 18],[{v:"New Zealand", f:"New Zealand"}, 1497, 0, 78, 21, 0, 1398],[{v:"Nicaragua", f:"Nicaragua"}, 16, 0, 4, 5, 0, 7],[{v:"Niger", f:"Niger"}, 832, 0, 149, 46, 0, 637],[{v:"Nigeria", f:"Nigeria"}, 4641, 0, 3589, 150, 0, 902],[{v:"North Macedonia", f:"North Macedonia"}, 1674, 10, 377, 92, 1, 1205],[{v:"Norway", f:"Norway"}, 8132, 0, 7876, 224, 0, 32],[{v:"Oman", f:"Oman"}, 3721, 148, 2454, 17, 0, 1250],[{v:"Pakistan", f:"Pakistan"}, 32674, 593, 23395, 724, 18, 8555],[{v:"Palestine", f:"Palestine"}, 375, 0, 55, 4, 0, 316],[{v:"Panama", f:"Panama"}, 8616, 0, 3680, 249, 0, 4687],[{v:"Papua New Guinea", f:"Papua New Guinea"}, 8, 0, 0, 0, 0, 8],[{v:"Paraguay", f:"Paraguay"}, 724, 0, 544, 10, 0, 170],[{v:"Peru", f:"Peru"}, 68822, 0, 44455, 1961, 0, 22406],[{v:"Philippines", f:"Philippines"}, 11350, 264, 8493, 751, 25, 2106],[{v:"Poland", f:"Poland"}, 16921, 595, 9951, 839, 28, 6131],[{v:"Portugal", f:"Portugal"}, 27913, 234, 23737, 1163, 19, 3013],[{v:"Qatar", f:"Qatar"}, 25149, 1526, 22116, 14, 0, 3019],[{v:"Republic of the Congo", f:"Republic of the Congo"}, 333, 0, 269, 11, 0, 53],[{v:"Reunion", f:"Reunion"}, 436, 0, 82, 0, 0, 354],[{v:"Romania", f:"Romania"}, 15778, 190, 7091, 1002, 20, 7685],[{v:"Russia", f:"Russia"}, 232243, 10899, 186615, 2116, 107, 43512],[{v:"Rwanda", f:"Rwanda"}, 285, 0, 135, 0, 0, 150],[{v:"Saint Barthelemy", f:"Saint Barthelemy"}, 6, 0, 0, 0, 0, 6],[{v:"Saint Kitts and Nevis", f:"Saint Kitts and Nevis"}, 15, 0, 1, 0, 0, 14],[{v:"Saint Lucia", f:"Saint Lucia"}, 18, 0, 1, 0, 0, 17],[{v:"Saint Martin", f:"Saint Martin"}, 39, 0, 6, 3, 0, 30],[{v:"Saint Vincent and the Grenadines", f:"Saint Vincent and the Grenadines"}, 17, 0, 8, 0, 0, 9],[{v:"San Marino", f:"San Marino"}, 638, 1, 436, 41, 0, 161],[{v:"Saudi Arabia", f:"Saudi Arabia"}, 42925, 1911, 27404, 264, 9, 15257],[{v:"Senegal", f:"Senegal"}, 1995, 109, 1234, 19, 0, 742],[{v:"Serbia", f:"Serbia"}, 10243, 67, 6423, 220, 2, 3600],[{v:"Seychelles", f:"Seychelles"}, 11, 0, 1, 0, 0, 10],[{v:"Singapore", f:"<a href='https://smartable.ai/apps/coronavirus/stats/singapore/'>Singapore</a>"}, 24671, 849, 20799, 21, 0, 3851],[{v:"Sint Maarten", f:"Sint Maarten"}, 76, 0, 15, 15, 0, 46],[{v:"Slovakia", f:"Slovakia"}, 1465, 8, 455, 27, 1, 983],[{v:"Slovenia", f:"Slovenia"}, 1461, 1, 1100, 102, 0, 259],[{v:"Somalia", f:"Somalia"}, 1170, 81, 992, 52, 0, 126],[{v:"South Africa", f:"South Africa"}, 11350, 698, 6787, 206, 0, 4357],[{v:"South Korea", f:"<a href='https://smartable.ai/apps/coronavirus/stats/south-korea/'>South Korea</a>"}, 10936, 0, 1008, 258, 0, 9670],[{v:"Spain", f:"<a href='https://smartable.ai/apps/coronavirus/stats/spain/'>Spain</a>"}, 269520, 1377, 62130, 26920, 176, 180470],[{v:"Sri Lanka", f:"Sri Lanka"}, 884, 15, 509, 9, 0, 366],[{v:"Sudan", f:"Sudan"}, 1526, 0, 1290, 74, 0, 162],[{v:"Suriname", f:"Suriname"}, 10, 0, 0, 1, 0, 9],[{v:"Sweden", f:"<a href='https://smartable.ai/apps/coronavirus/stats/sweden/'>Sweden</a>"}, 27272, 602, 18988, 3313, 57, 4971],[{v:"Switzerland", f:"<a href='https://smartable.ai/apps/coronavirus/stats/switzerland/'>Switzerland</a>"}, 30380, 36, 1713, 1867, 22, 26800],[{v:"Syria", f:"Syria"}, 47, 0, 13, 5, 0, 29],[{v:"Taiwan", f:"Taiwan"}, 440, 0, 61, 7, 0, 372],[{v:"Tanzania", f:"Tanzania"}, 509, 0, 305, 21, 0, 183],[{v:"Thailand", f:"Thailand"}, 3017, 0, 163, 56, 0, 2798],[{v:"The Bahamas", f:"The Bahamas"}, 93, 0, 43, 11, 0, 39],[{v:"The Gambia", f:"The Gambia"}, 22, 0, 11, 1, 0, 10],[{v:"Timor-Leste", f:"Timor-Leste"}, 24, 0, 3, 0, 0, 21],[{v:"Togo", f:"Togo"}, 181, 0, 81, 11, 0, 89],[{v:"Trinidad and Tobago", f:"Trinidad and Tobago"}, 116, 0, 1, 8, 0, 107],[{v:"Tunisia", f:"Tunisia"}, 1032, 0, 260, 45, 0, 727],[{v:"Turkey", f:"Turkey"}, 141475, 1704, 38692, 3894, 53, 98889],[{v:"Turks and Caicos", f:"Turks and Caicos"}, 12, 0, 3, 1, 0, 8],[{v:"Turks and Caicos Islands", f:"Turks and Caicos Islands"}, 12, 0, 3, 1, 0, 8],[{v:"Uganda", f:"Uganda"}, 122, 1, 67, 0, 0, 55],[{v:"Ukraine", f:"Ukraine"}, 16023, 0, 12225, 425, 0, 3373],[{v:"United Arab Emirates", f:"United Arab Emirates"}, 19661, 783, 13446, 203, 2, 6012],[{v:"United Kingdom", f:"<a href='https://smartable.ai/apps/coronavirus/stats/uk/'>United Kingdom</a>"}, 226463, 3403, 193427, 32692, 627, 344],[{v:"Uruguay", f:"Uruguay"}, 711, 0, 169, 19, 0, 523],[{v:"Uzbekistan", f:"Uzbekistan"}, 2519, 10, 499, 10, 0, 2010],[{v:"Venezuela", f:"Venezuela"}, 422, 0, 201, 16, 0, 205],[{v:"Vietnam", f:"Vietnam"}, 288, 0, 36, 0, 0, 252],[{v:"West Bank and Gaza", f:"West Bank and Gaza"}, 495, 0, 175, 4, 0, 316],[{v:"Zambia", f:"Zambia"}, 441, 174, 317, 7, 0, 117],[{v:"Zimbabwe", f:"Zimbabwe"}, 40, 0, 27, 4, 0, 9],[{v:"Sierra Leone", f:"Sierra Leone"}, 338, 0, 247, 19, 0, 72],[{v:"Burundi", f:"Burundi"}, 15, 0, 7, 1, 0, 7],[{v:"Caribbean Netherlands", f:"Caribbean Netherlands"}, 6, 0, 6, 0, 0, 0],[{v:"Malawi", f:"Malawi"}, 57, 0, 30, 3, 0, 24],[{v:"Falkland Islands", f:"Falkland Islands"}, 13, 0, 0, 0, 0, 13],[{v:"Western Sahara", f:"Western Sahara"}, 6, 0, 0, 0, 0, 6],[{v:"Saint Pierre Miquelon", f:"Saint Pierre Miquelon"}, 1, 0, 0, 0, 0, 1],[{v:"South Sudan", f:"South Sudan"}, 156, 0, 154, 0, 0, 2],[{v:"Sao Tome and Principe", f:"Sao Tome and Principe"}, 208, 0, 199, 5, 0, 4],[{v:"Yemen", f:"Yemen"}, 65, 9, 54, 10, 1, 1],[{v:"Falkland Islands (Malvinas)", f:"Falkland Islands (Malvinas)"}, 13, 0, 0, 0, 0, 13],[{v:"Saint Pierre and Miquelon", f:"Saint Pierre and Miquelon"}, 1, 0, 0, 0, 0, 1],[{v:"Tajikistan", f:"Tajikistan"}, 661, 0, 640, 21, 0, 0],[{v:"Comoros", f:"Comoros"}, 11, 0, 10, 1, 0, 0],
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

