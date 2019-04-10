### Harbor Testing Scope

#### OS
- [ ] Test on Ubuntu 16.04 (64-bit)
- [ ] Test on Ubuntu 18.04 (64-bit)
- [ ] Test on RancherOS 1.5.1 (64-bit)
- [ ] Test on Red Hat Enterprise Linux (RHEL)/CentOS 7.6 (64-bit)

#### Kubernetes Providers
- [ ] Support Google GKE
- [ ] Support Amazon EKS
- [ ] Support Azure AKS
- [ ] Support RKE
   - [ ] DO nodes
   - [ ] AWS EC2

#### Kuberetnes Version
- [ ] Test on v1.13
- [ ] Test on v1.14

#### Docker
- [ ] Support Docker 17.03.x, 18.06.x, 18.09.x

### Features
- [ ] Users should be able to choose Harbor service type and tls certificate:
  + [ ] secretName (existing certificate).
  + [ ] custom CA (uploading a new one).
  + [ ] Rancher (only in Rancher-HA mode and the app namespace must be `cattle-system`).
  + [ ] self-signed x509 certificate (the default expiration is 3,650 days).
- [ ] Users should be able to enable the persistent storage for the following components:
  + [ ] Registry
  + [ ] ChartMuseum
- [ ] Users should be able to enable and choosing the backend storage:
  + [ ] filesystem (localPath)
  + [ ] s3
  + [ ] oss
  + [ ] gcs
- [ ] Install PostgreSQL database should work
  + [ ] Enable PVC should work
  + [ ] Use external database should work
- [ ] Install Redis should works
  + [ ] Enable PVC should work
  + [ ] Use external Redis should work
 
#### Bugs

#### Enhancement

#### Others
