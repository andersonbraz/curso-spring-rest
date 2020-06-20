# Curso Spring Rest da Algaworks

Avaliação de Conteúdo do Curso de Spring Rest da Algaworks

## Dia 01 - Implementando uma REST API com Spring

O video disponibilizado possui nos primeiros 10 minutos os testemunhos da galera que fez cursos com a AlgaWorks e conseguiram emprego ou melhora do seu conhecimento. Tem também uso de todos aqueles gatilhos de info produtos nos moldes de uma "Fórmula de Lançamento".

### Para empacotar lembrar de definir Goals com:

```
clean package
```


## Dia 02 - Persistência, Validation e Exception

O video disponibilizado possui nos primeiros 10 minutos os comentários da galera que está fazendo este treinamento e em seguida já passa para a parte de conteúdo exeplicando sobre conexão com banco de dados MySql.

*Para configurar conexão com banco de dados lembrar de definir:*

```
spring.datasource.url=jdbc:mysql://localhost:3306/osworks?createDatabaseIfNotExist=true&serverTimezone=UTC
spring.datasource.username=<<username>>
spring.datasource.password=<<password>>
```

*Script de criação da tabela cliente:*

```sql
create table cliente(
	id bigint not null auto_increment,
	nome  varchar(60) not null,
	email varchar(255) not null,
	telefone varchar(20) not null,
	primary key(id)
);
```

## IMPORTANTE

- [Flyway - Version control your database](http://flywaydb.org)

## Dia 03 - Técnicas e boas práticas

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

## Dia 04 - Alcançando o próximo nível

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

## WARNINGS

Build path specifies execution environment JavaSE-11. There are no JREs installed in the workspace that are strictly compatible with this environment.

**Resolve**

In Spring Tool Suite from your project:

1. Right-click on your project
2. Click Properties
3. Java build path: Libraries; Remove the "JRE System Library[J2SE 1.4]"
4. Click Add Library -> JRE System Library
5. Select the new "Execution Environment" or Workspace default JRE