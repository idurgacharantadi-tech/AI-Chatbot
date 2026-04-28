# 🤖 AI Chatbot

> A full-stack AI chatbot powered by Amazon Bedrock (Claude), Spring Boot, Angular, and AWS serverless architecture.

---

## 🌐 Overview

**AI Chatbot** is a conversational AI web application that enables users to interact with an intelligent assistant in real-time.

The chatbot can:

- 💬 Answer questions
- 🧠 Generate intelligent responses
- 📚 Understand conversational context
- ⚡ Provide fast, AI-powered replies

This project demonstrates how to build a **production-style AI chatbot using AWS Bedrock + Java backend + Angular frontend + serverless deployment**.

---

## 🚀 Features

- ✅ Real-time conversational UI
- ✅ AI-powered responses using Claude (Amazon Bedrock)
- ✅ Clean chat interface
- ✅ Scalable serverless backend
- ✅ REST API integration
- ✅ Extensible for knowledge base / RAG use cases
- ✅ Modular architecture for future enhancements

---

## 🧰 Tech Stack

| Technology | Purpose |
|----------|---------|
| 🅰️ **Angular** | Frontend chat UI |
| ☕ **Java** | Backend logic |
| 🌱 **Spring Boot** | REST API layer |
| 🤖 **Claude (Amazon Bedrock)** | AI response generation |
| ⚡ **AWS Lambda** | Serverless backend |
| 🌐 **API Gateway** | API exposure |
| 🪣 **Amazon S3** | Frontend hosting |
| 🚀 **CloudFront** | CDN distribution |
| 🔐 **IAM** | Secure AWS access |

---

## 🏗️ Architecture

```text
User
 │
 ▼
Angular Chat UI
 │
 ▼
API Gateway
 │
 ▼
AWS Lambda
 │
 ▼
Spring Boot Backend
 │
 ▼
Amazon Bedrock (Claude)
 │
 ▼
AI Response → User
