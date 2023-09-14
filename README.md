<h1>Subnet Association with Network Security Groups</h2>

<h2>Overview</h2>
In this lab, we'll build out a Virtual Network and divide a 10.0.0.0/24 subnet into two subnets of 10.0.0.0/25 and a 10.0.0.128/25. We'll then apply subnet association utilizing a Network Security Group.
<br />
<img sr="https://imgur.com/d68JinP.png" alt="overview of lab"/>
<br />

<h2>Process</h2>
<br />
We'll start by creating our initial virtual network.
<img src="https://imgur.com/zdaWpw0.png" alt="create virtual network"/>
Now we’ll create our address space of 10.0.0.0/24 with 256 addresses, and create a subnet of 10.0.0.0/25 with 128 addresses.

After our subnet gets created we can see it on our overview of VNets.
<img src="https://imgur.com/8obFdyj.png" alt="creating first subnet"/>
If we click on "subnet" on the left toolbar, we can now build out our second subnet of 10.0.0.128/25.
<img src="https://imgur.com/KZqrYub.png" alt="adding second subnet"/>
Now that we have both subnets created, we will create a Network Security Group.
<img src="https://imgur.com/KvTbwYR.png" alt="create network security group">
<img src="https://imgur.com/7o8TONL.png" alt="network security group features">
At this point we’ll associate our two subnets.
<img src="https://imgur.com/YpeccpW.png" alt="associate subnet 1"/>
<img src="https://imgur.com/TlciQDD.png" alt="associate subnet 2"/>
<img src="https://imgur.com/6ytdWmL.png" alt="subnet overview"/>
If we look at our Virtual Network, we can see both of our subnets are associated with our Network Security Group.
<img src="https://imgur.com/abj6grC.png" alt="subnets">