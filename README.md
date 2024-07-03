
Nesse projeto estou automatizando um processo de verificação de uma base de dados em uma planilha do Excel se o cliente estiver em atraso ou em dia com os pagamentos.
1- O Código Entrar na planilha fornecida pelo cliente onde contém NOME, VALOR, CPF, VENCEDOR, STATUS e extrair o cpf do cliente
2- Entrar no site que o cliente usa para consultar https://consultcpf-devaprender.netlify.app/ e usar o cpf da planilha para consultar o status do pagamento de cada cliente
3- verificar se o pagamento está "em dia" ou "atrasado"
4- Se estiver "em dia", pegar os dados do pagamento e o método de pagamento foi pago no (cartão ou boleto)
5- Caso contrário (se estiver atrasado), colocando o status como pendente
6- Inserir essas informações (NOME, VALOR, CPF, VENCEDOR, STATUS e caso esteja em dia, DADOS DE PAGAMENTO, MÉTODO DE PAGAMENTO (cartão ou boleto)) em outra planilha de fechamento.
A automação abre a Tabela de base de dados dos clientes, pega o CPF do primeiro cliente, abre o site de consulta e verifica se o cliente está com o pagamento "em dia" ou em "atraso".
Se o cliente estiver "em dia" automaticamente pega as informações de DADOS DE PAGAMENTO e MÉTODO DE PAGAMENTO e adiciona essas informações em outra planilha de fechamento do mês onde será possível verificar quais clientes estão com pendências e quais estão em dia.
Se o cliente estiver em "atraso" a automação pega os dados iniciais do cliente e adiciona na planilha de fechamento conforme pendente.
E ele repete este mesmo processo para todos os clientes da base de dados.
###############DADOS FICTÍCIOS##############


![Consulta-de-Status-por-CPF](https://github.com/hiury-kawai/Automa-o/assets/70663979/1d98448c-39e9-4059-9ac7-6f46bd26cca5)
![Consulta-de-Status-por-CPF (1)](https://github.com/hiury-kawai/Automa-o/assets/70663979/8a4a4d82-7314-48a6-8a99-831a54f4a2d0)

