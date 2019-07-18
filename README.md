# kubernetes-learning-demo-app

This is created to document my learnings on Kubernetes. As part of this project, I did the following.

- Set up a Kubernetes CLuster Using Kubernetes Engine in GCP.
- Created Deployments for Guestbook front end application and REDIS backend. Yaml files added in respective folders.
- Created ClusterIP Services for REDIS for communication between deployments.
- Created a LoadBalancer Service to enable external communication for Frontend application.
- Application can be accessed [here](http://104.197.56.213/).

### Docker Images Used:-

Frontend: gcr.io/google-samples/gb-frontend:v4
REDIS: gcr.io/google_samples/gb-redisslave:v1
