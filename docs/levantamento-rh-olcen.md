# Levantamento de features — RH Olcen

Data: 2026-05-31

Fonte analisada: `/Users/marcondesmacaneiro/workspace/olcen/helium_app`

## Leitura executiva

O RH Olcen está estruturado como uma plataforma SaaS de RH para PMEs brasileiras, com foco em gestão por competências, ciclo de colaborador, portal do colaborador, recrutamento, ponto, remuneração e indicadores.

Para apresentação comercial, a narrativa mais forte não deve ser uma lista de telas. O melhor eixo é:

1. Centralizar a operação de RH em uma única plataforma.
2. Tirar processos críticos de planilhas, e-mail e WhatsApp.
3. Conectar dados de pessoas, cargos, desempenho, ponto, recrutamento e remuneração.
4. Dar ao colaborador um portal próprio, com autoatendimento e comunicação interna.
5. Apoiar decisões de RH com indicadores, IA e rastreabilidade.

## Evidências principais

- O README define o produto como "Plataforma SaaS de Gestão por Competências para PMEs brasileiras" e marca o status como desenvolvimento ativo.
- O menu administrativo expõe módulos reais para indicadores, empresas, departamentos, carreiras, panorama salarial, plano de ação, CHA, avaliação comportamental, ninebox, colaboradores, calendário, recrutamento, entrevistas, onboarding, exames, 1:1, controle de ponto, denúncias, férias e usuários.
- O portal do colaborador possui módulos configuráveis para mural, documentos, tempo livre, solicitações, pessoas, pesquisas, benefícios, aprendizagem, organograma, autoavaliação e férias.
- O schema tem domínio robusto para ATS, entrevistas remotas, análise IA de match, mercado salarial, ponto, onboarding, ninebox e canal de denúncias.

## Massa demo local

Depois de aplicar migrations e rodar seeds idempotentes, a base local `/demo` ficou com:

- 85 colaboradores.
- 5 carreiras.
- 3 vagas publicadas.
- 10 candidatos/candidaturas.
- 12 entrevistas.
- 40 benchmarks salariais públicos.
- Controle de ponto habilitado por flag local.

Observação: alguns módulos existem no código, mas a base demo ainda não está populada o suficiente para gerar prints fortes, especialmente mural/documentos do portal, denúncias, ninebox, avaliações comportamentais e férias.

## Screenshots brutos capturados

Pasta:

`public/screenshots/rh-olcen/raw/`

Arquivos:

- `dashboard.png`
- `colaboradores-lista.png`
- `colaboradores-organograma.png`
- `carreiras.png`
- `panorama-salarial.png`
- `recrutamento.png`
- `recrutamento-entrevistas.png`
- `recrutamento-onboarding.png`
- `controle-ponto.png`
- `ferias.png`
- `portal-colaborador.png`
- `denuncias-admin.png`

## Features candidatas para slides

### 1. Gestão executiva de RH

Resumo comercial:

O RH Olcen dá ao RH uma visão executiva da operação: headcount, turnover, absenteísmo, retenção, custo de rotatividade e recortes por área.

Valor para o cliente:

- Substitui planilhas de fechamento manual por um painel central.
- Ajuda o RH a enxergar problemas por área, não apenas no agregado.
- Cria base para decisões de retenção, custo e produtividade.

Print disponível:

- `dashboard.png`

Status para deck:

Pronto para virar slide.

### 2. Cadastro e estrutura organizacional

Resumo comercial:

Empresas, departamentos, colaboradores, vínculos, status e estrutura organizacional ficam centralizados.

Valor para o cliente:

- Uma fonte única para dados de pessoas.
- Facilita segmentar indicadores por empresa/departamento.
- Sustenta organograma, portal, ponto, recrutamento, férias e remuneração.

Print disponível:

- `colaboradores-lista.png`
- `colaboradores-organograma.png`

Status para deck:

Usar a lista de colaboradores. O organograma precisa de revisão na massa demo antes de virar print principal, pois apareceu com departamentos sem colaboradores na captura.

### 3. Carreiras, cargos e gestão por competências

Resumo comercial:

O produto organiza carreiras, níveis, requisitos, atividades, atitudes e grade de complexidade para estruturar cargos com critérios claros.

Valor para o cliente:

