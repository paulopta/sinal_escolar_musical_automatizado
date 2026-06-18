# ⏱️ SinalEscolarTray

> Software para tocar uma música (mp3) de tempos em tempos programados podendo ser usado para sinal de intervalo escolar.
As músicas são executadas, por dois minutos, de forma aleatória, tendo como referências os arquivos .mp3 disponibilizados pelo usuário.

---

## 🛠️ Arquitetura e Tecnologias Utilizadas
* **Software:** Java
* **Músicas:** mp3
* **Arquitetura do Sistema:** Programa Principal

---

## 🚀 Como Começar

### Pré-requisitos
O que você precisa executar o software:
* JVM (Java Virtual Machine) instalada na máquina
* Arquivos de Música MP3

### Instalação e Configuração

1. **Download do Software:**
   Crie uma pasta no C: chamada "musicas_sinal"	
   Faça download dos arquivos SinalEscolarTray.jar e horarios.txt e salve ambos na pasta criada (C:\musicas_sinal) 

2. **Ajustes dos horários:**
   Edite o arquivo horários.txt, abrindo ele no Bloco de Notas, informando os horários que o sistema deve executar a música.
   Atenção! Deve haver somente um horário por linha do arquivo, conforme já está informado no arquivo baixado.	

2. **Adicione as músicas na pasta:**
   Cole os arquivos de música no formato mp3 que você gostaria que tocasse dentro da pasta criada ("C:\musicas_sinal")
   

4. **Adicione o programa para inicializar junto com o Windows:**

a) Abra a pasta de Inicialização: Pressione as teclas Windows + R no seu teclado. Na janela "Executar" que aparecer, digite shell:startup e pressione Enter, essa ação irá abrir uma pasta "Inicializar", minimize-a.

b) Crie um atalho do programa: Vá a pasta do programa (C:\musicas sinal) clique com o botão direito no arquivo SinalEscolarTray.jar, clique na opção "Criar Atalho". Caso essa opção não, clique em "Mostrar mais Opções" que ela aparecerá. Recorte (ctrl + x) o arquivo de atalho e cole (ctrl + v) na pasta "Inicializar" que você abriu no Passo A. 
Pronto. A partir de agora toda vez que ligar o computador o sistema inicializará automaticamente.


5. **Acessando o software:**
   Uma vez disponível, o sistema pode ser acessado ao lado do ícone do relógio do Windows. O ícone do sistema é um relógio de ponteiros analógicos com fundo branco.
   Para encerrar o sistema, recarregar horários, ou ver os créditos, basta clicar no ícone do programa com o botão direito.

6. **Alterando os horários em tempo de execução:**
   É pssível alterar os horários sem precisar sair do sistema. Para tal, você deve editar o arquivo horarios.txt (C:\musicas_sinal\horarios.txt) informando os horários novos.
   Depois clique no ícone do programa com o botão direito e escolha a opção "Recarregar Horários".  	


---

## 📐 Estrutura do Projeto

Uma visão macro de como os arquivos estão organizados:

```C:
├── musicas_sinal/
│   ├── SinalEscolarTray.jar      # software java da solução
│   ├── horários.txt              # arquivo com os horários em que o sinal deve tocar, formato hh:mm
│   └── *.mp3                     # arquivos de música que são opção para o programa escolher aleatoriamente
```

---

## 🤝 Dúvidas / Sugestões / Agradecimentos

prof. Paulo Henrique Rodrigues 
paulohenriquerodrigues@outlook.com

---

## 📄 Licença

Este projeto está sob a licença Creative Commons. Os usuários podem copiar e utilizar sem que seja necessário o pagamento de direitos autorais. 

