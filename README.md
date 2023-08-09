ffmpeg -i rtmp://[IP]:80/live-record/SSAE-416514-DFDCB -c:v copy -c:a aac -f flv rtmp://localhost:1935/live/SSAE-416514-DFDCB

ffplay http://[IP]:8000/live/SSAE-416514-DFDCB/index.mpd

 while true; do ffmpeg -re -i output.mp4 -c copy -f flv rtmp://localhost/live/5; done

 
wget --load-cookies /path/to/cookies.txt "https://docs.google.com/uc?export=download&confirm=$(wget --quiet --save-cookies /path/to/cookies.txt --keep-session-cookies --no-check-certificate 'https://docs.google.com/uc?export=download&id=1UXCPAAAJNBuDfyAZXt2kog7_1fkbKv17' -O- | sed -rn 's/.*confirm=([0-9A-Za-z_]+).*/\1\n/p')&id=1UXCPAAAJNBuDfyAZXt2kog7_1fkbKv17" -O output.mp4
