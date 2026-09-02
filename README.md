# Omni Clinic

Omni Clinic is a specialized clinic and patient management app built on the **Frappe Framework**, designed to streamline clinic workflows and integrate with ERPNext Healthcare.

## Modules & Capabilities

- **Patient Management:** Medical profiles, history, and vitals tracking.
- **Appointments & Queues:** Doctor scheduling and dynamic waiting room management.
- **Consultation & EMR:** Standardized clinical notes and diagnostic records.
- **Billing:** Direct linkage to ERPNext invoicing and payments.

## Installation

```bash
bench get-app https://github.com/b0yx/Omni-Clinic.git
bench --site <site-name> install-app omni_clinic
bench --site <site-name> migrate
