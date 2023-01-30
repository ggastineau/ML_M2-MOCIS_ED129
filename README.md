# ML_M2-MOCIS_ED129

Les transparents utilisés en début de séance sont disponibles dans les fichiers ci-dessus.

Pour le TP deux options sont possibles :

1. Sur le mésocentre de l'IPSL:

Les notebooks des séances de TP sont disponibles sont à executer de manière préférentiel sur le mésocentre de l'IPSL. Ceux-ci sont disponibles sur spirit :

/home/ggalod/ED129-ML/TP

Connectez vous sur spirit en ssh (remplacer login par votre login). 

ssh login@spirit1.ipsl.fr 

Copiez ces notebook dans un répertoir de votre home. 

Pour exectuer le nootbook charger l'environnement meso-3.8 :

module load python/meso-3.8

Puis ouvrir un notebook accessible par le port XXXX (remplacer XXXX par un nombre entre 1000 et 9999):

jupyter notebook --no-browser --port=XXXX --ip=spirit1

Ouvrir un terminal et ouvrir le port XXXX :

ssh -L XXXX:spirit1:XXXX login@spirit1.ipsl.fr 

Votre notebook est alors accessible avec votre navigateur préféré.

2. En colab google:

Connectez vous sur votre compte google. Copiez chacuns des TP ci-dessous dans votre espace colab. Vous pouvez ensuite les executer.

Les liens vers les TPs en colab (accessible sous reserve d'avoir un compte google):

TP1:
https://colab.research.google.com/drive/1_vNvZkytJ9fPl4CjSl7qFUNXqWFq6Yz9?usp=sharing

TP2:
https://colab.research.google.com/drive/1rw_wziyFmdtXRmS-I8QVQGkOhv_iTpG-?usp=sharing

TP3:
https://colab.research.google.com/drive/1qJL-CL9ZtmjaBv5mDkWHfV0JX_m_rCM-?usp=sharing

TP4:
https://colab.research.google.com/drive/16aRQpiqdfjo2lnMR5ZtAHkze07ZdtQXT?usp=sharing

