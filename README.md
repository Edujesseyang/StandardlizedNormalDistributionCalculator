# Standardized Normal Distribution Calculator

A simple **JavaFX desktop application** for calculating probabilities and z-scores in the **standard normal distribution** (Z ~ N(0,1)).

---

## 📘 Features
- Compute the cumulative probability **P(Z < x)** for a given z-value
- Compute the **z-value** corresponding to a given probability
- Simple and clean **JavaFX** UI
- Supports both positive and negative z-values
- Results rounded to **4 decimal places**

---

## 📁 Project Structure
```text
src/
└── main/
├── java/
│ ├── Launcher.java # Main application entry
│ ├── Controller/PageController.java # Handles button actions and logic
│ ├── Model/DataTable.java # Z-table data / calculation model
│ └── View/MainPage.java # JavaFX scene setup
└── resources/
```

---

## Notes

The calculator uses the standard normal distribution formula and internal approximation to compute the CDF (Φ(z)) and inverse CDF.

Values P(Z < x) = 0 and P(Z < x) = 1 correspond to theoretical limits x = -∞ and x = +∞.

Precision is kept to 4 decimal places, suitable for most statistical tasks.

## Requirements

Java 21 or higher

Maven 3.9+

OpenJFX 21.x

## License

This project is distributed for educational and academic use.
Feel free to modify and adapt it for your own projects.