# API - Planta de nível
Projeto realizado na disciplina de C213 (Sistemas Embarcados) durante a graduação em Engenharia de Computação pelo [Inatel](https://inatel.br/home/). Ele permite que através de um arquivo .MAT de amostras de um circuito, calcule os ganhos de malha aberta, malha fechada, malha fechada com ganho proporcional (Kp) e malha fechada com ganho proporcional integral (Kp e Ki), e returna através de um arquivo .JSON esse dados.

---
## Tecnologias utilizadas
* <img height="30" src="https://cdn.worldvectorlogo.com/logos/numpy.svg"/> [NumPy](https://numpy.org/)
* <img height="30" src="https://upload.wikimedia.org/wikipedia/commons/thumb/b/b2/SCIPY_2.svg/512px-SCIPY_2.svg.png"/> [SciPy](https://www.scipy.org/)
* <img height="30" src="https://upload.wikimedia.org/wikipedia/commons/thumb/5/5e/Control_logo.svg/1200px-Control_logo.svg.png"/> [Control](https://python-control.readthedocs.io/en/0.8.3/)
* <img height="30" src="https://camo.githubusercontent.com/028d16eb9f6d7d94854a6a773cb80cff7d839a58182995ef284e225a624136d9/68747470733a2f2f7777772e70726f62797465732e6e65742f77702d636f6e74656e742f75706c6f6164732f323031382f31302f666c61736b2d6c6f676f2d706e672d7472616e73706172656e742e706e67"/> [Flask](https://flask.palletsprojects.com/en/1.1.x/)

---
## Como utilizar?

- Instalar o [Python](https://www.python.org/downloads/) 3.6 ou superior, caso não tenha.

```bash

# Clonar o repositório
$ git clone https://github.com/MoisesSDelmoro/planta-de-nivel-api

# Na pasta raíz, executar:
$ pip install -r requirements.txt 

#Entrar no diretório
$ cd planta-de-nivel-api

# rodar
$ code .

```
- Para visualizar os dados, acesse a parte WEB do nosso projeto, através do [link](https://github.com/GabrielGSD/planta-de-nivel-web)

---
## Colaboradores

<table>
  <tr>
    <td align="center"><a href="https://github.com/GabrielGSD/"><img style="border-radius: 50%;" src="https://user-images.githubusercontent.com/57488202/117461169-a57bc400-af23-11eb-8e32-86dc54da88c2.png" width="100px;" alt=""/><br /><sub><b>Gabriel S. Daniel</b></sub></a></td>      
    <td align="center"><a href="https://github.com/MoisesSDelmoro"><img style="border-radius: 50%;" src="https://user-images.githubusercontent.com/57488202/117151468-7f251f80-ad8f-11eb-9e56-7a242b89ed72.png" width="100px;" alt=""/><br /><sub><b>Moises S. Delmoro</b></sub></a></td>  
  </tr>
</table>

---

##  Licença

Este projeto está sob a licença [MIT](./LICENSE).
