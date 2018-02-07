# zfs-prometheus-collector

This collects analytics from an Oracle ZFS Appliance. It uses requests to scrape the API for measurements, and parses them into Prometheus metrics classes.

The metrics classes are stored in 
the urls are store in urls.py. They can be customized to add additional analytics. 

