# Processo de Gerenciamento de Problemas

## 1. Objetivo
Identificar e gerenciar as causas raiz dos incidentes recorrentes e problemas potenciais na infraestrutura de TI da TechHelp, minimizando o impacto negativo e prevenindo ocorrências futuras, contribuindo para a estabilidade e confiabilidade dos serviços.

## 2. Escopo
Este processo abrange a identificação, registro, classificação, investigação e resolução permanente de problemas em toda a infraestrutura e serviços de TI gerenciados pela TechHelp, incluindo tanto atividades reativas quanto proativas.

## 3. Definições

- **Problema**: Causa raiz de um ou mais incidentes existentes ou potenciais.
- **Erro Conhecido**: Problema que foi diagnosticado completamente e para o qual existe uma solução de contorno ou permanente.
- **Solução de Contorno**: Solução temporária para reduzir ou eliminar o impacto de um problema quando uma resolução permanente ainda não está disponível.
- **Análise de Causa Raiz**: Método de identificação das causas fundamentais que geram os problemas.
- **Base de Erros Conhecidos (KEDB)**: Repositório documentado de problemas identificados e suas soluções.

## 4. Fluxo do Processo

### 4.1 Detecção e Registro
- Identificação de problemas por análise de incidentes, monitoramento proativo ou notificação da equipe técnica
- Registro com ID único, descrição detalhada, impacto no negócio e serviços afetados
- Vinculação com incidentes relacionados na base de dados

### 4.2 Categorização 
- Classificação por área tecnológica (hardware, software, rede, etc.)
- Definição da origem do problema (infraestrutura, aplicação, fornecedor)
- Vinculação com itens de configuração na CMDB

### 4.3 Priorização
- Baseada no impacto atual e potencial nos negócios
- Consideração da frequência de incidentes relacionados
- Análise de urgência para resolução permanente

| Impacto/Urgência | Baixa | Média | Alta |
|------------------|-------|-------|------|
| Baixo            | P5    | P4    | P3   |
| Médio            | P4    | P3    | P2   |
| Alto             | P3    | P2    | P1   |

### 4.4 Investigação e Diagnóstico
- Formação de equipe de análise conforme necessidade técnica
- Aplicação de métodos de análise de causa raiz
- Documentação detalhada de evidências e descobertas
- Reprodução do problema em ambiente controlado quando possível

### 4.5 Identificação de Erro Conhecido
- Documentação completa do problema diagnosticado
- Registro na Base de Erros Conhecidos (KEDB)
- Desenvolvimento e documentação de soluções de contorno
- Comunicação para a equipe de suporte

### 4.6 Resolução
- Desenvolvimento da solução permanente
- Criação de Requisição de Mudança (RFC) quando necessário
- Verificação da eficácia da solução após implementação
- Atualização da documentação técnica e procedimentos

### 4.7 Encerramento
- Revisão de todas as ações realizadas
- Documentação de lições aprendidas
- Atualização final da Base de Erros Conhecidos
- Avaliação de medidas preventivas adicionais

### 4.8 Revisão de Problemas Graves
- Análise pós-implementação para problemas de alto impacto
- Identificação de melhorias no processo
- Documentação de recomendações para evitar recorrência
- Relatório para a gerência com análise completa

## 5. Matriz RACI

| Atividade | Gerente de Problemas | Analista de Problemas | Especialista Técnico | Analista de Central | Gerente de TI |
|-----------|---------------------|----------------------|---------------------|-------------------|-------------|
| Detecção e Registro | A | R | C | R | I |
| Categorização | A | R | C | I | I |
| Priorização | R/A | C | C | I | C |
| Investigação | A | R | R | C | I |
| Erro Conhecido | A | R | C | I | I |
| Resolução | A | C | R | I | C |
| Encerramento | R/A | R | C | I | I |
| Revisão de Problemas Graves | R/A | R | R | C | R |

R = Responsável, A = Aprovador, C = Consultado, I = Informado

## 6. KPIs e Métricas

- Redução percentual de incidentes recorrentes
- Tempo médio de resolução de problemas por prioridade
- Número de problemas que ultrapassaram o tempo acordado
- Quantidade e percentual de incidentes vinculados a erros conhecidos
- Eficácia das soluções de contorno (redução de impacto)
- Volume de problemas por categoria e serviço
- Custo evitado por gerenciamento proativo de problemas

## 7. Abordagens de Análise de Causa Raiz

- **Análise dos 5 Porquês**: Método de questionamento sequencial para identificar a causa fundamental
- **Diagrama de Ishikawa**: Análise de causa e efeito com categorização
- **Análise de Árvore de Falhas**: Método dedutivo para identificar combinações de falhas
- **Análise de Pareto**: Identificação do "vital few" - 20% das causas que geram 80% dos problemas

## 8. Gerenciamento Proativo de Problemas

### 8.1 Análise de Tendências
- Revisão periódica de dados de incidentes para identificar padrões
- Monitoramento de performance e capacidade para detectar problemas potenciais
- Análise estatística de tickets e chamados

### 8.2 Avaliações Preventivas
- Revisões regulares de infraestrutura
- Análise de vulnerabilidades e riscos
- Auditorias de configuração e versões

### 8.3 Comitê de Revisão
- Reuniões periódicas para análise de problemas recorrentes
- Avaliação da efetividade das soluções implementadas
- Priorização de iniciativas de melhoria

## 9. Integração com Outros Processos

- **Gerenciamento de Incidentes**: Fonte de informação para identificação de problemas
- **Gerenciamento de Mudanças**: Implementação de soluções permanentes
- **Gerenciamento de Configuração**: Análise de impacto e relações entre CIs
- **Gerenciamento de Conhecimento**: Documentação de problemas e soluções
- **Melhoria Contínua**: Identificação de oportunidades de otimização

## 10. Base de Erros Conhecidos (KEDB)

- Estrutura padronizada de documentação
- Mecanismos de busca avançada
- Vinculação com a base de conhecimento
- Integração com ferramentas de monitoramento e diagnóstico
- Processo de revisão e atualização periódica