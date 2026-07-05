# RE-KnowledgeBase-
Welcome to my knowledge base for reverse engineering and malware analysis. This repository was built to be a deep and organized reference for all the concepts, functions, and techniques I encounter during my journey in this field.
# RE-KnowledgeBase (V1) 🎯
## 🗺️ خريطة المستودع (Table of Contents)

### 🪟 Windows API
* [CreateFile](Windows_API/CreateFile.md) - فتح وإنشاء قنوات الاتصال مع الكائنات.
* [VirtualAlloc](Windows_API/VirtualAlloc.md) - حجز مساحات الذاكرة ديناميكياً.
* [VirtualProtect](Windows_API/VirtualProtect.md) - تغيير صلاحيات صفحات الذاكرة.
* [IsDebuggerPresent](Windows_API/IsDebuggerPresent.md) - كشف المصححات بالطريقة القياسية.

### ⚙️ Assembly Language
* [MOV](Assembly/MOV.md) - نقل البيانات بين المسجلات والذاكرة.
* [LEA](Assembly/LEA.md) - تحميل العنوان الفعال.
* [CALL](Assembly/CALL.md) - استدعاء الدوال والتحكم في سير البرنامج.

### 📌 Persistence Techniques
* [Registry Run Keys](Persistence/Registry_Run_Keys.md)
* [Scheduled Tasks](Persistence/Scheduled_Tasks.md)

### 🌐 Networking
* [WinInet](Networking/WinInet.md)
* [WinHTTP](Networking/WinHTTP.md)

### 🔐 Cryptography & Obfuscation
* [XOR](Crypto/XOR.md)
* [AES](Crypto/AES.md)

### 🛡️ Anti-Analysis & Evasion
* [Timing Checks](AntiAnalysis/Timing_Checks.md)
* [PEB (Process Environment Block)](AntiAnalysis/PEB.md)
* [Sandbox Detection](AntiAnalysis/Sandbox_Detection.md)

---

## 📑 هيكل التوثيق الموحد
كل دالة أو مفهوم يتم توثيقه بناءً على هيكل صارم وعميق يشمل:
1. **What is it? & Why does it exist?**
2. **Parameters & Return Values**
3. **Malware vs Legitimate Usage**
4. **RE & DFIR Perspectives**
5. **Detection Opportunities & ATT&CK Mapping**
6. **Reverse Engineering Tips & Questions to Ask Yourself**

---
💡 *ملاحظة: هذا المستودع مخصص للأغراض التعليمية وبناء العقلية التحليلية فقط.*
