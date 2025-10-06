# Tank-Battle-Arena-PVE-PVP-
Simulação de Combate POO em Java: Arena de Battle Tanks (PvE/PvP) – Sistema de gestão e simulação de partidas com regras de dano polimórficas (Tanques Leves, Médios, Pesados, Módulos e IAs).
Integrantes Grupo: 
- Douglas Maurício.
- Eduardo Aragão.
- João Paulo Oliveira.
- Marcos Silva.

**Battle Tanks** é um jogo de simulação de batalhas entre tanques, desenvolvido em Java. O jogo permite batalhas 1v1 ou 3v3, utilizando tanques com diferentes classes e pilotos.  

---

## Funcionalidades

- Escolha de tanques para batalhas.
- Diferentes classes de tanques: Leve, Médio e Pesado.
- Batalha automatizada com turnos.
- Atualização de status dos tanques após cada batalha.
- Menu interativo para escolher modos de jogo e listar status dos tanques.
- Script SQL para popular o banco de dados com tanques.
  
---

## Configuração do Banco de Dados

Antes de rodar o projeto, verifique o usuário e a senha do MySQL no arquivo `Conexao.java`.  
O padrão é:

- Usuário: root  
- Senha: [sua senha local]

Se no seu computador o MySQL usar outro usuário ou senha, altere `Conexao.java` para refletir isso.  

Além disso, rode o script `battle_tanks.sql` dentro da pasta `database` para criar o banco e popular os tanques.

---
## Tecnologias utilizadas
- Java 17
- Maven
- MySQL
- JDBC
