# Kubetools - A Curated List of Kubernetes Tools

![stars](https://img.shields.io/github/stars/collabnix/kubetools)
![forks](https://img.shields.io/github/forks/collabnix/kubetools)
![issues](https://img.shields.io/github/issues/collabnix/kubetools)
![Visitor count](https://shields-io-visitor-counter.herokuapp.com/badge?page=collabnix.kubetools)
![GitHub contributors](https://img.shields.io/github/contributors/collabnix/kubetools)
![Twitter](https://img.shields.io/twitter/follow/kubetools?style=social)


![Image](https://raw.githubusercontent.com/collabnix/kubetools/master/img/kubetool.jpg) 



There are more than 300+ [Kubernetes Certified Service Providers](https://www.cncf.io/certification/kcsp/) and [tons of Kubernetes Certified distributions](https://kubernetes.io/partners/). Choosing a right distribution can be a daunting task. Kubetools is built with a purpose to build a curated list of popular Kubernetes tools. It is actively maintained by [Collabnix Slack Community](https://collabnix.com).  

Follow the Kubetools [Twitter](https://twitter.com/kubetools) account for updates on new list additions.

Have Questions? Join us over [Slack](https://launchpass.com/collabnix) and get chance to be a part of 7800+ DevOps enthusiasts.<br>

## Table of Contents

- [Categories](#categories)
  - 🧰 [Cluster Management](#cluster-management)
  - 🧑‍💻 [Cluster with Core CLI tools](#cluster-with-core-cli-tools)
  - 🫙 [Alert and Monitoring](#alert-and-monitoring)
  - 🌐 [Logging and Tracing](#logging-and-tracing)
  - 🗄️ [Troubleshooting / Debugging](#troubleshooting--debugging)
  - 💾 [Developement Tools/Kit](#developement-toolskit)
  - 🔒 [Alternative Tools for Developement](#alternative-tools-for-developement)
  - 🪵 [CI/CD integration Tools](#cicd-integration-tools)
  - 🎮 [Security Tools](#security-tools)
  - 🧪 [Network Policies](#network-policies)
  - 🏗️ [Testing Tools](#testing-tools)
  - ⚙️ [Service Mesh](#service-mesh)
  - 🇼 [Observability](#observability)
  - 🧰 [Machine Learning/Deep Learning](#machine-learningdeep-learning)
  - 🧑‍💻 [Compute Edge Tools](#compute-edge-tools)
  - 🫙 [Kubernetes Tools for Specific Cloud](#kubernetes-tools-for-specific-cloud)
  - 🌐 [Storage Providers](#storage-providers)
  - 🗄️ [Multiple Tools Repo](#multiple-tools-repo)
  - 💾 [Cost Optimisation](#cost-optimisation)
  - 🔒 [Non-Categorize](#non-categorize)

## Cluster Management						
									
|	Sr No	|	Tool Name	|		Description with URL	|	GitHub Popularity	|
| ---------- | --------------------- | --------------------- | ------------------ |
|	1	|	Monokle  	|	[	Desktop unified visual tool for authoring, analysis and deployment of Kubernetes configurations](https://github.com/kubeshop/monokle)	|	![Github Stars](https://img.shields.io/github/stars/kubeshop/monokle)	|
|	2	|	kops  	|	[	Production Grade K8s Installation, Upgrades, and Management](https://github.com/kubernetes/kops)	|	![Github Stars](https://img.shields.io/github/stars/kubernetes/kops)	|
|	3	|	silver-surfer  	|	[	Check ApiVersion compatibility and provide Migration path for Kubernetes objects when upgrading Kubernetes to latest versions](https://github.com/devtron-labs/silver-surfer)	|	![Github Stars](https://img.shields.io/github/stars/devtron-labs/silver-surfer)	|
|	4	|	Kube-ops-view  	|	[	Kubernetes Operational View - read-only system dashboard for multiple K8s clusters](https://github.com/hjacobs/kube-ops-view)	|	![Github Stars](https://img.shields.io/github/stars/hjacobs/kube-ops-view)	|
|	5	|	kubeprompt  	|	[	Kubernetes prompt info](https://github.com/jlesquembre/kubeprompt)	|	![Github Stars](https://img.shields.io/github/stars/jlesquembre/kubeprompt)	|
|	6	|	Metalk8s  	|	[	An opinionated Kubernetes distribution with a focus on long-term on-prem deployments](https://github.com/scality/metalk8s)	|	![Github Stars](https://img.shields.io/github/stars/scality/metalk8s)	|
|	7	|	kind  	|	[	Kubernetes IN Docker - local clusters for testing Kubernetes](https://github.com/kubernetes-sigs/kind)	|	![Github Stars](https://img.shields.io/github/stars/kubernetes-sigs/kind)	|
|	8	|	Clusterman  	|	[	Cluster Autoscaler for Kubernetes and Mesos](https://github.com/Yelp/clusterman)	|	![Github Stars](https://img.shields.io/github/stars/Yelp/clusterman)	|
|	9	|	Cert-manager  	|	[	Automatically provision and manage TLS certificates](https://github.com/jetstack/cert-manager)	|	![Github Stars](https://img.shields.io/github/stars/jetstack/cert-manager)	|
|	10	|	Goldilocks  	|	[	Get your resource requests "Just Right"](https://github.com/FairwindsOps/goldilocks)	|	![Github Stars](https://img.shields.io/github/stars/FairwindsOps/goldilocks)	|
|	11	|	katafygio  	|	[	Dump, or continuously backup Kubernetes objets as yaml files in git](https://github.com/bpineau/katafygio)	|	![Github Stars](https://img.shields.io/github/stars/bpineau/katafygio)	|
|	12	|	Rancher  	|	[	Complete container management platform](https://github.com/rancher/rancher)	|	![Github Stars](https://img.shields.io/github/stars/rancher/rancher)	|
|	13	|	Sealed Secrets  	|	[	A Kubernetes controller and tool for one-way encrypted Secrets](https://github.com/bitnami-labs/sealed-secrets)	|	![Github Stars](https://img.shields.io/github/stars/bitnami-labs/sealed-secrets)	|
|	14	|	OpenKruise/Kruise  	|	[	Automate application workloads management on Kubernetes https://openkruise.io](https://github.com/openkruise/kruise)	|	![Github Stars](https://img.shields.io/github/stars/openkruise/kruise)	|
|	15	|	kubectl snapshot  	|	[	Take Cluster Snapshots](https://github.com/fbrubbo/kubectl-snapshot)	|	![Github Stars](https://img.shields.io/github/stars/fbrubbo/kubectl-snapshot)	|
|	16	|	kapp  	|	[	simple deployment tool focused on the concept of "Kubernetes application" — a set of resources with the same label https://get-kapp.io](https://github.com/k14s/kapp)	|	![Github Stars](https://img.shields.io/github/stars/k14s/kapp)	|
|	17	|	keda  	|	[	Event-driven autoscaler for Kubernetes](https://keda.sh/)	|	-	|
|	18	|	Octant  	|	[	To better understand the complexity of Kubernetes clusters](https://github.com/vmware-tanzu/octant)	|	![Github Stars](https://img.shields.io/github/stars/vmware-tanzu/octant)	|
|	19	|	Portainer  	|	[	Portainer inside a Kubernetes environment](https://github.com/portainer/k8s)	|	![Github Stars](https://img.shields.io/github/stars/portainer/k8s)	|
|	20	|	Gardener  	|	[	Deliver fully-managed clusters at scale everywhere with your own Kubernetes-as-a-Service](https://gardener.cloud/)	|	-	|
|	21	|	xlskubectl  	|	[	xlskubectl — a spreadsheet to control your Kubernetes cluster](https://github.com/learnk8s/xlskubectl)	|	![Github Stars](https://img.shields.io/github/stars/learnk8s/xlskubectl)	|
|	22	|	Kubefirst  	|	[	Fully-automated OSS delivery & infrastructure management gitops platforms](https://github.com/kubefirst/kubefirst)	|	![Github Stars](https://img.shields.io/github/stars/kubefirst/kubefirst)	|
|	23	|	Kamaji  	|	[	Build and operate Kubernetes at scale with a fraction of operational burden](https://github.com/clastix/kamaji)	|	![Github Stars](https://img.shields.io/github/stars/clastix/kamaji)	|
|	24	|	kustomizer  	|	[	An experimental package manager for distributing Kubernetes configuration as OCI artifacts](https://github.com/stefanprodan/kustomizer)	|	![Github Stars](https://img.shields.io/github/stars/stefanprodan/kustomizer)	|
									
## Cluster with Core CLI tools						
									
|	Sr No	|	Tool Name	|		Description with URL	|	GitHub Popularity	|
| ---------- | --------------------- | --------------------- | ------------------|									
|	1	|	Bootkube  	|	[	bootkube - Launch a self-hosted Kubernetes cluster](https://github.com/kubernetes-sigs/bootkube)	|	![Github Stars](https://img.shields.io/github/stars/kubernetes-sigs/bootkube)	|
|	2	|	kubectx + kubens  	|	[	Switch faster between clusters and namespaces in kubectl](https://github.com/ahmetb/kubectx)	|	![Github Stars](https://img.shields.io/github/stars/ahmetb/kubectx)	|
|	3	|	kube-ps1  	|	[	Kubernetes prompt info for Bash and Zsh ](https://github.com/jonmosco/kube-ps1)	|	![Github Stars](https://img.shields.io/github/stars/jonmosco/kube-ps1)	|
|	4	|	kube-shell  	|	[	Kubernetes shell: An integrated shell for working with the Kubernetes](https://github.com/cloudnativelabs/kube-shell)	|	![Github Stars](https://img.shields.io/github/stars/cloudnativelabs/kube-shell)	|
|	5	|	kuttle: kubectl wrapper for sshuttle without SSH  	|	[	Kubernetes wrapper for sshuttle](https://github.com/kayrus/kuttle)	|	![Github Stars](https://img.shields.io/github/stars/kayrus/kuttle)	|
|	6	|	kubectl sudo  	|	[	Run kubernetes commands with the security privileges of another user](https://github.com/postfinance/kubectl-sudo)	|	![Github Stars](https://img.shields.io/github/stars/postfinance/kubectl-sudo)	|
|	7	|	K9s  	|	[	Kubernetes CLI To Manage Your Clusters In Style!](https://github.com/derailed/k9s)	|	![Github Stars](https://img.shields.io/github/stars/derailed/k9s)	|
|	8	|	Ktunnel  	|	[	A cli that exposes your local resources to kubernetes](https://github.com/omrikiei/ktunnel)	|	![Github Stars](https://img.shields.io/github/stars/omrikiei/ktunnel)	|
|	9	|	KubeOperator  	|	[	Run kubectl command in Web Browser. https://kubeoperator.io/](https://github.com/KubeOperator/webkubectl)	|	![Github Stars](https://img.shields.io/github/stars/KubeOperator/webkubectl)	|
|	10	|	Vimkubectl  	|	[	Manage any Kubernetes resource from Vim https://www.vim.org/scripts/script.ph](https://github.com/rottencandy/vimkubectl)	|	![Github Stars](https://img.shields.io/github/stars/rottencandy/vimkubectl)	|
|	11	|	KubeHelper  	|	[	KubeHelper - simplifies many daily Kubernetes cluster tasks through a web interface.](https://github.com/KubeHelper/kubehelper)	|	![Github Stars](https://img.shields.io/github/stars/KubeHelper/kubehelper)	|
|	12	|	kubecolor  	|	[	colorizes kubectl output](https://github.com/hidetatz/kubecolor)	|	![Github Stars](https://img.shields.io/github/stars/hidetatz/kubecolor)	|
|	13	|	Krew  	|	[	Krew is the package manager for kubectl plugins](https://github.com/kubernetes-sigs/krew)	|	![Github Stars](https://img.shields.io/github/stars/kubernetes-sigs/krew)	|
|	14	|	Kueue  	|	[	Kueue is a set of APIs and controller for job queueing](https://github.com/kubernetes-sigs/kueue)	|	![Github Stars](https://img.shields.io/github/stars/kubernetes-sigs/kueue)	|
|	15	|	fubectl  	|	[	Reduces repetitive interactions with kubectl](https://github.com/kubermatic/fubectl)	|	![Github Stars](https://img.shields.io/github/stars/kubermatic/fubectl)	|
|	16	|	kube-ps1  	|	[	Kubernetes prompt for bash and zsh](https://github.com/jonmosco/kube-ps1)	|	![Github Stars](https://img.shields.io/github/stars/jonmosco/kube-ps1)	|
									
									
## Alert and Monitoring						
									
|	Sr No	|	Tool Name	|		Description with URL	|	GitHub Popularity	|
| ---------- | --------------------- | --------------------- | ------------------|									
|	1	|	Thanos  	|	[	Highly available Prometheus setup with long term storage capabilities. CNCF Sandbox project. https://thanos.io](https://github.com/thanos-io/thanos)	|	![Github Stars](https://img.shields.io/github/stars/thanos-io/thanos)	|
|	2	|	Prometheus  	|	[	The Prometheus monitoring system and time series database.](https://github.com/prometheus/prometheus)	|	![Github Stars](https://img.shields.io/github/stars/prometheus/prometheus)	|
|	3	|	Grafana  	|	[	The tool for beautiful monitoring and metric analytics & dashboards for Graphite, InfluxDB & Prometheus & More](https://github.com/grafana/grafana)	|	![Github Stars](https://img.shields.io/github/stars/grafana/grafana)	|
|	4	|	Kubetail  	|	[	Bash script to tail Kubernetes logs from multiple pods at the same time](https://github.com/johanhaleby/kubetail)	|	![Github Stars](https://img.shields.io/github/stars/johanhaleby/kubetail)	|
|	5	|	Searchlight  	|	[	Alerts for Kubernetes](https://github.com/searchlight/searchlight)	|	![Github Stars](https://img.shields.io/github/stars/searchlight/searchlight)	|
|	6	|	linkerd2 Monitoring Mixin for Grafana  	|	[	Grafana dashboards for linkerd2 monitoring and can work in standalone (default) or in multi cluster setup](https://github.com/andrew-waters/linkerd2-mixin)	|	![Github Stars](https://img.shields.io/github/stars/andrew-waters/linkerd2-mixin)	|
|	7	|	kuberhaus  	|	[	Kubernetes resource dashboard with node/pod layout and resource requests](https://github.com/stevelacy/kuberhaus)	|	![Github Stars](https://img.shields.io/github/stars/stevelacy/kuberhaus)	|
|	8	|	Kubernetes Job/CronJob Notifier  	|	[	This tool sends an alert to slack whenever there is a Kubernetes cronJob/Job failure/success](https://github.com/sukeesh/k8s-job-notify)	|	![Github Stars](https://img.shields.io/github/stars/sukeesh/k8s-job-notify)	|
|	9	|	Argus  	|	[	This tool monitors changes in the filesystem on specified paths](https://clustergarage.io/argus/docs/overview)	|	-	|
|	10	|	Kube-Scout  	|	[	Scout for alarming issues across your Kubernetes clusters](https://github.com/ReallyLiri/kubescout)	|	![Github Stars](https://img.shields.io/github/stars/ReallyLiri/kubescout)	|
									
									
## Logging and Tracing						
									
|	Sr No	|	Tool Name	|		Description with URL	|	GitHub Popularity	|
| ---------- | --------------------- | --------------------- | ------------------|									
|	1	|	Jaeger  	|	[	CNCF Jaeger, a Distributed Tracing Platform](https://github.com/jaegertracing/jaeger)	|	![Github Stars](https://img.shields.io/github/stars/jaegertracing/jaeger)	|
|	2	|	Kiali  	|	[	Kiali project, observability for the Istio service mesh](https://github.com/kiali/kiali)	|	![Github Stars](https://img.shields.io/github/stars/kiali/kiali)	|
|	3	|	ELK  	|	[	Elasticsearch, Logstash, Kibana](https://github.com/elastic)	|	![Github Stars](https://img.shields.io/github/stars/elastic)	|
|	4	|	fluentbit  	|	[	Fast and Lightweight Log processor and forwarder for Linux, BSD and OSX](https://github.com/fluent/fluent-bit)	|	![Github Stars](https://img.shields.io/github/stars/fluent/fluent-bit)	|
|	5	|	Loki  	|	[	Like Prometheus, but for logs](https://github.com/grafana/loki)	|	![Github Stars](https://img.shields.io/github/stars/grafana/loki)	|
|	6	|kubectl-mtail  |	[ tail logs from multiple pods matching label selector](https://gitlab.com/grzesuav/kubectl-mtail) | ![Github Stars](https://img.shields.io/github/stars/grzesuav/kubectl-mtail)	
									
									
## Troubleshooting / Debugging						
									
|	Sr No	|	Tool Name	|		Description with URL	|	GitHub Popularity	|
| ---------- | --------------------- | --------------------- | ------------------|									
|	1	|	Monokle  	|	[	Desktop unified visual tool for authoring, analysis and deployment of Kubernetes configurations](https://github.com/kubeshop/monokle)	|	![Github Stars](https://img.shields.io/github/stars/kubeshop/monokle)	|
|	2	|	Kubectl-debug  	|	[	Allows you to run a new container with all the troubleshooting tools installed in running pod for debugging purposed](https://github.com/aylei/kubectl-debug)	|	![Github Stars](https://img.shields.io/github/stars/aylei/kubectl-debug)	|
|	3	|	PowerfulSeal  	|	[	A powerful testing tool for Kubernetes clustersd](https://github.com/bloomberg/powerfulseal)	|	![Github Stars](https://img.shields.io/github/stars/bloomberg/powerfulseal)	|
|	4	|	Crash-diagnostic  	|	[	Crash-Diagnostics is a tool to help investigate, analyze, and troubleshoot unresponsive or crashed Kubernetes clustersd](https://github.com/vmware-tanzu/crash-diagnostics)	|	![Github Stars](https://img.shields.io/github/stars/vmware-tanzu/crash-diagnostics)	|
|	5	|	K9s  	|	[	Kubernetes CLI To Manage Your Clusters In Style!d](https://github.com/derailed/k9s)	|	![Github Stars](https://img.shields.io/github/stars/derailed/k9s)	|
|	6	|	Kubernetes CLI Plugin - Doctor 	|	[	kubectl cluster triage plugin for k8s - 🏥 (brew doctor equivalent)d](https://github.com/emirozer/kubectl-doctor)	|	![Github Stars](https://img.shields.io/github/stars/emirozer/kubectl-doctor)	|
|	7	|	Knative Inspect  	|	[	A light-weight debugging tool for Knative's system componentsd](https://github.com/nimakaviani/knative-inspect)	|	![Github Stars](https://img.shields.io/github/stars/nimakaviani/knative-inspect)	|
|	8	|	Kubeman  	|	[	To find information from Kubernetes clusters, and to investigate issues related to Kubernetes and Istiod](https://github.com/walmartlabs/kubeman)	|	![Github Stars](https://img.shields.io/github/stars/walmartlabs/kubeman)	|
|	9	|	kpexec  	|	[	kpexec is a kubernetes cli that runs commands in a container with high privilegesd](https://github.com/ssup2/kpexec)	|	![Github Stars](https://img.shields.io/github/stars/ssup2/kpexec)	|
|	10	|	Koolkits  	|	[	🧰 Opinionated, language-specific, batteries-included debug container images for Kubernetes](https://github.com/lightrun-platform/koolkits)	|	![Github Stars](https://img.shields.io/github/stars/lightrun-platform/koolkits)	|
|	11	|	kubespy  	|	[	pod debugging tool for kubernetes clusters with docker runtimes](https://github.com/huazhihao/kubespy)	|	![Github Stars](https://img.shields.io/github/stars/huazhihao/kubespy)	|
									
## Developement Tools/Kit						
									
|	Sr No	|	Tool Name	|		Description with URL	|	GitHub Popularity	|
| ---------- | --------------------- | --------------------- | ------------------|									
|	1	|	Okteto: A Tool for Cloud Native Developers  	|	[	Build better applications by developing and testing your code directly in Kubernetes](https://github.com/okteto/okteto)	|	![Github Stars](https://img.shields.io/github/stars/okteto/okteto)	|
|	2	|	Tilt: Tilt manages local development instances for teams that deploy to Kubernetes  	|	[	Local Kubernetes development with no stress](https://github.com/windmilleng/tilt)	|	![Github Stars](https://img.shields.io/github/stars/windmilleng/tilt)	|
|	3	|	Garden: Kubernetes from source to finish  	|	[	Development orchestrator for Kubernetes, containers and functions.](https://github.com/garden-io/garden)	|	![Github Stars](https://img.shields.io/github/stars/garden-io/garden)	|
|	4	|	KuberNix  	|	[	Single dependency Kubernetes clusters for local testing, experimenting and development](https://github.com/saschagrunert/kubernix)	|	![Github Stars](https://img.shields.io/github/stars/saschagrunert/kubernix)	|
|	5	|	Copper  	|	[	A configuration file validator for Kubernetes](https://github.com/cloud66-oss/copper)	|	![Github Stars](https://img.shields.io/github/stars/cloud66-oss/copper)	|
|	6	|	ko  	|	[	Build and deploy Go applications on Kubernetes](https://github.com/google/ko)	|	![Github Stars](https://img.shields.io/github/stars/google/ko)	|
|	7	|	Dekorate  	|	[	Java annotation processors for Kubernetes](https://github.com/dekorateio/dekorate)	|	![Github Stars](https://img.shields.io/github/stars/dekorateio/dekorate)	|
|	8	|	Lens IDE  	|	[	A powerful interface and toolkit for managing, visualizing, and interacting with multiple Kubernetes clusters](https://k8slens.dev/)	|	-	|
|	9	|	Kosko  	|	[	Organize Kubernetes manifests in JavaScript](https://kosko.dev/)	|	-	|
|	10	|	Telepresence  	|	[	Fast, local development for Kubernetes and Openshift microservices](https://www.telepresence.io/)	|	-	|
|	11	|	Monokle  	|	[	Desktop unified visual tool for authoring, analysis and deployment of Kubernetes configurations](https://github.com/kubeshop/monokle)	|	![Github Stars](https://img.shields.io/github/stars/kubeshop/monokle)	|
|	12	|	KuberEz  	|	[	Graphical modeling tool for Kubernetes manifest](https://github.com/uengine-oss/kuber-ez)	|	![Github Stars](https://img.shields.io/github/stars/uengine-oss/kuber-ez)	|
|	13	|	mirrord  	|	[	Run your local process in the context of your cloud cluster](https://github.com/metalbear-co/mirrord)	|	![Github Stars](https://img.shields.io/github/stars/metalbear-co/mirrord)	|
|	14	|	Aptakube  	|	[	A modern, lightweight and multi-cluster desktop client for Kubernetes](https://aptakube.com)	|	-	|
|	15	|	Kubes  	|	[	Kubernetes App Deploy Tool: build docker image, compile Kubernetes YAML files, and apply them](https://github.com/boltops-tools/kubes)	|	![Github Stars](https://img.shields.io/github/stars/boltops-tools/kubes)	|
									
## Alternative Tools for Developement						
									
|	Sr No	|	Tool Name	|		Description with URL	|	GitHub Popularity	|
| ---------- | --------------------- | --------------------- | ------------------|									
|	1	|	Minikube  	|	[	minikube implements a local Kubernetes clusterd](https://github.com/kubernetes/minikube)	|	![Github Stars](https://img.shields.io/github/stars/kubernetes/minikube)	|
|	2	|	KubeSphere  	|	[	Easy-to-use Production Ready Container Platform https://kubesphere.io](https://github.com/kubesphere/kubesphere)	|	![Github Stars](https://img.shields.io/github/stars/kubesphere/kubesphere)	|
|	3	|	skippbox  	|	[	A Desktop application for k8sd](https://github.com/skippbox/skippbox)	|	![Github Stars](https://img.shields.io/github/stars/skippbox/skippbox)	|
|	4	|	kind  	|	[	Kubernetes IN Docker - local clusters for testing Kubernetes https://kind.sigs.k8s.io/d](https://github.com/kubernetes-sigs/kind)	|	![Github Stars](https://img.shields.io/github/stars/kubernetes-sigs/kind)	|
|	5	|	k3d  	|	[	k3d is a lightweight wrapper to run k3s (Rancher Lab’s minimal Kubernetes distribution) in docker.d](https://k3d.io/)	|	-	
|	6	|	Systemk: virtual kubelet for systemd  	|	[	Systemk is a systemd backend for the virtual-kubelet. Instead of starting containers, you start systemd units](https://github.com/virtual-kubelet/systemk)	|	![Github Stars](https://img.shields.io/github/stars/virtual-kubelet/systemk)	|
									
									
## CI/CD integration Tools						
									
|	Sr No	|	Tool Name	|		Description with URL	|	GitHub Popularity	|
| ---------- | --------------------- | --------------------- | ------------------|									
|	1	|	HybridK8s Droid  	|	[	Intelligence foor your favourite Delivery Platform](https://hybridk8s.tech/)	|	-	|
|	2	|	Devtron  	|	[	Software Delivery Workflow for Kubernetes](https://github.com/devtron-labs/devtron)	|	![Github Stars](https://img.shields.io/github/stars/devtron-labs/devtron)	|
|	3	|	Skaffold  	|	[	Easy and Repeatable Kubernetes Development](https://github.com/GoogleContainerTools/skaffold)	|	![Github Stars](https://img.shields.io/github/stars/GoogleContainerTools/skaffold)	|
|	4	|	Apollo  	|	[	Apollo - The logz.io continuous deployment solution over kubernetes](https://github.com/logzio/apollo)	|	![Github Stars](https://img.shields.io/github/stars/logzio/apollo)	|
|	5	|	Helm Cabin  	|	[	Web UI that visualizes Helm releases in a Kubernetes cluster](https://github.com/Nick-Triller/helm-cabin)	|	![Github Stars](https://img.shields.io/github/stars/Nick-Triller/helm-cabin)	|
|	6	|	flagger  	|	[	Progressive delivery Kubernetes operator (Canary, A/B Testing and Blue/Green deployments)](https://github.com/weaveworks/flagger)	|	![Github Stars](https://img.shields.io/github/stars/weaveworks/flagger)	|
|	7	|	Kubeform  	|	[	Kubernetes CRDs for Terraform providers https://kubeform.com](https://github.com/kubeform/kubeform)	|	![Github Stars](https://img.shields.io/github/stars/kubeform/kubeform)	|
|	8	|	Spinnaker  	|	[	Spinnaker is an open source, multi-cloud continuous delivery platform for releasing software changes with high velocity and confidence. http://www.spinnaker.io/](https://github.com/spinnaker/spinnaker)	|	![Github Stars](https://img.shields.io/github/stars/spinnaker/spinnaker)	|
|	9	|	werf  	|	[	GitOps tool to deliver apps to Kubernetes and integrate this process with GitLab and other CI tools](https://github.com/werf/werf)	|	![Github Stars](https://img.shields.io/github/stars/werf/werf)	|
|	10	|	Flux  	|	[	GitOps Kubernetes operator](https://github.com/fluxcd/flux)	|	![Github Stars](https://img.shields.io/github/stars/fluxcd/flux)	|
|	11	|	Argo CD  	|	[	Declarative continuous deployment for Kubernetes](https://github.com/argoproj/argo-cd)	|	![Github Stars](https://img.shields.io/github/stars/argoproj/argo-cd)	|
|	12	|	Tekton  	|	[	A cloud native continuous integration and delivery (CI/CD) solution](https://github.com/tektoncd/pipeline)	|	![Github Stars](https://img.shields.io/github/stars/tektoncd/pipeline)	|
|	13	|	Jenkins X  	|	[	Jenkins X provides automated CI+CD for Kubernetes with Preview Environments on Pull Requests using Tekton, Knative, Lighthouse, Skaffold and Helm](https://github.com/jenkins-x/jx)	|	![Github Stars](https://img.shields.io/github/stars/jenkins-x/jx)	|
|	14	|	Drone  	|	[	Drone is a Container-Native, Continuous Delivery Platform](https://github.com/harness/drone)	|	![Github Stars](https://img.shields.io/github/stars/harness/drone)	|
|	15	|	Helmwave  	|	[	Helmwave is helm3-native tool for deploy your Helm Charts](https://github.com/helmwave/helmwave)	|	![Github Stars](https://img.shields.io/github/stars/helmwave/helmwave)	|
									
## Security Tools						
									
|	Sr No	|	Tool Name	|		Description with URL	|	GitHub Popularity	|
| ---------- | --------------------- | --------------------- | ------------------|									
|	1	|	Kubevious CLI  	|	[	Prevent cross-manifest errors and violations of best practicees in YAML files, Helm Charts and Kubernetes clusters](https://github.com/kubevious/cli)	|	![Github Stars](https://img.shields.io/github/stars/kubevious/cli)	|
|	2	|	TerraScan  	|	[	Detect compliance and security violations across Infrastructure as Code to mitigate risk before provisioning cloud native infrastructure.](https://github.com/accurics/terrascan)	|	![Github Stars](https://img.shields.io/github/stars/accurics/terrascan)	|
|	3	|	klum  	|	[	Kubernetes Lazy User Manager](https://github.com/ibuildthecloud/klum)	|	![Github Stars](https://img.shields.io/github/stars/ibuildthecloud/klum)	|
|	4	|	kube2iam  	|	[	IAM credentials to containers running inside a kubernetes cluster based on annotations.](https://github.com/jtblin/kube2iam)	|	![Github Stars](https://img.shields.io/github/stars/jtblin/kube2iam)	|
|	5	|	Kyverno  	|	[	Kubernetes Native Policy Management https://kyverno.io](https://github.com/nirmata/kyverno)	|	![Github Stars](https://img.shields.io/github/stars/nirmata/kyverno)	|
|	6	|	kiosk  	|	[	kiosk office Multi-Tenancy Extension For Kubernetes - Secure Cluster Sharing & Self-Service Namespace Provisioning](https://github.com/kiosk-sh/kiosk)	|	![Github Stars](https://img.shields.io/github/stars/kiosk-sh/kiosk)	|
|	7	|	kube-bench  	|	[	CIS Kubernetes Benchmark tool](https://github.com/aquasecurity/kube-bench)	|	![Github Stars](https://img.shields.io/github/stars/aquasecurity/kube-bench)	|
|	8	|	kube-hunter  	|	[	Pentesting tool - Hunts for security weaknesses in Kubernetes clusters](https://github.com/aquasecurity/kube-hunter)	|	![Github Stars](https://img.shields.io/github/stars/aquasecurity/kube-hunter)	|
|	9	|	kube-who-can  	|	[	Show who has RBAC permissions to perform actions on different resources in Kubernetes](https://github.com/aquasecurity/kubectl-who-can)	|	![Github Stars](https://img.shields.io/github/stars/aquasecurity/kubectl-who-can)	|
|	10	|	starboard  	|	[	Kubernetes-native security toolkit](https://github.com/aquasecurity/starboard)	|	![Github Stars](https://img.shields.io/github/stars/aquasecurity/starboard)	|
|	11	|	Simulator  	|	[	Kubernetes Security Training Platform - Focussing on security mitigation](https://github.com/kubernetes-simulator/simulator)	|	![Github Stars](https://img.shields.io/github/stars/kubernetes-simulator/simulator)	|
|	12	|	RBAC Lookup  	|	[	Easily find roles and cluster roles attached to any user, service account, or group name in your Kubernetes cluster https://fairwinds.com](https://github.com/FairwindsOps/rbac-lookup)	|	![Github Stars](https://img.shields.io/github/stars/FairwindsOps/rbac-lookup)	|
|	13	|	Kubeaudit  	|	[	kubeaudit helps you audit your Kubernetes clusters against common security controls](https://github.com/Shopify/kubeaudit)	|	![Github Stars](https://img.shields.io/github/stars/Shopify/kubeaudit)	|
|	14	|	Gangway  	|	[	An application that can be used to easily enable authentication flows via OIDC for a kubernetes cluster](https://github.com/heptiolabs/gangway)	|	![Github Stars](https://img.shields.io/github/stars/heptiolabs/gangway)	|
|	15	|	Audit2rbac  	|	[	Autogenerate RBAC policies based on Kubernetes audit logs](https://github.com/liggitt/audit2rbac)	|	![Github Stars](https://img.shields.io/github/stars/liggitt/audit2rbac)	|
|	16	|	Chartsec  	|	[	Helm Chart security scanner](https://github.com/banzaicloud/chartsec)	|	![Github Stars](https://img.shields.io/github/stars/banzaicloud/chartsec)	|
|	17	|	kubestriker  	|	[	Security Auditing tool](https://github.com/vchinnipilli/kubestriker)	|	![Github Stars](https://img.shields.io/github/stars/vchinnipilli/kubestriker)	|
|	18	|	Datree  	|	[	CLI tool to prevent K8s misconfigurations by ensuring that manifests and Helm charts follow best practices as well as your organization’s policies](https://datree.io/)	|	-	|
|	19	|	Krane  	|	[	Kubernetes RBAC static Analysis & visualisation tool](https://github.com/appvia/krane)	|	![Github Stars](https://img.shields.io/github/stars/appvia/krane)	|
|	20	|	Falco  	|	[	The Falco Project - Cloud-Native runtime security](https://falco.org/)	|	-	|
|	21	|	Clair  	|	[	Vulnerability Static Analysis for Containers](https://github.com/quay/clair)	|	![Github Stars](https://img.shields.io/github/stars/quay/clair)	|
|	22	|	M9sweeper  	|	[	Complete Kubernetes Security Platform](https://github.com/m9sweeper/m9sweeper)	|	![Github Stars](https://img.shields.io/github/stars/m9sweeper/m9sweeper)	|
									
									
## Network Policies						
									
|	Sr No	|	Tool Name	|		Description with URL	|	GitHub Popularity	|
| ---------- | --------------------- | --------------------- | ------------------|									
|	1	|	trireme-kubernetes  	|	[	Aporeto integration with Kubernetes Network Policies](https://github.com/aporeto-inc/trireme-kubernetes)	|	![Github Stars](https://img.shields.io/github/stars/aporeto-inc/trireme-kubernetes)	|
|	2	|	Calico  	|	[	Cloud native connectivity and network policy](https://github.com/projectcalico/calico)	|	![Github Stars](https://img.shields.io/github/stars/projectcalico/calico)	|
|	3	|	kubepox  	|	[	Kubernetes network Policy eXploration tool](https://github.com/aporeto-inc/kubepox)	|	![Github Stars](https://img.shields.io/github/stars/aporeto-inc/kubepox)	|
|	4	|	kokotap  	|	[	Tools for kubernetes pod network tapping](https://github.com/redhat-nfvpe/kokotap)	|	![Github Stars](https://img.shields.io/github/stars/redhat-nfvpe/kokotap)	|
|	5	|	Submariner  	|	[	Connect all your Kubernetes clusters, no matter where they are in the world](https://github.com/submariner-io/submariner)	|	![Github Stars](https://img.shields.io/github/stars/submariner-io/submariner)	|
|	6	|	egress-operator  	|	[	An operator to produce egress gateway pods and control access to them with network policies](https://github.com/monzo/egress-operator)	|	![Github Stars](https://img.shields.io/github/stars/monzo/egress-operator)	|
|	7	|	kubefwd (Kube Forward)  	|	[	Bulk port forwarding Kubernetes services for local development](https://github.com/txn2/kubefwd)	|	![Github Stars](https://img.shields.io/github/stars/txn2/kubefwd)	|
									
									
## Testing Tools						
									
|	Sr No	|	Tool Name	|		Description with URL	|	GitHub Popularity	|
| ---------- | --------------------- | --------------------- | ------------------|									
|	1	|	Testkube  	|	[	Kubernetes-native testing framework for testers and developers](https://github.com/kubeshop/testkube)	|	![Github Stars](https://img.shields.io/github/stars/kubeshop/testkube)	|
|	2	|	k6d  	|	[	A modern load testing tool, using Go and JavaScript](https://github.com/loadimpact/k6)	|	![Github Stars](https://img.shields.io/github/stars/loadimpact/k6)	|
|	3	|	Network bandwith and load testingd - 	|	[	Test suite for Kubernetes](https://github.com/mrahbar/k8s-testsuite)	|	![Github Stars](https://img.shields.io/github/stars/mrahbar/k8s-testsuite)	|
|	4	|	test-infrad  	|	[	Test infrastructure for the Kubernetes project](https://github.com/kubernetes/test-infra)	|	![Github Stars](https://img.shields.io/github/stars/kubernetes/test-infra)	|
|	5	|	kube-scored  	|	[	Kubernetes object analysis with recommendations for improved reliability and security](https://github.com/zegl/kube-score)	|	![Github Stars](https://img.shields.io/github/stars/zegl/kube-score)	|
|	6	|	Litmusd  	|	[	Cloud-Native Chaos Engineering; Kubernetes-Native Chaos Engineering; Chaos Engineering for Kubernetes](https://github.com/litmuschaos/litmus)	|	![Github Stars](https://img.shields.io/github/stars/litmuschaos/litmus)	|
|	7	|	PowerfulSeald  	|	[	A powerful testing tool for Kubernetes clusters](https://github.com/bloomberg/powerfulseal)	|	![Github Stars](https://img.shields.io/github/stars/bloomberg/powerfulseal)	|
|	8	|	kube-burnerd  	|	[	Kube-burner is a tool aimed at stressing kubernetes clusters](https://kube-burner.readthedocs.io/en/latest/)	|	-	|
|	9	|	Tracetest  	|	[	Generate end-to-end and integration tests automatically from your OpenTelemetry traces](https://github.com/kubeshop/tracetest)	|	![Github Stars](https://img.shields.io/github/stars/kubeshop/tracetest)	|
									
## Service Mesh						
									
|	Sr No	|	Tool Name	|		Description with URL	|	GitHub Popularity	|
| ---------- | --------------------- | --------------------- | ------------------|									
|	1	|	Istio  	|	[	Connect, secure, control, and observe services](https://github.com/istio/istio)	|	![Github Stars](https://img.shields.io/github/stars/istio/istio)	|
|	2	|	Traefik  	|	[	The Cloud Native Edge Router](https://github.com/containous/traefik)	|	![Github Stars](https://img.shields.io/github/stars/containous/traefik)	|
|	3	|	NGINX Ingress Controller  	|	[	NGINX and NGINX Plus Ingress Controllers for Kubernetes](https://github.com/nginxinc/kubernetes-ingress)	|	![Github Stars](https://img.shields.io/github/stars/nginxinc/kubernetes-ingress)	|
|	4	|	Autopilot  	|	[	THE SERVICE MESH SDK](https://docs.solo.io/autopilot/latest)	|	-	|
|	5	|	linkerd-config  	|	[	A Kubernetes controller that knows how to reconcile the Linkerd configuration](https://github.com/ihcsim/linkerd-config)	|	![Github Stars](https://img.shields.io/github/stars/ihcsim/linkerd-config)	|
|	6	|	Kong  	|	[	Kong for Kubernetes: the official Ingress Controller for Kubernetes](https://github.com/Kong/kubernetes-ingress-controller)	|	![Github Stars](https://img.shields.io/github/stars/Kong/kubernetes-ingress-controller)	|
|	7	|	OSM 	|	[	Open Service Mesh (OSM) is a lightweight, extensible, cloud native service mesh](https://github.com/openservicemesh/osm)	|	![Github Stars](https://img.shields.io/github/stars/openservicemesh/osm)	|
|	8	|	Layer5  	|	[	Layer5, the service mesh company, representing every service mesh](https://github.com/layer5io/layer5)	|	![Github Stars](https://img.shields.io/github/stars/layer5io/layer5)	|
|	9	|	Gloo Mesh  	|	[	The Service Mesh Orchestration Platform](https://github.com/solo-io/gloo-mesh)	|	![Github Stars](https://img.shields.io/github/stars/solo-io/gloo-mesh)	|
|	10	|	APISIX 	|	[	Apache APISIX is a dynamic, real-time, high-performance API gateway.](https://github.com/apache/apisix)	|	![Github Stars](https://img.shields.io/github/stars/apache/apisix)	|
|	11	|	Contour  	|	[	High performance ingress controller for Kubernetes](https://projectcontour.io/)	|	-	|
|	12	|	Kusk Gateway  	|	[	OpenAPI-driven Ingress Controller for Kubernetes](https://kusk.io/kusk-gateway)	|	-	|
									
									
## Observability						
									
|	Sr No	|	Tool Name	|		Description with URL	|	GitHub Popularity	|
| ---------- | --------------------- | --------------------- | ------------------|									
|	1	|	Kubespy  	|	[	Tools for observing Kubernetes resources in real time](https://github.com/pulumi/kubespy)	|	![Github Stars](https://img.shields.io/github/stars/pulumi/kubespy)	|
|	2	|	Popeye  	|	[	A Kubernetes cluster resource sanitizer](https://github.com/derailed/popeye)	|	![Github Stars](https://img.shields.io/github/stars/derailed/popeye)	|
|	3	|	Stern  	|	[	Multi pod and container log tailing for Kubernetes](https://github.com/wercker/stern)	|	![Github Stars](https://img.shields.io/github/stars/wercker/stern)	|
|	4	|	Cri-tools  	|	[	CLI and validation tools for Kubelet Container Runtime Interface (CRI)](https://github.com/kubernetes-sigs/cri-tools)	|	![Github Stars](https://img.shields.io/github/stars/kubernetes-sigs/cri-tools)	|
|	5	|	Kubebox  	|	[	Terminal and Web console for Kubernetes](https://github.com/astefanutti/kubebox)	|	![Github Stars](https://img.shields.io/github/stars/astefanutti/kubebox)	|
|	6	|	Kubewatch  	|	[	Watch k8s events and trigger Handlers](https://github.com/bitnami-labs/kubewatch)	|	![Github Stars](https://img.shields.io/github/stars/bitnami-labs/kubewatch)	|
|	7	|	kube-state-metrics  	|	[	Add-on agent to generate and expose cluster-level metrics](https://github.com/kubernetes/kube-state-metrics)	|	![Github Stars](https://img.shields.io/github/stars/kubernetes/kube-state-metrics)	|
|	8	|	Sloop  	|	[	Kubernetes History Visualization](https://github.com/salesforce/sloop?utm_sq=g90yo8t8s1)	|	![Github Stars](https://img.shields.io/github/stars/salesforce/sloop?utm_sq=g90yo8t8s1)	|
|	9	|	kubectl tree 🎄  	|	[	Kubectl plugin to observe object hierarchies through ownerReferences](https://github.com/ahmetb/kubectl-tree)	|	![Github Stars](https://img.shields.io/github/stars/ahmetb/kubectl-tree)	|
|	10	|	chaoskube  	|	[	chaoskube periodically kills random pods in your Kubernetes cluster](https://github.com/linki/chaoskube)	|	![Github Stars](https://img.shields.io/github/stars/linki/chaoskube)	|
|	11	|	BotKube  	|	[	Helps you monitor your Kubernetes cluster(s), debug critical deployments and gives recommendations for standard practices](https://www.botkube.io/)	|	-	|
|	12	|	Kubestone  	|	[	Kubestone is a benchmarking Operator that can evaluate the performance of Kubernetes installations](https://kubestone.io/en/latest)	|	-	|
|	13	|	Chaos Mesh  	|	[	A Chaos Engineering Platform for Kubernetes](https://github.com/pingcap/chaos-mesh)	|	![Github Stars](https://img.shields.io/github/stars/pingcap/chaos-mesh)	|
|	14	|	Lemur  	|	[	LEMUR: Observability and Context](https://github.com/turbonomic/lemur)	|	![Github Stars](https://img.shields.io/github/stars/turbonomic/lemur)	|
|	15	|	kubernetes-event-exporter  	|	[	Export Kubernetes events to multiple destinations with routing and filtering](https://github.com/opsgenie/kubernetes-event-exporter)	|	![Github Stars](https://img.shields.io/github/stars/opsgenie/kubernetes-event-exporter)	|
|	16	|	Kubevious  	|	[	Kubevious is an app-centric assurance, validation, and introspection platform for Kubernetes](https://kubevious.io/)	|	-	|
|	17	|	OpenTelemetry  	|	[	High-quality, ubiquitous, and portable telemetry to enable effective observability](https://opentelemetry.io/)	|	-	|
|	18	|	Grafana Tempo  	|	[	Grafana Tempo is a high volume, minimal dependency distributed tracing backend](https://github.com/grafana/tempo)	|	![Github Stars](https://img.shields.io/github/stars/grafana/tempo)	|
|	19	|	Tracetest 	|	[	Generate end-to-end and integration tests automatically from your OpenTelemetry traces](https://github.com/kubeshop/tracetest)	|	![Github Stars](https://img.shields.io/github/stars/kubeshop/tracetest)	|
									
## Machine Learning/Deep Learning						
									
|	Sr No	|	Tool Name	|		Description with URL	|	GitHub Popularity	|
| ---------- | --------------------- | --------------------- | ------------------|									
|	1	|	Nos  	|	[	nos is an open-source platform to efficiently run AI workloads on Kubernetes, increasing GPU utilization and reducing infrastructure and operational costs](https://github.com/nebuly-ai/nos)	|	![Github Stars](https://img.shields.io/github/stars/nebuly-ai/nos)	|
|	2	|	Kubeflow  	|	[	Machine Learning Toolkit for Kubernetes](https://github.com/kubeflow/kubeflow)	|	![Github Stars](https://img.shields.io/github/stars/kubeflow/kubeflow)	|
|	3	|	Volcano  	|	[	A Kubernetes Native Batch System](https://github.com/volcano-sh/volcano)	|	![Github Stars](https://img.shields.io/github/stars/volcano-sh/volcano)	|
									
									
## Compute Edge Tools						
									
|	Sr No	|	Tool Name	|		Description with URL	|	GitHub Popularity	|
| ---------- | --------------------- | --------------------- | ------------------|									
|	1	|	KubeEdge 	|	[	Kubernetes Native Edge Computing Framework](https://github.com/kubeedge/kubeedge)	|	![Github Stars](https://img.shields.io/github/stars/kubeedge/kubeedge)	|
|	2	|	OpenYurt  	|	[	Extending your native Kubernetes to edge](https://github.com/openyurtio/openyurt)	|	![Github Stars](https://img.shields.io/github/stars/openyurtio/openyurt)	|
|	3	|	Akri  	|	[	A Kubernetes Resource Interface for the Edge](https://github.com/project-akri/akri)	|	![Github Stars](https://img.shields.io/github/stars/project-akri/akri)	|
|	4	|	SuperEdge  	|	[	An edge-native container management system for edge computing](https://github.com/superedge/superedge)	|	![Github Stars](https://img.shields.io/github/stars/superedge/superedge)	|
|	5	|	Keylime  	|	[	A CNCF Project to Bootstrap & Maintain Trust on the Edge / Cloud and IoT](https://github.com/keylime/keylime)	|	![Github Stars](https://img.shields.io/github/stars/keylime/keylime)	|
									
									
## Kubernetes Tools for Specific Cloud						
									
|	Sr No	|	Tool Name	|		Description with URL	|	GitHub Popularity	|
| ---------- | --------------------- | --------------------- | ------------------|									
|	1	|	Kubernetes on AWS (kube-aws)  	|	[	A command-line tool to declaratively manage Kubernetes clusters on AWS](https://github.com/kubernetes-incubator/kube-aws)	|	![Github Stars](https://img.shields.io/github/stars/kubernetes-incubator/kube-aws)	|
|	2	|	Draft: Streamlined Kubernetes Development  	|	[	A tool for developers to create cloud-native applications on Kubernetes](https://github.com/azure/draft)	|	![Github Stars](https://img.shields.io/github/stars/azure/draft)	|
|	3	|	helm-ssm  	|	[	A low dependency tool for retrieving and injecting secrets from AWS SSM into Helm](https://github.com/totango/helm-ssm)	|	![Github Stars](https://img.shields.io/github/stars/totango/helm-ssm)	|
|	4	|	Skupper  	|	[	Multicloud communication for Kubernetes](https://skupper.io/)	|	-	|
									
									
## Storage Providers						
									
|	Sr No	|	Tool Name	|		Description with URL	|	GitHub Popularity	|
| ---------- | --------------------- | --------------------- | ------------------|									
|	1	|	ChubaoFS  	|	[	distributed file system and object storage](https://github.com/chubaofs/chubaofs)	|	![Github Stars](https://img.shields.io/github/stars/chubaofs/chubaofs)	|
|	2	|	Longhorn 	|	[	Cloud-Native distributed block storage built on and for Kubernetes](https://github.com/longhorn/longhorn)	|	![Github Stars](https://img.shields.io/github/stars/longhorn/longhorn)	|
|	3	|	OpenEBS  	|	[	Kubernetes native - hyperconverged block storage with multiple storage engines](https://github.com/openebs/openebs)	|	![Github Stars](https://img.shields.io/github/stars/openebs/openebs)	|
|	4	|	Rook  	|	[	Storage Orchestration for Kubernetes](https://github.com/rook/rook)	|	![Github Stars](https://img.shields.io/github/stars/rook/rook)	|
|	5	|	SeaweedFS  	|	[	Distributed file system supports read-write many volumes](https://github.com/chrislusf/seaweedfs)	|	![Github Stars](https://img.shields.io/github/stars/chrislusf/seaweedfs)	|
|	6	|	TiKV  	|	[	Distributed transactional key-value database](https://github.com/tikv/tikv)	|	![Github Stars](https://img.shields.io/github/stars/tikv/tikv)	|
|	7	|	TopoLVM  	|	[	Capacity-aware CSI plugin for Kubernetes](https://github.com/topolvm/topolvm)	|	![Github Stars](https://img.shields.io/github/stars/topolvm/topolvm)	|
|	8	|	velero  	|	[	Backup and migrate Kubernetes applications and their persistent volumes](https://github.com/vmware-tanzu/velero)	|	![Github Stars](https://img.shields.io/github/stars/vmware-tanzu/velero)	|
|	9	|	Vitess  	|	[	Vitess is a database clustering system for horizontal scaling of MySQL](https://github.com/vitessio/vitess)	|	![Github Stars](https://img.shields.io/github/stars/vitessio/vitess)	|
|	10	|	kaDalu  	|	[	A lightweight Persistent storage solution for Kubernetes / OpenShift using GlusterFS in background](https://github.com/kadalu/kadalu)	|	![Github Stars](https://img.shields.io/github/stars/kadalu/kadalu)	|
									
									
## Multiple Tools Repo						
									
|	Sr No	|	Tool Name	|		Description with URL	|	GitHub Popularity	|
| ---------- | --------------------- | --------------------- | ------------------|									
|	1	|	Chaos Toolkit Kubernetes Support  	|	[	Kubernetes driver extension of the Chaos Toolkit probes and actions API](https://github.com/chaostoolkit/chaostoolkit-kubernetes)	|	![Github Stars](https://img.shields.io/github/stars/chaostoolkit/chaostoolkit-kubernetes)	|
|	2	|	k14s  	|	[	Kubernetes Tools that follow Unix philosophy to be simple and composable](https://github.com/k14s)	|	![Github Stars](https://img.shields.io/github/stars/k14s)	|
|	3	|	Pulumi  	|	[	Pulumi - Modern Infrastructure as Code. Any cloud, any language. Give your team cloud superpowers rocket https://www.pulumi.com](https://github.com/pulumi/pulumi)	|	![Github Stars](https://img.shields.io/github/stars/pulumi/pulumi)	|
									
									
## Cost Optimisation						
									
|	Sr No	|	Tool Name	|		Description with URL	|	GitHub Popularity	|
| ---------- | --------------------- | --------------------- | ------------------|									
|	1	|	Kubecost  	|	[	Cross-cloud cost allocation models for workloads running on Kubernetes](https://github.com/kubecost/cost-model)	|	![Github Stars](https://img.shields.io/github/stars/kubecost/cost-model)	|
|	2	|	PerfectScale  	|	[	Reduce Kubernetes costs while improving performance and resilience with data-driven intelligence built for continuous optimization](https://www.perfectscale.io)	|	-	|
|	3	|	OpenCost  	|	[	OpenCost — your favorite open source cost monitoring tool for Kubernetes](https://github.com/opencost/opencost)	|	![Github Stars](https://img.shields.io/github/stars/opencost/opencost)	|
									
									
## Non-Categorize						
									
|	Sr No	|	Tool Name	|		Description with URL	|	GitHub Popularity	|
| ---------- | --------------------- | --------------------- | ------------------|									
|	1	|	Rudr  	|	[	A Kubernetes implementation of the Open Application Model specification](https://github.com/oam-dev/rudr)	|	![Github Stars](https://img.shields.io/github/stars/oam-dev/rudr)	|
|	2	|	Keel 	|	[	Kubernetes Operator to automate Helm, DaemonSet, StatefulSet & Deployment updates](https://keel.sh/)	|	-	|
|	3	|	Cabin, the mobile app for Kubernetes - 	|	[	The Mobile Dashboard for Kubernetes](https://github.com/bitnami-labs/cabin)	|	![Github Stars](https://img.shields.io/github/stars/bitnami-labs/cabin)	|
|	4	|	Funktion 	|	[	CLI tool for working with funktion](https://github.com/funktionio/funktion)	|	![Github Stars](https://img.shields.io/github/stars/funktionio/funktion)	|
|	5	|	Alterant  	|	[	A simple Kubernetes configuration modifier](https://github.com/cloud66-oss/alterant)	|	![Github Stars](https://img.shields.io/github/stars/cloud66-oss/alterant)	|
|	6	|	BUCK  	|	[	Brigade Universal Controller for Kubernetes](https://github.com/brigadecore/buck)	|	![Github Stars](https://img.shields.io/github/stars/brigadecore/buck)	|
|	7	|	kube-fledged  	|	[	A kubernetes add-on for creating and managing a cache of container images directly on the cluster worker nodes, so application pods start almost instantly](https://github.com/senthilrch/kube-fledged)	|	![Github Stars](https://img.shields.io/github/stars/senthilrch/kube-fledged)	|
|	8	|	kpt  	|	[	toolkit to help you manage, manipulate, customize, and apply Kubernetes Resource configuration](https://github.com/GoogleContainerTools/kpt)	|	![Github Stars](https://img.shields.io/github/stars/GoogleContainerTools/kpt)	|
|	9	|	capsule  	|	[	Capsule helps to implement a multi-tenancy and policy-based environment in your Kubernetes cluster](https://github.com/clastix/capsule)	|	![Github Stars](https://img.shields.io/github/stars/clastix/capsule)	|
|	10	|	KubeSlice  	|	[	KubeSlice enables Kubernetes pods and services to communicate seamlessly across clusters, clouds, edges, and data centers by creating logical application boundaries known as Slices](https://github.com/kubeslice)	|	![Github Stars](https://img.shields.io/github/stars/kubeslice)	|
|	11	|	routernetes 	|	[	Use Kubernetes to make a home router!](https://github.com/routernetes/routernetes)	|	![Github Stars](https://img.shields.io/github/stars/routernetes/routernetes)	|
									
## Maintainer

- [Apurva Bhandari](https://www.linkedin.com/in/apurvabhandari-linux/)
- [Ajeet Singh Raina](https://www.linkedin.com/in/ajeetsraina)
