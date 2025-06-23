
# 🔐 Microsoft Defender for Endpoint + Microsoft Sentinel SIEM Integration

## 🔍 Overview
This project documents the real-world integration of **Microsoft Defender for Endpoint** with **Microsoft Sentinel**, creating a unified security monitoring and incident response platform. The goal was to streamline endpoint telemetry into the SIEM to enable rapid detection, correlation, and response to threats targeting a hybrid healthcare environment.

---

## 👤 My Role
**Security Engineer / Threat Detection Lead**  
I designed and implemented the integration, wrote KQL detection rules, and built automated response workflows using Microsoft Logic Apps and custom alert rules.

---

## 🎯 Objectives
- Ingest Defender endpoint alerts into Microsoft Sentinel
- Create custom detection rules using KQL
- Automate response workflows with Logic Apps
- Enable SOC teams to triage and remediate faster

---

## 🧰 Tools & Technologies
- **Microsoft Sentinel (SIEM)**
- **Microsoft Defender for Endpoint**
- **Azure Log Analytics**
- **Kusto Query Language (KQL)**
- **Logic Apps**
- **Microsoft 365 Defender Portal**

---

## 🚀 Key Implementation Steps

1. **Connector Setup**
   - Enabled native Defender → Sentinel connector
   - Verified data ingestion in Log Analytics workspace

2. **KQL Rule Development**
   - Created custom rules for suspicious PowerShell, WMI access, and credential theft
   - Tuned noise levels by filtering known safe activity

3. **Alert Automation**
   - Used Logic Apps to:
     - Send high-severity alerts to Microsoft Teams + email
     - Isolate device via Defender APIs
     - Create ServiceNow incident tickets

4. **Dashboard & Workbook Customization**
   - Built a “Defender Threat Center” workbook in Sentinel
   - Added visuals for endpoint health, active incidents, lateral movement paths

---

## 📊 Results

| Metric                             | Outcome                         |
|-----------------------------------|----------------------------------|
| ⚠️ Alert handling time             | Reduced from 20 mins to 3 mins   |
| 🚨 SOC resolution efficiency       | Improved by 45%                  |
| 🔒 Endpoint visibility             | Achieved full OS-level telemetry |
| 🧠 KQL query execution speed       | <2 seconds for 95% of rules      |

---

## ✅ Keywords
`Microsoft Sentinel` • `Microsoft Defender for Endpoint` • `SIEM` • `KQL` • `Threat Hunting` • `Logic Apps` • `Azure` • `Incident Response` • `SOC Automation`

---