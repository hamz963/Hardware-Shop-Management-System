# Hardware Shop Management System | پارڈویٹر دکان انتظام نظام

Desktop application for managing hardware shop inventory, customers, billing, transactions, and reports. Built with Python/Tkinter. Bilingual (English/Urdu).

## ✨ Features
- **Inventory**: Add/Edit/Delete items, update stock, price history tracking, search/filter by category.
- **Customers**: Add/Edit/Delete customer records (name, contact, address).
- **Billing**: Create bills with cart (stock validation), walk-in/new customers, save transactions.
- **Transactions**: View sales history, filter by customer.
- **Reports**: Low stock alerts, high-value items, total inventory value/sales KPIs.
- **Exports**: CSV/JSON inventory backups.
- **Data**: JSON-based (shop_data.json), sample data included.
- **UI**: Modern theme, responsive tables, modals.

## 📱 Screenshots
*(Add screenshots here: inventory table, billing modal, reports)*

## 🚀 Quick Start

### Prerequisites
- Python 3.8+

### Installation
```bash
pip install -r requirements.txt
```

### Run
**Windows:**
- Double-click `run.bat`
- Or: `python main.py`

**Linux/macOS:**
```bash
python main.py
```

Sample data loads automatically. Data saved to `shop_data.json`.

## 📂 Project Structure
```
.
├── main.py          # Core app
├── requirements.txt # Dependencies
├── shop_data.json   # Data (gitignored)
├── run.bat          # Windows launcher
├── README.md
└── .gitignore
```

## 🔧 Usage
1. **Inventory Tab**: Manage items (add, edit, stock/price updates).
2. **Customers**: Add customer details.
3. **Billing**: Select customer/items/Qty → Save bill (updates stock).
4. **Transactions/Reports**: View analytics.

**Hotkeys**: Double-click to edit rows.

## 🛠 Development
- Theme constants in `main.py` (C dict).
- Data model extensible (add fields).
- Future: PDF bills, SQLite migration.

## 🤝 Contributing
Fork, PR welcome!

## 📄 License
MIT
