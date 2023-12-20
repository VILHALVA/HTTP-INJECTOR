# HTTP INJECTOR - SIMULATOR
👨‍💻ESSE É PEQUENO JOGO QUE RODA NO CONSOLE DA IDE.

[![GitHub Repo stars](https://img.shields.io/badge/VILHALVA-GITHUB-03A9F4?logo=github)](https://github.com/VILHALVA)
[![GitHub Repo stars](https://img.shields.io/badge/MEUS-CURSOS-03A9F4?logo=github)](https://github.com/VILHALVA?tab=repositories&q=CURSO&type=public&language=&sort=)

<img src="https://cdn6.aptoide.com/imgs/4/a/1/4a1cb561e6a8be1086f53e8c37aff19f_icon.png" align="center" width="280"> <br>

## DESCRIÇÃO:
Este programa é um simulador interativo de um jogo com temática de HTTP injector e navegação na internet. Aqui está uma descrição mais concisa do que o programa faz:

1. **Configuração inicial:** O programa inicia exibindo uma mensagem de boas-vindas e entra em um loop infinito, criando um menu de IPs disponíveis.

2. **Escolha do IP:** O usuário deve escolher um IP digitando a letra correspondente a partir de um menu apresentado. O programa então gera aleatoriamente um IP associado a uma letra.

3. **Conexão:** O programa simula uma tentativa de conexão, exibindo mensagens de progresso e feedback. Se a escolha do usuário corresponder à conexão gerada aleatoriamente, a conexão é estabelecida com sucesso.

4. **Menu de Sites:** Se a conexão for bem-sucedida, o programa exibe um novo menu com opções de sites. O usuário deve escolher um site digitando a letra correspondente.

5. **Navegação:** O programa simula a abertura do site escolhido, exibe mensagens de progresso e utiliza a biblioteca `webbrowser` para abrir o navegador padrão do sistema com a URL associada ao site escolhido.

6. **Tempo de Conexão:** Após a navegação, o programa conta regressivamente a desconexão, exibindo mensagens de status.

7. **Repetição:** Após a desconexão, o programa retorna ao início do loop, permitindo que o usuário escolha um novo IP e repita o processo.

