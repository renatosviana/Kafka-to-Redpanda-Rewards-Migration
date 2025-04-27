# Kafka to Redpanda Rewards Migration

This project showcases the migration of a Kafka-based streaming system to Redpanda. It simulates a rewards system using Spring Boot, Avro, and Docker.

## Components
- **Producer**: Sends transaction events
- **Consumer**: Processes events and routes them
- **Redpanda**: Local setup via Docker
- **Avro Schemas**: Defines the event structure

## Goal
Demonstrate real-time reward eligibility logic and the transition from Kafka to Redpanda.