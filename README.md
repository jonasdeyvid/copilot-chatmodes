# 🤖 Copilot ChatModes Collection

Uma coleção curada de **ChatModes personalizados** para GitHub Copilot, projetados para maximizar a produtividade em tarefas específicas de desenvolvimento.

<div align="center">

![GitHub](https://img.shields.io/badge/GitHub_Copilot-ChatModes-blue?style=for-the-badge&logo=github)
![License](https://img.shields.io/badge/license-MIT-green?style=for-the-badge)
![VS Code](https://img.shields.io/badge/VS_Code-Extension-purple?style=for-the-badge&logo=visualstudiocode)

</div>

## 📋 Índice

- [Sobre](#-sobre)
- [ChatModes Disponíveis](#-chatmodes-disponíveis)
- [Como Usar](#-como-usar)
- [Estrutura do Repositório](#-estrutura-do-repositório)
- [Instalação](#-instalação)
- [Exemplos de Uso](#-exemplos-de-uso)
- [Contribuindo](#-contribuindo)
- [Licença](#-licença)

## 🎯 Sobre

Este repositório contém **ChatModes especializados** para GitHub Copilot que transformam o assistente de IA em especialistas focados em tarefas específicas. Cada ChatMode é cuidadosamente configurado com:

- ✅ **Ferramentas específicas** para o domínio
- ✅ **Instruções detalhadas** e comportamentos otimizados
- ✅ **Melhores práticas** para cada tipo de tarefa
- ✅ **Workflows automatizados** para aumentar produtividade


## 🚀 ChatModes Disponíveis

### 1️⃣ 🎨 ChatMode Generator

**Arquivo:** `.github/chatmodes/chatmode-generator.chatmode.md`

Especialista em criar novos ChatModes personalizados para GitHub Copilot.

**Principais Features:**

- 📋 Análise de requisitos e descoberta
- 🛠️ Seleção inteligente de ferramentas
- 📝 Geração de estrutura completa
- 🎯 Templates por categoria (Dev, Tests, DevOps, Docs)
- ✅ Validação de sintaxe e boas práticas
- 🔄 Iteração e melhoria contínua

**Ideal para:**

- Criar novos ChatModes customizados
- Padronizar estrutura de ChatModes
- Aprender sobre ferramentas disponíveis
- Manter consistência no projeto

**Templates Disponíveis:**

- Development ChatModes
- Test Automation ChatModes
- DevOps/CI-CD ChatModes
- Documentation ChatModes

---

### 2️⃣ 🤖 Robot Framework Test Automator

**Arquivo:** `.github/chatmodes/robot-tester.chatmode.md`

Especialista em criar testes automatizados com Robot Framework e SeleniumLibrary.

**Principais Features:**

- 🔍 Analisa código-fonte antes de criar testes
- 🎯 Cria testes E2E completos e precisos
- 🛠️ Suporta Vue.js, React e outros frameworks
- 📊 Gera locators baseados no código real
- ✨ Segue boas práticas de test automation

**Ideal para:**

- Criar suítes de testes automatizados
- Testes de interface (UI Testing)
- Testes E2E complexos
- Integração contínua

---

### 3️⃣ 📚 Code Documentation Assistant

**Arquivo:** `.github/chatmodes/code-documentation.chatmode.md`

Assistente especializado em documentação técnica com análise arquitetural.

**Principais Features:**

- 🏗️ Análise de arquitetura de alto nível
- 📊 Geração de diagramas Mermaid
- 📝 Documentação de APIs e interfaces
- 🔧 Guias de setup e desenvolvimento
- 📖 READMEs profissionais

**Ideal para:**

- Documentar projetos novos ou existentes
- Criar diagramas de arquitetura
- Guias de contribuição
- Documentação de APIs

**Tipos de Diagramas Suportados:**

- Architecture diagrams
- Sequence diagrams
- Flowcharts
- Class diagrams
- Entity relationships

---

### 4️⃣ 🔒 Security Vulnerability Fixer

**Arquivo:** `.github/chatmodes/fix-vuln-dependabot.chatmode.md`

Especialista em análise e correção de vulnerabilidades do Dependabot.

**Principais Features:**

- 🔍 Análise de vulnerabilidades por severidade
- 🛡️ Estratégias de correção inteligentes
- 📦 Gestão de dependências
- 🔄 Migração segura de pacotes
- 📊 Avaliação de impacto

**Ideal para:**

- Corrigir alertas de segurança
- Atualizar dependências com segurança
- Análise de CVEs
- Refatoração para versões seguras

---

---

## 📖 Como Usar

### Pré-requisitos

- GitHub Copilot instalado no VS Code
- VS Code versão 1.80 ou superior
- Conta do GitHub Copilot ativa

### Método 1: Clone Direto no Workspace

1. **Clone este repositório no seu workspace:**

   ```bash
   git clone https://github.com/jonasdeyvid/copilot-chatmodes.git
   ```

2. **O GitHub Copilot detectará automaticamente** os ChatModes na pasta `.github/chatmodes/`

3. **Acesse no VS Code:**
   - Abra o Copilot Chat (`Ctrl+Shift+I` ou `Cmd+Shift+I`)
   - Clique no ícone de configurações (⚙️)
   - Selecione o ChatMode desejado

### 🖼️ Como Selecionar um ChatMode

No Copilot Chat, clique no ícone de configurações (⚙️) e selecione o ChatMode desejado:

<div align="center">
  <img src="images/chatmode-selection.png" alt="Seleção de ChatMode" width="600">
  <p><em>Clique no ícone ⚙️ no canto superior direito e escolha o ChatMode no dropdown</em></p>
</div>

> 💡 **Dica:** O ChatMode ativo será exibido no topo do chat e você pode alternar entre eles a qualquer momento!

### Método 2: Copiar ChatModes Específicos

1. **Navegue até a pasta do seu projeto:**

   ```bash
   cd seu-projeto
   ```

2. **Crie a estrutura necessária:**

   ```bash
   mkdir -p .github/chatmodes
   ```

3. **Copie o ChatMode desejado:**

   ```bash
   cp copilot-chatmodes/.github/chatmodes/[nome-do-chatmode].chatmode.md .github/chatmodes/
   ```

4. **Recarregue o VS Code** ou reabra a janela do Copilot Chat

## 📁 Estrutura do Repositório

```
copilot-chatmodes/
│
├── .github/
│   └── chatmodes/
│       ├── robot-tester.chatmode.md
│       ├── code-documentation.chatmode.md
│       ├── fix-vuln-dependabot.chatmode.md
│       └── chatmode-generator.chatmode.md
│
├── images/
│   └── chatmode-selection.png
│
└── README.md
```

## 💡 Exemplos de Uso

### Exemplo 1: Criando Testes Automatizados

```plaintext
[No Copilot Chat com Robot Tester ativo]

Você: "Crie testes E2E para o fluxo de login do meu app Vue.js"

AI: [Analisa o código-fonte, identifica elementos e cria testes precisos]
```

### Exemplo 2: Documentando Arquitetura

```plaintext
[No Copilot Chat com Documentation Assistant ativo]

Você: "Analise este repositório e crie documentação completa com diagramas"

AI: [Gera README, diagramas de arquitetura e documentação técnica]
```

### Exemplo 3: Corrigindo Vulnerabilidades

```plaintext
[No Copilot Chat com Security Fixer ativo]

Você: "Analise e corrija as vulnerabilidades do Dependabot"

AI: [Lista vulnerabilidades, avalia impacto e aplica correções]
```

### Exemplo 4: Criando Novos ChatModes

```plaintext
[No Copilot Chat com ChatMode Generator ativo]

Você: "Crie um ChatMode para trabalhar com APIs GraphQL"

AI: [Analisa requisitos, seleciona ferramentas e gera ChatMode completo]
```

## 🛠️ Estrutura de um ChatMode

Cada ChatMode segue esta estrutura:

```markdown
---
description: 'Descrição breve do ChatMode'
tools: ['lista', 'de', 'ferramentas', 'disponíveis']
model: Claude Sonnet 4
---

# Título do ChatMode

## Objetivo
[Descrição detalhada]

## Comportamento do AI
[Instruções específicas para o comportamento]

## Exemplos
[Casos de uso e exemplos]
```

## 🤝 Contribuindo

Contribuições são bem-vindas! Se você tem um ChatMode útil, siga estes passos:

1. **Fork este repositório**
2. **Crie uma branch para sua feature:**

   ```bash
   git checkout -b feature/novo-chatmode
   ```

3. **Adicione seu ChatMode** em `.github/chatmodes/`
4. **Atualize este README** com informações sobre o novo ChatMode
5. **Commit suas mudanças:**

   ```bash
   git commit -m "feat: adiciona chatmode para [funcionalidade]"
   ```

6. **Push para a branch:**

   ```bash
   git push origin feature/novo-chatmode
   ```

7. **Abra um Pull Request**

### Guidelines para Novos ChatModes

- ✅ Use nomes descritivos em kebab-case
- ✅ Inclua descrição clara no frontmatter
- ✅ Documente casos de uso
- ✅ Liste ferramentas necessárias
- ✅ Adicione exemplos práticos

## 📝 Licença

Este projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

## 🌟 Agradecimentos

- **GitHub Copilot Team** - Pela incrível ferramenta
- **Comunidade Open Source** - Por inspiração e feedback
- **Contribuidores** - Por tornar este projeto melhor

---

<div align="center">

**⭐ Se este projeto foi útil, considere dar uma estrela!**

Feito com ❤️ por [Jonas Deyvid](https://github.com/jonasdeyvid)

</div>