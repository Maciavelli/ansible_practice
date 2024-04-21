This is the my result of practice with ansible
Goal was
1. To learn basics of ansible: ad hoc commands, how to use playbooks, what is the inventory file, tasks, templates, roles, handlers
2. Set up environment with control node and 2 managed nodes.
3. Gathering facts from managed nodes
4. Installing packages(system packages from linux repositories) like curl, zip, nano, mc, vim and etc
5. Learn and practice with conditionals, default values, handlers.
6. Installing collecd service, gathering OS metrics. 
7. Installing prometheus write plugin, exporting using promQL endpoint metrics

My environment:
MackBook pro m1 chipset, MacOs 13.0.1(Ventura). 
Virtualization: VMWare Fusion with 3 vm(control, and 2 managed nodes) based on Ubuntu. I have create kuatos user on each VM, with sudoers privileges. 


Architecture:


<img width="1466" alt="image" src="https://github.com/Maciavelli/ansible_practice/assets/6698135/298d3fd2-1a43-439e-8a52-5c48b0e46661">


