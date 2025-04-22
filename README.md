# CPP
# AIRGEAD BANKING INVESTMENT CALCULATOR 
A C++ console application for calculating compound interest with and without monthly deposits, featuring robust input validation and clean financial reporting.
## Features
 **Dual Calculation Modes**  
- Project growth with initial investment only
- Project growth with monthly contributions

 **Professional Financial Reporting**  
- Formatted yearly breakdowns
- Accrued interest tracking
- Clean console output with proper alignment

**Input Validation**  
- Negative value prevention
- Percentage range checking (0-100%)
- Minimum year requirement enforcement

# Technical Implementation
**Core Components:**
- Object-oriented design with `InvestmentCalculator` class
- Compound interest algorithm using monthly compounding periods
- Exception handling for invalid inputs
- Precision formatting using `<iomanip>`

**Key Functions:**
```cpp
void CalculateWithoutMonthlyDeposits();  // Projects base growth
void CalculateWithMonthlyDeposits();    // Projects growth with contributions
void ValidateInputs();                  // Input safety checks
