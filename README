# mongo-sts-with-nfs

1.Create all kubernetes resources
2.Run the following commands to get the exact FQDN
  >)kubectl run -i --tty --image busybox:1.28 dns-test --restart=Never --rm
  >)nslookup <headless-service-name>
3.Access the pod created using the <pod-4.yaml> file, and connect to any stateful pod using the resu  lt returned by the previous command
  >)mongo <pod-hostname>.<headless-service-name>.default.svc.cluster.local

