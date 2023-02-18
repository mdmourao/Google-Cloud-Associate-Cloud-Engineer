# Google Cloud Certification

Google Cloud Associate Cloud Engineer certification is focused on the fundamental skills of deploying, monitoring, and maintaining projects on Google Cloud.

Notes from my certification classes on Udemy!  

# Refs Price

https://cloud.google.com/products/calculator  

# Refs Console

1. gcloud CLI - https://cloud.google.com/sdk/docs/cheatsheet

Install local: https://cloud.google.com/sdk/docs/install  

gcloud container clusters list  
gcloud container images list-tags  
gcloud compute instances describe  

2. gsutil https://cloud.google.com/storage/docs/gsutil (buckets)

gsutil ls   

3.  bq (big query)

bq help

4. cbt help 

# Refs APIs from google cloud usage

https://console.cloud.google.com/apis/dashboard  
https://cloud.google.com/products/  

# Examples Commands Used

```
export PROJECT_ID=$(gcloud info --format='value(config.project)')  

gcloud services enable cloudapis.googleapis.com  container.googleapis.com containerregistry.googleapis.com  

gcloud container clusters create cluster-steam --zone europe-west4-a --num-nodes 2 --enable-autoscaling --min-nodes 1 --max-nodes 3 --enable-autorepair  

gcloud auth configure-docker  

export username=$(gcloud secrets versions access 1 --secret="username" --format='get(payload.data)' | tr '_-' '/+' | base64 -d)  (SECRETS)

export password=$(gcloud secrets versions access 1 --secret="password" --format='get(payload.data)' | tr '_-' '/+' | base64 -d)  

kubectl delete -f MicroServices/ingress.yaml  
helm del nginx-ingress  
helm repo remove ingress-nginx  
gcloud container clusters delete cluster-steam --zone=europe-west4-a  

```


# Always check metrics: 

Latency  
Traffic  
Errors  
Saturation 


🚀🚀🚀🚀🚀
