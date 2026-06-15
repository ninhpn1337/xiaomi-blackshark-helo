```
wget https://www.tenable.com/downloads/api/v2/pages/nessus/files/Nessus-latest-ubuntu1804_aarch64.deb
chmod +x Nessus-latest-ubuntu1804_aarch64.deb
sudo dpkg -i Nessus-latest-ubuntu1804_aarch64.deb

```
sudo /opt/nessus/sbin/nessus-service -D
