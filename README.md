# devops-challenge
this ansible repo will run simple python application using supervisor in vagrant machine
# steps to use it
1- install virtual box in your machine 
sudo apt-get install virtualbox

2- install vagrant in you machine
sudo apt-get install vagrant

3- git clone this repo
git clone 

4- enter into repo and run below command
vagrant up
vagrant provision

this will run all the mentioned roles in playbook.yml

5- just type http://10.10.10.20/ in the url you will get below response.


{
  "headers": {
    "Accept": "text/html,application/xhtml+xml,application/xml;q=0.9,image/webp,image/apng,*/*;q=0.8", 
    "Accept-Encoding": "gzip, deflate", 
    "Accept-Language": "en-GB,en;q=0.9,en-US;q=0.8,hi;q=0.7", 
    "Cache-Control": "max-age=0", 
    "Connection": "close", 
    "Host": "10.10.10.20", 
    "Upgrade-Insecure-Requests": "1", 
    "User-Agent": "Mozilla/5.0 (Macintosh; Intel Mac OS X 10_12_6) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/66.0.3359.117 Safari/537.36", 
    "X-Forwarded-For": "10.10.10.1"
  }, 
  "origin": "10.10.10.1"
}

