# vagrantfile-alsa
Minimal Vagrantfile to make ALSA work on Ubuntu/Trusty guest on Mac OS (Tested on 10.11)
   
   1. vagrant up (wait for a min as it reboots guest after provisioning)
   2. vagrant ssh
   3. aplay /usr/share/sounds/alsa/Front_Center.wav 

You should hear sound after step #3
