# 📈 Stock Price Simulation using NumPy

This project simulates the movement of a stock price over a number of days using a simple **random walk model**. It’s built using **NumPy** and is great for beginners who want to practice numerical computing and random data generation.

---

## 🔧 What It Does

- Simulates daily stock price changes
- Uses **normal distribution** to mimic realistic market fluctuations
- Visualizes the price movement over time (optional with Matplotlib)

---

## 🛠️ Technologies Used

- Python 🐍
- NumPy 🔢
- (Optional) Matplotlib 📊

---

## 📁 Files

| File | Description |
|------|-------------|
| `stock_simulation.py` | Main script that runs the simulation |
| `README.md` | Project overview |

---

## 🚀 How It Works

1. Start with a base stock price (e.g., ₹100)
2. Simulate daily returns using:
   ```python
   np.random.normal(loc=0.001, scale=0.02, size=days)

