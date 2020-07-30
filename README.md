# Ovpn_config
Configurator for openvpn on a linux server.
This is a bash script that with user interactions to help the user setup a linux server so that it can route connection to another linux server which is called the client trough openvpn software.
The client in this configuration has a constans ip address attached to it which is 10.8.0.6/32 so the script (and you) are able to tunnel the connection.
If you want a windows os as a client then you should edit the base.conf file because it is deafultly set to linux users.
