<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:FF5A00,100:1C1E24&height=220&section=header&text=Frotas%20e%20Expedi%C3%A7%C3%B5es&fontSize=46&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=Fleet%20%C3%97%20Logistics%20%C3%97%20Operations%20Management&descAlignY=58&descSize=18" width="100%" alt="banner"/>

<a href="https://git.io/typing-svg">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=20&duration=3500&pause=900&color=FF5A00&center=true&vCenter=true&width=750&lines=Fleet+management+%7C+Gest%C3%A3o+de+frota;Drivers%2C+routes+%26+dispatches+%7C+Expedi%C3%A7%C3%B5es;Real-time+dashboard+%7C+Painel+em+tempo+real;Built+for+a+real+operation+in+MS%2C+Brazil" alt="Typing SVG" />
</a>

<br/><br/>

### <a href="#english">🇺🇸 English</a> &nbsp;|&nbsp; <a href="#portugues">🇧🇷 Português</a>

<br/>

![Status](https://img.shields.io/badge/status-live%20demo-FF5A00?style=for-the-badge&logo=vercel&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-vanilla-1C1E24?style=for-the-badge&logo=javascript&logoColor=F7DF1E)
![Tailwind](https://img.shields.io/badge/TailwindCSS-FF7A2E?style=for-the-badge&logo=tailwindcss&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-production-E04E00?style=for-the-badge&logo=firebase&logoColor=white)

<br/>

### 🌐 [**Open the live demo / Abrir a demonstração**](https://demofrotasexpedicoes.vercel.app/)

</div>

<br/>

<!-- ======================================================== -->
<!-- ======================= ENGLISH ======================== -->
<!-- ======================================================== -->

<a id="english"></a>

# 🇺🇸 English

## 📌 About the project

> *"The data existed. It was just scattered across spreadsheets, chats and notebooks."*

**Frotas & Expedições** is a web app for day-to-day operations management, born from a real need of an
operations coordinator at an **autonomous convenience store chain in Mato Grosso do Sul, Brazil**. Fleet,
drivers, stores, routes, fueling, inspections and maintenance were tracked in different places, which made
it hard to control costs, follow the operation and make decisions.

I mapped the logistics flow with the coordinator, defined what had to be tracked and turned it into **one
dashboard** shaped around his actual routine.

- 🚚 **Fleet & drivers** in one place, with vehicle status updated automatically
- 📦 **Dispatches** with departure/arrival odometer and automatic km driven
- 🔧 **17-item inspections** and maintenance records with invoice photo
- ⛽ **Fueling** with automatic price per liter
- 📊 **Dashboard + reports** filterable by period, driver, vehicle, route and status, exportable to Excel and PDF
- 🪪 **Alerts** for driver's licenses (CNH) expired or expiring within 30 days

<br/>

## 🧩 How it was built

<div align="center">

<table>
<tr>
<td align="center" width="20%">🔍<br/><b>Diagnosis</b><br/><sub>Pain points with the coordinator</sub></td>
<td align="center">➜</td>
<td align="center" width="20%">🗺️<br/><b>Mapping</b><br/><sub>End-to-end logistics flow</sub></td>
<td align="center">➜</td>
<td align="center" width="20%">📐<br/><b>Indicators</b><br/><sub>What to track and why</sub></td>
<td align="center">➜</td>
<td align="center" width="20%">🔁<br/><b>Validation</b><br/><sub>Check-ins and adjustments</sub></td>
<td align="center">➜</td>
<td align="center" width="20%">💻<br/><b>Web app</b><br/><sub>Firebase + public demo</sub></td>
</tr>
</table>

</div>

I built it with **vanilla HTML, CSS and JavaScript**, with **Claude (Anthropic)** as a coding copilot. The goal
was a tool that costs nothing to run: free-tier cloud resources and no paid software licenses.

**Operational pains and how the app answers them:**

| Pain | Solution |
|---|---|
| Nobody knew which vehicles were free | Vehicle status (**Available / In use / Maintenance**) is derived automatically from open dispatches and maintenance |
| Km driven calculated by hand | Each dispatch stores departure and arrival odometer and **calculates the km driven** on finish |
| Fuel costs hard to compare | Every fueling record computes the **price per liter** from total value and liters |
| Licenses expiring unnoticed | The dashboard shows a **warning** for CNH expired or expiring within 30 days |
| Duplicate vehicle records | **Unique check** on plate, Renavam and chassis |
| Reports assembled by hand | General report with filters, **CSV export** for Excel and **print / save as PDF** |

<br/>

## 🛠️ Tech Stack

<table>
<tr>
<td width="50%" valign="top">

### 💻 Frontend
<img src="https://img.shields.io/badge/HTML5-FF5A00?style=for-the-badge&logo=html5&logoColor=white"/>
<img src="https://img.shields.io/badge/CSS3-E04E00?style=for-the-badge&logo=css3&logoColor=white"/>
<img src="https://img.shields.io/badge/JavaScript-1C1E24?style=for-the-badge&logo=javascript&logoColor=F7DF1E"/>
<img src="https://img.shields.io/badge/TailwindCSS-FF7A2E?style=for-the-badge&logo=tailwindcss&logoColor=white"/>

</td>
<td width="50%" valign="top">

### ☁️ Backend & Hosting
<img src="https://img.shields.io/badge/Firebase%20Auth-E04E00?style=for-the-badge&logo=firebase&logoColor=white"/>
<img src="https://img.shields.io/badge/Firestore-FF5A00?style=for-the-badge&logo=firebase&logoColor=white"/>
<img src="https://img.shields.io/badge/Security%20Rules-1C1E24?style=for-the-badge&logo=firebase&logoColor=white"/>
<img src="https://img.shields.io/badge/Vercel-1C1E24?style=for-the-badge&logo=vercel&logoColor=white"/>

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 📊 Data & Reports
<img src="https://img.shields.io/badge/localStorage%20(demo)-FF7A2E?style=for-the-badge&logoColor=white"/>
<img src="https://img.shields.io/badge/CSV%20%2F%20Excel-E04E00?style=for-the-badge&logoColor=white"/>
<img src="https://img.shields.io/badge/Print%20to%20PDF-FF5A00?style=for-the-badge&logoColor=white"/>

</td>
<td width="50%" valign="top">

### 🧰 Tools
<img src="https://img.shields.io/badge/Git-FF5A00?style=for-the-badge&logo=git&logoColor=white"/>
<img src="https://img.shields.io/badge/GitHub-1C1E24?style=for-the-badge&logo=github&logoColor=white"/>
<img src="https://img.shields.io/badge/Claude%20(copilot)-E04E00?style=for-the-badge&logo=anthropic&logoColor=white"/>

</td>
</tr>
</table>

<br/>

## ✨ What it does

| Module | What you can do |
|---|---|
| 📊 Dashboard | Expeditions, km driven, vehicles in use / available / in maintenance, active drivers, critical inspections, charts by period |
| 👤 Drivers | Name, contact, CNH number and expiry date, active/inactive status |
| 🚚 Vehicles | Name, code, plate, model year, Renavam, chassis, owner and automatic status |
| 🏪 Stores · 🛣️ Routes | Stores by city, routes with linked stores, responsible driver and weekdays |
| ⛽ Fueling | Date, vehicle, driver, fuel type, liters, total value and price per liter |
| 📝 Inspections | Odometer, dashboard alerts and a **17-item checklist** rated OK / Attention / Critical |
| 🔧 Maintenance | Workshop, invoice number and photo, service, value, open/finished |
| 📦 Expeditions | Driver + route + vehicle, departure and return notes, one-click finish |

<br/>

## 🏗️ Architecture

The whole demo lives in **a single HTML file (~640 lines)**, with no build step.

| Part | What it does |
|---|---|
| ⚙️ `E` (entity config) | Describes each module once (fields, types, columns), and forms and tables are generated from it |
| 🧠 Business rules | Vehicle status, km driven, price per liter, CNH alerts, unique fields |
| 🖥️ Rendering | Template strings + Tailwind; sidebar, cards, tables, modals and toasts |
| 💾 Storage | `localStorage` in the demo; Firebase Auth + Firestore with Security Rules in production |
| 🧾 Reports | Filters, CSV export and a print-only layout for PDF |

Adding a new module is mostly configuration:

```js
const E = {
  lojas: {
    t: 'Lojas', n: 'Nova loja',
    f: [['nomeLoja', 'Nome da loja'], ['cidade', 'Cidade'], ['observacoes', 'Observações', 'textarea']],
    c: ['nomeLoja', 'cidade', 'observacoes']
  }
}
```

<br/>

## 🔐 About this demo

| | |
|---|---|
| 🏢 **Production** | The client's version has login and password, **role-based access** (Coordinator and Driver) and a Firebase database |
| 🧪 **Public demo** | Runs entirely in the browser with **fictional data** in `localStorage`, so no company data is exposed |
| ♻️ **Reset** | The **"Restaurar Dados Iniciais"** button brings back the original sample data at any time |

<br/>

## 🚀 Getting started

Just use the [live demo](https://demofrotasexpedicoes.vercel.app/), or run it locally:

```bash
git clone https://github.com/amandapasqualotto/frotas-expedicoesdemo.git
cd frotas-expedicoesdemo
# open index.html.html in your browser (internet needed for Tailwind and fonts)
```

<br/>

<div align="center">

<a href="#portugues">🇧🇷 Ler em Português</a> &nbsp;|&nbsp; <a href="#english">⬆️ Back to top</a>

</div>

<br/>

---

<br/>

<!-- ======================================================== -->
<!-- ====================== PORTUGUÊS ======================= -->
<!-- ======================================================== -->

<a id="portugues"></a>

# 🇧🇷 Português

## 📌 Sobre o projeto

> *"Os dados existiam. Só estavam espalhados em planilhas, conversas e cadernos."*

O **Frotas & Expedições** é um app web de gestão operacional que nasceu de uma necessidade real de um
coordenador de operações de uma **rede de minimercados autônomos em Mato Grosso do Sul**. Frota, motoristas,
lojas, rotas, abastecimentos, inspeções e manutenções eram controlados em lugares diferentes, o que dificultava
o controle de gastos, o acompanhamento da operação e a tomada de decisões.

Mapeei o fluxo logístico junto com o coordenador, defini o que precisava ser acompanhado e transformei tudo
em **um único painel**, pensado para a rotina real dele.

- 🚚 **Frota e motoristas** em um só lugar, com status do veículo atualizado sozinho
- 📦 **Expedições** com KM de saída e chegada e cálculo automático do KM rodado
- 🔧 **Inspeções com 17 itens** e registro de manutenções com foto da nota fiscal
- ⛽ **Abastecimentos** com cotação por litro calculada automaticamente
- 📊 **Painel e relatórios** filtráveis por período, motorista, veículo, rota e status, exportáveis para Excel e PDF
- 🪪 **Alertas** de CNH vencida ou vencendo em até 30 dias

<br/>

## 🧩 Como foi construído

<div align="center">

<table>
<tr>
<td align="center" width="20%">🔍<br/><b>Diagnóstico</b><br/><sub>Dores com o coordenador</sub></td>
<td align="center">➜</td>
<td align="center" width="20%">🗺️<br/><b>Mapeamento</b><br/><sub>Fluxo logístico completo</sub></td>
<td align="center">➜</td>
<td align="center" width="20%">📐<br/><b>Indicadores</b><br/><sub>O que acompanhar e por quê</sub></td>
<td align="center">➜</td>
<td align="center" width="20%">🔁<br/><b>Validação</b><br/><sub>Reuniões e ajustes</sub></td>
<td align="center">➜</td>
<td align="center" width="20%">💻<br/><b>App web</b><br/><sub>Firebase + demo pública</sub></td>
</tr>
</table>

</div>

Desenvolvi com **HTML, CSS e JavaScript puros**, usando o **Claude (Anthropic)** como copiloto de código. O
objetivo era uma ferramenta que não custasse nada para rodar: recursos gratuitos de nuvem e nenhuma licença
de software paga.

**Dores da operação e como o app resolve:**

| Dor | Solução |
|---|---|
| Ninguém sabia quais veículos estavam livres | O status (**Disponível / Em uso / Manutenção**) é calculado sozinho a partir das expedições e manutenções abertas |
| KM rodado calculado na mão | Cada expedição guarda o KM de saída e de chegada e **calcula o KM rodado** ao finalizar |
| Gastos com combustível difíceis de comparar | Cada abastecimento calcula a **cotação por litro** a partir do valor total e dos litros |
| CNHs vencendo sem ninguém perceber | O painel mostra um **aviso** de CNH vencida ou vencendo em até 30 dias |
| Veículos cadastrados em duplicidade | **Verificação de unicidade** de placa, Renavam e chassi |
| Relatórios montados manualmente | Relatório geral com filtros, **exportação em CSV** para Excel e **impressão / salvar em PDF** |

<br/>

## 🛠️ Tecnologias

<table>
<tr>
<td width="50%" valign="top">

### 💻 Frontend
<img src="https://img.shields.io/badge/HTML5-FF5A00?style=for-the-badge&logo=html5&logoColor=white"/>
<img src="https://img.shields.io/badge/CSS3-E04E00?style=for-the-badge&logo=css3&logoColor=white"/>
<img src="https://img.shields.io/badge/JavaScript-1C1E24?style=for-the-badge&logo=javascript&logoColor=F7DF1E"/>
<img src="https://img.shields.io/badge/TailwindCSS-FF7A2E?style=for-the-badge&logo=tailwindcss&logoColor=white"/>

</td>
<td width="50%" valign="top">

### ☁️ Backend e Hospedagem
<img src="https://img.shields.io/badge/Firebase%20Auth-E04E00?style=for-the-badge&logo=firebase&logoColor=white"/>
<img src="https://img.shields.io/badge/Firestore-FF5A00?style=for-the-badge&logo=firebase&logoColor=white"/>
<img src="https://img.shields.io/badge/Security%20Rules-1C1E24?style=for-the-badge&logo=firebase&logoColor=white"/>
<img src="https://img.shields.io/badge/Vercel-1C1E24?style=for-the-badge&logo=vercel&logoColor=white"/>

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 📊 Dados e Relatórios
<img src="https://img.shields.io/badge/localStorage%20(demo)-FF7A2E?style=for-the-badge&logoColor=white"/>
<img src="https://img.shields.io/badge/CSV%20%2F%20Excel-E04E00?style=for-the-badge&logoColor=white"/>
<img src="https://img.shields.io/badge/Imprimir%20em%20PDF-FF5A00?style=for-the-badge&logoColor=white"/>

</td>
<td width="50%" valign="top">

### 🧰 Ferramentas
<img src="https://img.shields.io/badge/Git-FF5A00?style=for-the-badge&logo=git&logoColor=white"/>
<img src="https://img.shields.io/badge/GitHub-1C1E24?style=for-the-badge&logo=github&logoColor=white"/>
<img src="https://img.shields.io/badge/Claude%20(copiloto)-E04E00?style=for-the-badge&logo=anthropic&logoColor=white"/>

</td>
</tr>
</table>

<br/>

## ✨ O que ele faz

| Módulo | O que dá para fazer |
|---|---|
| 📊 Dashboard | Expedições, KM rodado, veículos em uso / disponíveis / em manutenção, motoristas ativos, inspeções críticas, gráficos por período |
| 👤 Motoristas | Nome, contato, número e validade da CNH, status ativo/inativo |
| 🚚 Veículos | Nome, código, placa, mês/ano, Renavam, chassi, proprietário e status automático |
| 🏪 Lojas · 🛣️ Rotas | Lojas por cidade, rotas com lojas vinculadas, motorista responsável e dias da semana |
| ⛽ Abastecimentos | Data, veículo, motorista, combustível, litros, valor total e cotação por litro |
| 📝 Inspeções | Odômetro, alertas do painel e **checklist de 17 itens** avaliados como OK / Atenção / Crítico |
| 🔧 Manutenção | Oficina, número e foto da nota fiscal, serviço, valor, aberta/finalizada |
| 📦 Expedições | Motorista + rota + veículo, observações de saída e retorno, finalização com um clique |

<br/>

## 🏗️ Arquitetura

A demonstração inteira fica em **um único arquivo HTML (cerca de 640 linhas)**, sem etapa de build.

| Parte | O que faz |
|---|---|
| ⚙️ `E` (configuração das entidades) | Descreve cada módulo uma vez só (campos, tipos, colunas), e os formulários e tabelas são gerados a partir disso |
| 🧠 Regras de negócio | Status do veículo, KM rodado, cotação por litro, alertas de CNH, campos únicos |
| 🖥️ Renderização | Template strings + Tailwind; menu lateral, cards, tabelas, modais e avisos |
| 💾 Armazenamento | `localStorage` na demo; Firebase Auth + Firestore com Security Rules em produção |
| 🧾 Relatórios | Filtros, exportação em CSV e layout próprio para impressão em PDF |

Criar um módulo novo é, na maior parte, configuração:

```js
const E = {
  lojas: {
    t: 'Lojas', n: 'Nova loja',
    f: [['nomeLoja', 'Nome da loja'], ['cidade', 'Cidade'], ['observacoes', 'Observações', 'textarea']],
    c: ['nomeLoja', 'cidade', 'observacoes']
  }
}
```

<br/>

## 🔐 Sobre esta demonstração

| | |
|---|---|
| 🏢 **Produção** | A versão do cliente tem login e senha, **perfis de acesso** (Coordenador e Motorista) e banco de dados no Firebase |
| 🧪 **Demo pública** | Roda inteira no navegador com **dados fictícios** no `localStorage`, sem expor nenhuma informação da empresa |
| ♻️ **Restaurar** | O botão **"Restaurar Dados Iniciais"** traz de volta os dados de exemplo a qualquer momento |

<br/>

## 🚀 Como usar

É só abrir a [demonstração online](https://demofrotasexpedicoes.vercel.app/), ou rodar no seu computador:

```bash
git clone https://github.com/amandapasqualotto/frotas-expedicoesdemo.git
cd frotas-expedicoesdemo
# abra o arquivo index.html.html no navegador (precisa de internet para o Tailwind e as fontes)
```

<br/>

## 📚 Principais aprendizados

Mais do que escrever código, o desafio foi **entender a dor real de quem usa** e transformá-la em uma ferramenta
prática. O projeto juntou gestão operacional, análise de processos e desenvolvimento, e me ensinou a
priorizar o que o usuário de fato precisa no dia a dia.

<br/>

<div align="center">

Feito com 🧡 por [Amanda Pasqualotto](https://github.com/amandapasqualotto)

<br/>

<a href="#english">🇺🇸 Read in English</a> &nbsp;|&nbsp; <a href="#portugues">⬆️ Voltar ao topo</a>

</div>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:1C1E24,100:FF5A00&height=120&section=footer" width="100%" alt="footer"/>
