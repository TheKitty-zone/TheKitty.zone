---
title: About the project
---
The kitty zone is a place where you can feel safe, be yourself and not worry about big tech watching or tracking you.\
You may ask why this name?\
Well, I wanted it to be more then just a Y instance of Z project hence I came up with this name/domain. 

Also I feel the need to express myself on the internet while not being like everyone else just using social media, instead I also want to give back to people who don't want to jump through all the hoops to host all kind of services.

About me
---

I'm just someone that is interested in DevOps and Software Engineering.\
I go by 11tuvork28/Zozo depending on where you see me online.\
I my opinion social media is really really unproductive and to say the least its plain dangerous but who has their own homepage right? right? :>)

I love tinkering with Terraform, Ansible and Kubernetes k3s to be specific :) So I always try to deliver the experience while not taking anything not even more data then required, which leads quite good to the policy part.


Polices
---

Logging:\
What gets logged across all services:
- Request timestamp
- Accessed services:
    - Service namespace
    - Service name
    - Service port
- Response timestamp
- Status code

That's it! I really don't need more to get a good understanding of what is going on and what services are used much, which not so much and which are unhealthy.

You might ask yourself but can't she correlate requests to users?\
No, I can't since these log lines I get from traefik don't contain any Personal indetifyable information about the client.\
You don't trust me? Good!\
You can just visit this repository [here](https://github.com/11Tuvork28/k3s-infra/blob/d41397556d7be647ffdc8e6696a3f22e932d8c4d/deployments/traefik/traefik.yaml#L30) and check the traefik deployment file youself.



