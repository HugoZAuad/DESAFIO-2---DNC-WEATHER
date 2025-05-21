# DNC Weather

## Descrição do Projeto

DNC Weather é uma aplicação web simples que oferece previsões do tempo e informações de endereços em tempo real. A interface é responsiva e estilizada para proporcionar uma boa experiência de usuário em diferentes tamanhos de tela, incluindo telas muito grandes (até 2560px de largura).

---

## Estrutura do Código

### 1. `index.html`

Este arquivo contém a estrutura principal da página web, organizada em seções semânticas:

- **Cabeçalho (`header`)**  
  Contém o título do site "DncWeather" e um menu de navegação com opções "Endereços" e "Previsão do tempo".

- **Barra Lateral (`aside`)**  
  Apresenta uma mensagem de destaque sobre o serviço e uma imagem ilustrativa.

- **Conteúdo Principal (`main`)**  
  Formulário para o usuário inserir seu primeiro nome, e-mail, CEP, latitude e longitude para obter a previsão do tempo e informações de endereço.

- **Seção de Resultado da Busca por CEP (`section`)**  
  Exibe o resultado da busca com uma tabela contendo logradouro, bairro e localidade.

- **Seção de Previsão do Tempo (`section`)**  
  Mostra a previsão do tempo na região com texto e imagens ilustrativas.

- **Rodapé (`footer`)**  
  Contém links para "Termos de Uso" e "Política de Privacidade".

### 2. `style.css`

Arquivo responsável pela estilização da página, com as seguintes características principais:

- **Estilos Globais**  
  Define fonte Montserrat, cores de fundo, margens e padding padrão.

- **Layout com Flexbox**  
  Utilizado em vários elementos como `header`, `aside`, `main`, e `footer` para organizar o conteúdo em linhas e colunas.

- **Responsividade**  
  Contém media queries para diferentes larguras de tela:  
  - Até 600px: Ajustes para dispositivos móveis, com layout em coluna e fontes menores.  
  - Entre 601px e 1024px: Ajustes para tablets e telas médias.  
  - Acima de 1025px: Layout para desktops padrão.  
  - Acima de 2560px: Centraliza todo o conteúdo horizontalmente para telas muito largas, ajustando margens e alinhamentos.

- **Estilização de Componentes**  
  - Botões com cores e efeitos de hover.  
  - Tabela estilizada com cores, bordas arredondadas e alinhamento central.  
  - Imagens responsivas com largura máxima e altura automática.

---

## Como Usar

1. Abra o arquivo `index.html` em um navegador moderno.  
2. Insira os dados solicitados no formulário principal (nome, e-mail, CEP, latitude e longitude).  
3. Clique no botão "Acessar" para visualizar as informações de endereço e previsão do tempo.  
4. A página se adapta automaticamente ao tamanho da tela, garantindo boa visualização em dispositivos móveis, tablets, desktops e telas muito grandes.

---

## Considerações Finais

Este projeto é uma base para um sistema de consulta de previsão do tempo e endereços, com foco em usabilidade e design responsivo. Pode ser expandido com funcionalidades de backend para integração com APIs reais de clima e geolocalização.
