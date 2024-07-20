.PHONY: all homelab test

all: test

test:
	ansible-playbook -CD -i inventory.ini playbook.yml

homelab:
	ansible-playbook -i inventory.ini playbook.yml
