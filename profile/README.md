# BitPath Inc.

## Introduction
BitPath Inc. is a company headquartered in Virginia, USA. BitPath’s all-new broadcast data network is vastly more efficient than any cellular network for delivering the same data streams and files to large numbers of users and devices.

The mission of the company is to provide our customers with an entirely new wireless platform, built upon an efficient broadcast architecture, which can meet the exploding demand for data services that cover an ocean of devices simultaneously.

BitPath aims to distribute public domain software through these github repositories.

## Documentation
BitPath Devkit documentation consists of 2 types are as follows,
1.	User Guide   
> The User Guide documentation, designed with simplicity in mind, is primarily for those who use the golden image that BitPath provides to effortlessly collect the data from the receiver via Redis-server.   
>    
> **[Working With Golden Image](https://github.com/BitPath-DevKit/.github/blob/main/Documentation/User%20Guide/Working%20with%20Golden%20Image.pdf)**    
>	- To get started with the golden image, you need to download it from AWS S3 Bucket and clone it to the SD Card.   
>    
> **[User Guide](https://github.com/BitPath-DevKit/.github/blob/main/Documentation/User%20Guide/UserGuide.pdf)**   
>	- Once you have successfully installed the Golden Image, the User Guide provides a step-by-step guide on how to collect data from the Redis server remotely.    

2.	Golden Image and Cloud Set-Up    
> The Golden Image and Cloud Set-Up are used to build the Golden Image from scratch as well as install and set up the required application in the cloud.    
>      
> **[Golden Image Details](https://github.com/BitPath-DevKit/.github/blob/main/Documentation/Golden%20Image%20and%20Cloud%20Set%20Up/Golden%20Image%20Details.pdf)**    
>	- Here are the tools and libraries that need to be installed on the Golden Image, along with initial configuration details for setting up a Raspberry Pi.    
>    
> **[Influx-Grafana-Installation](https://github.com/BitPath-DevKit/.github/blob/main/Documentation/Golden%20Image%20and%20Cloud%20Set%20Up/Influx-Grafana-Installation.pdf)**    
>	- Here are instructions for selecting and configuring EC2 instances on AWS, as well as the installation and configuration procedure for Grafana and Influx on an EC2 instance.    
>     
> **[Installing TIG Stack](https://github.com/BitPath-DevKit/.github/blob/main/Documentation/Golden%20Image%20and%20Cloud%20Set%20Up/Installing%20TIG%20Stack.pdf)**    
>	- Enabling and configuring ssl in the Grafana and influxDB.    
>	- Installing and configuring Telegraf on the edge device.    
>     
> **[Installed Tools and Configuration](https://github.com/BitPath-DevKit/.github/blob/main/Documentation/Golden%20Image%20and%20Cloud%20Set%20Up/Installed%20Tools%20and%20Configuration.pdf)**     
>	- List of installed tools and instructions to install and configure software such as Promtail, system manager components, and Telegraf agent with vcgencmd for preparing a golden image on an SD card.    
>     
> **[Remote Jobs using AWS IoT Core FleetHub](https://github.com/BitPath-DevKit/.github/blob/main/Documentation/Golden%20Image%20and%20Cloud%20Set%20Up/Remote%20jobs%20using%20AWS%20IoT%20Core%20FleetHub.pdf)**    
>	- AWS IoT Jobs define remote operations to be executed on multiple devices.    
>	- Configuring and managing instructions for AWS IoT Core FleetHub.    
>     
> **[IoT Job Testing](https://github.com/BitPath-DevKit/.github/blob/main/Documentation/Golden%20Image%20and%20Cloud%20Set%20Up/IoT%20Job%20Testing.pdf)**    
>	- This is a document to test the IoT job after configuring IoT Core FleetHub.   

