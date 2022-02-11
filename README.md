# gitops-rbac-example


Policies:

1. Install-Operator
2. Configure-ArgoCD
3. Setup-Groups and add users

openshift-setup

1. Create users
2. Create groups and map-users
3. Setup Roles

#UsersGroups:  SreAdminGrp, AppX-AdminGrp, AppX-ViewGrp, AppY-AdminGrp, AppY-ViewGrp
#Users: 
#clusteradminuser
#devuser2
#devuser1
#adminuser
#adminuser2

namespaces:
openshift-gitops
dev1 (AppX-AdminGrp, AppX-ViewGrp)
dev2 (AppY-AdminGrp, AppY-ViewGrp)


argo-projects

1. default-project
2. dev1 project
3. dev2 project


application-sets

1. default
2. dev1
3. dev2

acm-gitops

gitopscluster (default, dev1, dev2)
bindings (default, dev1, dev2)


rhacm-rbac

todo







