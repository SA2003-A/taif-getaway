
# Taif Getaway Recommender System

نموذج توصية سياحي يعتمد على التصفية التعاونية (Collaborative Filtering) لتقديم اقتراحات مخصصة لزوار مدينة الطائف بناءً على تفضيلاتهم وسلوكيات المستخدمين الآخرين.

---

## محتويات المشروع
- model.ipynb : كود نموذج التوصية
- data.csv : البيانات المستخدمة (وهمية أو مأخوذة من Foursquare)
- recommendations.csv : نتائج التوصيات لكل مستخدم
- README.md : هذا الملف التوضيحي
- exploration.py أو eda.ipynb: تحليل واستكشاف البيانات

---

## التقنيات المستخدمة
- Python
- Pandas, NumPy
- Surprise Library (SVD)
- Google Colab
- Foursquare API (لجمع البيانات)
- Git & GitHub

---

## آلية النموذج
1. جمع البيانات عن الأماكن السياحية من Foursquare API.
2. تمثيل تفضيلات المستخدمين على شكل مصفوفة.
3. استخدام خوارزمية SVD من مكتبة Surprise لبناء نموذج توصية.
4. إعطاء اقتراحات مخصصة لكل مستخدم بناءً على سلوك المستخدمين الآخرين.

---
## فريق العمل
- أعضاء فريق Taif Getaway
---

## طريقة التشغيل
```bash
git clone https://github.com/username/taif-getaway-model.git
cd taif-getaway-model
