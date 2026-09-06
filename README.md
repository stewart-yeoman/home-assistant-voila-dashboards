# home-assistant-voila-dashboards
**Jupyter notebooks with ipywidgets that can be used in HomeAssistant with Voila**

If you have the [HomeAssistant Jupyter Add-on/App](https://github.com/hassio-addons/app-jupyterlab) (packaged by Franck Nijhof) installed, you can use the Voila dashboard feature of Jupyter to display notebooks as dashboards inside HomeAssistant.  You can pack your notebooks with all kinds of explanatory markdown, but have Voila only display your final widgets.

Here are screenshots from my HomeAssistant installation:

The notebook in this repo named **docker_disk_space.ipynb** uses the Plotly sunburst graph and ipydatagrid to display Docker disk usage by Home Assistant:
![Docker Disk Space](images/docker_disk_space.png?raw=true "Docker Disk Space")

https://github.com/user-attachments/assets/ac833a3d-086e-434d-b790-96475452da14




The notebook in this repo named **influx_conntrack_3D_voila.ipynb** uses the Plotly Scatterplot3D widget to display network traffic.

*For this notebook I used the [HomeAssistant InfluxDB Add-on/App](https://community.home-assistant.io/t/home-assistant-community-add-on-influxdb/54491) that was packaged by Franck Nijhof.  Sadly, he just archived this repo last week (end of August, 2026)!  I guess I'll upgrade to [this one](https://community.home-assistant.io/t/home-assistant-add-on-influxdb-v2/617977) that was packaged by Daniel Oldberg.*
![Network Traffic Display](images/network_traffic_display.png?raw=true "Network Traffic Display")

[network2.webm](https://github.com/user-attachments/assets/c2a92f01-ca57-4a57-ab40-005c90358bb1)


Both these notebooks depend on some setup which is described in the notebook: **luxury_notebook_environment.ipynb**
