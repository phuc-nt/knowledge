# Documentation Templates

Bộ template này được thiết kế để giúp bạn triển khai hệ thống tài liệu "AI-friendly" được mô tả trong bài blog **"AI Không Đọc Được Suy Nghĩ Của Bạn"**.

## 🎯 Cách Sử Dụng

### **Bước 1: Copy Toàn Bộ Cấu Trúc**
```bash
# Copy toàn bộ thư mục templates vào dự án mới
cp -r templates/ your-new-project/docs/
```

### **Bước 2: Thay Thế Placeholders**
Mỗi template chứa các placeholder dạng `{{PLACEHOLDER}}` mà bạn cần thay thế:
- `{{PROJECT_NAME}}` - Tên dự án của bạn
- `{{TECH_STACK}}` - Công nghệ sử dụng (ví dụ: "React + Node.js")
- `{{MAIN_GOAL}}` - Mục tiêu chính của dự án
- `{{CURRENT_WEEK}}` - Tuần hiện tại trong roadmap
- `{{NEXT_MILESTONE}}` - Cột mốc tiếp theo

### **Bước 3: Điền Nội Dung Cụ Thể**
Sau khi thay thế placeholder, điền nội dung cụ thể theo hướng dẫn trong từng template.

## 📁 Cấu Trúc Templates

```
templates/
├── README.md                    # File này
├── docs_structure/              # Cấu trúc thư mục docs/ hoàn chỉnh
│   ├── README.md               # Template cho file README chính
│   ├── 00_context/
│   │   ├── project_overview.md
│   │   └── current_status.md
│   ├── 00_guides/
│   │   ├── task_management_guide.md
│   │   ├── checklist_system_guide.md
│   │   └── documentation_maintenance_guide.md
│   ├── 01_preparation/
│   ├── 02_development/
│   ├── 03_implementation/
│   └── 04_troubleshooting/
└── sample_prompts/              # Các prompt mẫu để làm việc với AI
    ├── srs_creation_prompt.md
    ├── dev_guide_prompt.md
    └── ai_onboarding_prompt.md
```

## 🚀 Quick Start

1. **Tạo dự án mới**: Copy cấu trúc `docs_structure/` vào dự án
2. **Thay thế placeholders**: Tìm và thay thế tất cả `{{...}}`
3. **Tạo SRS**: Sử dụng prompt trong `sample_prompts/srs_creation_prompt.md`
4. **Setup môi trường**: Dùng prompt trong `sample_prompts/dev_guide_prompt.md`
5. **Onboard AI**: Dùng prompt trong `sample_prompts/ai_onboarding_prompt.md`

## 💡 Tips

- **Luôn bắt đầu với file `docs/README.md`** - đây là điểm vào duy nhất
- **Cập nhật `current_status.md` hàng ngày** - chỉ mất 2 phút
- **Tuân thủ `task_management_guide.md`** - đảm bảo quy trình nhất quán
- **Sử dụng checklist system** - AI làm việc tốt với checklist

---
*Templates được tạo ra từ kinh nghiệm thực tế trong dự án iOS Chatbot.* 