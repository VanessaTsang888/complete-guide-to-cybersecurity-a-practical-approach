# Building your cybersecurity lab

To gain hands on cybersecurity experience. I am studying for the [Offensive Security Essentials CyberCore 100 (SEC-100) Certification](https://www.offsec.com/courses/sec-100/) as I am looking to secure a new role as a cybersecurity professional such as one of the below:

1. Website Application Security Developer.
2. Website Application Security Engineer.
3. Security Software Engineer.
4. Website Application Security Administrator.
5. Website Application Security Penetration Tester.
6. Website Application Security Consultant.
7. Cybersecurity Analyst
8. Bug Bounty Hunter.

## Why the SEC-100?

This course is very hands-on practical cybersecurity training course with many labs. Also, this course is a large-scale and in-depth course that covers x40 moduels such:

- Background to Contemporary Generative AI (GenAI)
- Cloud Computing Fundmentals
- Offensive Cloud Fundamentals
- Cloud Architecture Fundaments
- Introduction to Defensive Cybersecurity Skills
- Understand Web Attacks.

### Offensive Security (OffSec)

I decided to study cybersecurity with the Offensive Security (OffSec) company because they are a popular American international company working in information security, penetration testing, and digital forensics. Studying with this company will provide me with a comprehensive understanding of how cyber attackers operate, enabling me to better protect against potential threats. By simulating real-world attacks, I can identify vulnerabilities and weaknesses in my organization's defenses, which can then be addressed and remediated before they can be exploited by actual malicious actors.

Offensive Security strategies help improve the visibility of my cyber footprint and identify issues, allowing me to enhance my employer's security posture. Engaging in offensive security measures, such as penetration testing, social engineering, and phishing simulations, can offer key insights into the health of my employer's network and where risks are present.

Moreover, offensive security testing can be more effective than defensive measures alone because it allows me to test my employer's defenses in a proactive manner, rather than waiting for a real attack to occur. This approach helps ensure that my employers defensive measures are robust and can withstand actual cyber threats.

Additionally, offensive security can help me stay ahead of cybercriminals by continuously innovating and adapting to new attack techniques. This proactive stance is crucial in the ever-evolving landscape of cybersecurity.

By studying Offensive Security, I can develop the skills and knowledge necessary to protect my employer's organization's data and systems from potential breaches, thereby safeguarding the company's reputation, growth, and overall health.

## Transcript

Building a cybersecurity lab can be a great way to gain hands-on experience and improve your skills in the field. Here are some tips for building your own lab. First, identify your goals, determine what you want to accomplish with your lab. This can be learning a specific technology, a security tool, an ethical hacking methodology, and so on. This will help you determine what equipment and resources you need. Choose your hardware. Decide on the type of hardware you will use for your lab. You can use things like physical equipments, virtual machines, or a combination of both. Configure your network. Set up your lab network, including routers, switches, firewalls, and those can be virtual or physical. Configure your lab network with the same protocols and settings that you will find in real world environments. Install software. Install things like the operating system, software that you will use in your lab, security tools, as we mentioned. You know, make sure to include these security tools such as intrusion detection systems, intrusion prevention systems, or IPS, firewalls, antivirals, anti-malware, malware analysis tools, and so on. Practice and experiment. Once your lab is set up, use it to practice and experiment with different security techniques and tools. This will help you get a better understanding on how to protect networks and systems from cyber threats and also how to attack them in the case of ethical hacking. Create virtual machines. Use virtualization software like Proxmox, KVM, VirtualBox, and you can use, you know, these to create virtual machines to use in your lab, or even use container technologies like Docker, Kubernetes, and many others. Let's go over a learning environment that I created called WebSploit. I want to draw your attention to this learning environment because I will be using this learning environment throughout the class. To get access to this, you go to websploit.org, as I'm showing in the screen, and it will take you, of course, to this website and where it has basically two steps. First, is to download either Kali Linux, or Parrot, and those are the most popular Linux distributions for people that are getting started in cybersecurity or ethical hacking and so on. Now, at the end of the day, behind the scenes, they're running DBN, right? And what I did in here is that I have the minimum requirements that you will put in a VM. Make this a little bit bigger. And at the end of the day, you know, with four gigs of Ram, two virtual CPUs and 50 gigs of hard drive, you can get this VM started that has a significant number of resources, including over 500 different exercises related to ethical hacking and cybersecurity. Now, how you set this up is you download Kali or Parrot. You can download both if you want to, but one or the other, you put it in the virtualization technology of your choosing, whether it's Proxmox, VMware, an ESXi server, an OPC, you know, running KVM, and so on. And then the second step is extremely easy. Basically run the script that I have in the screen, and this will install different tools that do not come with Kali or Parrot, and it will also install Docker, and it will instantiate different intentional vulnerable applications that I'm running in containers. Now, those containers include applications that have different exercises and different learning environments that you can use. You may recognize some of them in here, like WebGoat, JuiceShop, Mutilidae. Those are projects from the Open Web Application Security Project. It's a non-profit organization that is very well known in the industry. The ones on the left are beginner to intermediate. Now the ones on the right are intermediate to advanced, and these are several that I have personally created for things like Capture the Flag and DEF CON. And DEF CON is the biggest hacking conference in the world. I lead the Red Team Village there. And I use these as learning environments for many competitions and many workshops and where people, you know, try to hack and find different vulnerabilities. And again, I have included them in here in a very safe environment to use with technologies like Docker, Docker bridge interfaces, and so on. So you can practice your skills in a very safe environment and don't affect anything else in your network. So I strongly recommend that you take advantage of these resources and we will continue to use them throughout the training.
