---
layout: default
language: pt
lang_code: pt-BR
title: Workflow de Agentes
permalink: /workflow/
description: Como uso Claude Code com agentes especializados para pesquisa acadêmica.
---

<p class="eyebrow">Ferramentas</p>
<section class="bio-layout" aria-labelledby="workflow-overview">
  <article class="bio-copy" id="workflow-overview">
    <h1 class="page-title">Workflow de Agentes</h1>
    <p class="page-intro">Uso <a href="https://docs.anthropic.com/en/docs/agents-and-tools/claude-code/overview">Claude Code</a> como ambiente de trabalho para pesquisa acadêmica. O sistema combina agentes especializados, regras de qualidade e um protocolo plan-first para tarefas como escrever papers, analisar dados, revisar manuscritos e preparar apresentações.</p>
    <p>A inspiração veio do workflow de <a href="https://psantanna.com/claude-code-my-workflow/">Pedro Sant'Anna</a>. A minha versão é mais enxuta, adaptada ao meu dia a dia de pesquisa em ciência política e economia política internacional.</p>
  </article>

  <aside class="profile-card" aria-labelledby="workflow-numbers">
    <h2 id="workflow-numbers">Visão Geral</h2>
    <p><strong>38</strong> skills especializadas</p>
    <p><strong>3</strong> regras de contexto</p>
    <p><strong>R</strong> para análise de dados</p>
    <p><strong>Python</strong> para ML, scraping e apps</p>
    <p><strong>PDF</strong> como output padrão</p>
    <p><a href="https://github.com/mgaldino/agents-workflow">Ver no GitHub</a></p>
  </aside>
</section>

<section aria-labelledby="how-it-works">
  <div class="section-header">
    <h2 id="how-it-works" class="section-title">Como Funciona</h2>
  </div>

  <div class="featured-grid">
    <article class="featured-card">
      <div class="featured-top teal"></div>
      <div class="featured-body">
        <h3>1. Plan First</h3>
        <p>Toda tarefa não-trivial começa em modo planejamento. O agente lê a memória persistente, rascunha um plano, salva em disco e espera aprovação antes de executar.</p>
      </div>
    </article>

    <article class="featured-card">
      <div class="featured-top peach"></div>
      <div class="featured-body">
        <h3>2. Agentes Especializados</h3>
        <p>Cada skill é um prompt especializado: revisão de paper, análise de dados em R, auditoria de slides, proofreading, modelagem formal. O agente escolhe a skill certa para a tarefa.</p>
      </div>
    </article>

    <article class="featured-card">
      <div class="featured-top blue"></div>
      <div class="featured-body">
        <h3>3. Quality Gates</h3>
        <p>Scoring automático com rubrica por tipo de arquivo. 80/100 para commit, 90/100 para circulação, 95/100 como meta de excelência. Erros críticos zeram a nota.</p>
      </div>
    </article>
  </div>
</section>

<section class="section-block" aria-labelledby="skills-review">
  <h2 id="skills-review">Revisão e Qualidade de Pesquisa</h2>
  <p>Skills focadas em avaliar e melhorar manuscritos, com múltiplas perspectivas e critérios formais.</p>
  <ul class="simple-list">
    <li><strong>review-paper</strong> — Revisão estilo referee de top journal (dois pareceristas independentes)</li>
    <li><strong>research-pipeline</strong> — Pipeline com agentes separados: reviewer, implementador, verificação cruzada</li>
    <li><strong>edmans-review</strong> — Avaliação nas 3 dimensões Edmans: Contribution, Execution, Exposition</li>
    <li><strong>proofread</strong> — Gramática, typos e consistência</li>
    <li><strong>validate-bib</strong> — Validação cruzada de referências e citações</li>
    <li><strong>abstract-annotator / introduction-annotator</strong> — Avaliação estrutural de abstracts e introduções</li>
  </ul>
</section>

<section class="section-block" aria-labelledby="skills-formal">
  <h2 id="skills-formal">Modelos Formais</h2>
  <p>Avaliação de papers com modelos formais em Ciência Política e Relações Internacionais.</p>
  <ul class="simple-list">
    <li><strong>review-formal-model</strong> — Parecer completo: design, apresentação técnica e exposição</li>
    <li><strong>formal-model-design</strong> — Design conceitual (Dixit, Varian, Board)</li>
    <li><strong>formal-model-writing</strong> — Notação, definições, provas e figuras (Thomson, Board)</li>
    <li><strong>formal-model-exposition</strong> — Comunicação e estrutura do paper</li>
    <li><strong>math-guide</strong> — Guia matemático em PDF para provas de artigos</li>
  </ul>
</section>

