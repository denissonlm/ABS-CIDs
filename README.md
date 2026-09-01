# Açotubo | ABSENTEÍSMO - CID'S 2026

Dashboard corporativo executivo para consolidação e análise periódica de atestados médicos e afastamentos por CID (Classificação Internacional de Doenças) para o **Grupo Açotubo**.

---

## 🚀 Funcionalidades Principais

- **Visão Geral Executiva**: Totalizador consolidado de **20.646,38 horas** de afastamento com gráficos em paleta corporativa (Branco, Vermelho, Preto e Cinza).
- **Importador da Pasta "Fontes"**: Suporte a upload em lote de arquivos `.xlsx` com leitura automática do período a partir do nome do arquivo.
- **Adequação Inteligente de CIDs**: Enquadramento automático no capítulo CID-10 oficial mais próximo (sem categorias genéricas como "Outros" ou dados em branco).
- **Painel de Auditoria de Planilhas**: Rastreamento detalhado de anomalias com indicação exata do arquivo e número da linha do Excel.
- **Monitoramento de Recorrência & Colaboradores**: Acompanhamento de casos frequentes e matriz de planos de ação preventiva.
- **Exportação & Persistência**: Exportação dos dados para Excel (`.xlsx`), backup em JSON e armazenamento em `localStorage`.

---

## 🛠️ Tecnologias Utilizadas

- **HTML5 & Vanilla JavaScript**: Sem dependências de build pesadas.
- **Tailwind CSS**: Estilização moderna e responsiva.
- **Chart.js**: Gráficos analíticos interativos de alta precisão.
- **SheetJS (`xlsx.full.min.js`)**: Processamento nativo de planilhas Excel direto no navegador.
- **Lucide Icons**: Ícones corporativos vetorizados.

---

## 🌐 Publicação na Vercel

1. Suba este repositório no seu GitHub (ex: `acotubo-bi-cids-dashboard`).
2. Acesse [vercel.com](https://vercel.com) e conecte o repositório.
3. Deploy instantâneo como aplicação estática.
