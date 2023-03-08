# bitnode
IoT device for monitoring purposes. It uses protobuf messages. It connects to a backend using secure connections (SSL, TLS). Firmware developed in C/C++.

## features
- Connects to a WiFi router using SSID and Pass.
- Uses TCP socket to send data to an endpoint.
- Reads just one sensor at periodic time.
- Sends data at periodic time.
- Reads battery level before sending any data.
- Reads RTC to get timestamp.
- All parameters can be set during build time.