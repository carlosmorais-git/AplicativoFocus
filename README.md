# 🎯 FOCO - App de Produtividade e Pomodoro# 🎯 FOCO - App de Produtividade e Pomodoro

Aplicativo mobile de produtividade que combina timer Pomodoro com gerenciamento de tarefas. Desenvolvido com React Native e Expo.Aplicativo mobile de produtividade que combina timer Pomodoro com gerenciamento de tarefas. Desenvolvido com React Native e Expo.

## ✨ O que tem## ✨ O que tem

- 🍅 **Timer Pomodoro** - Cronômetro para sessões de foco- 🍅 **Timer Pomodoro** - Cronômetro para sessões de foco

- 📋 **Lista de Tarefas** - Criar, editar, excluir e marcar como concluídas - 📋 **Lista de Tarefas** - Criar, editar, excluir e marcar como concluídas

- 🎨 **Animações** - Feedback visual quando completa tarefas- 🎨 **Animações** - Feedback visual quando completa tarefas

- 📱 **Navegação por Abas** - Interface moderna bottom tabs- 📱 **Navegação por Abas** - Interface moderna bottom tabs

- 🌙 **Tema Escuro** - Design em tons escuros/roxos- 🌙 **Tema Escuro** - Design em tons escuros/roxos

## 🚀 Como rodar## 🚀 Como rodar

`bash`bash

# Clone o repo# Clone o repo

git clone https://github.com/carlosmorais-git/AplicativoFocus.gitgit clone https://github.com/carlosmorais-git/AplicativoFocus.git

cd AplicativoFocuscd AplicativoFocus

# Instala dependências# Instala dependências

npm installnpm install

# Roda o app# Roda o app

npm startnpm start

````



**No Windows:** Pode usar o `iniciar-projeto-foco.bat`**No Windows:** Pode usar o `iniciar-projeto-foco.bat`



Depois é só escanear o QR code com o Expo Go ou rodar no emulador (tecla `a` para Android, `i` para iOS).Depois é só escanear o QR code com o Expo Go ou rodar no emulador (tecla `a` para Android, `i` para iOS).



## 🔧 Stack## � Stack



React Native + Expo + Reanimated para as animaçõesReact Native + Expo + Reanimated para as animações



## ℹ️ Sobre## ℹ️ Sobre



Projeto pessoal de um app de produtividade. Refatorei de drawer navigation para bottom tabs e implementei animações quando você completa uma tarefa. Bem simples mas funciona! 😄Projeto pessoal de um app de produtividade. Refatorei de drawer navigation para bottom tabs e implementei animações quando você completa uma tarefa. Bem simples mas funciona! �

## 🏗️ Estrutura do Projeto

```
app/
├── _layout.jsx          # Layout principal com navegação por abas
├── index.jsx            # Tela inicial (Timer Pomodoro)
├── pomodoro.jsx         # Funcionalidades do timer
├── add_tarefa/          # Tela para adicionar tarefas
├── edit_tarefa/         # Tela para editar tarefas
└── tarefas/             # Lista de tarefas

components/
├── Actions/             # Botões de ação
├── DigitarTarefa/       # Input para tarefas
├── FocoBotao/           # Botão principal do timer
├── ModalGlobal/         # Modal reutilizável
├── NotificacaoGlobal/   # Sistema de notificações
├── TarefaItem/          # Item individual da tarefa
└── Tempo/               # Componente do cronômetro

context/
├── modal/               # Context API para modais
├── notificacao/         # Context API para notificações
└── tarefas/             # Context API para gerenciamento de tarefas
```

## 🎯 Funcionalidades Detalhadas

### Sistema de Navegação

- **Bottom Tabs**: Navegação intuitiva entre "Foco" e "Tarefas"
- **Roteamento**: Baseado em arquivos com Expo Router
- **Transições**: Animações suaves entre telas

### Animações e Feedback

- **Tarefa Concluída**: Animação de celebração com pulso e mudança de cor
- **Modais**: Entrada/saída com spring e scale
- **Notificações**: Animações fluidas com barra de progresso
- **Interações**: Feedback visual em todos os toques

### Gerenciamento de Estado

- **Context API**: Para estados globais (tarefas, modais, notificações)
- **Hooks customizados**: Para lógicas específicas
- **Persistência**: Estados mantidos durante a sessão

