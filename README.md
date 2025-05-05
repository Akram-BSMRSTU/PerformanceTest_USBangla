# 🚀 Performance Testing with Apache JMeter

This repository contains performance testing work using **Apache JMeter**. It demonstrates how to design and execute load tests, analyze results, and generate performance reports. The tests are applied to the ✈️ [US-Bangla Airlines](https://www.usbair.com) website.

---

## 🧩 Features

- 🛠️ **Test Plan Setup** – Includes detailed `.jmx` files for structured performance testing  
- 📈 **Report Generation** – Automated HTML reports showing response times, throughput & errors  
- 🔁 **Scalability Testing** – Simulate different load levels to evaluate system behavior  

---

## 🧰 Tools & Technologies

- 🧪 **Apache JMeter** – Core tool for test creation & execution  
- 🗂️ **GitHub** – Version control & collaboration  
- 🌐 **Web Browsers** – For viewing generated HTML reports  

---

## 🎯 Project Objectives

- 📊 Measure application performance under varying user loads  
- 🔍 Identify performance bottlenecks and slow response areas  
- ⚙️ Optimize application and server configuration for better resource utilization  

---

## 📁 Repository Structure

| File Name              | Description                                      |
|------------------------|--------------------------------------------------|
| `us_bangla_100.html`   | 📄 JMeter performance report for 100 virtual users |
| `us_bangla_500.html`   | 📄 JMeter performance report for 500 virtual users |
| `us_bangla_500.jmx`    | 🧪 JMeter test plan for simulating 500 users      |
| `README.md`            | 📘 This project documentation                    |

---

## 📊 JMeter Performance Reports

These HTML reports summarize key metrics from JMeter test runs:

### 🔹 [us_bangla_100.html](us_bangla_100.html)
- Simulates 100 virtual users accessing the US-Bangla website
- Reports include:
  - ✅ Success rate
  - ⏱️ Average response time
  - 📉 Response time distribution
  - 📈 Requests per second

### 🔹 [us_bangla_500.html](us_bangla_500.html)
- Simulates 500 concurrent users
- Highlights system scalability and performance bottlenecks under high load
- Useful for stress testing and tuning

🖼️ **Screenshot Preview:**  

![apdex](https://github.com/user-attachments/assets/ec17502e-c9b0-4982-b215-79a514396fbe)

![tps](https://github.com/user-attachments/assets/48fd63fd-cc42-4068-a58b-eb4c22de1308)

![Response Time Percentiles](https://github.com/user-attachments/assets/8cd46887-fa02-4d03-9bb2-f52c9909f9ce)

![error](https://github.com/user-attachments/assets/651a951d-3336-41dc-a03e-7f0e0e9ac19b)

> 📌 Open the `.html` files in a browser to explore the interactive reports.

---

## Contributions
Contributions are welcome! If you'd like to enhance this project, please fork the repository and submit a pull request.

Happy Testing:)
