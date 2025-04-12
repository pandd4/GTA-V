# 🌆 Projeto GTA V - Interface Personalizada

Este projeto tem como objetivo criar uma interface personalizada para GTA V utilizando **HTML**, **CSS** e **JavaScript**, com foco em imersão, usabilidade e desempenho.

> 🎮 Ideal para servidores RP (Roleplay), FiveM, RageMP, ou projetos standalone inspirados no universo de Grand Theft Auto V.

---

## 📁 Estrutura do Projeto

```bash
📦 gta-v-interface
├── index.html         # Página principal da interface
├── style.css          # Estilização da interface
├── script.js          # Funcionalidades e interações
└── assets/            # Imagens, ícones, fontes, etc.
```

---

## 🚀 Funcionalidades

- HUD personalizada (vida, colete, fome, sede)
- Painel de login e registro estilizado
- Menu de inventário com animações
- Notificações na tela
- Painel administrativo (opcional)
- Design responsivo e otimizado para integração com mods e servidores

---

## 🛠️ Tecnologias Utilizadas

- HTML5
- CSS3 (com transições e animações)
- JavaScript (vanilla JS, sem frameworks)
- FiveM NUI (para integração com servidores, opcional)

---

## 🔧 Como Usar

1. Clone o repositório:
   ```bash
   git clone https://github.com/seu-usuario/gta-v-interface.git
   ```
2. Coloque os arquivos na pasta `resources` do seu servidor FiveM ou utilize como base para seu projeto de mod.
   
3. Se estiver usando com FiveM, adicione no `__resource.lua` ou `fxmanifest.lua`:

   ```lua
   ui_page 'index.html'

   files {
       'index.html',
       'style.css',
       'script.js',
       'assets/**/*'
   }
   ```

4. Inicie o recurso no servidor com:
   ```bash
   ensure gta-v-interface
   ```

---

## 👨‍💻 Contribuição

Contribuições são bem-vindas! Sinta-se livre para abrir issues, enviar pull requests ou propor melhorias.

---

## 📄 Licença

Este projeto está licenciado sob a [MIT License](LICENSE).

---

## 📸 Imagens do Projeto

![HUD](assets/screenshots/hud-example.png)
![Painel de Inventário](assets/screenshots/inventory-example.png)

---

## 📬 Contato

Desenvolvido por Amanda dos Santos (https://github.com/pandd4)  
📧 Email: amand4contato@gmail.com 
🔗 Projeto para fins educacionais e de entretenimento realizado na Imersão do Dev em Dobro.
```

