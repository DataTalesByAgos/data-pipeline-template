Estructura:

````
├── data/
│   ├── raw/            # Datos originales sin procesar
│   ├── interim/        # Datos intermedios
│   └── processed/      # Datos finales listos para modelar
├── src/
│   └── data_module/
│       ├── __init__.py
│       ├── data_loader.py
│       ├── data_cleaning.py
│       ├── data_imputation.py
│       ├── data_new_features.py
│       ├── data_validation.py
│       ├── data_splitting.py
│       ├── data_saving.py
│       └── pipeline.py
├── tests/
│   └── data/
│       ├── test_cleaning.py
│       ├── test_imputation.py
│       ├── test_features.py
│       └── test_pipeline.py
├── requirements.txt
├── pyproject.toml
└── README.md
````
