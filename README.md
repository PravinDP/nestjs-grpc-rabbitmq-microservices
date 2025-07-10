# 🚀 NestJS Microservices Starter (gRPC + RabbitMQ + OpenTelemetry + Saga)

**Production-grade NestJS microservices architecture**, ready for real-world applications.  
Built with best practices for scalability, observability, and resilience.

> 🟣 Looking for the full private repo?  
> 👉 [Sponsor me to unlock it](https://github.com/sponsors/PravinDP)

---

## 🔥 Features

- ✅ Microservices using **NestJS**, **gRPC**, and **RabbitMQ**
- 📦 **Schema-per-service** architecture
- 🔁 **Saga pattern** for distributed workflows
- 🧯 **Circuit Breaker**, Retry, Timeout handling
- 📊 **OpenTelemetry** (Tempo, Loki, Prometheus, Grafana)
- 🐳 Ready for **Docker Compose & Kubernetes (Helm)** deployment
- ⚙️ Built-in **CI/CD** templates (GitHub Actions)
- 🧼 Clean folder structure and modular architecture

---

## 📁 Technologies Used

| Type           | Stack                                      |
|----------------|--------------------------------------------|
| Framework      | [NestJS](https://nestjs.com/)              |
| Messaging      | gRPC, RabbitMQ                             |
| Tracing & Logs | OpenTelemetry, Loki, Tempo                 |
| Monitoring     | Prometheus + Grafana                       |
| Deployment     | Docker Compose, Helm, Kubernetes-ready     |
| CI/CD          | GitHub Actions (staging + production)      |

---

## 📸 Architecture Preview

> High-level architecture and folder structure available in the **private repo**.
```
gateway-service/
└── HTTP entrypoint → gRPC to services
product-service/
└── gRPC microservice with DB
user-service/
└── gRPC + Event-based messaging (RabbitMQ)
charts/
└── Helm charts
docs/
└── SDD, OpenAPI, Postman Collection, ERD, PlantUML
```

## 💎 Who Is This For?

✅ Developers building:
- Scalable microservice-based applications  
- SaaS products, APIs, and B2B services  
- Event-driven or gRPC systems with DevOps focus  

---

## 🔐 Get Full Access (Private Repo)

This is just a **preview**.

By becoming a **GitHub Sponsor**, you unlock the full private repository with:

✅ Clean, battle-tested code  
✅ Real-world observability setup  
✅ Docker + Helm + CI/CD configs  
✅ Ongoing updates & improvements

<p align="center">
  <a href="https://github.com/sponsors/PravinDP">
    <img src="https://img.shields.io/badge/Sponsor%20to%20Access-❤️-ff4081?style=for-the-badge" />
  </a>
</p>

---

## 📬 Questions?

Feel free to reach out:

- 💼 [LinkedIn](https://www.linkedin.com/in/pravin-dabhi-79871322/)
- 📧 pravindabhi311@gmail.com

---

## ⭐ Star This Repo

If this starter inspired you, give it a ⭐️ to help others find it!


---

<p align="center">
  Built with ❤️ by <a href="https://github.com/PravinDP">Pravin Dabhi</a>
</p>