## 🔧 Scripts Disponíveis

```bash
# Iniciar o app
npm start

# Executar diretamente no Android
npm run android

# Executar diretamente no iOS
npm run ios

# Executar na web
npm run web

# Verificar código com ESLint
npm run lint

# Resetar projeto (limpar exemplo)
npm run reset-project
```

## ❓ FAQ

### **P: O app funciona offline?**

R: Sim! Todas as funcionalidades principais funcionam offline. Os dados são armazenados localmente no dispositivo.

### **P: É possível personalizar os tempos do Pomodoro?**

R: Atualmente o timer é fixo, mas a personalização está no roadmap para futuras versões.

### **P: O app consome muita bateria?**

R: Não! O app foi otimizado para uso eficiente de recursos, com animações nativas e gerenciamento inteligente de estado.

### **P: Funciona em tablets?**

R: Sim! O design é responsivo e se adapta a diferentes tamanhos de tela.

## 🤝 Contribuindo

Contribuições são sempre bem-vindas! Para contribuir:

1. Faça um fork do projeto
2. Crie uma branch para sua feature (`git checkout -b feature/AmazingFeature`)
3. Commit suas mudanças (`git commit -m 'Add some AmazingFeature'`)
4. Push para a branch (`git push origin feature/AmazingFeature`)
5. Abra um Pull Request

### 🐛 Reportando Bugs

- Use as [Issues do GitHub](https://github.com/carlosmorais-git/AplicativoFocus/issues)
- Descreva os passos para reproduzir o problema
- Inclua screenshots se possível
- Mencione seu dispositivo e versão do OS

## 📋 Roadmap

- [ ] Implementar persistência de dados (AsyncStorage)
- [ ] Adicionar estatísticas de produtividade
- [ ] Notificações push para lembretes
- [ ] Temas personalizáveis (claro/escuro)
- [ ] Integração com calendário
- [ ] Backup na nuvem
- [ ] Múltiplos perfis de timer

## � Documentação

- 📋 **[CONTRIBUTING.md](CONTRIBUTING.md)** - Guia para contribuidores
- 📜 **[CODE_OF_CONDUCT.md](CODE_OF_CONDUCT.md)** - Código de conduta da comunidade
- 📝 **[CHANGELOG.md](CHANGELOG.md)** - Histórico de mudanças e versões
- 🚦 **[Templates GitHub](.github/)** - Templates para Issues e PRs

## �📝 Licença

Este projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

## 📞 Contato

**Carlos Morais** - [GitHub](https://github.com/carlosmorais-git)

**Link do Projeto:** [https://github.com/carlosmorais-git/AplicativoFocus](https://github.com/carlosmorais-git/AplicativoFocus)

---

## 📈 Histórico de Desenvolvimento

### 🚀 Versão 2.0 - Refatoração Completa (Outubro 2025)

Este projeto passou por uma **refatoração completa** focada na experiência do usuário:

#### 🔄 **Principais Mudanças:**

- **Navegação:** Migração de Drawer Navigator → Bottom Tabs
- **Design:** Implementação de tema escuro moderno (#021123, #B872FF)
- **Animações:** Sistema completo com React Native Reanimated
- **UX:** Feedback visual aprimorado em todas as interações

#### ✨ **Melhorias Implementadas:**

| Área             | Antes                        | Depois                                    |
| ---------------- | ---------------------------- | ----------------------------------------- |
| **Navegação**    | Menu lateral (Drawer)        | Abas inferiores (Bottom Tabs)             |
| **Modais**       | Básicos com animação simples | Modernos com spring e scale               |
| **Notificações** | Apenas auto-close            | Fechamento manual + tipos específicos     |
| **Tarefas**      | Lista simples                | Animações de celebração + feedback visual |

#### 🎯 **Funcionalidades Testadas:**

- ✅ Navegação fluida entre abas
- ✅ Timer Pomodoro funcionando perfeitamente
- ✅ CRUD completo de tarefas
- ✅ Animações de conclusão de tarefa
- ✅ Sistema de notificações responsivo
- ✅ Responsividade em diferentes dispositivos

---

_Desenvolvido com ❤️ usando React Native e Expo_
````
