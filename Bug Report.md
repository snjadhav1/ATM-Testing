✅ Bug Report (Markdown) – ATM Scenario

**Bug: Withdrawal accepts invalid amount like ₹13**

```markdown
# 🐞 Bug Report – Invalid Amount Accepted in Withdrawal

## 🧾 Bug Summary

| Field           | Details                                                              |
|----------------|----------------------------------------------------------------------|
| **Bug ID**      | ATM-BUG-002                                                          |
| **Title**       | ATM allows withdrawal of invalid denominations like ₹13              |
| **Reported By** | Saniya Bhosale                                                       |
| **Date Reported** | 22-July-2025                                                       |
| **Environment** | ATM Simulator v2.0, Windows 10, Edge Browser                         |
| **Module**      | Cash Withdrawal                                                      |
| **Severity**    | Medium                                                               |
| **Priority**    | High                                                                 |
| **Status**      | Open                                                                 |
| **Assigned To** | _(To be filled)_                                                     |

---

## ✅ Steps to Reproduce

1. Insert test card and enter valid PIN.
2. Select "Withdraw Cash".
3. Enter **₹13** as withdrawal amount.
4. Confirm transaction.

---

## 📌 Expected Result

- System should reject the transaction with a message:  
  **"Please enter amount in multiples of ₹100 or ₹500 only."**
- Transaction should not proceed.

---

## ❌ Actual Result

- ATM proceeds with the transaction and attempts to dispense ₹13.
- No validation error is shown.

---

## 🔍 Notes

- ATMs are designed to accept only standard denominations.
- Lack of validation may lead to transaction errors or user confusion.

---

## 📷 Attachments

- **Screenshot:** _[Insert screenshot of withdrawal input ₹13]_  
- **Video (Optional):** _[Add screen recording of bug occurrence]_
```

---
