# Skill para claude e outras IA's para produção de tabela

Antes de abordar sobre a Skill, é importante salientar alguns pontos.\
1 - A IA pode cometer erros, sempre verifique se os dados da tabela criada conferem com os dados que você tem em mãos.\
2 - Não insira bases com a presença de dados sensíveis de acordo com a LGPD.\
3 - Para que possa usar essa skill é necessário que tenha uma conta, independente se paga ou não, do Claude ou de outra IA que possibilita a inserção de skills.\
4 - Instale em seu computador a linguagem R, que é gratuita e pode ser encontrada em: [<img src="https://cran.r-project.org/Rlogo.svg" alt="Descrição" width="20">](https://cran.r-project.org/)


## Como adicionar a Skill no seu claude
- Há duas formas para fazer a inserção da skill na sua conta.

1- Atráves das instruções de um projeto.\
  Você deve criar um projeto no claude com o nome que desejar, recomendo "Criação de tabelas".\
  Em seguida vá em instruções e cole o texto disponível em [Skill.txt](skill.txt).

2 - Através das configurações de uma Skill.\
  Acesse as configurações do se Claude desktop;\
  Vá em recursos e habilite a Pesquisa de Conectores;\
  Após configurado vá na aba skills e clique a adicionar;\
  Escolha a opção de Fazer upload de Skill;\
  Após isso arraste ou procure a skill tabela-cientifica-r.zip que você pode baixar [Tabela.zip](tabela-cientifica-r.zip).
  

## Como testar se funcionou?
Para testar, anexe em uma conversa nova uma tabela no formato xlsx ou csv e peça para criar uma tabela com os dados. Caso a IA não lhe pergunte nada e mostre uma tabela pronta, a Skill não foi ativada, caso ela pergunte como deve proceder nos próximos passos ela foi ativada.\
No caso da não ativação, para que ela seja ativada basta pedir no chat que ela faça a tabela de acordo com a skill tabela científica r.

## Utilizando no Browser 
Caso você utilize a inteligência artificial em um browser, como Chrome, você pode colar o txt nas instruções do projeto e ao final, quando a tabela for criada, você solicita para a tabela ser criada em excel e você irá conseguir baixá-la.
