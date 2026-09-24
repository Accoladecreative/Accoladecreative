<div align="center">

# Kolade Oluwadare

### Senior Backend Engineer · Fintech & Payments

**I build the systems that must not be wrong.**

Payment processing, ledgers, reconciliation. The part nobody sees until it fails.

<br/>

[![Portfolio](https://img.shields.io/badge/Portfolio-koladebuilds.com-1A1A1A?style=for-the-badge&logo=google-chrome&logoColor=white)](https://koladebuilds.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/Oluwadare-Kolade)
[![X](https://img.shields.io/badge/X-@KoladeBuilds-000000?style=for-the-badge&logo=x&logoColor=white)](https://x.com/KoladeBuilds)
[![YouTube](https://img.shields.io/badge/YouTube-@KoladeBuilds-FF0000?style=for-the-badge&logo=youtube&logoColor=white)](https://youtube.com/@KoladeBuilds)
[![Email](https://img.shields.io/badge/Email-Get_in_touch-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:kolade4jesus10@gmail.com)

</div>

---

## About

I'm a backend engineer with 6+ years in fintech, based in Lagos, Nigeria.

Most of my work lives in transaction-critical systems where a duplicate request means someone gets charged twice and a dropped callback means money is stuck in limbo. That shapes how I build: idempotency first, reconciliation always, audit trails on everything, and failure treated as the normal case rather than the exception.

Day to day that means **Kotlin and Java on Spring Boot**, **PostgreSQL** at the depth where locking and isolation levels actually matter, and event-driven services held together with queues, retries and dead-letter handling. I also ship **native Android** and **React Native**, which means I've argued both sides of an API contract more than once.

Currently studying for an **MSc in Financial Engineering** at WorldQuant University, because I want to understand the money as deeply as the systems moving it.

---

## What I'm working on

| Project | What it is | Stack |
|---|---|---|
| **MiniLedger** | Double-entry payment service with derived balances, idempotent endpoints and automated reconciliation | Kotlin · Spring Boot · PostgreSQL |
| **ChaosClient** | Adversarial harness that attacks MiniLedger — request replay, duplicate webhooks, mid-flight connection kills, concurrent double-spend | Kotlin · Testcontainers |
| **koladebuilds.com** | Long-form writing on payment reliability, reconciliation design and production debugging | Next.js · TypeScript |

> Currently in progress — pinned here as they ship.

---

## Tech

**Languages**

![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=flat-square&logo=kotlin&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)

**Backend & APIs**

![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![NestJS](https://img.shields.io/badge/NestJS-E0234E?style=flat-square&logo=nestjs&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![GraphQL](https://img.shields.io/badge/GraphQL-E10098?style=flat-square&logo=graphql&logoColor=white)
![Kafka](https://img.shields.io/badge/Apache_Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white)

**Data**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)

**Platform & Delivery**

![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)

**Mobile**

![Android](https://img.shields.io/badge/Android-3DDC84?style=flat-square&logo=android&logoColor=white)
![Jetpack Compose](https://img.shields.io/badge/Jetpack_Compose-4285F4?style=flat-square&logo=jetpackcompose&logoColor=white)
![React Native](https://img.shields.io/badge/React_Native-61DAFB?style=flat-square&logo=react&logoColor=black)

---

## How I think about backend work

**Correctness beats cleverness.** In payments, the elegant solution that loses a transaction once a month is worse than the boring one that never does.

**Design for the retry.** Every network call will be repeated, delayed or duplicated at some point. If the system only works when each request arrives exactly once, it doesn't work.

**Reconcile, don't assume.** External systems drift from yours. The question isn't whether it happens, it's whether you find out before your customer does.

**Attack your own work.** I write harnesses that replay requests, double-fire webhooks and kill connections mid-flight, so production isn't the first place a flaw shows up.

**Leave the trail.** If you can't reconstruct what happened from the logs and the audit table, you don't have a system — you have a guess.

---

## Writing

I publish on backend engineering, fintech systems and the realities of an engineering career at [koladebuilds.com](https://koladebuilds.com) and across [@KoladeBuilds](https://x.com/KoladeBuilds).

Recent themes: idempotency patterns in payment APIs · reconciliation design · debugging production incidents · building a career from Nigeria into global remote work.

---

<div align="center">

### Currently

Building payment infrastructure · Studying financial engineering · Writing about both

**Open to senior backend roles in fintech and payments — remote or Lagos.**

<br/>

![Profile views](https://komarev.com/ghpvc/?username=Accoladecreative&style=flat-square&color=1A1A1A)

</div>