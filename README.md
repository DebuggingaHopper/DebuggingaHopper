<div id="header" align="center">
  <img src="https://i.giphy.com/media/v1.Y2lkPTc5MGI3NjExdGRrdW5ndGViOXN2c20xdDc4b3hkMGd5cW51bmpkb25hMGt5Zmh6eCZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/Ex1w4IdYJDfa0/giphy.gif" width="100"/>
</div>

<h1 align="center">Hi, I'm Nelson Alvarez</h1>
<h3 align="center">System Administrator & Integration Engineer</h3>

<div id="badges" align="center">
  <a href="https://www.linkedin.com/in/nelsonjalvarez-dev">
    <img src="https://img.shields.io/badge/LinkedIn-blue?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn Badge"/>
  </a>
  <img src="https://komarev.com/ghpvc/?username=DebuggingaHopper&style=for-the-badge&color=blue" alt="Profile Views"/>
</div>

<div align="center">
  <img src="https://img.shields.io/badge/Current_Role-Lead_System_Administrator-success?style=for-the-badge" alt="Current Role"/>
  <img src="https://img.shields.io/badge/Experience-3_Years-blue?style=for-the-badge" alt="Experience"/>
  <img src="https://img.shields.io/badge/Specialization-Healthcare_IT-critical?style=for-the-badge" alt="Specialization"/>
</div>

---

### 👨‍💻 About Me

I'm a **System Administrator & Integration Engineer** specializing in healthcare IT infrastructure and Epic HL7 integrations. I manage Windows Server/Oracle environments and develop XSLT-based interfaces for 50+ healthcare facilities.

**What I do:**
- 🏥 Design and deploy Epic HL7 interfaces (inbound/outbound via Mirth Connect)
- 🖥️ Architect Windows Server and Oracle Database infrastructure
- 🔐 Implement Active Directory/LDAP integrations for enterprise authentication
- 🛡️ Maintain HIPAA compliance and security remediation for FDA-regulated systems
- 📊 Build internal automation tools using C# .NET and PowerShell

**Current Focus:**
- Leading interface development for 13+ custom Epic integrations
- Managing infrastructure deployments and server migrations
- Automating deployment workflows and configuration management

**Career Milestone:** Promoted from intern to Lead System Administrator in 10 months 🚀

---

### 🛠️ Technical Stack

<details>
<summary><b>🖥️ Infrastructure & Databases</b> (Click to expand)</summary>

| Technology | Proficiency | Use Case |
|------------|-------------|----------|
| **Windows Server 2016/2021** | ⭐⭐⭐⭐⭐ | Primary server environment for 50+ healthcare facilities |
| **Oracle Database 12c/19c** | ⭐⭐⭐⭐ | Database management, patching (OPatch), performance tuning |
| **Active Directory/LDAP** | ⭐⭐⭐⭐ | Enterprise authentication, security group integration |
| **VMware/Hyper-V** | ⭐⭐ | Virtual machine management for test/prod environments |

</details>

<details>
<summary><b>🔌 Integration & Messaging</b> (Click to expand)</summary>

| Technology | Proficiency | Use Case |
|------------|-------------|----------|
| **HL7 v2.x** | ⭐⭐⭐⭐⭐ | Healthcare messaging standard for Epic integrations |
| **XSLT** | ⭐⭐⭐⭐⭐ | Primary language for interface transformations |
| **Mirth Connect** | ⭐⭐⭐⭐ | Channel configuration for bi-directional messaging |
| **Epic Systems** | ⭐⭐⭐⭐ | Integration with Epic HIS (RXE, ORM, ORU messages) |
| **REST/SOAP APIs** | ⭐⭐⭐⭐ | ASP.NET web service brokers, API integrations |

</details>

<details>
<summary><b>💻 Development & Automation</b> (Click to expand)</summary>

| Technology | Proficiency | Use Case |
|------------|-------------|----------|
| **C# / .NET Framework** | ⭐⭐⭐⭐ | Internal tools, automation utilities, WinForms applications |
| **PowerShell** | ⭐⭐⭐⭐⭐ | Deployment automation, system configuration, scripting |
| **PL/SQL / T-SQL** | ⭐⭐⭐ | Database queries, stored procedures, data manipulation |
| **Git/GitLab** | ⭐⭐⭐⭐ | Version control for interface configurations |
| **TeamCity** | ⭐⭐⭐ | CI/CD pipelines for automated builds and deployments |

