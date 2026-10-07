# Politique de confidentialité — changements proposés pour la v2.8

Option « Mon visage sur le mannequin » (selfie, offre Premium). Document de travail du 07/10/2026 : ce n'est pas le fichier à publier.

- Les textes « actuels » sont ceux de la **v2.6 en ligne** (SHA-256 `99cbae94…ac41`). La v2.7 (RevenueCat), livrée le 07/10 et non publiée, n'est pas sous la main de l'agent : le fichier complet v2.8 sera assemblé sur la v2.7 dès qu'elle est fournie.
- Aucun autre passage n'est modifié. Les articles 1, 3, 4.2, 6.1, 6.3, 6.4, 8 à 13 restent tels quels.
- 14 changements, dans l'ordre du document.

---

## 1. En-tête

**Texte actuel**

```
**Version 2.6 — En vigueur à compter du 04/10/2026**
**Dernière mise à jour : 04/10/2026**
```

**Texte proposé**

```
**Version 2.8 — En vigueur à compter du 07/10/2026**
**Dernière mise à jour : 07/10/2026**
```

*Dates à mettre au jour de la publication.*

---

## 2. Art. 2.2 — tableau : une ligne ajoutée après « Photo de portrait »

**Texte actuel**

```
| Photo de portrait | Affichage dans votre profil | Exécution du contrat |
```

**Texte proposé**

```
| Photo de portrait | Affichage dans votre profil | Exécution du contrat |
| Selfie de l'option « Mon visage sur le mannequin » (photo de votre visage) et date de votre accord — **facultatif**, offre Premium | Placer votre visage sur le mannequin des images de tenues | Votre consentement (article 6(1)(a) du RGPD), donné par une case à cocher au moment où vous fournissez le selfie |
```

*Base légale à confirmer par l'avocat (consentement explicite de l'article 9 si le selfie est regardé comme une donnée biométrique).*

---

## 3. Art. 2.2 — paragraphe « Important »

**Texte actuel**

```
Nedos n'analyse aucune photo de votre visage ou de votre corps ; votre photo de portrait n'est jamais transmise à un service d'intelligence artificielle. Votre palette de couleurs est calculée sur votre appareil à partir de ces choix.
```

**Texte proposé**

```
Nedos ne déduit ni votre teint, ni votre silhouette, ni aucune autre caractéristique d'une photo de votre visage ou de votre corps ; votre photo de portrait n'est jamais transmise à un service d'intelligence artificielle. Votre palette de couleurs est calculée sur votre appareil à partir de ces choix.

**Option « Mon visage sur le mannequin » — seulement si vous l'activez.** Cette option de l'offre Premium, désactivée par défaut, utilise un selfie que vous fournissez pour placer votre visage sur le mannequin des images de vos tenues ; le corps reste celui du mannequin. Vous l'activez depuis votre profil en cochant une case qui confirme qu'il s'agit bien de vous et que vous acceptez la transmission de ce selfie à Google (article 4.1). Le selfie est conservé dans votre espace privé et transmis à Google à chaque génération d'une image de tenue. Nedos n'en tire aucun gabarit biométrique, ne s'en sert pas pour vous identifier ou vous reconnaître, et ne l'utilise ni pour les statistiques de l'article 6 ni pour de la publicité. Il est supprimé dès que vous désactivez l'option, que vous retirez votre accord à la transmission aux services d'intelligence artificielle, ou que votre abonnement Premium prend fin ; les images déjà générées restent enregistrées avec vos tenues jusqu'à ce que vous les supprimiez. Vous ne devez utiliser que votre propre photo, jamais celle d'une autre personne.
```

*La première phrase est resserrée : « n'analyse aucune photo de votre visage » ne serait plus exact, le selfie étant transmis à un service d'IA.*

---

## 4. Art. 2.2 — fin du même paragraphe

**Texte actuel**

```
Les autres données de profil (année de naissance, ville, photo de portrait, préférences) sont facultatives
```

**Texte proposé**

```
Les autres données de profil (année de naissance, ville, photo de portrait, selfie, préférences) sont facultatives
```

---

## 5. Art. 2.3 — tableau, ligne des tenues

**Texte actuel**

```
| Tenues enregistrées et images de tenues générées | Consultation, partage à votre initiative | Exécution du contrat |
```

**Texte proposé**

```
| Tenues enregistrées et images de tenues générées (avec votre visage si vous avez activé l'option « Mon visage sur le mannequin ») | Consultation, partage à votre initiative ; les images partagées depuis l'application portent la mention « Image générée par IA » | Exécution du contrat |
```

---

## 6. Art. 2.3 — dernier paragraphe

**Texte actuel**

```
Nedos ne vous demande jamais de photographier une personne. Nous vous recommandons de photographier vos vêtements seuls, sans personne identifiable.
```

**Texte proposé**

```
Pour votre garde-robe, Nedos ne vous demande jamais de photographier une personne : nous vous recommandons de photographier vos vêtements seuls, sans personne identifiable. La seule photo d'une personne que Nedos peut recevoir de vous, en dehors de votre photo de portrait, est votre propre selfie, si vous activez l'option « Mon visage sur le mannequin » (article 2.2).
```

