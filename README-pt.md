
# Flask Init

Um modelo inicial de aplicação em Flask.


### 🔗 Outras Versões deste Readme

[Versão em inglês](README.md)

### 📖 Sobre

Um modelo inicial de aplicação em Flask utilizando o modelo  Factory.
Este modelo facilita a criação dos arquivos iniciais economizando tempo e facilitando a implementação.
O modelo já vem com o FlaskSQL-alchemy e Flask-WTF prontos para o uso. tendo somente que configurar os caminhos do banco de dados.

### 📋 Pré-requisitos

```
Python 3.8 ou superior
Pip 20.0 ou superior
virtualenv 20.4 ou superior
```

### 🔧 Instalação

Para fazer a instalação do requirements é necessario primeiramente criar um ambiente virtual para podermos utilizar o app.

**Linux**
instalação do virtualenv:
```
sudo apt-get install python3-venv
```
criando o ambiente virtual:
```
python3 -m venv nome_do_ambiente
```
para ativar o ambiente virtual :
```
source nome_do_ambiente/bin/activate
```
Com o ambiente devidamente ativado instalamos os requerimentos com o seguinte código:
```
pip3 install -r requirements.txt
```
após a instalação dos frameworks não se esqueça de alterar os caminhos para os bancos de dados

## ⚙️ Executando os testes

Com o virtualenv ativado podemos rodar a Aplicação em localhost utilizamos o seguinte código, para rodar a aplição em produção  mude o tipo de ambiente.
```
flask run
```

## 🛠️ Construído com

Ferramentas utilizadas na criação desta aplicação

 * python

* [Flask](https://flask.palletsprojects.com/en/1.1.x/)
* [Flask-SQLAlchemy](https://flask-sqlalchemy.palletsprojects.com/en/2.x/)
* [Flask-WTF](https://flask-wtf.readthedocs.io/en/stable/)


## ✒️ Desenvolvedor

* **Bruno Alves** - *Desenvolvedor Fullstack* - [Bruno Azzireluto](https://github.com/Brunoazzireluto)

---
Um projeto de [Azzireluto](https://github.com/Brunoazzireluto)