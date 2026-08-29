<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=1,11,20&height=180&section=header&text=Nitin%20Kumar&fontSize=42&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=Full-Stack%20Architect%20|%20Problem%20Solver%20|%20Innovation%20Driver&descAlignY=60&descAlign=50" width="100%"/>
</div>

<h2 align="center">Full-Stack Developer and Architect</h2>

<div align="center">
  <img src="https://raw.githubusercontent.com/yasiwes/yasiwes/main/assets/developer.gif" width="480" />
</div>

<p align="center">
  <a href="https://linkedin.com"><img src="https://img.shields.io/badge/LINKEDIN-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
  <a href="https://github.com/nkmalyan"><img src="https://img.shields.io/badge/GITHUB-181717?style=for-the-badge&logo=github&logoColor=white" /></a>
  <a href="mailto:your-email@gmail.com"><img src="https://img.shields.io/badge/GMAIL-EA4335?style=for-the-badge&logo=gmail&logoColor=white" /></a>
</p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=nkmalyan&label=PROFILE+VIEWS&style=flat-square&color=blue" />
</p>

---

### 💻 About Me

<table>
<tr>
<td width="60%">

```typescript
class Developer {
    readonly name: string = "Nitin Kumar";
    readonly location: string = "🇮🇳 MNNIT Allahabad, India";
    readonly education: string = "B.Tech (2022-2026)";
    
    private skills = {
        languages: ["C++", "JavaScript", "TypeScript", "SQL"],
        
        frontend: {
            frameworks: ["React.js", "Next.js"],
            styling: ["TailwindCSS", "shadcn/ui"],
            tools: ["Vite", "Zustand"]
        },
        
        backend: {
            runtime: ["Node.js", "Express.js"],
            databases: ["PostgreSQL", "MongoDB", "Neon DB"],
            orm: ["Prisma", "Mongoose"],
            apis: ["REST", "WebSockets (Socket.io)"]
        },
        
        ai_and_devOps: {
            ai: ["Gemini API", "Agentic Workflows"],
            tools: ["Git", "GitHub", "Postman", "Render"]
        }
    };

    getCurrentFocus(): string[] {
        return [
            "🎯 Mastering Distributed Systems & Microservices",
            "🤖 Integrating Agentic AI Workflows",
            "🚀 Building Production-Ready Full-Stack Apps",
            "📚 Advanced System Design & Scalability"
        ];
    }

    funFact(): string {
        return "I turn coffee ☕ into code 💻 and bugs into features! 😄";
    }
}

const me = new Developer();
console.log(me.getCurrentFocus());
🚀 Featured Projects🤖 PREPO - AI-Powered Career Prep Platform Status: LiveProject Overview:An intelligent career preparation platform integrating Google Gemini LLM for automated interview content synthesis, structured assessments, and instant dynamic evaluation.Tech Architecture:
- Frontend: Next.js 14 (App Router), TypeScript, Tailwind CSS, shadcn/ui
- Backend: Next.js Server Actions, REST APIs
- Database: PostgreSQL (Neon DB), Prisma ORM
- Auth & AI: Clerk Auth, Google Gemini Pro API
- Infrastructure: Deployed on Vercel / Render
🔒 Security & AuthenticationJWT & Clerk AuthenticationRole-Based Access Control (RBAC)Multi-factor session safeguardsProtected Server Actions⚡ Performance OptimizationsSub-second serverless executionServer-Side Rendering (SSR) & StreamingStructured JSON parsing for LLM outputsOptimized Prisma connection pooling📊 Performance MetricsMetricBeforeAfterImprovementQuiz Generation Latency3.5s1.1s⚡ 68%API Response Time900ms310ms🚀 65%Page Load Time3.2s1.2s⚡ 62%System Uptime-99.9%🟩 Live💬 ChatSync - Real-Time Collaboration Engine Status: ProductionProject Overview:A low-latency, bidirectional real-time chat application engineered with WebSockets, structured state persistence, and instant event routing.System Architecture:
- Frontend: React.js, Zustand State Management, Tailwind CSS
- Backend: Node.js, Express.js, Socket.io
- Database: MongoDB Atlas, Mongoose
- Security: JSON Web Tokens (JWT)
🚀 Real-Time CommunicationWebSocket bidirectional channels<100ms message delivery latencyLive online/offline presence indicatorsDynamic typing status signals📦 Architecture & ReliabilityScalable Socket room allocationsClient-side cache sync with ZustandSecure handshake JWT verificationError boundary event recovery
