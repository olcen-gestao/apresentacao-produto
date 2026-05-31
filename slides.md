---
theme: default
title: Olcen | Apresentação de produto
info: |
  Deck público de apresentação de produto da Olcen.
class: olcen-deck
favicon: ./public/olcen-simbolo.svg
fonts:
  sans: DM Sans
  serif: Newsreader
  mono: JetBrains Mono
transition: fade-out
mdc: true
---

<section class="cover-slide stage-frame">
  <div class="deck-kicker">
    <img src="./public/olcen-simbolo.svg" alt="Olcen" />
    <span>Portfólio de produto</span>
  </div>
  <div class="cover-grid">
    <div class="reveal-seq">
      <h1>Produtos para transformar operação em clareza de gestão.</h1>
      <p class="lead">Um deck navegável para apresentar módulos, fluxos e evidências reais de produto com ritmo executivo.</p>
    </div>
    <div class="hero-panel delay-1">
      <div class="hero-panel-head"><span>Suite Olcen</span><strong>2026</strong></div>
      <div class="hero-metrics"><div><strong>01</strong><span>Produto com demo real</span></div><div><strong>04</strong><span>Linhas no portfólio</span></div><div><strong>12</strong><span>Prints capturados</span></div></div>
      <div class="hero-rail"><span>RU Olcen</span><span>CRM</span><span>Ponto</span><span>Voz</span></div>
    </div>
  </div>
</section>

---
routeAlias: produtos
---

<section class="menu-slide stage-frame">
  <div class="slide-head reveal-seq">
    <p class="eyebrow">Menu inicial</p>
    <h1>Escolha a narrativa do produto.</h1>
    <p class="lead">A apresentação abre pelo portfólio e cada produto tem sua própria história comercial, demo e próximos passos.</p>
  </div>

  <div class="product-menu reveal-seq delay-1">
    <div class="product-card product-card-featured">
      <div class="product-card-top"><span>01</span><small>Pronto para apresentar</small></div>
      <h3>RU Olcen</h3>
      <p>Gestão de pessoas, recrutamento, portal, ponto, férias, remuneração e indicadores em uma base única.</p>
      <Link to="rh" class="card-link">Abrir apresentação</Link>
    </div>
    <div class="product-card">
      <div class="product-card-top"><span>02</span><small>Base narrativa</small></div>
      <h3>Olcen CRM</h3>
      <p>Relacionamento comercial com histórico, oportunidades e próximos passos visíveis para o time.</p>
      <Link to="crm" class="card-link">Ver estrutura</Link>
    </div>
    <div class="product-card">
      <div class="product-card-top"><span>03</span><small>Base narrativa</small></div>
      <h3>Olcen Ponto</h3>
      <p>Controle de jornada e registro de ponto com foco em clareza operacional, auditoria e fechamento.</p>
      <Link to="ponto" class="card-link">Ver estrutura</Link>
    </div>
    <div class="product-card">
      <div class="product-card-top"><span>04</span><small>Base narrativa</small></div>
      <h3>Olcen Voz</h3>
      <p>Experiências por voz para apoiar atendimento, triagem e rotinas digitais com menor atrito.</p>
      <Link to="voz" class="card-link">Ver estrutura</Link>
    </div>
  </div>
</section>

---
routeAlias: rh
---

<section class="product-hero stage-frame dark-slide">
  <Link to="produtos" class="back-link">Voltar ao menu</Link>

  <div class="product-hero-copy reveal-seq">
    <p class="eyebrow">Produto 01</p>
    <h1>RU Olcen</h1>
    <p class="lead">A camada operacional e analítica para RH que precisa controlar pessoas, jornada, talentos e remuneração sem depender de planilhas paralelas.</p>
  </div>

  <div class="product-hero-shot reveal-seq delay-1">
    <img src="./public/screenshots/ru-olcen/raw/dashboard.png" alt="Dashboard de indicadores do RU Olcen" />
  </div>
</section>

---
layout: default
---

<section class="problem-slide stage-frame">
  <div class="slide-head reveal-seq">
    <p class="eyebrow">O problema</p>
    <h1>RH cresce, mas a operação fica espalhada.</h1>
  </div>

  <div class="pain-matrix reveal-seq delay-1">
    <div>
      <span>Dados</span>
      <h3>Planilhas paralelas</h3>
      <p>Colaboradores, cargos, férias, ponto e remuneração vivem em fontes desconectadas.</p>
    </div>
    <div>
      <span>Rotina</span>
      <h3>Baixa rastreabilidade</h3>
      <p>Solicitações, entrevistas, ajustes e aprovações dependem de mensagens soltas.</p>
    </div>
    <div>
      <span>Decisão</span>
      <h3>Pouca visibilidade</h3>
      <p>Liderança acompanha turnover, absenteísmo e custo de pessoal tarde demais.</p>
    </div>
  </div>
