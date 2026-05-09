# 🏟️ Grêmio Arena Dashboard

Dashboard interativo e dinâmico para análise de arrecadação e bilhetagem da Arena do Grêmio. Projeto desenvolvido para visualização rápida de métricas financeiras e ocupação por setor.

🔗 **Acesse o Dashboard Online:** [https://meneguinha.github.io/arena-dash/](https://meneguinha.github.io/arena-dash/)

---

## 🚀 Funcionalidades Principais

- **Carregamento Inteligente**: Sincronização automática com o arquivo `dados_gremio_processados.xlsx` no repositório.
- **Filtros Dinâmicos**: Filtragem por **Ano (2023-2025)** e **Visitante** com atualização em tempo real de todos os gráficos.
- **Visualizações Avançadas (ApexCharts)**:
  - **Arrecadação por Setor**: Gráfico de barras horizontais com quebra de texto para nomes longos.
  - **Bilhetes Vendidos**: Donut chart com escala de azul progressiva e totalizador central.
  - **Evolução por Jogo**: Gráfico de linha suave (smooth) com ordenação cronológica precisa.
- **Tabela Detalhada**: Listagem completa dos registros com suporte a ordenação (A-Z / Z-A) em todas as colunas.
- **Interface Premium**: Design responsivo com animações de elevação nos cards e sombras dinâmicas.

---

## 📊 Estrutura de Dados

O dashboard processa arquivos nos formatos `.xlsx` e `.csv`. Para o correto funcionamento automático, o arquivo deve conter as colunas:
- `Data` (DD/MM/YYYY)
- `Mandante` / `Visitante`
- `Setor`
- `Vendidos`
- `Arrecadacao`

---

## 🛠️ Tecnologias Utilizadas

- **Frontend**: HTML5, Tailwind CSS (Design Premium)
- **Gráficos**: ApexCharts.js
- **Processamento de Dados**: SheetJS (XLSX) & PapaParse (CSV)
- **Hospedagem**: GitHub Pages

---

## 📄 Licença

Este projeto é de uso demonstrativo para gestão de dados esportivos.
