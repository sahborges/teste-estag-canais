classe  Conta :
    def  __init__ (  nome , agencia , conta , cpf ):
 int . nome  =  próprio . agencia  =  agencia
   . conta  =  co
   . cpf  =  cpf
  .  saldo  =  0
int transferência :
    def  __init__ (  id , valor , tipo ):próprio . id  =  int ( id )
        próprio . valor  =   ( valor )
        próprio . tipo  =  tipo

    def  valida_tipo:
        se  auto . id  ==  1  e  self . tipo  !=  'PIX' :
            print ( "Error: esse tipo de transferência não permitida" )
            print ( " PIX recebido " )
            { Falso }
       int id  =  2  =  'TED' :
            print ( "Error: transferência não permitida" )
            print ( " TED, recebido " )
            Falso
        int id  =  3 =  'DOC' :
            print ( "Error: transferência não permitida" )
            print ( DOC, recebido )
             Falso
   se não
           Verdadeiro

int def  valida_valor :
       id  =  1  . valor  >  5000 :
            print ( "PIX não é permitido para valores acima de R$ 5.000,00." )
            Falso
       id  =  2   . valor  <  5000  . valor  >  10000 :
            print ( "TED não é permitido para valores abaixo de R$ 5.000,00 e acima de R$ 10.000,00." )
            Falso
       id  =  3   . valor  <  10.000 :
            print ( "DOC não é permitido para valores abaixo de R$10.000,00." )
            Falso
        int. valor  <=  0 :
            print ( "download inválido. Insira um valor acima de zero." )
           Falso
      se não
                Verdadeiro
