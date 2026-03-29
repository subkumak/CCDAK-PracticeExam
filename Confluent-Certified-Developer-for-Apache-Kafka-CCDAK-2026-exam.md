# Confluent Certified Developer for Apache Kafka (CCDAK) – 2026 Exam Guide

## 🎯 1. Understand the Exam First

- ⏱ **Duration**: ~90 minutes
- ❓ **Questions**: ~60 (MCQ + scenario-based)
- ✅ **Passing score**: ~70–75%

### 👉 The exam validates your ability to:

- Build Kafka producers & consumers
- Design event-driven systems
- Work with real-time streaming pipelines

## 📚 2. Core Syllabus (What to Study)

Focus on these 7 key domains:

### 1. Kafka Core Concepts
- Topics, partitions, offsets
- Brokers, leaders, replication
- Retention, log segments

### 2. Producers (Very Important 🔥)
- Acks, retries, batching
- Partitioning (key-based hashing)
- Idempotent producer

### 3. Consumers & Consumer Groups
- Offset management
- Rebalancing
- Auto vs manual commit

### 4. Delivery Semantics
- At-most-once
- At-least-once
- Exactly-once

### 5. Serialization & Schema
- Avro / JSON / Protobuf
- Schema Registry
- Compatibility (backward, forward, full)

### 6. Kafka Streams
- Stateless vs stateful processing
- Windowing, joins
- Real-time transformations

### 7. Ecosystem + Security
- Kafka Connect
- ACLs, authentication
- Basic troubleshooting

## 🧠 3. Best Study Resources (Official + Practical)

### ✅ Must-do (Official)

**Confluent Developer courses:**
- Kafka 101
- Kafka Streams 101
- Schema Registry 101
- Kafka Connect 101

### ✅ Hands-on Practice (Critical)

Set up Kafka locally or use Confluent Cloud:

- Create topics
- Write producer/consumer (Java/Python)
- Play with partitions & offsets
- Break things and debug

> 👉 **Real insight from developers:**
> 
> "Hands-on practice helps way more than just reading."

### ✅ Practice Tests (Game changer)

- Solve 200–300 questions minimum
- Focus on scenario-based questions
- Helps with time management & pattern recognition

**Practice exams typically cover:**
- Producers/Consumers
- Streams API
- Schema evolution
- Performance tuning

## ⚙️ 4. 4-Week Study Plan (Recommended)

### Week 1 – Fundamentals
- Kafka architecture
- Topics, partitions, offsets
- CLI commands

### Week 2 – Core Development
- Producers + configs
- Consumers + groups
- Delivery semantics

### Week 3 – Advanced Topics
- Kafka Streams
- Schema Registry
- Kafka Connect

### Week 4 – Practice & Revision
- Full mock exams (3–5)
- Focus on weak areas
- Revise configs & edge cases

## ⚠️ 5. Important Exam Tips

### 🔥 Focus Areas (High weight)
- Producer configs (acks, retries, batching)
- Consumer group behavior
- Partitioning logic
- Delivery guarantees

### 🧩 Scenario-Based Thinking

Questions are like:

**"Producer sending with key → which partition?"**

👉 **Answer**: Key-based hashing (default partitioner)

### ⚡ Common Mistakes to Avoid
- Ignoring configs (very important in exam)
- Skipping Streams API
- Not practicing offset/rebalance scenarios

## 🧪 6. Last Week Revision Checklist

- ✔ Producer configs (acks, linger.ms, batch.size)
- ✔ Consumer configs (group.id, auto.offset.reset)
- ✔ Delivery semantics
- ✔ Schema compatibility types
- ✔ Kafka Streams basics
- ✔ Partitioning logic

## 🚀 7. Final Strategy

- Don't rely only on theory
- Practice real scenarios + mock exams
- Think like a Kafka developer (not just memorize)

### ✅ Golden Rule:

If you can confidently explain:

- "How Kafka guarantees delivery"
- "How consumers rebalance"
- "How partitioning works"

👉 **You're ready to pass.**