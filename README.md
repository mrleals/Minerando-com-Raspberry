# Minerando-com_Raspberry
Como minerar usando raspberry pi modelo 3b 
> Estou usando a imagem Rapbian lite Arm64 disponivel: [Aqui](https://downloads.raspberrypi.org/raspios_lite_arm64/images/raspios_lite_arm64-2021-11-08/2021-10-30-raspios-bullseye-arm64-lite.zip)

### primeiro atualizaremos nossa raspberry com o seguinte comando no terminal:
```shell
sudo apt update
```
### Assim que estiver tudo atualizado basta instalar:
```shell
sudo apt install git build-essential cmake libuv1-dev libssl-dev libhwloc-dev -y
```
### Usaremos um codigo já pronto disponibilizado diretamente no Github com comando:
```shell
git clone https://github.com/xmrig/xmrig.git
```
