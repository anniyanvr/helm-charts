# Changelog

This file documents all notable changes to [Gravitee.io Alert Engine](https://github.com/gravitee-io/helm-charts/tree/master/ae) Helm Chart. The release numbering uses [semantic versioning](http://semver.org).

### 2.0.1

- Upgrade AE to v2.3.0

### 2.0.0

- Upgrade AE to v2.2.1
- Upgrade Hazelcast configuration

### 1.1.46

- add networkPolicy

### 1.1.45

- [x] fix: license deleted after helm upgrade

### 1.1.44

- [X] Allow users to define extra manifests
- [X] Upgrade AE version

### 1.1.43

- [X] Allow wildcard in ingress host
- [X] Add podSecurityContext

### 1.1.42

- [X] Allow users to define their own configuration file by defining a volume
- [X] Add `externalTrafficPolicy` in service configuration

### 1.1.41

- [X] Replace ClusterRole with Role

### 1.1.40

- [X] Add optional value to use gravitee licence key

- Update gravitee.io AE v1.6.5

### 1.1.39

- [X] Trunc port name with k8s limit (63)

### 1.1.38

- [X] Fix security context implementation

### 1.1.37

- [X] Add support for autoscaling/v2
- [X] Add support for appProtocol to the services

- Update gravitee.io AE v1.6.4

### 1.1.36

- [X] Add version labels on pods
- [X] Add support for ingressClassName

### 1.1.35

- [X] Add support for managed ServiceAccounts name provided by user
- 
### 1.1.34

- [X] Add support for PodDisruptionBudget

### 1.1.33

- [X] Allow name overriding

### 1.1.32

- [X] Reorder HPA resources to avoid outofsync state with ArgoCD

### 1.1.31 

- [X] Fix Technical API Ingress

### 1.1.30

- [X] Add support for Technical API
- [X] Add support for envFrom

- Update gravitee.io AE v1.6.1

### 1.1.29

- [X] Fix ignoring the managedServiceAccount in the deployment files

### 1.1.28

- [X] Set default array for topologySpreadConstraints

### 1.1.27

- [X] Add support for topologySpreadConstraints

### 1.1.26

- Make app.kubernetes.io/version label consistent
- Add quotes to version to fix #6450
- Update gravitee.io AE v1.6.0

### 1.1.25

- Add support for revisionHistoryLimit
- Update gravitee.io AE v1.5.1

### 1.1.24

- Update processor env var to remove hyphens

### 1.1.23

- [X] startupProbe better management
- Add documentation on production ready environment

### 1.1.22

- [X] Support Ingress kubernetes >= 1.22.x

### 1.1.21

- [X] Configure deployment strategy
- Update gravitee.io AE v1.4.1

### 1.1.20

- [X] Update Hazelcast configuration
- Update gravitee.io AE v1.4.0

### 1.1.19

- [X] Fix Deployment issue

### 1.1.18

- [X] Improve Deployment configurability
- Update gravitee.io AE v1.3.3

### 1.1.17

- [X] Add native support for service account + cluster role creation
- Update gravitee.io AE v1.3.2

### 1.1.16

- [X] Downgrade required kube version to 1.14
