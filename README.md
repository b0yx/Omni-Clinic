<<<<<<< HEAD
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
=======
### Omni Clinic

App for manage clinc operations

### Installation

You can install this app using the [bench](https://github.com/frappe/bench) CLI:

```bash
cd $PATH_TO_YOUR_BENCH
bench get-app $URL_OF_THIS_REPO --branch develop
bench install-app omni_clinic
```

### Contributing

This app uses `pre-commit` for code formatting and linting. Please [install pre-commit](https://pre-commit.com/#installation) and enable it for this repository:

```bash
cd apps/omni_clinic
pre-commit install
```

Pre-commit is configured to use the following tools for checking and formatting your code:

- ruff
- eslint
- prettier
- pyupgrade

### License

mit
>>>>>>> 1685a3e (feat: Initialize App)
