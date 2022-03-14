# restaurante

print("Boa tarde, seja bem vindo ao restaurante Não sei")
print("para começarmos precisamos saber seu nome"


print("Espero que goste da sua refeição", usuario)

print( "então vamos para suas opções", usuario, ("\n temos pizza e pratos feitos\n para pizza digite 1 para carne digite 2")
opcoes = int(input())


while opcoes < 1 or opcoes >2:
    print("Algo deu errado digite 1 para pizza ou 2 para pratos feitos fisica ")
    pessoa= int(input("pizza \n pratos feitos\n -:"))
    
    if pessoa == 1:
        print("então vamos para suas opções", usuario)
        int(input())
    
    elif pessoa == 2:
        nome = input("Digite seu nome completo\n -:")
        cpf= input("Digite seu CPF\n-:")
        print("Cadastro feito com sucesso aqui estão seus dados cadastrados")
        print("Nome\n", nome, "\nCPF\n" , cpf)
        
if pessoa == 1:
        nomef= input("Insira seu nome fantasia\n-:")
        razao= input("Razão social\n-:")
        cnpj= input("Digite seu CNPJ\n-:")
        print("Cadastro feito com sucesso aqui estão seus dados cadastrados")
        print("Nome fantasia\n", nomef, "\n Razão social\n",razao, "\nCNPJ\n",cnpj)
    
elif pessoa == 2:
    nome = input("Digite seu nome completo\n -:")
    cpf= input("Digite seu CPF\n-:")
    print("Cadastro feito com sucesso aqui estão seus dados cadastrados")
    print("Nome\n", nome, "\nCPF\n" , cpf)