</section>

---
---

<section class="platform-map-slide stage-frame">
  <div class="slide-head reveal-seq">
    <p class="eyebrow">Como o RU organiza o sistema</p>
    <h1>Uma base única conectando operação, experiência e decisão.</h1>
  </div>

  <div class="platform-map reveal-seq delay-1">
    <div class="platform-core">
      <small>Centro da plataforma</small>
      <strong>Base de pessoas</strong>
      <span>Colaborador, cargo, empresa, departamento, status e histórico</span>
    </div>
    <div class="platform-lane lane-left">
      <span>Entrada</span>
      <strong>Recrutamento e onboarding</strong>
      <small>Vagas, candidatos, entrevistas, admissão e exames</small>
    </div>
    <div class="platform-lane lane-top">
      <span>Rotina</span>
      <strong>Ponto, férias e solicitações</strong>
      <small>Presença, ajustes, escalas, documentos e autoatendimento</small>
    </div>
    <div class="platform-lane lane-right">
      <span>Crescimento</span>
      <strong>Carreira e desenvolvimento</strong>
      <small>CHA, competências, avaliações, 1:1, PDI e ninebox</small>
    </div>
    <div class="platform-lane lane-bottom">
      <span>Gestão</span>
      <strong>Indicadores e remuneração</strong>
      <small>Turnover, absenteísmo, salários, benchmarks e recortes por área</small>
    </div>
  </div>
</section>

---
---

<section class="workflow-slide stage-frame">
  <div class="slide-head reveal-seq">
    <p class="eyebrow">Jornada demonstrável</p>
    <h1>Da contratação à decisão de gestão.</h1>
  </div>

  <div class="journey-lanes reveal-seq delay-1">
    <div>
      <span>01</span>
      <h3>Atrair</h3>
      <p>Publicar vagas, acompanhar candidatos e organizar entrevistas.</p>
    </div>
    <div>
      <span>02</span>
      <h3>Admitir</h3>
      <p>Transformar contratação em onboarding, documentos e acesso ao portal.</p>
    </div>
    <div>
      <span>03</span>
      <h3>Operar</h3>
      <p>Controlar ponto, férias, solicitações, benefícios e comunicação interna.</p>
    </div>
    <div>
      <span>04</span>
      <h3>Desenvolver</h3>
      <p>Conectar cargos, competências, feedbacks, avaliações e PDI.</p>
    </div>
    <div>
      <span>05</span>
      <h3>Decidir</h3>
      <p>Ler indicadores, comparar remuneração e priorizar ações de gestão.</p>
    </div>
  </div>
</section>

---
---

<section class="evidence-slide stage-frame">
  <div class="evidence-copy reveal-seq">
    <p class="eyebrow">Visão executiva</p>
    <h1>Indicadores RH</h1>
    <p class="lead">Headcount, turnover, absenteísmo, retenção e custo de rotatividade com recortes para liderança agir antes do problema virar rotina.</p>
    <div class="proof-chips">
      <span>Turnover</span>
      <span>Absenteísmo</span>
      <span>Retenção</span>
    </div>
  </div>
  <div class="shot-frame reveal-seq delay-1">
    <div class="shot-bar"><span></span><span></span><span></span><strong>dashboard.rh</strong></div>
    <img src="./public/screenshots/ru-olcen/raw/dashboard.png" alt="Dashboard de indicadores do RU Olcen" />
  </div>
</section>

---
---

<section class="evidence-slide reverse stage-frame">
  <div class="evidence-copy reveal-seq">
    <p class="eyebrow">Base operacional</p>
    <h1>Colaboradores e estrutura</h1>
    <p class="lead">Cadastro vivo de colaboradores com empresa, departamento, status, presença, acesso ao portal e ações administrativas.</p>
    <div class="proof-chips">
      <span>Departamentos</span>
      <span>Status</span>
      <span>Portal</span>
    </div>
  </div>
  <div class="shot-frame reveal-seq delay-1">
    <div class="shot-bar"><span></span><span></span><span></span><strong>colaboradores.rh</strong></div>
    <img src="./public/screenshots/ru-olcen/raw/colaboradores-lista.png" alt="Lista de colaboradores do RU Olcen" />
  </div>
