# Awesome-Serverless-Event-Bus-Event-Driven-Architecture

# Top Serverless Event Bus & Event-Driven Architecture Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Event Routing, Pub/Sub Messaging & Self-Hosted Event Backbones*  
**Last updated: October 2026**

This repository tracks notable **commercial event bus platforms** and **open-source projects** that enable event-driven architectures — routing events between services, triggering workflows, and decoupling producers from consumers at scale.

**Examples** include Amazon EventBridge, Google Cloud Eventarc, Azure Event Grid, Apache Kafka, Confluent Cloud, Upstash QStash, RabbitMQ Cloud, Inngest, Trigger.dev, and Redpanda Cloud (the category leaders).

**Open-source emphasis**: Event-driven architecture is one of the strongest open-source domains. **Apache Kafka** and **Redpanda** anchor event streaming. **NATS** brings cloud-native messaging, **RabbitMQ** delivers reliable queuing, and **Apache Pulsar** adds multi-tenancy. **CloudEvents** provides the open standard for event interoperability. **Inngest** and **Trigger.dev** open-source their durable function platforms. This section is heavily expanded.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[Amazon EventBridge](https://aws.amazon.com/eventbridge/)**  
  **AWS's serverless event bus** — route events between AWS services, SaaS apps, and custom applications . **Schema registry, event replay, and archive** . **The reference for cloud-native event routing** . **Best for AWS-native event-driven architectures** .

- **[Google Cloud Eventarc](https://cloud.google.com/eventarc)**  
  **Google's event routing service** — standard CloudEvents support with audit logging . **Best for GCP-native event routing** .

- **[Azure Event Grid](https://azure.microsoft.com/en-us/products/event-grid/)**  
  **Microsoft's fully managed event routing** — publish-subscribe with dead-letter queues and filtering . **Best for Azure-native event routing** .

- **[Confluent Cloud](https://www.confluent.io/confluent-cloud/)**  
  **The leading managed Kafka platform** — fully managed Kafka, ksqlDB, Flink, and connectors . **Best for enterprise event streaming** .

- **[Upstash QStash](https://upstash.com/qstash)**  
  **Serverless message queue and scheduler** — HTTP-based with retries and delays . **Best for serverless event-driven workflows** .

- **[RabbitMQ Cloud](https://www.cloudamqp.com/)**  
  **Managed RabbitMQ** — reliable message queuing with AMQP, MQTT, and STOMP . **Best for traditional message queuing** .

- **[Inngest](https://www.inngest.com/)**  
  **Event-driven workflow platform** — durable functions with automatic retries and step functions . **Best for modern event-driven workflows** .

- **[Trigger.dev](https://trigger.dev/)**  
  **Background jobs framework** — event-driven triggers with long-running tasks . **Best for background job orchestration** .

- **[Redpanda Cloud](https://redpanda.com/)**  
  **Kafka-compatible streaming platform** — no Zookeeper or JVM . **Best for high-performance streaming** .

## Open-Source GitHub Projects

### Event Streaming Platforms

- **[Apache Kafka](https://github.com/apache/kafka)**  
  **The de facto standard for event streaming**, Apache-2.0 licensed with **28,000+ GitHub stars** . **Distributed, fault-tolerant, high-throughput pub/sub messaging** . **Kafka Connect for source/sink connectors** and **Kafka Streams for stream processing** . **The foundation for most event-driven architectures** . **Best for enterprise event streaming at scale** .

- **[Redpanda](https://github.com/redpanda-data/redpanda)**  
  **Kafka-compatible streaming platform in C++**, BSL licensed (free for most uses) . **No Zookeeper, no JVM** — simpler operations . **10x faster than Kafka** in some benchmarks . **Best for teams wanting Kafka compatibility with better performance** .

- **[Apache Pulsar](https://github.com/apache/pulsar)**  
  **Distributed messaging and streaming platform**, Apache-2.0 licensed with **14,000+ GitHub stars** . **Multi-tenancy, geo-replication, and tiered storage** . **The main alternative to Kafka** . **Best for multi-tenant and geo-distributed streaming** .

- **[NATS](https://github.com/nats-io/nats-server)**  
  **Cloud-native messaging system**, Apache-2.0 licensed . **Lightweight, high-performance pub/sub** with JetStream for persistence . **The simplest event bus** . **Best for IoT and edge event-driven architectures** .

- **[Apache RocketMQ](https://github.com/apache/rocketmq)**  
  **Distributed messaging and streaming platform**, Apache-2.0 licensed with **20,000+ GitHub stars** . **Low-latency, high-throughput with transactional messages** . **Best for e-commerce and financial services** .

### Message Queuing

- **[RabbitMQ](https://github.com/rabbitmq/rabbitmq-server)**  
  **The most widely deployed open-source message broker**, MPL-2.0 licensed with **12,000+ GitHub stars** . **AMQP, MQTT, STOMP, and WebSocket support** . **Reliable queuing with flexible routing** . **Best for traditional message queuing** .

- **[Apache ActiveMQ](https://github.com/apache/activemq)**  
  **The veteran open-source message broker**, Apache-2.0 licensed . **JMS, AMQP, MQTT, and STOMP** . **Best for Java-centric messaging** .

- **[ZeroMQ](https://github.com/zeromq/libzmq)**  
  **High-performance asynchronous messaging library**, MPL-2.0 licensed . **Embedded networking library** — no broker required . **Best for custom messaging patterns** .

- **[NSQ](https://github.com/nsqio/nsq)**  
  **Real-time distributed messaging platform**, MIT licensed with **12,000+ GitHub stars** . **Simple, reliable, and scalable** . **Best for simple messaging at scale** .

- **[BullMQ](https://github.com/taskforcesh/bullmq)**  
  **Redis-based queue for Node.js**, MIT licensed with **5,000+ GitHub stars** . **Fast, reliable job queuing** . **Best for Node.js background jobs** .

### Event Standards & Routing

- **[CloudEvents](https://github.com/cloudevents/spec)**  
  **The open standard for event interoperability**, Apache-2.0 licensed . **Vendor-neutral event format** — supported by all major cloud providers . **The foundation for portable event-driven architectures** . **Best for interoperable events** .

- **[Knative Eventing](https://github.com/knative/eventing)**  
  **Kubernetes-native event routing**, Apache-2.0 licensed . **Brokers, triggers, and channels** . **Best for Kubernetes event-driven architectures** .

- **[Dapr](https://github.com/dapr/dapr)**  
  **Distributed application runtime**, Apache-2.0 licensed with **23,000+ GitHub stars** . **Pub/sub building block with pluggable brokers** . **Best for microservices event-driven patterns** .

- **[KubeMQ](https://github.com/kubemq-io/kubemq-community)**  
  **Kubernetes-native message broker**, Apache-2.0 licensed . **Lightweight and scalable** . **Best for Kubernetes messaging** .

### Durable Functions & Workflows

- **[Inngest](https://github.com/inngest/inngest)**  
  **Open-source event-driven workflow platform**, Apache-2.0 licensed . **Durable functions with automatic retries and step functions** . **Self-hosted or cloud** . **Best for modern event-driven workflows** .

- **[Trigger.dev](https://github.com/triggerdotdev/trigger.dev)**  
  **Open-source background jobs framework**, Apache-2.0 licensed . **Event-driven triggers with long-running tasks** . **Best for background job orchestration** .

- **[Temporal](https://github.com/temporalio/temporal)**  
  **Durable execution platform**, MIT licensed with **15,000+ GitHub stars** . **Workflows survive crashes and resume from exact failure points** . **Best for mission-critical workflows** .

### Additional Strong Open-Source Options

- **Apache Camel** — Integration framework with 300+ connectors .
- **Debezium** — CDC platform for database events .
- **Apache Flink** — Stateful stream processing .
- **Kafka Streams** — Stream processing library .
- **Apache Beam** — Unified batch and stream processing .
- **Benthos (Redpanda Connect)** — Stream processing without code .
- **Vector** — Observability data pipeline .
- **Watermill** — Go event-driven library .
- **Eventuate** — Event sourcing framework .

**Frameworks for building custom event-driven architectures**: Combine **Apache Kafka** or **Redpanda** for high-throughput event streaming . Use **NATS** for lightweight, cloud-native messaging . Deploy **RabbitMQ** for traditional message queuing . Choose **CloudEvents** for interoperable event formats . Integrate **Inngest** or **Trigger.dev** for durable functions . Use **Temporal** for mission-critical workflows . Note that true serverless event buses with managed infrastructure, global scale, and vendor-supported SLAs (EventBridge, Eventarc, Event Grid) remain primarily commercial territory; open-source stacks provide strong event streaming, messaging, and routing foundations that require integration for complete event-driven architectures.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Event bus platforms handle critical business events and may process sensitive data. Self-hosted solutions require proper security hardening, access controls, and compliance with data privacy regulations.
- **License considerations**: Redpanda uses BSL (free for most uses but not OSI), RabbitMQ uses MPL-2.0, and NATS uses Apache-2.0. Verify licensing against your use case before committing .
- **Exactly-once semantics are hard** — Kafka, Pulsar, and NATS JetStream each handle delivery guarantees differently. Understand your requirements before choosing .
- **Event ordering matters** — Kafka guarantees order per partition; other systems may not. Design for idempotency and handle out-of-order events .
- The open-source ecosystem provides strong event streaming, messaging, and routing foundations, but **managed infrastructure, global scale, and vendor-supported SLAs** remain primarily commercial offerings.

---

**Made for platform engineers, event-driven architects, and organizations seeking event bus sovereignty.**  
Let's make serverless event buses and event-driven architectures more open, transparent, and reliable.
