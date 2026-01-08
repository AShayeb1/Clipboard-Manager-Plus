# 📋 Clipboard Manager

![Image](https://github.com/user-attachments/assets/a3558cd9-c264-4e77-b4e6-889e5c754354)

## 📝 Program Idea
**Clipboard Manager** is a professional desktop application that keeps a history of everything you copy to the clipboard. It lets you quickly access and restore previously copied items with ease. The app runs in the background and automatically monitors the clipboard to save every text or link you copy.

## ✨ Main Features

### 📂 Groups Management
- **Organize items into groups** — Create custom groups to sort your texts and links
- **Automatic default group** — All copied items are saved automatically to the active group
- **Quick group switching** — Easily switch between your different groups

### 📌 Pinning & Priority
- **Pin important items** — Pin texts you want to protect from deletion
- **Pinned items appear first** — Quick access to your most important clips

### 🔍 Quick Search
- **Instant content search** — Search through all saved texts and links

### ⌨️ Keyboard Shortcuts
- **Quick open shortcut** — `Ctrl + Shift + V` to open the window instantly
- **Customizable** — You can change the shortcut from settings

### 💾 Backup & Restore
- **Full backup** — Create a complete backup of all groups and items with one click
- **Easy restore** — Restore your previous data easily with automatic app restart
- **ZIP format** — Backups are saved as compressed ZIP files for easy transfer & storage
- **Single instance protection** — Prevents running multiple instances at the same time to protect your data

### 🌍 Language Support
- 🇸🇦 Arabic
- 🇺🇸 English
- 🇫🇷 French
- 🇷🇺 Russian
- 🇨🇳 Chinese

## 🚀 How to Run

### Requirements
- **Windows 10** or newer
- **.NET 8.0 Runtime** or newer

## ⚙️ Settings
Access settings by clicking the ⚙️ icon in the app interface.

### Available Settings
| Setting                  | Description                                                  | Default Value     |
|--------------------------|--------------------------------------------------------------|-------------------|
| **Language**             | Interface language (Arabic, English, French, Russian, Chinese) | `English`         |
| **Run at startup**       | Start the program automatically with Windows                 |
| **Keyboard shortcut**    | Modifier keys + main key to open the app                     | `Ctrl + Shift + V`|
| **Backup**               | Create and restore data backups                              | -                 |

### Data Storage Location

%APPDATA%\ClipboardManager
├── groups.json    # Groups and saved items
├── settings.json  # Application settings

# 📋 Clipboard Manager

## 📝 فكرة البرنامج

**Clipboard Manager** هو تطبيق سطح مكتب احترافي يقوم بحفظ سجل لكل ما تنسخه إلى الحافظة، مما يتيح لك الوصول السريع إلى العناصر المنسوخة السابقة واستعادتها بسهولة. يعمل البرنامج في الخلفية ويراقب الحافظة تلقائياً ليحفظ كل نص أو رابط تقوم بنسخه.

## ✨ الميزات الرئيسية

### 📂 إدارة المجموعات
- **تنظيم العناصر في مجموعات** - قم بإنشاء مجموعات مخصصة لتنظيم النصوص والروابط
- **مجموعة افتراضية تلقائية** - جميع العناصر المنسوخة تُحفظ تلقائياً في المجموعة النشطة
- **التبديل السريع بين المجموعات** - انتقل بسهولة بين مجموعاتك المختلفة

### 📌 التثبيت والأولوية
- **تثبيت العناصر المهمة** - قم بتثبيت النصوص المهمة لحمايتها من الحذف
- **العناصر المثبتة تظهر أولاً** - سهولة الوصول للعناصر الأكثر أهمية

### 🔍 البحث السريع
- **بحث فوري في المحتوى** - ابحث في جميع النصوص والروابط المحفوظ

### ⌨️ اختصارات لوحة المفاتيح
- **اختصار سريع للفتح** - `Ctrl + Shift + V` لفتح النافذة بسرعة
- **قابل للتخصيص** - يمكنك تغيير الاختصار من الإعدادات

### 💾 النسخ الاحتياطي والاستعادة
- **نسخ احتياطي كامل** - قم بإنشاء نسخة احتياطية من جميع مجموعاتك وعناصرك بضغطة زر
- **استعادة سهلة** - استعد بياناتك السابقة بسهولة مع إعادة تشغيل تلقائية للبرنامج
- **حفظ بصيغة ZIP** - يتم حفظ النسخ الاحتياطية في ملفات مضغوطة لسهولة النقل والتخزين
- **منع تكرار التشغيل** - يضمن البرنامج عدم تشغيل أكثر من نسخة في نفس الوقت للحفاظ على سلامة البيانات

### 🌍 دعم اللغات
- 🇸🇦 العربية
- 🇺🇸 الإنجليزية
- 🇫🇷 الفرنسية
- 🇷🇺 الروسية
- 🇨🇳 الصينية

## 🚀 التشغيل

### المتطلبات
- نظام **Windows 10** أو أحدث
- **.NET 8.0 Runtime** أو أحدث

## ⚙️ الإعدادات

يمكن الوصول للإعدادات عبر الضغط على أيقونة ⚙️ في واجهة البرنامج.

### الإعدادات المتاحة

| الإعداد | الوصف | القيمة الافتراضية |
|---------|-------|-------------------|
| **اللغة** | لغة واجهة البرنامج (عربي، إنجليزي، فرنسي، روسي، صيني) | `English` |
| **تشغيل مع النظام** | بدء البرنامج تلقائياً مع Windows |
| **اختصار لوحة المفاتيح** | مفاتيح التعديل والمفتاح الرئيسي لفتح البرنامج | `Ctrl + Shift + V` |
| **النسخ الاحتياطي** | إنشاء واستعادة نسخ احتياطية للبيانات | - |

### مكان حفظ البيانات
```
%APPDATA%\ClipboardManager\
├── groups.json       # المجموعات والعناصر المحفوظة
├── settings.json     # إعدادات البرنامج

```

<div align="center">


</div>

