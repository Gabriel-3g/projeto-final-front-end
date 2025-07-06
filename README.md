# VidaPlus - Sistema de Gestão Hospitalar

## 📋 Descrição

O VidaPlus é um sistema completo de gestão hospitalar desenvolvido em HTML, CSS e JavaScript. O sistema oferece uma interface moderna e intuitiva para gerenciar diferentes aspectos de um ambiente hospitalar, com painéis específicos para administradores, profissionais de saúde e pacientes.

## 🎯 Funcionalidades Principais

### 🔐 Sistema de Autenticação
- Login Multiperfil: Suporte para três tipos de usuários:
  - Administrador: Acesso completo ao sistema
  - Profissional de Saúde: Acesso às funcionalidades médicas
  - Paciente: Acesso ao próprio histórico e agendamentos

### 👨‍💼 Painel do Administrador
- Dashboard com estatísticas em tempo real
- Gestão de usuários e permissões
- Relatórios e análises
- Configurações do sistema
- Monitoramento de atividades

### 👩‍⚕️ Painel do Profissional de Saúde
- Gestão de pacientes
- Agendamento de consultas
- Histórico médico
- Prescrições e exames
- Comunicação com pacientes

### 👤 Painel do Paciente
- Visualização do histórico médico
- Agendamento de consultas
- Resultados de exames
- Comunicação com profissionais
- Perfil pessoal

## 🚀 Tecnologias Utilizadas

- HTML5: Estrutura semântica e acessível
- CSS3: Design responsivo e moderno
  - Flexbox e Grid para layouts
  - Animações e transições suaves
  - Design system com variáveis CSS
- JavaScript: Funcionalidades interativas
- Font Awesome: Ícones profissionais
- Google Fonts: Tipografia Inter para melhor legibilidade

## 📁 Estrutura do Projeto

VidaPlus_Gabriel/
├── index.html              # Página principal do sistema
├── login.html              # Sistema de autenticação
├── painel-admin.html       # Painel do administrador
├── painel-profissional.html # Painel do profissional de saúde
├── painel-paciente.html    # Painel do paciente
├── css/
│   └── base.css           # Estilos base do sistema
└── README.md              # Este arquivo
## 🎨 Design e Interface

### Características do Design
- Interface Moderna: Design limpo e profissional
- Responsivo: Adaptável a diferentes tamanhos de tela
- Acessível: Navegação intuitiva e compatível com leitores de tela
- Performance: Carregamento otimizado e animações suaves

### Paleta de Cores
- Primária: #1976d2 (Azul)
- Secundária: #43a047 (Verde)
- Fundo: #f5f7fa (Cinza claro)
- Texto: #222 (Cinza escuro)

## 🔧 Como Usar

### 1. Acesso ao Sistema
1. Abra o arquivo index.html em seu navegador
2. Clique em "Acessar Sistema" para ir à tela de login

### 2. Login
1. Selecione seu perfil (Administrador, Profissional ou Paciente)
2. Digite suas credenciais
3. Clique em "Entrar"

### 3. Navegação
- Use o menu lateral para navegar entre as funcionalidades
- O painel principal exibe informações relevantes ao seu perfil
- Use os botões de ação rápida para tarefas comuns

## 📱 Compatibilidade

- Navegadores: Chrome, Firefox, Safari, Edge (versões recentes)
- Dispositivos: Desktop, Tablet, Mobile
- Sistemas: Windows, macOS, Linux

## 🛠️ Desenvolvimento

### Pré-requisitos
- Navegador web moderno
- Editor de código (VS Code, Sublime Text, etc.)

### Executando Localmente
1. Clone ou baixe o projeto
2. Abra o arquivo index.html em seu navegador
3. O sistema estará pronto para uso

### Estrutura de Desenvolvimento
- HTML: Estrutura semântica e acessível
- CSS: Organizado com variáveis CSS para fácil manutenção
- JavaScript: Código modular e bem documentado

## 🔒 Segurança

### Funcionalidades de Segurança
- Validação de formulários no cliente
- Controle de acesso baseado em perfil
- Sessões seguras
- Proteção contra ataques XSS básicos

### Boas Práticas
- Validação de entrada de dados
- Sanitização de conteúdo
- Controle de permissões por perfil

## 📊 Funcionalidades Avançadas

### Dashboard Administrativo
- Estatísticas em tempo real
- Gráficos de performance
- Relatórios exportáveis
- Monitoramento de sistema
