<div align="center">

<!-- Header Banner -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:00F0FF,50:7000FF,100:00FF87&height=220&section=header&text=Avinash%20Kumar&fontSize=48&fontAlignY=38&desc=DevSecOps%20Engineer%20%7C%20Cloud%20Architect%20%7C%20Security%20Automation&descAlignY=60&descAlign=50&fontColor=ffffff" width="100%" alt="Avinash Kumar Header Banner"/>

<!-- Dynamic Typing Subtitle -->
<a href="https://github.com/AjavinashAj">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=21&pause=1000&color=00F0FF&center=true&vCenter=true&width=850&lines=DevSecOps+Engineer+with+3%2B+Years+of+Production+Experience;Architecting+Zero-Trust+Cloud+%26+Azure+Infrastructure;Shift-Left+Security%3A+GitLeaks+%E2%9E%9E+Trivy+%E2%9E%9E+SonarQube;Automating+Everything+with+Terraform%2C+Docker+%26+Kubernetes;Turning+Complex+Cloud+Systems+into+Declarative+Code" alt="Typing SVG" />
</a>

<br/>

<!-- Real-Time Status Badges -->
<p align="center">
  <a href="https://linkedin.com/in/avinashkumar1345" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-Avinash_Kumar-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn Badge"/>
  </a>
  <a href="https://github.com/AjavinashAj">
    <img src="https://img.shields.io/badge/Experience-3+_Years_in_DevSecOps-00F0FF?style=for-the-badge&logo=codewars&logoColor=black" alt="Experience Badge"/>
  </a>
  <a href="https://github.com/AjavinashAj">
    <img src="https://img.shields.io/badge/Focus-Cloud_&_DevSecOps-7000FF?style=for-the-badge&logo=cloud&logoColor=white" alt="Focus Badge"/>
  </a>
  <a href="https://komarev.com/ghpvc/?username=AjavinashAj&label=PROFILE+VIEWS&style=for-the-badge&color=00ff87" target="_blank">
    <img src="https://komarev.com/ghpvc/?username=AjavinashAj&label=PROFILE+VIEWS&style=for-the-badge&color=00ff87" alt="Profile Views"/>
  </a>
</p>

<!-- Quick Navigation Anchors -->
<p align="center">
  <a href="#-about-me"><b>About Me</b></a> •
  <a href="#-devsecops-pipeline-architecture"><b>DevSecOps Pipeline</b></a> •
  <a href="#-technical-arsenal"><b>Tech Arsenal</b></a> •
  <a href="#-featured-projects"><b>Featured Projects</b></a> •
  <a href="#-engineering-philosophy"><b>Core Principles</b></a> •
  <a href="#-github-metrics--telemetry"><b>Metrics & Telemetry</b></a> •
  <a href="#-connect-with-me"><b>Connect</b></a>
</p>

---

</div>

## 👤 About Me

```yaml
apiVersion: universe/v1
kind: DevSecOpsEngineer
metadata:
  name: "Avinash Kumar"
  experience: "3+ Years in Enterprise DevOps & DevSecOps"
  reputation: "Battle-Tested Production Engineer 🛡️"
spec:
  cloud_ecosystem: ["Microsoft Azure", "Multi-Cloud Architectures"]
  iac_standards: ["Terraform", "Terragrunt", "Ansible", "Bash/Python"]
  containers_orchestration: ["Docker", "Kubernetes (AKS)", "Helm", "Microservices"]
  security_posture: ["Zero-Trust", "Shift-Left", "SAST/DAST/SCA", "Container Hardening"]
  ci_cd_engines: ["GitHub Actions", "Azure DevOps Pipelines", "Jenkins", "GitOps"]
  observability: ["Prometheus", "Grafana", "Azure Monitor", "Alertmanager"]
  mission: "Eliminating deployment friction while embedding unbreachable security gates into every commit."
```

