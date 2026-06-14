<div align="center">

# Hi, I'm Luca 👋

### Computer Science Student @ HdM Stuttgart · Backend & Cloud Engineer

*Deploy now, panic later.*

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/luca-walz)

</div>

I'm a backend and cloud engineer who likes working across the stack, from the APIs and services down to the infrastructure they run on. Lately that has mostly meant Kubernetes, NixOS, and GitOps: a homelab I run entirely from Git and a bachelor thesis on autonomous cluster remediation with LLM agents. Outside of software I tinker with robotics and IoT, usually with the 3D printer running and a hardware project on the bench, a drone being the next one. I read a lot too, a steady mix of systems books and fiction, and I'm always happy to pick up a new tool or language when a project calls for it.

**Languages:** German (native), English (C2)

## What I'm Building

- **[vigil](https://github.com/lucawalz/vigil)** · Python, Go  
  My bachelor thesis: a multi-agent system that diagnoses and repairs faults in a Kubernetes cluster on its own. The LLM agents act through typed MCP tools and are reversible by construction, with Flux GitOps and NixOS generations giving every repair a clean way back.
- **[bedrock](https://github.com/lucawalz/bedrock)** · Nix  
  A bare-metal Kubernetes homelab that lives entirely in Git. Three NixOS nodes run K3s, and Flux reconciles the cluster from the repository instead of by hand.
- **[horizon](https://github.com/lucawalz/horizon)** · Go  
  The active half of the homelab: a controller that watches K3s for resource pressure and bursts onto Hetzner Cloud over a WireGuard overlay, then tears the node down once the spike passes.
- **[sentio-systems](https://github.com/lucawalz/sentio-systems)** · Java, TypeScript, Python  
  A wildlife and weather monitoring platform. Raspberry Pi field devices feed sensor and camera data to a Spring Boot backend, where AI classifies the animals down to the bird species, with a React dashboard and an agentic chatbot to explore it all.

## Tech

<div align="center">
  <img src="https://skillicons.dev/icons?i=go,py,java,ts,spring,react,nix,linux" height="50" alt="languages and runtimes" />
</div>

<div align="center">
  <img src="https://skillicons.dev/icons?i=kubernetes,docker,terraform,postgres,redis,prometheus,grafana,raspberrypi" height="50" alt="infrastructure and data" />
</div>

## GitHub Activity

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/lucawalz/lucawalz/output/pacman-contribution-graph-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/lucawalz/lucawalz/output/pacman-contribution-graph.svg">
  <img alt="pacman contribution graph" src="https://raw.githubusercontent.com/lucawalz/lucawalz/output/pacman-contribution-graph.svg">
</picture>

## Connect

Always happy to talk backend, infrastructure, homelabs, robotics, or whatever you are building. Reach me on [LinkedIn](https://www.linkedin.com/in/luca-walz).
