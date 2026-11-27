# RC Riding Club

Jogo de motas ao estilo GTA 2 em pixel art: cidade de Londres com o Tamisa, missões do clube nas cabines telefónicas, polícia, corridas, garagem com 19 motas (125cc até 2458cc, marcas fictícias) e mini-jogos 3D (oficina, bombas, café e arrancada).

- **Jogo:** `www/rc-riding-club/` (`index.html` + `three.min.js`). Com o GitHub Pages ativo fica em `/rc-riding-club/`.
- **CrazyGames:** cada alteração ao jogo gera o ZIP em **Actions → RC Riding Club - pacote CrazyGames**, já com o SDK v3 para anúncios.
- **Android:** passos em [`ANDROID.md`](ANDROID.md) (Capacitor, AdMob e compras no Google Play).

## Monetização
- Anúncios com recompensa opcionais: duplicar o pagamento da missão, reparar a mota, atestar o depósito, limpar as estrelas da polícia e duplicar o prémio diário.
- Anúncios intercalares só entre missões ou à saída de mini-jogos, no máximo 1 a cada 3 minutos. Nunca durante a condução.
- Compras cosméticas (versão Android): pinturas especiais, capacetes, casacos do clube e Pack Lenda.
- Merch: em `index.html`, preenche `merchUrl` em `const CFG=` com o site da loja do clube.

Fora da CrazyGames e do Android, anúncios e compras funcionam em modo de demonstração.
