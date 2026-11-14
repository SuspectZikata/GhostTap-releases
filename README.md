# ⚡ GhostTap v4.0

A **versão 4.0** representa o maior salto de engenharia do GhostTap até hoje! Eliminamos de forma definitiva a necessidade de aplicativos de terceiros: agora o nosso motor nativo roda de forma **100% autônoma em qualquer celular Android**, com economia pesada de bateria e zero travamentos para você rodar na rua o dia todo no 4G/5G.

---

### 🚀 O Fim dos Apps Externos (Adeus Shizuku e Truque do Roteador!)
- **Compatibilidade Universal Nativa:** O GhostTap agora funciona direto em celulares de entrada e intermediários (como **Samsung Galaxy A07, A14, A36, Linha M e Motorola Moto G/Edge**) sem precisar instalar o Shizuku e sem precisar ligar o roteador/ponto de acesso do celular.
- **Transição 4G/5G Blindada:** Ao sair do Wi-Fi de casa e ir para os dados móveis na rua, o motor permanece vivo em nível de sistema operacional (Kernel Android). Ele não cai e não fecha.
- **Motor Interno GhostEngine com Binder IPC:** Nova comunicação ultrarrápida direta pelo sistema, entregando a menor latência de clique da história do app (in-memory, resposta instantânea).

---

### 🔋 Otimização Extrema de Bateria e Processamento (Celular Frio o Dia Todo)
- **Zero Aquecimento (Pacing de 35 FPS):** Otimizamos a taxa de varredura da tela para manter uma reação superveloz (abaixo de 30ms) consumindo **60% menos CPU**. Seu celular não vai esquentar e não vai sofrer com lentidão no sol.
- **Economia Máxima de Bateria:** O app desliga automaticamente as varreduras de rede (mDNS) assim que o motor sobe, permitindo que o chip Wi-Fi e o modem 4G/5G do celular entrem em repouso profundo quando você estiver rodando.
- **Sem Engasgos de Memória (Zero-GC):** Toda a análise visual do OpenCV agora utiliza memória pré-alocada em pool, eliminando coletas de lixo do Android e travamentos mesmo em aparelhos com apenas 3GB ou 4GB de RAM.

---

### 🎯 Experiência e Praticidade para o Entregador
- **Bolinha Flutuante com Reativação Rápida:** Ao apagar a tela do celular ou atender uma ligação, o botão flutuante não some da tela. Quando você desbloquear o aparelho, basta dar **1 toque na bolinha** para ela voltar a ler a tela e aceitar pedidos na hora!
- **Interface e Diagnóstico em Tempo Real:** A tela inicial do app agora identifica o status do motor em tempo real: conectado, pronto para 4G ou com aviso amigável caso precise de 2 segundos de Wi-Fi para rearmar.

---

### 📥 Como Instalar / Atualizar
1. Baixe o arquivo **`GhostTap-v4.0.apk`** logo abaixo na seção **Assets**.
2. Abra o arquivo no seu Android para atualizar por cima da sua versão atual (suas configurações e área de busca continuam salvas).
3. Conecte no Wi-Fi por alguns segundos para ativar a Depuração Wi-Fi no Passo 1 e pronto: pode ir pra rua faturar no 4G!

---

### 💬 Dúvidas, Parcerias e Suporte
- 📱 **Instagram do Desenvolvedor:** [@wagnersrjunior](https://www.instagram.com/wagnersrjunior/)
- 💬 **Suporte WhatsApp:** Disponível diretamente pelo botão no topo do aplicativo.
