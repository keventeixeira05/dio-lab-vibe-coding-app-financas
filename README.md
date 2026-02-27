# 💸 App de Finanças Pessoais do kéven com Vibe Coding

Este projeto foi desenvolvido como un Desafio de Projeto da DID de Vibe Coding utilizando o Lovable e o Copilot Meb. A proposta é criar un aplicativo de organização financeirs pessoal baseado en interações en linguagem natural.

---

PRD refinado no copilot web:

```markdown

PRD – Aplicativo de Organização de Finanças Pessoais

1. Contexto
Criar um aplicativo de organização financeira pessoal que funcione por meio de conversas em linguagem natural, eliminando a necessidade de formulários complexos ou planilhas.  
O objetivo é tornar o controle financeiro mais simples, acessível e intuitivo, com foco em Design Universal para garantir que qualquer pessoa, independentemente de perfil ou habilidade, tenha uma boa experiência.

2. Problema
- Usuários desistem de controlar gastos porque os apps atuais exigem entrada manual extensa e oferecem pouca personalização.  
- Falta de experiência fluida e amigável para iniciantes.  
- Muitos aplicativos não consideram acessibilidade e inclusão, limitando o alcance.  

Solução proposta: um sistema conversacional que registre gastos, sugira economia e acompanhe metas de forma natural, com design inclusivo e acessível.

3. Público-Alvo
- Pessoas que desejam iniciar o controle financeiro sem complicações.  
- Usuários iniciantes em apps de finanças, que buscam praticidade e orientação personalizada.  
- Pessoas com diferentes níveis de familiaridade tecnológica, garantindo acessibilidade ampla.  
- Usuários que precisam de recursos inclusivos (ex.: suporte a leitores de tela, comandos de voz, contraste adequado).

4. Funcionalidades-Chave
1. Registro de gastos via chat em linguagem natural.  
2. Classificação automática das transações (ex.: alimentação, transporte).  
3. Definição e acompanhamento de metas financeiras (ex.: poupar R$200/mês).  
4. Agente Financeiro que fornece dicas de economia personalizadas.  
5. Relatórios simples e visuais para acompanhamento rápido.  
6. Design Universal: interface inclusiva, acessível e adaptável a diferentes perfis de usuários.  
7. Privacidade e segurança: dados financeiros protegidos, com transparência no uso da informação.  

5. Entregável da IA
Plano de MVP contendo:
- Principais telas:  
  - Tela de chat (interação com o agente)  
  - Tela de metas financeiras  
  - Tela de relatórios simples  
- Recursos necessários:  
  - Processamento de linguagem natural (NLP)  
  - Banco de dados para transações  
  - Motor de categorização automática  
  - Sistema de notificações/dicas  
  - Diretrizes de acessibilidade (Design Universal)  
  - Camada de segurança e privacidade  
- Validação inicial:  
  - Teste com grupo piloto de usuários iniciantes e diversos perfis  
  - Coleta de feedback sobre clareza da conversa, acessibilidade e utilidade das recomendações  
  - Ajustes iterativos com base na experiência real

---

Conceito de Design Universal
Definição: abordagem de design que busca criar produtos e serviços que possam ser usados pelo maior número possível de pessoas, sem necessidade de adaptações específicas.  
Princípio central: acessibilidade e inclusão são pensadas desde o início do projeto, não como ajustes posteriores.  
Exemplos práticos no app:  
- Textos claros e linguagem simples.  
- Contraste adequado de cores para pessoas com baixa visão.  
- Navegação intuitiva para iniciantes.  
- Compatibilidade com leitores de tela e comandos de voz.  
- Ícones e elementos visuais de fácil interpretação.  
Benefício: amplia o alcance do produto, melhora a experiência de todos os usuários e demonstra responsabilidade social e tecnológica.
```

---

Interação com o Lovable:

> Crie um App de Finanças Pessoais com base no seguinte PRD: (Product Requirements Document) PRD – Aplicativo de Organização de Finanças Pessoais

