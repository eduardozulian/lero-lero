O Fabuloso Gerador de Lero-Lero para WordPress
=========

O Fabuloso Gerador de Lero-Lero para WordPress permite que você insira rapidamente pedaços de _dummy text_ em posts, páginas ou até mesmo em seu template. Assim, você pode dar um descanso pra esse Lorem Ipsum manjado.

Este plugin é baseado no [Fabuloso Gerador de Lero-Lero](http://www.suicidiovirtual.net/dados/lerolero.html).


## Como usar

Por enquanto, o plugin trabalha através dos _shortcodes_ do WordPress.

### Funcionamento padrão

Sem atributos, são retornados cinco parágrafos, cada um com quatro frases.

        [lero-lero]

É possível também usar uma versão alternativa, sem hífen:

        [lerolero]

### Com atributos

Um parágrafo, usando o valor padrão de quatro sentenças

        [lero-lero p="1"]

Três parágrafos com três sentenças cada

        [lerolero p="3" s="3"]

Um parágrafo, uma sentença

        [lerolero s="1" p="1"]

Sete frases em um parágrafo

        [lerolero s="7" p="1"]
         
### Em um template WordPress
Você pode usar a função [`do_shortcode`](http://codex.wordpress.org/Function_Reference/do_shortcode) em seus templates do WordPress usando o seguinte comando: 
 
 ```php
 echo do_shortcode( '[lero-lero p=2 s=1]' );
 ```
