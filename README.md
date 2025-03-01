<p align="center"> 
<img src="images/opencart.png" alt="OpenCart">
</p>

# OpenCart

The package deploys the [OpenCart](https://www.opencart.com/) solution - an open-source e-commerce platform to create, scale, and run your business. OpenCart provides a professional and reliable foundation for building an online store. It offers a wide range of powerful features and extensions, making it easy to customize and scale.


## Environment Topology

This package creates a dedicated OpenCart environment that contains one application server and one database container. It automatically deploys and sets the OpenCart application. The automatic vertical scaling is enabled out of the box, and [horizontal scaling](https://www.virtuozzo.com/application-platform-docs/automatic-horizontal-scaling/) can be configured (if needed). The default software stacks utilized in the package are the following:

- Apache 2 PHP application server (PHP 8.3)
- MySQL 8 database
- OpenCart 4.0.2.3


## Deployment to Cloud

To get your OpenCart solution, click the "**Deploy to Cloud**" button below, specify your email address within the widget, choose one of the [Virtuozzo Public Cloud Providers](https://www.virtuozzo.com/application-platform-partners/), and confirm by clicking **Install**.

[![Deploy to Cloud](https://raw.githubusercontent.com/jelastic-jps/common/main/images/deploy-to-cloud.png)](https://www.virtuozzo.com/install/?manifest=https://raw.githubusercontent.com/jelastic-jps/opencart/refs/heads/master/manifest.jps)

> If you already have a Virtuozzo Application Platform (VAP) account, you can deploy this solution from the [Marketplace](https://www.virtuozzo.com/application-platform-docs/marketplace/) or [import](https://www.virtuozzo.com/application-platform-docs/environment-import/) a manifest file from this repository.


## Installation Process

In the opened installation window at the VAP dashboard, provide a preferred environment and display names, choose a region (if available), and confirm the installation.

![OpenCart deployment wizard](images/opencart-deployment-wizard.png)

Your OpenCart application will be automatically installed in a few minutes.
