# smtppatterns.inc
Como manter a reputação e a taxa de entregabilidade da sua infraestrutura de email marketing com PowerMTA? Primeiro, mantenha sua pattern-list atualizada!

PowerMTA usa as pattern-lists para controlar o comportamento das filas de e-mails conforme as respostas enviadas pelos destinos (MXs). Por exemplo, nesse arquivo, uma resposta recebida que contenha a palavra "blacklisted" faz com que a fila de e-mail para aqueie destino seja automaticamente paralisada.

Esse arquivo é criado e mantido pelo administrador do servidor PowerMTA e deve ser constantemente atualizado com novos comportamentos para novas respostas. 

Esse arquivo é usado no modelo de configuração meuemkt. Para saber mais visite http://www.mxemm.com/ ou fale comigo por e-mail: mngr.vps at gmail.com
