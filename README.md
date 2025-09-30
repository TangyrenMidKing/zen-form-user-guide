# Massage Shop Intake Form System (Zen Form) / 按摩店 Intake Form 系统

A paperless customer information collection and management system designed for massage shops, compliant with Florida legal requirements (House Bill 197). / 一个专为按摩店设计的无纸化客户信息收集和管理系统，符合佛罗里达州法律要求（House Bill 197）。

## 📋 Project Overview / 项目概述

Zen Form is a modern web platform that provides massage shops with: / Zen Form 是一个现代化的 Web 平台，为按摩店提供：

- **Paperless intake form collection** / **无纸化 intake form 收集**
- **Customer information management tools** / **客户信息管理工具**
- **Compliance assurance** / **合规性保障**
- **Convenient customer filling experience** / **便捷的客户填写体验**

## 🎯 Core Values / 核心价值

1. **Compliance** / **合规性** - Meet Florida legal requirements for recording customer information in massage shops / 满足佛罗里达按摩店记录客户信息的法律要求
2. **Efficiency** / **效率提升** - Scan to fill forms, reducing paper form management / 扫码即填表，减少纸质表单管理
3. **Customer Experience** / **客户体验** - Returning customers can check in instantly, reducing repetitive form filling / 老顾客秒级签到，降低重复填写负担
4. **Data Security** / **数据安全** - Cloud storage of customer privacy information with secure export and deletion support / 客户隐私信息云端存储，支持安全导出与删除

## 👥 User Roles / 用户角色

| Role / 角色 | Description / 描述 |
|------|------|
| **Guest (Customer)** / **客人（客户）** | Fill out intake form by scanning QR code upon arrival, no login required, completely anonymous process / 到店后通过扫码填写 intake form，无需登录，流程完全匿名化 |
| **Store Owner/Admin** / **店主/管理员** | Has admin account access to manage stores, customer information, QR codes, form records, exports, etc. / 拥有管理后台账号，可以管理门店、客户信息、二维码、表单记录、导出等操作 |

## 🚀 Features / 功能特性

### Client Features (Anonymous Access) / 客户端功能（匿名访问）
- ✅ **QR Code Store Access** / **扫码进入门店界面** - URL structure: `domain.com/{store_name}` / URL 结构为 `domain.com/{store_name}`
- ✅ **Check-in Process** / **Check-in 流程** - New customers fill complete info, returning customers search by name + birthday / 新顾客填写完整信息，老顾客通过名字 + 生日搜索
- ✅ **New Customer Form** / **新顾客表单** - Name, birthday, phone, address, emergency contact, medical/allergy history, e-signature, massage preferences / 姓名、生日、电话、地址、紧急联系人、医疗/过敏史、电子签名、按摩需求
- ✅ **Returning Customer Info Update** / **老顾客信息更新** - Can update address/phone fields after search / 搜索后可更新地址/电话等字段
- ✅ **Submission Confirmation** / **提交结果提示** - Shows check-in success, automatically clears form / 显示签到成功，自动清空表单

### Store Owner Admin Features / 店主管理端功能
- ✅ **Account Login** / **账号登录** - Store owners login with email/username + password / 店主通过邮箱/用户名 + 密码登录
- ✅ **Store Information Management** / **店铺信息管理** - Add/modify store address, store name, store QR code generation / 添加/修改店铺地址、店铺名称、店铺二维码生成
- ✅ **QR Code Download & Print** / **二维码下载打印** - System auto-generates QR codes, supports PNG/JPG download for printing / 系统自动生成二维码，支持下载 PNG/JPG 文件供打印张贴
- ✅ **Customer Form Search** / **客户表单查询** - Search customer submission records by date, name, phone / 支持按日期、客户姓名、电话搜索客户提交记录
- ✅ **Customer Form Deletion** / **客户表单删除** - Allow deletion of expired or invalid customer records when compliant / 符合法规时，允许删除过期或无效客户记录
- ✅ **Customer Data Export** / **客户信息导出** - Support CSV/Excel export for customer info and service records backup / 支持导出 CSV / Excel 备份客户信息和服务记录

## 🔄 User Workflows / 用户流程

### Customer Check-in Process / 客人填写流程
1. **QR Code Store Access** / **扫码进入店铺页面** - Scan store QR code to access `domain.com/{store_name}` / 扫描店铺二维码进入 `domain.com/{store_name}`
2. **Check-in Process** / **Check-in 签到流程**：
   - **New Customer** / **新顾客** - Fill complete intake form with all required information / 填写完整的 intake form，包含所有必需信息
   - **Returning Customer** / **老顾客** - Search by name + birthday, then update necessary information / 通过姓名+生日搜索，然后更新必要信息
3. **Submission Complete** / **提交完成** - System shows "Check-in successful" / 系统提示"签到成功"

### Store Owner Management Process / 店主管理流程
1. **Login to Admin Panel** / **登录后台** - Login with username + password / 使用用户名+密码登录
2. **Store Management** / **店铺管理** - Manage store information, generate QR codes / 管理店铺信息，生成二维码
3. **Customer Management** / **客户管理** - Query, delete, export customer information / 查询、删除、导出客户信息

## 🎯 MVP Feature Scope / MVP 功能范围

| Module / 模块 | MVP Included / MVP 包含 | Notes / 备注 |
|------|----------|------|
| New Customer Complete Form / 新客户完整表单 | ✅ | Complete info + signature / 完整信息 + 签名 |
| Returning Customer Quick Check-in / 老客户快速签到 | ✅ | Name + birthday search / 名字 + 生日搜索 |
| Store Owner Admin Login / 店主后台登录 | ✅ | Single account only / 单账号即可 |
| Store QR Code Generation / 店铺二维码生成 | ✅ | Auto-generate QR code PNG / 自动生成二维码 PNG |
| Customer Query/Delete / 客户查询/删除 | ✅ | Basic query functionality / 基础查询功能 |
| Customer Export / 客户导出 | ✅ | CSV or PDF export / CSV 或者 PDF 导出 |
| Multi-language Support / 多语言支持 | ✅ | Future version expansion / 未来版本可扩展 |

## 📝 License / 许可证

MIT License

## 📞 Support / 支持

For questions or suggestions, please contact us through: / 如有问题或建议，请通过以下方式联系：
- Create an Issue / 创建 Issue
- Send email to project maintainers / 发送邮件至项目维护者

---

**Note** / **注意**: This project is specifically designed for the massage shop industry, ensuring compliance with Florida legal and regulatory requirements. Before using in production, please ensure all data storage and processing comply with local laws and privacy protection requirements. / 本项目专为按摩店行业设计，确保符合佛罗里达州相关法律法规要求。在生产环境使用前，请确保所有数据存储和处理符合当地法律和隐私保护要求。
