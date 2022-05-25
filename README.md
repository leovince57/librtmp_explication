# librtmp_explication

## Study Guide

1. overall procedure
[markdown files](explication)

2. source code line by line explication
```
/// parse file from flv path for metadata
/// metadata include flv duration and some other basic infos
// read flv script data payload
nStatus = OpenResumeFile(flvFile, &file, &size, &metaHeader, &nMetaHeaderSize, &duration);
```
The first two lines are explication