</section>

---
---

<section class="evidence-slide stage-frame">
  <div class="evidence-copy reveal-seq">
    <p class="eyebrow">Desenvolvimento</p>
    <h1>Carreiras, competências e CHA</h1>
    <p class="lead">Cargos, níveis, requisitos, atividades e critérios comportamentais ficam estruturados para sustentar avaliação e evolução profissional.</p>
    <div class="proof-chips">
      <span>Cargos</span>
      <span>CHA</span>
      <span>PDI</span>
    </div>
  </div>
  <div class="shot-frame reveal-seq delay-1">
    <div class="shot-bar"><span></span><span></span><span></span><strong>carreiras.rh</strong></div>
    <img src="./public/screenshots/ru-olcen/raw/carreiras.png" alt="Tela de carreiras do RU Olcen" />
  </div>
</section>

---
---

<section class="evidence-slide reverse stage-frame">
  <div class="evidence-copy reveal-seq">
    <p class="eyebrow">Remuneração</p>
    <h1>Panorama salarial</h1>
    <p class="lead">Comparação entre salário atual, carreira, cargo e benchmarks públicos para orientar ajustes com critério e rastreabilidade.</p>
    <div class="proof-chips">
      <span>Benchmarks</span>
      <span>Faixas</span>
      <span>Equidade</span>
    </div>
  </div>
  <div class="shot-frame reveal-seq delay-1">
    <div class="shot-bar"><span></span><span></span><span></span><strong>remuneracao.rh</strong></div>
    <img src="./public/screenshots/ru-olcen/raw/panorama-salarial.png" alt="Panorama salarial do RU Olcen" />
  </div>
</section>

---
---

<section class="evidence-slide stage-frame">
  <div class="evidence-copy reveal-seq">
    <p class="eyebrow">Aquisição de talentos</p>
    <h1>Recrutamento e seleção</h1>
    <p class="lead">Vagas, candidatos, candidaturas, entrevistas, banco de talentos, portal público e análise de aderência por IA em um fluxo único.</p>
    <div class="proof-chips">
      <span>Vagas</span>
      <span>Entrevistas</span>
      <span>IA</span>
    </div>
  </div>
  <div class="shot-frame reveal-seq delay-1">
    <div class="shot-bar"><span></span><span></span><span></span><strong>recrutamento.rh</strong></div>
    <img src="./public/screenshots/ru-olcen/raw/recrutamento.png" alt="Tela de recrutamento do RU Olcen" />
  </div>
</section>

---
---

<section class="evidence-slide reverse stage-frame">
  <div class="evidence-copy reveal-seq">
    <p class="eyebrow">Jornada e DP</p>
    <h1>Controle de ponto</h1>
    <p class="lead">Presença, horas extras, banco de horas, ajustes, escalas, auditoria geográfica, importações e fechamento operacional.</p>
    <div class="proof-chips">
      <span>Escalas</span>
      <span>Banco de horas</span>
      <span>Auditoria</span>
    </div>
  </div>
  <div class="shot-frame reveal-seq delay-1">
    <div class="shot-bar"><span></span><span></span><span></span><strong>ponto.rh</strong></div>
    <img src="./public/screenshots/ru-olcen/raw/controle-ponto.png" alt="Controle de ponto do RU Olcen" />
  </div>
</section>

---
---

<section class="evidence-slide stage-frame">
  <div class="evidence-copy reveal-seq">
    <p class="eyebrow">Experiência do colaborador</p>
    <h1>Portal do colaborador</h1>
    <p class="lead">Autoatendimento para mural, ponto, documentos, holerites, 1:1, férias, solicitações, pessoas, pesquisas e benefícios.</p>
    <div class="proof-chips">
      <span>Autoatendimento</span>
      <span>Documentos</span>
      <span>Benefícios</span>
    </div>
  </div>
  <div class="shot-frame reveal-seq delay-1">
    <div class="shot-bar"><span></span><span></span><span></span><strong>portal.rh</strong></div>
    <img src="./public/screenshots/ru-olcen/raw/portal-colaborador.png" alt="Portal do colaborador do RU Olcen" />
  </div>
</section>

---
---

