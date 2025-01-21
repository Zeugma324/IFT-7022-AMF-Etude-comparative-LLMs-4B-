##Code à run sur google collab + GPU A100##



Le calcul des métriques n'a rien donnée de proban. Pour cause le dataset aurait du etre mieux nettoyer que de simplement prendre les lignes ayant des champs rempli (et un body > 60 caracteres).

Les colonnes To, From et Subject du dataset sont extremement pollués, ne veulent rien dire, ce qui apporte un resultat de 0 pour toutes les metriques. Ayant fait le test sur 100 emails random ayant les colonnes cités precedemment rempli, la NER semblent bien fonctionner globalement pour les 3 modèles ayant moi même verifier les mails. TinyLlama a un easter egg j'ai l'impression lorsqu'il ne reconnait aucune entitées, le To et le From devienne Jhon Doe.

Malheuresement je n'ai pas pu vous proposer de resultat probant sur cette étude. Veuillez m'en excuser, vous trouverez également en pièce jointe un fichier txt contenant les réponses de mes 3 modèles sur les 100 emails.
Avec plus de temps, une comparaison avec BERT ou LargeBERT donnerait de très de bon résultat.
