"# -lab-2" 

aws ec2 run-instances --image-id ami-01bc990364452ab3e --count 1 --instance-type t2.micro --key-name nicoleskey09 --security-group-ids sg-09fe5ce78c3ecff75 --subnet-id subnet-0891f1fccaa2b2ed4 --user-data file://run.sh
