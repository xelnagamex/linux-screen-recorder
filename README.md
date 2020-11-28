# linux-screen-recorder


Useful bash script for ease recoding your screen on linux using slop and ffmpeg.

### Dependencies

* slop
* ffmpeg
 
 
### Installation

```bash
git clone https://github.com/xelnagamex/linux-screen-recorder.git /tmp/linux-screen-recorder
sudo cp tmp/linux-screen-recorder/recvid /usr/local/bin/recvid
chmod +x /usr/local/bin/recvid
```


### Usage

```bash
recvid
#select screen region
#q or ctrl+c ffmpeg terminal to stop recording
#new mp4 file appears in your home dir
