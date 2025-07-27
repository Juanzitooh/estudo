## Regras da Pasta Wiki

1. **Sempre use extensão .md**: Todos os arquivos criados na pasta wiki devem ter extensão `.md` (Markdown).
2. **Use frontmatter obrigatório**: Todo arquivo deve ter frontmatter com tags, status e aliases seguindo o padrão estabelecido.
3. **Siga formatação Obsidian**: Utilize callouts, wikilinks, separadores e emojis como nos arquivos existentes.
4. **Mantenha estrutura hierárquica**: Use índices com wikilinks, seções bem definidas e separadores `---`.
5. **Inclua referências bíblicas**: Quando relevante, cite passagens das Escrituras usando os arquivos em `biblias/`.
6. **Mantenha contexto bíblico**: Considere o contexto bíblico apropriado em toda documentação.
7. **Proteção da pasta .obsidian**: A pasta `.obsidian/` contém configurações do programa Obsidian e **NÃO deve ser modificada** sem autorização prévia explícita.

---

## ⚠️ Proteção de Arquivos

### 📁 Pasta .obsidian
- **Localização**: `wiki/.obsidian/`
- **Propósito**: Configurações e funcionamento do programa Obsidian
- **Regra**: **NUNCA modifique** arquivos nesta pasta sem autorização prévia
- **Conteúdo**: Snippets, templates, configurações de plugins, etc.
- **Exceção**: Apenas com autorização explícita do usuário

### 📄 Arquivos Permitidos
- **Arquivos .md** na pasta `wiki/` (exceto `.obsidian/`)
- **Novos documentos** seguindo as diretrizes estabelecidas
- **Modificações** em arquivos .md existentes (seguindo padrões)
- **Referências bíblicas** usando arquivos em `biblias/`

---

## 📋 Estrutura Obrigatória

### Frontmatter Padrão
```yaml
---
tags: [biblical, study, category, tipo, status]
status: completed/draft/in-progress
aliases: [Nome Alternativo, Alias 1, Alias 2]
bible-versions: [KJV, TR, Vulgate] # Quando aplicável
---
```

### Estrutura de Conteúdo
```markdown
# Título do Documento

> [!info] Descrição breve do documento

## 📋 Índice
- [[#Seção 1]]
- [[#Seção 2]]

---

## Seção 1

Conteúdo aqui...

> [!bible] Referência Bíblica (quando aplicável)
> Citação da passagem bíblica

---

## Seção 2

Conteúdo aqui...

---

> [!success] Consulte também:
> - [[Documento Relacionado 1]]
> - [[Documento Relacionado 2]]
```

---

## 🎨 Elementos de Formatação Obrigatórios

### Callouts
- `> [!info]` - Informações gerais
- `> [!tip]` - Dicas e sugestões
- `> [!warning]` - Avisos importantes
- `> [!success]` - Conclusões positivas
- `> [!note]` - Notas adicionais
- `> [!example]` - Exemplos práticos
- `> [!bible]` - Citações bíblicas diretas
- `> [!study]` - Estudos bíblicos e análises
- `> [!context]` - Contexto histórico e cultural

### Wikilinks
- `[[#Seção]]` - Links internos
- `[[Documento]]` - Links para outros documentos
- `[[Documento#Seção]]` - Links para seções específicas

### Separadores
- `---` - Separadores entre seções principais

### Emojis
- Use emojis para categorizar seções (📋, 🎯, 🔧, 📖, etc.)

---

## 📝 Checklist para Novos Arquivos

- [ ] Extensão `.md`
- [ ] Frontmatter com tags, status e aliases
- [ ] Título principal com `#`
- [ ] Callout informativo no início
- [ ] Índice com wikilinks
- [ ] Separadores `---` entre seções
- [ ] Emojis para categorização
- [ ] Callout de referências no final
- [ ] Linguagem clara e objetiva
- [ ] Referências bíblicas quando apropriado
- [ ] Contexto bíblico mantido
- [ ] **NÃO modificar pasta `.obsidian/`** sem autorização

---

## 📖 **Regras Específicas para Documentos Bíblicos**

1. **Citações precisas**: Sempre cite exatamente como aparece nos arquivos JSON em `biblias/`.
2. **Especificar fonte**: Indique qual versão bíblica está sendo usada (KJV, TR, Vulgate, etc.).
3. **Contexto adequado**: Forneça contexto suficiente para entender a citação bíblica.
4. **Reverência**: Trate todas as referências bíblicas com respeito e reverência.
5. **Interpretação cuidadosa**: Evite interpretações que contradigam o contexto bíblico geral.

### Frontmatter para Documentos Bíblicos
```yaml
---
tags: [biblical, study, old-testament, new-testament, category]
status: completed/draft/in-progress
aliases: [Nome do Documento, Alias 1, Alias 2]
bible-versions: [KJV, TR, Vulgate]
---
``` 