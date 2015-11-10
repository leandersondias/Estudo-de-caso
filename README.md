#Abrir o livro
livro = open('livro1.txt','r')
#Ler o livro
ler = livro.read()
#Deixar minusculo
minusculas = ler.lower()
#Quebrar os espacos em branco e pontos
quebra = minusculas.split(' ')
quebra2 = minusculas.split(',')
quebra3 = minusculas.split('.')
quebra4 = minusculas.split('#')
quebra5 = minusculas.split('*')
quebra6 = minusculas.split('!')
quebra7 = minusculas.split('?')
quebra8 = minusculas.split('"')
quebra9 = minusculas.split('%')
quebra10 = minusculas.split(':')
quebra11 = minusculas.split(';')
quebra12 = minusculas.split('(')
quebra13 = minusculas.split(')')
quebra14 = minusculas.split('&')
quebra15 = minusculas.split('-')
quebra16 = minusculas.split('+')
quebra17 = minusculas.split('/')
quebra18 = minusculas.split('$')
quebra19 = minusculas.split('<')
quebra20 = minusculas.split('>')
quebra21 = minusculas.split('=')
quebra22 = minusculas.split('@')
quebra23 = minusculas.split('[')
quebra24 = minusculas.split(']')
quebra25 = minusculas.split('_')
quebra26 = minusculas.split('{')
quebra27 = minusculas.split('|')
quebra28 = minusculas.split('}')
quebra29 = minusculas.split('~')
quebra30 = minusculas.split('illustration')
#Quebra linhas
qlin = minusculas.strip()
#Manipulando a lista
#Contando palavras
palavras = len(minusculas)
print 'O eBook possui %d palavras'%palavras
#Contando palavras repetidas
#Tentei mas nao consegui :(
#Procurar lista de palavras no livro
lpalavras = open('palavras.txt', 'r')
linha = lpalavras.readline()
linhaf = linha.strip()
for linhaf in quebra:
    print 'Palavras da lista pre-definida foram encontradas no livro'
    break
#Comparar vocabulario entre livros
livro2 = open('livro2.txt', 'r')
ler2 = livro2.read()
minusculas2 = ler2.lower()
#Quebrar novamente espacos e pontos
quebra = minusculas2.split(' ')
quebra2 = minusculas2.split(',')
quebra3 = minusculas2.split('.')
quebra4 = minusculas2.split('#')
quebra5 = minusculas2.split('*')
quebra6 = minusculas2.split('!')
quebra7 = minusculas2.split('?')
quebra8 = minusculas2.split('"')
quebra9 = minusculas2.split('%')
quebra10 = minusculas2.split(':')
quebra11 = minusculas2.split(';')
quebra12 = minusculas2.split('(')
quebra13 = minusculas2.split(')')
quebra14 = minusculas2.split('&')
quebra15 = minusculas2.split('-')
quebra16 = minusculas2.split('+')
quebra17 = minusculas2.split('/')
quebra18 = minusculas2.split('$')
quebra19 = minusculas2.split('<')
quebra20 = minusculas2.split('>')
quebra21 = minusculas2.split('=')
quebra22 = minusculas2.split('@')
quebra23 = minusculas2.split('[')
quebra24 = minusculas2.split(']')
quebra25 = minusculas2.split('_')
quebra26 = minusculas2.split('{')
quebra27 = minusculas2.split('|')
quebra28 = minusculas2.split('}')
quebra29 = minusculas2.split('~')
quebra30 = minusculas2.split('illustration')
palavras2 = len(minusculas2)
print 'o eBook 2 possui %d palavras'%palavras2
if palavras2 > palavras:
    print 'O eBook 2 possui mais palavras que o eBook 1'
elif palavras2 == palavras:
    print 'O eBook 2 possui a mesma quantidade de palavras que o eBook 1'
else:
    print 'O eBook 1 possui mais palavras que o eBook 2'
