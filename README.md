# SQA Engineer Intern Assessment

## RoBenDevs - Software Engineering Internship Application

### About This Repository
This repository was created as part of the **SQA Engineer Intern Assessment** for applying to the **Software Engineering Internship** position at **RoBenDevs**.

The assessment includes comprehensive test case design for a food delivery application called **QuickBite**, covering functional, negative, boundary, edge-case, and non-functional testing scenarios.

---

### Company
**RoBenDevs** - Software Solutions

### Position Applied
**Software Engineering Intern** (SQA Focus)

---

### Project Overview
QuickBite is a food delivery application where users can:
- Browse restaurants and menus
- Add items to cart with quantity management
- Apply coupons and discounts
- Choose from multiple payment methods (Card, UPI, Wallet, COD)
- Track order status in real-time
- Cancel orders and get refunds
- Rate orders and delivery partners

---

### Modules Covered

| Module | Test Cases | Priority |
|--------|-----------|----------|
| Cart Management | 12 | High |
| Coupons & Discounts | 14 | High |
| Checkout & Order Value | 11 | High |
| Payment | 10 | High |
| Order Tracking | 4 | Medium |
| Cancellation & Refund | 5 | High |
| Ratings & Reviews | 4 | Medium |
| Business Rules | 7 | Medium |
| Persona Scenarios | 3 | Medium |
| Non-Functional | 6 | High |
| **Total** | **76** | |

---

### Test Case Types
- **Functional** - Core feature validation
- **Negative** - Invalid input/edge scenarios
- **Boundary** - Min/Max value testing
- **Edge Case** - Unusual scenarios
- **Non-Functional** - Performance, Security, Compatibility

---

### Files Included
| File | Description |
|------|-------------|
| `QuickBite_Test_Cases.csv` | 76 test cases in CSV format (Google Sheets compatible) |
| `SQA Engineer Intern Assessment.pdf` | Original assessment document from RoBenDevs |
| `README.md` | Project documentation |

---

### How to Use
1. Download `QuickBite_Test_Cases.csv`
2. Open Google Sheets → File → Import → Upload
3. Select the CSV file
4. Start executing test cases

---

### Key Features Tested
- Cart management (add, remove, quantity limits)
- Coupon system (WELCOME50, FLAT20, auto-removal)
- Payment methods (Card, UPI, Wallet, COD)
- Order tracking & status flow
- Cancellation & refund process
- User ratings & reviews
- Business rules (referral, wallet, guest user)
- Non-functional (performance, security, compatibility)

---

### PRD Ambiguities Identified
1. Delivery fee vs minimum order value contradiction
2. Restaurant rejection scenario missing
3. Payment success + restaurant reject handling unclear
4. Referral bonus recipient ambiguous
5. Rating edit after 24 hours behavior undefined
6. Coupon re-apply after removal scenario missing

---

### Author
**Fahim Montasir**  
Software Engineering Intern Candidate  
RoBenDevs

---

### Connect
- GitHub: [Fahim232](https://github.com/Fahim232)
- Repository: [SQA_Engineer_Intern_Assignment](https://github.com/Fahim232/SQA_Engineer_Intern_Assignment)

---
*Assessment Completed: 2026*
