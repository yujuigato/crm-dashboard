# CRM 智慧查詢儀表板 — Streamlit CRM Dashboard

讓業務主管**不需要懂 SQL**，也能即時查詢 CRM 客戶資料、多條件篩選、一鍵匯出報表，內網部署開機自動啟動。

## 🔍 專案概述

過去每次查詢 CRM 資料都需要請工程師寫 SQL，等待時間以天計算。本工具以 Streamlit 建構 GUI 介面，直連 SQL Server，業務拉選單即可秒級查詢，並一鍵匯出 CSV / Excel。

## ✨ 核心功能

- 多維度篩選（業務員 / 地區 / 狀態 / 日期）
- 即時回傳，秒級響應
- CSV / Excel 一鍵匯出
- NSSM Windows 服務，開機自動啟動
- SQL Injection 防護（Parameterized Query）

## 🛠 技術棧

Python · Streamlit · SQL Server · pyodbc · Pandas · NSSM · openpyxl

## 🌐 作品集頁面

詳細說明請見：**[https://yujuigato.github.io/crm-dashboard/](https://yujuigato.github.io/crm-dashboard/)**

---

> 原始碼因含企業內部資料庫連線設定，不公開於此 repo。
