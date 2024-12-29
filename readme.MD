


# quick start

Follow the below steps to run the playbook to create a new vm, this requires you to already having a hypervisosr running KVM 


python3 -m venv venv
pip install -r requirements.txt
ansible-playbook start-vm.yml -i inventory -kKb -e 'root_password=your$pecial!password'