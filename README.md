# 💫 About Me:
Hello 👋 I'm Uddhav  <br><br>🛠️ Aspiring DevOps Engineer focused on automation and cloud technologies  <br>🐧 Hands-on experience with Linux, Git, Docker, and CI/CD tools  <br>☁️ Learning cloud platforms and container orchestration  <br>📈 Passionate about improving system reliability and deployment efficiency  <br>


# 💻 Skills:
![AWS](https://img.shields.io/badge/AWS-%23FF9900.svg?style=for-the-badge&logo=amazon-aws&logoColor=white) ![Java](https://img.shields.io/badge/java-%23ED8B00.svg?style=for-the-badge&logo=openjdk&logoColor=white) ![Jenkins](https://img.shields.io/badge/jenkins-%232C5263.svg?style=for-the-badge&logo=jenkins&logoColor=white) ![Apache Tomcat](https://img.shields.io/badge/apache%20tomcat-%23F8DC75.svg?style=for-the-badge&logo=apache-tomcat&logoColor=black) ![MySQL](https://img.shields.io/badge/mysql-4479A1.svg?style=for-the-badge&logo=mysql&logoColor=white) ![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white) ![Git](https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white) ![Ansible](https://img.shields.io/badge/ansible-%231A1918.svg?style=for-the-badge&logo=ansible&logoColor=white) ![Kubernetes](https://img.shields.io/badge/kubernetes-%23326ce5.svg?style=for-the-badge&logo=kubernetes&logoColor=white) ![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white)

# Personol Projects

## 🌐 Socials:
[![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?logo=linkedin&logoColor=white)](https://linkedin.com/in/Uddhav-hon) [![email](https://img.shields.io/badge/Email-D14836?logo=gmail&logoColor=white)](mailto:uddhavhon8265@gmail.com) 


### ✍️ Random Dev Quote
![](https://quotes-github-readme.vercel.app/api?type=horizontal&theme=radical)

---
[![](https://visitcount.itsvg.in/api?id=uddhav19&icon=0&color=0)](https://visitcount.itsvg.in)



<!-- HEADER BANNER -->
<div align="center">

```
╔══════════════════════════════════════════════════════════╗
║                                                          ║
║        ██████╗ ███████╗██╗   ██╗ ██████╗ ██████╗ ███████╗║
║        ██╔══██╗██╔════╝██║   ██║██╔═══██╗██╔══██╗██╔════╝║
║        ██║  ██║█████╗  ██║   ██║██║   ██║██████╔╝███████╗║
║        ██║  ██║██╔══╝  ╚██╗ ██╔╝██║   ██║██╔═══╝ ╚════██║║
║        ██████╔╝███████╗ ╚████╔╝ ╚██████╔╝██║     ███████║║
║        ╚═════╝ ╚══════╝  ╚═══╝   ╚═════╝ ╚═╝     ╚══════╝║
║                                                          ║
╚══════════════════════════════════════════════════════════╝
```

### `$ whoami`
> **Cloud & DevOps Engineer** · Automating the World, One Pipeline at a Time 🚀

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&size=18&pause=1000&color=00D4FF&center=true&vCenter=true&width=600&lines=Infrastructure+as+Code+%F0%9F%8F%97%EF%B8%8F;CI%2FCD+Pipeline+Architect+%F0%9F%94%A7;AWS+Cloud+Enthusiast+%E2%98%81%EF%B8%8F;Automating+Everything+%F0%9F%A4%96)](https://git.io/typing-svg)

</div>

---

## 🖥️ `cat /etc/about_me`

```yaml
name: "Your Name"
role: "DevOps / Cloud Engineer"
location: "Earth 🌍"
currently_learning: ["Kubernetes", "Terraform Advanced", "GitOps"]
ask_me_about: ["AWS", "CI/CD", "Docker", "Ansible", "Linux"]
fun_fact: "I automate things so I can be lazy the right way 😄"
```

---

## 🗂️ `ls -la ~/projects/`

### 🔧 Jenkins CI/CD Pipeline with Docker & GitHub
```bash
$ jenkins --deploy --env=production
✅ Build triggered  →  Tests passed  →  Docker image built  →  Deployed!
```
> Automated end-to-end CI/CD pipeline integrating **Jenkins**, **Docker**, and **GitHub webhooks** for seamless build, test, and deployment cycles. Zero-downtime deployments as a standard.

**Stack:** `Jenkins` `Docker` `GitHub Actions` `Shell Scripting`

---

### ☁️ AWS VPC Peering & EC2 Connectivity
```bash
$ aws ec2 create-vpc-peering-connection \
    --vpc-id vpc-XXXXXXX \
    --peer-vpc-id vpc-YYYYYYY
→ Peering connection: ACTIVE ✅
```
> Architected secure **cross-VPC communication** using AWS VPC Peering, enabling private EC2 instance communication without public internet exposure.

**Stack:** `AWS VPC` `EC2` `Route Tables` `Security Groups` `Linux CLI`

---

### 🌐 Static Website Hosting on AWS S3
```bash
$ aws s3 sync ./website s3://my-bucket --acl public-read
→ Upload complete: 42 files synced ✅
→ Website URL: http://my-bucket.s3-website-us-east-1.amazonaws.com
```
> Deployed and managed **production-grade static websites** using AWS S3 + CloudFront CDN. Optimized for scalability, low-latency delivery, and cost efficiency.

**Stack:** `AWS S3` `CloudFront` `AWS CLI` `Route53`

---

### ⚙️ Ansible Orchestrated Apache Web Hosting
```bash
$ ansible-playbook -i inventory.ini apache-setup.yml
PLAY RECAP ────────────────────────────────────────
server_01  : ok=5  changed=3  unreachable=0  failed=0
server_02  : ok=5  changed=3  unreachable=0  failed=0
server_03  : ok=5  changed=3  unreachable=0  failed=0
```
> Provisioned and configured a **multi-node Apache web server environment** on AWS EC2 using Ansible playbooks — consistent, repeatable, and idempotent.

**Stack:** `Ansible` `AWS EC2` `Apache` `Ubuntu` `YAML`

---

### 🏗️ Terraform AWS EC2 Provisioning
```hcl
resource "aws_instance" "linux_server" {
  ami           = "ami-0abcdef1234567890"
  instance_type = "t2.micro"
  tags = { Name = "linux" }
}
# terraform apply → Plan: 1 to add ✅
```
> Automated **AWS infrastructure provisioning** using Terraform IaC — version-controlled, reproducible cloud environments with a single command.

**Stack:** `Terraform` `AWS EC2` `HCL` `Infrastructure as Code`

---

## 🛠️ `dpkg --list | grep skills`

<div align="center">

| Cloud | DevOps | IaC | OS |
|:---:|:---:|:---:|:---:|
| ![AWS](https://img.shields.io/badge/AWS-%23FF9900.svg?style=for-the-badge&logo=amazon-aws&logoColor=white) | ![Jenkins](https://img.shields.io/badge/jenkins-%232C5263.svg?style=for-the-badge&logo=jenkins&logoColor=white) | ![Terraform](https://img.shields.io/badge/terraform-%235835CC.svg?style=for-the-badge&logo=terraform&logoColor=white) | ![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black) |
| ![EC2](https://img.shields.io/badge/Amazon%20EC2-FF9900?style=for-the-badge&logo=amazonec2&logoColor=white) | ![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white) | ![Ansible](https://img.shields.io/badge/ansible-%231A1918.svg?style=for-the-badge&logo=ansible&logoColor=white) | ![Ubuntu](https://img.shields.io/badge/Ubuntu-E95420?style=for-the-badge&logo=ubuntu&logoColor=white) |
| ![S3](https://img.shields.io/badge/Amazon%20S3-FF9900?style=for-the-badge&logo=amazons3&logoColor=white) | ![GitHub Actions](https://img.shields.io/badge/github%20actions-%232671E5.svg?style=for-the-badge&logo=githubactions&logoColor=white) | ![YAML](https://img.shields.io/badge/yaml-%23ffffff.svg?style=for-the-badge&logo=yaml&logoColor=151515) | ![Bash](https://img.shields.io/badge/bash-%23121011.svg?style=for-the-badge&logo=gnu-bash&logoColor=white) |

</div>

---

## 📊 `git log --stat`

<div align="center">

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=YOUR_USERNAME&show_icons=true&theme=tokyonight&hide_border=true)
![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=YOUR_USERNAME&layout=compact&theme=tokyonight&hide_border=true)

</div>

---

## 🤝 `ping social_links`

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/YOUR_USERNAME)
[![GitHub](https://img.shields.io/badge/GitHub-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)](https://github.com/YOUR_USERNAME)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:your@email.com)

</div>

---

<div align="center">

```bash
$ echo "Thanks for visiting! Let's build something great together." 
Thanks for visiting! Let's build something great together. 🚀
```

![Profile Views](https://komarev.com/ghpvc/?username=YOUR_USERNAME&color=00d4ff&style=flat-square)

</div>
