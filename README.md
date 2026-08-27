For Elecrow 7 HMI ESP2-s3 With 4MB FLash Using Home Assistant
(Also Known as IoTeikXgo on Amazon)

Graphite Theme Set To E-ink On Home Assistant Works the best

If the image is too big for flash, Merge your app partitions:

copy C:\esphb\[DeviceFolder]-\build\elecrow-hmi-7\partitions.csv and rename the copy to custom_partitions.csv, replace the lines within then flash
 
otadata, data, ota, , 0x2000,
phy_init, data, phy, , 0x1000,
app0, app, ota_0, , 0x300000,
nvs, data, nvs, , 0x70000,
