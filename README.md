🚀 elha, aconselha — Consultoria em Transformação Digital

🔗 Acesse o Aplicativo Online (GitHub Pages): Clique aqui para abrir o App

Diagnóstico 360º de Maturidade Digital (ERP, CRM, Nuvem e IA), desenvolvido como apoio ao Plano de Modernização e Transformação Digital da VarejoAtivo (trabalho A3).

👥 Especialistas Responsáveis (Autores)
Eduardo Daniel Gonçalves Pereira
Andriele de Oliveira Antunes
Douglas de Almeida Ruver
João Henrique Marchetto Vieira
Gustavo Leão da Silva

Unidade Curricular: Exploração Digital e Fundamentos Tecnológicos (Objetos de Conhecimento 05 e 06)
Docentes: Clarissa Carneiro Mussi e Rodrigo Brandelero
🎯 1. O Problema Empresarial e Objetivo do Aplicativo

Muitas empresas, como a VarejoAtivo (12 lojas, e-commerce e cerca de 220 colaboradores), sabem que precisam se modernizar, mas convivem com sistemas isolados, planilhas e conferências manuais, infraestrutura local sujeita a quedas em picos como Black Friday e Natal, ausência de uma visão gerencial única e equipes com níveis desiguais de familiaridade digital. O elha, aconselha ajuda a responder "por onde começar?": a empresa responde a 8 perguntas estratégicas e recebe um Índice de Maturidade Digital (0 a 100%), um gráfico radar e um Laudo de Boas Práticas priorizado, apoiando decisões de forma gradual, como em um projeto-piloto.

🏛 2. Os 4 Pilares de Boas Práticas Aplicados no Diagnóstico
☁ Infraestrutura e Migração para a Nuvem: avalia elasticidade em picos e política de backup; recomenda SaaS, PaaS ou IaaS conforme o cenário, backup 3-2-1 automatizado, redundância de link e monitoramento de custos (FinOps).
🔄 Sistemas Empresariais (ERP/CRM) e Fluxo de Dados: avalia a integração entre vendas, estoque e financeiro e o acompanhamento de indicadores; recomenda integração via APIs, fonte única da verdade (Single Source of Truth) e dashboards em tempo real, eliminando silos de planilhas.
🤖 IA Generativa e Automação No-Code: identifica o grau de automação de tarefas repetitivas e o uso de IA; recomenda fluxos No-Code (marketing → venda → estoque) e assistentes de IA com revisão humana (Human-in-the-Loop).
🛡 Governança, Ética e Segurança Digital (LGPD): avalia controles de acesso, adequação à LGPD, capacitação e política de IA; recomenda MFA, menor privilégio, anonimização de dados, uso ético de IA e programa contínuo de treinamento.
Como o app funciona
Etapa	Descrição
Entrada	Nome da empresa, setor, porte e 8 perguntas (2 por pilar), com 5 opções de 0 a 4 pontos
Cálculo	Nota do pilar = (soma ÷ 8) × 100; nota geral = média dos 4 pilares, tudo em JavaScript, sem recarregar a página
Classificação	0–29% Iniciante · 30–59% Em Transição · 60–84% Conectada · 85–100% Líder Digital
Saída	Cards por pilar, gráfico radar (Chart.js) e laudo de recomendações priorizado pelos pilares de menor nota
Extras	Botão "Carregar Empresa Exemplo (VarejoAtivo)" e botão "Imprimir / Salvar Laudo em PDF"
Conexão com o Plano de Modernização (A3)

As perguntas do app foram desenhadas a partir dos requisitos do diagnóstico da VarejoAtivo: R1 (integração de sistemas), R2 (visão única do cliente e LGPD), R3 (nuvem elástica), R4 (dashboards em tempo real) e R5 (transição gradual e capacitação).

🛠 3. IAs Generativas e Ferramentas Utilizadas
Ferramenta / IA	Como foi utilizada no projeto
Claude (Anthropic)	Adaptação do prompt mestre ao caso VarejoAtivo, definição das perguntas, pesos e faixas de classificação do diagnóstico e redação da documentação. (Ajuste conforme as IAs que a equipe realmente usou para gerar o código.)
[PREENCHER: ex. Gemini / ChatGPT / Claude Artifacts / v0 / Bolt / Lovable]	Geração e refinamento do código HTML/JS do index.html.
TailwindCSS & Chart.js (CDN)	Estilização executiva responsiva e geração do gráfico radar dinâmico de maturidade.
GitHub & GitHub Pages	Versionamento de código e publicação em nuvem estática (PaaS/CDN).
🧠 4. Diário de Construção: Como Construímos e Refinamos o App
Concepção e Engenharia de Prompt: Escolhemos a Opção B (Diagnóstico 360º) por ser a que mais se alinha às seções do nosso plano A3 (nuvem, ERP/CRM, dados, automação, pessoas e segurança). O prompt inicial deu à IA o papel de engenheiro sênior e consultor, descreveu o caso VarejoAtivo, definiu as 8 perguntas com pontuação 0 a 4, as faixas de classificação, o formato de arquivo único index.html e o aviso de Privacy by Design.
Ajustes e Refinamentos Técnicos: [PREENCHER com o que a equipe realmente pediu após o primeiro teste. Sugestões de pontos a registrar: diferenciação de SaaS/PaaS/IaaS no pilar de Nuvem; etiquetas de requisito (R1–R5) nas recomendações; CSS de impressão do laudo; validação de perguntas não respondidas.]
Principal Aprendizado: [PREENCHER com o aprendizado real da equipe sobre Transformação Digital, Nuvem e IA.]
🔒 Privacy by Design (LGPD)

Todos os dados informados são processados localmente no navegador do usuário. O aplicativo não envia nem armazena informações em bancos de dados ou servidores externos.

▶️ Como executar localmente
Baixe o arquivo index.html.
Dê dois cliques para abri-lo no navegador (requer internet para carregar Tailwind e Chart.js via CDN).
Clique em Carregar Empresa Exemplo para ver uma demonstração.
