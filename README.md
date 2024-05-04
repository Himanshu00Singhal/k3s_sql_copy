token: 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



supervisorctl reread
supervisorctl update
supervisorctl restart all

cd into /var/log/
tail ds-rating-qa-stderr.log


/usr/local/bin/python3.9


1 */12 * * * cd /home/ubuntu/cars24_ds/profecto/pricing/faraz/scripts/vehicle_health_report && python3 vhr_tp_CRON.py


k3s verbose/debug


ubuntu/mysql:edge

nexcloud backup:  rsync -av --progress /mnt/wd_elements/nextcloud/ryuk/* /mnt/wd_elements/nextcloud/ryuk_backup/

rsync -av --progress /mnt/wd_elements/nextcloud/ryuk_backup/* /mnt/wd_elements/nextcloud/ryuk/

scan in nextcloud pods:
kubectl exec --stdin --tty nextcloud-deployment-69957bccd7-wwsvv  -- /bin/bash
sudo -u www-data php occ files:scan --path "ryuk/files/"    photos"


curl -sfL https://get.k3s.io | K3S_URL=https://192.168.29.161:6443 K3S_TOKEN=K100fddfa244a777f41a7ab32c09088dcccb7d1a7faaea46e0b64dca7fb43acd8db::server:c1db03ec6d95599df960ca10b58b6f7a K3S_NODE_NAME="lenlap" sh -

k9s --kubeconfig /etc/rancher/k3s/k3s.yml


kubectl port-forward pod/mysql-79b9745f94-mp6px 32211:3444

kubectl create configmap mysql-config --from-file=main-config=my-custom.cnf -n default

kubectl create configmap nx-config --from-file=nxmain-config=my.config.php -n default

/mnt/wd_elements/nextcloud/ryuk/files/movies


curl -sfL https://get.k3s.io | sh -s - server \
  --datastore-endpoint="mysql://root:a1s2d3f4g5@tcp(192.168.29.161:3333)/rancher_raspberry"

mysql://root:a1s2d3f4g5@tcp(192.168.29.161:3333)/rancher_raspberry



github token:
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
