# 📊 SAP Smart Analytics & Report Bot

![Status](https://img.shields.io/badge/Status-Concluído-success)
![Tipo](https://img.shields.io/badge/Tipo-Enterprise%2FShowcase-blue)
![Integração](https://img.shields.io/badge/Integração-SAP%20ERP-orange)

> 🔒 **Aviso de Propriedade Intelectual:** Este é um repositório de demonstração (Showcase). Por motivos de confidencialidade (NDA) e proteção de regras de negócio, o código-fonte proprietário não está público. Este espaço detalha a arquitetura, os desafios e o valor entregue pela solução.

## 💡 O Desafio Operacional
A gestão de dados da usina contava com a robustez do SAP, porém a extração de inteligência analítica era engessada. O time dependia de exportações manuais e horas de manipulação no Excel (PROCV e Macros) para gerar relatórios gerenciais. Faltava dinamismo para criar cenários rápidos que apoiassem a tomada de decisão da diretoria em relação a compras e estoque.

## ⚙️ A Solução Desenvolvida
Projetei e desenvolvi uma solução ponta a ponta composta por um motor de processamento de dados e um **Bot interativo**, eliminando a dependência de planilhas manuais.

A arquitetura do projeto atua em três frentes:
1. **Extração e Leitura:** Captura e leitura automatizada dos relatórios brutos emitidos pelo SAP em formato CSV (Pedidos de Compra, Movimentação de Estoque/Kardex e Cadastro Base de Materiais).
2. **Processamento e Cruzamento:** Motor lógico que cruza os dados das três bases para extrair inteligência real de negócio.
3. **Bot Gerador de Cenários:** Uma interface onde o gerente/usuário insere parâmetros e o Bot monta relatórios dinâmicos sob demanda, entregando o cenário exato que a diretoria precisa ver.

## 🚀 Principais Funcionalidades e Dashboards
O cruzamento de dados alimenta painéis de BI de alto impacto para a diretoria, destacando:
* 🏆 **Top 10 Produtos:** Identificação instantânea dos itens de maior custo.
* 📈 **Curva ABC de Consumo:** Classificação inteligente do inventário para priorização de fluxo de caixa.
* 🤝 **Ranking de Fornecedores:** Análise de volume financeiro por parceiro comercial.
* 💡 **Sugestão de Ressuprimento:** Algoritmo que sugere contratos e compras com base no histórico de movimentação.

## 🎯 Resultados Alcançados
* **Automação Total:** Eliminação do uso de planilhas manuais e macros quebradas.
* **Agilidade na Decisão:** Cenários complexos que demoravam horas agora são montados pelo Bot em segundos.
* **Governança:** A diretoria passou a consumir indicadores (KPIs) confiáveis, rastreáveis e extraídos diretamente da fonte (SAP), blindando a operação contra falhas humanas na manipulação dos dados.