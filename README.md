meme_dict = {
            "CRINGE": "Garip ya da utandırıcı bir şey",
            "LOL": "Komik bir şeye verilen cevap",
            "GTG": "gıtmem lazım",
            "RN": "su anda",
            "GNG": "gang, ortak, bro"
            "GN": "iyi geceler"
            "COOKED": "bittin"
            "ROASTED"
            }
word = input("Anlamadığınız bir kelime yazın (hepsini büyük harflerle yazın!): ")
if word in meme_dict.keys():
    print(meme_dict[word])
else:
    print("bu sozun anlamını bılmıyoruz")
