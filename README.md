# sdn-app-dev
SDN Applications Development using Ryu framework on Docker


### Usage

Runs simple_switch_13.py application in interactive mode

Docker port 6633 -> Host port 5566
```
docker run -it -p 0.0.0.0:5566:6633 --rm linton/ryu ./bin/ryu-manager ./ryu/myapp/simple_switch_13.py
```

Runs simple_switch.py application in detached mode

Docker port 6633 -> Host port 5566
```
docker run -d -p 0.0.0.0:5566:6633 --rm linton/ryu ./bin/ryu-manager ./ryu/myapp/simple_switch_13.py
```