> O app não responde a qualquer pergunta só perguntas pré-preparadas, quero que responda a qualquer coisa financeiramente. O app também já começou com saldo e despesas e etc. Quero que ele comece zerado, e quando for adicionando os valores ai sim ele vai organizando, dessa forma ele realmente se tornar útil. Também quando pedir para adicionar metas vá de forma automática para a janela de Metas

Resultado final no Lovable: https://talk-track-wealth.lovable.app

<img width="1862" height="962" alt="image" src="https://github.com/user-attachments/assets/36f125fc-e263-4126-91ff-ec89fa23709d" />

##  Objetivo
Facilitar o controle financeiro para usuários iniciantes ou com pouca familiaridade tecnológica, oferecendo uma experiência fluida, acessível e orientada por um **Agente Financeiro inteligente**.

---

## Funcionalidades Principais

### Interação Conversacional (Chat)
- Registro de **gastos e receitas em linguagem natural**  
  - Exemplo:  
    - `Gastei 50 reais no mercado`  
    - `Comprei um livro de estudo por 48 reais`
- Interpretação automática de:
  - Valores
  - Categorias
  - Contexto da transação
- Agente Financeiro que responde dúvidas e orienta o usuário
- Ideal para iniciantes e públicos diversos

---

### Relatórios Financeiros Simplificados
Tela dedicada à visualização rápida da situação financeira do usuário.

#### Resumo Financeiro
- Receita total
- Despesas totais
- Saldo atual
- Destaque visual com ícones e cores de fácil compreensão

#### Gastos por Categoria
- Classificação automática dos gastos (ex.: Alimentação, Educação)
- Visualização em barras de progresso
- Exibição de:
  - Valor gasto
  - Percentual em relação ao total

#### Transações Recentes
- Lista das últimas movimentações financeiras
- Exibe:
  - Nome da transação
  - Categoria
  - Valor
- Facilita conferência e correções rápidas

---

### Metas Financeiras
- Criação de metas de forma simples e guiada  
  - Exemplo: `Economizar R$ 200 por mês`
- Acompanhamento visual do progresso
- Feedback motivador para incentivar hábitos financeiros saudáveis

---

## Design Universal e Acessibilidade
O aplicativo foi projetado desde o início para ser acessível ao maior número possível de pessoas.

- Linguagem clara e direta
- Interface limpa e intuitiva
- Alto contraste de cores
- Ícones acompanhados de texto explicativo
- Navegação simples por abas:
  - Chat
  - Metas
  - Relatórios
- Compatível com leitores de tela
- Estrutura preparada para comandos de voz

---

## Automação e Inteligência
- Classificação automática de transações
- Geração de relatórios sem esforço manual
- Base para recomendações personalizadas de economia
- Aprendizado contínuo conforme o uso do usuário

---

## Segurança e Privacidade
- Armazenamento seguro dos dados financeiros
- Transparência no uso das informações
- Controle total do usuário sobre seus dados

---

## Visão Geral
O aplicativo oferece uma experiência de controle financeiro **humana, simples e inclusiva**, reduzindo barreiras tecnológicas e incentivando a educação financeira de forma prática e acessível.

Ele transforma dados financeiros em informações claras e úteis, cumprindo o objetivo central do MVP: **ajudar o usuário a entender e melhorar sua relação com o dinheiro, sem complexidade**.

---

## Reflexão

### O que funcionou bem?  
O refinamento do PRD previamente feito no Copilot ajudou muito, pois os créditos do Lovable acabaran en apenas 3 interações. 

### O que não funcionou como o esperado?  
Esperava poder interagir mais vezes gratuitamente com o Lovable, mas as interações feita já foram de grande valia para aprender mais sobre Vibe Coding.

###O que aprendeu sobre conversar com IAs?
Aprendi que é basicamente igual a conversar com uma pessoa, quapto mais detalhes e clareza você dá, melhor é a interação.

Vibe Coding é sobre clareza, curiosidade e criatividade, não sobre perfeição técnica. O verdadeiro objetivo aqui é aprender a pensar junto com a IA, transformando ideias em conceitos reais e enxergando a tecnologia como uma extensão do seu raciocínio criativo. Cada interação é um experimento, quanto mais clara for sua intenção, mais surpreendente será o resultado.
