# Curso de Expressões regulares: capturando textos de forma mágica


João Fulano,123.456.789-00,21 de Maio de 1993,(21) 3079-9987,Rua do Ouvidor,50,20040-030,Rio de Janeiro

Maria Fulana, 98765432100,11 de Abril de 1995,(11) 933339871,Rua Vergueiro,3185,04101-300,São Paulo

denise teste, 987.654.321.00,28 de Dezembro de 1991,(31)45562712,SCS Qd. 8 Bl. B-50,11,70333-900,Rio Grande

Encontrar o cpf nestes três registros de exemplo de um arquivo CSV (Comma-separated Values)

Regex: \d{3}\.?\d{3}\.?\d{3}[-.]?\d{2}

Encontrar a data em extenso

Regex: [0-3]?\d\s*de\s*[A-Z][a-zç]{3,8}\s*de\s*[12]\d{3}