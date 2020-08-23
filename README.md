# Atrtribute Log Server
Attribute Server is a python based server module used to log attributes emitted by AttributeDumpingHandler of Elytron. It is an integral part of Intrusion Detection System project & will log attributes of http events, which will be used to train the machine learning model for anomaly detection.


### Getting Started
To clone the project in your local systems: 
```console
$ git clone https://github.com/piyush-palta/attribute-log-server.git
```

### Prerequisites
Make sure you have installed all of the following prerequisites on your development machine:
* Git - [Download & Install Git](https://git-scm.com/downloads). OSX and Linux machines typically have this already installed.
* Python - [Download & Install Python](https://www.python.org/downloads/). For linux machines, you can also use this [Python Docs](https://docs.python-guide.org/starting/install3/linux/) to install Python.
* pip - [Download & Install pip](https://pip.pypa.io/en/stable/installing/). Make sure you've installed python first.

### Installing

The below command will start the syslog server :

```bash
$ python main.py
```

To configure host, tcp_port, udp_port & log file location :
  
```bash
$ python main.py host_name tcp_port udp_port log_file
```