👋 **Hello, World! I'm Avinash Kumar** — a passionate **DevSecOps & Cloud Engineer** with over 3 years of hands-on experience designing, automating, and securing cloud-native infrastructures.

- 🛡️ **Shift-Left Security Advocate**: I inject automated security gates (*SAST, SCA, Secret Scanning, Container Auditing, and IaC Hardening*) into CI/CD pipelines before code ever reaches production.
- ☁️ **Cloud & Infrastructure as Code (IaC)**: Architecting highly available, modular Azure environments using **Terraform**, automated networking (VNet, NSG, Private Endpoints), and zero-drift state management.
- 🚀 **Continuous Delivery & Automation**: Building blazing-fast, declarative CI/CD pipelines using **GitHub Actions**, **Azure DevOps**, and **Jenkins** to take features from pull request to production with zero downtime.
- 🐳 **Containerization & Orchestration**: Hardening Docker images with multi-stage builds and managing resilient workloads on **Kubernetes (AKS)** using Helm and GitOps best practices.

---

## 🛡️ DevSecOps Pipeline Architecture

> *"Security isn't a gatekeeper at the end of the line — it is the steel foundation running through every stage of software delivery."*

```mermaid
flowchart LR
    A[📝 Code Commit] -->|GitLeaks / Pre-commit| B(🏗️ Build Stage)
    B -->|SonarQube SAST / Snyk SCA| C{🧪 Test & Verify}
    C -->|Trivy / Container Scan| D[📦 Package & Harden]
    D -->|Checkov / tfsec| E[📜 IaC Terraform Apply]
    E -->|Cosign / Signed Image| F[🚀 Deploy to AKS]
    F -->|Prometheus / Grafana / Falco| G[🛡️ Monitor & Defend]

    classDef stage fill:#0d1117,stroke:#00f0ff,stroke-width:2px,color:#fff;
    classDef gate fill:#161b22,stroke:#7000ff,stroke-width:2px,color:#fff;
    classDef deploy fill:#0d1117,stroke:#00ff87,stroke-width:2px,color:#fff;
    class A,B,D,E stage;
    class C gate;
    class F,G deploy;
```

### 🔒 Enterprise Security Gates Matrix

| Pipeline Phase | Primary Objective | Weapons & Tools Deployed | Security Impact |
| :--- | :--- | :--- | :--- |
| **01. Source & Commit** | Prevent Secrets & Credential Leakage | `GitLeaks`, `Pre-commit Hooks`, `Git` | Zero accidental API keys or passwords in Git history |
| **02. Continuous Integration** | Static Code Analysis & Dependency Check | `SonarQube (SAST)`, `Snyk (SCA)`, `OWASP` | Identifies CVEs and code smells at the PR stage |
| **03. Artifact Packaging** | Vulnerability-Free Container Images | `Docker Multi-stage`, `Trivy`, `Alpine/Distroless` | Eliminates image bloat, root privileges & CVEs |
| **04. Infrastructure as Code** | Compliance & Misconfiguration Auditing | `Terraform`, `tfsec`, `Checkov`, `Infracost` | Prevents exposed ports, open S3/Blob storage, and cost surprises |
| **05. Artifact Verification** | Cryptographic Supply Chain Security | `Cosign`, `Docker Content Trust` | Ensures only trusted, signed binaries run on Kubernetes |
| **06. Orchestration & GitOps** | Resilient Zero-Downtime Deployment | `Azure Kubernetes Service (AKS)`, `Helm`, `ArgoCD` | Declarative rollouts, self-healing pods, network isolation |
| **07. Telemetry & Runtime** | Proactive Observability & Threat Detection | `Prometheus`, `Grafana`, `Azure Monitor`, `Falco` | Real-time alerts, SLA monitoring, and runtime intrusion detection |

---

## 🛠️ Technical Arsenal

