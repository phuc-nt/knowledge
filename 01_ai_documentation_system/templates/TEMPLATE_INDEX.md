# Template Index - AI Documentation System

Danh sách đầy đủ các template có sẵn trong bộ công cụ này.

## 📋 **Templates Overview**

| Template | Mục đích | Thời gian setup | Tái sử dụng |
|----------|----------|-----------------|-------------|
| [README.md](docs_structure/README.md) | Điểm vào chính của docs | 10 phút | 90% |
| [project_overview.md](docs_structure/00_context/project_overview.md) | Context dài hạn | 15 phút | 70% |
| [current_status.md](docs_structure/00_context/current_status.md) | Context ngắn hạn | 5 phút | 80% |
| [task_management_guide.md](docs_structure/00_guides/task_management_guide.md) | Quy trình làm việc | 20 phút | 95% |
| [documentation_maintenance_guide.md](docs_structure/00_guides/documentation_maintenance_guide.md) | Quy tắc viết tài liệu | 25 phút | 95% |
| [checklist_system_guide.md](docs_structure/00_guides/checklist_system_guide.md) | Hệ thống checklist | 15 phút | 90% |
| [feature_backlog.md](docs_structure/01_preparation/feature_backlog.md) | Quản lý features | 30 phút | 80% |
| [project_roadmap.md](docs_structure/01_preparation/project_roadmap.md) | Timeline & milestones | 25 phút | 85% |
| [progress_tracker.md](docs_structure/03_implementation/progress_tracker.md) | Theo dõi tiến độ | 10 phút | 85% |
| [AI Onboarding Prompt](sample_prompts/ai_onboarding_prompt.md) | Onboard AI nhanh | 5 phút | 85% |
| [SRS Creation Prompt](sample_prompts/srs_creation_prompt.md) | Tạo SRS với AI | 30 phút | 90% |

## 🚀 **Quick Start Guide**

### **Bước 1: Tạo Dự Án Mới**
```bash
# Tạo thư mục dự án
mkdir my-new-project
cd my-new-project

# Copy template structure
cp -r path/to/templates/docs_structure/ docs/

# Tạo .cursorrules (nếu cần)
touch .cursorrules
```

### **Bước 2: Customize Templates**
1. **Tìm và thay thế placeholders**:
   ```bash
   # Tìm tất cả placeholders
   grep -r "{{.*}}" docs/
   
   # Thay thế bằng sed hoặc editor
   sed -i 's/{{PROJECT_NAME}}/My Awesome Project/g' docs/**/*.md
   ```

2. **Cập nhật thông tin cụ thể**:
   - Tech stack
   - Timeline
   - Team size
   - Goals

### **Bước 3: Tạo SRS**
1. Sử dụng [SRS Creation Prompt](sample_prompts/srs_creation_prompt.md)
2. Thay thế placeholders trong prompt
3. Chạy với Reasoning AI (Claude, ChatGPT)
4. Lưu kết quả vào `docs/01_preparation/srs_v1.md`

### **Bước 4: Onboard AI**
1. Sử dụng [AI Onboarding Prompt](sample_prompts/ai_onboarding_prompt.md)
2. Customize cho AI cụ thể
3. Test với AI mới
4. Điều chỉnh nếu cần

## 📁 **Template Details**

### **Core Documentation Templates**

#### **README.md** - Điểm Vào Chính
- **Mục đích**: Navigation hub cho toàn bộ docs
- **Thời gian setup**: 10 phút
- **Tái sử dụng**: 90%
- **Cần customize**: Project name, roles, timelines

#### **project_overview.md** - Long-term Memory
- **Mục đích**: Context dài hạn không thay đổi
- **Thời gian setup**: 15 phút
- **Tái sử dụng**: 70%
- **Cần customize**: Goals, tech stack, features, timeline

#### **current_status.md** - Short-term Memory
- **Mục đích**: Context ngắn hạn, cập nhật thường xuyên
- **Thời gian setup**: 5 phút
- **Tái sử dụng**: 80%
- **Cần customize**: Current week, tasks, blockers

### **Process Templates**

#### **task_management_guide.md** - Workflow
- **Mục đích**: Quy trình làm việc chuẩn hóa
- **Thời gian setup**: 20 phút
- **Tái sử dụng**: 95%
- **Cần customize**: Tools, team size, naming conventions

#### **documentation_maintenance_guide.md** - Documentation Rules
- **Mục đích**: Quy tắc và standards cho việc viết tài liệu
- **Thời gian setup**: 25 phút
- **Tái sử dụng**: 95%
- **Cần customize**: Language, tools, review process

