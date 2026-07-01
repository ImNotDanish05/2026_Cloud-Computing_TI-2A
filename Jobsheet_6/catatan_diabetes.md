## 1. Sangat Sehat (Prediksi kemungkinan Non-Diabetes)

```text
Pregnancies: 0
Glucose: 85
BloodPressure: 70
SkinThickness: 20
Insulin: 80
BMI: 22.5
DiabetesPedigreeFunction: 0.20
Age: 23
```

---

## 2. Masih Normal

```text
Pregnancies: 1
Glucose: 95
BloodPressure: 72
SkinThickness: 25
Insulin: 90
BMI: 24.8
DiabetesPedigreeFunction: 0.30
Age: 30
```

---

## 3. Borderline / Perlu Waspada

```text
Pregnancies: 2
Glucose: 120
BloodPressure: 80
SkinThickness: 30
Insulin: 120
BMI: 29.5
DiabetesPedigreeFunction: 0.45
Age: 38
```

---

## 4. Risiko Tinggi

```text
Pregnancies: 5
Glucose: 165
BloodPressure: 85
SkinThickness: 35
Insulin: 180
BMI: 34.2
DiabetesPedigreeFunction: 0.80
Age: 52
```

---

## 5. Sangat Berisiko / Kemungkinan Diabetes

```text
Pregnancies: 8
Glucose: 195
BloodPressure: 95
SkinThickness: 40
Insulin: 250
BMI: 41.0
DiabetesPedigreeFunction: 1.20
Age: 61
```

---

**Catatan kecil:** karena modelmu adalah hasil training Machine Learning, **tidak ada jaminan** data nomor 3, 4, atau 5 akan menghasilkan prediksi yang persis sesuai label yang kuberi. Yang hampir pasti hanya:

* Dataset 1 → biasanya **Non-Diabetes**
* Dataset 5 → biasanya **Diabetes**

Kalau buat demo di depan dosen, aku biasanya siapkan **2 data yang sudah benar-benar dites** (satu pasti Non-Diabetes dan satu pasti Diabetes), jadi hasilnya tidak meleset saat presentasi.
