
# JAVA
                                    
## TIPOS DE DADOS EM JAVA

Dá para separarmos isso em 2 grandes grupos, como tipos numéricos e boolean.
Tipos numéricos recebem números dos tipo integrais: byte, short, int long, char.        
E números de casas decimais: float, double.
Valores booleanos, recebe valores de verdadeiro ou falso: boolean.
Também temos os tipos que recebem caracteres como: string e também o char.


 ## ESTRUTURA DE CONDICIONAL


São condições, de estruturas booleanas, que se verdadeiras iram entrar nas instruções definidas, e se falso terá outras instruções. Pode-se usar para coisas onde temos que preparar o programa para coisas como: se acontecer isso se não acontecer isso. síntaxe: **if(se)** **else(se não)**.

int numero = -2;

if (numero > 0) {
  System.out.println("O número é positivo");
} else {
  System.out.println("O número é negativo");
}

 ## SWITCH/CASE

Em ocasiões de muitas condicionais o switch/case entra para reduzir o número de if else para não ficar um código extenso. O switch/case testa o valor contido em uma variável, realizando uma comparação com cada uma das opções. Cada uma dessas possíveis opções é delimitada pela instrução case. Quando o código do case corresponder ele será executado, caso contrário somente o último bloco será executado, sendo chamado de default (padrão).

 ## ESTRUTURA DE REPETIÇÃO

São estruturas onde as intruções serão repetidas até a condição desejada. Temos tipos de repetições como:
**FOR**- Utilizado quando temos um número fixo de iterações necessárias para o loop.Estrutura 
    for (início; condição; incremento/decremento) EX:
    for (int i = 0; i < 10; i++){
    System.out.println(i) -apresenta o valor da variãvel.
    }
Nesse exemplo todas as intruções dentro do for, serão executadas até o i=0 chegar à 10.

**WHILE**- É uma estrutura de repetição, que antes das intruções serem executadas a condição será verificada, se a condição não for correspondida, as intruções não serão executadas.
    int i = 0;
    while (i < 10){
    System.out.println(i)
    i++;
    } 
A instrução será repetida enquanto i for menor do que 10.

**DO/WHILE**-  Diferente do WHILE, o DO/WHILE irá executar as intruções e depois verificar a condição, ou seja, as intruções vão ser executadas pelo menos uma vez antes de ser verificadas.
    int i = 0;
    do {
    System.out.println(i);
    i++;
    } while (i < 10);
Aqui o DO significa faça, e o while seria até (até a condição ser verdadeira).  


 # ANDROID STUDIO

 ## TIPOS DE ELEMENTOS VISUAIS **(view)**  

TextView- Exibe o texto para o usuário;  
EditText- Edita o texto que foi exibido para o usuário;  
ImageView- Utilizado para o tratamento e apresentações de imagens;  
Button- Botões para ser utilizado;  
ListView- Componente que mostra uma lista de informações;  
CheckBox- É um tipo de botão que é selecionado ou não selecionado;  
RadioButton- Permitem ao usuário selecionar uma opção de um conjunto de opções;  
ToggleButton- Permite que o usuário execute duas operações em um único botão;  
Menu- Três barrinhas formado com opções de menu;  
Entre outros.

