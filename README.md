# FormasGeometricasPOO
Trabalho II de POO - Formas Geométricas

O trabalho consiste na implementação da seguinte hierarquia de classes para representar formas geométricas.
Os nomes das classes estão português.

Toda forma possui uma localização no espaço, isto é, o ponto de referência que define onde ela se encontra.
Defina uma classe chamada Ponto para esse propósito.
Todas as formas geométricas devem sempre possuir valores consistentes durante todo o seu tempo de vida. 
Toda forma 2D deve possuir um método para avaliar sua área.
Toda forma 3D deve possuir um método para avaliar seu volume.
As classes Shape, TwoDimensionalShape e ThreDimensionalShape devem ser abstratas, pois não há sentido na instanciação direta de objetos dessas classes.
Em outras palavras, elas sercem apenas como base para a definição de outras classes.
Sobrecarregue os operadores de adição (+) subtração (-)  e comparação (<, <=, >, >=, ==).
Os operadores de adição (+) e subtração (-) quando operarados sobre objetos do mesmo tipo e devem retornar um novo
objeto correpondendo a soma ou subtração das áreas (para formas 2D) e volumes (para formas 3D).
Quando acrescidos/decrementado de um valor constante, deve retornar um novo objeto com a nova área (se 2D) ou volume (se 3D).
Os operadores relacionais devem ser capazes de comparar um objeto com o outro quanto a área (2D) e volume (3D),
mesmo que sejam objetos de diferentes tipos. Sobrecarregue também o operador de extração de stream (<<) para 
formatar a saída de dados associado a um objeto. 
Por fim, dado uma lista de formas 2D ou 3D seu programa deve disponibilizar funções para descobrir qual 
a maior forma (em termos de área ou volume), bem como a área ou volume total ocupado por elas.
Crie construtores e destrutores apropriados para todas as classes.
Seu programa principal deve explorar a funcionalidade implementada na hierarquia, a fim de testa-la.

