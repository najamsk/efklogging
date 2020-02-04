

max virutal memory areas issue: vm.max_map_count [65530] is too low, increase to at least [262144]
sudo sysctl -w vm.max_map_count=262144



docker run --log-driver=fluentd --log-opt fluentd-address=192.168.0.42:24224 hello-world
