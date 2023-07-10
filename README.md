ffmpeg -i rtmp://[IP]:80/live-record/SSAE-416514-DFDCB -c:v copy -c:a aac -f flv rtmp://localhost:1935/live/SSAE-416514-DFDCB

ffplay http://[IP]:8000/live/SSAE-416514-DFDCB/index.mpd
