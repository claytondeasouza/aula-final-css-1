# SEOCamp 2026 - Site Educacional em HTML e CSS Puro

Um site completo desenvolvido com **HTML semântico** e **CSS responsivo puro**, sem frameworks. Perfeito para ensinar web design prático em sala de aula!

## 📋 Estrutura do Projeto

```
seocamp-html-css/
├── index.html          # Estrutura HTML semântica completa
├── style.css           # CSS responsivo com media queries
└── README.md           # Este arquivo
```

## 🎯 Características Principais

### HTML Semântico
- Uso correto de tags semânticas: `<header>`, `<nav>`, `<section>`, `<article>`, `<footer>`
- Estrutura limpa e bem organizada
- Sem divs desnecessárias
- Acessibilidade em mente

### CSS Responsivo
- **Desktop**: Layout em colunas amplas (1024px+)
- **Tablet**: Ajuste de espaçamento e fontes (768px - 1024px)
- **Mobile**: Layout empilhado verticalmente (<768px)
- Media queries bem documentadas
- Variáveis CSS para fácil customização

### Design Moderno
- Tema dark mode com gradientes orange/amber
- Animações suaves e transições
- Efeitos hover interativos
- Tipografia profissional (Poppins + Inter do Google Fonts)

## 🚀 Como Usar

### 1. Abrir Localmente
```bash
# Opção 1: Usar Python (qualquer versão)
python -m http.server 8000

# Opção 2: Usar Node.js (se tiver instalado)
npx http-server

# Opção 3: Abrir diretamente no navegador
# Clique duplo em index.html
```

### 2. Acessar no Navegador
- Abra `http://localhost:8000` (ou a porta que escolheu)
- Ou abra o arquivo `index.html` diretamente

### 3. Testar Responsividade
- **Desktop**: Veja o site em tela cheia
- **Tablet**: Redimensione a janela para ~768px
- **Mobile**: Redimensione para ~480px ou use o DevTools (F12 → Toggle device toolbar)

## 📚 Conteúdo das Seções

### 1. Header (Cabeçalho)
- Logo com gradiente
- Navegação com links âncora
- Botão de CTA "Participar"
- Responsivo com menu colapsável

### 2. Hero Section
- Imagem de fundo com overlay
- Título impactante com gradiente
- Badges e estatísticas
- Botões de ação
- Indicador de scroll

### 3. CSS Responsivo
- Explicação de Flexbox
- Explicação de Media Queries
- Explicação de Mobile-First
- Visualização de estratégia com demos

### 4. Carreiras Digitais
- Cards para SEO, GEO e CRO
- Informações de salários
- Competências necessárias
- Conexão com Web Design

### 5. Evento
- Informações do SEOCamp 2026
- Cronograma das aulas
- Highlights e benefícios
- CTA para inscrição

### 6. Footer
- Links de navegação
- Redes sociais
- Informações legais

## 🎓 Usando na Aula

### Demonstração Prática
1. **Abra o DevTools** (F12)
2. **Ative o modo responsivo** (Ctrl+Shift+M)
3. **Redimensione a janela** e mostre como o layout se adapta
4. **Inspecione os elementos** para ver o HTML e CSS
5. **Modifique o CSS** em tempo real para demonstrar conceitos

### Exercícios para Alunos

#### Exercício 1: Modificar Cores
```css
/* Altere as cores no :root */
--accent-orange: #FF6B35;  /* Laranja diferente */
--accent-amber: #FFA500;   /* Âmbar diferente */
```

#### Exercício 2: Adicionar Nova Seção
```html
<section class="nova-secao">
    <div class="container">
        <h2>Minha Nova Seção</h2>
        <!-- Conteúdo aqui -->
    </div>
</section>
```

#### Exercício 3: Criar Novo Card
```html
<article class="concept-card">
    <div class="concept-icon">🎨</div>
    <h3>Meu Conceito</h3>
    <p>Descrição do conceito...</p>
</article>
```

#### Exercício 4: Media Query Customizada
```css
@media (max-width: 600px) {
    /* Estilos para telas muito pequenas */
    h2 {
        font-size: 1.5rem;
    }
}
```

## 🛠️ Customização

### Mudar Cores
Edite as variáveis CSS no topo do `style.css`:

