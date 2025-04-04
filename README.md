# 🏃‍♂️ Race Time Predictor

**Race Time Predictor** is a lightweight web app that estimates your potential finish times across common race distances using your past performances and the **Riegel formula**. It's designed for runners who want to set smarter goals and track performance trends over time.

## 📌 Features

- **Simple Interface** – Clean, intuitive layout for quick and easy use.
- **Multiple Entries Per Distance** – Input up to 3 times per distance; the tool combines them.
- **Date-Weighted Predictions** – More recent results have higher impact.
- **Real-Time Calculations** – Predictions are generated instantly.
- **Sample Data Button** – Populate with example data to try it out quickly.

## 📈 How It Works

The predictor uses the **Riegel formula**, a widely used method for estimating endurance performance:

T₂ = T₁ × (D₂ / D₁)^1.06


Where:
- `T₁` = time you achieved for distance `D₁`
- `T₂` = predicted time for distance `D₂`
- The exponent `1.06` accounts for endurance drop-off over distance

The app averages predictions from your valid entries, applying higher weight to more recent times based on their date.

## 🚀 Try It Now

🔗 **Live App:** [alexgasconn.github.io/RaceTimePredictor](https://alexgasconn.github.io/RaceTimePredictor/)

## 🧪 How to Use

1. **Enter Your Best Times**  
   Fill in times for the supported distances (Mile, 5K, 10K, Half Marathon, Marathon, or custom). Use `hh:mm:ss` format. Optionally include the date to improve accuracy.

2. **Get Predictions**  
   Click **"Predict Times"** to calculate expected race times across distances.

3. **Try with Sample Data**  
   Click **"Sample Data"** to auto-fill the form with example results and see how it works.

4. **Analyze Output**  
   The tool will show predicted times, pace per km, and a confidence score for each distance.

## 🗂️ Project Structure

| File         | Purpose                                 |
|--------------|------------------------------------------|
| `index.html` | The main HTML page                      |
| `script.js`  | JavaScript logic for inputs and output  |
| `style.css`  | (Optional) CSS for styling (currently inline) |

## 🌍 Deployment

The app is 100% static and deployed using **GitHub Pages**.  
Changes pushed to `main` are immediately live at the [project URL](https://alexgasconn.github.io/RaceTimePredictor/).

## 🤝 Contributing

Feel free to open issues or submit pull requests to improve functionality or UI/UX.  
Ideas, refactors, and clean code are welcome!

## 📄 License

Licensed under the [MIT License](LICENSE).

---

Train smarter. Set realistic goals. Run with confidence.  
Thanks for using **Race Time Predictor**! 🏁
