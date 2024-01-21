# HTTP INJECTOR - SIMULATOR
👨‍💻ESSE É PEQUENO JOGO QUE RODA NO CONSOLE DA IDE.

<img src="FOTO.png" align="center" width="500"> <br>

## DESCRIÇÃO:
Este programa é um simulador interativo de um jogo com temática de HTTP injector e navegação na internet. Aqui está uma descrição mais concisa do que o programa faz:

1. **Configuração inicial:** O programa inicia exibindo uma mensagem de boas-vindas e entra em um loop infinito, criando um menu de IPs disponíveis.

2. **Escolha do IP:** O usuário deve escolher um IP digitando a letra correspondente a partir de um menu apresentado. O programa então gera aleatoriamente um IP associado a uma letra.

3. **Conexão:** O programa simula uma tentativa de conexão, exibindo mensagens de progresso e feedback. Se a escolha do usuário corresponder à conexão gerada aleatoriamente, a conexão é estabelecida com sucesso.

4. **Menu de Sites:** Se a conexão for bem-sucedida, o programa exibe um novo menu com opções de sites. O usuário deve escolher um site digitando a letra correspondente.

5. **Navegação:** O programa simula a abertura do site escolhido, exibe mensagens de progresso e utiliza a biblioteca `webbrowser` para abrir o navegador padrão do sistema com a URL associada ao site escolhido.

6. **Tempo de Conexão:** Após a navegação, o programa conta regressivamente a desconexão, exibindo mensagens de status.

7. **Repetição:** Após a desconexão, o programa retorna ao início do loop, permitindo que o usuário escolha um novo IP e repita o processo.

## COMO USAR?
**Passo 1:** Clone o repositório para o seu sistema local.

```bash
git clone https://github.com/VILHALVA/HTTP-INJECTOR.git
```

**Passo 2:** Navegue até o diretório do projeto.

```bash
cd HTTP-INJECTOR
```

**Passo 3:** Descompacte o arquivo ZIP (se você baixou manualmente):

```bash
unzip HTTP-INJECTOR.zip
```

**Passo 4:** Execute o executável do projeto.

```bash
./HTTP-INJECTOR
```

## CREDITOS:
- [PROJETO CRIADO PELO VILHALVA](https://github.com/VILHALVA)


