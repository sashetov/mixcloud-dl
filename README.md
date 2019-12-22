# Mixcloud downloader v1.1
## build
```bash
./build.sh 
```
## run
```
./mixcloud-dl MIXCLOUD_URL (NUM_PROC)
```
## USAGE
USAGE: ./mixcloud_dl.py [MIXCLOUD_URL] (NUM_PROC)

NOTE: args in [] are required
      args in () are not
## DESCRIPTION:
downloads mixcloud stream in chunks in parallel (with optional number of 
subprocesses and recombines to form mp4 file, which you can convert with
your favorite ffmpeg -i in out command to mp3 or other format
## LICENSE
http://www.wtfpl.net/about/
