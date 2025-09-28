# **Tutorial Front-End: Desenvolvimento com Engenharia de Software**

## **FASE 1: FUNDAMENTOS FRONT-END**

### **Etapa 1: Planejamento e Documentação**

**1. Criação do PRD (Product Requirements Document)**
**Prompt:**

```
Crie um documento PRD para o desenvolvimento de um front-end que deve permitir que o usuário salve seu nome e email localmente. Inclua:
- Objetivos do produto
- Público-alvo
- Requisitos funcionais
- Requisitos não-funcionais
- Critérios de aceitação
- Escopo e limitações
```

**2. Criação do TechSpec (Technical Specification)**
**Prompt:**

```
Crie um documento TechSpec para o desenvolvimento de um front-end com as seguintes especificações:
- Stack: HTML5, CSS3, JavaScript vanilla
- Banco de dados local: LocalStorage
- Framework UI/UX: Bootstrap 5 para melhorar aparência e experiência
- Responsividade: Layout adaptável para desktop, tablet e mobile
- Feedback visual: Mensagem de confirmação após salvar dados
- Arquitetura de componentes
- Estrutura de arquivos do projeto
```

### **Etapa 2: Setup e Configuração**

**3. Configuração do Ambiente**
**Prompt:**

```
Configure o ambiente de desenvolvimento front-end incluindo:
- Estrutura de pastas do projeto
- Servidor local para desenvolvimento
- Configuração de ferramentas de desenvolvimento
- Setup do controle de versão (Git)
```

**4. Configuração Base (Documento HTML básico)**
**Prompt:**

```
Crie a estrutura HTML5 básica com:
- DOCTYPE e meta tags essenciais
- Links para Bootstrap CDN
- Estrutura semântica (header, main, footer)
- Preparação para scripts JavaScript
```

### **Etapa 3: Implementação por Componentes**

**5. Documento do backlog do produto**

```
Crie o backlog do produto.
Liste as tarefas. Cada tarefa deve ter:
- Descrição
- Requisitos Funcionais
- Comportamentos Esperados
- Diretrizes Técnicas
- Critérios de Aceitação
```

**6. Implementação Task #1: Componente Header e Título**
**Prompt:**

```
Implemente o componente header com:
- Título "Minha Primeira API"
- Subtítulo explicativo
- Meta tags para responsividade
- CSS básico para estilização inicial
- Estrutura semântica adequada
```

**7. Implementação Task #2: Componente Formulário (Input e Button)**
**Prompt:**

```
Crie um formulário responsivo com:
- Input para "nome de usuário" com validação
- Input para "email" com validação HTML5
- Botão de envio estilizado
- Classes Bootstrap para layout responsivo
- Atributos de acessibilidade (aria-labels, etc.)
```

**8. Implementação Task #3: Funcionalidade LocalStorage**
**Prompt:**

```
Adicione JavaScript para:
- Capturar dados do formulário
- Validar campos obrigatórios
- Salvar dados no localStorage
- Exibir mensagem de confirmação
- Tratamento de erros básico
```

### **Etapa 4: Qualidade e Validação**

**9. Refatoração e Otimização**
**Prompt:**

```
Refatore o código para melhorar:
- Separação de responsabilidades
- Modularização do JavaScript
- Otimização de CSS
- Melhoria da estrutura de arquivos
- Implementação de design patterns apropriados
```

**10. Code Review**
**Prompt:**

```
Faça uma revisão completa do código verificando:
- Boas práticas de HTML semântico
- Organização e legibilidade do CSS
- Qualidade e eficiência do JavaScript
- Conformidade com padrões web
- Otimizações de performance
- Comentários e documentação do código
Crie o documento:
Resumo
[Breve descrição da mudança]
Tarefa Relacionada:
PRs Relacionados
[Link para PRs relacionados]
Tipo de Mudança:
Nova funcionalidade
Correção de bug
Refatoração
Documentação
Estilo (formatação, identação, etc.)
Outro: ___
O que foi feito:
[Descrever de forma objetiva o que foi implementado ou corrigido]
Como Testar:
[Passos resumidos para validar a mudança]
Notas Adicionais
```

**11. Documentação dos Testes**
**Prompt:**

