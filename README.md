# ScoreSight 2.0 - EPL Match Predictor

ScoreSight 2.0 is a machine learning application that predicts English Premier League (EPL) match outcomes using historical data from 10 seasons (2010-2011 to 2019-2020). The project combines data science techniques with a user-friendly web interface to provide football fans with match predictions.

## Project Structure

```
ScoreSight_2.0/
├── app/                    # Main application package
│   ├── __init__.py
│   ├── app.py             # Flask application factory
│   ├── config.py          # Configuration settings
│   ├── models/            # Data models and prediction logic
│   ├── views/             # Route handlers
│   ├── api/               # API clients
│   └── utils/             # Utility functions
├── data/                  # Data files
│   ├── raw/               # Raw data files
│   ├── processed/         # Processed data files
│   └── models/            # Trained models
├── static/                # Static files
│   ├── css/
│   ├── js/
│   └── images/
├── templates/             # HTML templates
├── tests/                 # Test files
├── docs/                  # Documentation
├── scripts/               # Utility scripts
├── .env                   # Environment variables
├── .gitignore
├── requirements.txt
└── run.py                 # Application entry point
```

## Getting Started

1. **Install Dependencies**:
   ```bash
   pip install -r scripts/requirements.txt
   ```

2. **Run the Web Application**:
   ```bash
   python run.py
   ```

3. **Access the Application**:
   Open your browser and go to `http://localhost:5000`

## Documentation

For detailed documentation, please see [docs/README.md](docs/README.md)
