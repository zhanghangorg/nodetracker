```
cd /root
mv /root/nodetracker/config/config.json /root
pkill node
rm -fr /root/nodetracker
cd /root
git clone https://github.com/zhanghangorg/nodetracker.git
cd nodetracker
mkdir config
mv /root/config.json ./config/
npm install
```
