# Delphi-SelecaoDeRestaurante

# Requisitos de ambiente necessários para compilar e rodar o software
    Sistema operacional windows xp ou superior
    Delphi 5 ou superior
    DevExpress
    
# Instruções de como utilizar o sistema
    O sistema abre na tela de Seleção de restaurante
    O usuário informa o seu nome no campo "Digite seu nome"
    O usuário inicia a votação
      Caso o usuário já tenha realizado votação nesse dia, então o sistema exibe uma mensagem informativa de que o usuário já realizou a votação do seu restaurante e a operação é abortada.
      Caso o usuário não tenha informado o nome no campo "Digite seu nome", então o sistema exibe uma mensagem informativa de que o campo de nome não foi preenchido e a operação é abortada.
    O usuário verifica se o seu restaurante favorito já está na listagem de votações.
      Caso o seu restaurante favorito não esteja na listagem de restaurantes, então o usuário pode inserir o seu restaurante através do botão de inserção localizado acima da grade de informações de restaurantes.
        O restaurante somente será aceito como válido caso ele não tenha sido escolhido ainda na semana de votação.
      Caso o seu restaurante favorito já esteja na listagem de restaurantes, então o usuário pode votar nesse restaurante através de clique no botão localizado na coluna de votos registrados para o restaurante em questão.
    Os votos somente podem ser efetuados até antes do meio dia.
    O resultado do dia e dos outros dias da semana pode ser evidenciado através de verificação no botão de Resumo semanal, onde é exibida uma grade de informações com os restaurantes vencedores e o restaurante mais votado até o presente momento.
      
# O que vale destacar no código implementado?
  Código bastante simples para manutenibilidade, utilizando padrões de responsabilidade única, entre outros, e de fácil entendimento.
  
# O que poderia ser feito para melhorar o sistema?
  O sistema poderia ser um App por exemplo, com opções de extensão de resultados e interatividade com redes sociais, entre outros.
