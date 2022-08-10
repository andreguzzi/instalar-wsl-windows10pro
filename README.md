# instalar-wsl-windows10pro

Tutorial

Instalar o Wsl no Windows 10 pro

Painel de controle -> programas
Ativar desativar recursos do Windows

habilitar :
* Plataforma de maquina virtual
* Plataforma do hypervisor do Windows
* Subsistema do windows para Linux

ok e reiniciar 

Abrir site https://aka.ms/wsl2kernel
Menu Instalar -> Etapas de instalação manual para versões mais antigas.. 
na etapa 4 baixar pacote de atualização do kernel do linux do wsl2 para computadores x64

Instalar e reiniciar

No cmd digitar :
bcdedit, conferir se o hypervisorlauchtype está auto

Caso não estiver digitar :
bcdedit /set hypervisorlaunchtype auto

Reiniciar

(no virtual box não funciona com o auto precisa ser off, escolher usar entre o wsl ou o virtual box)

Por último ir até a loja microsoft store e baixar o ubuntu, ao iniciar vai solicitar um usuário e senha
