## Criação e Permissões de usuários

O arquivo "iac1.sh" criará usuários especificos, grupos específicos, dando permissões específicas. De forma adicional e diferenciar do projeto, usei o comando ``passwd -d -e -q <user>`` para que seja exigido configuração de senha no próximo login dos usuários criados a partir do shell script.

use:

```shell
git clone https://github.com/PedroIeremis/DIO-Bootcamp-Linux-Experience.git

cd DIO-Bootcamp-Linux-Experience

cd Script_Usuarios_Perms

chmod +x iac.sh

./iac1.sh
```
