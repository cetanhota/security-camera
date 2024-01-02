# security-camera
Raspberry Pi Security Camera

 nohup ./mjpg_streamer -i "input_raspicam.so" -o "output_http.so -p 8080 -w /home/pi/mjpg-streamer/www" &
 nohup ffmpeg -y -i http://backyard.local:8080/?action=stream /camera/camera-backyard.avi &