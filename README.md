print("Boa tarde, seja bem vindo ao restaurante Não sei")
print("para começarmos precisamos saber seu nome")
usuario = input("Qual o seu nome?")

print("Espero que goste da sua refeição", usuario)

print( "então vamos para suas opções\n temos pizza e pratos feitos\n para pizza digite 1 para carne digite 2")
opcoes = int(input())


while opcoes < 1 or opcoes >2:
    print("Algo deu errado digite 1 para pizza ou 2 para pratos feitos fisica ")
    opcoes= int(input("pizza \n pratos feitos\n -:"))
    
    if opcoes == 1:
        print("então vamos para os sabores", usuario)
        print(" Musarela (1) \n calabrese(2) \n Bolonhesa(3) \n quatro queijos(4) \n Frango catupiri(5) ") 
        saborp= input("Escolha o sabor da sua pizza com seu respectivo numero: \n : ")
        if saborp == "1":
            print(" Sua pizza de mussarela estara pronta em 30 minutos ")
            print("30 minutes later")
            atoa= input(" podemos trazer para mesa? (Sim ou Não")
            if atoa == "sim" or "Sim" :
                print(" aqui esta seu pedido, boa refeição",usuario, ":)")
            elif atoa == "não" or "Não":
                print("ok", usuario, " iquando quiser é só chamar")
            else:
                print(" quer fazer mais algum pedido?")
                
    elif saborp == "2":  
        print(" Sua pizza de calabresa estara pronta em 30 minutos ")
        print("30 minutes later")
        atoa= input(" podemos trazer para mesa? (Sim ou Não")
        if atoa == "sim" or "Sim":
                print(" aqui esta seu pedido, boa refeição",usuario, ":)")
        elif atoa == "não" or "Não" :
            print("ok", usuario, " iquando quiser é só chamar")
        else:
            print(" quer fazer mais algum pedido?")
             
             
    elif saborp == "3":
        print(" Sua pizza de Bolonhesa estara pronta em 30 minutos ")
        print("30 minutes later")
        atoa= input(" podemos trazer para mesa? (Sim ou Não")
        if atoa == "sim" or "Sim":
                print(" aqui esta seu pedido, boa refeição",usuario, ":)")
        elif atoa == "não" or "Não" :
            print("ok", usuario, " iquando quiser é s´chamar")
        else:
            print(" quer fazer mais algum pedido?")
            
        
    elif saborp == "4":
        print(" Sua pizza de Quatro queijo estara pronta em 30 minutos ")
        print("30 minutes later")
        atoa= input(" podemos trazer para mesa? (Sim ou Não")
        if atoa == "sim" or "Sim" :
                print(" aqui esta seu pedido, boa refeição",usuario, ":)")
        elif atoa == "não" or "Não" :
            print("ok", usuario, " iquando quiser é s´chamar")
        else:
            print(" quer fazer mais algum pedido?")
        
            
    elif saborp == "5":
        print(" Sua pizza de Frango catupiri estara pronta em 30 minutos ")
        print("30 minutes later")
        atoa= input(" podemos trazer para mesa? (Sim ou Não")
        if atoa == "sim" or "Sim":
                print(" aqui esta seu pedido, boa refeição",usuario, ":)")
        elif atoa == "não" or " Não" :
            print("ok", usuario, " iquando quiser é s´chamar")
        else:
            print(" quer fazer mais algum pedido?")
                
        
        
    
if opcoes == "1":
    print("então vamos para os sabores", usuario)
    print(" Musarela (1) \n calabresa(2) \n Bolonhesa, Queijo com presunto(3) \n quatro queijos(4) \n FRanfo catupiri(5) ") 
    saborp= input("Escolha o sabor da sua pizza com seu respectivo numero: \n : ")
           
    if saborp == "1":
            
       print(" Sua pizza de mussarela estara pronta em 30 minutos ")
       print("30 minutes later")
       atoa= input(" podemos trazer para mesa? (Sim ou Não")
       if atoa == "sim" or "Sim":
            print(" aqui esta seu pedido, boa refeição",usuario, ":)")
       elif atoa == "não" or "Não" :
            print("ok", usuario, " iquando quiser é s´chamar")
       else:
           print(" quer fazer mais algum pedido?")
