Usage:

Firs, lets perform check wit: ansible-playbook increase.yaml -i hosts -e nodes=(enter node name) -e vg=(enter vg) -e lv=(enter lv) -e size=(enter size) --check

p.s. dont forget "m" for MB and "g" for GB then:

ansible-playbook increase.yaml -i hosts -e nodes=(enter node name) -e vg=(enter vg) -e lv=(enter lv) -e size=(enter size)

You can specify on which cluster to apply the change as giving extra variable “nodes” as shown above.

Inventory groups:

nodes=dpd

