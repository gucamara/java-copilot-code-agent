# Guia de Templates de Issues para Professores

Este diretório contém templates de issues do GitHub projetados para facilitar que professores solicitem mudanças e melhorias no Sistema de Gestão Escolar da Mergington High School.

## 📋 Templates Disponíveis

### 1. 🎓 Adicionar Nova Atividade
**Arquivo:** `01-add-new-activity.yml`

Use este template quando precisar adicionar uma nova atividade extracurricular ao sistema.

**Informações necessárias:**
- Nome da atividade
- Descrição completa
- Categoria (Esportes, Artes, Acadêmico, etc.)
- Dias da semana
- Horário de início e término
- Capacidade máxima de participantes
- Participantes iniciais (opcional)

### 2. ✏️ Modificar Atividade Existente
**Arquivo:** `02-modify-activity.yml`

Use este template quando precisar alterar informações de uma atividade já cadastrada.

**Informações necessárias:**
- Nome da atividade a modificar
- Campos que deseja alterar (nome, descrição, horário, etc.)
- Novos valores para cada campo
- Motivo da mudança

### 3. 👥 Gerenciar Inscrições de Estudantes
**Arquivo:** `03-manage-enrollments.yml`

Use este template quando precisar adicionar ou remover estudantes de atividades.

**Informações necessárias:**
- Nome da atividade
- Ação desejada (adicionar, remover ou ambos)
- Lista de emails dos estudantes
- Motivo das mudanças

### 4. 🐛 Reportar Bug ou Problema
**Arquivo:** `04-bug-report.yml`

Use este template quando encontrar um problema ou comportamento inesperado no sistema.

**Informações necessárias:**
- Área do sistema afetada
- Descrição clara do problema
- Passos para reproduzir
- Comportamento esperado vs. atual
- Gravidade e frequência do problema

### 5. 🔐 Gerenciar Contas de Professores
**Arquivo:** `05-manage-teachers.yml`

Use este template quando precisar adicionar, modificar ou remover contas de professores.

**Informações necessárias:**
- Ação desejada (adicionar, modificar, remover, resetar senha)
- Username do professor
- Nome completo e email
- Função/permissão (TEACHER ou ADMIN)
- Senha inicial (apenas para novos professores)

### 6. ✨ Solicitar Nova Funcionalidade
**Arquivo:** `06-feature-request.yml`

Use este template quando tiver uma ideia para uma nova funcionalidade ou melhoria significativa.

**Informações necessárias:**
- Área da funcionalidade
- Descrição detalhada
- Problema que resolve
- Solução proposta
- Critérios de aceitação

### 7. 🎨 Melhorias na Interface
**Arquivo:** `07-ui-improvements.yml`

Use este template para sugerir melhorias visuais ou de usabilidade na interface web.

**Informações necessárias:**
- Tipo de melhoria (visual, usabilidade, acessibilidade, etc.)
- Página ou seção afetada
- Estado atual e melhoria proposta
- Benefícios esperados

### 8. 📊 Problemas com Dados ou Relatórios
**Arquivo:** `08-data-issues.yml`

Use este template quando encontrar dados incorretos ou inconsistentes no sistema.

**Informações necessárias:**
- Tipo de dado afetado
- Dados incorretos atuais
- Dados corretos esperados
- Onde os dados estão incorretos
- Impacto do problema

## 🚀 Como Usar os Templates

1. **Acesse a página de Issues do repositório:**
   - Vá para: https://github.com/gucamara/java-copilot-code-agent/issues

2. **Clique em "New Issue":**
   - Você verá todos os templates disponíveis

3. **Escolha o template apropriado:**
   - Selecione o template que melhor se adequa à sua necessidade

4. **Preencha todos os campos obrigatórios:**
   - Os campos marcados como obrigatórios devem ser preenchidos
   - Forneça o máximo de detalhes possível

5. **Revise e envie:**
   - Revise as informações fornecidas
   - Clique em "Submit new issue"

6. **Agente Copilot será automaticamente atribuído:**
   - O agente de codificação será designado para resolver a issue
   - Você pode acompanhar o progresso através de comentários

## ✅ Dicas para Issues Eficazes

### Seja Específico
- Forneça detalhes completos e precisos
- Use exemplos concretos quando possível
- Mencione nomes exatos de atividades, emails, etc.

### Seja Claro
- Descreva o problema ou necessidade claramente
- Explique o que você espera que aconteça
- Use linguagem simples e direta

### Forneça Contexto
- Explique por que a mudança é necessária
- Mencione quem será beneficiado
- Descreva o impacto esperado

### Seja Completo
- Preencha todos os campos obrigatórios
- Forneça informações adicionais quando disponível
- Anexe screenshots ou exemplos se relevante

## 🎯 Critérios de Aceitação

Cada template inclui critérios de aceitação claros que definem quando a tarefa está completa. Estes critérios ajudam a garantir que:

- ✅ A solicitação seja completamente atendida
- ✅ A qualidade do código seja mantida
- ✅ Não haja quebra de funcionalidades existentes
- ✅ A mudança seja testada adequadamente

## 🔧 Informações Técnicas para o Agente

Cada template inclui uma seção técnica detalhada para o agente de codificação Copilot, contendo:

- Arquivos específicos a modificar
- Padrões de código a seguir
- Validações necessárias
- Exemplos de implementação
- Princípios arquiteturais do projeto

Isso garante que o agente tenha todas as informações necessárias para implementar a solicitação sem precisar de esclarecimentos adicionais.

## 📚 Recursos Adicionais

- **Documentação do Sistema:** [docs/README.md](../../docs/README.md)
- **Instruções do Copilot:** [.github/copilot-instructions.md](../copilot-instructions.md)
- **Código Fonte:** [src/](../../src/)

## 💡 Precisa de Ajuda?

Se você não tem certeza de qual template usar ou precisa de assistência:

1. Consulte a [documentação do sistema](../../docs/README.md)
2. Escolha o template que parecer mais próximo da sua necessidade
3. Preencha o máximo de informações que puder
4. O agente Copilot pode pedir esclarecimentos se necessário

## 🔄 Atualizações e Melhorias

Estes templates são vivos e podem ser melhorados. Se você tiver sugestões para melhorar os templates:

- Use o template "Solicitar Nova Funcionalidade" para propor melhorias
- Descreva como o template poderia ser mais útil
- Sugira campos adicionais ou mudanças na estrutura
