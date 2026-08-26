# Sistema de Contabilização de Vendas 

Sistema web desenvolvido para substituir o controle manual de vendas em planilhas Excel, permitindo à gestão da filial registrar, acompanhar e analisar o desempenho diário da equipe e da loja.

## Contexto e problema
O controle de metas, vendas e ranking da equipe era feito manualmente em Excel, um processo sujeito a erros, sem histórico auditável e sem visão consolidada de desempenho ao longo do ano.

## Processo
- **Descoberta e especificação**: levantamento de requisitos funcionais e não funcionais junto à rotina real da gestão da filial, formalizados em um documento de especificação (RFs, RNFs e regras de negócio)
- **Prototipação e validação incremental**: construção em fases (cadastro e metas → operação diária e ranking → fechamento e auditoria → dashboard e relatórios), validada a cada etapa com dados reais da filial
- **Desenvolvimento assistido por IA generativa**: sistema concebido, especificado e validado com apoio de IA generativa para a implementação técnica

## Funcionalidades principais
- Cadastro, edição e inativação de vendedores, com preservação de histórico
- Definição de meta mensal da filial com divisão automática entre vendedores ativos (e ajuste manual)
- Lançamento diário de vendas e ajustes financeiros da filial
- Ranking automático com percentual de meta atingido, valor restante e meta diária necessária
- Fechamento mensal com bloqueio de dados e trilha de auditoria (histórico de alterações)
- Dashboard anual e relatórios consolidados
- Geração de "Placar do Dia" em imagem, para compartilhamento com a equipe

## Stack
Front-end em HTML/CSS/JavaScript puro, com Firebase (Authentication + Firestore) como backend em nuvem.