<div align="center">
  <img src="https://skillicons.dev/icons?i=azure,kubernetes,docker,terraform,ansible,githubactions,jenkins,linux,bash,python,git,prometheus,grafana" alt="Skill Icons Matrix"/>
</div>

<br/>

### ☁️ Cloud & Container Orchestration
<p>
  <img src="https://img.shields.io/badge/Microsoft_Azure-0089D6?style=for-the-badge&logo=microsoft-azure&logoColor=white" alt="Azure"/>
  <img src="https://img.shields.io/badge/Kubernetes_(AKS)-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white" alt="Kubernetes"/>
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker"/>
  <img src="https://img.shields.io/badge/Helm-0F1689?style=for-the-badge&logo=helm&logoColor=white" alt="Helm"/>
  <img src="https://img.shields.io/badge/Amazon_AWS-232F3E?style=for-the-badge&logo=amazon-aws&logoColor=white" alt="AWS"/>
</p>

### 📜 Infrastructure as Code (IaC) & Automation
<p>
  <img src="https://img.shields.io/badge/Terraform-7B42BC?style=for-the-badge&logo=terraform&logoColor=white" alt="Terraform"/>
  <img src="https://img.shields.io/badge/Ansible-EE0000?style=for-the-badge&logo=ansible&logoColor=white" alt="Ansible"/>
  <img src="https://img.shields.io/badge/GNU_Bash-4EAA25?style=for-the-badge&logo=gnu-bash&logoColor=white" alt="Bash"/>
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python"/>
  <img src="https://img.shields.io/badge/Linux_(Ubuntu/RHEL)-FCC624?style=for-the-badge&logo=linux&logoColor=black" alt="Linux"/>
</p>

### 🚀 CI/CD & GitOps Automation
<p>
  <img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=github-actions&logoColor=white" alt="GitHub Actions"/>
  <img src="https://img.shields.io/badge/Azure_DevOps_Pipelines-0078D7?style=for-the-badge&logo=azure-devops&logoColor=white" alt="Azure DevOps"/>
  <img src="https://img.shields.io/badge/Jenkins-D24939?style=for-the-badge&logo=jenkins&logoColor=white" alt="Jenkins"/>
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" alt="Git"/>
  <img src="https://img.shields.io/badge/ArgoCD-EF7B4D?style=for-the-badge&logo=argo&logoColor=white" alt="ArgoCD"/>
</p>

### 🛡️ DevSecOps, AppSec & Cloud Security
<p>
  <img src="https://img.shields.io/badge/Trivy_Scanner-0052CC?style=for-the-badge&logo=aquasec&logoColor=white" alt="Trivy"/>
  <img src="https://img.shields.io/badge/SonarQube_(SAST)-4E9BCD?style=for-the-badge&logo=sonarqube&logoColor=white" alt="SonarQube"/>
  <img src="https://img.shields.io/badge/Snyk_(SCA)-4C4A73?style=for-the-badge&logo=snyk&logoColor=white" alt="Snyk"/>
  <img src="https://img.shields.io/badge/Checkov_IaC_Security-1E88E5?style=for-the-badge&logo=bridgecrew&logoColor=white" alt="Checkov"/>
  <img src="https://img.shields.io/badge/HashiCorp_Vault-000000?style=for-the-badge&logo=vault&logoColor=white" alt="Vault"/>
  <img src="https://img.shields.io/badge/OWASP_ZAP-00549E?style=for-the-badge&logo=owasp&logoColor=white" alt="OWASP"/>
</p>

### 📊 Observability, Telemetry & Logging
<p>
  <img src="https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=prometheus&logoColor=white" alt="Prometheus"/>
  <img src="https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=white" alt="Grafana"/>
  <img src="https://img.shields.io/badge/Azure_Monitor-0078D4?style=for-the-badge&logo=microsoft-azure&logoColor=white" alt="Azure Monitor"/>
  <img src="https://img.shields.io/badge/Nginx-009639?style=for-the-badge&logo=nginx&logoColor=white" alt="Nginx"/>
