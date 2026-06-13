# projeto-loja-virtual-
Aplicação comercial de e-commerce interativa desenvolvida com foco em Eventos JavaScript. O sistema possui vitrina fluida de produtos de panificação, controles e acionamentos dinâmicos de carrinho, contadores de porções, barra de busca e filtragem em tempo real, além de um formulário de cadastro seguro 
https://tatiane347.github.io/projeto-loja-virtual-/


🥖 Padaria Doce Sabor - Loja Virtual Interativa

Prática 11 & 12 - Programação Web (120h) > Estudante: Tatiane Nascimento De Souza Instituição: Escola Técnica FAT Tecnologias Utilizadas: HTML5, CSS3, JavaScript (ES6), Git e GitHub Pages

🔗 Links de Acesso

Repositório Oficial:
 https://github.com/tatiane347/projeto-loja-virtual- 

Site Ativo no Ar (GitHub Pages):
 https://tatiane347.github.io/projeto-loja-virtual-/

📝 Descrição do Projeto

Este projeto simula uma Loja Virtual Interativa de Delivery para a fictícia Padaria Doce Sabor. A aplicação foi projetada e estruturada para demonstrar o controle dinâmico de interações do utilizador num navegador web sem a necessidade de recarregar a página (Single Page Application - SPA básica).

O layout adota uma filosofia Mobile-First com cores acolhedoras inspiradas em panificação artesanal, assegurando perfeita legibilidade e acessibilidade tanto em telemóveis como em ecrãs de computadores (desktops).

⚡ Eventos JavaScript Implementados (Atividade 1 a 5)

Para satisfazer as exigências da Prática 11, o projeto implementa de forma avançada os seguintes eventos interativos utilizando a abordagem recomendada do addEventListener():

load (Carregamento da Página):

Inicializa de forma segura todas as lógicas de monitorização do sistema e exibe uma notificação flutuante acolhedora de boas-vindas ao utilizador assim que a página é totalmente carregada.

click (Interações e Controles Básicos):

Contador de Quantidade: Botões de + e - para ajustar a quantidade de produtos de forma visual e reativa.

Ver Detalhes: Botão interativo que revela ou esconde informações sobre a receita e os ingredientes específicos de cada item.

Adicionar ao Carrinho: Processa o cálculo do preço, soma os valores e adiciona a linha de registo com a quantidade certa no histórico do carrinho.

Limpar Carrinho: Botão com evento de clique que solicita confirmação de segurança (popup) antes de esvaziar os itens acumulados.

mouseover e mouseout (Interações Visuais do Rato):

Efeito Hover: Ao passar o cursor (mouse) sobre as imagens dos produtos, a foto principal é trocada de forma fluida por uma foto do interior da receita (foto de hover) e o card inteiro ganha uma borda destacada e sombra visual. Ao retirar o rato, o estado original é restaurado.

keyup (Interações do Teclado e Filtros):

Barra de Pesquisa: Filtra instantaneamente a vitrina de produtos ocultando aqueles que não batem com as palavras-chave que o utilizador está a escrever.

Medidor de Senha: Analisa a palavra-passe do checkout em tempo real à medida que o utilizador digita, aumentando uma barra gráfica e alterando a cor para verde (forte), laranja (média) ou vermelho (fraca).

keydown (Atalhos e Acessibilidade):

Navegação: Permite navegar e focar os cards dos produtos de forma visual apenas utilizando as setas direcionais do teclado (← e →).

Atalho de Compra: Atalho global utilizando a combinação Ctrl + Enter que foca e rola o ecrã automaticamente para o formulário de finalização de compras rápida se o carrinho tiver itens.

input (Validações de Formulário):

Valida instantaneamente a estrutura do campo de e-mail ao ser digitado, alertando o utilizador em tempo real caso o padrão de e-mail seja inválido.
<img width="712" height="1280" alt="Screenshot_20260613-174136_Chrome" src="https://github.com/user-attachments/assets/1556a9cc-1b20-48d3-8190-701fe4fc0a49" />
<img width="712" height="1280" alt="Screenshot_20260613-174120_Chrome" src="https://github.com/user-attachments/assets/6b715d1c-c902-4b55-85f5-deba21770f18" />
<img width="712" height="1280" alt="Screenshot_20260613-174110_Chrome" src="https://github.com/user-attachments/assets/6c947996-3c8b-4b86-8d2c-020fdb6526a3" />
<img width="712" height="1280" alt="Screenshot_20260613-174049_Chrome" src="https://github.com/user-attachments/assets/1ed8c1d3-ecd6-4591-9a74-fa585a47ab20" />

submit (Envio Seguro de Dados):

Intercepta o envio do formulário através de e.preventDefault(), realiza uma última validação de segurança nos dados obrigatórios e exibe uma mensagem personalizada de sucesso antes de resetar o carrinho.

🛠️ Tecnologias e Recursos

Estrutura: HTML5 com tags semânticas para melhor indexação e SEO (header, main, section, article, footer).

Estilização: CSS3 puro e responsivo focado em grelhas flexíveis (Grid Layout) e alinhamentos fluídos (Flexbox).

Lógica Dinâmica: JavaScript (ES6) nativo focado em manipulação do DOM e escuta de eventos.

Hospedagem: GitHub Pages.

📂 Estrutura de Arquivos do Repositório

projeto-loja-virtual/
├── index.html     # Página principal da aplicação com CSS e JS integrados
└── README.md      # Documentação detalhada do projeto

👤 Autoria

Desenvolvedora: Tatiane Nascimento De Souza

Trabalho Conclusivo das Práticas de Programação Web * Escola Técnica FAT - Junho de 2026

