# Desafio-Ramsonware
Desafio de curso DIO
- Neste desafio, criei dois arquivos python, onde basicamente um criptografa um arquivo e outro descriptografa.
- No arquivo de criptografia, primeiro dou instruções para abertura de leitura do arquivo alvo e captura uma variavel todo o seu conteudo. Com esse conteudo salvo, excluo o arquivo para que a "vitima" nao tenha mais acesso ao arquivo original. Logo depois criptografo esse arquivo, utilizando a biblioteca "pyaes" para criptografar o arquivo, com base numa chave de 16 bits. Concluido com exito esta tarefa, crio um novo arquivo contendo o conteudo do arquivo original criptografado, impossibilitando de ser lido.
- No arquivo de descriptografia, faço o caminho inverso. Novamento leio o arquivo e extraio o conteudo dele, desta vez criptografado. Novamente excluo o arquivo atual para logo após passar pela descriptografia, com base na mesma chave de 16 bits usada para criptografa-lo. Para concluir crio um novo arquivo contendo o conteudo descriptografado legivel novamente.

- Este desafio mostra o quao simples é criar um arquivo de criptografia, capaz de roubar seus dados e serem feito deles o que quiser pelo atacante. Devemos nos alertar, principalmente pela engenharia social, onde é o meio mais comum de ser atacado com exito.
