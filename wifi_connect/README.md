The official examples were using a C++ version that wasn't compatible with my arduino IDE's, so this fixes that.

*NOTE*
Don't forget to enable the logging in the IDE! For the version I'm using now, it's `Tools > Core Debug Level`. Select "info". Change
```
#define EXAMPLE_ESP_WIFI_SSID      "network name"
#define EXAMPLE_ESP_WIFI_PASS      "password"
```
to the network and password you want to connect to. 
