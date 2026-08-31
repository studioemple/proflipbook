# Rentlio Pro — interaktivna brošura (flipbook)

Interaktivna web brošura s realističnom page-flip animacijom ([StPageFlip](https://github.com/Nodlik/StPageFlip)).

## Pokretanje
Otvori `index.html` u browseru, ili posluži folder bilo kojim static serverom:

```bash
python3 -m http.server 5599
```

## Responzivnost
- **≥ 1024px** — desktop edicija: 16 kvadratnih stranica, prikaz kao otvorena knjiga (spread)
- **< 1024px** — mobilna edicija: 13 vertikalnih stranica, jedna po prikazu

Upravljanje: povlačenje ruba stranice mišem, klik na rub, tipke ←/→, swipe na mobitelu.
