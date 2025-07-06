# SRS Creation Prompt Template

<!-- 
📝 HƯỚNG DẪN SỬ DỤNG:
1. Dùng prompt này với Reasoning AI (Claude, ChatGPT, v.v.)
2. Thay thế {{PLACEHOLDER}} bằng thông tin thực tế của dự án
3. Có thể chia nhỏ thành nhiều lần chat nếu dự án phức tạp
4. Kết quả sẽ là file SRS chi tiết để team development sử dụng
-->

## 🎯 **SRS Creation Prompt**

```
I need you to help me create a comprehensive Software Requirements Specification (SRS) document for my new project. I'll provide you with the basic idea, and you'll help me develop it into a detailed, actionable specification.

## 📋 **Project Information**

**Project Name**: {{PROJECT_NAME}}
**Project Type**: {{PROJECT_TYPE}} (e.g., "Mobile App", "Web Application", "Desktop Software", "API Service")
**Platform**: {{TARGET_PLATFORM}} (e.g., "iOS", "Android", "Web", "Cross-platform")
**Target Audience**: {{TARGET_USERS}} (e.g., "General consumers", "Business users", "Developers")

## 💡 **Core Idea**

{{PROJECT_DESCRIPTION}}
<!-- Example:
"I want to create an iOS chatbot app that allows users to connect to multiple LLM providers (OpenAI, Anthropic, etc.) using their own API keys. The app should provide a clean, native iOS experience with conversation history, different AI models, and secure API key storage."
-->

## 🎯 **Key Goals**

1. {{GOAL_1}} (e.g., "Provide a native iOS alternative to web-based AI chats")
2. {{GOAL_2}} (e.g., "Support multiple LLM providers in one app")
3. {{GOAL_3}} (e.g., "Ensure user privacy and data security")
4. {{GOAL_4}} (e.g., "Create an intuitive, user-friendly interface")

## 🚀 **Success Criteria**

- {{SUCCESS_CRITERION_1}} (e.g., "App approved on App Store")
- {{SUCCESS_CRITERION_2}} (e.g., "Supports at least 3 major LLM providers")
- {{SUCCESS_CRITERION_3}} (e.g., "Positive user feedback on usability")
- {{SUCCESS_CRITERION_4}} (e.g., "No security vulnerabilities in API key handling")

## 🔧 **Technical Constraints**

- **Budget**: {{BUDGET_CONSTRAINT}} (e.g., "Bootstrap/minimal cost", "Small budget", "Well-funded")
- **Timeline**: {{TIMELINE_CONSTRAINT}} (e.g., "3 months", "6 months", "No strict deadline")
- **Team Size**: {{TEAM_SIZE}} (e.g., "Solo developer", "2-3 developers", "Full team")
- **Technical Skills**: {{TECH_SKILLS}} (e.g., "Experienced iOS developer", "Full-stack developer", "Beginner")

## 📱 **Platform Requirements**

- **Primary Platform**: {{PRIMARY_PLATFORM}}
- **Secondary Platforms**: {{SECONDARY_PLATFORMS}} (if any)
- **Minimum OS Version**: {{MIN_OS_VERSION}} (e.g., "iOS 15+", "Android 8+")
- **Device Support**: {{DEVICE_SUPPORT}} (e.g., "iPhone + iPad", "Phone only")

## 🎨 **User Experience Expectations**

- **Design Style**: {{DESIGN_STYLE}} (e.g., "Modern, minimalist", "Colorful and playful", "Professional")
- **Complexity Level**: {{COMPLEXITY_LEVEL}} (e.g., "Simple and intuitive", "Feature-rich", "Power user focused")
- **Performance**: {{PERFORMANCE_EXPECTATIONS}} (e.g., "Fast and responsive", "Smooth animations", "Low battery usage")

## 🔒 **Security & Privacy Requirements**

- **Data Storage**: {{DATA_STORAGE}} (e.g., "Local only", "Cloud sync optional", "Cloud-first")
- **API Keys**: {{API_KEY_HANDLING}} (e.g., "User-provided, stored securely", "App-managed", "Both options")
- **Privacy Level**: {{PRIVACY_LEVEL}} (e.g., "No data collection", "Minimal analytics", "Full analytics")

## 🛠️ **Technical Preferences**

- **Architecture**: {{ARCHITECTURE_PREFERENCE}} (e.g., "MVVM", "Clean Architecture", "No preference")
- **Database**: {{DATABASE_PREFERENCE}} (e.g., "Core Data", "SQLite", "Realm", "No preference")
- **UI Framework**: {{UI_FRAMEWORK}} (e.g., "SwiftUI", "UIKit", "React Native", "Flutter")
- **Testing**: {{TESTING_PREFERENCE}} (e.g., "Unit tests required", "Basic testing", "Comprehensive testing")

## 📊 **Business Requirements**

- **Monetization**: {{MONETIZATION}} (e.g., "Free and open source", "Freemium", "Paid app", "Subscription")
- **Distribution**: {{DISTRIBUTION}} (e.g., "App Store only", "Open source", "Enterprise")
- **Support**: {{SUPPORT_LEVEL}} (e.g., "Community support", "Basic support", "Full support")

## 🎯 **What I Need From You**

Please create a comprehensive SRS document that includes:

1. **Executive Summary** - High-level overview
2. **Functional Requirements** - What the app should do
3. **Non-Functional Requirements** - Performance, security, usability
4. **User Stories** - Detailed user scenarios
5. **Technical Architecture** - High-level technical approach
6. **API Specifications** - If applicable
7. **Data Models** - Core data structures
8. **User Interface Requirements** - Key screens and flows
9. **Security Requirements** - Detailed security considerations
10. **Testing Strategy** - How to validate the requirements
11. **Deployment Strategy** - How to release the app
12. **Maintenance Plan** - Post-launch considerations

## 📝 **Output Format**

Please structure the SRS as a markdown document with:
- Clear headings and sections
- Numbered requirements for easy reference
- User stories in "As a [user], I want [goal] so that [benefit]" format
- Technical details appropriate for developers
- Acceptance criteria for each major feature

## 🔄 **Iterative Process**

After you provide the initial SRS:
1. I'll review and provide feedback
2. We'll refine unclear or missing requirements
3. We'll prioritize features for MVP vs future versions
4. We'll finalize the document for development

Ready to start? Please ask any clarifying questions you need, then begin creating the SRS document.
```

---

## 🎯 **Follow-up Prompts**

### **For Refinement:**
```
Please review the SRS and:
1. Identify any ambiguous requirements
2. Suggest missing requirements you think are important
3. Prioritize features into MVP, Version 2, and Future categories
4. Estimate complexity for each major feature (Simple/Medium/Complex)
```

### **For Technical Deep-dive:**
```
Please expand the technical architecture section with:
1. Detailed component diagrams
2. Database schema design
3. API endpoint specifications
4. Security implementation details
5. Performance optimization strategies
```

### **For User Experience:**
```
Please create detailed user journey maps for:
1. First-time user onboarding
2. Daily usage scenarios
3. Power user workflows
4. Error handling and recovery
```

---

## 📊 **Quality Checklist**

A good SRS should be:
- [ ] **Complete**: All requirements covered
- [ ] **Consistent**: No contradictions
- [ ] **Clear**: Unambiguous language
- [ ] **Correct**: Technically feasible
- [ ] **Ranked**: Prioritized by importance
- [ ] **Verifiable**: Testable requirements
- [ ] **Modifiable**: Easy to update
- [ ] **Traceable**: Requirements linked to goals

---

*Template based on {{PROJECT_NAME}} SRS creation experience*  
*Last updated: {{LAST_UPDATED}}* 