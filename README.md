# Sistema de Contabilização de Vendas — Filial

Sistema web criado para uma filial de agência de viagens, para substituir o controle manual de vendas em planilhas Excel por uma ferramenta centralizada de metas, desempenho e fechamento mensal.

## O problema
O acompanhamento de metas, vendas diárias e ranking da equipe era feito manualmente em Excel — um processo sujeito a erros de digitação, sem histórico auditável de alterações e sem visão consolidada do desempenho da filial ao longo do ano. Fechar um mês e abrir o próximo exigia recriar planilhas do zero, sem garantia de que os dados anteriores permaneceriam intactos.

## Meu papel
Concebi, especifiquei os requisitos e validei o sistema em cada etapa, atuando como responsável de produto ao longo de todo o processo. Formalizei um documento de especificação com requisitos funcionais, não funcionais e regras de negócio antes do início do desenvolvimento, e conduzi a construção em fases, validando cada uma com dados reais da filial antes de avançar para a próxima. O desenvolvimento foi conduzido com apoio de IA generativa, sob minha orientação e decisões de escopo.

## Requisitos levantados
Com base na rotina real de gestão da filial, defini:
- Cadastro, edição e inativação de vendedores, preservando o histórico mesmo após a saída de um colaborador
- Meta mensal da filial com divisão automática entre vendedores ativos, e possibilidade de ajuste manual por vendedor
- Lançamento diário do valor acumulado de vendas, com data de referência controlada
- Registro de ajustes financeiros da filial (ex: vendas canceladas, serviços de ex-colaboradores) separados das vendas de vendedores ativos
- Ranking automático por percentual de meta atingido, com faixas visuais de desempenho
- Fechamento mensal com bloqueio de dados e abertura automática do período seguinte
- Histórico de auditoria de todas as alterações críticas (usuário, data, valor anterior e novo)
- Geração de um "Placar do Dia" em imagem, para compartilhamento com a equipe

## Funcionalidades
- Cadastro e gestão de vendedores e metas mensais
- Lançamento diário de vendas e ajustes da filial
- Ranking com percentual, valor restante e meta diária necessária por vendedor
- Fechamento mensal com imutabilidade dos dados e trilha de auditoria
- Dashboard anual com evolução mês a mês e ranking acumulado por vendedor
- Relatórios consolidados da filial e de ranking diário
- Placar do Dia exportável como imagem, pronto para WhatsApp ou e-mail
- Login individual da gestora via Firebase Authentication

## Processo de validação
O sistema foi construído e testado em quatro fases (cadastro e metas → operação diária e ranking → fechamento e auditoria → dashboard e relatórios), cada uma validada com dados reais da filial antes de avançar. Esse processo permitiu identificar e corrigir ajustes de usabilidade ao longo do caminho — como a exibição das cores de desempenho e o nível de detalhe do Placar do Dia, incorporados nas iterações seguintes.

## Stack
- Firebase / Firestore (armazenamento e autenticação)
- Desenvolvimento assistido por IA generativa, sob orientação e validação da autora

## Aprendizados
Este projeto reforçou minha experiência em especificação formal de requisitos, priorização de funcionalidades por fases de valor incremental, e validação iterativa de produto com usuário real, habilidades centrais para atuação em Coordenação de Projetos e Product Ownership.
