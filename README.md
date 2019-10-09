# init-scripts
General Linux init scripts model files

# System V
mv systemv-init /etc/init.d

sudo update-rc.d systemv-init defaults

sudo update-rc.d systemv-init enable

# Systemd
mv systemd-unit-name.service /etc/systemd/system

mv systemd-script /somewhere/linked/by/unit/

sudo systemctl enable systemd-unit-name
