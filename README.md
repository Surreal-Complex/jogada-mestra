# Jogada Mestra

Site estático em português com 12 jogos e laboratórios matemáticos. Funciona no GitHub Pages, sem servidor, cadastro, instalação ou dependências.

## Abrir
Abra `index.html` em um navegador. Para publicar, envie `index.html`, `style.css` e `app.js` para a raiz de um novo repositório público no GitHub. Em **Settings → Pages**, selecione **Deploy from a branch**, branch **main**, pasta **/(root)** e salve. O GitHub exibirá o endereço de acesso após a publicação.

## Recursos
- Uma aba para cada um dos 12 exercícios, com regras reescritas e identidade própria.
- Três variações adicionais por jogo, exceto Paridade secreta, que oferece os dois modos e novas rodadas aleatórias.
- Modo de dois jogadores no mesmo dispositivo nos jogos competitivos; computador nos jogos 1, 2, 3, 4 e 10.
- Simulações individuais nos jogos 8, 9, 11 e 12.
- Pistas e análise matemática recolhíveis; dois campos de escrita por jogo.
- Respostas guardadas em localStorage; exportação de todos os registros em TXT.
- Não há coleta, sincronização ou entrega automática ao professor. Exporte o caderno para entregar. Partidas reiniciam ao trocar de aba; textos são preservados.
- Layout responsivo para computador e celular, rótulos acessíveis e navegação por teclado.
- O tabuleiro do jogo 7 usa dimensões reduzidas; a análise inclui o caso geral de lado 2026.

## Editar
Em `app.js`, o vetor `games` contém títulos, regras, estratégias e exemplos. `style.css` controla aparência e responsividade. Para conferir as regras automatizadas, execute `node test.cjs` na pasta do site.

## Observação pedagógica
Os textos argumentativos não recebem avaliação automática. Incentive demonstrações e a comparação entre diferentes estratégias. A igualdade de probabilidades no modo módulo 3 é condicionada à distribuição equilibrada das classes de restos, como explicitado nas pistas.
