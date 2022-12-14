# CrowdStrike Container Security

[![CrowdStrike Container Security](./assets/youtube.png)](http://www.youtube.com/watch?v=4F1MtmgIvus "CrowdStrike Container Security")

## Runtime Protection
To protect container workloads choose between the following approaches
1) Run **Falcon Sensor for Linux** per worker node as a **DaemonSet**, recommended when worker node OS is supported.
2) Run **Falcon Container Sensor for Linux** per pod as a **sidecar**, recommended when worker node OS is not supported.

> Note: The DaemonSet deployment will protect both host and container workloads while sidecar deployments only protect the container workloads.

## Deployment

Use the [Falcon Helm Chart](https://github.com/CrowdStrike/falcon-helm/tree/main/helm-charts/falcon-sensor) or the [Falcon Operator](https://github.com/CrowdStrike/falcon-operator).

## Additional Resources
 - CrowdStrike Container Security: [Product Page](https://www.crowdstrike.com/products/cloud-security/falcon-cloud-workload-protection/container-security/)
 - So You Think Your Containers Are Secure? Four Steps to Ensure a Secure Container Deployment: [Blog Post](https://www.crowdstrike.com/blog/four-steps-to-ensure-a-secure-containter-deployment/)
 - Container Security With CrowdStrike: [Blog Post](https://www.crowdstrike.com/blog/tech-center/container-security/)
 - To learn more about Falcon Container Sensor for Linux: [Deployment Guide](https://falcon.crowdstrike.com/support/documentation/146/falcon-container-sensor-for-linux), [Release Notes](https://falcon.crowdstrike.com/support/news/release-notes-falcon-container-sensor-for-linux)
