# Guardião 360° - Painel de Gestão Operacional

## 📖 Descrição do Projeto

`Guardião 360°` é uma plataforma web robusta de gestão interna, projetada especificamente para o Corpo de Bombeiros. O sistema visa centralizar o registro, acompanhamento e análise de ocorrências, além de fornecer ferramentas administrativas essenciais para a gestão de usuários, auditoria de ações e geração de relatórios operacionais.

## ⚠️ Status do Projeto: Em Andamento (Fase de Prototipação)

Atualmente, o projeto encontra-se na fase inicial de desenvolvimento, focado na prototipação e estruturação visual (UI). Todas as telas listadas abaixo foram construídas com **HTML5** e **CSS3** para validar o design e a experiência do usuário (UX) antes da implementação do back-end e da lógica de programação.

## ✨ Funcionalidades Planejadas

Este projeto está sendo construído com base em um conjunto de *features* (funcionalidades) definidas, que incluem:

* **W-01: Login & Perfis:** Acesso distintos para admin, analista e chefe, limitando o acesso a dados e funcionalidades.
* **W-02: Lista & Filtros de Ocorrências:** Capacidade de filtrar ocorrências por período, tipo, região, status, e incluir paginação.
* **W-03: Visualização de Detalhe:** Ver campos detalhados da ocorrência, mídias, localização, timeline e baixar anexos.
* **W-04: Relatórios Básicos & Exportação:** Gerar e exportar relatórios em CSV/PDF com métricas selecionadas.
* **W-05: Gestão de Usuários:** CRUD (Criar, Ler, Atualizar, Deletar) de usuários, redefinição de senha e vinculação de perfis.
* **W-06: Auditoria & Logs:** Trilhas de auditoria para saber "quem fez o quê e quando", com filtros por evento.
* **W-07: Dashboard Operacional:** Apresentação de KPIs (Indicadores-Chave de Performance) simples, com cards e gráficos de ocorrências.
* **(Futuro) W-08: Catálogo/Form Builder:** Permitir a criação e alteração de campos de formulários dinamicamente.

## 💻 Telas Concluídas (HTML/CSS)

Até o momento, as seguintes telas estáticas foram desenvolvidas, servindo como protótipos visuais do sistema:

* **Login** (`login.html`, `login.css`)
* **Recuperação de Senha** (`recuperar-senha.html`, `recuperar-senha.css`)
* **Lista de Ocorrências (Tela Principal)** (`telaprincipalocorrencias.html`, `dashboard.css`)
* **Detalhes da Ocorrência** (`detalhes-ocorrencia.html`, `detalhes.css`)
* **Gestão de Usuários** (`gestao-usuarios.html`, `gestao-usuarios.css`)
* **Auditoria e Logs de Ações** (`auditoria.html`, `auditoria.css`)
* **Ajustes de Perfil** (`ajustes.html`, `ajustes.css`)
* **Dashboard Operacional** (`dashboard-operacional.html`, `dashboard-operacional.css`)
* **Relatórios Analíticos** (`relatorios.html`, `relatorios.css`)

## 🛠️ Tecnologias Utilizadas (Fase Atual)

* **HTML5:** Para a estruturação semântica das páginas.
* **CSS3:** Para estilização, layout (Flexbox/Grid) e responsividade.
* **Font Awesome:** Para a biblioteca de ícones.
* **Google Fonts (Nunito Sans):** Para a tipografia do projeto.

## 🚀 Como Visualizar

Como este é um projeto front-end estático (apenas HTML/CSS), não há necessidade de instalação de dependências ou de um servidor.

1.  Clone este repositório:
    ```bash
    git clone [URL_DO_SEU_REPOSITORIO]
    ```
2.  Navegue até a pasta do projeto.
3.  Abra qualquer um dos arquivos `.html` (por exemplo, `login.html`) diretamente no seu navegador de preferência.
