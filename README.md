# Dashboard de Controle

Um painel de controle moderno e responsivo desenvolvido em HTML e CSS para gerenciamento de projetos e tarefas.

## 📋 Descrição

Este projeto implementa um dashboard completo com funcionalidades de visualização de dados, gerenciamento de tarefas e criação de projetos. A interface apresenta um design limpo e profissional, otimizada para uso em ambientes corporativos.

## 🎨 Características Visuais

- Design moderno com esquema de cores azul e cinza
- Interface responsiva e intuitiva
- Cards informativos com shadow effects
- Tabela estilizada para exibição de tarefas
- Formulário para criação de novos projetos
- Sidebar de navegação fixa

## 🚀 Funcionalidades

### Painel Principal
- **Métricas principais**: Exibe projetos ativos (12), tarefas concluídas (48) e alertas pendentes (5)
- **Busca integrada**: Campo de pesquisa no topo do dashboard
- **Logout**: Botão de saída com ícone

### Gerenciamento de Tarefas
- **Visualização em tabela**: Lista de tarefas recentes com informações detalhadas
- **Status badges**: Indicadores visuais de status (Em Andamento, Pendente, Concluído)
- **Cards de tarefas pessoais**: Seção "Minhas Tarefas" com prioridades coloridas
- **Sistema de prioridades**: Alta (vermelho), Média (laranja), Baixa (azul)

### Criação de Projetos
- **Formulário completo**: Nome, responsável, prazo e descrição
- **Validação**: Campos obrigatórios marcados
- **Interface amigável**: Design consistente com o resto da aplicação

### Navegação
- **Sidebar fixa**: Menu lateral com ícones e labels
- **Seções organizadas**: Visão Geral, Projetos, Tarefas, Relatórios e Configurações
- **Avatar do usuário**: Identificação visual com iniciais "US"

## 📁 Estrutura de Arquivos

```
projeto/
├── index.html          # Página principal
├── style.css           # Estilos CSS
└── img/
    └── Config-White-ic.png  # Ícone de configurações
```

## 🛠️ Tecnologias Utilizadas

- **HTML5**: Estrutura semântica
- **CSS3**: Estilização avançada com Grid Layout e Flexbox
- **Google Material Icons**: Ícones da interface
- **Google Fonts**: Tipografia (Material Icons)

## 🎯 Layout e Responsividade

### Estrutura Principal
- **Sidebar**: 15% da largura da tela (fixa)
- **Conteúdo principal**: 85% da largura restante
- **Grid system**: Cards organizados em grid responsivo

### Elementos Visuais
- **Cores principais**: 
  - Azul escuro (#182c46) - Sidebar
  - Azul claro (#0c97e7) - Avatar e elementos de destaque
  - Cinza claro (#f0f0f0) - Fundo principal
- **Shadows**: Efeito de profundidade nos cards
- **Border radius**: Cantos arredondados (12px nos cards principais)

## 🚀 Como Usar

1. **Instalação**:
   ```bash
   # Clone ou baixe os arquivos
   # Certifique-se de ter a pasta img/ com o ícone necessário
   ```

2. **Execução**:
   - Abra o arquivo `index.html` em qualquer navegador moderno
   - A aplicação funciona localmente sem necessidade de servidor

3. **Personalização**:
   - Modifique as cores no arquivo `style.css`
   - Adicione novos itens de menu na seção `#itens-Header`
   - Customize os cards alterando o conteúdo HTML

## 📊 Componentes Principais

### Cards de Métricas
```html
<div class="card">
    <h2>Título da Métrica</h2>
    <h1>Valor</h1>
</div>
```

### Status Badges
- `.status-andamento` - Amarelo para tarefas em progresso
- `.status-pendente` - Vermelho para tarefas pendentes  
- `.status-concluido` - Verde para tarefas finalizadas

### Formulário de Projeto
- Campos de entrada com validação HTML5
- Design consistente com o padrão visual
- Textarea para descrições longas

## 🎨 Customização

### Alterando Cores
No arquivo `style.css`, modifique as variáveis de cor:
- Sidebar: `rgb(24, 44, 70)`
- Fundo principal: `rgb(240, 240, 240)`
- Accent color: `rgb(3, 34, 75)`

### Adicionando Novos Cards
Duplique a estrutura de card existente e personalize o conteúdo:
```html
<div class="card">
    <h2>Nova Métrica</h2>
    <h1>Novo Valor</h1>
</div>
```

## 📱 Compatibilidade

- ✅ Chrome 60+
- ✅ Firefox 55+
- ✅ Safari 11+
- ✅ Edge 16+

## 🔧 Melhorias Futuras

- [ ] Implementar responsividade para dispositivos móveis
- [ ] Adicionar funcionalidade JavaScript para interações
- [ ] Integrar com backend para dados dinâmicos
- [ ] Implementar modo escuro
- [ ] Adicionar filtros e ordenação na tabela
- [ ] Sistema de notificações

## 📄 Licença

Este projeto está disponível para uso livre e modificação.

---

**Desenvolvido para fins academicos :)**
