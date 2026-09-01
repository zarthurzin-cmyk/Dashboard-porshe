Porsche Analytics Dashboard 🏎️

Dashboard financeiro interativo com insights de vendas de veículos Porsche, construído em HTML, CSS e JavaScript puro, com identidade visual inspirada no design system da Porsche (preto, vermelho 
#D5001C e tipografia Roboto).

🔗 Demo

Ver dashboard ao vivo »

Repositório: github.com/zarthurzin-cmyk/Dashboard-porshe

🤖 Sobre o desenvolvimento

Este projeto foi desenvolvido com apoio de Inteligência Artificial (prompt engineering + IA generativa para geração de código), com curadoria, ajustes e testes feitos por mim. A ideia, a estrutura de dados, os filtros e as decisões de UX/insights do dashboard foram definidos e validados manualmente.

📊 Sobre o projeto

O dashboard consome uma base de vendas (modelo, ano, preço, forma de pagamento, cidade e estado) e gera, em tempo real, indicadores e visualizações que respondem aos filtros aplicados pelo usuário — sem nenhum backend, tudo roda no navegador.

Funcionalidades
Filtros globais dinâmicos: Modelo, Ano, Forma de Pagamento, Estado e Cidade, combináveis entre si.
KPIs em destaque: modelo mais vendido (com volume), ano de modelo em maior destaque, receita total e ticket médio — todos recalculados a cada filtro.
Gráficos interativos (Chart.js):
Volume de vendas por modelo (top 8).
Distribuição da receita por forma de pagamento.
Tabela de insights regionais: cruza cidade/estado com o modelo mais vendido em cada praça.
Design responsivo: layout adapta de desktop a mobile.
Zero dependências de build: um único arquivo .html, sem necessidade de servidor, framework ou instalação.
🛠️ Tecnologias
HTML5 + CSS3 (variáveis CSS, Flexbox)
JavaScript (Vanilla JS — manipulação de DOM e lógica de filtros)
Chart.js via CDN
🚀 Como rodar localmente

Não é necessário instalar nada. Basta baixar o repositório e abrir o arquivo no navegador:

bash
git clone https://github.com/zarthurzin-cmyk/Dashboard-porshe.git
cd Dashboard-porshe

Depois é só abrir o .html (duplo clique ou arrastar para o navegador).

📁 Estrutura
├── dashboard_porsche_responsivo_luxo.html   # aplicação completa (HTML + CSS + JS)
└── README.md
💡 Próximos passos
 Conectar a uma fonte de dados real (API/CSV) no lugar dos dados mockados
 Adicionar exportação dos dados filtrados (CSV/PDF)
 Novo gráfico de evolução de receita ao longo do tempo
👤 Autor

Arthur Lobo Desenvolvido com apoio de IA generativa.
