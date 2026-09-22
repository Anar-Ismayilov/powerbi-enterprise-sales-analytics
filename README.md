# 🚀 My First Power BI Project: Enterprise Sales & Inventory Analytics

Welcome to my **first-end-to-end Power BI project**! This repository showcases my journey into business intelligence, data modeling, and dashboard development, focusing on transforming raw business data into actionable insights.

---

## 🏗️ Project Architecture & Data Flow

The project follows a structured data transformation and modeling approach, divided into clear logical layers:

* **01_stage (Raw Data Layer):** Contains raw extracted tables including orders, customer master data, invoices, campaigns, and inventory records (`Address`, `CUST_MASTER`, `INVOICES`, `ORDERS_2025`, `ORDERS_2026`, etc.).
* **02_Dimensions (Dimension Tables):** Cleaned and structured dimensional tables (`dim_customer`, `dim_product`, `dim_order_junk`, `dim_cities`, `dim_campaing`) serving as the descriptive context for business analysis.
* **03_facts (Fact Tables):** Transactional and operational tables (`fact_sales`, `fact_inventory`, `fact_promotion`, `fact_campaing`, `fact_order_process`, `fact_sales_targets`) capturing core metrics and events.
* **04_Support / Security:** Houses security configurations (`security` table) and supporting auxiliary queries (`channels`).

---

## 🛠️ Key Technical Implementations

* **Power Query Transformations:** Cleaned, merged, renamed, and structured raw tables to establish a clean relational model.
* **Star Schema Design:** Built robust relationships between Dimension tables and Fact tables to optimize query performance and reporting accuracy.
* **DAX Calculations:** Developed custom measures and calculated columns for advanced business metrics.
* **Row-Level Security (RLS):** Implemented security roles using the `security` table to restrict data access based on user permissions.

---

## 📂 Repository Contents

* `portfolio.pbix`: The final, fully functional Power BI report file containing data models, relationships, DAX measures, and visual dashboards.
* `Raw_Data/`: Sample and source tables utilized during the ingestion phase.

* # 🚀 İlk Power BI Layihəm: Korporativ Satış və Anbar Analitikası

Bu, mənim **ilk hərtərəfli (end-to-end) Power BI layihəmdir**! Bu repository xam məlumatların biznes üçün faydalı hesabatlara və analitikaya çevrilməsi prosesini, eləcə də məlumatların modelləşdirilməsi bacarıqlarımı nümayiş etdirir.

---

## 🏗️ Layihə Arxitekturası və Məlumat Axını

Layihə məlumatların təmizlənməsi və modelləşdirilməsi üçün məntiqi qatlara bölünmüşdür:

* **01_stage (Xam Məlumat Qatı):** Sifarişlər, müştəri məlumatları, qaimələr, kampaniyalar və anbar qeydləri daxil olmaqla xam cədvəlləri ehtiva edir (`Address`, `CUST_MASTER`, `INVOICES`, `ORDERS_2025`, `ORDERS_2026` və s.).
* **02_Dimensions (Ölçü Cədvəlləri):** Biznes təhlili üçün təsviri kontekst yaradan təmizlənmiş ölçü cədvəlləri (`dim_customer`, `dim_product`, `dim_order_junk`, `dim_cities`, `dim_campaing`).
* **03_facts (Fakt Cədvəlləri):** Əsas göstəriciləri və əməliyyatları əks etdirən cədvəllər (`fact_sales`, `fact_inventory`, `fact_promotion`, `fact_campaing`, `fact_order_process`, `fact_sales_targets`).
* **04_Support / Security:** Təhlükəsizlik konfiqurasiyaları (`security` cədvəli) və köməkçi sorğular (`channels`).

---

## 🛠️ Texniki Xüsusiyyətlər və Görülən İşlər

* **Power Query Çevrilmələri:** Xam cədvəllərin birləşdirilməsi (merge), adlarının dəyişdirilməsi, təmizlənməsi və strukturlaşdırılması.
* **Ulduz Sxemi (Star Schema) Dizaynı:** Hesabat sürətini və dəqiqliyini artırmaq üçün Ölçü və Fakt cədvəlləri arasında güclü əlaqələrin qurulması.
* **DAX Hesablamaları:** Qabaqcıl biznes göstəriciləri üçün fərdi ölçülərin (measures) yazılması.
* **Səviyyəli Təhlükəsizlik (Row-Level Security - RLS):** İstifadəçi icazələrinə əsasən məlumat girişini məhdudlaşdırmaq üçün təhlükəsizlik rollarının tətbiqi.

---

## 📂 Repository Məzmunu

* `portfolio.pbix`: Məlumat modelləri, əlaqələr, DAX düsturları və vizual dashboard-ları özündə birləşdirən son Power BI hesabat faylı.
* `Raw_Data/`: İlkin mərhələdə istifadə olunan xam mənbə cədvəlləri.
