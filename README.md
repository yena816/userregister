<h1>Spring Boot</h1>
<p>Tutorial used: https://youtu.be/yp_uleaOzV4?si=pimcOzQa9GEXgQvz </p>
<p>Things I changed: MySQL info in application.properties to my RDS database</p>
<p>Make sure RDS database is publicly accessible.</p>
<p>Use MySQL Workbench to query database and make sure changes are going through. </p>

<h1>EKS Cluster</h1>
<p>Follow same instructions as document but use NGINX controller: https://aws.amazon.com/blogs/containers/exposing-kubernetes-applications-part-3-nginx-ingress-controller/ </p>
<p>Change the containerPort in deployment yaml to 8080. Make sure the image is your ECR image URI.</p>
