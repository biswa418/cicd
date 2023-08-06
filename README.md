# deploy an application on web

## Step 1
Build the app
Test the app
Get the app prod ready

## Step 2
1. AWS -- cloud (GCP/ Azure)
2. EC2 instance
3. SSH key
4. port open - 80, 443, 3000
5. ssh -i (certificate_name) ubuntu@(ipv4 url)

( the cert should have restrictive permission)
earlier -> -rw-r--r--
chmod 600 ./(cert_name)
now -> -rw------

then run the above command ^

6. clone your repo
7. install node on your cloud machine

