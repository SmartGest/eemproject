<html>
<head>
<script type="text/javascript"
  src="dygraph-combined-dev.js"></script>
</head>
<body>
<div id="graphdiv3"
  style="width:500px; height:300px;"></div>
<script type="text/javascript">
  g3 = new Dygraph(
    document.getElementById("graphdiv3"),
    "temperatures.csv",
    {
      rollPeriod: 7,
      showRoller: true,
      ylabel: 'Temperature (F)'
    }
  );
</script>
</body>
</html>
