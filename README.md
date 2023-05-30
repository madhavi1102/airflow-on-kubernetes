# airflow-on-kubernetes
This repo maintains manifest files to perform minimal Airflow deployment including it's components: webserver, scheduler, db-migrations,postgresql database on  multinode (3 VMs) kubernetes cluster environment.

This is very helpful for the start with setting up Airflow on Kubernetes cluster. This stores neccessary files required to make airflow running on the Kubernetes.

Th official Airflow provides Helm chart to perform installation of Airflow on Kubernetes with few lines of instructions, but for the starter, it's also important to understand the inside airflow working, configuration details and dependencies, so that I will be able to tweak these settings and yamls according to a business need.

