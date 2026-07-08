# Microsoft Entra ID Security Lab Assignment

## Lab 1: Multi-Factor Authentication (MFA)

### Objective
Configure MFA for user accounts.

### Result
- Microsoft Authenticator configured
- MFA enabled successfully

---

## Lab 2: Conditional Access Policy

### Objective
Create a Conditional Access Policy for Finance users.

### Configuration

- Users: Finance Group
- Cloud Apps: All
- Grant Control: Require MFA
- Named Location: Trusted Office IP

### Result
Conditional Access Policy created successfully.

---

## Lab 3: Privileged Identity Management (PIM)

### Objective
Configure Just-In-Time (JIT) access.

### Configuration

- Role: Group Administrator
- Assignment: Eligible
- Activation Duration: 8 Hours
- Require MFA: Yes
- Require Approval: Yes

### Result
PIM configured successfully.

---

## Lab 4: Sign-in Logs

### Objective
Review authentication logs.

### Result

- MFA Triggered
- Conditional Access Applied
- Sign-in monitored successfully
