## To clone just this branch
git clone -b my-branch https://git@github.com/username/myproject.git


# ENOSPEC Error
http://stackoverflow.com/questions/22475849/node-js-error-enospc
(Ensure Docker permissions are enabled in advanced nitrous options for the (paid) workstation), then run:
     echo fs.inotify.max_user_watches=524288 | sudo tee -a /etc/sysctl.conf && sudo sysctl -p

The following may also fix:
     npm dedupe


## Allowing more temp space before update
mkdir ~/temp

env TMPDIR=~/temp meteor update
