# Link Bio - Gustavo Zollim

Um site link bio moderno e responsivo inspirado no design fornecido, perfeito para centralizar todos os seus links importantes em uma única página.

## 🎨 Características

- **Design Moderno**: Layout inspirado no estilo fitness/bodybuilding com cores vibrantes
- **Responsivo**: Funciona perfeitamente em dispositivos móveis e desktop
- **Animações Suaves**: Efeitos de hover e animações de entrada
- **Fácil Personalização**: Código limpo e bem organizado

## 📱 Estrutura

### Header
- Foto de perfil circular
- Nome em destaque (GUSTAVO ZOLLIM)
- Ícones das redes sociais (Instagram, YouTube, TikTok)

### Cards de Links
1. **Card Verde**: Fila de Espera do CF (Close Friends)
2. **Card Vermelho**: Canal do YouTube
3. **Card Azul**: Cupom Growth Supplements

## 🛠️ Como Personalizar

### 1. Alterar Foto de Perfil
Substitua a URL no arquivo `index.html`:
```html
<img src="SUA_FOTO_AQUI.jpg" alt="Seu Nome">
```

### 2. Atualizar Links das Redes Sociais
No arquivo `index.html`, altere os links:
```html
<a href="https://instagram.com/seuperfil" class="social-icon instagram" target="_blank">
<a href="https://youtube.com/seucanal" class="social-icon youtube" target="_blank">
<a href="https://tiktok.com/@seuperfil" class="social-icon tiktok" target="_blank">
```

### 3. Personalizar Cards
Para cada card, você pode alterar:
- **Título**: Modifique o texto dentro de `<h3>`
- **Subtítulo**: Altere o conteúdo de `card-subtitle`
- **Link**: Mude o `href` do elemento `<a>`
- **Imagem**: Substitua a URL da imagem

### 4. Alterar Cores
No arquivo `style.css`, você pode modificar:
- **Background geral**: Altere o `linear-gradient` do `body`
- **Cores dos cards**: Modifique os gradientes das classes `.card-green`, `.card-red`, `.card-blue`
- **Cores das redes sociais**: Ajuste as cores dos `.social-icon`

## 🚀 Como Usar

1. **Visualização Local**: Abra o arquivo `index.html` diretamente no navegador
2. **Servidor Local**: Use qualquer servidor HTTP simples
3. **Deploy**: Faça upload dos arquivos para qualquer serviço de hospedagem

## 📁 Arquivos

- `index.html` - Estrutura HTML do site
- `style.css` - Estilos e animações
- `README.md` - Este arquivo de documentação

## 🎯 Dicas de Uso

- Mantenha os títulos dos cards curtos e impactantes
- Use imagens de alta qualidade para melhor aparência
- Teste sempre em dispositivos móveis
- Considere adicionar Google Analytics para acompanhar cliques

## 🔧 Tecnologias Utilizadas

- HTML5
- CSS3 (Flexbox, Grid, Animations)
- Font Awesome (Ícones)
- Design Responsivo

---