```css
:root {
    --accent-orange: #EA580C;  /* Cor primária */
    --accent-amber: #F59E0B;   /* Cor secundária */
    --bg-dark: #0F172A;        /* Fundo escuro */
    --text-primary: #F8FAFC;   /* Texto principal */
}
```

### Mudar Tipografia
Altere as fontes do Google Fonts no `index.html`:

```html
<link href="https://fonts.googleapis.com/css2?family=SuaFonte:wght@400;700&display=swap" rel="stylesheet">
```

Depois atualize no CSS:
```css
--font-display: 'SuaFonte', sans-serif;
```

### Adicionar Conteúdo
- Edite as seções diretamente no `index.html`
- Mantenha a estrutura semântica
- Use as classes CSS existentes para manter o estilo

## 📱 Breakpoints Responsivos

O site usa os seguintes breakpoints:

| Dispositivo | Largura | Características |
|-------------|---------|-----------------|
| Mobile | < 480px | Layout vertical, fontes menores |
| Mobile Grande | 480px - 768px | Layout começando a se adaptar |
| Tablet | 768px - 1024px | Duas colunas em alguns lugares |
| Desktop | > 1024px | Layout completo com múltiplas colunas |

## 🎨 Estrutura CSS

O CSS está organizado em seções comentadas:

1. **Reset e Variáveis Globais** - Estilos base
2. **Estilos Globais** - Tipografia, links, etc
3. **Botões** - Todos os estilos de botão
4. **Header** - Cabeçalho e navegação
5. **Hero Section** - Seção principal
6. **Seções Comuns** - Estilos reutilizáveis
7. **Conceitos** - Cards de conceitos
8. **Carreiras** - Cards de carreiras
9. **Evento** - Seção de evento
10. **Footer** - Rodapé
11. **Media Queries** - Responsividade

## ♿ Acessibilidade

O site inclui:
- Contraste adequado de cores
- Semântica HTML correta
- Links com texto descritivo
- Suporte a navegação por teclado
- Respeito a `prefers-reduced-motion`

## 🔍 Validação

Para validar o HTML:
- Acesse [W3C Validator](https://validator.w3.org/)
- Cole o código HTML

Para validar o CSS:
- Acesse [W3C CSS Validator](https://jigsaw.w3.org/css-validator/)
- Cole o código CSS

## 📖 Recursos de Aprendizado

### HTML Semântico
- [MDN: HTML Semântico](https://developer.mozilla.org/pt-BR/docs/Glossary/Semantics)
- [W3C: Elementos Semânticos](https://www.w3.org/TR/html52/sections.html)

### CSS Responsivo
- [MDN: Media Queries](https://developer.mozilla.org/pt-BR/docs/Web/CSS/Media_Queries)
- [MDN: Flexbox](https://developer.mozilla.org/pt-BR/docs/Web/CSS/CSS_Flexible_Box_Layout)
- [MDN: Grid](https://developer.mozilla.org/pt-BR/docs/Web/CSS/CSS_Grid_Layout)

### Design
- [Google Fonts](https://fonts.google.com/)
- [Color Hunt](https://colorhunt.co/)
- [Unsplash](https://unsplash.com/) - Imagens gratuitas

## 💡 Dicas para a Aula

1. **Comece pelo HTML** - Mostre a estrutura semântica
2. **Depois o CSS** - Explique como os estilos são aplicados
3. **Teste no mobile** - Demonstre a responsividade
4. **Modifique em tempo real** - Use DevTools para editar CSS ao vivo
5. **Deixe os alunos experimentar** - Peça para mudarem cores, fontes, etc
6. **Crie desafios** - "Adicione uma nova seção", "Mude o layout"

## 📝 Notas Importantes

- O site usa **Google Fonts** - precisa de internet para carregar as fontes
- A imagem de fundo do hero é de uma URL CDN - precisa de internet
- Sem dependências externas (sem npm, webpack, etc)
- Funciona em qualquer navegador moderno
- Totalmente editável e customizável

## 🤝 Contribuições

Sinta-se livre para:
- Adicionar novas seções
- Melhorar o design
- Corrigir bugs
- Sugerir melhorias

## 📄 Licença

Este projeto é livre para usar em fins educacionais.

---

**Desenvolvido com ❤️ para educação em Web Design**

Perfeito para aulas de CSS Responsivo e HTML Semântico!
