# <div align="center"><h1>:medical_symbol: CLINICA HEALING::medical_symbol:</h1></div>


 <p align="center">
  <img src="templates/static/geral/img/logo.png" alt="logo" style="width: 100px;">
</p>

___

# <div align="center"><h2> TELA DE LOGIN </h2></div>
![TELA LOGIN](logar.png)
___

No que consite este projeto:
-- Back end de uma clínica médica
- Telas de login e cadastro para os usuários
- Cadastro para médicos
- Pacientes podem marcar consultas e ter atendimento online com facilidade
- Médicos consegue atender seus pacientes e entregar documentos via anexo

## Configurando o ambiente para executar a aplicação web.
Faça o download deste repositorio:

```
$ git clone https://github.com/jorgevendramini/Healing.git
```

Crie um maquina virtual e instale as bibliotecas disponiveis no 
arquivo requirements.txt: (TBA)

Entre na pasta criada e inicie um ambiente virtual:
```
$ cd Healing
$ python3 -m venv .venv (win: python -m venv .venv)
```
Depois voce deve ativa-lo com o seguinte comando:

```
$ source ./venv/bin/activate (win: ./venv/Scripts/activate)
```
Apos ativado, instale as bibliotecas necessárias para executar o projeto:
```
 (venv)$ pip install -r requirements.txt (TBA)
```
Para poder ter o primeiro acesso e pode configurar o aplicação vamos executar o comando 
'migrate' para gerar o banco de dados padrão do Django(SQLite). E depois criar o superusuario:
```
(venv)$ ./manage.py migrate
(venv)$ ./manage.py createsuperuser
Apelido/Usuário: admin
E-mail: admin@mail.com
Password: 
Password (again):
```

Para iniciar o servidor depois deste passo você deve:
```
(venv)$ ./manage.py runserver (win: python manage.py runserver)
```
___

<div align="center">Desenvolvedores/Contribuintes :octocat:

 [<img src="https://avatars.githubusercontent.com/u/7544824?s=400&u=853465e4d59e6e05490754e0b6ea7e118b7084f4&v=4" width=115  align="center"><br><sub>Jorge Enrique Vendramini</sub>](https://github.com/jorgevendramini)
 </div>
