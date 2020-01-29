# **1ER DAM. Desarrotllament D'Aplicacions Multiplataforma. EDD. Entorns de Desenvolupament.**

***2019- Editat per Máxim Sánchez Porta***


# Index:



>### UNITAT 4. Automatització amb Make.
>
>***[1.-Com instalar Git i Make en Ubuntu 18.](https://github.com/Maxim1erDAM/Unitat4#1-com-instalar-git-i-make-en-ubuntu-18)***
>
>***[2. Com utilitzar Git Part 1](https://github.com/Maxim1erDAM/Unitat4#2-com-utilitzar-git-part-1)***
>
>***[3. Make i el fitxer Makefile](https://github.com/Maxim1erDAM/Unitat4/blob/master/Readme.md#3-make-i-el-fitxer-makefile)***
>
>***[4. Com utilitzar Git Part 2](https://github.com/Maxim1erDAM/Unitat4/blob/master/Readme.md#4-com-utilitzar-git-part-2)***

#    **-Activitat pràctica-**



# UNITAT 4. Automatització amb Make.


## 1.-Com instalar Git i Make en Ubuntu 18.

>***`Actualizar llistat de repositoris de Ubuntu:`***  

sudo apt update

>***`Instalar git:`***  

sudo apt install git


>***`Instalar gcc i make:`***  

sudo apt install gcc make

## 2.-Com utilitzar Git Part 1.

>***`Descarregar el nostre repositori complet de Github a un directori per a treballar:`***  
>***`El nom del repositori deu ser el mateix que el repositori del sistema local. En aquest cas, será “Unitat-4”. Per aixó, abans que res, hi ha que iniciar sessió en Github al introduir la comanda.
Una vegada fet aixó es creará el repositori i será posible pujar o sincronitzar el contingut del repositori local en el repositori de GitHub. Per a conectar el directori al repositori remot de GitHub hi ha que executar la comanda "git remote add origin git clone https://github.com/USUARIGITHUB/REPOSITORI.git" `***  


>***`Eixemple, sincronizant el repositori dins de un directori anomenat "EJERCICIO", amb la comanda "git clone https://github.com/USUARIGITHUB/REPOSITORI.git":`***  

cd EJERCICIO/

git clone https://github.com/USUARIGITHUB/REPOSITORI.git

>***`En el meu cas:`***  

git clone https://github.com/Maxim1erDAM/Unitat-4.git



>***`Després de descarregar-lo, ens situarem en el directori i sincronitzarem el directori amb el repositori de Github.`***  
"git remote add origin https://github.com/USUARIGITHUB/REPOSITORI.git" :`***  

>***`Eixemple:`***  


>***`Así es quan finalment puc fer el push, despres de fer el commit relatiu a origin2:`***  
>***`Eixemple:`*** 

![Copiantsegorepositori](Projecte/Imatges/COPIANT%20CONTINGUT%20A%20UN%20SEGON%20REPOSITORI%202.png)
