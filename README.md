# Format_data_thc — Data Cleaning & Normalization Tool

Utility Python untuk **merapikan, menggabungkan, dan menstandarkan format data THC dari berbagai sumber** agar siap dipakai untuk analisis, reporting, dan kebutuhan audit.

> Target pengguna: Internal Audit / Data Analyst  
> Use case: preprocessing data operasional sebelum validasi, rekonsiliasi, dan analisis anomali.

---

## 🎯 Problem Statement
Data THC sering berasal dari beberapa sumber dengan format yang tidak konsisten:
- nama kolom berbeda
- tipe data tidak seragam (tanggal, numerik, string)
- encoding/delimiter berbeda
- duplikasi baris dan missing values

Hal ini memperlambat pekerjaan audit/analitik dan meningkatkan risiko human error jika dirapikan manual (Excel).

**Tool ini mengotomatisasi proses standardisasi tersebut.**

---

## 🚀 Features
- Normalisasi nama kolom ke schema baku  
- Parsing & standardisasi format tanggal  
- Pembersihan nilai kosong (null handling)  
- Deduplikasi data  
- Merge beberapa file input menjadi satu dataset rapi  
- Output siap dipakai untuk analisis / pelaporan

---

## 🛠 Tech Stack
- Python  
- Library utama: pandas  
- Dependency lain:
    - numpy
    - streamlit
    - openpyxl
    - xlsxwriter

---

## 📁 Project Structure
