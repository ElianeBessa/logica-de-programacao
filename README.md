# logica-de-programacao
Introdução a lógica de programação

Os dados lógicos, também conhecidos como tipos booleanos, funcionam como uma base binária para a tomada de decisões em um programa
. De acordo com as fontes, aqui estão os detalhes fundamentais sobre como eles operam:
1. Estados Possíveis
Um dado lógico só pode assumir um de dois estados: verdadeiro (true) ou falso (false)
. No sistema do computador, esses estados são frequentemente representados pelos valores numéricos 1 (verdadeiro) e 0 (falso)
. O nome "booleano" é uma homenagem a George Boole, o matemático que inventou a álgebra binária
.
2. Como esses dados são gerados?
Na programação, os valores lógicos são geralmente o resultado de expressões relacionais (comparações)
. Quando o computador compara dois valores, ele gera uma resposta lógica:
Exemplo: Se você perguntar ao programa se 5 > 3, a expressão retornará o valor verdadeiro
.
Exemplo: Se perguntar se 10 == 2, o resultado será falso
.
3. Operadores Lógicos (Combinação de Condições)
Você pode combinar múltiplos valores lógicos para criar condições mais complexas usando operadores específicos
:
Operador E (AND): O resultado só é verdadeiro se todas as condições envolvidas forem verdadeiras
. Se uma única for falsa, o resultado final é falso
.
Operador OU (OR): O resultado é verdadeiro se pelo menos uma das condições for verdadeira
. Só será falso se todas forem falsas
.
Operador NÃO (NOT): É um "inversor". Ele transforma o que é verdadeiro em falso e o que é falso em verdadeiro
.
4. Utilidade Prática
Os dados lógicos são o "cérebro" das estruturas de controle
:
Estruturas de Decisão (se): O código dentro de um bloco se só é executado se a condição testada resultar em verdadeiro
.
Estruturas de Repetição (enquanto): Um laço de repetição continuará executando enquanto a condição lógica que o controla permanecer como verdadeira
.
Um exemplo prático mencionado nas fontes é um sistema de alarme residencial: o estado de cada sensor de janela (aberta ou fechada) é um dado lógico
. O alarme só dispara se a condição "janela aberta" for verdadeira em qualquer um dos sensores
.