</details>

<details>
<summary><b>🔒 Security & Monitoring</b> (Click to expand)</summary>

| Technology | Proficiency | Use Case |
|------------|-------------|----------|
| **Tenable/Nessus** | ⭐⭐⭐⭐ | Vulnerability scanning and remediation planning |
| **ELK Stack** | ⭐⭐⭐ | Elasticsearch/Kibana for application monitoring |
| **FastReport** | ⭐⭐⭐⭐ | Label/report template customization |
| **HIPAA Compliance** | ⭐⭐⭐⭐ | Healthcare data security and privacy standards |

</details>

---

### 🚀 Public Projects

> **Note:** Most recent work is on private Gitea server for proprietary projects. Public repos showcase completed personal/academic projects.

#### **🔧 NEST** - Infrastructure Deployment Automation
> **Status:** ✅ Complete | **Last Updated:** 10/19/2025

PowerShell module automating standardized directory scaffolding for interface repositories and backup folders during platform upgrades and database migrations.

**Key Features:**
- Automated folder structure generation for repository deliverables
- Backup directory creation for platform upgrades
- Centralized, reusable module replacing one-off scripts

**Tech Stack:** PowerShell  
**Personal Note:** *Built to solve tedious manual directory setup - saves ~15 minutes per deployment*

[📁 View Repository](https://github.com/DebuggingaHopper/NEST) | [📖 Documentation](https://github.com/DebuggingaHopper/NEST/blob/main/README.md)

---

#### **📊 SPOT** - Support Performance & Operations Tracker
> **Status:** ✅ Complete | **Last Updated:** 09/01/2025

C# console application integrating with Airtable REST API to automate weekly helpdesk call log exports, eliminating manual reporting process.

**Key Features:**
- Automated Airtable REST API integration
- Weekly scheduler via Windows Power Automate
- Email delivery to team leads with formatted reports

**Tech Stack:** C# .NET, Airtable REST API, Windows Power Automate  
**Personal Note:** *Reduced weekly reporting time from 30 minutes to automated. Good example of API integration and task automation*

---

#### **🖨️ Printer Queue Manager**
> **Status:** ✅ Complete | **Last Updated:** 11/23/2025

WinForms utility automating printer queue clearing for Zebra label printers in pharmacy compounding workflows, deployed via TeamCity CI/CD pipeline.

**Key Features:**
- One-click printer queue clearing for Zebra printers
- CI/CD pipeline with automated NUnit testing
- MSI installer for easy deployment across sites

**Tech Stack:** C# .NET, WinForms, TeamCity, NUnit  
**Personal Note:** *Simple but effective - common production issue solved with straightforward tool. Good CI/CD practice implementation*

---

### 🎯 Work In Progress

> Projects currently in development (not yet published)

<details>
<summary><b>📝 Blog/Portfolio Site</b></summary>

**Purpose:** Technical blog and portfolio site showcasing projects and documenting solutions to interesting problems

**Tech Stack:** Nest.JS, MDX
**Status:** Planning phase  
**Target Completion:** TBD

**Personal Notes:**
- Will host on GitHub Pages
- Current Posts: Story about the creation of Printer Queue Manager **NOTE: Those blogs need to be updated with refactored code** 
- Content ideas: Interface troubleshooting case studies, PowerShell automation tips, Oracle patching guides

</details>

---

### 📚 Skills & Learning Path

#### **Current Expertise** (What I use daily)
```
Infrastructure:    ████████████████████ 100%  Windows Server, Oracle, AD/LDAP
Integration:       ████████████████████ 100%  HL7, XSLT, Mirth, Epic
Development:       ████████████████░░░░  80%  C# .NET, PowerShell
Security:          ███████████████░░░░░  75%  Vulnerability mgmt, HIPAA compliance
```

#### **Currently Learning**
- 📖 Advanced Oracle performance tuning
- 📖 Kubernetes and containerization (Docker)
- 📖 Powershell for automation scripting
- 📖 C# Solutions to auotmate tasks
- 📖 Azure cloud infrastructure

#### **Want to Learn**
- [ ] Epic Bridges Certification
- [ ] Advanced Mirth Connect administration
- [ ] Infrastructure as Code (Terraform/Ansible)
- [ ] Advanced PowerShell DSC

---

### 📈 Experience Timeline
```
2024-Present  │ Lead System Administrator - Loccioni USA
              │ ├─ Managing 50+ healthcare facility infrastructures
              │ ├─ Sole technical owner for 13+ Epic HL7 integrations
              │ └─ Leading AD/LDAP integration projects
              │
2023-2024     │ System Administrator Intern → Lead (Promoted in 10 months)
              │ ├─ Built bi-directional HL7 interfaces
              │ ├─ Infrastructure deployments (80% of annual implementations)
              │ └─ Initiated vulnerability remediation program
              │
2020-2023     │ B.Sc. Computer Science - Capitol Technology University
              │ └─ GPA: 4.0
```

---

### 🏆 Key Achievements

- 🎯 **Rapid Promotion:** Intern → Lead System Administrator in 10 months
- 🏥 **Scale:** Managing infrastructure/integrations for 50+ healthcare facilities
- 🔧 **Ownership:** Sole technical owner for 13+ custom Epic integrations
- 🚀 **Project Leadership:** Led ARIA-to-Epic migration across multiple hospital implementations
- 🔐 **Security:** Established quarterly vulnerability remediation program
- 📦 **DevOps:** Built centralized Git repository system for American market

---

### 📊 GitHub Activity

![](https://github-readme-streak-stats.herokuapp.com/?user=DebuggingaHopper&theme=dark&hide_border=false)
![DebuggingaHopper's GitHub stats](https://github-readme-stats.vercel.app/api?username=DebuggingaHopper&show_icons=true&theme=dark)

---

### 📫 Connect With Me

<div align="center">

| Platform | Link | Purpose |
|----------|------|---------|
| 💼 **LinkedIn** | [nelson-alvarez](https://www.linkedin.com/in/nelsonjalvarez-dev) | Professional networking |
| 📧 **Email** | njalvarez.dev@gmail.com | Direct contact |
| 📝 **Technical Blog** | *In Development* | Technical writing & tutorials |

</div>

---

### 🗂️ Repository Organization

> **For Future Me:** How this profile is organized

#### **Public Repositories:**
- ✅ **Completed projects** ready for showcase
- ✅ Each has comprehensive README with setup instructions
- ✅ Code is clean, commented, and production-ready

#### **Private Repositories (Gitea):**
- 🔒 **Work-in-progress** projects
- 🔒 **Proprietary** work for Loccioni
- 🔒 **Experimental** code and prototypes

#### **Repository Naming Convention:**
- `tool-name` - Production tools (e.g., `nest`, `spot`, `printer-queue-manager`)
- `project-name` - Personal projects
- `study-topic` - Learning projects/experiments

---

### 💡 Personal Development Notes

> **For Future Me:** Track progress and goals

#### **2024 Goals:**
- [x] Establish GitHub presence with professional README
- [x] Publish 3 completed projects (NEST, SPOT, Printer Queue Manager)
- [ ] Launch technical blog/portfolio site
- [ ] Contribute to open-source healthcare IT projects
- [ ] Write 4 technical blog posts

#### **Project Publishing Checklist:**
Before publishing any project to GitHub, ensure:
- [ ] Code is clean and well-commented
- [ ] Comprehensive README with setup instructions
- [ ] Remove any proprietary/sensitive information
- [ ] Add appropriate license
- [ ] Include screenshots/demo if applicable
- [ ] Test on fresh environment to ensure reproducibility

#### **Blog Post Ideas:**
- "From Intern to Lead: How I Got Promoted in 10 Months"
- "HL7 Integration 101: A Practical Guide to Epic Interfaces"
- "PowerShell Automation for System Administrators"
- "Managing 50+ Production Servers: Lessons Learned"
- "XSLT for Healthcare Integration: Tips and Tricks"
- "Building CI/CD Pipelines for Healthcare Applications"

---

### 📝 Documentation Philosophy

> **Why I document everything:**

- 📚 **Knowledge Retention:** Future me will forget implementation details
- 🤝 **Knowledge Sharing:** Help others facing similar problems
- 💼 **Professional Portfolio:** Demonstrate capabilities to potential employers
- 🔍 **Problem Solving:** Writing forces clarity of thought
- 📈 **Career Growth:** Track progression and learning

---

<div align="center">

**"Document today what you'll need to remember tomorrow."**

Last Updated: [11/29/2025]  
Profile Version: 2.0

</div>
