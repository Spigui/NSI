import random as rdm
li_mer= (["oui","non"])
class Chambre :
    def __init__(self,numero,etage,capacite,etat_proprete,tarif):
        self.numero = numero
        self.etage = etage
        self.etat_proprete = etat_proprete
        if capacite >3 :
            self.capacite = False
            self.occupation = True
        elif capacite <1 :
            self.capacite = False
            self.occupation = False
        else :
            self.capacite = capacite
            self.occupation = True
        self.tarif = tarif
        if self.etat_proprete == "sale" :
            self.etat_proprete = False
        elif self.etat_proprete == "propre":
            self.etat_proprete == True
        self.vue_mer = rdm.choice(li_mer)
    def nettoyer(self,menage) :
        if état_proprete == "sale":
            self.etat_proprete == "propre"
