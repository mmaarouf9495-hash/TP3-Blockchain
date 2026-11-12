# Analyse détaillée d'une transaction Bitcoin sur TestNet4

## 1. Présentation du projet

Ce travail consiste à analyser une transaction Bitcoin réalisée sur le réseau TestNet4 afin de comprendre son fonctionnement et les différentes étapes de son exécution.

## 2. Identification de la transaction

- **Identifiant de transaction (TxID) :** 97ad267395a4d905d7af521c8b2edcf3da04504b0b03c5b145f9933a8bed585c
- **Réseau utilisé :** Bitcoin TestNet4
- **Date et heure :** 25/10/2026 à 02:52:43
- **Nombre de confirmations affiché :** 3 079

## 3. Analyse des entrées (Inputs)

La transaction contient une seule entrée :

- **Nombre d'entrées :** 1
- **Montant :** 0,00348326 tBTC
- **Type de script précédent :** V1_P2TR (Taproot)

L'entrée représente les fonds utilisés pour financer la transaction. Elle fait référence à un UTXO (Unspent Transaction Output), c'est-à-dire une sortie de transaction précédente qui n'a pas encore été dépensée.

## 4. Analyse des sorties (Outputs)

La transaction contient deux sorties :

- **Première sortie :** 0,000001236 tBTC, de type V1_P2TR.
- **Deuxième sortie :** 0,00345854 tBTC, de type V0_P2WPKH.

Les sorties correspondent aux montants destinés aux adresses bénéficiaires. Chaque sortie crée un nouvel UTXO qui pourra être utilisé dans une transaction future.

## 5. Frais de transaction

D'après les informations affichées sur Mempool :

- **Frais indiqués :** 1 236 satoshis.
- **Taux de frais :** 8,70 sat/vB.
- **Taille virtuelle :** 142 vB.

Les frais de transaction représentent le montant attribué au mineur pour inclure la transaction dans un bloc.

## 6. Confirmations

La transaction affiche 3 079 confirmations sur Mempool.

Une confirmation signifie que la transaction a été incluse dans un bloc Bitcoin. Plus le nombre de confirmations augmente, plus la transaction est considérée comme difficile à modifier.

## 7. Détails techniques

- **Taille :** 193 octets.
- **Taille virtuelle :** 142 vB.
- **Poids :** 568 WU.
- **Version :** 2.
- **Temps de verrouillage :** 157 413.
- **Sigops :** 0.

## 8. Conclusion

Cette analyse permet de comprendre la structure d'une transaction Bitcoin sur TestNet4. Elle montre le rôle des entrées, des sorties, des frais et des confirmations dans le fonctionnement de la blockchain Bitcoin.

## 9. Sources

- Mempool.space – Explorateur Bitcoin TestNet4.
- Support de cours TP2 – Bitcoin, Wallets et TestNet4.
- Documentation Bitcoin.

## 10. Outils utilisés

- GitHub
- GitHub Desktop
- Mempool.space
- Assistant d'intelligence artificielle pour l'accompagnement et les explications.
Liens de vérification des transactions:
  Transaction 1 : 97ad267395a4d905d7af521c8b2edcf3da04504b0b03c5b145f9933a8bed585c
