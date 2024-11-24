# Jogo-soma-dos-jogos
Esse jogo foi o início dos meus códigos em Swift, é basicamente um mini jogo que ainda precisa de vários reajustes mas que você consegue interagir bem.

echo "# Jogo-soma-dos-jogos" >> README.md 
git init 
git add README.md 
git commit -m "primeiro commit" 
git branch -M main 
git remote add origin https://github.com/Alisonxz/Jogo-soma-dos-jogos.git
 git push -u origin main



// jogo simples como demonstração de interação com CLI

             
 print("__Bem vindo ao jogo__")
 
print(" • Você tem que fazer o somatório dos números que aparecem na tela,após você ter escolhido um jogo .")

print("Qual é o seu nome?")
let nome = readLine()


print(" Olá \(nome ?? "amigo" ) esses são os jogos")


print("Escolha um jogo e observe o número que lhe foi atribuído ")

print("1. Braw Star")
print("2. Minecraft")
print("3. Clash Royale ")
print("4. God of our")
print("5. Fifa 24")
let escolha1 = readLine()

var n1 = Int.random(in: 1...100)
print("o numero atribuido ao jogo é \(n1) ")

print("Escolha novamente")
let escolha2 = readLine()

var n2 = Int.random(in: 1...100) 

print("o numero atribuido ao jogo é \(n2) ")

print("Escolha mais um jogo")


let escolha3 = readLine()
var n3 = Int.random(in: 1...100)
print("O número atribuido ao jogo é \(n3)")

print("Qual a soma dos números atribuídos aos jogos ?")
var somaUsuario = Int()
var somaCorreta = n1 + n2 + n3

print("Digite a soma correta !!! ")
var somapessoa = readLine()


if somaUsuario == somaCorreta {
  print("Parabéns você acertou !!!")
} else {
  print(" Você errou a soma correta é \(somaCorreta)" )
}


