# 🚚 Supply Chain Data Analysis Dashboard

![Python](https://img.shields.io/badge/Python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)
![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![Figma](https://img.shields.io/badge/Figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white)

---

An end-to-end Supply Chain & Logistics Analytics project leveraging **Python** for data cleaning, transformation, and ETL processes, followed by **Power BI** for interactive data visualization, dynamic business intelligence dashboards, and performance monitoring.

---

## 📌 Business Objectives & Key Metrics
The goal of this project is to evaluate supply chain efficiency, logistics performance, delivery statuses, product profitability, and customer purchasing behavior to optimize operational workflows and maximize profit margins.

### 📊 Executive KPI Summary:
* **Total Sales:** $37M
* **Total Orders:** 66K
* **Total Customers:** 21K
* **Total Items Sold:** 181K
* **Total Profit:** $4M
* **Profit Margin %:** 11%
* **On-Time Delivery %:** 45.2%
* **Late Delivery %:** 55%
* **Average Order Value (AOV):** $559

---

## 🛠️ Tools & Technologies Used
* **Python (Pandas, NumPy):** Automated data extraction, ETL pipelines, handling missing data, and cleaning.
* **Power BI:** Multi-page dashboard construction, DAX measures, star schema modeling, and dynamic tooltips.
* **Figma:** Dashboard wireframing, dark theme visual structure, and UI layout design.

---

## 🗺️ Dashboard Structure & Pages

### 1️⃣ 🏠 Home Page
* **Purpose:** High-impact visual landing page providing seamless navigation across all dashboard sections.
* **Key Features:** Clean UI dark layout featuring project title, core tech stack, and quick navigation.

![Home Page](Home%20.png)

---

### 2️⃣ 📊 Overview Page
* **Purpose:** High-level executive overview of global business performance and high-impact operational metrics.
* **Key Visuals:** Sales trends by month, delivery status splits, departmental sales, and regional market distribution.

![Overview Page](Overview.png)

---

### 3️⃣ 📦 Sales & Orders Page
* **Purpose:** Deep dive into order volumes, average order values, shipping class distributions, and customer segment revenue contribution.
* **Key Visuals:** Shipping mode breakdown, monthly AOV trends, customer segment share, and category profit margins.

![Sales & Orders Page](Sales%20&%20Orders.png)

---

### 4️⃣ 👥 Customer Analysis Page
* **Purpose:** Comprehensive analysis of customer demographics, retention rates, acquisition trends, and purchasing patterns.
* **Key Visuals:** Geographic customer map, acquisition trends, customer segment spending, and top individual buyers.

![Customer Analysis Page](Customer.png)

---

### 5️⃣ 💰 Product & Profitability Page
* **Purpose:** Financial performance evaluation focused on category margins, shipping mode profits, and top profit-generating inventory.
* **Key Visuals:** Shipping mode profit split, market profitability funnel, department treemaps, and top profit-driving products.

![Product & Profitability Page](product%20&%20profitability.png)

---

### 6️⃣ 🚚 Delivery & Supply Chain Page
* **Purpose:** Monitoring supply chain logistics, identifying delivery delays, evaluating vendor performance, and detecting fulfillment bottlenecks.
* **Key Visuals:** Delay days tracking, delivery status by shipping class, actual vs. scheduled transit times, and regional late delivery rates.

![Delivery & Supply Chain Page](Delivery%20&%20Supply%20Chain.png)

---

### 7️⃣ 💡 Dynamic Tooltips Page
* **Purpose:** Custom interactive hover tooltips embedded across report visuals to provide quick context summaries without navigating away from active dashboards.

![Tooltips Page](Tooltips.png)

---

## 💡 Recommendations & Actionable Insights (التوصيات الإستراتيجية)

1. **معالجة ارتفاع نسبة تأخير التوصيل (Late Delivery Rate):**
   * تصل نسبة التأخير في التسليم إلى **55%**، وهو معدل مرتفع جداً يتطلب مراجعة فورية لاتفاقيات مستوى الخدمة (SLAs) مع شركات الشحن والتوصيل.
   * التركيز على تحسين عمليات التوصيل في الأسواق الأكثر تأثراً بالتأخير، وخاصة منطقتي **Pacific Asia (55.30%)** و **Europe (54.95%)**.
   * إعادة معالجة وإعادة تنظيم خطوط الشحن والتأخير المرتفع في أقسام مثل **Pet Shop (58.94%)** و **Book Shop (56.54%)**.

2. **تحسين استراتيجيات طرق الشحن (Shipping Modes):**
   * يعتمد معظم العملاء على الشحن القياسي (**Standard Class**) بحجم طلبات يصل إلى 39K طلب. يجب إعادة توزيع الضغط التشغيلي أو تحفيز العملاء لاستخدام طرق شحن أسرع وأكثر كفاءة.
   * خيار الشحن في نفس اليوم (**Same Day**) يعاني من معدلات إلغاء وتأخير مرتفعة نسبياً مقارنة بحجمه الصغير، مما يتطلب تقييم الجدوى التشغيلية له.

3. **التركيز على القطاعات والفئات الأكثر إيراداً وربحية:**
   * قطاع الأفراد (**Consumer**) يمثل النسبة الأكبر بـ **51.91%** من إجمالي المبيعات بقيمة **19M**، لذا يُوصى بتوجيه حملات تسويقية وبرامج ولاء مخصصة لهذا القطاع.
   * قسم **Fan Shop** يتصدر باقي الأقسام بمبيعات **17,114K** وأرباح **1,834K**، بينما فئة **Fishing** تتصدر الفئات بمبيعات **6,930K** وأرباح **756K**؛ مما يوجب التأكد الدائم من توفر مخزونها وتجنب أي انقطاع.

4. **إعادة هيكلة المنتجات والأقسام ذات الأداء المنخفض:**
   * أقسام مثل **Book Shop** (مبيعات 13K / أرباح 1K) و **Pet Shop** (مبيعات 42K / أرباح 4K) تحقق عوائد ضئيلة جداً لا تتناسب مع تكاليف التشغيل والتوصيل، مما يقتضي إعادة النظر في تسعيرها أو جدوى استمرارها.
   * الحد من التكاليف التشغيلية الناتجة عن المنتجات الخاسرة التي تشكل **3%** من إجمالي المنتجات (**Loss-making Products**).

5. **معالجة الانخفاض الموسمي في الربع الأخير (Q4):**
   * يلاحظ انخفاض ملحوظ في متوسط قيمة الطلب (**Average Order Value**) وإجمالي المبيعات خلال شهري **نوفمبر وديسمبر**. يُوصى بتجهيز عروض وتخفيضات موسمية وحزم منتجات (Bundles) لرفع متوسط قيمة السلة خلال نهاية العام.

---

## 🛠️ How to Run / Open the Dashboard
1. Execute Python data prep scripts if re-processing raw datasets.
2. Download the `.pbix` file from this repository.
3. Open using **Microsoft Power BI Desktop**.
4. Use the **Home Page** dynamic buttons or sidebar navigation to explore all interactive pages.

---

### 👤 Created By:
**Ebrahim Mustafa** — *Data Analyst & BI Analyst*
