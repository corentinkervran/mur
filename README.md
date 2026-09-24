# Mur

Mur de messages pour la borne du bureau. Une seule page, sans backend.

- `https://corentinkervran.github.io/mur/` : sur un téléphone, on écrit un mot.
- `https://corentinkervran.github.io/mur/?borne` : sur la borne, plein écran, le mur.

Transport : un topic [ntfy.sh](https://ntfy.sh) (nom dans `.topic`, aussi codé en dur dans `index.html`). ntfy garde les messages 12 h ; la borne les garde dans son localStorage.
