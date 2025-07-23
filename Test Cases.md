✅ Test Cases (Excel Sheet – Will provide downloadable soon)

### Until Excel download is available, here’s the copy-pasteable format:

| Test Case ID | Scenario ID | Test Case Title                      | Input Data                             | Steps                                             | Expected Result                       | Status |
| ------------ | ----------- | ------------------------------------ | -------------------------------------- | ------------------------------------------------- | ------------------------------------- | ------ |
| TC-01        | SC-01       | Valid Card and PIN Login             | Card: 1111 2222 3333 4444<br>PIN: 1234 | 1. Insert card<br>2. Enter valid PIN<br>3. Submit | Login successful, Main Menu shown     | Pass   |
| TC-02        | SC-02       | Invalid PIN Entry                    | PIN: 0000                              | 1. Insert card<br>2. Enter wrong PIN<br>3. Submit | Error shown: Invalid PIN              | Pass   |
| TC-03        | SC-03       | Balance Inquiry                      | -                                      | 1. Login<br>2. Select "Balance Inquiry"           | Shows correct account balance         | Pass   |
| TC-04        | SC-04       | Valid Cash Withdrawal                | Amount: ₹1000                          | 1. Login<br>2. Withdraw ₹1000<br>3. Confirm       | ₹1000 is dispensed<br>Balance updated | Pass   |
| TC-05        | SC-05       | Withdrawal with Insufficient Balance | Amount: ₹10000<br>Balance: ₹500        | 1. Login<br>2. Try to withdraw ₹10000             | Error: Insufficient balance           | Pass   |
| TC-06        | SC-06       | Invalid Denomination Withdrawal      | Amount: ₹13                            | 1. Login<br>2. Enter ₹13<br>3. Submit             | Error: Enter valid denomination       | Fail   |
| TC-07        | SC-07       | Session Timeout                      | -                                      | 1. Login<br>2. Wait 2 minutes without action      | Auto-logout with timeout message      | Pass   |
| TC-08        | SC-08       | Balance Updates After Withdrawal     | Balance: ₹5000 → Withdraw: ₹500        | 1. Login<br>2. Withdraw ₹500<br>3. Check balance  | Balance = ₹4500                       | Pass   |

