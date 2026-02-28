# Projeto E-commerce Educacional

Este projeto foi desenvolvido como parte de um processo de aprendizado prático em desenvolvimento web, com foco na criação de uma loja virtual completa.

## 📚 Objetivo Educacional

Este projeto serve como material de estudo para desenvolvedores que desejam aprimorar suas habilidades em:

- **Desenvolvimento Frontend**: HTML5, CSS3 com SASS, JavaScript ES6+
- **Automação de Build**: Gulp para compilação e otimização de assets
- **Simulação de API**: JSON Server para criar um backend fake
- **Webpack**: Empacotamento de módulos JavaScript
- **Design Responsivo**: Interface adaptável para diferentes dispositivos

## 🛍️ Sobre a Loja

Uma loja virtual de roupas e acessórios com funcionalidades essenciais de e-commerce:

- Catálogo de produtos com imagens, preços e especificações
- Sistema de parcelamento
- Diferentes tamanhos e cores
- Interface moderna e responsiva

## 🚀 Tecnologias Utilizadas

### Frontend
- **HTML5**: Estrutura semântica
- **SASS**: Pré-processador CSS com variáveis e mixins
- **JavaScript ES6+**: Lógica interativa
- **Webpack**: Empacotamento de módulos

### Ferramentas de Desenvolvimento
- **Gulp**: Task runner para automação
- **Babel**: Transpilação de JavaScript
- **Browser Sync**: Sincronização e recarregamento automático
- **JSON Server**: API REST fake para desenvolvimento

### Estrutura do Projeto
```
├── src/
│   ├── index.html      # Página principal
│   ├── scss/          # Arquivos SASS
│   ├── js/            # Módulos JavaScript
│   └── img/           # Imagens dos produtos
├── db.json            # Dados simulados da API
├── gulpfile.js        # Configuração do Gulp
└── webpack.config.js  # Configuração do Webpack
```

## 🛠️ Como Executar o Projeto

### Pré-requisitos
- Node.js instalado
- npm ou yarn

### Instalação
1. Clone o repositório
2. Instale as dependências:
   ```bash
   npm install
   ```

### Execução
1. Inicie o ambiente de desenvolvimento:
   ```bash
   npm start
   ```
   
   Este comando irá:
   - Compilar os arquivos SASS para CSS
   - Empacotar os módulos JavaScript com Webpack
   - Iniciar o servidor de desenvolvimento
   - Abrir o navegador automaticamente

## 📦 Scripts Disponíveis

- `npm start`: Inicia o ambiente de desenvolvimento completo
- `npm run dev`: Executa apenas as tarefas do Gulp
- `npm run server`: Inicia apenas o JSON Server na porta 5000

## 🎯 Aprendizados Esperados

Com este projeto, você irá aprender:

1. **Estrutura de Projeto**: Organização de arquivos e pastas
2. **CSS Avançado**: Uso de SASS para estilos maintaináveis
3. **JavaScript Modular**: Divisão de código em módulos reutilizáveis
4. **Automação**: Configuração de processos de build
5. **API Integration**: Consumo de endpoints REST
6. **Performance**: Otimização de assets e carregamento

## � Bugs Intencionais para Treinamento

Este projeto contém bugs intencionais para ajudar desenvolvedores juniores a praticar suas habilidades de debugging. Encontre e corrija os seguintes problemas:

### Bugs de JavaScript
1. **Contador do Carrinho**: O contador não reseta ao recarregar a página (persistência de estado)
2. **Event Listeners Duplicados**: No arquivo `src/js/index.js`, os event listeners são adicionados múltiplas vezes
3. **Função Não Exportada**: Em `src/js/views/productView.js`, há uma função comentada que deveria ser exportada
4. **Tratamento de Erros**: A função `productRender` lança erro mas não trata casos de API vazia

### Bugs de CSS/Estilo
1. **Responsividade**: Quebra de layout em dispositivos móveis abaixo de 320px
2. **Hover States**: Botões não têm estados de hover definidos
3. **Loading States**: Não há indicadores visuais durante carregamento de produtos
4. **Contraste**: Algumas cores podem não ter contraste suficiente para acessibilidade

### Bugs de Performance
1. **Renderização Ineficiente**: A lista de produtos é recriada completamente a cada filtro
2. **Memory Leaks**: Event listeners não são removidos adequadamente
3. **Imagens Não Otimizadas**: As imagens dos produtos não têm lazy loading

### Bugs de UX/Comportamento
1. **Filtros Não Cumulativos**: Aplicar um filtro sobrescreve os anteriores
2. **Ordenação Inconsistente**: A ordenação por preço não funciona corretamente com valores decimais
3. **Feedback Visual**: Não há feedback quando produtos são adicionados ao carrinho
4. **Validação**: Formulários não têm validação adequada

### 🎯 Desafios Propostos

**Nível Júnior:**
- Corrigir o contador do carrinho para persistir no localStorage
- Implementar estados de hover nos botões
- Adicionar tratamento de erro na função `productRender`

**Nível Intermediário:**
- Otimizar a renderização para evitar recriação completa da lista
- Implementar lazy loading nas imagens
- Corrigir os event listeners duplicados

**Nível Avançado:**
- Implementar um sistema de cache para produtos
- Criar animações e transições suaves
- Melhorar a acessibilidade geral do site

### 💡 Dicas para Debugging

1. **Use o Console**: `console.log()` e `console.error()` são seus melhores amigos
2. **DevTools**: Utilize as ferramentas de desenvolvedor do navegador
3. **Network Tab**: Monitore as requisições da API
4. **Breakpoints**: Use breakpoints para depurar código passo a passo
5. **Teste Unitário**: Escreva testes para validar correções

### 🏆 Como Validar Suas Correções

- ✅ Funcionalidade funciona conforme esperado
- ✅ Não introduz novos bugs
- ✅ Código segue as boas práticas
- ✅ Performance não é degradada
- ✅ UX é melhorada

## 👤 Desenvolvedor

| Nome | E-mail | Telefone |
|------|--------|----------|
| Gabriel Henrique Vieira Nunes | gabriel.ghvn@gmail.com | (15) 98109-0508 |

---

**Nota**: Este projeto tem fins exclusivamente educacionais e foi desenvolvido como parte de um processo de aprendizado em desenvolvimento web.
