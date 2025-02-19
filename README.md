Air pollution has become a significant concern affecting human health and the
environment. To address this issue, we propose an IoT-based Air Quality Monitoring System
utilizing the Controller Area Network (CAN) protocol for reliable and efficient data
transmission. The system comprises two ESP32 microcontrollers, where the first ESP32
collects real-time air quality data using multiple sensors, including the Nova PM SDS011 (for
particulate matter), DHT22 (for temperature and humidity), and MQ135 (for detecting harmful
gases). The collected data is displayed on a 0.96-inch OLED screen and transmitted via the
MCP2515 CAN module to the second ESP32.
The second ESP32 receives the data over CAN communication, processes it, and sends it to
ThingSpeak, a cloud-based IoT analytics platform, for remote monitoring and analysis. This
system ensures low-latency, robust, and interference-free communication using the CAN
protocol, making it suitable for industrial and environmental applications. The proposed
system provides real-time monitoring, remote accessibility, and improved data reliability,
making it a cost-effective solution for air quality assessment.
