📘 iot-realtime
======================

Panduan ini berisi langkah-langkah untuk menyiapkan environment Python serta menjalankan aplikasi Streamlit untuk proyek **iot-realtime**.

-------------------------------------

## ✅ 1. Cek Versi Python & PIP

Pastikan Python dan PIP sudah terinstall:

    python --version
    pip --version

**Versi Python yang digunakan dalam proyek ini:**

    Python 3.11.4

-------------------------------------

## 📦 2. Install Dependencies / Requirements

Install seluruh dependency:

    python -m pip install streamlit pandas numpy plotly paho-mqtt joblib streamlit-autorefresh

**Library yang digunakan:**
- streamlit — Dashboard web interaktif  
- pandas — Manipulasi data  
- numpy — Perhitungan numerik  
- plotly — Visualisasi data interaktif  
- paho-mqtt — komunikasi MQTT  
- joblib — Load/save model/data  
- streamlit-autorefresh — Auto refresh streamlit  

-------------------------------------

## 🚀 3. Menjalankan Aplikasi Streamlit

Untuk menjalankan:

    streamlit run app.py

Aplikasi akan berjalan di browser pada:

    http://localhost:8501

-------------------------------------

## 📝 Catatan Tambahan

- Jika menggunakan virtual environment, pastikan sudah diaktifkan.
- Jika terjadi error module not found, ulangi instalasi dependency.
- Pastikan file `app.py` berada di direktori utama proyek ini.

-------------------------------------
