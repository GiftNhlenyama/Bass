---

# **Bass Amortization Scheduler**

A web-based loan amortization calculator designed to help users understand their loan repayment schedule, visualize interest and principal payments over time, and compare different repayment scenarios — including the impact of additional monthly payments.

---

## **Features**

* **Comprehensive Loan Calculation**
  Calculates monthly payments, total interest paid, and remaining balance for each period.

* **Amortization Schedule Table**
  Detailed breakdown of each payment:

  * Starting balance
  * Principal paid
  * Interest paid
  * Fees
  * Ending balance

* **Loan Summary**
  Displays:

  * Original vs. new total interest
  * Interest saved
  * Total service fees and savings
  * Original vs. new loan term
  * Term reduction

* **Interactive Charts**

  * **Breakdown of Total Payments**: Pie chart showing principal vs. interest and fees
  * **Principal vs. Interest Paid Per Month**: Bar chart illustrating change over time
  * **Loan Balance Over Time**: Line chart of loan balance progression
  * **Total Loan Cost Comparison**: Bar chart of original vs. comparison scenarios
  * **Scenario Comparison**: Interest saved & term reduction across additional payments
  * **Multiple Scenario Comparison**: Input multiple values to compare impacts

* **Theme Switching**
  Toggle between light (Apple-inspired) and dark modes.

* **Export Functionality**
  Export amortization schedules and summaries to `.xlsx` files.

* **Input Validation**
  Ensures valid numerical input with clear error messages.

* **Loading Indicator**
  Displays a spinner during calculation for better user feedback.

---

## **How to Use**

1. **Input Loan Details**

   * Principal Loan Amount (R)
   * Annual Interest Rate (%)
   * Loan Term (Years)
   * Initiation Fee (R)
   * Monthly Service Fee (R)
   * Additional Monthly Payment (R)
   * For comparisons: comma-separated additional payments (e.g., `500,1000,2333`)

2. **Calculate Loan**
   Click **"Calculate Loan"** to process your input.

3. **Review Results**

   * **Loan Summary**: Key financial metrics
   * **Charts**: Visualize payments and balances
   * **Amortization Schedule**: Payment breakdown

4. **Export Data**
   Click **"Export All Scenarios to Excel"** to download the spreadsheet.

5. **Change Theme**
   Use the toggle to switch between **Light** and **Dark** modes.

---

## **Technical Details**

Built using:

* **HTML5**: Structure and layout
* **CSS3**: Styling and responsive design
* **JavaScript (ES6+)**: Logic, UI updates, and interactivity
* **Chart.js**: Interactive charting
* **SheetJS (xlsx)**: Excel export

---

## **Optimizations**

* Improved calculation stability for edge cases and precision
* Updated charts with solid color palettes (no gradients or purples)
* Removed redundant charts to streamline outputs
* Added `console.log` debugging for internal tracing
* Implemented `try...catch` error handling for exports

---

## **Future Enhancements**

* **Input Debouncing**
  Reduce unnecessary recalculations during fast typing

* **Modular JavaScript**
  Refactor into organized, scalable modules

* **Advanced Scenarios**
  Add irregular payments, lump sums, or variable interest

* **Print Functionality**
  Enable formatted printing of amortization schedule

* **Save/Load Functionality**
  Use local storage or backend to save and retrieve loan scenarios

---

