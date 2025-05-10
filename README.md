# projetohelpdeskphp

---

### 📌 **Descrição do Projeto: Sistema Help Desk em PHP**

**Nome do Projeto:** Sistema Help Desk Web – Suporte Técnico e Atendimento ao Cliente
**Tecnologias Utilizadas:** PHP, MySQL, HTML, CSS, JavaScript (AJAX), Bootstrap
**Arquitetura:** MVC (Model-View-Controller)
**Tipo de Projeto:** Web Application (Sistema Web Responsivo)

---

### 🧾 **Resumo**

Este projeto consiste em um sistema de **Help Desk** desenvolvido em PHP, com foco em facilitar o gerenciamento de chamados de suporte técnico. A aplicação permite que usuários finais registrem solicitações de ajuda (tickets), enquanto técnicos ou administradores gerenciam, respondem e acompanham o progresso desses chamados em tempo real. A interface é responsiva e intuitiva, com funcionalidades que otimizam o fluxo de atendimento ao cliente.

---

### 🔧 **Funcionalidades Principais**

#### 👤 Área do Usuário

* Abertura de chamados com título, descrição e categoria.
* Anexar arquivos (prints, documentos, etc.).
* Acompanhamento do status do chamado (aberto, em andamento, resolvido, fechado).
* Histórico de chamados abertos pelo usuário.
* Notificações de atualizações nos tickets via e-mail (opcional).

#### 🔧 Área do Suporte Técnico

* Visualização de todos os chamados abertos.
* Filtros por status, prioridade e categoria.
* Resposta direta aos chamados.
* Mudança de status do ticket.
* Encaminhamento de chamados entre setores.

#### ⚙️ Área do Administrador

* Cadastro e gerenciamento de usuários (clientes e técnicos).
* Cadastro de categorias de chamados (ex: TI, Financeiro, RH).
* Geração de relatórios por período, categoria ou responsável.
* Painel com métricas e estatísticas de atendimento (tempo médio, chamados por técnico, etc.).

---

### 🔐 **Controle de Acesso**

O sistema possui um mecanismo de autenticação seguro, com diferentes níveis de acesso:

* **Usuário comum:** Pode abrir e visualizar apenas seus próprios chamados.
* **Técnico:** Pode visualizar e responder chamados de sua categoria/setor.
* **Administrador:** Tem acesso completo a todos os recursos e configurações do sistema.

---

### 🗃️ **Banco de Dados**

O projeto utiliza **MySQL** para armazenar todas as informações:

* Tabela de usuários
* Tabela de chamados
* Tabela de respostas
* Tabela de categorias
* Tabela de logs (opcional para auditoria)

---

### 🧩 **Extras e Integrações**

* **Validações de formulário** (client-side e server-side).
* **AJAX** para atualizações dinâmicas sem reload de página.
* **Editor de texto enriquecido (WYSIWYG)** para facilitar a descrição dos chamados.
* **Exportação de relatórios** em PDF ou CSV (funcionalidade adicional).

---

### 🎯 **Objetivo do Projeto**

O objetivo principal é fornecer uma solução completa, acessível e customizável para empresas que precisam organizar e automatizar o atendimento interno e externo via chamados. Ideal para **empresas de tecnologia, setores de TI, provedores de internet, escolas e departamentos administrativos.**

---

### 📌 **Diferenciais do Projeto**

* Código limpo e bem estruturado seguindo o padrão MVC.
* Interface amigável com design responsivo.
* Fácil implementação e manutenção.
* Pode ser hospedado em servidores compartilhados (PHP/MySQL).
* Possibilidade de expansão com APIs ou novos módulos (ex: chat ao vivo, integração com WhatsApp).

---

Se quiser, posso complementar com o código-fonte base, sugestões de melhorias ou até criar um repositório com README para hospedagem no GitHub. Deseja seguir com isso?