- Tira descrição de cargo de documentos soltos.
- Cria base para avaliação CHA, enquadramento e crescimento.
- Ajuda a explicar promoções, trilhas e lacunas de competência.

Print disponível:

- `carreiras.png`

Status para deck:

Pronto como pilar conceitual. Vale capturar também uma tela de detalhe de carreira antes de fechar o slide.

### 4. Avaliação CHA e plano de desenvolvimento

Resumo comercial:

O sistema conecta carreira e avaliação de competências, habilidades e atitudes, apoiando decisão de enquadramento, evolução e PDI.

Valor para o cliente:

- Avaliação menos subjetiva.
- Diagnóstico ligado ao cargo esperado.
- Base para plano de ação e desenvolvimento individual.

Print disponível:

Ainda não capturei uma tela forte de CHA com dados preenchidos.

Status para deck:

Feature estratégica para narrativa. Precisa de print melhor ou mock controlado se a base demo não tiver ciclo populado.

### 5. Avaliação comportamental 360

Resumo comercial:

O RH Olcen inclui avaliação comportamental com DISC, Jung e Spranger, coleta por convidados e geração de relatório com IA.

Valor para o cliente:

- Melhora autoconhecimento e gestão.
- Apoia devolutiva 1:1 com relatório estruturado.
- Pode alimentar PDI e desenvolvimento de liderança.

Print disponível:

Ainda não capturei uma tela forte com avaliação populada.

Status para deck:

Boa feature para slide de diferenciação, mas precisa de print ou exemplo de relatório.

### 6. Panorama salarial e planejamento de ajustes

Resumo comercial:

O produto cruza salário atual, cargo/carreira e benchmarks públicos para mostrar posição frente ao mercado e apoiar planejamento salarial.

Valor para o cliente:

- Ajuda a priorizar ajustes com base em dados.
- Separa colaboradores abaixo, dentro ou acima da faixa.
- Permite planejamento por recorte, status e orçamento.

Print disponível:

- `panorama-salarial.png`

Status para deck:

Muito forte para slide comercial. É um dos melhores prints capturados.

### 7. Recrutamento e seleção

Resumo comercial:

O ATS cobre vagas, candidatos, candidaturas, triagem, análise IA de match, banco de talentos e portal público de vagas.

Valor para o cliente:

- Centraliza pipeline de seleção.
- Reduz triagem manual.
- Padroniza requisitos, perguntas e documentos obrigatórios por vaga.

Print disponível:

- `recrutamento.png`

Status para deck:

Pronto para slide.

### 8. Entrevistas e agenda RH

Resumo comercial:

O módulo de entrevistas registra agendas presenciais, remotas e híbridas, com base preparada para sala remota, consentimento, gravação, transcrição e análise IA.

Valor para o cliente:

- Organiza calendário e histórico de entrevistas.
- Reduz perda de contexto entre RH, gestor e candidato.
- Cria rastreabilidade do processo seletivo.

Print disponível:

- `recrutamento-entrevistas.png`

Status para deck:

Pronto para slide se o print mostrar calendário/lista com conteúdo suficiente. Pode exigir recorte.

### 9. Onboarding

Resumo comercial:

Após contratação, o onboarding vira processo com fases, checklist, documentos, exames, treinamentos, avaliações 45/90 e eventos de auditoria.

Valor para o cliente:

- Evita admissões soltas em e-mail.
- Dá visibilidade do que falta para cada novo colaborador.
- Integra contratação, documentos e experiência inicial.

Print disponível:

- `recrutamento-onboarding.png`

Status para deck:

Feature forte, mas precisa validar se a base demo tem cards suficientes para um print comercial.

### 10. Controle de ponto

Resumo comercial:

O módulo cobre painel operacional, espelho, ajustes, escalas, política, estabelecimentos, auditoria geográfica, revisão offline, jornada de motorista, tipos de ajuste, importações, certificado A1 e fechamentos.

Valor para o cliente:

- Concentra ponto, banco de horas e ajustes.
- Permite políticas por empresa/cargo/colaborador.
- Tem preocupação legal: AFD, AEJ, REP-P, geolocalização, privacidade e assinatura.

Print disponível:

- `controle-ponto.png`

Status para deck:

