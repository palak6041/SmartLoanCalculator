# Smart Loan & Wealth Dashboard 📊🏠

A powerful, single-page financial dashboard designed to help you crush your home loan faster while simultaneously building wealth. 

Standard EMI calculators fail when it comes to real-world real estate scenarios like under-construction disbursements, offset accounts, and annual salary hikes. This tool uniquely combines **progressive loan disbursements**, **offset account tracking**, and **step-up SIP growth** into one instantly reactive, beautifully visualized dashboard.

## ✨ Key Features

* **Under-Construction Ready:** Manually schedule loan disbursements tranche-by-tranche. The calculator accurately computes Pre-EMI interest vs. Full EMI principal reduction from Day 1.
* **The Offset Advantage:** Input your linked savings/offset account balance. Watch the "Effective Principal" drop and see exactly how much interest you save by parking cash.
* **Step-Up Progression:** Factor in your annual salary bumps by adding a % step-up to your SIP investments and your EMI payments automatically every 12 months.
* **Scenario Manager:** Instantly save, load, and compare different financial strategies (e.g., "Aggressive Prepayment" vs. "Max SIP") using local browser storage.
* **Pro-Level Visualizations:** Built-in 2x2 grid featuring four interactive charts:
  * *True Cost of Loan* (Principal vs. Interest)
  * *Amortization Shift* (EMI breakdown over time)
  * *Wealth Composition* (Capital Invested vs. Compound Returns)
  * *Offset Advantage* (Actual Debt vs. Interest-bearing Debt)
* **One-Click Exports:** Export your entire 20-year amortization matrix to a beautifully formatted PDF or an interactive Excel (`.xlsx`) file.

## 🛠️ Tech Stack

This is a blazing fast, zero-dependency Single Page Application (SPA). No backend or database is required; everything runs locally in your browser.

* **Frontend Framework:** [Vue.js 3](https://vuejs.org/) (via CDN)
* **UI & Styling:** [Bootstrap 5](https://getbootstrap.com/) & Google Inter Font
* **Charts:** [Chart.js](https://www.chartjs.org/)
* **Exports:** [SheetJS](https://sheetjs.com/) (Excel) & [jsPDF / AutoTable](https://github.com/simonbengtsson/jsPDF-AutoTable) (PDF)

## 🚀 How to Run

Because this app has no backend dependencies, running it is incredibly simple:

1. Clone or download this repository.
2. Open `index.html` directly in any modern web browser (Chrome, Edge, Safari, Firefox).
3. *That's it!*

### Hosting Online for Free
To access this tool from your phone or share it with others, you can host it for free in seconds:
* **GitHub Pages:** Go to Repo Settings -> Pages -> Select `main` branch.
* **Vercel / Netlify:** Drag and drop the folder containing `index.html` into Vercel Drop or Netlify Drop.

## 💡 How to Use

1. **Set Global Inputs:** Enter your Sanctioned Loan Amount, Interest Rate, Tenure, and base SIP plans in the top panel.
2. **Manage the Matrix:** Scroll down to the Data Matrix tab. If your property is under construction, you can adjust the "New Disbursement" column for Month 1, and manually add future disbursements in subsequent months.
3. **Add Extra Payments:** Got a bonus? Drop it into the "Extra Prepayment" or "Offset Deposit" column for that specific month and watch your tenure shrink instantly.
4. **Save Scenario:** Click "Save Plan" at the top to commit your layout to browser memory.
5. **Visualize:** Swap to the "Visual Dashboard" tab to see when your Net Worth officially crosses your Debt.

## 🔒 Privacy & Security

100% Client-Side. Your financial numbers, loan details, and scenarios never leave your device. Scenario saving utilizes your browser's local `localStorage`.

## 📄 License

This project is open-source and available under the [MIT License](LICENSE). Feel free to fork, modify, and improve it to fit your personal financial planning needs.