---

## 7. Art. 2.5

**Texte actuel**

```
votre navigation en dehors de l'application, ni aucune donnée biométrique. Si vous activez le verrouillage
```

**Texte proposé**

```
votre navigation en dehors de l'application, ni aucun gabarit biométrique permettant de vous reconnaître. Le selfie de l'option « Mon visage sur le mannequin » (article 2.2) est une photo que vous fournissez vous-même, seulement si vous activez cette option : Nedos ne s'en sert pas pour vous identifier. Si vous activez le verrouillage
```

*Point pour l'avocat : qualification du selfie (article 9 du RGPD, considérant 51).*

---

## 8. Art. 4.1 — tableau, ligne Google

**Texte actuel**

```
| **Google LLC** (Gemini) | Photos et caractéristiques des vêtements ; genre ; âge approximatif (calculé à partir de l'année de naissance) ; silhouette ; teint et sous-ton | Détourage des photos de vêtements, génération des images de tenues (mannequin sans visage) |
```

**Texte proposé**

```
| **Google LLC** (Gemini) | Photos et caractéristiques des vêtements ; genre ; âge approximatif (calculé à partir de l'année de naissance) ; silhouette ; teint et sous-ton ; **votre selfie, uniquement si vous avez activé l'option « Mon visage sur le mannequin »** | Détourage des photos de vêtements, génération des images de tenues (mannequin sans visage, ou portant votre visage si vous avez activé l'option) |
```

---

## 9. Art. 4.1 — « Ne sont jamais transmis »

**Texte actuel**

```
**Ne sont jamais transmis à ces prestataires** : votre adresse e-mail, votre nom, votre photo de portrait, ni aucun identifiant de compte.
```

**Texte proposé**

```
**Ne sont jamais transmis à ces prestataires** : votre adresse e-mail, votre nom, votre photo de portrait, ni aucun identifiant de compte. Votre selfie n'est transmis qu'à Google, jamais à Anthropic, et seulement tant que l'option « Mon visage sur le mannequin » est activée.
```

---

## 10. Art. 4.1 — « Votre accord préalable », phrase ajoutée avant la dernière

**Texte actuel**

```
plus aucune donnée n'est alors transmise, et l'accord vous est redemandé avant toute nouvelle utilisation. Tout nouveau prestataire
```

**Texte proposé**

```
plus aucune donnée n'est alors transmise, et l'accord vous est redemandé avant toute nouvelle utilisation. L'option « Mon visage sur le mannequin » demande en plus un accord propre, donné par une case à cocher au moment où vous fournissez votre selfie ; vous le retirez en désactivant l'option dans votre profil, et retirer votre accord général désactive aussi cette option et supprime votre selfie. Tout nouveau prestataire
```

---

## 11. Art. 5 — une ligne ajoutée après la première ligne du tableau

**Texte actuel**

```
| Toutes ces données après une demande de suppression du compte |
```

**Texte proposé**

```
| Selfie de l'option « Mon visage sur le mannequin » | Tant que l'option est activée. Supprimé dès que vous la désactivez, que vous retirez votre accord à la transmission aux services d'intelligence artificielle (article 4.1) ou que votre abonnement Premium prend fin ; lorsque vous le remplacez, l'ancien selfie est supprimé. Les images de tenues générées avec votre visage sont conservées comme vos autres images de tenues. |
| Toutes ces données après une demande de suppression du compte |
```

---

## 12. Art. 5 — ligne des preuves

**Texte actuel**

```
| Preuve de votre consentement (article 6), de votre accord à la transmission aux services d'intelligence artificielle (article 4.1) et de l'acceptation des CGU | Pendant toute la durée du compte |
```

**Texte proposé**

```
| Preuve de votre consentement (article 6), de votre accord à la transmission aux services d'intelligence artificielle (article 4.1) et de l'acceptation des CGU | Pendant toute la durée du compte |
| Date de votre accord à l'option « Mon visage sur le mannequin » | Tant que l'option est activée |
```

*Même question pour l'avocat que pour l'accord IA : la date est effacée quand l'option est désactivée.*

---

## 13. Art. 6.2

**Texte actuel**

```
Vos photos, votre adresse e-mail, votre nom et votre portrait ne sont jamais utilisés pour ces statistiques, pas plus que les noms de vos groupes de tenues ni votre planning.
```

**Texte proposé**

```
Vos photos, votre selfie, les images de vos tenues, votre adresse e-mail, votre nom et votre portrait ne sont jamais utilisés pour ces statistiques, pas plus que les noms de vos groupes de tenues ni votre planning. Votre selfie et les images générées avec votre visage ne servent à aucun ciblage publicitaire.
```

---

## 14. Art. 7 — effacement définitif

**Texte actuel**

```
ainsi que toutes vos photos et images (vêtements, tenues, portrait) — sont effacés définitivement
```

**Texte proposé**

```
ainsi que toutes vos photos et images (vêtements, tenues, portrait, selfie) — sont effacés définitivement
```
