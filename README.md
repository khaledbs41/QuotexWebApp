# Quotex Signals Web App

تطبيق ويب لتحليل CSV وإظهار إشارات BUY/SELL مع SMA, RSI, Bollinger وGraph شمعي.

## نشر على Streamlit Cloud
1. أنشئ مستودع GitHub جديد.
2. ضع الملفات: app.py, requirements.txt, README.md.
3. في Streamlit Cloud اختر "New App" → repo → Branch → Deploy.
4. افتح الرابط الذي يعطيك Streamlit وابدأ رفع CSV.

## اختبار محلي
```bash
pip install -r requirements.txt
streamlit run app.py
