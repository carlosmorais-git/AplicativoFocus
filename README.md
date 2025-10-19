# 🎯 FOCO — App de Produtividade e Pomodoro

Aplicativo mobile que combina **técnica Pomodoro** e **gerenciamento de tarefas**, desenvolvido com **React Native + Expo**.

---

## ✨ Funcionalidades

- 🍅 **Timer Pomodoro** — Sessões de foco com cronômetro
- 📋 **Lista de Tarefas** — Criar, editar, excluir e marcar como concluída
- 🎨 **Animações** — Feedback visual ao completar tarefas
- 📱 **Navegação por Abas** — Interface moderna com bottom tabs
- 🌙 **Tema Escuro** — Design em tons escuros e roxos

---

## 🚀 Como Rodar

```bash
# Clone o repositório
git clone https://github.com/carlosmorais-git/AplicativoFocus.git
cd AplicativoFocus

# Instale as dependências
npm install

# Inicie o app
npm start
```

💡 **No Windows:** execute `iniciar-projeto-foco.bat`  
Depois, escaneie o QR Code com o **Expo Go** ou use o emulador (`a` para Android, `i` para iOS).

---

## 🧩 Stack

React Native • Expo • React Native Reanimated

---

## 🏗️ Estrutura

```
app/
├── _layout.jsx         # Layout principal com navegação
├── index.jsx           # Tela inicial (Pomodoro)
├── tarefas/            # Lista de tarefas
├── add_tarefa/         # Adicionar tarefa
├── edit_tarefa/        # Editar tarefa
└── pomodoro.jsx        # Lógica do cronômetro

assets/
├── Designer/           # Fotos do app funcionando

components/
├── Actions/            # Botões de ação
├── FocoBotao/          # Botão principal do timer
├── ModalGlobal/        # Modal reutilizável
├── NotificacaoGlobal/  # Sistema de notificações
└── TarefaItem/         # Item individual da tarefa

context/
├── modal/              # Controle de modais
├── notificacao/        # Controle de notificações
└── tarefas/            # Controle global de tarefas
```

---

## 🔧 Scripts

```bash
npm start          # Iniciar o app
npm run android    # Executar no Android
npm run ios        # Executar no iOS
npm run web        # Executar na web
npm run lint       # Verificar código
npm run reset-project  # Resetar o projeto
```

---

## ❓ FAQ

**O app funciona offline?**  
✅ Sim! Todos os dados são armazenados localmente.

**Posso personalizar o tempo do Pomodoro?**  
🕒 Ainda não, mas está no roadmap.

**Consome muita bateria?**  
🔋 Não! As animações são otimizadas com Reanimated.

**Funciona em tablets?**  
📱 Sim, com layout responsivo.

---

## 📋 Roadmap

- [ ] Persistência de dados (AsyncStorage)
- [ ] Estatísticas de produtividade
- [ ] Notificações push
- [ ] Temas personalizáveis
- [ ] Backup na nuvem

---

## 🤝 Contribuindo

1. Faça um fork
2. Crie uma branch (`git checkout -b feature/NovaFeature`)
3. Commit (`git commit -m "feat: adiciona NovaFeature"`)
4. Push (`git push origin feature/NovaFeature`)
5. Abra um Pull Request

🐛 **Reportar bugs:** [Issues](https://github.com/carlosmorais-git/AplicativoFocus/issues)

---

## 📈 Versão 2.0 — Refatoração Completa (Out/2025)

**Principais mudanças:**

- Drawer → Bottom Tabs
- Tema escuro moderno (#021123 / #B872FF)
- Animações com Reanimated
- UX aprimorada e feedback visual em todas as ações

---

## 🧾 Licença

Licenciado sob **MIT** — veja [LICENSE](LICENSE).

---

## 📞 Contato

**Carlos Morais** — [GitHub](https://github.com/carlosmorais-git)  
📦 Projeto: [AplicativoFocus](https://github.com/carlosmorais-git/AplicativoFocus)

---

_Desenvolvido com ❤️ usando React Native e Expo._
