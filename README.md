# Health-Tracker-Program


<p align="center">
  <a href="https://coronasafe.network">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="./care/static/images/logos/light-logo.svg">
      <img alt="health logo" src="./care/static/images/logos/black-logo.svg"  width="300">
    </picture>
  </a>
</p>

[![Deploy health](https://github.com/coronasafe/care/actions/workflows/deployment.yaml/badge.svg)](https://github.com/coronasafe/care/actions/workflows/deployment.yaml)
[![Maintainability Rating](https://sonarcloud.io/api/project_badges/measure?project=coronasafe_care&metric=sqale_rating)](https://sonarcloud.io/summary/new_code?id=coronasafe_care)
[![DeepScan grade](https://deepscan.io/api/teams/10238/projects/12962/branches/208996/badge/grade.svg)](https://deepscan.io/dashboard#view=project&tid=10238&pid=12962&bid=208996)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)
[![Cookiecutter Django](https://img.shields.io/badge/built%20with-Cookiecutter%20Django-ff69b4.svg)](https://github.com/pydanny/cookiecutter-django/)
[![Code style: black](https://img.shields.io/badge/code%20style-black-000000.svg)](https://github.com/psf/black)
[![Chat](https://img.shields.io/badge/-Join%20us%20on%20slack-7b1c7d?logo=slack)](https://slack.coronasafe.in/)



This is the backend for care. an open source platform for managing patients, health workers, and hospitals.


## Features

Care backend makes the following features possible:

- Realtime Analytics of Beds, ICUs, Ventilators, Oxygen and other resources in hospitals
- Facility Management with Inventory Monitoring
- Integrated Tele-medicine & Triage
- Patient Management and Consultation History
- Realtime video feed and vitals monitoring of patients
- Clinical Data Visualizations.

## Getting Started

### Docs and Guides

You can find the docs at https://care-be-docs.coronasafe.network


### Staging Deployments

Staging instances for testing are automatically deployed on every commit to the `master` branch. The staging instances are available at:

- https://gdcapi.coronasafe.network
- https://careapi.coronasafe.in

### Self hosting

#### Compose

docker compose is the easiest way to get started with care.
put the required environment variables in a `.env` file and run:

```bash
make up
```

