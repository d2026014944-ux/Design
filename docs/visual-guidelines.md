# 🎨 Guia de Diretrizes Visuais do Portfólio

> Manter consistência visual em todo o portfólio transmite profissionalismo e cria uma identidade de marca pessoal forte. Este guia define os padrões que devem ser seguidos em todos os projetos.

---

## 🖼 Thumbnails & Capas de Projeto

### Por que padronizar as capas?

Miniaturas padronizadas fazem com que seu portfólio pareça uma coleção coesa, não uma miscelânea de projetos. Quando compartilhado em redes sociais, o link se destaca com uma imagem de preview atrativa.

### Especificações de Capa (Social Preview)

| Plataforma | Dimensão recomendada | Formato |
|---|---|---|
| **GitHub Social Preview** | 1280 × 640 px | PNG ou JPG |
| **Behance Cover** | 1400 × 600 px | PNG ou JPG |
| **LinkedIn Post** | 1200 × 627 px | PNG ou JPG |
| **Notion Cover** | 1500 × 600 px | PNG ou JPG |

### Elementos obrigatórios na capa

- [ ] Nome do projeto em destaque
- [ ] Categoria (UI/UX · Branding · Visual Design)
- [ ] Uma imagem ou mockup representativo do projeto
- [ ] Cor de fundo da paleta definida por categoria (ver abaixo)
- [ ] Seu nome ou logo pessoal (opcional, mas recomendado)

### Código de Cores por Categoria

```
UI/UX Design    → #6366F1 (Indigo)   + #EEF2FF (fundo claro)
Branding        → #F59E0B (Âmbar)    + #FFFBEB (fundo claro)
Visual Design   → #10B981 (Esmeralda)+ #ECFDF5 (fundo claro)
```

### Tipografia das Capas

- **Título do projeto:** Sans-serif bold, mínimo 48px
- **Subtítulo/categoria:** Sans-serif regular, 24–32px
- **Fontes recomendadas:** Inter, Plus Jakarta Sans, Satoshi

---

## 🗂 Padrão de Imagens nos Projetos

### Mockups

- Use mockups de dispositivos realistas (Figma Community, Mockup World)
- Prefira mockups com sombra suave e fundo neutro (branco, cinza claro ou cor da paleta do projeto)
- Resolução mínima: **1920 × 1080px** para imagens principais
- Formato: **PNG** para transparência, **JPG** para fotografias

### Screenshots de Interface

- Sempre capture em escala 1x ou 2x (@2x para Retina)
- Use bordas arredondadas quando necessário (border-radius visual)
- Inclua sombra sutil para destacar o elemento da tela

### Imagens de Processo

- Fotos de quadros brancos, post-its: podem ser informais, mas devem ser legíveis
- Fluxogramas: exporte em alta resolução ou inclua como SVG
- Wireframes: capture com fundo branco e boa legibilidade

---

## 📐 Grid e Layout dos READMEs

### Hierarquia visual nos documentos

```
H1 (#)     → Título do projeto (apenas 1 por documento)
H2 (##)    → Seções principais (Contexto, Problema, Solução...)
H3 (###)   → Subseções dentro de cada parte
H4 (####)  → Detalhes específicos (use com moderação)
```

### Uso de emojis

Use emojis como marcadores visuais de seção para facilitar a leitura rápida:

| Emoji | Uso recomendado |
|---|---|
| 📌 | Contexto e informações fixas |
| 🔍 | Pesquisa e descoberta |
| 💡 | Ideação e insights |
| 🎨 | Solução e design |
| 📊 | Resultados e métricas |
| 📦 | Entregáveis |
| 📬 | Contato e CTA |
| ⚠️ | Avisos e restrições |
| ✅ | Conquistas e checklists |

### Tabelas

Use tabelas para:
- Comparações antes/depois
- Design systems (cores, tipografia, espaçamento)
- Objetivos vs. métricas
- Ferramentas utilizadas

---

## 🏷 Badges e Labels

Use badges do [shields.io](https://shields.io) para informações rápidas:

```markdown
<!-- Ferramenta -->
![Figma](https://img.shields.io/badge/Figma-Design-F24E1E?style=flat-square&logo=figma&logoColor=white)

<!-- Status do projeto -->
![Status](https://img.shields.io/badge/Status-Concluído-10B981?style=flat-square)
![Status](https://img.shields.io/badge/Status-Em_Andamento-F59E0B?style=flat-square)

<!-- Categoria -->
![Categoria](https://img.shields.io/badge/Categoria-UI%2FUX-6366F1?style=flat-square)
```

---

## 📂 Nomenclatura de Arquivos

### Padrão de nome de arquivo

```
kebab-case sempre: palavras-separadas-por-hifens
sem espaços, sem acentos, sem caracteres especiais

Exemplos:
  ✅ user-flow-v2.png
  ✅ design-system-colors.png
  ✅ wireframe-home-mobile.png
  ❌ Fluxo do Usuário (2).png
  ❌ tela final FINAL v3_REAL.fig
```

### Convenção de versões

```
[nome]-v1.fig      → Primeira versão
[nome]-v2.fig      → Segunda iteração
[nome]-final.fig   → Versão entregue ao cliente
```

---

## 🌐 GitHub Repository Settings

### Como configurar o Social Preview no GitHub

1. Vá em **Settings** do repositório
2. Role até **Social preview**
3. Clique em **Edit**
4. Faça upload da imagem de capa (1280 × 640px)

Isso faz com que o link do repositório exiba uma imagem atrativa quando compartilhado no LinkedIn, WhatsApp, Twitter, etc.

### README com imagem de capa

Inclua sempre uma imagem de capa no topo do README principal:

```markdown
<div align="center">
  <img src="assets/images/cover.png" alt="Capa do Projeto" width="100%" />
</div>
```
