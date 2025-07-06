# AI Onboarding Prompt Template

<!-- 
📝 HƯỚNG DẪN SỬ DỤNG:
1. Copy prompt này và thay thế {{PLACEHOLDER}} bằng thông tin thực tế
2. Paste vào chat với AI mới (Claude, ChatGPT, v.v.)
3. Đảm bảo AI đã đọc được các file được reference
4. Điều chỉnh prompt cho phù hợp với AI cụ thể
-->

## 🎯 **AI Onboarding Prompt**

```
Hi! I'm bringing you into an ongoing project. I've set up a comprehensive documentation system to help you understand everything quickly.

**Project**: {{PROJECT_NAME}}
**My Role**: {{YOUR_ROLE}} (e.g., "Lead Developer", "Project Manager", "Solo Developer")
**Your Role**: {{AI_ROLE}} (e.g., "Coding Assistant", "Architecture Advisor", "Code Reviewer")

## 📚 **Please Read These Files First (in order):**

1. **docs/README.md** - Start here for navigation
2. **docs/00_context/project_overview.md** - What we're building
3. **docs/00_context/current_status.md** - Where we are now
4. **{{CURSORRULES_PATH}}** - Coding standards and preferences

**Total reading time**: ~5 minutes

## 🎯 **What I Need You To Do:**

After reading, please:
1. **Confirm Understanding**: Summarize the project in 2-3 sentences
2. **Identify Current Focus**: What should we work on next?
3. **Ask Clarifying Questions**: What's unclear or needs more context?
4. **Suggest Next Steps**: Based on current status, what are logical next actions?

## 🔧 **Working Style Preferences:**

- **Communication**: {{COMMUNICATION_STYLE}} (e.g., "Direct and concise", "Detailed explanations", "Step-by-step guidance")
- **Code Style**: Follow the .cursorrules file exactly
- **Documentation**: Update relevant docs when making changes
- **Decision Making**: {{DECISION_STYLE}} (e.g., "Ask before major changes", "Proceed with best practices", "Explain options and let me choose")

## 📋 **Current Session Goals:**

{{CURRENT_SESSION_GOALS}}
<!-- Example:
- Set up development environment
- Create basic project structure  
- Implement first core feature
- Review and improve documentation
-->

## ⚠️ **Important Notes:**

- **Always read current_status.md first** when starting a new session
- **Update documentation** as we make progress
- **Ask questions** if anything is unclear
- **Follow the established process** outlined in the guides

Ready to start? Please confirm you've read the files and understand the project context.
```

---

## 🔄 **Variations for Different AI Types**

### **For Coding-Focused AI (Claude, Cursor, etc.)**
```
Additional instructions:
- Focus on code quality and best practices
- Suggest architectural improvements
- Help with debugging and testing
- Review code for security issues
```

### **For Planning-Focused AI (ChatGPT, Reasoning models)**
```
Additional instructions:
- Help with project planning and prioritization
- Suggest process improvements
- Assist with requirement analysis
- Help break down complex tasks
```

### **For Specialized AI (Search, Research, etc.)**
```
Additional instructions:
- Research best practices for our tech stack
- Find solutions to technical challenges
- Compare different approaches
- Provide technical documentation
```

---

## 📊 **Success Metrics**

A successful onboarding should result in:
- [ ] AI understands project context in <5 minutes
- [ ] AI provides relevant, actionable suggestions
- [ ] AI follows established coding standards
- [ ] AI updates documentation appropriately
- [ ] AI asks good clarifying questions

---

## 🛠️ **Troubleshooting**

### **If AI seems confused:**
1. Check if it actually read the files
2. Provide more specific context
3. Break down the request into smaller parts
4. Reference specific sections of documentation

### **If AI ignores standards:**
1. Explicitly reference .cursorrules
2. Provide examples of expected output
3. Correct immediately and explain why
4. Update documentation if standards unclear

---

*Template created from {{PROJECT_NAME}} experience*  
*Last updated: {{LAST_UPDATED}}* 