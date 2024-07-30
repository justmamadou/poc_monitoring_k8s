## On this lab, we'll install odoo usinh helm with a custom value file

#### Install repo

''' helm repo add bitnami https://charts.bitnami.com/bitnam '''

#### Update repo

''' helm repo update '''

#### Deploy

''' helm install odoo bitnami/odoo -f values.yaml '''
