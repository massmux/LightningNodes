# LightningNode Group (Telegram)

## IT

Si tratta di un gruppo telegram, assistito da CheeseRobot nel quale si possono pubblicare nodi lightning, canali, rings of fire, al fine di creare connessioni, bilanciamenti, liquidità tra nodi "amici".

### Comandi di base

- /node [public key] - ottieni info su un nodo
- /claim - rivendica un nodo
- /unclaim - togli rivendicazione su un nodo
- /help - cheeserobot help

### Pubblicazione proprio nodo

inviare messaggio al gruppo con questa sintassi

```
#node
[public key]
```

### Pubblicazione di un ring of fire

1) definire un nuovo swap su https://lightningnetwork.plus/swaps/new
2) se necessario autenticare il proprio nodo con la firma
3) creare lo swap privato e pubblicare il link nel gruppo cosi

```
#swap #open
triangle
[link comprensivo di pin]
```

il link è qualcosa del tipo: https://lightningnetwork.plus/swaps/10204 pin:512ebd838c

4) quando il ring è completo, togliere #open e mettere #closed