<section class="section-block" aria-labelledby="skills-data">
  <h2 id="skills-data">Análise de Dados</h2>
  <ul class="simple-list">
    <li><strong>data-analysis-r</strong> — Pipeline end-to-end em R (fixest, tidyverse, modelsummary)</li>
    <li><strong>data-analysis-python</strong> — Análise em Python (pandas, statsmodels, linearmodels)</li>
    <li><strong>review-r / review-python</strong> — Revisão de qualidade de código</li>
    <li><strong>compile-rmd</strong> — Compilar RMarkdown (PDF/HTML)</li>
  </ul>
</section>

<section class="section-block" aria-labelledby="skills-slides">
  <h2 id="skills-slides">Apresentações e Escrita</h2>
  <ul class="simple-list">
    <li><strong>slide-excellence</strong> — Revisão multi-dimensão de slides</li>
    <li><strong>visual-audit</strong> — Auditoria visual de apresentações</li>
    <li><strong>pedagogy-review</strong> — Narrativa, notação e pacing</li>
    <li><strong>theory-framing</strong> — Diagnóstico de enquadramento teórico</li>
    <li><strong>lit-review</strong> — Revisão de literatura sistemática + síntese + gaps</li>
    <li><strong>research-ideation</strong> — Geração de questões de pesquisa + estratégias empíricas</li>
    <li><strong>interview-me</strong> — Entrevista interativa para refinar ideias, clarificar argumentos e descobrir a mensagem principal</li>
  </ul>
</section>

<section class="section-block" aria-labelledby="skills-stakeholder">
  <h2 id="skills-stakeholder">Análise de Stakeholders e Política</h2>
  <ul class="simple-list">
    <li><strong>stakeholder-pipeline</strong> — Pipeline completo: mapeamento, crítica, verificação, bios e deep-dive</li>
    <li><strong>policy-analysis</strong> — Framework de análise de políticas públicas (9 módulos)</li>
    <li><strong>strategic-negotiation</strong> — Preparação de negociações complexas (9 módulos)</li>
    <li><strong>ipe-expert</strong> — Domain expert em Economia Política Internacional</li>
    <li><strong>devils-advocate</strong> — Desafiar argumentos e apresentações</li>
  </ul>
</section>

<section aria-labelledby="examples">
  <div class="section-header">
    <h2 id="examples" class="section-title">Exemplos de Uso</h2>
  </div>

  <div class="featured-grid" style="grid-template-columns: repeat(2, minmax(0, 1fr));">
    <article class="featured-card">
      <div class="featured-top teal"></div>
      <div class="featured-body">
        <h3>Definindo a mensagem do site com <code>interview-me</code></h3>
        <p>Quando montei este site, não tinha clareza sobre qual deveria ser a mensagem principal. Rodei a skill <strong>interview-me</strong>, que funciona como uma entrevista socrática: o agente faz perguntas encadeadas sobre minha pesquisa, trajetória e público-alvo, forçando-me a articular o que importa. Em três rodadas de perguntas, ficou claro que o fio condutor era a combinação de modelos formais com estimação empírica — algo que não aparecia na versão anterior do site. Isso reorganizou toda a comunicação: bio, pesquisa em destaque e a estrutura das páginas.</p>
      </div>
    </article>

    <article class="featured-card">
      <div class="featured-top peach"></div>
      <div class="featured-body">
        <h3>Reescrevendo um paper com <code>edmans-review</code></h3>
        <p>Usei <strong>edmans-review</strong> para avaliar um working paper antes de submeter. O agente avalia Contribution, Execution e Exposition separadamente, com scoring e diagnósticos concretos. O parecer apontou que a contribuição estava diluída — eu listava vários resultados sem hierarquizar qual era o achado central. Mais útil foi a heurística bayesiana: o agente pergunta "quanto um leitor informado atualizaria suas crenças ao ler este paper?". Isso me obrigou a pensar na margem de contribuição real, não no que eu achava interessante. Reescrevi a introdução priorizando o resultado principal e cortei uma seção inteira que não movia o ponteiro de convicção do leitor.</p>
      </div>
    </article>
  </div>
</section>

<section class="section-block" aria-labelledby="rules">
  <h2 id="rules">Regras de Contexto</h2>
  <p>Três regras ativadas automaticamente conforme o tipo de arquivo ou situação:</p>
  <ul class="simple-list">
    <li><strong>Plan-First Workflow</strong> — Obriga planejamento antes de execução. Planos salvos em disco sobrevivem à compressão de contexto.</li>
    <li><strong>Quality Gates</strong> — Rubricas de scoring por tipo de arquivo (.R, .Rmd, .py, .qmd) com deduções por severidade.</li>
    <li><strong>Session Recovery</strong> — Protocolo de recuperação após compressão ou nova sessão: ler memória, verificar planos, checar git, declarar entendimento.</li>
  </ul>
</section>
