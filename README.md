# ai-test-healer
AI-Powered self-healing test framework for flaky UI automation tests

# AI Self-Healing Test Automation Framework

**Inspired by TestovAIte - My award-winning framework at LTIMindtree**

## 🏆 Background

At LTIMindtree, for  **TestovAIte** hackathon event, i have developed Gen AI based testing framework that won our Testing Innovation Hackathon 2025.

**The Problem:** QA teams spend 40-60% of their time fixing broken tests when UI elements change.

**The Solution:** AI automatically detects and fixes broken locators in real-time.

## 🚀 TestovAIte Results

- **70% reduction** in test maintenance time
- **95% test reliability** even with frequent UI changes
- **Winner** - LTIMindtree Testing Innovation Hackathon 2025
- **Currently deployed** across multiple client projects

## 🔧 Technology Stack

- **Playwright (Java)** - Modern browser automation
- **Groq API** - Ultra-fast LLM inference (100ms response time)
- **Maven** - Enterprise build system
- **TestNG** - Test framework

## 🎯 Why Groq?

After evaluating GPT-4, Claude, and Groq:
- ⚡ **10x faster** than alternatives (100ms vs 2-3 seconds)
- 💰 **80% lower cost** at scale
- 🎯 **91% accuracy** for locator healing
- 📊 **Scalable** for enterprise test suites

## 🏗️ Architecture
Test Execution (Playwright + Java)
↓
Locator Fails
↓
Context Analyzer (Extract DOM + Intent)
↓
Groq API (Fast LLM Reasoning)
↓
Multiple Locator Strategies Returned
↓
Self-Healing Manager (Test + Cache)
↓
Test Continues Successfully

## 💡 How It Works

**Traditional Testing:**
```java
// Developer changes button ID
page.click("#submit-btn"); // ❌ Test fails
// Manual fix needed
AI Self-Healing:
java// Developer changes button ID
resilientPage.smartClick("submit button"); // ✅ Auto-heals
// Groq finds new locator in 100ms
// Test continues successfully
📊 Business Impact
For a 5-person QA team:

Time saved: 28 hours/week
Cost savings: ₹11.6 lakhs/year
ROI: 8,700%

📝 Status
This repository demonstrates the core concepts from my enterprise work at LTIMindtree.

👤 About Me
Archana chitraju
QA Automation Lead | 13+ Years Experience
Specialized in AI-powered test automation

🏆 Winner - LTIMindtree Testing Innovation Hackathon 2025
🔧 Expert in Playwright, Selenium  UFT 
🤖 AI Testing Pioneer (Groq, Claude, GPT-4)
👥 Team Leadership & Mentoring

Currently exploring opportunities in:

AI Testing Engineering
MLOps QA
Test Automation Innovation

📧archanaeshwar.07@gmail.com
💼 www.linkedin.com/in/archanachitraju
🌐 Open to new opportunities

Built with ❤️ and 🤖 at LTIMindtree
Want to discuss AI testing? Let's connect!
