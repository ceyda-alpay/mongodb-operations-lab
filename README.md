# MongoDB Operations Lab

Hands-on experiments exploring MongoDB administration, performance, data retention, and operational reliability.

## Overview

This repository contains reproducible MongoDB administration labs designed to investigate database behavior, operational trade-offs, and common maintenance challenges.

Each lab includes the problem being investigated, the test environment, implementation details, observations, and lessons learned.

## Labs

### 1. TTL Index vs. Manual Batch Deletion

An experiment comparing MongoDB's automatic TTL expiration mechanism with controlled manual batch deletion.

**Objectives:**
- Understand how MongoDB TTL indexes work.
- Implement controlled batch deletion.
- Measure deletion throughput and execution time.
- Observe the impact on database resources and replication.
- Identify operational trade-offs between the two approaches.

**Status:** In progress

## Technologies

- MongoDB
- JavaScript (mongosh)
- Linux

## Methodology

Experiments use synthetic datasets in isolated lab environments.

Results will be documented alongside the test configuration, measurement methods, and limitations to support reproducibility.

## Disclaimer

This repository is intended for educational and experimental purposes. All examples use synthetic data and are independent of proprietary production environments.
