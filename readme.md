# Logstash Palo Alto Filter

#### Results on stdout
```
{
    "receive_time": "Jun  7 10:40:02",
    "session_id": "1",
    "time_generated": "2017/06/07 10:40:02",
    "repeat_count": "1",
    "message":"Jun  7 10:40:02 10.10.10.47 PAN-PA-5050-BSI-UII.bsi.uii.ac.id/ 1,2017/06/07 10:40:02,002201003950,THREAT,url,1,2017/06/07 10:40:02,10.100.41.1$",
    "type": "THREAT",
    "url": "PAN-PA-5050-BSI-UII.bsi.uii.ac.id/",
    "source_ip": "10.10.10.47",
    "path": "path/to/palo-alto.log",
    "other_timestamp": "2017/06/07 10:40:02",
    "@timestamp": "2017-08-08T06:08:31.245Z",
    "serial": "002201003950",
    "sub_type":"url",
    "dest_ip":"10.100.41.1",
    "@version":"1",
    "host":"MacBook-Air.local"
}
{
    "receive_time": "Jun  7 10:40:02",
    "session_id": "1",
    "time_generated": "2017/06/07 10:40:02",
    "repeat_count": "1",
    "message": "Jun  7 10:40:02 10.10.10.47 PAN-PA-5050-BSI-UII.bsi.uii.ac.id/ 1,2017/06/07 10:40:02,002201003950,THREAT,url,1,2017/06/07 10:40:02,10.100.41.1$",
    "type": "THREAT",
    "url": "PAN-PA-5050-BSI-UII.bsi.uii.ac.id/",
    "source_ip": "10.10.10.47",
    "path": "path/to/palo-alto.log",
    "other_timestamp": "2017/06/07 10:40:02",
    "@timestamp":" 2017-08-08T06:08:31.247Z",
    "serial": "002201003950",
    "sub_type": "url",
    "dest_ip": "10.100.41.1",
    "@version": "1",
    "host": "MacBook-Air.local"
}
```
