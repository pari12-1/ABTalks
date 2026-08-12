



$env:Path = "C:\Users\Abc\AppData\Local\Programs\Python\Python311;C:\Users\Abc\AppData\Local\Programs\Python\Python311\Scripts;" + $env:Path

py -3.11 -m venv venv

.\venv\Scripts\Activate.ps1

python -m pip install --upgrade pip