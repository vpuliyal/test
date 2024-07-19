# test
login into lktul : 

#mkdir -p /home/jenkins/workspace
cd /home/jenkins/workspace

download "buildnotifier_lktul.tar"

#mkdir -p /home/jenkins/userContent
#cd /home/jenkins/userContent

download "distro-ci-lktul.tar"
#tar -xvf distro-ci-lktul.tar
cd /home/jenkins/userContent/distro-ci
#chane machine in distro_support.cfg file as per your requirement. 

# copy PowerVMInstall_New.tar file to /var/lib/jenkins/workspace 
#login to ci-http-results : 

# mkdir /home/jenkins/workspace
#cd /home/jenkins/workspace
#download "buildnotifier_working.tar"
#tar -xvf buildnotifier_working.tar

#cd /home/jenkins
download "userContent_ci-http-results.tar"
#tar -xvf userContent_ci-http-results.tar
#cd /home/jenkins/workspace/buildnotifier

#to start buildnotifier job use below command : 
/usr/bin/python3.9 -u start_build_notification.py
