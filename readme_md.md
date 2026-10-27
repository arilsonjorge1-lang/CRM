# 🚀 ApexCRM Pro (CVE) - Gestão Comercial & Pipeline de Vendas

![Versão](https://img.shields.io/badge/vers%C3%A3o-2.0.0-blue.svg)
![Licença](https://img.shields.io/badge/licen%C3%A7a-MIT-green.svg)
![Tecnologias](https://img.shields.io/badge/stack-HTML5%20%7C%20TailwindCSS%20%7C%20JS%20ES6+-orange.svg)
![Moeda](https://img.shields.io/badge/moeda-CVE%20(%24)-blueviolet.svg)

O **ApexCRM Pro** é uma solução leve, moderna e interativa desenvolvida para a gestão eficiente de funis de vendas, oportunidades e relacionamento com clientes. Desenvolvido no formato **Single File Application (SFA)**, funciona diretamente no navegador web, garantindo alta performance sem necessidade de servidores backend ou dependências de instalação.

---

## 📸 Funcionalidades Principais

- **📋 Quadro Kanban Interativo:** Sistema *Drag & Drop* para movimentar oportunidades entre as 4 etapas do funil (*Novo Lead*, *Em Contato*, *Proposta Enviada* e *Venda Fechada*).
- **📊 Dashboard de KPIs em Tempo Real:** Cálculo automático do valor em pipeline, faturamento total, número de oportunidades ativas e taxa de conversão.
- **🏷️ Tags de Priorização:** Categorização visual por perfis (*VIP*, *Urgente*, *Hot Lead*, *Recorrente*, *Governo*).
- **📅 Controle de Follow-up:** Agendamento de próximas ações com alerta visual automático para tarefas vencidas ou do dia.
- **🔍 Filtros & Busca Instantânea:** Localização rápida por nome, empresa ou tag de prioridade.
- **📥 Relatórios & Exportação:** Download dos dados do funil em formato `.CSV` (compatível com Excel) e exportação de backup estruturado em `.JSON`.
- **🌙 Interface Adaptável (Dark/Light Mode):** Suporte nativo a tema escuro e claro com salvamento de preferência.
- **💾 Persistência de Dados Offline:** Dados armazenados localmente no navegador via `LocalStorage`.

---

## 🛠️ Tecnologias Utilizadas

* **HTML5:** Estrutura semântica e acessível.
* **Tailwind CSS (via CDN):** Estilização utilitária responsiva no padrão UI/UX SaaS.
* **JavaScript (ES6+):** Manipulação da DOM, drag & drop API, gestão de estado local e relatórios.
* **Lucide Icons:** Iconografia moderna em SVG.
* **Google Fonts (Plus Jakarta Sans):** Tipografia para interfaces digitais.

---

## 🚀 Como Executar o Projeto

### Rodar Localmente
1. Faça o download ou clone do repositório:
   ```bash
   git clone https://github.com/seu-usuario/apexcrm-pro.git
   ```
2. Abra a pasta do projeto e dê um duplo clique no arquivo `index.html` para abrir em qualquer navegador (Chrome, Edge, Firefox, Safari).

### Publicar no GitHub Pages (Gratuito)
1. No seu repositório do GitHub, vá em **Settings** > **Pages**.
2. Na opção **Branch**, selecione `main` (ou `master`) e clique em **Save**.
3. O projeto estará disponível online no link gerado pelo GitHub em poucos instantes.

---

## 📖 Guia Rápido de Uso

1. **Cadastrar Oportunidade:** Clique em **"Novo Lead"**, preencha os dados do cliente, valor estimado (CVE `$`), tag e data de retorno.
2. **Gerenciar Funil:** Arraste os cartões entre as colunas conforme o avanço das negociações.
3. **Analisar Desempenho:** Clique no botão de **Relatório** (ícone de gráfico) no topo para visualizar métricas agregadas e ticket médio.
4. **Exportar Dados:** Utilize o botão de download `.CSV` para exportar a lista completa de clientes para relatórios externos.

---

## 📜 Licença

Este projeto está licenciado sob a Licença **MIT** - consulte o arquivo [LICENSE](LICENSE) para mais detalhes.