Microfocus Operations Agent
=========

Requirements
------------
Make sure that the following files exist in the library folder:
- OA_<version>_Windows.zip
- OA_<version>_Linux.zip
  
Run
------------
ansible-playbook -i <nodename> site.yml --tags install
