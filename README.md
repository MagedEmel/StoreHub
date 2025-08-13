# 🛒 StoreHub

**StoreHub** هو مشروع متكامل لإدارة المتاجر الإلكترونية، مبني باستخدام **Django** مع العديد من الخصائص الحديثة زي إدارة المنتجات، الطلبات، عربات التسوق، تقييمات المستخدمين، داشبورد للإدارة، دعم متعدد اللغات، وضع ليلي، وغيرها!

![StoreHub Banner](https://via.placeholder.com/1200x400.png?text=StoreHub+-+Smart+Store+Management) <!-- تقدر تعدل الصورة لاحقاً -->

---

## ✨ Badges

![Django](https://img.shields.io/badge/Django-2.2.4-green)
![License](https://img.shields.io/badge/license-MIT-blue)
![Last Commit](https://img.shields.io/github/last-commit/fadya5323/storehub)

---

## 🚀 البدء (Getting Started)

### 1. إنشاء البيئة الافتراضية

```bash
pip install virtualenv
virtualenv env
```

### 2. تفعيل البيئة الافتراضية

- **على Mac/Linux:**

```bash
source env/bin/activate
```

- **على Windows:**

```bash
env\Scripts\activate
```

### 3. تثبيت المتطلبات

```bash
pip install -r requirements.txt
```

🔋 **ملاحظة مهمة:**
استخدم الإصدارات دي بالظبط لتفادي مشاكل تعارض الإصدارات:

```bash
pip install Django==2.2.4
python -m pip install django-allauth==0.40.0
pip install django-crispy-forms==1.7.2
pip install django-countries==5.5
pip install stripe==2.37.1
pip install Pillow
```

---

## 🛠️ أوامر إدارة المشروع

- إنشاء ملفات الهجرة:

```bash
python manage.py makemigrations
```

- تنفيذ الهجرة:

```bash
python manage.py migrate
```

- تشغيل السيرفر:

```bash
python manage.py runserver
```

---

## 🧹 المميزات (Features)

- تسجيل ودخول مستخدمين مع تحقق البريد الإلكتروني
- إدارة المنتجات (إضافة - تعديل - حذف)
- إدارة الطلبات مع تتبع الحالة
- تقييم ومراجعة المنتجات بنجوم ⭐
- إدارة العربة وعمليات الدفع باستخدام Stripe
- داشبورد للإدارة Admin Dashboard
- داشبورد خاص بالمندوبين Delivery Agents
- إشعارات وتنبيهات Realtime
- دعم تعدد اللغات 🌍
- وضع ليلي (Dark Mode) 🌑
- تصفح آمن مع حماية من CSRF, XSS, SQL Injection
- التوافق مع معايير حماية البيانات GDPR
- دعم Wishlist المفضلة ❤️
- نظام تقييم للصنايعية والعملاء
- تقارير وتحليلات Analytics

---

## 📂 هيكلية المشروع (Project Structure)

```
storehub/
|
|├── manage.py
|├── env/                  # بيئة العمل الافتراضية
|├── requirements.txt
|├── storehub/              # ملفات إعدادات المشروع
|    |
|    ├── settings.py
|    ├── urls.py
|    └── wsgi.py
|├── products/              # تطبيق إدارة المنتجات
|├── orders/                # تطبيق إدارة الطلبات
|├── users/                 # تطبيق تسجيل وإدارة المستخدمين
|├── cart/                  # تطبيق إدارة العربة
|├── reviews/               # تطبيق إدارة التقييمات
└── templates/             # ملفات الـ HTML
```

---

## ⚙️ تكنولوجيا مستخدمة (Tech Stack)

- **Backend:** Django
- **Frontend:** HTML, CSS, Bootstrap
- **Database:** SQL Server
- **APIs:** Stripe API
- **Authentication:** Django Allauth
- **Other Libraries:** Pillow, django-countries, crispy-forms

---

## 🧑‍💻 مطورين المشروع

> **Maged Emel Sobhy**

- GitHub: [MagedEmel](https://github.com/MagedEmel)
- LinkedIn: [Maged Emel Sobhy](#)
- Email: magedemel007@gmail.com

> **Mariam Ayman Saeed**
- GitHub: [[]]
---

