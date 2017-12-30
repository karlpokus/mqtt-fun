# mqtt-fun
playing with the mqtt protocol

# usage
```bash
# simple
$ node ./simple/simple.js
# garage door example
$ tmux
$ node ./garageDoor/controller.js
$ node ./garageDoor/garage.js
```

# todos
- [x] [simple node tut](https://blog.risingstack.com/getting-started-with-nodejs-and-mqtt/)
- [x] [complete js client](https://github.com/mqttjs/MQTT.js) (includes a cli)

# dyi
- [ ] [mqtt parser](https://github.com/mqttjs/mqtt-packet)
- [ ] [bare bones connection](https://github.com/mqttjs/mqtt-connection)
- [ ] parse and create packets
- [ ] send pings and pongs

# Refs
- [the docs](http://docs.oasis-open.org/mqtt/mqtt/v3.1.1/os/mqtt-v3.1.1-os.html)
- [mqtt broker](https://mosquitto.org/)

# license
MIT
