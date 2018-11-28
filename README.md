dockerbox

For CentOS

## installation  
yum update  
yum install git  
cd /tmp  
git clone https://github.com/OsmOOs/dockerbox.git  
cd dockerbox  
mv dockerbox.sh logo.sh /usr/local/bin  
mv iptables /etc/iptables  
cd /usr/local/bin  
chmod +x dockerbox.sh logo.sh  
dockerbox.sh  
