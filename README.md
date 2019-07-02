# uncompyle6_script
batch to uncompile python bytecode

sudo apt-get install python3-pip

obligatoire deja pour ne pas installer pip dans la version python2 qui est par défaut sur linux (car il reste pleind e code en python2 dans linux)
Nous on travaille avec python3. On suppose que seule une version de python3 est instalé sinon ca peut etre plus galre.

pip3 install uncompyle6

On install uncompyle6 dans notre python3

pip3 freeze
Cela montre beaucoup de modules installé dans python3

pip freeze
il y en a moins (c'est python2)

pip3 show uncompyle6
Cela montre que uncompyle s'est installé dans home

C'est installé dans python3. On peut le vérifier en faisant dans le terminal
python3
import uncompyle6
uncompyle6.version
Ca dit bien qu'il trouve le bon module


Mais en fait de toute faàon uncompyle6 est fait pour etre appelé depuis le bash...sinon je vais me taper toutes les petites méthodes a faire et à répeter le programme


