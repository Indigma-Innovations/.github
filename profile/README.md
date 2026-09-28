## Welcome to Indigma on GitHub 👋

At **Indigma**, we build AI systems designed to move beyond prototypes and operate in the real world.

Our work focuses on **Responsible AI, Federated Learning, Edge AI, Generative & Agentic AI, privacy-enhancing technologies, and intelligent software systems**. We combine applied research with production engineering to create technologies that are secure, transparent, efficient, and deployable across cloud, edge, and distributed environments.

For us, Responsible AI is an engineering principle from the start: **privacy, security, transparency, sustainability, and human trust are part of the system architecture**.


### 🚀 About Us
Our work spans several complementary areas:
- **Federated & Distributed AI**: collaborative machine learning across organizations, devices, and edge environments without centralizing raw data.
- **Privacy-Enhancing AI**: secure aggregation, differential privacy, homomorphic encryption, and architectures designed around data sovereignty.
- **Generative & Agentic AI**: intelligent systems that reason, route, coordinate tools and models, and automate complex workflows.
- **Edge AI**: bringing machine learning closer to where data is generated, including resource-constrained and heterogeneous devices.
- **Responsible AI Infrastructure**: systems designed for traceability, explainability, governance, efficiency, and trustworthy deployment.
- **Blockchain & Verifiable System**: decentralized technologies supporting integrity, transparency, and trusted data exchange.
- **Full-Stack AI Applications**: turning research and machine learning components into usable and scalable software products.

### 📁 Repository Organization

This GitHub organization hosts our publicly visible source projects, although the majority of our active development happens across 30 private repositories that are accessible only to our core team.

Together, these repositories power the workflows, services, and research prototypes that embody Indigma’s mission to responsibly innovate in AI and software engineering.

#### 🌐 Open Source at Indigma

We open-source selected technologies, research artifacts, and reference implementations that we believe can help advance practical Responsible AI.

🧠 [SeLMRoute](https://github.com/Indigma-Innovations/SeLMRoute)

**Probabilistic Semantic Evidence for Large Language Model Routing**

SeLMRoute explores a different approach to intelligent model routing: representing the requirements of an incoming task through structured semantic evidence and using that evidence to select among candidate language models. The project investigates semantic routing, model specialization, uncertainty, performance-aware selection, and cost-aware AI orchestration as building blocks for more efficient multi-model AI systems.

⚡ [fl-async-buffered](https://github.com/Indigma-Innovations/fl-async-buffered)*

**Asynchronous Buffered Federated Learning**

A compact reference implementation of asynchronous buffered federated learning built with PyTorch and FastAPI. Clients train independently and submit updates without requiring every participant to remain synchronized. Buffered aggregation and staleness-aware weighting make the architecture suitable for exploring federated learning in heterogeneous and intermittently available edge environments.

🔐 [fl-tas](https://github.com/Indigma-Innovations/fl-tas)*

**Trusted Aggregation Service for Federated Learning**

A standalone aggregation service for privacy-preserving federated learning. TAS supports encrypted model-update workflows with X25519 public-key encryption and optional CKKS Fully Homomorphic Encryption using Microsoft SEAL, allowing federated orchestration and privacy-sensitive aggregation to be separated into independent components.

🍓 [tenseal-rpi-docker](https://github.com/Indigma-Innovations/tenseal-rpi-docker)*

**TenSEAL and CKKS on Raspberry Pi ARM64**

A Docker-based environment for building and running TenSEAL on 64-bit Raspberry Pi devices, including CKKS homomorphic encryption support. The project helps bring privacy-enhancing cryptographic computation to resource-constrained edge hardware, providing a reproducible foundation for testing encrypted AI and federated learning directly at the edge.

🚗 [federated-learning-ev-charging-demand](https://github.com/Indigma-Innovations/federated-learning-ev-charging-demand)

**Federated Learning for Early Prediction of EV Charging Demand**

Companion implementation for our work on privacy-aware EV charging analytics. The project investigates whether the total energy demand of an EV charging session can be predicted from information available at plug-in time and during the first minutes of charging. It compares centralized and federated learning across distributed charging infrastructure and includes multiple model families, reproducible experiments, federated simulations, and resource profiling.

🇪🇺 Research & Funding
Projects marked with * were developed within or in support of ARIEL - federAted oRchestration In Ev fLeets, an initiative selected through [Open Call 1](https://o-cei.eu/indigma/) of the [O-CEI](https://o-cei.eu/) project (Grant Agreement No. [101189589](https://cordis.europa.eu/project/id/101189589)).


### 💬 Connect With Us

Want to learn more about Indigma or collaborate?

Visit our website [https://indigma.eu](https://indigma.eu) where you’ll find:
- Project highlights and case studies
- Insights on responsible AI and technology trends
- Contact info and collaboration opportunities

### 🍿 Fun Facts (Because We're Human)
- Our logo is inspired by our unofficial mascot (and very real pet cat 🐱), Stella, whose face was politely shown to GPT and turned into a logo. Yes, she approves. 🐾
- Many of our projects started as "small experiments" and somehow became production systems.
- Coffee ☕ is technically part of our development infrastructure.
- Some repository names were decided after midnight. We stand by most of them.
- If something looks simple on the outside, there's a good chance it's powered by an unreasonable amount of engineering on the inside.
