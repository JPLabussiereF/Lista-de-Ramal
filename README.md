# 📞 Lista de Ramais Corporativa

Sistema web responsivo para consulta e gerenciamento de ramais internos das empresas. Interface moderna e intuitiva para facilitar a comunicação interna.

## ✨ Funcionalidades

- 🔍 **Busca em Tempo Real** - Pesquise por nome, setor ou número do ramal
- 🔄 **Ordenação Inteligente** - Ordene por nome (alfabética), setor ou ramal (numérica)
- 📄 **Paginação** - Visualização otimizada com 20 registros por página
- 📱 **Design Responsivo** - Funciona perfeitamente em desktop, tablet e mobile
- 🎨 **Interface Moderna** - Design limpo e profissional
- ⚡ **Performance** - Carregamento rápido sem dependências externas

## 🚀 Demo

### Funcionalidades Principais
- **Pesquisa Instantânea**: Digite qualquer termo para filtrar instantaneamente
- **Ordenação por Clique**: Clique nos cabeçalhos da tabela para ordenar
- **Navegação por Páginas**: Sistema de paginação com indicadores visuais
- **Responsividade Total**: Interface adaptada para todos os dispositivos

## 🛠️ Tecnologias Utilizadas

- **HTML5** - Estrutura semântica
- **CSS3** - Estilização avançada com variáveis CSS e Flexbox
- **JavaScript ES6** - Lógica de interação e manipulação do DOM
- **Design System** - Paleta de cores consistente e componentes reutilizáveis

## 📋 Como Usar

### 1. Clone o repositório
```bash
git clone https://github.com/seu-usuario/lista-ramais.git
cd lista-ramais
```

### 2. Abra o arquivo
```bash
# Simplesmente abra o arquivo index.html no seu navegador
open index.html
```

### 3. Personalize os dados
Edite o array `ramaisData` no JavaScript para incluir os dados da sua empresa:

```javascript
const ramaisData = [
    { nome: "João Silva", setor: "TI", ramal: "1001" },
    { nome: "Maria Santos", setor: "RH", ramal: "1002" },
    // Adicione seus dados aqui...
];
```

### 4. Customize a logo
Substitua a URL da imagem no HTML:

```html
<img src="/assets/logo.png" alt="Logo da Empresa" class="logo-image">
```

## 🎨 Customização

### Cores e Tema
As cores podem ser facilmente alteradas através das variáveis CSS no início do arquivo:

```css
:root {
    --azul-royal: #0033A0;
    --azul-claro: #3366CC;
    --azul-escuro: #001F5B;
    /* Personalize suas cores aqui */
}
```

### Itens por Página
Para alterar a quantidade de registros por página, modifique a constante:

```javascript
const itemsPerPage = 20; // Altere para o número desejado
```

## 📱 Responsividade

O sistema é totalmente responsivo e se adapta a diferentes tamanhos de tela:

- **Desktop**: Visualização completa com todas as funcionalidades
- **Tablet**: Layout adaptado mantendo usabilidade
- **Mobile**: Interface otimizada para touch com navegação simplificada

## 🔧 Estrutura do Projeto

```
lista-ramais/
│
├── index.html        # Arquivo principal
├── README.md         # Documentação
└── assets/           # (opcional)
    ├── logo.png      # Logo da empresa
    └── icon.png      # Icon da empresa
```

## 🌟 Características Técnicas

- **Zero Dependências**: Não requer bibliotecas externas
- **SEO Friendly**: Estrutura HTML semântica
- **Acessibilidade**: Navegação por teclado e screen readers
- **Performance**: Carregamento otimizado
- **Cross-browser**: Compatível com navegadores modernos

## 📈 Futuras Melhorias

- [x] Exportação para PDF/Excel
- [ ] Importação de Ramais
- [ ] Integração com APIs corporativas
- [ ] Modo escuro/claro
- [ ] Favoritos pessoais

## 🤝 Contribuindo

1. Faça um **fork** deste repositório.
2. Crie uma **branch** para a sua funcionalidade:
   `git checkout -b feature/NomeDaFuncionalidade`
3. Realize o **commit** das suas alterações:
   `git commit -m 'Adiciona NomeDaFuncionalidade'`
4. Envie as alterações para o seu repositório remoto:
   `git push origin feature/NomeDaFuncionalidade`
5. Abra um **Pull Request** e descreva detalhadamente as modificações realizadas.

## 👨‍💻 Autor

Desenvolvido com 💜 por [João Pedro Labussiere](https://www.linkedin.com/in/joaolabussiere/) para facilitar a comunicação interna corporativa.

---

⭐ Se este projeto foi útil para você, considere dar uma estrela no repositório!