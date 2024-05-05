# VZPOSTAVITEV PROJEKTA
1. Kreacija poetry projekta: poetry new iis_vaje
2. Dodajanje knjižnic:
    poetry add pandas
    poetry add scikit-learn
    poetry add evidently 
3. Dodajanje map: mkdir -p data/{processed,raw} models reports src/{data,models}
4. Kreiranje README.md in init datotek: 
    touch README.md pyproject.toml
    touch src/__init__.py

5. Inicializacija git-a: 
    git init

6. Kreacija repota na githubu.
7. Povezava repozitorijev: git remote add origin https://github.com/ivanalav00/vaja_iis.git
8.  

# VZPOSTAVITEV VERZIONIRANJA PODATKOV   
1. Inicializacija dvc: dvc init 
2. Verzioniranje mape data: dvc add data
3. Dodajanje data.dvc in .gitignore na git: 
    git add data.dvc .gitignore
    git commit -m "Initial commit"