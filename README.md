# Hosting mulitple static websites on a single server
This repository acts as a guide to host multiple websites on a single server using AWS (Amazon Web Services).

![](images/aws%20logo.png)


<h2> Attribution </h2>
Hello everyone, you are welcome to make use of this guide and learn from it but please do not copy without giving attribution to the author.

<h2> Let's Start the Guide </h2>

First of all we will learn how to launch a virtual server on AWS on which we will be hosting our static websites. It takes only a few clicks to launch a new virtual server.
1. Open the AWS Management Console at https://console.aws.amazon.com.

2. Choose the region in which you want to launch your virtual server and make sure you choose the region nearer to users to        reduce latency.

3. Find the EC2 service in the navigation bar under Services and click it. It will open the EC2 Management Console.

4. To start the wizard for launching a virtual server, start by clicking on Launch Instance button.

This is how your EC2 Management looks like.

![](images/1.png)

After clicking on the Launch Instance button you will be redirected for selecting the operating system for your virtual machine. The first step is to choose a bundle of an OS and preinstalled software for your virtual server called an Amazon Machine Image(AMI). Here I will be working on Amazon Linux AMI 2018.03.0(HVM).

![](images/2.png)


