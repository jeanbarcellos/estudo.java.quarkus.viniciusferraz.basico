_Repositório apenas para estudo_

# Curso: Desenvolvimento Web com Quarkus - Básico

Códigos gerado a partir do curso '**Microsserviços Java com Spring Boot e Spring Cloud**'

<br>

**Descrição:**

Neste curso irei abordar o Quarkus: framework que irá revolucionar o mundo Java e de microsserviços que rodam em nuvem. Quarkus é um framework Open Source mantido pela Red Hat que promete tornar o desenvolvimento em Java divertido, rápido, com utilização de memória incrivelmente baixo e tempo de boot incrivelmente rápido.

É o 'framework' ideal para desenvolvimento de aplicações que rodarão em nuvem: Azure, AWS e Google Cloud.

Trata-se de um curso básico, que tem por finalidade configurar um ambiente completo para desenvolvimento, apresentar o que o Quarkus traz de novidades, criar um CRUD básico para demonstração do seu potencial e ao final compararemos o boot time e a utilização de memória com uma aplicação similar desenvolvida em Spring Boot.

<br>

**Instrutor:**

- [Vinicius Ferraz Campos Florentino](https://www.udemy.com/user/vinicius-florentino/)

**Referências:**

- https://www.udemy.com/course/des-web-quarkus-basico/
- https://github.com/viniciusfcf/udemy-quarkus-basico

<br>
<br>
<br>

---

## Anotações

Adicionar as extensões

```
quarkus-hibernate-orm-panache
quarkus-rest-client-jsonb
quarkus-jdbc-mysql
```

Executar a applicação

```bash
./mvnw quarkus:dev
```

Banco de dados

```bash
docker run --network host -e MYSQL_ROOT_PASSWORD=root -e MYSQL_DATABASE=teste -d --rm mysql:8.0.19
```

Adicionar extensão `Health`

```bash
./mvnw.cmd quarkus:add-extension -Dextensions="io.quarkus:quarkus-smallrye-health"
```
