### Prerequisite :
#### you can install first
    apt-get update -y && apt-get install git -y
### Steps :
    chmod ug+x /path/to/your/script.sh
#### Steps 2 :
    crontab -e
#### steps 3 : 
    */5 * * * * /path/to/your/script.sh
#### run setup command : 
    ./script.sh
#### Note :
Remember to replace /path/to/your/script.sh to your actual script location
