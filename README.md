# ProjIntegrador

1) navegar para diretoria onde se vai instalar este repositório
2) correr <mark>git clone https://github.com/FC1104-XX/ProjIntegrador.git </mark> no terminal
3) <mark>cd ProjIntegrador</mark>
4) se for a primeira vez, ou seja, logo após instalar repo o ambiente virtual tem que ser criado, ativado, e todas as dependências têm que ser instaladas nele <br>
   <mark>python -m venv .venv</mark><br>
   <mark>.venv/Scripts/activate</mark> (para Windows)<br>
   <mark>source .venv/bin/activate</mark> (para Linux)<br>
   agora com o ambiente virtual criado e ativado instalamos todas as depêndencias<br>
   <mark>pip install -r requirements.txt</mark><br>
   para desativar o ambiente virtual <mark>deactivate</mark>
5) O passo anterior pode ser passado à frente ao simplesmente instalar todas as dependências sem nenhum ambiente (embora não seja recomendado)<br>
   <mark>pip install -r requirements.txt</mark><br>
6) Escolher o kernel do ambiente virtual (ou não se se passou o quarto passo à frente) no editor de código e correr<br>

Para correr o código no jupyter online fazer os primeiros 4 passos iguais e depois em windows correr no terminal(na diretoria do repositorio):<br>
<mark>Set-ExecutionPolicy -ExecutionPolicy Bypass -Scope Process</mark><br>
<mark>.venv/Scripts/activate</mark><br>
<mark>python -m ipykernel install --user --name=venv-kernel --display-name "Python (venv)"<mark><br>
Escolher o kernel "Python (venv)" no jupyter


