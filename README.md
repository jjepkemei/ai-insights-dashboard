# AI Insights Dashboard

> A React-based dashboard that integrates OpenAI's GPT-3.5 API to generate real‑time, natural‑language insights from user prompts. Built to demonstrate front‑end AI integration, performance optimization, and clean UI/UX.

![React](https://img.shields.io/badge/React-18.2-61DAFB?logo=react)
![OpenAI](https://img.shields.io/badge/OpenAI-API-412991?logo=openai)
![Tailwind CSS](https://img.shields.io/badge/Tailwind-3.4-06B6D4?logo=tailwindcss)
![Vite](https://img.shields.io/badge/Vite-5.0-646CFF?logo=vite)

## 🚀 Live Demo

[**ai-insights-dashboard.vercel.app**](https://ai-insights-dashboard.vercel.app) (replace with your actual link)

## 📌 Table of Contents

- [Overview](#overview)
- [Why This Project?](#why-this-project)
- [Tech Stack](#tech-stack)
- [Features](#features)
- [Installation & Setup](#installation--setup)
- [Environment Variables](#environment-variables)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Performance Optimizations](#performance-optimizations)
- [Future Improvements](#future-improvements)
- [License](#license)

## Overview

This project demonstrates how to **securely integrate OpenAI's GPT-3.5 API** into a modern React frontend. Users enter a prompt (e.g., "Analyze this sales data: [120, 145, 132]") and receive an AI-generated insight in real time.

It's designed as a portfolio piece for front‑end engineering roles at **AI‑focused companies** like Handshake AI, showcasing skills in:

- API integration (REST, streaming-ready)
- Responsive, accessible UI with Tailwind CSS
- Error handling & loading states
- Performance awareness (lazy loading, code splitting)

## Why This Project?

Handshake AI builds platforms that empower experts to train and evaluate frontier AI models. A key part of that is creating **intuitive, high‑performance internal tools** that leverage LLMs. This project simulates exactly that: a tool where a user (e.g., an annotator or researcher) can query an AI to accelerate their workflow.

By building this, I wanted to demonstrate:

- Ability to work with **LLM APIs** (OpenAI)
- Front‑end architecture for **AI‑powered features**
- Attention to **UX, error resilience, and responsiveness**

## Tech Stack

| Category       | Technologies                                                                 |
|----------------|------------------------------------------------------------------------------|
| Frontend       | React 18, TypeScript (optional), Vite                                        |
| Styling        | Tailwind CSS                                                                 |
| API Integration| OpenAI SDK (`openai`), Fetch API                                             |
| Deployment     | Vercel / Netlify (environment variables for API key)                         |
| Version Control| Git + GitHub                                                                 |

## Features

✅ **Real‑time AI insights** – Send prompts to GPT-3.5 and display responses  
✅ **Loading & error states** – User‑friendly feedback during API calls  
✅ **Responsive design** – Works on desktop, tablet, and mobile  
✅ **Secure API key handling** – Uses `.env` (never committed)  
✅ **Accessible markup** – Semantic HTML, ARIA labels, keyboard navigation  
✅ **Modular component** – Easy to embed into larger dashboards  

## Installation & Setup

### Prerequisites

- Node.js (v18+)
- npm or yarn
- An [OpenAI API key](https://platform.openai.com/api-keys)

### Steps

1. **Clone the repository**

```bash
git clone https://github.com/joanjepkemei/ai-insights-dashboard.git
cd ai-insights-dashboard
