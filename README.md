# Pizza Yassin — Système de commande par QR code

Snack à Salé — Rue Said Taib Alaoui, Corniche Sidi Moussa.
Pizzas cuites au feu de bois, tacos, pasticcio, tacos gratiné, pakidwich.
Ouvert 12h–02h, 7j/7. Tél snack : 0622 647 629 — Livraison : 0644 523 052.

## Pages

- `yassin-menu.html` — menu public
- `yassin-order.html?table=N&t=<token>` — commande client (tables 1–12, QR token)
- `yassin-counter.html` — comptoir (PIN, commandes live, Stats + Top plats)

## Système

- 41 plats commandables (20 pizzas M/L, 6 tacos, 5 pasticcio, 6 tacos gratiné, 4 pakidwich)
- Boissons (Sidi Ali, Limonades, Jus d'Orange) : prix à confirmer, menu seulement pour l'instant
- Firebase (projet thon-3s-orders) : `yassin-orders` / `yassin-availability` / `yassin-cancelled`
- Comptoir protégé par PIN (4 chiffres, à choisir par le propriétaire), verrouillage 30 s après code faux
- Commande par QR token uniquement, son deux-tons à chaque commande, Stats du jour + Top plats
- Sur place / À emporter, note client, plats "Makaynch", additions par table, Payé

## Liens (GitHub Pages)

- Menu : https://darwinnamosa-gif.github.io/pizza-yassin/yassin-menu.html
- Comptoir : https://darwinnamosa-gif.github.io/pizza-yassin/yassin-counter.html
