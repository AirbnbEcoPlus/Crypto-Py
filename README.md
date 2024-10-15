# Crypto-Py
###### A proof of concept RSA




En cryptographie asymétrique, on a besoin de grands nombres permiers pour fabriquer des clés publiques et privées.

C’est le cas avec RSA. En effet, le module RSA est obtenu en multipliant deux grands nombres premiers choisis aléatoirement. Si un attaquant arrive à factoriser le module RSA, il peut casser le chiffrement ! Il lui suffira de calculer la clé privée à partir de la clé publique.
