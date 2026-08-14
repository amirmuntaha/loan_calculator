# Loan Amortization Calculator

An interactive loan amortization calculator that helps you simulate and predict loan payments based on yearly interest rates.

## 🔗 Live Demo

**[View the Calculator](https://amirmuntaha.github.io/loan_calculator/)**

## 📋 Features

- **Interactive Sliders** — Adjust loan amount, interest rate, and loan term in real time
- **Monthly Payment Summary** — Instantly see your estimated monthly payment, total interest, and total amount paid
- **Visual Chart** — Stacked bar chart showing principal vs. interest paid each year over the loan's life
- **Amortization Schedule** — Detailed payment-by-payment breakdown table with beginning balance, interest, principal, and ending balance

## 🛠️ Tech Stack

- HTML5
- [Tailwind CSS](https://tailwindcss.com/) (via CDN)
- [Chart.js](https://www.chartjs.org/) (via CDN)
- Vanilla JavaScript

## 🚀 Usage

Simply open the [live demo](https://amirmuntaha.github.io/loan_calculator/) or clone the repository and open `index.html` in your browser:

```bash
git clone https://github.com/amirmuntaha/loan_calculator.git
cd loan_calculator
open index.html
```

No build step or dependencies required — it's a single HTML file with everything included.

## 📐 How It Works

The calculator uses the standard amortization formula (PMT) to compute fixed monthly payments:

```
PMT = (PV × r × (1 + r)^n) / ((1 + r)^n − 1)
```

Where:
- **PV** = Present Value (loan amount)
- **r** = Monthly interest rate (annual rate ÷ 12)
- **n** = Total number of payments (months)

## 📄 License

This project is open source and available for personal and educational use.
