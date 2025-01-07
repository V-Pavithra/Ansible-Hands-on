# Ansible project

# Task 1

Create three EC2 instances on AWS using Ansible loops
- 2 Instances with Ubuntu Distribution
- 1 Instance with Centos Distribution

Hint: Use `connection: local` on Ansible Control node.

# Task 2

Set up passwordless authentication between Ansible control node and newly created 
instances.

# Task 3

Automate the shutdown of only Ubuntu Instances using Ansible Conditionals (i.e when)

Hint: Use `when` condition on ansible `gather_facts`