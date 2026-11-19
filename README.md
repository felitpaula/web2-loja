# Explicação do Like

Se o usuário digitar   ' OR '1'='1, sem o ?, o texto vira parte do comando, o que permitiria ao usuário conseguir todos os registros, Aalém de que com outra entrada poderia até ler outras tabelas e apagar dados. Com o ?, o comando já é montado antes do valor chegar e o texto é tratado como texto e nada mais.