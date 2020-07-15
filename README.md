# eks
Deploy the joomla application on top of amazon EKS. In this i created mysql and joomla deployment and for persistent storage, i create dynamic pvc with efs provisioning because by default eks uses EBS as a pvc. Also i created node balancer service so that my traffic can be balanced.
