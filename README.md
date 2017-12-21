# cotolengo

Esse aplicativo destina-se a facilitar o trabalho na farmácia e farmácia clínica da Organização Não Governamental Pequeno Cotolengo em Curitiba-PR, e foi feito sem nenhum custo para a entidade.

Esse aplicativo utiliza o kit de ferramentas gráficas GTK+ 3.18.3.
Os bindings do GTK+ 3 com o Python é feito pelo pacote PyGobject.

Para fazer o download do PyGobject siga as instruções no link abaixo (em inglês):
https://pygobject.readthedocs.io/en/latest/getting_started.html

PyGobject está disponível pelo pip, mas todas as dependências devem estar satisfeitas, caso contrário a instalação falhará.

Esse aplicativo utiliza o banco de dados MongoDB 3.4.
Os bindings do MongoDB 3.4 com o Python é feito pelo pacote pymongo 3.5.1.

Para fazer o download do MongoDB, acesse:
https://www.mongodb.com/download-center#community
e escolha a versão do seu sistema operacional.
Esse aplicativo pode ou não ser compatível com a versão mais recente do MongoDB, mas foi testado somente na versão 3.4.
Para fazer o download da versão 3.4, ao entrar no link acima e selecionar o seu sistema operacional, clique em 'All version binaries' para ter acesso a versões anteriores, incluindo a 3.4.

Para fazer o download do pymongo, instale pelo pip digitando no console/terminal:
pip install pymongo==3.5.1

Para instalar no sistema todo em sistemas Unix, pode ser necessário adicionar 'sudo' na frente:
sudo pipo install pymongo==3.5.1

Dúvidas? Mande um e-mail para gidaltijunior@gmail.com com perguntas.