</p>

---

## 🚀 Featured Projects & Production Architectures

<table>
  <tr>
    <td width="50%" valign="top">
      <h3>🏗️ <a href="https://github.com/AjavinashAj/terraform-azure-modular-infrastructure">Terraform Azure Modular Infrastructure</a></h3>
      <p><b>Production-Grade Enterprise Cloud Foundation</b></p>
      <ul>
        <li>Architected modular, reusable Terraform blueprints for Azure Hub-and-Spoke networks.</li>
        <li>Implemented Azure VNets, Subnets, Network Security Groups (NSGs), and Private Endpoints.</li>
        <li>Zero-Trust state isolation utilizing Azure Blob Storage with remote state locking.</li>
        <li>CIS benchmark compliance integration with automated <code>tfsec</code> scanning.</li>
      </ul>
      <p>
        <img src="https://img.shields.io/badge/Terraform-1.5+-7B42BC?style=flat-square&logo=terraform&logoColor=white"/>
        <img src="https://img.shields.io/badge/Azure-Production-0089D6?style=flat-square&logo=microsoft-azure&logoColor=white"/>
        <img src="https://img.shields.io/badge/Security-tfsec_Passed-00FF87?style=flat-square"/>
      </p>
    </td>
    <td width="50%" valign="top">
      <h3>⚡ <a href="https://github.com/AjavinashAj/Azure_Terraform_DevOps">Azure DevOps CI/CD Automation Engine</a></h3>
      <p><b>End-to-End Automated Cloud Provisioning Pipeline</b></p>
      <ul>
        <li>Built resilient multi-stage CI/CD pipelines deploying infrastructure across Dev, Stage, and Prod.</li>
        <li>Integrated automated validation, <code>terraform plan</code> diff generation, and manual security gates.</li>
        <li>Integrated Azure Key Vault for seamless, zero-hardcoded secret injection during deployments.</li>
        <li>Self-hosted Azure DevOps agent configuration on hardened Linux virtual machines.</li>
      </ul>
      <p>
        <img src="https://img.shields.io/badge/Azure_DevOps-Pipelines-0078D7?style=flat-square&logo=azure-devops&logoColor=white"/>
        <img src="https://img.shields.io/badge/IaC-Automated-7B42BC?style=flat-square"/>
        <img src="https://img.shields.io/badge/Key_Vault-Secured-00F0FF?style=flat-square"/>
      </p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3>🛡️ <a href="https://github.com/AjavinashAj/Avinash_DevOps">Enterprise DevSecOps & Container Security</a></h3>
      <p><b>Multi-Stage Hardened Microservices Pipeline</b></p>
      <ul>
        <li>Developed production Docker images with distroless base images, reducing attack surface by 70%.</li>
        <li>Automated container vulnerability scanning using <b>Trivy</b> with build break thresholds for Critical CVEs.</li>
        <li>Implemented <b>GitLeaks</b> pre-commit and pipeline scans to prevent secret leaks across repos.</li>
        <li>Configured SonarQube quality gates ensuring code reliability, security rating A, and high test coverage.</li>
      </ul>
      <p>
        <img src="https://img.shields.io/badge/Docker-Hardened-2496ED?style=flat-square&logo=docker&logoColor=white"/>
        <img src="https://img.shields.io/badge/Trivy-CVE_Audited-0052CC?style=flat-square"/>
        <img src="https://img.shields.io/badge/SonarQube-Gate_Passed-4E9BCD?style=flat-square"/>
      </p>
    </td>
    <td width="50%" valign="top">
      <h3>☸️ <a href="https://github.com/AjavinashAj/Avinash_DevOps">Kubernetes (AKS) Cluster & GitOps Delivery</a></h3>
      <p><b>Scalable High-Availability Cloud Orchestration</b></p>
      <ul>
        <li>Configured multi-node Azure Kubernetes Service (AKS) with automated node scaling.</li>
        <li>Packaged microservices into customized <b>Helm Charts</b> with parameterized values for each environment.</li>
        <li>Enforced Kubernetes NetworkPolicies, Pod Security Standards, and RBAC least-privilege access.</li>
        <li>Deployed Nginx Ingress Controller with automated TLS termination via Cert-Manager and Let's Encrypt.</li>
      </ul>
      <p>
        <img src="https://img.shields.io/badge/Kubernetes-AKS-326CE5?style=flat-square&logo=kubernetes&logoColor=white"/>
        <img src="https://img.shields.io/badge/Helm-Charts-0F1689?style=flat-square&logo=helm&logoColor=white"/>
        <img src="https://img.shields.io/badge/TLS-Auto_SSL-00FF87?style=flat-square"/>
      </p>
    </td>
  </tr>
