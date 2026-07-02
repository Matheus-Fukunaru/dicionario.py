meme_dict = {
            "LOW PROFILE": "Uma pessoa inativa ou q utiliza pouco as redes sociais",
            "GHOSTING": "Sumir do nada em uma conversa",
            "F NO CHAT": "Quando uma situação triste acontece"
            }

word = input("Digite uma palavra moderna que você não entende (escreva todo a palavra em letras maiúsculas): ")

if word in meme_dict.keys():
    print(meme_dict[word])
else:
    print('Essa palavra nem nós conhecemos😣')
