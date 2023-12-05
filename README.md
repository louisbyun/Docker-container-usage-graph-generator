# Docker-container-usage-graph-generator
Docker container usage graph generator

1. CPU Usage Plot:
Each Docker container's CPU usage percentage is plotted over time.

2. Memory Usage Plot:
Memory usage for each container is plotted over time.

The resulting plots are saved as an image file ('docker_stats_graph.png') and displayed on the screen. 
![docker_stats_graph](https://github.com/louisbyun/Docker-container-usage-graph-generator/assets/55345082/fdc5b9f2-65a1-493f-8b86-0951d43fd877)

The code uses the matplotlib.pyplot and pandas libraries for plotting and data manipulation, respectively. 
The title of the graph indicates that it represents CPU and memory usage over time for two Docker containers named Visualizer and EVAM.
