# environment prep
- This repo provides the environment needed to run legacy fissa scripts for neuropil decontamination
- requires python 3.8.10 (can download via microsoft store for windows)
1. Clone repository `https://github.com/xiubert/fissa_env_legacy.git` and change to respository directory (`cd fissa_env_legacy`).
2. Create python venv using Python 3.8 for running these scripts to isolate dependencies: `python3.8 -m venv env_fissa`
3. Activate virtual environment:
    - Unix: `source env/bin/activate`
    - Windows: 
        - VSCode terminal defaults to PowerShell: `.\env\Scripts\Activate.ps1`
        - If in command prompt `.\env\bin\activate.bat`
4. Install dependencies: `pip install -r requirements.txt`

# run notebook