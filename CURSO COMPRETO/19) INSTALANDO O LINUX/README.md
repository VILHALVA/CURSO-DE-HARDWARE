# Instalando o Linux (Ubuntu) em Dual Boot com o Windows
A instalação do Ubuntu em dual boot com o Windows permite que você tenha dois sistemas operacionais no mesmo computador. Isso é útil para desenvolvedores que desejam usar o Linux para desenvolvimento, mas ainda precisam do Windows para outras tarefas. Siga este guia passo a passo para realizar a instalação do Ubuntu em dual boot com o Windows:

## **Requisitos:**
- Computador com Windows já instalado.
- Pendrive com uma imagem do Ubuntu (ISO) - você pode baixá-la no [site oficial do Ubuntu](https://ubuntu.com/download/desktop).
- Software de criação de mídia de instalação, como o Rufus (para Windows) ou Etcher (multiplataforma).

## **Passos para Instalar o Ubuntu em Dual Boot:**
### **Passo 1: Preparando o Pendrive:**
1. Insira o pendrive no seu computador.

2. Baixe e instale um software de criação de mídia de instalação, como o Rufus (para Windows) ou o Etcher (multiplataforma).

3. Abra o software de criação de mídia e siga as instruções para criar um pendrive de inicialização a partir da imagem do Ubuntu. Certifique-se de selecionar a imagem do Ubuntu que você baixou e escolher o pendrive como o dispositivo de destino.

4. O software irá formatar o pendrive e criar uma unidade de inicialização do Ubuntu.

### **Passo 2: Configurando o Computador para Inicializar a partir do Pendrive:**
1. Insira o pendrive preparado no seu computador.

2. Ligue o computador e acesse a BIOS/UEFI (a tecla para acessar a BIOS varia de acordo com o fabricante, geralmente é DEL, F2, F12 ou Esc; consulte o manual da placa-mãe).

3. Vá para as configurações de inicialização e defina o pendrive como a primeira opção de inicialização.

4. Salve as configurações e reinicie o computador.

### **Passo 3: Iniciando a Instalação do Ubuntu:**
1. O computador iniciará a partir do pendrive e você verá o menu de instalação do Ubuntu.

2. Selecione o idioma e clique em "Instalar Ubuntu".

3. Siga as instruções na tela para configurar as preferências de idioma, teclado e fuso horário.

### **Passo 4: Configurando as Partições:**
1. Quando você chegar à tela de particionamento de disco, escolha a opção "Instalar o Ubuntu ao lado do Windows" para criar um sistema dual boot.

2. O Ubuntu detectará automaticamente a partição do Windows e alocará espaço para o Ubuntu. Você pode ajustar o tamanho da partição, se desejar.

3. Siga as instruções para criar uma conta de usuário e configurar sua senha.

4. Conclua a instalação do Ubuntu.

### **Passo 5: Inicialização Dual (Dual Boot):**
1. Após a instalação, o sistema permitirá que você escolha entre o Ubuntu e o Windows durante a inicialização. Selecione o sistema operacional que deseja usar.

2. Você agora tem um sistema dual-boot com o Ubuntu e o Windows. Pode escolher qual sistema operacional inicializar sempre que ligar o computador.

Após concluir esses passos, o Ubuntu estará instalado no seu computador, permitindo que você escolha entre o Ubuntu e o Windows durante a inicialização. Certifique-se de instalar todos os drivers necessários para o Ubuntu e atualizar o sistema para obter as últimas correções de segurança e atualizações de recursos. O seu computador agora é um sistema dual-boot com dois sistemas operacionais.