#### **checklist_system_guide.md** - Quality Assurance
- **Mục đích**: Hệ thống checklist cho consistency
- **Thời gian setup**: 15 phút
- **Tái sử dụng**: 90%
- **Cần customize**: Checklist types, tools integration

### **Planning Templates**

#### **feature_backlog.md** - Feature Management
- **Mục đích**: Organize và prioritize features
- **Thời gian setup**: 30 phút
- **Tái sử dụng**: 80%
- **Cần customize**: Features từ SRS, priorities, sprint planning

#### **project_roadmap.md** - Timeline Planning
- **Mục đích**: Timeline, milestones, và phases
- **Thời gian setup**: 25 phút
- **Tái sử dụng**: 85%
- **Cần customize**: Phases, milestones, dates, team size

### **Implementation Templates**

#### **progress_tracker.md** - Daily/Weekly Tracking
- **Mục đích**: Track progress và velocity hàng ngày
- **Thời gian setup**: 10 phút
- **Tái sử dụng**: 85%
- **Cần customize**: Sprint info, features, metrics

### **AI Interaction Templates**

#### **AI Onboarding Prompt** - Quick Start
- **Mục đích**: Onboard AI trong <5 phút
- **Thời gian setup**: 5 phút
- **Tái sử dụng**: 85%
- **Cần customize**: Project info, session goals

#### **SRS Creation Prompt** - Requirements
- **Mục đích**: Tạo SRS chi tiết với AI
- **Thời gian setup**: 30 phút
- **Tái sử dụng**: 90%
- **Cần customize**: Project description, constraints

## 🎯 **Customization Guide**

### **Placeholders to Replace**

| Placeholder | Ví dụ | Mô tả |
|-------------|-------|-------|
| `{{PROJECT_NAME}}` | "iOS Chatbot" | Tên dự án |
| `{{TECH_STACK}}` | "SwiftUI + Core Data" | Công nghệ chính |
| `{{MAIN_GOAL}}` | "Create AI chat app" | Mục tiêu chính |
| `{{CURRENT_WEEK}}` | "3 of 18" | Tuần hiện tại |
| `{{TEAM_SIZE}}` | "Solo developer" | Quy mô team |

### **Sections to Customize**

1. **Tech Stack**: Điều chỉnh cho phù hợp
2. **Timeline**: Chia thành phases hợp lý
3. **Features**: Liệt kê từ SRS
4. **Tools**: Chọn tools phù hợp
5. **Process**: Điều chỉnh cho team size

## 🔧 **Advanced Usage**

### **Multi-Project Setup**
```bash
# Tạo template library
mkdir ~/dev-templates
cp -r templates/* ~/dev-templates/

# Tạo script auto-setup
cat > ~/dev-templates/setup.sh << 'EOF'
#!/bin/bash
PROJECT_NAME=$1
cp -r docs_structure/ $PROJECT_NAME/docs/
echo "Setup complete for $PROJECT_NAME"
EOF
```

### **Team Onboarding**
1. Chia sẻ template library
2. Tạo team-specific customizations
3. Document team conventions
4. Train team trên workflow

### **Continuous Improvement**
- Thu thập feedback từ team
- Cập nhật templates dựa trên lessons learned
- Version control cho templates
- Share improvements với community

## 📊 **Success Metrics**

### **Template Quality**
- [ ] AI onboarding <5 phút
- [ ] Setup dự án mới <30 phút
- [ ] Team hiểu workflow ngay lập tức
- [ ] Docs luôn up-to-date

### **Process Efficiency**
- [ ] Giảm 80% thời gian setup
- [ ] Tăng 50% consistency
- [ ] Giảm 90% onboarding time
- [ ] Tăng AI collaboration quality

## 🛠️ **Troubleshooting**

### **Common Issues**

**AI không hiểu context**:
- Kiểm tra placeholders đã thay thế chưa
- Đảm bảo links trong docs hoạt động
- Cập nhật current_status.md

**Team không follow process**:
- Simplify workflow
- Provide more examples
- Regular training sessions

**Templates quá phức tạp**:
- Tạo simplified version
- Focus on core templates first
- Gradual adoption

## 🎉 **Next Steps**

1. **Thử nghiệm**: Setup 1 dự án nhỏ
2. **Customize**: Điều chỉnh cho team
3. **Scale**: Áp dụng cho nhiều dự án
4. **Improve**: Cập nhật dựa trên feedback
5. **Share**: Chia sẻ với community

---

*Template system được tạo ra từ kinh nghiệm thực tế với iOS Chatbot project*  
*Cập nhật lần cuối: {{LAST_UPDATED}}* 