# Jmeter-Monitoring-Dashboard
Using Jmeter to perform test on API use the results from test to Graph Stuffs on Dashboard. This will be a repurposed API monitoring tool.

- Setup Jmeter to launch with Bash Script
- Have it Load test, automatically with Bash
- Have Bash start job that moves files once an hour to SQL should do FAT insert.


# Will Need:
- Machine that executed jmeter script per minute and moves Data to cloud can live in docker Image
- Machine that connects and displays data fron the CLOUD SQL --- Currently Grafana
- Machine that will run InfluxDB to store timeSeries
- Grafana will display InfluxDB data as datasource
- Grafana will be used to visualize
- Grafana configure Data Sources


# Look Into:
- Repurposing Automatic Dashboard Generation from jmeter Script.
- https://www.blazemeter.com/blog/how-to-use-grafana-to-monitor-jmeter-non-gui-results
- Seems Easy just update Dependencies https://github.com/BushnevYuri/DockerGrafanaInfluxKit

