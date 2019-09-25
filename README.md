# iot_tardis_demo_home
 IoT TARDIS Project Demo Home page

## TO DO

- [ ] review under "Live Interactive Demo" account credential inclusion
- [ ] substitute "motion" for "cam2ip" for existing webcam driver
  - https://motion-project.github.io/4.2.2/motion_config.html#basic_setup_picam
  - https://ffmpeg.org/ffmpeg-all.html#video4linux2_002c-v4l2
  - https://medium.com/@petehouston/streaming-mjpg-from-webcam-to-rtsp-using-vlc-7b732926cc3d
  - https://www.instructables.com/id/How-to-turn-an-USB-camera-with-Raspberry-Pi-into-a/
  - https://github.com/jacksonliam/mjpg-streamer
  - https://www.raspberrypi.org/forums/viewtopic.php?f=43&t=45178
  - [x] https://www.instructables.com/id/How-to-turn-an-USB-camera-with-Raspberry-Pi-into-a/
  - [x] http://raspi3b:8080/%20?action=stream.
  - [ ] https://www.acmesystems.it/video_streaming
  - [x] ./mjpg_streamer -i "./input_uvc.so -r 1280x720" -o "./output_http.so -w ./www"
  - [x] http://raspi3b:8080/javascript_simple.html
  - [ ] https://www.raspberrypi.org/forums/viewtopic.php?f=43&t=45178
  - [x] /usr/local/www
  - [ ] https://sourceforge.net/projects/mjpg-streamer/
  - [ ] https://github.com/cncjs/cncjs/wiki/Setup-Guide:-Raspberry-Pi-%7C-MJPEG-Streamer-Install-&-Setup-&-FFMpeg-Recording
  - [ ] https://askubuntu.com/questions/214977/how-can-i-find-out-the-supported-webcam-resolutions
  - [x] v4l2-ctl --list-formats-ext  [list all formats]
  - [ ] modify node-red garbage collection https://discourse.nodered.org/t/memory-leak-what-am-i-doing-wrong/627/13
  The nodered.service file in /lib/systemd/system/ contains the --max_old_space_size=256 parameter that is used to set when the Garbage collection kicks in… BUT it is only a guide as the GC in node.js is “lazy” in that it doesn’t kick in until the limits are exceeded - so a) it will always appear like it is leaking memory as the GC won’t kick in all the time and b) if you are near the limit and then handle a few “large” objects then you may well blow way past it. We picked 256 to try to be too greedy with Pi memory but feel free to tune as you see fit.
		- https://discourse.nodered.org/t/memory-leakage-of-node-red-on-raspi/552
		- https://marmelab.com/blog/2018/04/03/how-to-track-and-fix-memory-leak-with-nodejs.html
		- /etc/systemd/system/multi-user.target.wants/nodered.service
        - /lib/systemd/system/nodered.service
        - https://www.cyberciti.biz/faq/how-to-restart-a-process-out-of-crontab-on-a-linuxunix/
        - 