i)Firstly install mqtt package
Enter following command in your command prompt:
```bash
nmp install mqtt --save
```


ii)Use following details for sub/pub message on a public broker:
```bash
    Host: 'broker.hivemq.com'
    TCP Port: '1883'
    Websocket Port: '8000'
```

iii)You can subscribe or publish from your device in a single time.

iv)To use command promp  as user your one of client then 
```bash
i)For Subscribe:
mosquitto_sub -h "broker.hivemq.com" -p "1883" -t "topic/tushar/#"
    
ii)For Publish:
mosquittp_pub -h "broker.hivemq.com" -p "1883" -m "hello, this is msg from nodejs client" -t "topic/tushar"
```
v)To use command prompt as one of your client, you need to install mqtt broker in your device.

vi)IP address of the comp: `192.168.56.1`