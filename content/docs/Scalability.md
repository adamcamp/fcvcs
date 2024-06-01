+++
title = "Scalability"
weight = 4
+++

Scalability is how the internet works. Do you ever wonder how Google or Amazon or Facebook can handle billions of requests per second without missing a beat? The answer is scalability, or specifically horizontal scalability.

There are two types of scalability. Vertical scalability, which is making what you have bigger. Horizontal scalability, which is adding multiple instances, or copies, of the same thing.

Imagine you have a school building. That building has a capacity for 500 students. Obviously with population growth and such, 500 students is not enough. What do you do?

Either:

* Open a new school (scale horizontally)
* Make the existing school bigger (scale vertically)

So, if we look at the public school system as a whole, it has achieved both vertical and horizontal scalability. However, many of these changes are step functions, meaning they can not be made incrementally, and provisioning any new capacity is a process measured in years not weeks.

One major innovation of the last decade or so is the broader adoption of dynamic scaling. If you think of cloud computing and AWS EC2, this was really where it started. The ability to provision capacity dynamically in minutes means you don't need to worry about running out of capacity because in most circumstances it's just a few clicks away. If you get above 90% utilization you can easily provision enough new instances to get to a more comfortable utilization. 

What all this means for schools is that a virtual classroom no longer has the lead time of traditional brick and mortar schools. That means instead of overcrowding the classrooms, they can be scaled efficiently to handle the number of students at any given point in time. If you can create 1 virtual classroom, creating 100 or even 1000 virtual classrooms is just as easy to provision.

When the electric grid needs extra capacity they fire up a peaker plant. When Amazon is running slow because some dynamodb database doesn't have enough IOPs provisioned, they increase the IOPs. Same should happen with schools. When more students arrive than the school anticipated, then more teachers should be hired and classrooms should be stood up for them.

Let's be real, who wouldn't love to send their kid to one of Frederick County's wonderful charter schools? 

Now wouldn't it be nice if there was no waitlist, and a dedicated classroom could be spun up with a new teacher anytime the rooms got overcrowded?
