Para usar ícones em HTML puro, você tem algumas opções:

### 1. **Font Awesome**

**Font Awesome** é uma das bibliotecas de ícones mais populares. 

#### Como usar:

1. **Adicione o link para o CSS do Font Awesome no `<head>` do seu HTML:**

   ```html
   <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
   ```

2. **Use os ícones no seu HTML:**

   ```html
   <i class="fas fa-home"></i>
   ```

   Para ver a lista completa de ícones disponíveis e como usá-los, visite a [documentação do Font Awesome](https://fontawesome.com/icons).

### 2. **Material Icons**

**Material Icons** é uma biblioteca de ícones desenvolvida pelo Google.

#### Como usar:

1. **Adicione o link para o CSS dos Material Icons no `<head>` do seu HTML:**

   ```html
   <link rel="stylesheet" href="https://fonts.googleapis.com/icon?family=Material+Icons">
   ```

2. **Use os ícones no seu HTML:**

   ```html
   <i class="material-icons">home</i>
   ```

   Você pode consultar a lista de ícones e seus nomes na [documentação do Material Icons](https://material.io/resources/icons/).

### 3. **Ionicons**

**Ionicons** é uma coleção de ícones projetados para apps móveis e web.

#### Como usar:

1. **Adicione o link para o CSS do Ionicons no `<head>` do seu HTML:**

   ```html
   <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/ionicons/5.5.2/collection/components/ionicons.css">
   ```

2. **Use os ícones no seu HTML:**

   ```html
   <i class="ion ion-md-home"></i>
   ```

   Confira a [documentação do Ionicons](https://ionicons.com/) para ver a lista completa de ícones.

### 4. **SVGs Inline**

Você também pode usar ícones SVG diretamente no HTML.

#### Como usar:

1. **Cole o código SVG diretamente no seu HTML:**

   ```html
   <svg width="24" height="24" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
     <path d="M10 20v-6h4v6h5v-8h3L12 3 2 12h3v8z" fill="currentColor"/>
   </svg>
   ```

   Substitua o código SVG pelo ícone que você deseja usar. Você pode encontrar SVGs em sites como [Heroicons](https://heroicons.com/) ou [Feather Icons](https://feathericons.com/).

Escolha a opção que melhor se adapta às suas necessidades e ao seu projeto!