# Rain Alert Using GitHub Actions

This repository contains a GitHub Actions workflow to alert users when rain is forecasted in their area. This can be useful for anyone wanting to stay informed about weather changes and plan their activities accordingly.

## Features
- **Real-time Rain Alerts**: The Script runs every morning around 6 am UTC and takes into account the weather forcast for next 9 hrs.
- **Customizable Alerts**: Modify Location Parameters to customize notification according to your area.
- **Integration with Email Service**: Directly integrates with email services for notifications.

## Installation
1. **Clone the repository**:
   ```bash
   git clone https://github.com/Sohamtam46/Rain-Alert-Github-Actions-
   ```
2. **Set up your GitHub Actions workflow** by editing the `.github/workflows/schedule.yml` file according to your needs.

## Configuration
To customize the rain alert settings, modify the following parameters in the `main.py` file:
- **Location**: Set your location to get accurate rain forecasts.
- **Notification Method**: Choose the "MY_EMAIL" and "TO_EMAIL" to receive alerts.
- **Alert Threshold**: Define how much rain constitutes an alert.

## Usage
After setting up and configuring the workflow, GitHub Actions will run based on your schedule. You can check the Actions tab in your GitHub repository to view the status of the alerts and any logs generated.

## Contact
For questions or suggestions, feel free to reach out to [Sohamtam46](https://github.com/Sohamtam46).
