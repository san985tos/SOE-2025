# Red Hat Insights and Malware Detection (Yara) Notes


```
sudo yum install -y insights-client yara
sudo insights-client --test-connection
sudo insights-client --register

sudo insights-client --collector malware-detection
sed -i 's/test_scan: true/test_scan: false/g'  /etc/insights-client/malware-detection-config.yml
sudo insights-client --collector malware-detection

curl https://secure.eicar.org/eicar.com -o /root/eicar.com
curl https://secure.eicar.org/eicar.com -o /root/eicar.com.txt
curl https://secure.eicar.org/eicar_com.zip -o /root/eicar_com.zip
curl https://secure.eicar.org/eicarcom2.zip -o /root/eicar_com2.zip

sudo insights-client --collector malware-detection

```
