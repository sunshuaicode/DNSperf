# DNSperf
- [English](README.md) | [中文](README_ZH.md)  

DNSperf is a DNS server performance tester that can help you choose the most suitable DNS for your local network.
# How to use
You can add domain name that you want to test the DNS in domain_names.json.
```json
[
    "www.github.com",
    "www.baidu.com"
]
```
You can add DNS server that you want to test in dns_server.json.
```json
[
    {
        "name":"Google DNS",
        "ip":"8.8.8.8"
        },
    {
        "name":"Alibaba DNS",
        "ip":"223.5.5.5"
    }
]
```
# Develop Environment
- Python 3.12.3  

Yon can download from https://www.python.org/.
# Dependent Libraries
- dnspython 2.7.0
- numpy 2.1.3
- pandas 2.2.3  

Run the following code in bash (Linux) or cmd (Windows) to install dependency libraries.
```cmd
pip install dnspython
pip install numpy
pip install pandas
```
Run in DNSperf path.
```cmd
python DNSperf.py
```