```
Crie o documento de cenários de testes:
Nome da funcionalidade:
Crie testes para validar:
Cenário de Teste XX – [Título do cenário]
Objetivo:
[Descreva o objetivo do teste]
Pré-condições:
[Liste as pré-condições necessárias]
Passos:
[Passo 1]
[Passo 2]
[Passo 3]
Resultado Esperado:
[Descreva o resultado esperado]
Evidência:
[Informe a evidência de validação, ex.: captura de tela]
```

**12. Implementação de Testes**
**Prompt:**

```
Crie testes para validar:
- Funcionamento do formulário
- Salvamento no localStorage
- Validação de campos
- Responsividade em diferentes dispositivos
- Casos de erro e exceções
- Acessibilidade básica
```

### **Etapa 5: Deploy e Monitoramento**

**13. Preparação para Deploy**
**Prompt:**

```
Prepare o projeto para deploy:
- Minificação de CSS e JavaScript
- Otimização de imagens
- Configuração de meta tags para SEO
- Validação de compatibilidade entre navegadores
- Criação de build de produção
```

**14. Deploy**
**Prompt:**

```
Configure o deploy da aplicação:
- Hospedagem em GitHub Pages ou Netlify
- Configuração de domínio personalizado (opcional)
- Setup de SSL/HTTPS
- Configuração de redirecionamentos
- Teste da aplicação em produção
```

**15. Monitoramento e Analytics**
**Prompt:**

```
Implemente ferramentas de monitoramento:
- Google Analytics para métricas de uso
- Console de erros do navegador
- Monitoramento de performance (Core Web Vitals)
- Feedback de usuários
- Logs de erros JavaScript
- Testes de usabilidade
```

---

## **FASE 2: FUNCIONALIDADES AVANÇADAS**

### **Etapa 6: Melhorias de UX/UI**

**14. Implementação de Loading States**
**Prompt:**

```
Adicione estados de carregamento:
- Spinner durante salvamento
- Desabilitação do botão durante processo
- Feedback visual de progresso
- Animações CSS suaves
```

**15. Validação Avançada**
**Prompt:**

```
Implemente validação em tempo real:
- Validação conforme o usuário digita
- Mensagens de erro específicas
- Indicadores visuais de campo válido/inválido
- Prevenção de spam/dados inválidos
```

**16. Gestão de Estado Local**
**Prompt:**

```
Melhore o gerenciamento de estado:
- Estrutura organizada para localStorage
- Versionamento de dados salvos
- Limpeza automática de dados antigos
- Backup e restauração de dados
```

### **Etapa 7: Performance e Acessibilidade**

**17. Otimização de Performance**
**Prompt:**

```
Otimize a performance da aplicação:
- Lazy loading de recursos
- Debounce em eventos de input
- Otimização de reflows/repaints
- Minificação adicional de assets
```

**18. Acessibilidade (a11y)**
**Prompt:**

```
Melhore a acessibilidade:
- Navegação por teclado
- Screen reader compatibility
- Contraste adequado de cores
- ARIA labels e landmarks
- Testes com ferramentas de acessibilidade
```

### **Etapa 8: Testes Avançados**

**19. Testes Automatizados**
**Prompt:**

```
Configure testes automatizados:
- Testes unitários com Jest
- Testes de integração
- Testes de regressão visual
- Automação com GitHub Actions
```

**20. Documentação Final**
**Prompt:**

```
Crie documentação completa:
- README.md detalhado
- Guia de instalação e uso
- Documentação da arquitetura
- Changelog de versões
- Guia de contribuição
```

---

## **Conceitos de Engenharia de Software Aplicados:**

-   **Documentação Técnica:** PRD e TechSpec
-   **Metodologia Ágil:** Desenvolvimento por tasks/sprints
-   **Clean Code:** Código limpo e bem documentado
-   **Testing:** Testes manuais e automatizados
-   **Code Review:** Revisão sistemática de código
-   **CI/CD:** Deploy contínuo e integração
-   **Monitoring:** Observabilidade e métricas
-   **Performance:** Otimização e boas práticas
-   **Accessibility:** Inclusão e usabilidade universal
-   **Documentation:** Documentação técnica completa
