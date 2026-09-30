# 🚚 Supply Chain Data Analysis Dashboard

An end-to-end Supply Chain & Logistics Analytics project leveraging **Python** for data processing and ETL, and **Power BI** for interactive data visualization, business intelligence, and performance monitoring.

---

## 👨‍💻 Project Overview
* **Data Analyst:** Ebrahim Mostafa
* **Tools Used:** Python | Power BI | SQL
* **Project Type:** Supply Chain, Logistics, Sales & Customer Analytics

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

## 🗺️ Dashboard Structure & Pages

### 1. 🏠 Home Page
* **Purpose:** High-impact visual landing page providing seamless navigation across all dashboard sections.
* **Features:** Direct interactive buttons to jump into Overview, Sales & Orders, Customer Analysis, Product & Profitability, and Delivery & Supply Chain pages.

### 2. 📊 Overview
* **Purpose:** High-level executive overview of global business performance.
* **Key Visuals:**
  * **Top KPIs:** Total Sales ($37M), Total Orders (66K), Total Customers (21K), Items Sold (181K), Total Profit ($4M), On-Time Delivery % (45.2%).
  * **Total Sales by Month:** Monthly trend analysis highlighting sales peak in early/mid-year and decline in Q4.
  * **Total Orders by Delivery Status:** Breakdown of order fulfillment (Late delivery, Advance shipping, Shipping on time, Shipping canceled).
  * **Total Sales by Department Name:** Top performing departments led by Fan Shop ($17,114K) and Apparel ($7,976K).
  * **Total Sales by Market:** Regional sales performance with Europe ($10.9M) and LATAM ($10.3M) as top markets.
  * **Total Sales by Category Name:** Top category performance led by Fishing ($6,930K) and Cleats ($4,432K).

### 3. 📦 Sales & Orders
* **Purpose:** Deep dive into order volumes, average order values, and customer segment revenue distribution.
* **Key Visuals:**
  * **KPI Cards:** Sales, Orders, AOV ($559), Profit, Profit Margin % (11%).
  * **Total Orders by Shipping Mode:** Order volume distribution across Standard Class (39K), Second Class (13K), First Class (10K), and Same Day (4K).
  * **Average Order Value by Month:** Trend line showing monthly AOV variations.
  * **Total Sales by Customer Segment:** Segment contribution with Consumer leading at $19M (51.91%), followed by Corporate at $11M (30.36%) and Home Office at $7M (17.73%).
  * **Top 5 Profit Margin % by Category:** Category profitability rankings led by Golf Bags & Carts (17%).
  * **Total Profit by Department Name:** Profit breakdown per department.

### 4. 👥 Customer Analysis
* **Purpose:** Understanding customer demographics, repeat rate, acquisition trends, and spending power.
* **Key Visuals:**
  * **Customer KPIs:** Total Customers (21K), Avg Orders/Customer (3.18), Avg Sales/Customer ($1.78K), Avg Profit/Customer ($192.08), Repeat Customers % (57%).
  * **Customers by Country:** Global geographic distribution map.
  * **New Customers by Month:** Acquisition trend throughout the year.
  * **Total Customers by Segment:** Donut chart breakdown by Consumer, Corporate, and Home Office.
  * **Avg Sales per Customer by Segment:** Comparison of spending power across segments.
  * **Top 10 Customers by Sales:** Identification of top revenue-generating individual customers.

### 5. 💰 Product & Profitability
* **Purpose:** Financial analysis focusing on category margins, shipping mode profitability, and top profit drivers.
* **Key Visuals:**
  * **Financial KPIs:** Total Profit ($4M), Profit Margin % (11%), Total Items Sold (181K), Avg Discount (10%), Loss-making Products % (3%).
  * **Profit by Shipping Mode:** Profit contribution by delivery option (Standard Class generating $2,370K).
  * **Profit by Market:** Doughnut chart detailing market profit shares.
  * **Total Profit by Category:** Waterfall/Funnel visualization of category profits (Fishing at $756K).
  * **Total Profit by Department Name:** Treemap showing relative profitability of departments.
  * **Top 10 Products by Profit:** Individual product leaderboards (Field & Stream Sportsman 16 Gun Fire Safe generating $756K).

### 6. 🚚 Delivery & Supply Chain
* **Purpose:** Supply chain operations monitoring, delivery delays, delay duration, and departmental logistics bottlenecks.
* **Key Visuals:**
  * **Logistics KPIs:** On-Time Delivery % (45.2%), Late Delivery % (55%), Avg Scheduled Days (2.93), Avg Delay Days (0.57), Canceled Orders %.
  * **Avg Delay Days by Month:** Monthly delivery delay duration tracking.
  * **Delivery Status by Shipping Mode:** Stacked bar chart showing late vs. on-time fulfillment rates per shipping option.
  * **Actual vs Scheduled Days:** Comparison across shipping classes.
  * **Late Delivery % by Market:** Identification of regional shipping issues (Pacific Asia at 55.30%, Europe at 54.95%).
  * **Late Delivery % by Department:** Departmental delay analysis (Pet Shop at 58.94%, Book Shop at 56.54%).

### 7. 💡 Interactive Tooltips Page
* **Purpose:** Provides custom dynamic tooltips across the report cards for quick context summaries (Total Sales, Total Orders, Total Profit, and Customer Segment percentages) without switching pages.

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
1. Download the `.pbix` file from this repository.
2. Open using **Microsoft Power BI Desktop**.
3. Use the **Home Page** buttons or sidebar navigation to explore all interactive pages.
