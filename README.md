# ⏱️ Meeting Timer

Um cronômetro profissional e intuitivo desenvolvido para a gestão de tempo em reuniões, com suporte a múltiplas abas, alertas visuais (semáforo) e compartilhamento de relatórios.

---

## 📥 Download do Aplicativo (Android)

Para sua comodidade, você pode instalar o **Meeting Timer** diretamente no seu celular Android. Clique no botão abaixo para baixar a versão mais recente:

[![Baixar APK](https://img.shields.io/badge/Download-APK_Instalador-success?style=for-the-badge&logo=android)](https://github.com/felipesenajw/meeting-timer-web/releases/download/v1.0.0/app-release.apk)

> **💡 Dica de Instalação:** Como o app é distribuído fora da Play Store, ao abrir o arquivo, o Android pode solicitar permissão para "Instalar de Fontes Desconhecidas". Basta autorizar para concluir a instalação.

---

## 🚀 Principais Funcionalidades

* **Dual Mode:** Abas separadas para reuniões de *Meio de Semana* e *Fim de Semana*.
* **Alerta Visual (Semáforo):**
    * 🟢 **Verde:** Tempo em execução.
    * 🟡 **Amarelo:** Alerta de 1 minuto restante.
    * 🔴 **Vermelho Pulsante:** Meta de tempo ultrapassada.
* **Relatórios Automáticos:** Gere um resumo detalhado e envie para o WhatsApp com um clique.
* **Customização Total:** Edite nomes, tempos e organize a ordem das partes arrastando os cards.
* **Modo Escuro:** Interface adaptável para ambientes com pouca luz.

## 🛠️ Como usar a versão Web
Se preferir não instalar o app, você pode abrir o arquivo `index.html` diretamente em qualquer navegador moderno (Chrome, Safari ou Edge).

[ ![Acesse o App](https://img.shields.io/badge/Acesse%20o%20App-Clique%20Aqui-5a3d8d?style=for-the-badge) ](https://felipesenajw.github.io/meeting-timer-web/)

## 🚀 Funcionalidades
- **Feedback Visual:** Cards mudam de cor (amarelo/vermelho) conforme o tempo se aproxima da meta ou a ultrapassa.
- **Organização Flexível:** Arraste e solte (Drag & Drop) para reordenar partes dentro das seções.
- **Modo Offline:** Funciona via navegador e salva todos os dados localmente (localStorage).
- **Relatórios:** Compartilhamento formatado via WhatsApp com um clique.
- **Personalização:** Suporte a Tema Escuro (Dark Mode) e edição completa de seções.

## 🛠️ Tecnologias
- HTML5 / CSS3 (Variáveis CSS, Flexbox)
- JavaScript Vanilla (Puro)
- [SortableJS](https://sortablejs.github.io/Sortable/) (para a funcionalidade de drag & drop)
- Material Icons (Google)

## 📱 Como usar no Celular
Este projeto foi desenhado como um **Web App**. 
1. Abra o link do GitHub Pages no seu navegador mobile.
2. No Chrome (Android) ou Safari (iOS), selecione "Adicionar à Tela Inicial".
3. O ícone aparecerá como um aplicativo nativo.

## 🚀 Últimas Atualizações

<details>
<summary><b>Clique para conferir as novidades da Versão Atual – 0.1.1</b></summary>

### 💡 Experiência de Uso (UX/UI)
* **Barra de Navegação Unificada:** O botão **Compartilhar** agora reside na barra inferior, centralizando as ações e liberando mais espaço para os cronômetros.
* **Modo de Edição Dinâmico:** Ao clicar em `Configurar`, o botão se transforma em um check de `Confirmar` (verde), indicando visualmente que você está em modo de ajuste.
* **Indicador de Tela Ativa:** Um novo ícone de **lâmpada 💡** no rodapé acende sempre que o modo "Sempre Ligado" está operando.

---

### ⚙️ Funcionalidades e APIs
* **📱 Screen Wake Lock API:** O sistema agora impede que o celular apague a tela automaticamente enquanto um cronômetro estiver rodando. Ao pausar, a tela é liberada para economizar bateria.
* **📳 API de Vibração (Feedback Tátil):**
    * **Vibração Curta (200ms):** Alerta quando falta exatamente **1 minuto** para atingir a meta.
    * **Vibração Dupla (400ms):** Notifica quando o tempo da parte se **esgotou**.

---

### 📝 Relatórios e Compartilhamento
* **Relatórios Segmentados:** O app agora é inteligente! Ele identifica se você está na aba "Meio de Semana" ou "Fim de Semana" e gera o relatório apenas da reunião atual.
* **Organização por Marcadores:** As mensagens enviadas via WhatsApp agora contam com divisores visuais temáticos, facilitando a leitura de quem recebe:
    * 💎 **TESOUROS**
    * 🎤 **MINISTÉRIO**
    * 🌳 **VIDA CRISTÃ**
* **Novo Título:** Relatórios agora são identificados como `⏱️ TEMPO DAS PARTES`.

</details>
