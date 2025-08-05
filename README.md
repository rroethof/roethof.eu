# roethof.eu

Dit is de broncode voor de website [roethof.eu](https://roethof.eu).

## Lokale ontwikkeling

Volg deze stappen om een volledige lokale kopie van de repository op te zetten, inclusief de benodigde submodules.

1.  **Clone de repository:**

    ```bash
    git clone https://github.com/rroethof/roethof.eu
    ```

2.  **Navigeer naar de projectmap:**

    ```bash
    cd roethof.eu
    ```

3.  **Initialiseer en update de submodules:**

    Deze repository maakt gebruik van Git submodules. Haal deze als volgt binnen:
    ```bash
    git submodule update --init --recursive
    ```

Hierna is de lokale kopie compleet en klaar voor gebruik.

## Hugo Server

Om de website lokaal te bekijken, start je de Hugo server:

```bash
hugo server
```

Open vervolgens je browser en navigeer naar `http://localhost:1313/`.
