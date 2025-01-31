# wind-turbine-abm

A web-based wind turbine pre-construction simulator using agent-based modeling, built with Flask and Mesa.

## Overview
Wind Turbine ABM is a SaaS platform that simulates wind farm layouts and energy production using agent-based modeling. The system allows users to experiment with different turbine configurations and analyze their potential performance before actual construction.

## Features
- User authentication system
- Interactive wind farm layout designer
- Real-time simulation visualization
- Agent-based modeling of wind turbine interactions
- Parameter adjustment interface
- Simulation results export

## Tech Stack
- **Backend**: Python, Flask
- **Simulation Engine**: Mesa
- **Database**: SQLite
- **Authentication**: Flask-Login
- **Frontend**: Bootstrap, JavaScript
- **Visualization**: Mesa's built-in visualization server

## Quick Start
### Clone the repository
```
git clone https://github.com/yourusername/wind-turbine-abm.git
cd wind-turbine-abm
```
### Create and activate virtual environment
```
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

### Install dependencies
```pip install -r requirements.txt```

### Run the application
```python app.py```

## Project Structure
```
wind-turbine-abm/
├── app/
│   ├── __init__.py
│   ├── auth/
│   │   ├── __init__.py
│   │   ├── forms.py
│   │   └── routes.py
│   ├── models/
│   │   ├── __init__.py
│   │   ├── user.py
│   │   └── turbine_agent.py
│   ├── simulation/
│   │   ├── __init__.py
│   │   └── routes.py
│   ├── templates/
│   │   ├── auth/
│   │   │   ├── login.html
│   │   │   └── register.html
│   │   ├── base.html
│   │   ├── dashboard.html
│   │   └── simulation.html
│   └── static/
│       ├── css/
│       │   └── style.css
│       └── js/
│           └── simulation.js
├── config.py
├── requirements.txt
└── run.py
```

## License
Distributed under the MIT License. See `LICENSE` for more information.

## Contact
David Galfi - galfidavid314@gmail.com
