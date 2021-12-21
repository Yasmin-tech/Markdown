# Tutorial Markdown
### **Tamanho da fonte**
#### Para você escrever em tamanhos de fontes diferentes, será necessário o uso da hashtag (#) no começo da sentença, como o uso do h1 no html. Quanto mais hastags colocadas no inicio da setença, menor a fonte. No HTML o h1 é usado para cabeçalhos e títulos, em Markdown o uso de uma única hashtag tem a mesma função. 
#### Código:
```Markdown
# Titulo
## Titulo
### Titulo
```
#### Resultado: 

# Titulo 
## Titulo
### Titulo
---
### **Divers - Divisores**
#### Para você marcar uma divisão, é usado três tracinhos (---) ou três asterístico (***)
---
### **Enfâse**
#### Para se dar enfâse em uma sentença, coloque-a entre asterísticos (*) sem nenhum espaço. 
#### Código:
```Markdown
*texto*
```
#### Resultado:
*texto*
---
### **Strong - Negrito**
#### Para colocar em negrito, coloque a sentença entre asterísticos duplos (**) sem nenhum espaço. 
#### Código: 
```markdown
**texto**
```
#### Resultado:
**texto**
---
### **Italic - Itálico**
#### Para se colocar em itálico, coloque a sentença entre inderline (_) sem espaço nenhum.  
#### Código:
```Markdown
_texto_
```
#### Resulatdo:
_texto_
---
### **Lista Ordernada**
#### Para se criar uma lista ordernada, digite um número e logo em seguida um ponto(.), que ao decorrer de seu arquivo, a lista será criada automaticamente. 
#### Código: 
```markdown
 1. 
 1.
 1.
```
#### Resultado: 
1.
1.
1.
---
### **Lista não ordenada**
#### Para criar uma lista não ordenada, coloque um asterístico (*) ou um tracinho (-) no começo.
#### Código: 
```Markdown
* Lista
```
#### Resulatdo: 
* Lista

---
### **Lista com Checkbox**
#### Para se criar uma lista com checkbox ou com marcações, coloque colchetes após o arterístico (*) ou o tracinho (-). 
#### Código: 
```Markdown
* []Item 1
```
#### Resultado:
* [] Item 1

#### E para marcar a caixinha coloque um "x" entre os colchetes. Ex: 
#### Código: 
```Markdown
*[x] Item 1
``` 
#### Ex: 
* [x] item 1

---
### **Citação**
#### Para criar uma citação coloque "> " no ínicio da sentença. 
#### Código: 
```Markdown
> citação
```
#### Ex:
> citação
---
### **Inline Code **
#### Para colocar uma linha de um código, digite o mesmo dentro de uma crase.
#### Código: `Yarn install´
#### Ex:
`yarn install`

---
### **Code Block **
#### Para escrever um bloco de código use três cases e logo dos três primeiros cases, coloque a linguagem em que se encontra o código.
 ```javascript
 if(n >1){
     document.write("Positivo");
 }
 else{
     document.write("Negativo");
 }
```

---
### **Tabelas**
#### Para a criação de tabelas, use o pipe (|), para dar forma a sua tabela e use |-| para separar o cabeçalho e o corpo da tabela.
#### Código: 
```Markdown
 | Nome | Idade |
 | - || - |
 | Yasmin | 18 |
```
#### Resultado:

| Nome | Idade |
| - | - |
| Yasmin | 18 |
---
### **Inserir  link**
#### Para inserir um link você terá que atribuir a uma palavra ou frase o link para onde será direcionado ao ser clicado, colocando-a dentro de conchetes e em seguida colocar entre parênteses o link e se quiser, pode ser colocado um título para aquele link entre aspas.
#### Código:
```markdown
[Clique aqui oara acessar o link](https://www.google.com/ "Google")
```
### Resultado:
[ Clique aqui para acessar o link](https://www.google.com/ "Google")

---
### **Inserindo imagens**
#### O código para se inserir imagem é bem parecido com o do inserir link, a única diferença é o ponto de exclamação (!) no início. Também é precico colocar o endereço da imagem entre parênteses.
#### Código:
```markdown
![](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQ116J-Ewb6FmilXc5zyLYP5oIhptdEKW8blCese_UKGFt1AvX1m_04xdmMbeGUW-NDl-I&usqp=CAU)
```
#### Resultado:
![](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQ116J-Ewb6FmilXc5zyLYP5oIhptdEKW8blCese_UKGFt1AvX1m_04xdmMbeGUW-NDl-I&usqp=CAU)




















