# BitPath Inc.

## Introduction
BitPath Inc. is a company headquartered in Virginia, USA. BitPath’s all-new broadcast data network is vastly more efficient than any cellular network for delivering the same data streams and files to large numbers of users and devices.

The mission of the company is to provide our customers with an entirely new wireless platform, built upon an efficient broadcast architecture, which can meet the exploding demand for data services that cover an ocean of devices simultaneously.

BitPath aims to distribute public domain software through these github repositories.

## Documentation
BitPath Devkit documentation consists of 2 types are as follows,
1.	User Guide   

> The User Guide documentation, designed with simplicity in mind, is primarily for those who use the golden image that BitPath provides to effortlessly collect the data from the receiver via Redis-server.   
> [Working With Golden Image]()    
>	To get started with the golden image, you need to download it from AWS S3 Bucket and clone it to the SD Card.   
> [User Guide]()   
>	Once you have successfully installed the Golden Image, the User Guide provides a step-by-step guide on how to collect data from the Redis server remotely.    

2.	Golden Image and Cloud Set-Up    

> The Golden Image and Cloud Set-Up are used to build the Golden Image from scratch as well as install and set up the required application in the cloud.    
> [Golden Image Details]()    
>	Here are the tools and libraries that need to be installed on the Golden Image, along with initial configuration details for setting up a Raspberry Pi.    
> [Influx-Grafana-Installation]()    
>	Here are instructions for selecting and configuring EC2 instances on AWS, as well as the installation and configuration procedure for Grafana and Influx on an EC2 instance.    
> [Installing TIG Stack]()    
>	Enabling and configuring ssl in the Grafana and influxDB.    
>	Installing and configuring Telegraf on the edge device.    
> [Installed Tools and Configuration]()     
>	List of installed tools and instructions to install and configure software such as Promtail, system manager components, and Telegraf agent with vcgencmd for preparing a golden image on an SD card.    
> [Remote Jobs using AWS IoT Core FleetHub]()    
>	AWS IoT Jobs define remote operations to be executed on multiple devices.    
>	Configuring and managing instructions for AWS IoT Core FleetHub.    
> [IoT Job Testing]()    
>	This is a document to test the IoT job after configuring IoT Core FleetHub.   

