<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=1,11,20&height=180&section=header&text=Nitin%20Kumar&fontSize=42&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=Full-Stack%20Architect%20%7C%20Problem%20Solver%20%7C%20Innovation%20Driver&descAlignY=60&descAlign=50" width="100%"/>
</div>

<h2 align="center">Full-Stack Developer and Architect</h2>

<div align="center">
  <img src="https://raw.githubusercontent.com/yasiwes/yasiwes/main/assets/developer.gif" width="480" />
</div>

<p align="center">
  <a href="https://linkedin.com"><img src="https://img.shields.io/badge/LINKEDIN-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
  <a href="https://github.com/nkmalyan"><img src="https://img.shields.io/badge/GITHUB-181717?style=for-the-badge&logo=github&logoColor=white" /></a>
  <a href="https://leetcode.com"><img src="https://img.shields.io/badge/LEETCODE-FFA116?style=for-the-badge&logo=leetcode&logoColor=black" /></a>
  <a href="mailto:nitinkumarmalyan.010@gmail.com"><img src="https://img.shields.io/badge/GMAIL-EA4335?style=for-the-badge&logo=gmail&logoColor=white" /></a>
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
    readonly education: string = "B.Tech Electrical Engineering (2022-2026)";
    
    private skills = {
        languages: ["C++", "C", "JavaScript", "TypeScript", "SQL", "HTML/CSS"],
        
        frontend: {
            frameworks: ["React.js", "Next.js 14"],
            styling: ["TailwindCSS", "shadcn/ui"],
            stateManagement: ["Zustand", "Context API"]
        },
        
        backend: {
            runtime: ["Node.js", "Express.js"],
            databases: ["PostgreSQL (Neon DB)", "MongoDB Atlas"],
            orm: ["Prisma ORM", "Mongoose"],
            apis: ["REST APIs", "Socket.io (WebSockets)"]
        },
        
        ai_devOps: {
            ai: ["Google Gemini API", "LLM Orchestration"],
            automation: ["Inngest Workflows", "Agentic Pipelines"],
            cloud: ["AWS", "Vercel", "Render", "Docker"]
        }
    };

    competitive = {
        leetcode: {
            solved: "400+ Problems",
            focus: ["Dynamic Programming", "Graphs", "Trees", "Arrays"]
        },
        achievements: [
            "🏆 IBM SKILLSBUILD 'Fundamentals of AI' Certified",
            "🎓 Dakshana Student's Academic Mentor",
            "⚡ Conducted National Dakshana Scholarship Test"
        ]
    };

    getCurrentFocus(): string[] {
        return [
            "🎯 Distributed Systems & Scalable Real-Time Architectures",
            "🤖 Integrating Production-Ready Agentic AI Workflows",
            "🧩 Advanced DSA Problem Solving in C++",
            "🚀 Building Full-Stack Production SaaS Products"
        ];
    }

    funFact(): string {
        return "I turn coffee ☕ into clean code 💻 and complex problems into scalable features! 🚀";
    }
}

const me = new Developer();
console.log(me.getCurrentFocus());  
