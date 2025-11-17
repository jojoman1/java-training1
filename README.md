# 🏠 Mortgage Calculator (Java Console Application)

A simple and efficient **Mortgage Calculator** built in **Java**.  
It allows users to input loan details (principal, annual interest rate, and loan period) and generates:
- Monthly mortgage payments
- A complete payment schedule showing remaining balance after each month

---

## 🚀 Features

✅ Calculates monthly mortgage payments  
✅ Displays a full **payment schedule** (remaining balance each month)  
✅ Input validation (ensures values within logical ranges)  
✅ Clean console UI  
✅ Written with **modular, reusable methods**

---

## 🧮 Formula Used

### Monthly Payment:
\[
M = P \times \frac{r(1 + r)^n}{(1 + r)^n - 1}
\]

Where:
- `M` = monthly payment  
- `P` = principal (loan amount)  
- `r` = monthly interest rate (annual interest / 12 / 100)  
- `n` = total number of payments (years × 12)

---

## 💻 Example Run

Principal: 100000
Annual Interest Rate: 3.5
Period (Years): 15

MORTGAGE

Monthly Payments: $714.88

PAYMENT SCHEDULE

$99,785.12
$99,567.21
...
$0.00


---

🏗️ Project Structure
src/
└── com/
    └── sajid/
        └── Main.java
---

## ⚙️ How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/mortgage-calculator.git
   cd mortgage-calculator


Compile the program:

javac -d out src/com/sajid/Main.java


Run the program:

java -cp out com.sajid.Main

🧠 Concepts Demonstrated

Java fundamentals (loops, conditionals, data types)

Methods & modularization

User input handling with Scanner

Mathematical computation

Formatting with NumberFormat

Constants (final static)

Encapsulation of logic (clean code structure)

🌟 Future Enhancements

Add file export for mortgage summary (CSV / PDF)

Build a JavaFX GUI version for interactive UI

Add unit tests using JUnit

Create a web version using Spring Boot

Allow extra payments or early payoff simulation

📸 Demo Screenshots (Optional)

Add some screenshots of your IntelliJ console output here, e.g.:

👨‍💻 Author

Mohamed Sajith
QA Automation Engineer → learning Java backend & finance tools
📧 contact@sajidmohamed.dev

🌐 [LinkedIn Profile
](https://www.linkedin.com/in/mohamed-sajith-36579a188/)
📝 License

This project is open-source and available under the MIT License
.


---

## 🧱 What Else You Can Add to Showcase Your Project

Here’s how to make this stand out on GitHub or in your portfolio:

### ✅ 1. Add a `LICENSE` file
Use [MIT License](https://choosealicense.com/licenses/mit/) — it shows professionalism.

---

### ✅ 2. Add sample screenshots
- Take screenshots of console runs (MORTGAGE + PAYMENT SCHEDULE)
- Save them in a `/screenshots` folder

---

### ✅ 3. Add Javadoc comments
For example:
  java
/**
 * Calculates the mortgage payment based on principal, annual interest rate, and years.
 * @param principal The loan amount.
 * @param annualInterest The annual interest rate.
 * @param years The loan duration in years.
 * @return The monthly mortgage payment.
 */

✅ 4. Add Unit Tests

You can add a small test class using JUnit to show professionalism:

import static org.junit.jupiter.api.Assertions.*;
import org.junit.jupiter.api.Test;

class MortgageTest {
    @Test
    void testMortgageCalculation() {
        double result = Main.calculateMortgage(100000, 3.5f, (byte)15);
        assertEquals(714.88, result, 0.5);
    }
}

✅ 5. Add a GitHub banner

Create a simple banner image (mortgage-banner.png) with your name and project title — looks great on top of your repo.
