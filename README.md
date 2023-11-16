# testes-unitarios-07: Multa? Que multa seu guarda?

- Da mesma forma como validamos os cenários onde tudo acontece como previsto, devemos validar os cenários onde as coisas não andam exatamente como gostaríamos.
- No código abaixo existe um cenário onde a service lança um 404 quando o usuário não é encontrado com a propriedade `licenseId`.
- ➡️ Implemente os testes do arquivo `unit/infractions.test.ts` usando o `spyOn` para mockar os respectivos comportamentos dos repositórios.
    - A implementação já possui alguns testes de integração para que você possa entender a regra de negócio básica.