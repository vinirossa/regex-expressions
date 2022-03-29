# Useful Regex Expressions

[a-z] = letras minúsculas

[A-Z] = letras maiúsculas

[\d] = números

[àèìòùáéíóúâêîôûäëïöüãõ] = letras minúsculas e maiúsculas acentuadas

[\p{Letter}] = letras minúsculas e maiúsculas acentuadas e cedilha

[ç] = cedilha

[`´^~¨] = acentos

[.:,;\-_<>=+*!?)(}{|''""\][\\/] = sinais de pontuação

[@#$%&] = símbolos

[\s] = espaços

[\n] = quebras de linha

(?![ -~ç´¨àèìòùáéíóúâêîôûäëïöüãõ\n]). = caracteres non-unicode

[^\p{Letter}\d`´^~¨.,;\-_<>=+*!?)(}{|'"\][\\/@#$%&\s\n] = caracteres non-unicode

[a-zA-Z\dàèìòùáéíóúâêîôûäëïöüãõç`´^~¨.:,;\-_<>=+*!?)(}{|'"\][\\/@#$%&\s\n]

[\p{Letter}\d`´^~¨.:,;\-_<>=+*!?)(}{|'"\][\\/@#$%&\s\n]
