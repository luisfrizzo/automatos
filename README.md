Descrição do Autômato (Exercício 3) Aluno: Luis Fernando Figueiredo Frizzo RGM: 35388471

Estados: q0 (inicial), q1, q2, q3 (final)

Alfabeto: {a, b, c}

Transições:

De q0 para q1 com a, b ou c

De q1 para q2 com a, b ou c

De q2 para q3 com a, b ou c

Estado Final: Apenas q3 é estado de aceitação, garantindo que apenas cadeias com exatamente 3 símbolos sejam aceitas.

Esse autômato é determinístico, sem transições vazias, e mínimo para essa linguagem. Ele aceita cadeias como abc, aaa, bca, ccb, etc., e rejeita qualquer cadeia com menos ou mais de 3 símbolos.
