# Dictionnaire de données

Fichier : `Projet2_Donnees_Commercial.xlsx`

| Feuille | Lignes | Rôle | Colonnes principales |
|---|---|---|---|
| `ventes` | 330 | Table de faits (1 ligne = 1 produit commandé) | N° Cmde, Date Cdme, N° Client, Nom Client, Commerciaux, Shipped Date, Ship Name, Type Paiment, Nom Produit, Quantité, Revenue, Frais Expédition, JOURS |
| `Clients` | 30 | Dimension clients | N° Client, Nom Client, Adresse, Code_ville, Ville |
| `Codeville` | 12 | Référentiel des villes | Code_ville, Ville |
| `Commerciaux` | 9 | Dimension commerciaux | Commerciaux, Code_région, Region |
| `Coderégion` | 4 | Référentiel des régions | Code_région, Region |
| `shipper` | 18 | Dimension livreurs | Shipper Name, Ship Name, Ship Address, Ship City |
| `Produits` | 46 | Dimension produits | Nom Produit, Categories, Prix Unitaire |

## Notes
- `JOURS` : délai de livraison en jours.
- `Revenue` : chiffre d'affaires de la ligne ; `Frais Expédition` : frais associés.
- Valeurs manquantes dans `ventes` : `Shipped Date` (39), `Type Paiment` (63), `Nom Produit` (3).
- Données fictives.
