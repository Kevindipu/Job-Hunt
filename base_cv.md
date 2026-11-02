# Kevin Thomas Dipu

kevindipu17@gmail.com | LinkedIn | GitHub | Germany | Student residence permit (§ 16b) | Available immediately

## EDUCATION

- **Master of Science in Data Analytics**, *Universität Hildesheim*  
  04/2026 – 04/2028 | Hildesheim
- **B.E in Computer Science and Engineering**, *JSS Science and Technology University*  
  12/2020 – 06/2024 | German grade equivalent - 1.7 | India

## PROFESSIONAL EXPERIENCE

### IT Engineer, *Qualcomm*  
07/2024 – 03/2026 | Bengaluru, India

- Took ownership of QPI tool development, adding 4 commands and optimizing 7 existing commands in a 30+ command Python CLI; introduced Git branching workflows for feature development and hotfixes.
- Supported QPI adoption across 4 engineering teams; cut developer workspace setup from 60 to 15 minutes.
- Replaced manual IP management reporting with a daily Python pipeline covering 15 active development IPs, integrating MongoDB and Splunk dashboards to save 8+ hours of manual effort weekly.
- Built a Python-based CMDB monitoring solution across 500+ servers, automating infrastructure validation and owner notifications through Splunk dashboards; improved data accuracy by 15% compared with the previous baseline.

### Interim Engineering Intern, *Qualcomm*  
01/2024 – 07/2024 | Bengaluru, India

- Built a Python reporting pipeline and MongoDB-backed dashboard for 100+ chip IP records, replacing recurring manual reporting with automated reporting.
- Developed Python-based license monitoring across 50+ users and 4 environments, identifying inactive accounts and enabling reclamation of 20% of software license capacity through an approval workflow.

## SKILLS

| Programming | Cloud & Infrastructure | Containers & CI/CD |
| --- | --- | --- |
| Python, SQL, Bash, C++ | AWS, Terraform, Docker, Linux | Kubernetes, KServe, GitHub Actions, Git |

| Data & Monitoring | ML & AI | Tools |
| --- | --- | --- |
| PostgreSQL, MongoDB, Splunk, Data Pipelines | PyTorch, TensorFlow, Scikit-learn, BERT, NLP, Computer Vision | Jira, ServiceNow, Confluence |

## LANGUAGES

- **English:** C1
- **German:** A2

## PROJECTS

### URL Shortener on AWS | GitHub
*Tech Stack: Python, FastAPI, Docker, Terraform, GitHub Actions, AWS*

- Provisioned a two-AZ AWS infrastructure using Terraform, automating VPC networking, EC2, Application Load Balancer, RDS PostgreSQL, ECR, IAM and CloudWatch resources.
- Automated Docker image builds and deployment through GitHub Actions and Amazon ECR, updating two EC2 instances and verifying application health after deployment.
- Deployed two EC2 instances across separate Availability Zones behind an Application Load Balancer, using RDS PostgreSQL for shared storage; tested instance failure and verified traffic failover.

### Churn Prediction MLOps Pipeline | GitHub
*Tech Stack: Python, Scikit-learn, FastAPI, Kubernetes, KServe, AWS S3, DVC*

- Trained a Random Forest churn classifier and deployed the same serialized model artifact through FastAPI and KServe, demonstrating both standalone API serving and Kubernetes-native inference.
- Integrated KServe with AWS S3 using Kubernetes Service Account and IAM permissions to retrieve model artifacts; configured Horizontal Pod Autoscaling (HPA) for inference workloads.
- Implemented dataset versioning with DVC and an S3 remote, tracking dataset metadata in Git; used uv for dependency management and reproducible environment setup.

### Multimodal Deepfake Content Detection | GitHub
*Tech Stack: Python, Flask, BERT, VGG19, VGGish, NLP, Computer Vision*

- Fine-tuned BERT and implemented lexical feature extraction using MAAS and Yule's K for text-based deepfake detection, achieving 84.3% test accuracy.
- Developed Flask REST API endpoints integrating independently developed text, image and audio detection models, implementing file validation and standardized prediction responses within a four-member team.
- Integrated the three detection capabilities into a unified framework, with teammate-developed image and audio models achieving 93.7% and 95.1% test accuracy, respectively.
