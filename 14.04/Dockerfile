from ubuntu:14.04
run apt-get update 
run  apt-get install -y curl git
run apt-get install -y wget
run wget -O - https://files.freeswitch.org/repo/ubuntu/freeswitch-unstable/freeswitch_archive_g0.pub | apt-key add -
 
run echo "deb http://files.freeswitch.org/repo/ubuntu/freeswitch-unstable/ trusty main" > /etc/apt/sources.list.d/freeswitch.list
 
# you may want to populate /etc/freeswitch at this point.
# if /etc/freeswitch does not exist, the standard vanilla configuration is deployed
run apt-get update
run  apt-get install -y freeswitch-all 
