# Novas Funcionalidades

    O projeto com as novas funcionalidades utilizou-se da base ja criada pelo vídeo já disponibilizado pelo email.

# Consideraçãoes iniciais
Para o correto funcionamento do projeto, é preciso que se altere o item config.py com email (gmail) e senha do usuário,
pois eu considerei que um usuário (adm) enviará um email com seu email de usuário para outra pessoa (fictícia), em que essa
pessoa fictícia receberá as instruções das funcionalidades. Além disso, para o correto funcionamento do teste, é preciso
desativar a verificação em duas etapas no gmail e ativar o acesso a app menos seguro na aba "segurança". É preciso também, 
ativar a opção IMAP na aba "encaminhamento e POP/IMAP". É preciso tudo isso pois seá usado o acesso ao email (admin) para 
enviar as requisiçoes para o email do usuário fictício.

# As funcionalidades

    Foiram implementadas as funçoes de "Nome, E-mail, Tarefa e descrição", em que após preenchidos, será enviado um 
email para uma determinada pessoa fictícia (pensei numa pessoa que trabalha numa empresa, por exemplo). Então,
esse email carregará o nome e amail da pessoa (adimin) que enviará as instruções. As instruções são a tarefa
ou tipo de tarefa e a descrição dessa tarefa, ou seja, instruçoes de como fazer ou resolver aquela determinada 
tarefa passada pelo usuário admin. O espaço "Email" a ser preenchido será com o email do usuário fictício.

    No corpo do email terá a segunte menssagem:
    
    "Nome do admin" com o email "email do admin" te enviou a seguinte tarefa:

                Tarefa: "Tarefa ou tipo de tarefa"

                Descrição: "Descrição da tarefa"

