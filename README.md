# iotsensing
iotsensingstack
Sensors Supported :
1.Temprature
2.Humidity
3.Pressure
4.UV
5.Light
6.IR
7.Sound
8.Dust partical

To Run the application on the Board
1. Connect the sensor as per the wiring digarms in the wiki
1. On host
  # scp Debug/IoTSensing [ipaddress]/home/[prefered directory]
2.On Target
   # systemctl start iotkit-agent
   #./IoTSensing

