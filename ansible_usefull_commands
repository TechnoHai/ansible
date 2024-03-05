# Gather facts from all hosts
ansible all -m gather_facts

# Gather facts from all hosts and save them to a file
ansible all -m gather_facts --tree /tmp/facts

# Gather facts from all hosts and save them to a file in JSON format
ansible all -m gather_facts --tree /tmp/facts --format json

# Gather facts from a specific host identified by its IP address
ansible all -m gather_facts --limit=10.100.102.47