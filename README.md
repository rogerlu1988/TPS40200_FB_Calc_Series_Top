
With `Vref = 0.7V` for the TPS40200.

---

## 🔧 Features

- **Editable Target Output Voltage (Vout)**  
  Adjust via slider or input box (range: 20 V to 100 V, step: 0.01 V)

- **Configurable Resistor Inventory**  
  Input your own resistor values (in kΩ) — e.g. `324, 576, 1000, 1500, ...`  
  You can also clear the list and start fresh

- **Series Combination for R<sub>top</sub>**  
  Automatically selects **two resistors in series** for R<sub>top</sub>, and one resistor for R<sub>bottom</sub>

- **Instant Search**  
  Click a button to compute and display top 5 closest combinations to your Vout target (±0.25 V)

- **Responsive UI with Tailwind CSS**  
  Clean, modern interface optimized for desktop and mobile

---

## 📷 Screenshots

> *(Include screenshots of the page showing sliders, input area, and result table if hosted on GitHub)*

---

## 📁 Usage

1. Clone or download the repo
2. Open `index.html` in your browser
3. Enter your desired `Vout` and resistor list
4. Click the 🔍 **Find Best** button
5. View the recommended resistor combinations

---

## 📚 Why This Tool?

In power supply design, it’s common to have limited resistor values in stock. Manually calculating combinations is time-consuming and error-prone. This tool:

✅ Saves time  
✅ Reduces trial-and-error  
✅ Increases accuracy  
✅ Works offline  
✅ Helps you pick the best-fit resistor values from your inventory

---

## 🚀 Getting Started

### Run Locally
```bash
git clone https://github.com/yourusername/tps40200-feedback-calculator.git
cd tps40200-feedback-calculator
open index.html
