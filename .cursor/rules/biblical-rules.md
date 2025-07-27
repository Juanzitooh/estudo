## Regras para Referência Bíblica e Estudo

### 📖 **Regras de Citação Bíblica**

#### **1. Precisão nas Citações**
- ✅ **SEMPRE** cite exatamente como aparece no arquivo JSON
- ✅ **SEMPRE** especifique qual versão bíblica está sendo usada
- ✅ **SEMPRE** forneça contexto adequado
- ❌ **NUNCA** altere ou modifique o texto bíblico

#### **2. Tradução Obrigatória para Português**
- ✅ **SEMPRE** forneça tradução em português quando citar versículos
- ✅ **SEMPRE** mantenha o texto original em inglês/latim/hebraico
- ✅ **SEMPRE** use formato: "Texto Original (versão) - Tradução em Português"
- ✅ **SEMPRE** verifique se a tradução está correta e fiel ao original
- ❌ **NUNCA** cite apenas em idioma estrangeiro sem tradução

#### **3. Formato de Citação Padrão**
```
> [!bible] **Referência (Versão)**: "Texto Original" - "Tradução em Português"
```

**Exemplo:**
```
> [!bible] **João 3:16 (KJV)**: "For God so loved the world, that he gave his only begotten Son, that whosoever believeth in him should not perish, but have everlasting life." - "Porque Deus amou o mundo de tal maneira que deu o seu Filho unigênito, para que todo aquele que nele crê não pereça, mas tenha a vida eterna."
```

#### **4. Verificação de Tradução**
- ✅ **SEMPRE** confirme que a tradução está alinhada com o texto original
- ✅ **SEMPRE** mantenha o significado teológico correto
- ✅ **SEMPRE** use linguagem clara e acessível em português
- ❌ **NUNCA** use traduções que distorçam o significado original

### 📋 **Arquivos Bíblicos Disponíveis**

| Arquivo | Versão | Idioma Original | Uso Recomendado |
|---------|--------|-----------------|-----------------|
| `KJV.json` | King James Version | Inglês | Citações principais |
| `TR.json` | Textus Receptus | Grego | Estudos textuais |
| `Vulgate.json` | Vulgata | Latim | Estudos históricos |
| `VulgClementine.json` | Vulgata Clementina | Latim | Estudos católicos |
| `WLC.json` | Westminster Leningrad Codex | Hebraico | Estudos do AT |

### 📖 **Regras para Estudo Bíblico**

#### **1. Análise Textual**
- ✅ **SEMPRE** analise o contexto histórico e cultural
- ✅ **SEMPRE** considere o gênero literário do texto
- ✅ **SEMPRE** mantenha a coerência com o restante das Escrituras
- ❌ **NUNCA** interprete de forma que contradiga o contexto bíblico geral

#### **2. Interpretação Cuidadosa**
- ✅ **SEMPRE** trate com reverência e respeito
- ✅ **SEMPRE** reconheça a autoridade divina das Escrituras
- ✅ **SEMPRE** priorize a sabedoria que vem de Deus
- ❌ **NUNCA** faça interpretações que contradigam a revelação central

### ⚠️ **Restrições Importantes**

- ❌ **NUNCA** modifique arquivos em `biblias/`
- ❌ **NUNCA** adicione comentários aos arquivos bíblicos
- ❌ **NUNCA** interprete de forma que contradiga o contexto bíblico geral
- ❌ **NUNCA** cite versículos sem tradução em português
- ❌ **NUNCA** use traduções que distorçam o significado original

### ✅ **Checklist para Citações Bíblicas**

- [ ] Texto original citado corretamente
- [ ] Versão bíblica especificada
- [ ] Tradução em português fornecida
- [ ] Tradução verificada e fiel ao original
- [ ] Contexto adequado fornecido
- [ ] Formato de citação correto usado
- [ ] Significado teológico preservado

### 📖 **Elementos de Formatação Bíblica**

#### **Callouts Específicos**
- `[!bible]` - Para citações bíblicas diretas
- `[!study]` - Para estudos e análises
- `[!context]` - Para contexto histórico/cultural
- `[!cross-reference]` - Para referências cruzadas

#### **Wikilinks Bíblicos**
- `[[João 3:16]]` - Para referências a versículos
- `[[Evangelho de João]]` - Para referências a livros
- `[[Jesus Cristo]]` - Para referências a personagens

### 📋 **Estrutura para Documentos de Estudo Bíblico**

#### **Frontmatter Obrigatório**
```yaml
---
tags: [biblical, study, revelation, gospel]
type: guide
aliases: [Nomes alternativos]
bible-versions: [KJV, TR, Vulgate, etc.]
status: [primordial, completo, em desenvolvimento]
priority: [maximum, high, medium, low]
---
```

#### **Estrutura de Conteúdo**
1. **Introdução** - Contexto e objetivo
2. **Análise Bíblica** - Estudo dos textos
3. **Cruzamento de Informações** - Conexões entre passagens
4. **Aplicação Prática** - Como aplicar na vida
5. **Conclusão** - Síntese dos achados

> [!warning] **IMPORTANTE**: A pasta `biblias/` contém as Escrituras Sagradas e é a fonte autoritativa. Sempre cite com precisão e forneça tradução em português.

> [!bible] **Versículo Central**: João 3:16 (KJV) - "For God so loved the world, that he gave his only begotten Son, that whosoever believeth in him should not perish, but have everlasting life." - "Porque Deus amou o mundo de tal maneira que deu o seu Filho unigênito, para que todo aquele que nele crê não pereça, mas tenha a vida eterna." 