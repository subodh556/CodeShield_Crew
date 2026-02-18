# 🛡️CodeShield Crew

**CodeShield Crew** is an intelligent, multi-agent code review system that delivers comprehensive analysis across three critical dimensions: security, performance, and code quality. By leveraging specialized AI agents, it provides actionable insights that help teams ship better, safer code faster.

### Perfect For 
- Pre-deployment code validation and security audits
- Performance optimization and bottleneck identification
- Enforcing team code standards and best practices
- Architecture reviews and scalability assessments

---
 
## ✨ Key Features

- **🔒 Security Analysis**: Advanced vulnerability detection, threat modeling, and security best practices enforcement
- **⚡ Performance Profiling**: Bottleneck identification, optimization recommendations, and efficiency analysis
- **✅ Quality Assurance**: Code style enforcement, maintainability scoring, and design pattern validation
- **📊 Actionable Reports**: Comprehensive findings with prioritized, step-by-step remediation guidance

---

### How It Works
```
Code Submission → Security Analysis → Performance Review → Quality Assessment → Final Report
```

---

## 👥 Meet the Agent Team

| Agent | Responsibility | Expertise |
|-------|----------------|-----------|
| **Security Specialist** | Security vulnerabilities, threat analysis | Security best practices, vulnerability assessment |
| **Performance Analyst** | Performance optimization, bottlenecks | Performance profiling, optimization techniques |
| **Quality Reviewer** | Code style, maintainability, standards | Code quality, design patterns, best practices |
| **Senior Reviewer** | Architecture, final recommendations | System design, technical leadership |

---

## ⚙️ Installation

Get up and running in under 5 minutes:

### 1. Clone the Repository
```bash
git clone https://github.com/subodh556/CodeShield_Crew.git
cd CodeShield_Crew
```

### 2. Set Up Virtual Environment
```bash
# Install uv if not already installed
pip install uv

# Create and activate virtual environment
uv venv
.venv\Scripts\activate  # Windows
# source .venv/bin/activate  # Linux/Mac
```

### 3. Install Dependencies
```bash
uv pip install -r requirements.txt
```

### 4. Configure Environment Variables
- Rename `.env.example` to `.env` in your project root
- Add your API keys:
```env
# Choose your preferred AI providers
GEMINI_API_KEY=your-gemini-key-here
GROQ_API_KEY=your-groq-key-here
ANTHROPIC_API_KEY=your-anthropic-key-here
OPENAI_API_KEY=your-openai-key-here
```

### 5. Run CodeShield Crew
```bash
streamlit run codeshield_crew.py
```

---
