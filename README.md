class Developer {
    readonly name: string = "Nitin Kumar";
    readonly location: string = "🇮🇳 MNNIT Allahabad, India";
    readonly education: string = "B.Tech Electrical Engineering (2022-2026)";
    
    private skills = {
        languages: ["C++", "JavaScript", "TypeScript", "SQL"],
        
        frontend: {
            frameworks: ["React.js", "Next.js"],
            styling: ["TailwindCSS", "shadcn/ui"],
            stateManagement: ["Zustand"]
        },
        
        backend: {
            runtime: ["Node.js", "Express.js"],
            databases: ["PostgreSQL", "MongoDB", "Neon DB"],
            orm: ["Prisma ORM"],
            communication: ["REST APIs", "Socket.io (WebSockets)"]
        },
        
        ai_and_tools: [
            "Gemini API",
            "Generative AI Workflows",
            "Git",
            "GitHub",
            "Postman",
            "VS Code"
        ]
    };
    
    competitive = {
        dsa: "Practicing DSA patterns in C++ & Java",
        platforms: ["LeetCode", "GeeksforGeeks", "Coding Ninjas"]
    };
    
    getCurrentFocus(): string[] {
        return [
            "🚀 Building full-stack GenAI web applications",
            "⚡ Scaling real-time systems using WebSockets",
            "🎯 Advanced DSA & Core Engineering Concepts",
            "📚 System Design & Backend Architecture"
        ];
    }
    
    getFeaturedProjects(): string[] {
        return [
            "🤖 PREPO - AI-Powered Career Prep Platform (Next.js + Gemini API)",
            "💬 Real-Time Chat Engine (Socket.io + Zustand)",
            "📝 Full-Stack MERN Blog Application"
        ];
    }
    
    funFact(): string {
        return "I turn logic into scalable code 💻 and ideas into AI-driven products! 🚀";
    }
}

const me = new Developer();
console.log(me.getCurrentFocus());

---

### 📊 GitHub Stats & Streak

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=nkmalyan&show_icons=true&theme=tokyonight&hide_border=true" alt="GitHub Stats" />
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=nkmalyan&theme=tokyonight&hide_border=true" alt="GitHub Streak" />
</p>

---

### 🌐 Connect With Me

<p align="center">
  <a href="[https://www.linkedin.com/in/nitin-kumar-7aab74222]" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  <a href="mailto:nitinkumarmalyan.010@gmail.com">
    <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
  </a>
</p>
