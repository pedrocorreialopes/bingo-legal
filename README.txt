# Bingo 75 — Chamador Digital

Abra `index.html` em um navegador moderno. Não requer instalação nem servidor.

## Arquivos
- `index.html`: estrutura da aplicação
- `style.css`: identidade visual responsiva
- `script.js`: sorteio, controles, persistência, recuperação, pedra maior, sons e modo telão

## Persistência e privacidade
O estado é gravado no `localStorage` do navegador. Os dados permanecem neste perfil/dispositivo; limpar os dados do navegador, usar janela anônima ou trocar de dispositivo pode removê-los/não disponibilizá-los. Para segurança adicional, faça cópias do perfil do navegador ou exporte o armazenamento antes de manutenção.

## Operação
1. Clique em **Iniciar jogo** para iniciar o sorteio automático (se habilitado).
2. Use **Sortear próxima** para sortear manualmente.
3. Pause/continue conforme necessário.
4. Use **Recuperar** para restaurar a partida atual, o backup ou o último jogo finalizado.
5. Use **Pedra Maior** para desempate independente.
6. Ative **Modo telão** ou **Tela cheia** para projetar.

Os sons são sintetizados pela Web Audio API e podem depender de uma interação inicial do usuário e das permissões do navegador. A fonte externa é apenas decorativa; o sistema funciona sem ela.