<section class="coverage-slide stage-frame">
  <div class="slide-head reveal-seq">
    <p class="eyebrow">Cobertura funcional</p>
    <h1>O RU Olcen cobre o ciclo inteiro de gestão de pessoas.</h1>
  </div>

  <div class="module-map reveal-seq delay-1">
    <div><span>01</span><h3>Operação de RH</h3><p>Colaboradores, empresas, departamentos, usuários, calendário, férias, ponto e solicitações.</p></div>
    <div><span>02</span><h3>Talentos</h3><p>Recrutamento, entrevistas, onboarding, exames ocupacionais, treinamentos e banco de talentos.</p></div>
    <div><span>03</span><h3>Desenvolvimento</h3><p>Carreiras, CHA, avaliação comportamental, 1:1, ninebox, plano de ação e PDI.</p></div>
    <div><span>04</span><h3>Decisão</h3><p>Indicadores de RH, panorama salarial, benchmarks públicos e recortes por área.</p></div>
    <div><span>05</span><h3>Portal</h3><p>Mural, documentos, holerites, benefícios, pesquisas, organograma e autoatendimento.</p></div>
    <div><span>06</span><h3>Governança</h3><p>Canal de denúncias, auditoria, permissões, retenção de dados e histórico operacional.</p></div>
  </div>
</section>

---
routeAlias: crm
---

<section class="coming-slide stage-frame">
  <Link to="produtos" class="back-link">Voltar ao menu</Link>
  <div class="coming-copy reveal-seq">
    <p class="eyebrow">Produto 02</p>
    <h1>Olcen CRM</h1>
    <p class="lead">Estrutura inicial para uma narrativa comercial de relacionamento, pipeline e previsibilidade.</p>
  </div>
  <div class="coming-board reveal-seq delay-1">
    <div><span>01</span><h3>Pipeline comercial</h3><p>Etapas, oportunidades e responsáveis organizados em uma visão clara.</p></div>
    <div><span>02</span><h3>Histórico do cliente</h3><p>Contexto de conversas, propostas e decisões em um só lugar.</p></div>
    <div><span>03</span><h3>Próximo passo</h3><p>Ações comerciais explícitas para reduzir perda de timing.</p></div>
  </div>
</section>

---
routeAlias: ponto
---

<section class="coming-slide stage-frame">
  <Link to="produtos" class="back-link">Voltar ao menu</Link>
  <div class="coming-copy reveal-seq">
    <p class="eyebrow">Produto 03</p>
    <h1>Olcen Ponto</h1>
    <p class="lead">Estrutura inicial para apresentar controle de jornada, auditoria e fechamento operacional.</p>
  </div>
  <div class="coming-board reveal-seq delay-1">
    <div><span>01</span><h3>Registro claro</h3><p>Fluxo simples para acompanhar marcações, presença e pendências.</p></div>
    <div><span>02</span><h3>Gestão de exceções</h3><p>Alertas e visibilidade para tratar ajustes antes do retrabalho.</p></div>
    <div><span>03</span><h3>Base auditável</h3><p>Histórico organizado para conferência, fechamento e governança.</p></div>
  </div>
</section>

---
routeAlias: voz
---

<section class="coming-slide stage-frame">
  <Link to="produtos" class="back-link">Voltar ao menu</Link>
  <div class="coming-copy reveal-seq">
    <p class="eyebrow">Produto 04</p>
    <h1>Olcen Voz</h1>
    <p class="lead">Estrutura inicial para apresentar interfaces por voz em atendimento, triagem e rotinas digitais.</p>
  </div>
  <div class="coming-board reveal-seq delay-1">
    <div><span>01</span><h3>Entrada natural</h3><p>Conversas por voz transformam intenção em próximo passo.</p></div>
    <div><span>02</span><h3>Triagem com contexto</h3><p>Coleta informações relevantes antes do atendimento humano.</p></div>
    <div><span>03</span><h3>Experiência guiada</h3><p>Fluxos orientados reduzem espera, dúvida e abandono.</p></div>
  </div>
</section>

---
---

<section class="closing-slide stage-frame dark-slide">
  <div class="reveal-seq">
    <p class="eyebrow">Próximos passos</p>
    <h1>Completar cada produto com evidência real.</h1>
    <p class="lead">O RU Olcen já está pronto para apresentação. CRM, Ponto e Voz ficam preparados para receber prints, fluxo principal, métricas de impacto e chamada comercial específica.</p>
    <Link to="produtos" class="card-link">Voltar ao menu</Link>
  </div>
</section>
