#Criação de Apis Rest com RUST Lang
 - primeiro passo, escolher o framework interface web
 - É necessário instalar o compilador de C++/Gcc por conta do linker que vem empacotado com
 o compilador;
 - PrintLn é uma macro não uma função, quando chamamos uma macro no rust utilizamos !
 após o comando para o compilador identificar;
 - macros são similares a funções;
 #Ownership & Borrowing
 - Referenciar = Emprestar, quando se trata de variaveis, Rust utiliza modelo de emprestimos onde quando você tenta puxar uma variavel com outra função ele vai pegar emprestado temporariamente aquele valor.
 - variaveis mutaveis e imutaveis, similar a constante e variavel, para algo ser realmente variavel ou mutavel precisa ser especificado com prefixo mut.
 - 