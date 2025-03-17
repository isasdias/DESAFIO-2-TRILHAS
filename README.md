#Desafio 2 - Trilhas 2B

Este projeto é um formulário de inscrição para o programa Trilhas, desenvolvido como parte de um desafio. O formulário coleta informações pessoais, dados de contato, endereço e permite que o usuário selecione uma trilha de aprendizagem. Ele é estilizado utilizando CSS para garantir uma interface limpa e responsiva.

## Colaboradores

- [Israel2705](https://github.com/israel2705)
- [Isasdias](https://github.com/isasdias)

## Estrutura do Projeto

O projeto consiste em dois arquivos principais:

- **HTML** (`index.html`): Estrutura da página, incluindo o formulário de inscrição.
- **CSS** (`css/style.css`): Estilo da página, com foco na responsividade e usabilidade.

### Funcionalidades

- **Cabeçalho**: Exibe um título, uma seta de "voltar" e uma breve descrição sobre o formulário.
- **Formulário de Inscrição**:
  - Campos para nome completo, data de nascimento, CPF, sexo, e-mail, telefone e upload de documentos.
  - Validação do e-mail, com um alerta exibido quando o e-mail inserido é inválido.
  - Seção para o endereço residencial, incluindo CEP, rua, número, cidade e estado, além de upload de comprovante de residência.
- **Seleção de Trilha de Aprendizagem**: Permite que o usuário selecione apenas uma trilha de aprendizagem entre várias opções, como Programação Front-end, Back-end, Programação de Jogos, Design e Experiência, e Ciência de Dados.
- **Declaração**: O usuário deve marcar uma caixa de seleção confirmando que leu e concorda com os Termos e Condições.
- **Botões de Ação**: Inclui botões para cancelar ou finalizar a inscrição.

## Instalação

1. Clone o repositório ou baixe os arquivos.
2. Certifique-se de que o arquivo `css/style.css` esteja corretamente vinculado ao arquivo HTML.
3. Abra o arquivo `index.html` em seu navegador para visualizar o formulário.

```bash
git clone https://github.com/seu-usuario/desafio-trilhas.git
cd desafio-trilhas
