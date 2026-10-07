# Awesome-Managed-API-Gateway

# Top Managed API Gateway Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Managed API Gateways, Self-Hosted Proxies & Open-Source API Management*  
**Last updated: October 2026**

This repository tracks notable **commercial managed API gateway platforms** and **open-source projects** that route, secure, monitor, and monetize API traffic — from fully managed cloud gateways to self-hosted proxies, service meshes, and API management platforms.

**Examples** include Amazon API Gateway, Kong Konnect, Apigee, Tyk Cloud, Gravitee.io, MuleSoft Anypoint, Azure API Management, Traefik Hub, Postman, and Zuplo (the category leaders).

**Open-source emphasis**: Managed API gateways are anchored by **Kong Gateway** as the most widely adopted open-source API gateway, with **Apache APISIX**, **Traefik**, **Envoy Gateway**, and **Tyk** providing high-performance alternatives. **Gravitee**, **KrakenD**, and **WSO2** deliver full API management platforms, while **Kong Mesh** and **Istio** extend gateway capabilities into service mesh territory. **Apache ShenYu** and **Easegress** bring additional open-source options for microservices and cloud-native environments. This section is heavily expanded.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[Amazon API Gateway](https://aws.amazon.com/api-gateway/)**  
  **AWS's fully managed API gateway** — REST, HTTP, WebSocket, and GraphQL APIs with automatic scaling . **Usage plans, API keys, throttling, and AWS IAM authorization** . **Native integration with Lambda, ECS, and AWS services** . **Best for AWS-native API workloads** .

- **[Kong Konnect](https://konghq.com/products/kong-konnect)**  
  **The managed control plane for Kong Gateway** — unified management across hybrid and multi-cloud deployments . **Service catalog, developer portal, and AI Gateway capabilities** . **Runs on Kong Gateway OSS with enterprise plugins** . **Best for Kong users wanting managed control plane** .

- **[Apigee](https://cloud.google.com/apigee)**  
  **Google's enterprise API management platform** — full lifecycle management with analytics and monetization . **Best for large enterprises with complex API programs** .

- **[Tyk Cloud](https://tyk.io/cloud/)**  
  **Managed Tyk API gateway** — dashboard, developer portal, and analytics . **Supports REST, GraphQL, TCP, and UDP** . **Best for Tyk users wanting managed service** .

- **[Gravitee.io](https://www.gravitee.io/)**  
  **Open-source API management with managed cloud option** — event-native gateway with Kafka, MQTT, and WebSocket support . **Best for event-driven API management** .

- **[MuleSoft Anypoint](https://www.mulesoft.com/)**  
  **Salesforce's integration and API management platform** — API-led connectivity with Anypoint Exchange . **Best for enterprise integration** .

- **[Azure API Management](https://azure.microsoft.com/en-us/products/api-management/)**  
  **Microsoft's managed API gateway** — full lifecycle API management with developer portal . **Best for Azure-native API workloads** .

- **[Traefik Hub](https://traefik.io/traefik-hub/)**  
  **Managed Traefik platform** — cloud-native API management and ingress . **Best for Kubernetes-native API management** .

- **[Postman](https://www.postman.com/)**  
  **API platform with gateway capabilities** — API client, documentation, testing, and monitoring . **Postman API Gateway** provides API management capabilities . **Best for API development workflows** .

- **[Zuplo](https://zuplo.com/)**  
  **Serverless API gateway** — edge-deployed with built-in API key management and rate limiting . **Best for modern API development** .

## Open-Source GitHub Projects

### API Gateways

- **[Kong Gateway (OSS)](https://github.com/Kong/kong)**  
  **The most widely adopted open-source API gateway**, Apache-2.0 licensed with **40,000+ GitHub stars** . **Built on NGINX with LuaJIT for high performance** . **Plugin ecosystem with 100+ plugins for authentication, rate limiting, and transformations** . **Runs on any infrastructure with declarative configuration** . **The foundation for Kong Konnect** . **Best for API gateway with plugin extensibility** .

- **[Apache APISIX](https://github.com/apache/apisix)**  
  **High-performance API gateway**, Apache-2.0 licensed with **15,000+ GitHub stars** . **Dynamic routing with etcd-backed configuration** . **Rich plugin ecosystem with 100+ plugins** . **Supports HTTP, gRPC, WebSocket, and MQTT** . **Best for high-performance API gateway** .

- **[Traefik](https://github.com/traefik/traefik)**  
  **Cloud-native application proxy**, MIT licensed with **50,000+ GitHub stars** . **Automatic service discovery with Kubernetes, Docker, and Consul** . **Ingress, reverse proxy, and API gateway capabilities** . **Built-in Let's Encrypt and middleware support** . **Best for Kubernetes ingress and API gateway** .

- **[Envoy Gateway](https://github.com/envoyproxy/gateway)**  
  **Kubernetes-native gateway**, Apache-2.0 licensed with **2,000+ GitHub stars** . **Gateway API implementation based on Envoy** . **Supports HTTP, TCP, TLS, and gRPC** . **Best for Kubernetes Gateway API** .

- **[Tyk Gateway](https://github.com/TykTechnologies/tyk)**  
  **Open-source API gateway**, MPL-2.0 licensed with **10,000+ GitHub stars** . **Supports REST, GraphQL, TCP, and UDP** . **Analytics, rate limiting, and authentication middleware** . **Best for API management with analytics** .

- **[KrakenD](https://github.com/krakend/krakend-ce)**  
  **Ultra-fast API gateway**, Apache-2.0 licensed with **7,000+ GitHub stars** . **API composition and aggregation** . **Stateless and horizontally scalable** . **Best for API composition** .

- **[Apache ShenYu](https://github.com/apache/shenyu)**  
  **Java-native API gateway for microservices**, Apache-2.0 licensed with **8,000+ GitHub stars** . **Supports HTTP, Dubbo, Spring Cloud, gRPC, and more** . **Rich plugin ecosystem** . **Best for Java microservices gateway** .

- **[Easegress](https://github.com/megaease/easegress)**  
  **Cloud-native traffic orchestration system**, Apache-2.0 licensed with **6,000+ GitHub stars** . **API gateway, service mesh, and traffic orchestration** . **Best for cloud-native traffic orchestration** .

### API Management Platforms

- **[Gravitee.io (Community Edition)](https://github.com/gravitee-io/gravitee-api-management)**  
  **Event-native API management platform**, Apache-2.0 licensed with **5,000+ GitHub stars** . **Supports REST, GraphQL, Kafka, MQTT, and WebSocket** . **Developer portal, analytics, and policy enforcement** . **Best for event-driven API management** .

- **[WSO2 API Manager](https://github.com/wso2/product-apim)**  
  **Enterprise-grade open-source API management**, Apache-2.0 licensed . **Full lifecycle with publisher, developer portal, and gateway** . **Best for enterprise API management** .

- **[Kong Mesh](https://github.com/kumahq/kuma)** — Enterprise service mesh with API gateway capabilities .

- **[Gladys](https://github.com/gladysassistant/Gladys)** — Open-source API gateway for smart home (different domain) .

### Service Mesh as Gateway

- **[Istio](https://github.com/istio/istio)**  
  **The most feature-rich service mesh**, Apache-2.0 licensed with **36,000+ GitHub stars** . **Traffic management, mTLS, and observability** . **Istio Ingress Gateway provides API gateway capabilities** . **Best for enterprise service mesh** .

- **[Linkerd](https://github.com/linkerd/linkerd2)**  
  **The most performant service mesh**, Apache-2.0 licensed with **10,000+ GitHub stars** . **Rust-based micro-proxy** . **Best for simple service mesh** .

- **[Cilium](https://github.com/cilium/cilium)**  
  **eBPF-based service mesh**, Apache-2.0 licensed with **20,000+ GitHub stars** . **Sidecarless architecture** . **Best for Kubernetes-native networking** .

- **[Kuma](https://github.com/kumahq/kuma)**  
  **Universal service mesh**, Apache-2.0 licensed with **3,500+ GitHub stars** . **Multi-cluster, multi-cloud, and multi-platform** . **Best for universal service mesh** .

### Additional Strong Open-Source Options

- **Nginx** — The foundational web server and reverse proxy .
- **HAProxy** — High-performance load balancer .
- **Caddy** — Modern web server with automatic HTTPS .
- **OpenResty** — Nginx + LuaJIT for custom API gateways .
- **Zuul** — Netflix's API gateway (now maintained) .
- **Spring Cloud Gateway** — Spring Boot API gateway .
- **Ocelot** — .NET API gateway .
- **YARP** — Microsoft's reverse proxy .
- **Kong Ingress Controller** — Kubernetes ingress for Kong .

**Frameworks for building custom managed API gateway solutions**: Combine **Kong Gateway** or **Apache APISIX** for production-grade API gateways with plugin extensibility . Use **Traefik** or **Envoy Gateway** for Kubernetes-native ingress and Gateway API . Deploy **Gravitee** or **WSO2** for full API management platforms . Choose **Tyk** or **KrakenD** for specialized gateway needs . Integrate **Istio** or **Kuma** for service mesh capabilities . Note that true managed API gateways with global infrastructure, automatic scaling, and vendor-supported SLAs (Amazon API Gateway, Kong Konnect, Apigee) remain primarily commercial territory; open-source stacks provide strong routing, security, and management foundations that require integration for complete API gateway deployments.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- API gateways handle sensitive API traffic and authentication. Self-hosted solutions require proper security hardening, access controls, and compliance with data privacy regulations.
- **Gateway choice depends on protocol needs** — REST, GraphQL, gRPC, WebSocket, Kafka, and MQTT have different gateway requirements. Choose based on your API types .
- **Performance varies significantly** — APISIX and KrakenD are optimized for high throughput; Kong and Tyk balance features with performance. Benchmark against your workload .
- **License considerations**: Kong uses Apache-2.0, APISIX uses Apache-2.0, Traefik uses MIT, Tyk uses MPL-2.0, and Envoy Gateway uses Apache-2.0. Verify licensing against your use case before committing .
- The open-source ecosystem provides strong routing, security, and management foundations, but **global infrastructure, automatic scaling, and vendor-supported SLAs** remain primarily commercial offerings.

---

**Made for API engineers, platform teams, and organizations seeking API gateway sovereignty.**  
Let's make managed API gateways more open, transparent, and performant.
