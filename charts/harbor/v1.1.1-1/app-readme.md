# Harbor Registry  
   
Harbor is an an open source trusted cloud native registry project that stores, signs, and scans content. Harbor extends the open source Docker Distribution by adding the functionalities usually required by users such as security, identity and management. Having a registry closer to the build and run environment can improve the image transfer efficiency. Harbor supports replication of images between registries, and also offers advanced security features such as user management, access control and activity auditing.   
   
Harbor is hosted by the Cloud Native Computing Foundation (CNCF).
   
Before using this chart, you must create the destination workspace and deploy a valid certificate secret into it. The certificate cannot be self-signed; if you want to use a Let's Encrypt certificate you can use the "letsencrypt-certificate" chart to generate a valid certificate.   
