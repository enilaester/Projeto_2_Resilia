## <center>Projeto de Conclusão -  Módulo 2 - Curso Data Analyst</center>


![image](https://user-images.githubusercontent.com/106848389/180666234-915735fb-ebe4-4d95-80d0-470a129a5fab.png)


## 🧭 OBJETIVO 

Para o projeto final do Módulo 2 da formação em Data Analytics da [Resilia Educação](https://www.resilia.com.br), atuamos como uma empresa fictícia denominada "CKA - Consultoria em Tecnologia e Informação" com o objetivo de desenvolver uma pesquisa digital em linguagem Python sobre a percepção dos brasileiros a respeito do processo eleitoral do nosso país 🗳️ (sem nenhum cunho político/partidário). Essa pesquisa de opinião visa ser aplicada em diversas cidades do Brasil, abordando pessoas em locais públicos. Os dados coletados são automaticamente armazenados em um arquivo .csv (continuamente atualizado) para análises futuras. Para escrever o código utilizamos o [paradigma orientado a objetos (POO)](https://docs.python.org/pt-br/3/tutorial/classes.html)


## FERRAMENTAS UTILIZADAS 

<img src="https://user-images.githubusercontent.com/40433498/174687677-f42a2f52-1b0f-4f8d-ba9d-316e6d019c5f.png" width="50" height="50" /> <img src="https://user-images.githubusercontent.com/40433498/174687676-5d40a2fe-4b62-4fa1-a1fe-20737a1878f8.png" width="50" height="50" /> <img src="https://user-images.githubusercontent.com/40433498/174687678-7ea56222-a00e-4886-a63d-d4214221f8ca.jpg" width="50" height="50" />



## BIBLIOTECA UTILIZADA 

<img src="https://me315-unicamp.github.io/aulas/imgs_aula11/pandas.png" width="50" height="50" />



## 💻FUNCIONAMENTO 

Ao iniciar o programa, é apresentado uma breve explicação sobre a pesquisa e como é possível encerrar a aplicação. Em seguida, o usuário deve digitar a sua idade (utilizando apenas números):
* Caso digite '00', aparecerá uma mensagem de agradecimento e o questionário será finalizado;
* Caso digite uma idade entre 1 e 15 anos aparecerá uma mensagem informando que no Brasil uma pessoa é apta a se tornar eleitor(a) apenas a partir dos 16 anos de idade. Assim, como nossa pesquisa é destinada para pessoas que são já eleitores(as) a pesquisa também será finalizada;
* Ao digitar uma idade válida (entre 16 e 100 anos), será imediamante registrado a data e o horário naquele momento.

Logo em seguida, o usuário deve informar qual o gênero que se identifica. Para isso, deve digitar o número que corresponde a opção escolhida: '1','2','3' ou '4'. A pesquisa só irá avançar ao ser digitado uma opção válida, caso contrário é solicitado que o usuário verifique sua resposta e tente novamente. 

![image](https://cdn.discordapp.com/attachments/998027176605646848/1001698133417406524/Screenshot_2.png)


Essa mesma estrutura de loop foi aplicada nas 5 perguntas da pesquisa, de forma que é aceito apenas os inputs '1', '2' ou '3' como válidos. Ao término da última pergunta, o usuário recebe uma mensagem de agradecimento e um novo loop é acionado iniciando a pesquisa novamente para o próximo usuário.  

Todas as respostas obtidas são armazendas em um dicionário que será salvo quando o código for finalizado ao ser digitado '00' no campo idade. É somente nesse momento que será criado (ou atualizado) o arquivo csv.

No código será encontrado:

* classes, atributos e métodos (ex: construtor);
* listas e dicionário;
* estrutura de repetição: while e for;
* estrutura de condição: if, elif, else;
* biblioteca [pandas](https://pandas.pydata.org/) - para manipulação do arquivo csv;
* função [datetime.now](https://docs.python.org/pt-br/3/library/datetime.html);
* função [time.sleep]( https://docs.python.org/3/library/time.html);
* função [path.exists](https://docs.python.org/3/library/os.path.html).


Para visualizar os dados da pesquisa foi criado um dashboard com Power BI em que é possível filtrar as respostas de acordo com o gênero dos entrevistados:

![image](https://cdn.discordapp.com/attachments/998027176605646848/1001698133849415782/Screenshot_3.png)




## 💡 COMO EXECUTAR O PROJETO? 

**1º passo: o usuário deverá fazer o clone do repositório:** 
* No GitHub navegue até a página inicial do repositório;
* Copie a URL: https://github.com/AmandaAlR/Projeto_2_Resilia.git
* Abra o seu Git Bash;
* Selecione o local onde deseja ter o repositório clonado e digite:
```shell
git clone https://github.com/AmandaAlR/Projeto_2_Resilia.git
```
* Pressione enter para criar o seu clone local.


* Em caso de dúvidas, por favor acesse a documentação:
```shell
https://docs.github.com/pt/repositories/creating-and-managing-repositories/cloning-a-repository
```


**2º passo: criar seu ambiente virtual (no sistema Windows):**
* Digite o seguinte comando no terminal:
```shell
-m venv (nome_do_seu_ambiente_virtual)
```
* Porém, se as variáveis PATH e PATHEXT não estiverem configuradas, você provavelmente terá que digitar o caminho completo no terminal, por exemplo:

```shell
C:\Users\Name\AppData\Local\Programs\Python\Python310\python -m venv (nome_do_seu_ambiente_virtual)
```



**3º passo: ativar o seu ambiente virtual:**
* Se estiver utilizando o prompt de comando do Python, digite:
```shell
.\(nome_do_seu_ambiente_virtual)\Scripts\activate.bat
```
* Se estiver usando o PowerShell, digite:
```shell
.\(nome_do_seu_ambiente_virtual)\Scripts\activate.ps1
```
* Em seguida aparecerá no terminal o nome do seu ambiente virtual e ele estará ativado!




**4º passo: instalar no ambiente virtual os pacotes utilizados no projeto:**
* Execute o comando no terminal:
```shell
pip install -r requirements.txt 
```
* Automaticamente o gerenciador de pacotes baixará a biblioteca Pandas (será instalada somente no seu ambiente virtual).

**5º Se quiser desativar o seu ambiente virtual:**
* Digite o comando:
```shell
deactivate
```

**Caso necessário, acesse a [documentação ofical do Python sobre ambientes virtuais](https://docs.python.org/pt-br/3/library/venv.html).**


## 🤝 DESENVOLVEDORES


![image](https://media.discordapp.net/attachments/998027176605646848/1001698496065314836/Screenshot_4.png?width=1194&height=671)


###### Aline Gomes - Gestora de gente e engajamento 

[![Linkedin Badge](https://img.shields.io/badge/-LinkedIn-blue?style=flat-square&logo=Linkedin&logoColor=white&link=https:https://www.linkedin.com/in/aeogomes/)](https://www.linkedin.com/in/aeogomes/)

###### Amanda Alves - Gestora de Conhecimento 

[![Linkedin Badge](https://img.shields.io/badge/-LinkedIn-blue?style=flat-square&logo=Linkedin&logoColor=white&link=https:https://www.linkedin.com/in/amandaalvesres/)](https://www.linkedin.com/in/amandaalvesres/)

###### Carol Candeias - Colaboradora 

[![Linkedin Badge](https://img.shields.io/badge/-LinkedIn-blue?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/ana-carolina-candeias-ba328216a/)](https://https://www.linkedin.com/in/ana-carolina-candeias-ba328216a/)

###### Carlos Henrique - Colaborador 

[![Linkedin Badge](https://img.shields.io/badge/-LinkedIn-blue?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/carlos-augustin/)](https://www.linkedin.com/in/carlos-augustin/)

###### Karolina Juliana - Co-Facilitadora 

[![Linkedin Badge](https://img.shields.io/badge/-LinkedIn-blue?style=flat-square&logo=Linkedin&logoColor=white&link=https:https://www.linkedin.com/in/kjcsilva/)](http:https://www.linkedin.com/in/kjcsilva/)
















          