</table>

---

## ⚡ Engineering Philosophy

```
  +---------------------------------------------------------------------------------+
  |  "Amateurs defend systems at runtime. Masters design systems that cannot drift." |
  +---------------------------------------------------------------------------------+
```

- 🛡️ **Shift-Left Early & Uncompromisingly**: Security must be friction-free for developers. When security tools run inside pull requests with actionable feedback, bugs are fixed in minutes rather than weeks.
- 📜 **Infrastructure as Code (IaC) is Non-Negotiable**: No manual clicks in cloud consoles. If it's not codified, peer-reviewed, and versioned in Git, it does not exist in production.
- 🔄 **Immutable Infrastructure**: Servers and containers are disposable cattle, never pets. Immutable builds guarantee consistency between development, staging, and enterprise production.
- 📈 **Proactive Observability over Reactive Firefighting**: Metrics, distributed traces, and automated alerts empower engineering teams to prevent outages before users ever notice an anomaly.

---

## 📊 GitHub Metrics & Telemetry

<div align="center">

<table border="0">
  <tr>
    <td>
      <a href="https://github.com/AjavinashAj">
        <img src="https://github-readme-stats.vercel.app/api?username=AjavinashAj&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=00F0FF&icon_color=00F0FF&text_color=8B949E" alt="Avinash's GitHub Stats" />
      </a>
    </td>
    <td>
      <a href="https://github.com/AjavinashAj">
        <img src="https://github-readme-streak-stats.herokuapp.com/?user=AjavinashAj&theme=tokyonight&hide_border=true&background=0D1117&ring=00F0FF&fire=00F0FF&currStreakNum=ffffff" alt="Avinash's GitHub Streak" />
      </a>
    </td>
  </tr>
</table>

<br/>

<a href="https://github.com/AjavinashAj">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=AjavinashAj&layout=compact&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=00F0FF&text_color=8B949E" alt="Top Languages" />
</a>

</div>

---

## 📬 Connect With Me

<div align="center">

<p><b>Whether you want to discuss DevSecOps pipelines, Cloud Architecture, Kubernetes security, or collaborate on open-source projects — let's connect!</b></p>

<p align="center">
  <a href="https://www.linkedin.com/in/avinashkumar1345" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn Profile"/>
  </a>
  <a href="https://github.com/AjavinashAj" target="_blank">
    <img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" alt="GitHub Profile"/>
  </a>
  <a href="https://www.linkedin.com/in/avinashkumar1345" target="_blank">
    <img src="https://img.shields.io/badge/Direct_Message-Connect_on_LinkedIn-00F0FF?style=for-the-badge&logo=telegram&logoColor=black" alt="Direct Message"/>
  </a>
</p>

<br/>

<!-- Footer Banner -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:7000FF,50:0070F3,100:00F0FF&height=130&section=footer" width="100%" alt="Footer Banner"/>

<p align="center">
  <i>⚡ Engineered with passion for Zero-Trust Cloud & Bulletproof Pipelines • © Avinash Kumar ⚡</i>
</p>

</div>
