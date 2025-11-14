#stub matching
# 📡 Comparison of Single and Double Stub Matching  
### Transmission Lines – Skill Assessment II  
---

## 🔷 Introduction  
Impedance matching ensures:
- Maximum power transfer  
- Minimum signal reflections  
- Stable RF communication  

Stub matching is commonly used in:
- Wi-Fi routers  
- 5G repeaters  
- Satellite links  
- Microwave circuits  

We will compare **Single Stub Matching** and **Double Stub Matching** with **real-time engineering examples** and **diagrams**.

---

# 🟦 Single Stub Matching

## 📘 Real-Time Example: Wi-Fi Router PCB Antenna
Inside a Wi-Fi router, the antenna impedance is **fixed and known**.  
A **single microstrip stub** is printed on the PCB to match the 50Ω transmission line.

- Simple  
- Low cost  
- Suitable for **constant, stable antenna loads**

---

## 📐 Diagram – Single Stub Matching
<img width="962" height="639" alt="image" src="https://github.com/user-attachments/assets/2c1e2832-4f3c-4746-9364-05f66d543380" />

(Example diagram: Load → Transmission Line → Stub)

---

# 🟩 Double Stub Matching

## 📘 Real-Time Example: Outdoor 5G Repeater
5G repeaters face **changing** impedance due to:
- Rain  
- Humidity  
- Temperature  
- Antenna aging  

So they use **double stub matching**, which:
- Adjusts without shifting stub position  
- Works for varying/unknown loads  
- Offers high flexibility

---

## 📐 Diagram – Double Stub Matching

<img width="942" height="616" alt="image" src="https://github.com/user-attachments/assets/02b8a360-6379-41e9-b103-65def4dd1f90" />

---

# 📊 Comparison Table

| Feature | Single Stub | Double Stub |
|--------|-------------|-------------|
| No. of Stubs | 1 | 2 |
| Flexibility | Low | High |
| Suitable for Varying Loads | ❌ No | ✔ Yes |
| Complexity | Low | Medium |
| Cost | Low | Medium |
| Tunability | Limited | High |
<img width="972" height="645" alt="image" src="https://github.com/user-attachments/assets/3ccb8371-d2d5-425a-aee9-fc7fceef22ce" />

---

# 🧮 Numerical Problem – Single Stub Matching

**Given:**  
- Load: 30 + j40 Ω  
- Line impedance: 50 Ω  

**Normalize:**  
zL = (30 + j40) / 50 = 0.6 + j0.8

**Final results (Smith chart):**
- Stub position → **0.155 λ**  
- Stub length → **0.088 λ (short-circuited)**  
<img width="866" height="742" alt="image" src="https://github.com/user-attachments/assets/cb87e9ed-e5f6-4d27-85b3-ca2e0d2485e6" />

---

# 🧮 Numerical Problem – Double Stub Matching

**Given:**  
- ZL = 25 + j30 Ω  
- Z0 = 50 Ω  
- Stub spacing = λ/8  

**Normalize:**  
zL = 0.5 + j0.6

**Final results:**  
- Stub 1 length → **0.092 λ**  
- Stub 2 length → **0.128 λ**
<img width="636" height="633" alt="image" src="https://github.com/user-attachments/assets/3063ed1c-6c83-4f2b-b0e6-0e35d1326348" />

---

# 📝 Conclusion
- **Single Stub Matching** → Best for *fixed loads* (e.g., Wi-Fi router antennas).  
- **Double Stub Matching** → Best for *varying loads* (e.g., 5G outdoor repeaters).  

Stub matching is a practical and widely used method to achieve impedance matching in RF systems.

---

