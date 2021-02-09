# E-SUS Evento Adverso a Vacina SMS PMPL

Script feito para ajudar na identificação de casos novos do site Notifica-VE do DataSUS.

Para evitar o retrabalho de ficar analisando todos os casos gerados pelo arquivo csv do sistema,
criei esse script que identifica os casos novos com base na numeração do paciente. Após finalizada a execução é feito o download de uma cópia local,
e também é feito o envio automático por e-mail para os usuários cadastrados no arquivo credentials.json armazenado no meu drive.
