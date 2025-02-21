# 🎮 Number Guessing Game - Solidity Smart Contract

A simple Ethereum-based **Number Guessing Game** where players can bet **1 Ether** to guess a random number between **1 and 10**. If they guess correctly, they win **2 Ether** (their bet + prize).

---

## 📌 Features

✅ **Automated Prize Distribution** - Winners automatically receive **2 Ether**.
✅ **Random Number Generation** - Uses `block.timestamp` for randomness.\
✅ **Secure Betting** - Players must send exactly **1 Ether** to participate.\
✅ **No Constructor** - Uses `initialize()` to set up contract variables.\
✅ **Funds Withdrawal** - Owner can withdraw accumulated contract balance.

---

## 📍 Deployed Contract Address

- **Edu Chain Deployment:** [`0xfb0fd400279ecf7f984727668a322bb5664ca79c`](https://explorer.educhain.com/address/0xfb0fd400279ecf7f984727668a322bb5664ca79c)

---

## ⚡ How to Play

1. Send **1 Ether** to the contract and call `guessNumber(your_guess)`.
2. If your guess matches the random number, you win **2 Ether**.
3. If incorrect, your **1 Ether bet is lost**.
4. The contract generates a new random number for the next round.

---

## 🛠 Deployment & Usage

### **1️⃣ Deploy the Contract**

- Deploy the contract on **Edu Chain**.
- Call `initialize()` once after deployment.

### **2️⃣ Players Can Guess**

- Players call `guessNumber(uint _guess)` with **1 Ether**.
- Winning players receive **2 Ether** instantly.

### **3️⃣ Owner Functions**

- Owner can withdraw the total contract balance using `withdraw()`.

---

## 🚀 Connect & Explore

🔹 **Edu Chain Explorer:** [View Contract](https://explorer.educhain.com/address/0xfb0fd400279ecf7f984727668a322bb5664ca79c)\
🔹 **GitHub Repository:** *[Add your GitHub Repo Link here]*

---

Made with ❤️ by **[Bhairaram]**

