# Add custom grafana deployment to existing (in openshift-monitoring project)

It uses oc command, login to the cluster as cluster-admin:

oc login

Run:
ansible-playbook config-grafana.yaml

(default name for deployment is grafana-custom)

or 

ansible-playbook config-grafana.yaml -e grafana_name=my-grafana

name for deployment will be grafana-my-grafana
