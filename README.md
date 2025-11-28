# Grouply 🤝

> **Group purchases, share savings**  
> A microservices-based platform enabling Moroccan families to buy together at wholesale prices.

---

## 🎯 Project Vision

**Business Goal:**  
Help Moroccan consumers fight inflation by enabling group purchases directly from producers at wholesale prices.

**Technical Goal:**  
Master enterprise-grade microservices architecture through hands-on implementation.

---

## 🏗️ Architecture

### Microservices

- **User Service** - Authentication & user management (JWT + Keycloak)
- **Deal Service** - Suppliers & deals management
- **Group Service** - Buying groups orchestration
- **Order Service** - Order processing with CQRS/Event Sourcing (Axon Framework)
- **Payment Service** - Payment processing & commissions
- **Workflow Service** - Business process automation (Camunda)
- **Notification Service** - Email/SMS/Push notifications (Kafka Streams)
- **Search Service** - Full-text search (Elasticsearch)
- **Analytics Service** - Real-time analytics (Kafka Streams)
- **Audit Service** - Compliance & audit trail (Elasticsearch)

### Tech Stack

#### Backend
- **Framework:** Spring Boot 3.3.x, Spring Cloud
- **Language:** Java 17
- **Databases:** PostgreSQL, MongoDB, Redis
- **Message Broker:** Apache Kafka + Kafka Streams
- **Event Sourcing:** Axon Framework 4.x
- **Workflow Engine:** Camunda BPM 7.20
- **Search:** Elasticsearch 8.x
- **Auth:** JWT (users) + Keycloak (admins)
- **API Gateway:** Spring Cloud Gateway
- **Service Discovery:** Eureka/Consul

#### Frontend
- **Framework:** Angular 17+ (Standalone Components)
- **State Management:** Signals + RxJS
- **Styling:** Tailwind CSS
- **Real-time:** WebSocket

#### DevOps & Observability
- **Containerization:** Docker & Docker Compose
- **Orchestration:** Kubernetes + Helm
- **CI/CD:** GitLab CI / GitHub Actions
- **Monitoring:** Prometheus + Grafana
- **Logging:** ELK Stack (Elasticsearch, Logstash, Kibana)
- **Tracing:** Jaeger / Zipkin

---

## 🗓️ Development Timeline

**Duration:** 12 weeks (November 2025 - February 2026)

| Phase | Weeks | Focus |
|-------|-------|-------|
| **Foundations** | 1-2 | Architecture, Infrastructure, Learning Camunda/Axon/Kafka Streams |
| **Core Services** | 3-5 | User, Deal, Group, Admin services |
| **Advanced Services** | 6-8 | Order (Axon), Notification (Kafka Streams), Workflow (Camunda) |
| **Completion** | 9-10 | Payment, Analytics, Audit, Frontend Angular |
| **Production Ready** | 11-12 | CI/CD, K8s, Monitoring, Load testing |

---



## 🎓 Learning Objectives

This project is designed to master:

- ✅ **Microservices Architecture** - Service decomposition, API Gateway, Service Discovery
- ✅ **Event-Driven Architecture** - Kafka, Event Sourcing, CQRS
- ✅ **CQRS & Event Sourcing** - Axon Framework
- ✅ **Stream Processing** - Kafka Streams for real-time analytics
- ✅ **Business Process Management** - Camunda workflows
- ✅ **Modern Authentication** - JWT + OAuth2/OIDC with Keycloak
- ✅ **Full Observability** - Prometheus, Grafana, ELK Stack
- ✅ **DevOps Practices** - CI/CD, Kubernetes, Infrastructure as Code
- ✅ **Modern Frontend** - Angular 17+ with Signals

---


## 🤝 Contributing

This is a personal learning project, but feedback and suggestions are always welcome!

Feel free to:
- ⭐ Star the project if you find it interesting
- 🐛 Report bugs or issues
- 💡 Suggest improvements
- 📖 Learn from the code and architecture

---

## 👨‍💻 Author

**Abdelhay LASSERI**

- LinkedIn: [https://www.linkedin.com/in/abdelhay-lasseri-b86b12265/]
- Email: [lasseriabdelhay@gmail.com]
- GitHub: [https://github.com/abdelhay82]

---

## 🌟 Acknowledgments

This project is part of a 12-week intensive learning journey to master enterprise-grade backend technologies and microservices architecture.
