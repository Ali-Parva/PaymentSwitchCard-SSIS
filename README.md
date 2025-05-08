# 💳 Payment Switch Transaction ETL with SSIS

This project demonstrates a real-world **ETL pipeline** built with **SQL Server Integration Services (SSIS)** to process **bank card transactions** from multiple acceptance channels such as **ATM, POS, Internet**, and more. The goal is to load clean and structured data into a **SQL Server Data Warehouse** for downstream analysis and reporting.

---

## 🧠 Business Use Case

Banks and financial institutions receive millions of daily transactions from various channels. This solution gathers and processes these transactions from **TRC and SHP files**, stages them, and loads them into a structured **Fact table** for accurate analytics and dashboarding.

---

## 📁 Project Structure

### 📦 SSIS Packages

| # | Package Name | Description |
|--:|--------------|-------------|
| 1 | `1_Staging_Load_From_TRC_Files.dtsx` | Imports raw transaction data from **TRC files** into the staging layer. |
| 2 | `2_Fact_Load_From_TRC_Staging.dtsx` | Processes data from TRC staging and loads it into the **Fact table**. |
| 3 | `3_Staging_Load_From_SHP_Files.dtsx` | Imports raw transaction data from **SHP files** into the staging layer. |
| 4 | `4_Fact_Load_From_SHP_Staging.dtsx` | Processes data from SHP staging and loads it into the **Fact table**. |

---

## 🛠️ Technologies Used

- **SQL Server Integration Services (SSIS)**
- **SQL Server / Data Warehouse**
- **Flat file / TRC & SHP parsing**
- **Visual Studio SSIS Projects**
- **Data Flow Tasks & Conditional Splits**

---

## 🔁 ETL Workflow

1. **Raw Input**: TRC / SHP transaction files from payment switch
2. **Staging Load**: Parse and validate into staging tables
3. **Transformation**: Clean, derive, and enrich data
4. **Fact Load**: Insert into fact table with proper keys

---

## 📊 Sample Use Cases

- Analyze transaction volumes by **channel (ATM, POS, Internet)**
- Track trends across **time and geography**
- Measure **terminal/device performance**
- Support **fraud detection** and **risk analysis**

---

## 📌 Status

✅ Ready for deployment and demo  
💡 Ideal for recruiters, employers, or LinkedIn portfolio posts  

---

## 🔗 Author

**Ali Parva**  
💼 Data Engineer | Expert in ETL, SSIS, Azure Data Factory  
🌍 [LinkedIn](#) | [GitHub](#)  

---

## 📝 License

This project is for demonstration and learning purposes.
