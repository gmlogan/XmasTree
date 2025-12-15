## Build with command line esphome

Enable the Python virtual env
```
source venv/bin/activate
```
Install esphome, noting along version to espbuilder add-in of Home Assistant, eg 
```
pip3 install esphome==2025.6.3
```

### Compile
```
esphome compile your_code.yaml
```

### Flash over wifi
```
esphome run your_code.yaml --device 192.168.xxx.yyy
```
Make sure your secretys.yaml file is updated, the example in this repo should be renamed from _secrets.yaml to secrets.yaml (not NOT .secrets.yaml)