Bom para slide de abrangência operacional. Para venda, deve ser apresentado com cuidado para não prometer conformidade legal sem validar escopo final de produção.

### 11. Portal do colaborador

Resumo comercial:

O colaborador tem uma experiência própria com mural, ponto, documentos, holerites, 1:1, tempo livre, férias, solicitações, pessoas, organograma, pesquisas, aprendizagem, treinamentos, benefícios e autoavaliação.

Valor para o cliente:

- Reduz chamados repetitivos ao RH.
- Dá autonomia ao colaborador.
- Centraliza comunicação interna e solicitações.

Print disponível:

- `portal-colaborador.png`

Status para deck:

Usar como print de "autoatendimento". Para ficar mais convincente, a base demo precisa de mural, documentos, benefícios e solicitações populados.

### 12. Férias e tempo livre

Resumo comercial:

O produto modela férias, políticas, períodos aquisitivos, programação, vencimentos e ciência.

Valor para o cliente:

- Ajuda o RH a evitar vencimentos e perdas de prazo.
- Dá visibilidade ao colaborador.
- Conecta férias com portal e ponto.

Print disponível:

- `ferias.png`

Status para deck:

Feature relevante, mas precisa de massa demo com períodos aquisitivos para ficar forte visualmente.

### 13. Canal de denúncias

Resumo comercial:

Canal anônimo com protocolo, SLA, status, anexos, mensagens, auditoria e política de retenção.

Valor para o cliente:

- Cria canal formal e rastreável.
- Ajuda a lidar com temas sensíveis com controle de acesso.
- Reduz risco operacional e jurídico.

Print disponível:

- `denuncias-admin.png`

Status para deck:

Bom para slide de governança, mas precisa de exemplos fictícios se for usado visualmente.

### 14. Ninebox e sucessão

Resumo comercial:

O modelo de dados já cobre ciclos, posições, performance, potencial, talento crítico, sucessão e ações associadas.

Valor para o cliente:

- Ajuda a mapear talentos e riscos.
- Conecta avaliação a ações práticas.
- Fortalece planejamento de sucessão.

Print disponível:

Ainda não capturei tela populada.

Status para deck:

Usar como roadmap/diferencial se não houver demo populada.

### 15. 1:1 e desenvolvimento contínuo

Resumo comercial:

O produto possui trilhas para reuniões 1:1, preparação, gravação, transcrição, análise IA e ações de PDI.

Valor para o cliente:

- Transforma conversas de gestão em acompanhamento contínuo.
- Evita perda de contexto de feedbacks.
- Conecta desenvolvimento com plano de ação.

Print disponível:

Ainda não capturei tela populada.

Status para deck:

Boa para narrativa de desenvolvimento, mas precisa de dado demo.

## Roteiro sugerido para apresentação do RH Olcen

1. Abertura: "O RH opera em muitos sistemas, planilhas e conversas soltas."
2. Visão: "RH Olcen centraliza a operação de pessoas em uma plataforma única."
3. Dashboard executivo: indicadores e recortes por área.
4. Base de pessoas: colaboradores, empresas, departamentos e estrutura.
5. Carreiras e competências: cargos, níveis e critérios.
6. Avaliações: CHA, comportamental 360 e plano de desenvolvimento.
7. Remuneração: panorama salarial e planejamento de ajustes.
8. Recrutamento: vagas, candidatos, IA e entrevistas.
9. Onboarding: contratação vira processo rastreável.
10. Ponto e férias: operação legal e rotina do DP.
11. Portal do colaborador: autoatendimento, documentos, comunicação e solicitações.
12. Governança: denúncias, permissões, auditoria, LGPD e retenção.
13. Fechamento: "Do recrutamento à retenção, uma única base para decidir e executar."

## Próximos passos antes de criar os slides finais

1. Popular melhor a base demo para portal, férias, denúncias, ninebox, 1:1 e avaliação comportamental.
2. Capturar prints mais focados, com crop por área útil e sem excesso de sidebar quando o slide pedir.
3. Definir se o deck será para venda consultiva de 8-10 slides ou apresentação completa de produto com 14-16 slides.
4. Transformar os prints brutos em assets recortados para Slidev.
5. Criar uma seção "RH Olcen" dentro do deck atual, mantendo o menu inicial por produtos.
