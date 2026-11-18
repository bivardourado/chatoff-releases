# 📡 ChatOff — Mensagens P2P 100% Offline via Bluetooth

> **Comunique-se em qualquer lugar, sem operadoras, sem internet, sem servidores e com total privacidade.**

O **ChatOff** é um aplicativo de mensagens instantâneas descentralizado (Peer-to-Peer) que utiliza o rádio **Bluetooth Low Energy (BLE)** do smartphone para criar canais diretos de comunicação ponto-a-ponta. Ideal para situações de emergência, áreas rurais, trilhas, eventos lotados, apagões ou locais sem sinal de celular.

---

## ⚡ Principais Recursos

- 🚫 **Zero Internet**: Não precisa de Wi-Fi, 4G/5G, nem chip SIM instalado.
- 💬 **Interface Estilo WhatsApp**: Lista de conversas organizadas, mensagens com status de envio, entrega e leitura.
- 🔒 **Conversas Privadas (1 para 1)**: Inicie bate-papos exclusivos com chave de criptografia gerada sob demanda.
- 🌐 **Lobby Público (Radar Aberto)**: Envie mensagens abertas para todos os dispositivos ao seu redor.
- 🛡️ **Criptografia Real de Ponta-a-Ponta**: Todas as mensagens trafegam cifradas usando **ChaCha20-Poly1305 (256 bits)**.
- 🔄 **Atualizações Automáticas**: O app verifica e atualiza versões novas sozinho quando houver conexão disponível.
- 🔋 **Segundo Plano Confiável**: Serviço otimizado para não ser encerrado pelo modo de economia de energia do Android (Doze Mode).

---

## 📥 Como Baixar e Instalar

### 🤖 Android (APK Direto)

1. Vá até a seção de **[Releases Oficiais](https://github.com/bivardourado/chatoff-releases/releases/latest)** deste repositório.
2. Baixe o arquivo **`ChatOff.apk`** mais recente diretamente no seu celular Android.
3. Abra o arquivo baixado e autorize a opção **"Permitir instalação de fontes desconhecidas"** (caso seu Android solicite).
4. Abra o aplicativo e **conceda as permissões de Bluetooth e Dispositivos Próximos** para que o rádio possa encontrar aparelhos vizinhos.

### 🍏 iOS (iPhone)
O pacote compilado `.ipa` está disponível na aba de Releases para instalação via AltStore, Sideloadly ou perfis de provisionamento de desenvolvedor.

---

## 🚀 Como Usar o ChatOff

1. **Abrir o App**: Ao abrir, você verá seu apelido gerado (ex: `Android-4A2F`).
2. **Personalizar Nome**: Toque no menu `⋮` no topo direito ➔ **Renomear-me** para colocar seu nome real ou apelido.
3. **Conversar no Lobby Público**:
   - Toque em **Lobby Aberto**. Qualquer pessoa próxima com o app aberto receberá suas mensagens.
4. **Conversar Privadamente (1:1)**:
   - Na tela inicial, toque no botão flutuante **💬 (Nova Conversa)**.
   - O app fará uma varredura dos aparelhos ao redor.
   - Ao lado da pessoa desejada, toque em **CHAT**.
   - A outra pessoa receberá um aviso na tela para aceitar o chat.
   - Assim que aceito, uma conversa privada e exclusiva será aberta e salva na sua lista!

---

## 🔐 Privacidade e Segurança

- Nenhum dado passa por servidores centrais ou nuvem.
- As mensagens só existem na memória e tela dos aparelhos que participam da conversa.
- O código do aplicativo roda localmente no hardware dos aparelhos via Bluetooth GATT Server.

---

## 💡 Dicas de Alcance e Desempenho

- O alcance típico do Bluetooth BLE varia entre **10 e 30 metros** em ambientes com obstáculos e até **50 metros** em campo aberto.
- Para melhor conexão, mantenha o Bluetooth e a Localização (exigência do sistema Android para busca de rádio BLE) sempre ativados.
