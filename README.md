# PironmanPi5
# Project Overview: 
Real-Time Network Traffic Analyzer
# Goal: 
Monitor network activity, including device usage, web searches, visited websites, streaming time, and content analysis.

# Core Components & Tools

### Network Sniffing & Traffic Analysis Tools:

> #### Pi-hole: 
>- For DNS-level ad-blocking and tracking web domains queried.
> #### ntopng: 
>- A network monitoring tool with detailed traffic insights.
> #### Wireshark or Tshark: 
>- For deeper packet inspection.
> #### Suricata: 
>- For network intrusion detection and traffic logging.
> #### Data Storage & Logging:
>- Use dual NVMe for storing historical network data logs.
> #### InfluxDB and Grafana:
>- For data visualization and reporting.
> #### Media Content Analysis:
>- Use Machine Learning models with TensorFlow Lite to scan and analyze media files or streaming activity metadata if accessible.
> #### Dashboard & Notifications:
>- Set up a web-based dashboard with Grafana for real-time monitoring.
Trigger notifications using email or services like Pushover or Telegram for suspicious activity.
> #### OLED Display Integration:
>- Display live stats such as devices connected, top websites visited, and bandwidth usage.
> #### RGB Lighting for Alerts:
>- Configure lights to change based on specific activity thresholds (e.g., red for high data use or risky sites).

### How to Build It:
> #### Network Setup:
> Configure the Raspberry Pi as a network gateway/router using tools like OpenWRT or RaspAP.
Use port mirroring on your home router if direct network monitoring isn't possible.
> 
> Data Collection & Analysis:   
> Set up Pi-hole for DNS logging.
> #### Install ntopng and Suricata:</br>
> For deeper traffic inspection.
> 
> #### Use Elastic Stack (ELK):
> 
> For centralized logging if you want detailed logs and analysis.
> 
> #### Device Identification:
>Use MAC address fingerprinting to track devices individually.
Implement device aliases for easier identification.
> 
> #### Privacy Considerations:
>- Ensure sensitive data is encrypted.
>- Provide privacy alerts for monitored users.
> #### Visual Feedback:
>- Optionally configure the OLED to display live network usage stats.
>- Create a custom UI with Flask or Node.js for a real-time dashboard.
> #### Data Retention & Backup:
>- Use the dual NVMe for long-term data storage and RAID 1 redundancy.
>- Automate backups with cron jobs or rsync.
 ### Advanced Features to Add:
> #### Parental Controls: 
> Block certain sites or set screen time limits.
> #### AI-Powered Analysis:
> Use AI models to detect potentially harmful or concerning usage patterns.
> #### Streaming Content Analysis: 
> Scrape public streaming service APIs to analyze viewing history if such features are open.

### Link to SunFounder Site 

- [SunFounder Pironman 5 Project](https://www.sunfounder.com/products/pironman-5-nvme-m-2-ssd-pcie-mini-pc-case-for-raspberry-pi-5?variant=45654310584555)

### Pironman Reviews
- [Pironman 5 Review 1](https://magpi.raspberrypi.com/articles/pironman-5-case-review?mc_cid)

- [Pironman 5 Review 2](https://itsfoss.com/pironman-5-review/)

- [Pironman 5 Review 3](https://www.cnx-software.com/2024/07/28/pironman-5-review-mini-pc-case-for-the-raspberry-pi-5-sbc/)
