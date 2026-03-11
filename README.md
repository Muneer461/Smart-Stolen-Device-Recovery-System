📱 Smart Stolen Device Recovery System (IMEI-Based)

A web-based **device tracking and security monitoring platform** that detects unauthorized device usage and assists in recovering stolen mobile devices using IMEI-based identification.

---

## 🔍 What This Project Does

When a mobile device is stolen and used again — even with a new SIM card — the system detects it via the device's unique **IMEI number** and automatically alerts the original owner. The platform monitors device registrations, flags suspicious activity, and supports law enforcement follow-up.

---

## 🛡️ Security Features

| Feature | Description |
|---|---|
| IMEI Tracking | Identifies devices by unique hardware ID |
| Duplicate Detection | Flags duplicate IMEI registrations |
| Blacklist Monitoring | Cross-checks against blacklisted device database |
| Anomaly Detection | Identifies unusual access patterns and status changes |
| Access Control | Role-based access restricts sensitive data to authorized users |
| Alert System | Automatic owner notification on unauthorized device usage |

---

## ⚙️ How It Works

1. **Device Reported Stolen** — Original owner reports device via platform
2. **IMEI Blacklisted** — Device IMEI added to blacklist database
3. **New Registration Detected** — System detects if stolen device is registered by new user
4. **Alert Triggered** — Original owner automatically notified
5. **Log Generated** — Full access log recorded for law enforcement

---

## 🔐 Security Analysis

Attack vectors identified and addressed:

- **Unauthorized Device Registration** — Detected via IMEI blacklist cross-check
- **Duplicate IMEI Fraud** — Flagged via database query anomaly detection
- **Unauthorized Data Access** — Prevented via role-based access control
- **Log Tampering** — Access logs write-protected for forensic integrity

---

## 🛠️ Tech Stack

- **Backend:** PHP
- **Database:** MySQL (SQL-based anomaly detection queries)
- **Security:** Role-based access control, input validation, log correlation

---

## 🎯 Key Results

- ✅ Real-time detection of unauthorized device usage
- ✅ Automated owner alert on stolen device re-registration
- ✅ Duplicate IMEI and blacklist cross-checking
- ✅ Full audit log for law enforcement support

---

## 👤 Author

**Mohammad Muneeruddin**
- LinkedIn: [linkedin.com/in/Muneer461](https://linkedin.com/in/Muneer461)
- GitHub: [github.com/Muneer461](https://github.com/Muneer461)
