# Leilão de Futebol - Versão 15

## Melhorias implementadas:
1. **Estabilidade & Sincronização:** Heartbeat automático P2P, tratamento de exceções na rede e botão "🔄 Sincronizar Tela" caso o navegador de algum convidado oscile.
2. **Força Efetiva Real (11 Vagas):** O cálculo agora divide sempre pelas 11 vagas titulares obrigatórias e aplica penalidade por vaga vazia, impedindo que um time incompleto com 4 craques vença um time completo de 11 jogadores.
3. **Polivalência Defensiva com Ajuste de Overall:** Zagueiros, laterais e volantes podem jogar improvisados em outras posições defensivas, sofrendo redução realista de overall conforme a adaptação do jogador e da posição.
4. **Cooldown de 3 Segundos entre Lances:** Após dar um lance, o jogador aguarda 3 segundos antes de poder dar o próximo lance.
5. **Início Automático & Manual:** Assim que todos os participantes completarem 11 titulares, o leilão encerra e inicia a simulação automaticamente (mantendo o botão do anfitrião para iniciar quando quiser).
6. **Simulação ao Vivo Estilo 7a0:** Transmissão jogo por jogo, gol por gol em tempo real no placar e no feed de lances, com controles de velocidade (1x, 2x, 4x) e atualização dinâmica do chaveamento e da artilharia.
