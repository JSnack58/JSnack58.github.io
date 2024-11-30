# Anthony Frank
### Email: amclarenfrank@gmail.com
### [LinkedIn](https://www.linkedin.com/in/anthony-f-396056126?lipi=urn%3Ali%3Apage%3Ad_flagship3_profile_view_base_contact_details%3B5bk8ObDEQEGtd5p4WL6tIw%3D%3D)

# About Me

I'm a Masters student at San Jose State University studying Artificial Intelligence and Data Science. I previously was Computer Science student at UC Santa Cruz where I built a website for Researchers, trained AI Agents, and interned at NVIDIA AI for Gaming Team. After earning my Bachelor's I worked at Google as a Cloud Software Engineer and later moved toward FullStack Software Engineering and AI.

## Education

### San Jose State University| M.S Artificial Intelligence 27'

### University of California Santa Cruz| B.S Computer Science 22'

## Skills

| Languages | Frameworks/Libraries | Backend/DB | DevOps | AI/ML |
|---|---|---|---|---|
| Python | TensorFlow | Postgres | Docker | TensorFlow |
| Java | PyTorch | MongoDB | Kubernetes | PyTorch |
| TypeScript | Django | ProtoBufs | GKE | Numpy |
| JavaScript | Flask | SQLAlchemy | Linode | Pandas |
| HTML | NumPy |  | APISIX | ChromaDB |
| CSS | Pandas |  | KeyCloak | SciKit-learn |
| C | Scikit-learn |  | Ansible | Apache-Spark |
| C++ | NodeJS |  | Terraform | LangChain |
| YAML | React |  |  | LangGraph |
| SQL | NextJS |  |  | QLoRa |
|  | ExpressJS |  |  | LLMs |
|  | SpringBoot |  |  |  |

## Work Experience
### Contract FullStack Software Engineer Weir(Oct 2024 - Nov 2024)
A starup needed a live prototype website to show to for their product within a month for CES. I worked with the Weir's CEO to form the users stories for website's design with API-first approach. For my tech stack used I used React as its Frontend, built the API with Flask, and stored user/business data in the MongoDB. Once built deployed the website on a Linode cluster I created using Terraform, and managed the cluster's environment with Ansible.

### Contract FullStack Software Engineer My12Inch.com(July 2023 - Jan 2024)
I modernized an outdated internal webpage, transitioning from a legacy Flex (Flash-based) system to a robust and efficient stack comprising ReactJS, Flask, and PostgreSQL. This overhaul significantly enhanced the user experience and performance. 

Furthermore, I developed a cutting-edge music streaming service API using Spring Boot. By leveraging JPA's powerful architecture, I surpassed the computational capabilities of ExpressJS in handling complex business logic. This optimized API ensures seamless and scalable music streaming.

I spun up GKE cluster with APISIX Gateway with keycloak OAUTH2.0 security that housed our MongoDB instance and Microservices. I monitored the cluster with K9s and ran test on services using Postman.

To make the cluster more accessible on the internet I wrote the APISIX route so a user would only need to use the type out the site name rather than the IP address which also add more consistency and security to the site.


### Cloud Software Engineer Google(August 2022 - July 2023)
On Google's Borg team, I created scalable, sustainable, and flexible solutions for Google Cloud users worldwide. Different users have different needs(hardware, software, etc.) when they want to use our cloud, when ever new technologies need to be implemented I wrote solutions(C++ and Google Protobufs) for the new implementation.

Additionally, part of my job was Testing & Monitoring the cloud. I wrote the monitoring software that would retrieve and chart data(health, modes, etc.) from the machines within cloud. If anything was out of the ordinary alerts that I wrote would trigger to give warn team of potential problems long before things go wrong.

I also improved Google Borg Prime's legacy-code to improve to the Cloud's efficiency. Google was a great experience as my first job straight out of college. A head-first dive into Corporate Software, tackling tough problems while collaborating with many teams, pushing code with CI/CD, Testing new implementations for customers all within tight deadlines.

### FullStack Engineer UCSC(Sept 2021 - Dec 2021)
I developed a website for UCSC's researchers and the National Ocean and Atmosphere Admistration. The Researchers wanted a site that displays their datasets to make them easily accesible to the public. I created a typescript written site in NextJS that creates Cards to represent a dataset as a synopsis for the user to click on for more details. I wrote an API to access the MongoDB to perform CRUD on the datasets. I wrote the Frontend to call this API to retrieve metadata of each dataset to construct a card and had it organize the cards in a grid.


### Software Engineer NVIDIA(June 2021 - Sept 2021)
I interned at NVIDIA's AI for Gaming team where I build an Electron-based desktop application for image & video comparison from the ground up. The applicaiton was crucial to NVIDIA's marketing strategy for current and future feature. I closely worked with th PM and UCD Experts to define the application's UX design, and developed the paplication with minimal supervision in a distributed team under tight market pressures.


## Projects

### [Fine-tuning LLM for Medical Definitions(March 2024)](https://github.com/JSnack58/Fine-tuning-LLMs/tree/main)
 Used QLoRA to fine-tune a local model with a medical definition dataset to explain medial terms.

### [Web browsing LLM Agents - WebVoyager(February 2024)](https://github.com/JSnack58/WebVoyager.git)
   Created an AI agent that autonomously navigates the web using LangChain, LangGraph, and Python Playwright. Designed its behavior using State Graphs and Prompt Engineering. Compared various LLMs, [published findings](https://docs.google.com/document/d/1UYHTq_1CeGcV1_RV0zBpgJIo_8zoc-VeL-pVUWEO7vc/edit?usp=sharing), and open-sourced the code.

### [Trained Neural Net from Kubernetes Cluster- Names Generator(August 2023)](https://github.com/JSnack58/mongodb-trained-transformer)
I developed a Python script that leverages PyTorch to construct and train an Artificial Neural Network (ANN). The script dynamically fetches training data from a MongoDB instance, seamlessly integrated within a Kubernetes cluster. This project provided invaluable hands-on experience with Kubernetes, Docker, Ingress Controllers, and the intricacies of neural network architectures. By successfully orchestrating these technologies, I gained a deep understanding of modern data engineering and machine learning pipelines.
