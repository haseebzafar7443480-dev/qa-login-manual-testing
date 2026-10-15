# Sample Bug Reports

These are examples of how I write bug reports. Replace them with real bugs you find on any website or app.

---

## BUG-001: No error message shown when password is empty

| Field | Details |
|---|---|
| **Severity** | Medium |
| **Priority** | Medium |
| **Environment** | Chrome 120, Windows 11 |
| **Related test case** | TC05 |

**Steps to reproduce**
1. Open the login page
2. Enter a valid email
3. Leave the password field empty
4. Click Login

**Expected result:** A message says "Password is required".

**Actual result:** The page reloads and no message is shown.

**Attachment:** screenshot.png

---

## BUG-002: Login button can be clicked multiple times

| Field | Details |
|---|---|
| **Severity** | Low |
| **Priority** | Low |
| **Environment** | Safari, iPhone 14 |
| **Related test case** | TC01 |

**Steps to reproduce**
1. Enter valid credentials
2. Tap Login quickly 3 times

**Expected result:** The button is disabled after the first tap.

**Actual result:** Multiple login requests are sent.
