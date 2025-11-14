<div align="center">

<!-- Metallic Grey Gradient Header -->
<picture>
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:1a1a2e,50:2d2d3d,100:4a4a5a&height=200&section=header&text=SIGYL&fontSize=60&fontColor=e8e8ee&animation=fadeIn&fontAlignY=35&desc=Building%20an%20Intelligent%20Crypto%20AI%20Layer&descAlignY=55&descSize=20" alt="SIGYL AI Header" width="100%">
</picture>

<br/>

<!-- Tech Stack Badges -->
### Core Languages & Frameworks
![Rust](https://img.shields.io/badge/Rust-Core_Engine-2d2d3d?style=flat-square&logo=rust&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-Services-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Python](https://img.shields.io/badge/Python-Analytics-3776AB?style=flat-square&logo=python&logoColor=white)
![React](https://img.shields.io/badge/React-Frontend-61DAFB?style=flat-square&logo=react&logoColor=black)
![Node.js](https://img.shields.io/badge/Node.js-Runtime-339933?style=flat-square&logo=node.js&logoColor=white)

### AI & LLM Infrastructure
![OpenAI](https://img.shields.io/badge/OpenAI-GPT_Models-412991?style=flat-square&logo=openai&logoColor=white)
![Anthropic](https://img.shields.io/badge/Anthropic-Claude-191919?style=flat-square&logo=anthropic&logoColor=white)
![OpenRouter](https://img.shields.io/badge/OpenRouter-Multi_Provider-6366F1?style=flat-square)

### Databases & Storage
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-Relational-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Qdrant](https://img.shields.io/badge/Qdrant-Vector_DB-DC244C?style=flat-square)
![Redis](https://img.shields.io/badge/Redis-Cache-DC382D?style=flat-square&logo=redis&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-Backend-3ECF8E?style=flat-square&logo=supabase&logoColor=white)

### Rust Stack
![Tokio](https://img.shields.io/badge/Tokio-Async_Runtime-2d2d3d?style=flat-square)
![Axum](https://img.shields.io/badge/Axum-Web_Framework-2d2d3d?style=flat-square)
![SQLx](https://img.shields.io/badge/SQLx-Database-2d2d3d?style=flat-square)
![Serde](https://img.shields.io/badge/Serde-Serialization-2d2d3d?style=flat-square)
![Tracing](https://img.shields.io/badge/Tracing-Observability-2d2d3d?style=flat-square)

### TypeScript/JavaScript Stack
![Fastify](https://img.shields.io/badge/Fastify-API_Server-000000?style=flat-square&logo=fastify&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/TailwindCSS-Styling-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-Build_Tool-646CFF?style=flat-square&logo=vite&logoColor=white)

### Python Stack
![FastAPI](https://img.shields.io/badge/FastAPI-API_Framework-009688?style=flat-square&logo=fastapi&logoColor=white)
![Aiohttp](https://img.shields.io/badge/Aiohttp-Async_HTTP-2C5BB4?style=flat-square)
![NumPy](https://img.shields.io/badge/NumPy-Computation-013243?style=flat-square&logo=numpy&logoColor=white)

### Infrastructure
![Railway](https://img.shields.io/badge/Railway-Deployment-0B0D0E?style=flat-square&logo=railway&logoColor=white)
![WebSocket](https://img.shields.io/badge/WebSocket-Real_Time-010101?style=flat-square)
![Docker](https://img.shields.io/badge/Docker-Containerization-2496ED?style=flat-square&logo=docker&logoColor=white)

### Status
![Status](https://img.shields.io/badge/Status-Beta-4a4a5a?style=flat-square)
![Architecture](https://img.shields.io/badge/Architecture-Production_Ready-00C853?style=flat-square)

</div>

---

## Meet Sigyl


**Sigyl is a Crypto AI layer** that understands your questions about blockchains, market data, and social signals. Using advanced multi-stage language model pipelines, it can *analyze*, *track*, and *explain* complex crypto market dynamics in real-time.

Behind the scenes, Sigyl is powered by a **high-performance multi-language stack**—Rust for the core engine, TypeScript for real-time services, and Python for specialized analytics. Our intelligent pipeline understands intent, retrieves cross-conversation context from hybrid memory systems, and coordinates **100+ specialized blockchain tools**, delivering insights with streaming responses.

---

## Query Processing & Streaming Pipeline

<div align="center">

```mermaid
flowchart TD
    A[User Query] -->|WebSocket/SSE| B{Intent Analyzer}
    B -->|Contextual Analysis| C[Memory Retrieval]
    C -->|Cross-conversation Context| D{Planning Engine}

    D -->|Execution Plan| E[Tool Orchestrator]
    E -->|Parallel Execution| F1[Blockchain Tools]
    E -->|Parallel Execution| F2[Social Intelligence]
    E -->|Parallel Execution| F3[Market Analytics]

    F1 --> G[Result Aggregation]
    F2 --> G
    F3 --> G

    G -->|Streamed Chunks| H[Response Synthesizer]
    H -->|Real-time Stream| I[User]

    C -.->|Memory Update| J[Vector Store]
    H -.->|Conversation History| J

    style A fill:#e8e8ee,stroke:#333,color:#000
    style I fill:#e8e8ee,stroke:#333,color:#000
    style B fill:#1a1a2e,stroke:#666,color:#fff
    style D fill:#1a1a2e,stroke:#666,color:#fff
    style H fill:#1a1a2e,stroke:#666,color:#fff
    style E fill:#2d2d3d,stroke:#666,color:#fff
```

</div>

### How It Works

1. **Intent Understanding** - Multi-layer semantic analysis that understands crypto terminology, entity resolution, and query complexity patterns
2. **Cross-Conversation Memory** - Hybrid vector + relational memory retrieves relevant context across all user sessions, not just current conversation
3. **Intelligent Planning** - Dynamic execution planner decomposes complex queries into parallel tool invocations with dependency resolution
4. **Streaming Execution** - Server-Sent Events (SSE) stream responses in real-time as tools execute, providing immediate feedback
5. **Tool Orchestration** - 100+ blockchain tools execute in parallel, enabling composable multi-chain queries
6. **Context-Aware Synthesis** - Final response incorporates retrieved memories, real-time data, and conversation flow for coherent answers

---

## System Architecture

<div align="center">

```mermaid
graph TB
    subgraph "Presentation Layer"
        A1[Web API<br/>TypeScript + Axum]
        A2[WebSocket Gateway<br/>Real-time Streams]
        A3[Demo Dashboard<br/>React + TailwindCSS]
    end

    subgraph "Intelligence Layer - Rust Core"
        B1[Intent Classifier]
        B2[Planning Engine]
        B3[Response Synthesizer]
        B4[Context Manager]
    end

    subgraph "Execution Layer"
        C1[Tool Orchestrator<br/>Async Tokio Runtime]
        C2[Protocol Handler<br/>Tool Integration]
        C3[Event Processor<br/>Stream Coordinator]
    end

    subgraph "Memory Layer"
        D1[Hybrid Memory<br/>Postgres + Qdrant]
        D2[Vector Search<br/>Semantic Retrieval]
        D3[Session State<br/>Conversation Context]
    end

    subgraph "Integration Layer - TypeScript/Python"
        E1[Sentynel<br/>Twitter Intelligence]
        E2[Blockchain Adapters<br/>Multi-chain Support]
        E3[Tool Servers<br/>100+ EVM/Solana]
        E4[Custom Tracking<br/>Wallets & Tokens]
    end

    subgraph "Data Sources"
        F1[Twitter API]
        F2[Blockchain RPCs<br/>EVM/Solana]
        F3[Event Streams<br/>Real-time On-chain]
    end

    A1 --> B1
    A2 --> B4
    A3 --> A1

    B1 --> B2
    B2 --> C1
    B4 --> D3
    B3 --> A2

    C1 --> C2
    C2 --> E3
    C2 --> E4
    C3 --> D1

    D1 <--> D2
    D2 <--> B2
    D3 <--> B4

    E1 --> F1
    E2 --> E3
    E3 --> F2
    E3 --> F3

    style A1 fill:#1a1a2e,stroke:#666,color:#fff
    style A2 fill:#1a1a2e,stroke:#666,color:#fff
    style B2 fill:#2d2d3d,stroke:#666,color:#fff
    style C1 fill:#2d2d3d,stroke:#666,color:#fff
    style D1 fill:#4a4a5a,stroke:#666,color:#fff
```

</div>

---

## Technology Stack

<div align="center">

| Layer | Technologies | Purpose | Performance |
|-------|-------------|---------|-------------|
| **Frontend** | React, TailwindCSS, WebSocket | Interactive dashboard | Real-time updates |
| **API Gateway** | Axum (Rust), TypeScript Adapters | HTTP/WebSocket routing | <50ms overhead |
| **Core Engine** | Rust + Tokio async runtime | High-performance orchestration | Concurrent 100+ users |
| **Intelligence** | Multi-stage LLM pipeline | Intent → Planning → Synthesis | <5s end-to-end |
| **Memory** | PostgreSQL + Qdrant Vector DB | Hybrid relational + semantic search | <500ms retrieval |
| **Tool Integration** | Custom protocol handlers | 100+ blockchain tools | Parallel execution |
| **Event Processing** | TypeScript + Python services | Real-time blockchain/social events | 24/7 monitoring |
| **Tracking** | Sentynel (Rust), Event Streams | Wallet/token/Twitter tracking | Sub-second updates |

</div>

### Core Components

```rust
// Production query processing with streaming and memory
async fn process_crypto_query(
    query: UserQuery,
    user_id: Uuid,
    conversation_id: Option<Uuid>,
) -> Result<StreamResponse> {
    // 1. Retrieve cross-conversation context from hybrid memory
    let relevant_memories = memory_store
        .search_across_conversations(user_id, &query.text, limit: 5)
        .await?;

    // 2. Analyze intent with conversation history
    let intent = intent_classifier
        .analyze(&query, &relevant_memories)
        .await?;

    // 3. Generate execution plan with dependencies
    let plan = planning_engine
        .create_execution_plan(&intent, &relevant_memories)
        .await?;

    // 4. Execute tools in parallel via protocol handlers
    let tool_results = tool_orchestrator
        .execute_parallel(&plan.tool_calls)
        .await?;

    // 5. Stream response synthesis in real-time
    let response_stream = response_synthesizer
        .synthesize_streaming(&tool_results, &relevant_memories)
        .await?;

    // 6. Update memory with new conversation turn
    memory_store
        .create_memory(&query, &response_stream, conversation_id)
        .await?;

    Ok(response_stream)
}
```

---

## Advanced Memory System

<div align="center">

```mermaid
graph TB
    subgraph "Ingestion Pipeline"
        A1[User Query] --> A2[Response Generated]
        A2 --> A3[Memory Chunking]
        A3 --> A4[Embedding Generation]
    end

    subgraph "Dual Storage"
        B1[(PostgreSQL<br/>Structured Data)]
        B2[(Qdrant<br/>Vector Embeddings)]
    end

    subgraph "Retrieval Pipeline"
        C1[Query Embedding]
        C2[Semantic Search<br/>Qdrant KNN]
        C3[Metadata Filtering<br/>source_type, date_range]
        C4[Hybrid Ranking<br/>Vector + Recency]
        C5[Top-K Results]
    end

    subgraph "Context Enhancement"
        D1[Cross-Conversation<br/>Retrieval]
        D2[Entity Resolution<br/>Wallets/Tokens]
        D3[Temporal Context<br/>Historical Patterns]
    end

    A4 --> B1
    A4 --> B2

    C1 --> C2
    C2 --> B2
    B1 --> C3
    C3 --> C4
    C4 --> C5

    C5 --> D1
    C5 --> D2
    C5 --> D3

    D1 --> E[Enhanced Context<br/>for LLM]
    D2 --> E
    D3 --> E

    style B1 fill:#1a1a2e,stroke:#666,color:#fff
    style B2 fill:#1a1a2e,stroke:#666,color:#fff
    style C2 fill:#2d2d3d,stroke:#666,color:#fff
    style E fill:#4a4a5a,stroke:#666,color:#fff
```

</div>

**Key Features:**

- **Cross-Conversation Retrieval** - Semantic search across all user conversations, not just current session
- **Hybrid Storage** - PostgreSQL for structured data + Qdrant for 1536-dimensional embeddings
- **Smart Filtering** - Filter by source type (conversation/event/tracking), date ranges, entity types
- **Sub-500ms Retrieval** - Optimized vector search with metadata pre-filtering
- **Automatic Summarization** - Long-term memories condensed for efficient context injection
- **Entity Tracking** - Wallet addresses, tokens, and Twitter handles linked across memories

---

## Blockchain Tool Ecosystem

<div align="center">

| Tool Category | Blockchain Support | Capabilities | Tool Count |
|---------------|-------------------|--------------|------------|
| **EVM Chains** | Ethereum, Polygon, BSC, Arbitrum, Base | Token prices, balances, transfers, NFTs, DeFi protocols | 50+ tools |
| **Solana** | Mainnet, Devnet | SPL tokens, Raydium, Jupiter, wallet analysis | 30+ tools |
| **Market Data** | Multi-chain | OHLCV data, liquidity pools, trading volume, pair discovery | 10+ tools |
| **Wallet Tracking** | All chains | Real-time monitoring, P&L tracking, portfolio analysis | Custom |
| **Token Intelligence** | All chains | Price alerts, holder distribution, transfer patterns | Custom |
| **Social Signals** | Twitter | Following detection, sentiment analysis, influencer tracking | Custom |

</div>

**Tool Orchestration Architecture**

Sigyl's proprietary tool system enables:

- **Stateless Design** - Tools exposed as pure functions with JSON schemas for type safety
- **Parallel Execution** - Multiple tools execute concurrently across different blockchains
- **Error Resilience** - Failed tool calls don't crash the query pipeline; graceful degradation
- **Dynamic Composition** - Complex queries automatically decomposed into optimal tool sequences
- **Multi-chain Support** - Unified interface across EVM and Solana ecosystems

**Composability Example:**
```typescript
// Complex query automatically decomposed into parallel tool calls
query: "Compare profitability of wallet A and B on Ethereum"

execution_plan: [
  // Parallel execution across our blockchain tools
  { tool: "eth_wallet_pnl", args: { address: "0x...A", chain: "eth" } },
  { tool: "eth_wallet_pnl", args: { address: "0x...B", chain: "eth" } },
  { tool: "eth_token_balances", args: { address: "0x...A" } },
  { tool: "eth_token_balances", args: { address: "0x...B" } },
  { tool: "eth_transaction_history", args: { address: "0x...A" } },
  { tool: "eth_transaction_history", args: { address: "0x...B" } },

  // Results aggregated and synthesized into comprehensive response
]
```

---

## Real-Time Event Processing

<div align="center">

```mermaid
sequenceDiagram
    participant User
    participant Sigyl
    participant Tracker
    participant Blockchain
    participant Twitter

    User->>Sigyl: Track wallet 0x123
    Sigyl->>Tracker: Create webhook subscription
    Tracker->>Blockchain: Subscribe to event stream

    Note over Blockchain: User makes transaction

    Blockchain->>Tracker: Webhook event
    Tracker->>Tracker: Normalize event data
    Tracker->>Sigyl: POST /events/blockchain
    Sigyl->>Sigyl: Analyze transaction
    Sigyl->>Sigyl: Create memory
    Sigyl->>User: WebSocket notification

    Note over Twitter: Tracked user follows new account

    Twitter->>Tracker: Polling detects change
    Tracker->>Tracker: LLM analysis of relationship
    Tracker->>Sigyl: POST /events/social
    Sigyl->>Sigyl: Create memory + alert
    Sigyl->>User: WebSocket notification
```

</div>

**Event Sources:**
- **Blockchain Transactions** - Real-time webhooks for on-chain events across all supported chains
- **Token Transfers** - ERC-20, SPL, and native token movements
- **Social Signals** - Twitter following changes with intelligent relationship analysis
- **Price Movements** - Token price alerts from tracked holdings
- **DeFi Activity** - DEX swaps, liquidity changes, staking events

**Processing Pipeline:**
1. **Event Normalization** - Sentynel services normalize diverse event formats into unified schema
2. **Intelligence Layer** - LLM-based analysis determines significance and contextual relationships
3. **Memory Creation** - High-signal events stored as searchable memories for future retrieval
4. **Alert Generation** - User notifications via WebSocket for time-sensitive events

---

## Design Principles

<div align="center">

### **Performance-First**
Rust core + async Tokio runtime enables 100+ concurrent users with sub-5s query latency

### **Safety & Reliability**
Type-safe Rust prevents memory errors, with comprehensive error handling across the pipeline

### **Observability**
Distributed tracing and structured logging provide full visibility into query execution paths

### **Composability**
Modular tool architecture enables seamless integration of new capabilities without core changes

### **Scalability**
Stateless architecture + connection pooling + vector search optimizations support production workloads

</div>

---

## Our Vision

> **A world where anyone can query blockchains in natural language**

We're building the infrastructure for:
- **Natural language blockchain interactions** - Ask questions, get insights, no technical barriers
- **Autonomous AI agents** - Machine agents that can analyze markets, track wallets, and execute strategies
- **Open tool ecosystem** - Extensible protocol enabling third-party tool integrations
- **Cross-chain intelligence** - Unified interface across EVM, Solana, and future chains

---

## Get Started

<div align="center">

### Try Sigyl Today

[![Demo](https://img.shields.io/badge/Try%20the-Demo-E8E8EE?style=for-the-badge&logo=rocket&logoColor=000)](https://www.sigyl.ai/demo)

### Learn More

[![Website](https://img.shields.io/badge/Visit-sigyl.ai-1a1a2e?style=for-the-badge&logo=google-chrome&logoColor=E8E8EE)](https://sigyl.ai)
[![Links](https://img.shields.io/badge/All%20Links-Linktree-39E09B?style=for-the-badge&logo=linktree&logoColor=white)](https://linktr.ee/sigylai)

</div>

---

<div align="center">

### Further Reading

Dive deeper into Sigyl's architecture and vision:

[![Articles](https://img.shields.io/badge/Technical-Articles-686870?style=flat-square)](https://sigyl.ai/articles)
[![Whitepaper](https://img.shields.io/badge/Read-Whitepaper-686870?style=flat-square)](https://sigyl.ai/whitepaper)

<br/>

**© 2025 SIGYL**

</div>
