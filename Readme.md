###FTP FILES
----
Script criado para enviar arquivos via FTP, Todos os arquivos que estiverem com a data do dia vão ser enviados.

###Config.ini

Nome  | Descrição
------------- | -------------
host  | Host FTP
username  | Usuario FTP
password  | Senha FTP
dir	 | Diretorio local
remoto | Diretorio FTP(Deixe em branco se for pasta raiz)

###Exemplo

	[Teste]
	host = 127.0.0.1
	username = luissilva
	password = admin321
	dir = C:\FTP
	remoto = /pasta/
