uniinstall software + dependencies
 
sudo pacman -Rns

remove all dependencies that none doesn't need at all

sudo pacman -Qtdq | sudo pacman -Rns -

command for record

wf-recorder -f out.mkv --codec h264_vaapi -r 60

ctrl+c

v4l2-ctl --list-devices

ffplay /dev/video2
