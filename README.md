usshoustondive.com
==================

USS Houston (CA-30) Dive Team website

To generate the website:
  ttree -f ttree.cfg

Jay syncs the Dropbox images over to the website like so:
  rsync -av --progress --delete \
    ~/Dropbox/houston\ file/images jays.net:/var/www/usshoustondive.com/assets/

