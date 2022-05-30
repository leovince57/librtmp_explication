# librtmp_explication
This project aims to help developers better learning the **rtmp protocol**, the librtmp **source code** has related **streaming media knowledge**。

## About RTMP
Before entering the whole project you can read the following article to get a general understanding of rtmp.\
https://ottverse.com/rtmp-real-time-messaging-protocol-encoding-streaming/ \
And the wiki is here to help you check, there is no need to delve into the details.\
[RTMP Wiki](https://en.wikipedia.org/wiki/Real-Time_Messaging_Protocol#Connect)

## Study Guide

1. overall procedures are in
[explication directory](explication)

2. source code line by line explication
```
/// parse file from flv path for metadata
/// metadata include flv duration and some other basic infos
// read flv script data payload
nStatus = OpenResumeFile(flvFile, &file, &size, &metaHeader, &nMetaHeaderSize, &duration);
```
The first two lines are explication


## How to get involved
If you have your own understanding of the source code of librtmp, you can participate in the project and submit a merge-request.

