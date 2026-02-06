# Projeto DIO - Bruno L Mendes - APP Conversacional de Finanças Pessoais 

## PRD refinado do COPILOT WEB

## 1. Problema
Usuarios iniciantes em financas frequentemente abandonam apps tradicionais por exigirem insercao manual excessiva, categorias rigidas e interfaces pouco amigaveis. Alem disso, muitos desejam orientacoes simples sobre investimentos basicos, mas se sentem perdidos com jargoes tecnicos e plataformas complexas. O produto busca resolver isso com uma experiencia conversacional fluida, automacao inteligente, relatorios simples e a opcao de exportacao em Excel para quem prefere trabalhar com planilhas.

## 2. Publico-Alvo
* Pessoas que querem organizar suas financas com o minimo de esforco.
* Usuarios iniciantes ou leigos em economia.
* Pessoas que gostam de conversar com assistentes digitais.
* Usuarios que desejam relatorios simples e opcionais exportaveis em planilhas.

## 3. Funcionalidades-Chave

### 1. Registro de gastos via chat
O usuario digita frases naturais como:
* "Gastei 25 reais com lanche"
* "Paguei a internet hoje, 120 reais"

### 2. Classificacao automatica de gastos
* Algoritmo de IA identifica categoria provavel.
* Usuario pode corrigir, e o sistema aprende.

### 3. Metas financeiras claras e simples
* Guardar X por mes.
* Reduzir categoria Y.
* Acompanhamento via mensagens educativas.

### 4. Agente Financeiro Inteligente
Dara recomendacoes personalizadas com foco em educacao:
* Reducao de gastos e identificacao de padroes.
* Alertas quando categorias estourarem.
* Contextualizacao economica: Explicar como a SELIC afeta o bolso do usuario.

### 5. Relatorios simples e personalizados
* Resumo semanal e mensal com graficos basicos.
* Explicacoes simplificadas (sem "economes").

### 6. Exportacao para Excel
Para usuarios que preferem planilhas:
* Exportar transacoes mensais, metas e evolucao.
* Formato .xlsx amigavel para analise rapida.

### 7. Informacoes da Taxa SELIC + Sugestoes de Renda Fixa
O aplicativo apresentara ao usuario:
* Taxa SELIC atual: Consulta automatica via API (atualmente em 15% ao ano).
* Projecoes: Informar sobre expectativas de mercado (ex: queda gradual a partir de marco de 2026).
* Sugestoes Educativas de Renda Fixa:
    * Tesouro Selic: Liquidez diaria e risco baixissimo.
    * CDBs (100% CDI): Acompanham a taxa de juros com seguranca.
    * LCI/LCA: Opcoes isentas de IR para diversificacao simples.

## 4. MVP - Escopo Minimo Viavel

### Telas do MVP
1. Onboarding Conversacional: Coleta de perfil e demonstracao.
2. Chat Financeiro (Tela Principal): Registro de gastos, ver resumo e ver SELIC.
3. Resumo Financeiro: Gastos do mes e botao "Exportar Excel".
4. Metas Financas: Criacao e acompanhamento simples.
5. Configuracoes: Ajustes de categorias e preferencias.

### Recursos Tecnicos do MVP
* Backend: API para transacoes, Banco (Firebase/Postgres) e Servico de consulta periodica a SELIC.
* IA: NLP para interpretar frases e classificador de categorias.
* Integracoes: Gerador de arquivos .xlsx.
* Frontend: Interface de chat e graficos simples.

## 5. Validacao Inicial
* Fase 1 (Testes): 10-20 usuarios conseguem registrar gastos e entender a IA?
* Fase 2 (Entrevistas): A exportacao para Excel e utilizada? As dicas de investimento sao claras?
* Fase 3 (Metricas): Retencao (D7), % de gastos via chat e precisao da IA.

## 6. Objetivo do MVP
Validar duas hipoteses centrais:
1. Experiencia conversacional gera maior aderencia ao controle financeiro.
2. Informacoes simplificadas de investimentos (SELIC) aumentam o engajamento e a percepcao de valor do app.

## Interações com o Lovable:
1. Crie um APP de financas pessoais com base no seguinte PRD (Product Requirements Document): {PRD} 
2. Ok. Faça as seguintes adequações: altere o nome do APP para " MENDES FINANCIAL APP"; Integre com API real da SELIC do Banco Central para mostrar taxa atualizada automaticamente;
3. Por favor, faça os seguintes ajustes: crie uma tela inicial com autenticação segura com e-mail e senha habilitando o Lovable Cloud; Me apresente outra opção de layout do APP.

## Resultado Final no Lovable: 
https://happy-money-muse.lovable.app/auth

![Screenshot_20260205_230747_Samsung Internet](https://github.com/user-attachments/assets/a95d9072-f40f-4b7d-86b4-68ff91693f3d)


![Screenshot_20260205_231803_Samsung Internet](https://github.com/user-attachments/assets/0d5713af-a55c-49a6-b488-01f30ea8dc65)


## Resumo do Projeto: Assistente Financeiro Conversacional 

### ​O aplicativo é uma ferramenta de gestão de finanças pessoais focada em simplicidade e educação financeira. O grande diferencial é a substituição de formulários complexos por uma interface de chat (IA), onde o usuário registra gastos e ganhos usando linguagem natural.

### ​Pilares do Produto: ​Entrada de Dados Simplificada: Registro de transações via conversa (ex: "gastei 50 no mercado"), eliminando a barreira da inserção manual rígida. ​Inteligência de Mercado: Integração com dados reais da economia, fornecendo a taxa SELIC atualizada e explicando seu impacto no dia a dia. ​Educação para Investimentos: Sugestões curadas de Renda Fixa (Tesouro Selic, CDB, LCI/LCA) para usuários iniciantes, com foco em segurança e liquidez. ​Hibridismo de Uso: Oferece relatórios visuais simples no app, mas permite a exportação para Excel (.xlsx) para usuários que desejam realizar análises mais profundas ou manter um backup em planilhas. ​Engajamento Educativo: Um Agente Financeiro que não apenas categoriza gastos, mas monitora metas e envia alertas personalizados para evitar o estouro do orçamento. ​Objetivo: 

### Validar se uma experiência conversacional somada a orientações financeiras desmistificadas consegue aumentar a retenção de usuários que normalmente abandonariam o controle financeiro por achá-lo chato ou difícil.

## REFLEXÕES

### O que funcionou bem?
Minha solicitação de revisão do PRD foi feita de acordo com as expectativas. Por opção minha pude experenciar os agentes COPILOT, GEMINI e LOVABLE nas etapas do projeto ficando extremamente satisfeito com os resultados.
 
### O que não funcionou como esperado?
Por questões logísticas tive que utilizar meu computador no trabalho (COPILOT WEB), meu celular (GEMINI) e meu Tablet para finalizar no LOVABLE e GitHub. Isso acabou tomando mais tempo que o esperado. Além disso o Lovable acabou não efetuando uma adequação de layout como solicitei mas acabou ficando satisfatório o resultado.
 
### O que aprendeu sobre conversar com IAs?
O principal é: faça um bom prompt e terá uma boa resposta. Além disso, revisar o que foi respondido é indispensável para prosseguimento das interações. Por fim, aprendi que qualquer iniciante nesse novo mundo da IA, desde que tenha vontade e engajamento, tem condições de usufruir no seu dia a dia dos benefícios desses assistentes!! INCRÍVEL!!
