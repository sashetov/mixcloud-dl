# Mixcloud Downloader v1.1
## build
```bash
./build.sh 
```
## run
```bash
./mixcloud-dl MIXCLOUD_URL (NUM_PROC)
```
## usage
```
USAGE: ./mixcloud_dl.py [MIXCLOUD_URL] (NUM_PROC)

NOTE: args in [] are required
      args in () are not
```
## description
- Downloads mixcloud stream in chunks in parallel and recombines to form mp4 file
- Now is run in parallel with subprocesses ( default is number of cores )
## license
http://www.wtfpl.net/about/
