# Project Based Internship - Kimia Farma Big Data Analytics x Rakamin Academy

## Table of Contents
- [About Program](#about-program)
- [About Kimia Farma](#about-kimia-farma)
- [About Rakamin Academy](#about-rakamin-academy)
- [About Project](#about-project)
  - [Dataset](#dataset-)
  - [Tools 🛠️](#tools-%EF%B8%8F)
  - [Tasks](#tasks-)
  - [Results](#results)


## About Program
<p align="justify">
The Project-Based Internship Program, a collaboration between Rakamin Academy and Kimia Farma Big Data Analytics, is a self-development and career acceleration initiative designed for those interested in pursuing the role of Big Data Analytics at Kimia Farma. This program provides foundational learning resources, including Article Reviews (reading materials) and Company Coaching Videos (learning videos), to introduce participants to the competencies and skills required for a Big Data Analytics professional in the company. In addition to the materials, participants will be evaluated weekly through Task assignments and will complete a final project that will serve as their portfolio for this program.
</p>

## About Kimia Farma
<p align="center">
  <img src="https://github.com/user-attachments/assets/ff0199ba-8528-4a16-b4d4-6ff76456a129" alt="logo-removebg-preview">
</p>

<p align="justify">
Founded in 1817 by the Dutch East Indies government, Kimia Farma is Indonesia's first pharmaceutical company. Initially named NV Chemicalien Handle Rathkamp & Co, it was nationalized in 1958 and renamed PNF Bhinneka Kimia Farma. The company transitioned to PT Kimia Farma (Persero) in 1971 and became a publicly listed company in 2001, establishing itself as an integrated healthcare provider contributing significantly to Indonesia's health sector.

In 2020, 90.025% of Kimia Farma's shares were transferred to PT Bio Farma (Persero), forming the State-Owned Pharmaceutical Holding. Along with this restructuring, the company’s name changed to PT Kimia Farma Tbk. With decades of experience, Kimia Farma continues to play a vital role in national health development.

website : [kimiafarma.co.id](https://www.kimiafarma.co.id/)
</p>

## About Rakamin Academy
<p align="center">
  <img src="https://github.com/user-attachments/assets/de2ace4f-e08d-4158-934f-cb1998424045" alt="logo_rakamin-71bcd472-2d26-48e1-a544-4912cb59fb2d">
</p>

<p align="justify">
Rakamin Academy, founded in June 2020 by CEO Andika Deni Prasetya, was established to bridge the gap between industry demands and the skills and knowledge of school and university graduates in Indonesia. With a vision to create an inclusive and impactful educational ecosystem that improves societal well-being, Rakamin Academy offers affordable, accessible programs designed to empower individuals to develop and achieve better career opportunities. This commitment is reflected in its digital-based programs, including courses, project-based internships, and intensive bootcamps in high-demand fields like Data Science and Digital Marketing.

Over the past three years, Rakamin Academy has expanded its offerings to include services like consulting, talent development, and recruitment under Rakamin Career Solutions. Supported by a strong leadership team, Rakamin has collaborated with over 150 partner organizations and numerous universities, solidifying its role as a key player in fostering talent development and meeting Indonesia’s industry needs.

website : [rakamin.com](https://www.rakamin.com)
</p>

## About Project
<p align="justify">
As Big Data Analytics Interns at Kimia Farma, our role involves tackling various challenges that demand a deep understanding of data and strong analytical skills. One of our key projects will be analyzing Kimia Farma's business performance from 2020 to 2023.
</p>

### Dataset 📊
In this project, we will receive 4 CSV tables.
- **kf_final_transaction.csv** : customer transaction details
- **kf_inventory.csv** : product inventory stocks
- **kf_kantor_cabang.csv** : branch store details
- **kf_product.csv** : product details

### Tools 🛠️
In this project, we will use several tools, including:
- **Google BigQuery**: for querying tables,
- **Google Looker Studio**: for creating visualization dashboards,
- **YouTube**: for video presentations,
- **GitHub**: for storing query files and results,
- **Microsoft PowerPoint**: for presentation files of our work
  
### Tasks 🎯
- In this project, you are tasked with importing the provided datasets (`Dataset.rar`) into tables in BigQuery. The table names should match the dataset names, but without the ".csv" extension.
- you are also required to create an analysis table based on aggregated results from the four previously imported tables. The following columns are mandatory for the analysis table:
  - `transaction_id`: transaction ID code,
  - `date`: the date the transaction occurred,
  - `branch_id`: Kimia Farma branch ID code,
  - `branch_name`: name of the Kimia Farma branch,
  - `kota`: city where the Kimia Farma branch is located,
  - `provinsi`: province where the Kimia Farma branch is located,
  - `rating_cabang`: customer rating for the Kimia Farma branch,
  - `customer_name`: name of the customer making the transaction,
  - `product_id`: code for the medicine product,
  - `product_name`: name of the medicine product,
  - `actual_price`: price of the medicine,
  - `discount_percentage`: discount percentage applied to the medicine,
  - `gross_profit_percentage`: gross profit percentage expected from the medicine based on the following conditions:
    - `Price` <= Rp 50,000 -> profit 10%
    - `Price` > Rp 50,000 - 100,000 -> profit 15%
    - `Price` > Rp 100,000 - 300,000 -> profit 20%
    - `Price` > Rp 300,000 - 500,000 -> profit 25%
    - `Price` > Rp 500,000 -> profit 30%,
   - `nett_sales`: price after the discount,
   - `nett_profit`: profit earned by Kimia Farma,
   - `rating_transaksi`: customer rating for the transaction.
- In this project, you are required to create a performance analysis dashboard for Kimia Farma from 2020-2023 in Google Looker Studio. This dashboard should be based on the analysis table you previously created in BigQuery, so you will need to connect that table to Google Looker Studio. You are free to design the dashboard according to your creativity, but it must include the following:
  - **Dashboard Title**
  - **Dashboard Summary**
  - **Filter Control**
  - **Data Snapshot**
  - **Comparison of Kimia Farma’s revenue year-over-year**
  - **Top 10 branches by total transactions in each province**
  - **Top 10 branches by net sales in each province**
  - **Top 5 branches with the highest ratings but lowest transaction ratings**
  - **Indonesia's Geo Map showing total profit by province**
  - **Additional analysis that you can explore**

### Results
#### BigQuery 📊
The `SQL and Result.rar` file contains the following SQL and CSV files:  
- **kf_analisa_suyanto.sql**: SQL syntax for the `analisa` table  
- **kf_analisa_suyanto.csv**: CSV file containing the result of the `kf_analisa_suyanto.sql` file  
- **kf_inventory_suyanto.sql**: SQL syntax for the `inventory` table  
- **kf_inventory_suyanto.csv**: CSV file containing the result of the `kf_inventory_suyanto.sql` file  

#### Google Looker Studio : Dashboard 📈
link : [Google Looker Studio : Dashboard](https://lookerstudio.google.com/s/pY2dIJBmflo)
<p align="center">
  <img src="https://github.com/user-attachments/assets/891e5109-8808-4829-a3fd-0a0e4b6e80d2" alt="Overview Page">
  <img src="https://github.com/user-attachments/assets/b80e26f5-22ad-4cca-a95f-69073e9b4645" alt="Detailed Page">
  <img src="https://github.com/user-attachments/assets/b8395184-523a-4ad8-9b64-674c6abc001c" alt="Inventory Page">
</p>

#### Youtube 🎥
link : [Youtube : Presentation Video](https://youtu.be/RxbwlvBtqCg)

#### Microsoft Power Point
file name : `FinalTask_KimiaFarma_BDA_Suyanto.pptx`

#### GitHub Repository 📁
Link : [PBI-Kimia-Farma-Dec-2024](https://github.com/Yuandro/PBI-Kimia-Farma-Dec-2024)


## Let's Connect! 🌐  
- [LinkedIn](https://www.linkedin.com/in/suyanto-zhang/)   

<p align="center">
  🚀 Happy Coding! 🌟
</p>


