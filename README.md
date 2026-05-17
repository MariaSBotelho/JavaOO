# Guia Rápido — Orientação a Objetos em Java

## Paradigma Procedural
Modelo antigo de programação onde dados e funções ficam separados.  
Pode gerar repetição de código e dificultar manutenção e reutilização.

---

# Orientação a Objetos (OO)
Paradigma que organiza o sistema em objetos que juntam:
- atributos → dados
- métodos → comportamentos

Objetivo:
- reutilização de código
- organização
- manutenção mais simples

---

# Classe
É um molde que define como os objetos serão criados.

Define:
- atributos
- métodos

---

# Objeto / Instância
Objeto é uma criação baseada em uma classe.

Cada objeto possui seus próprios valores e comportamentos.

---

# Atributos
São as características de um objeto.

Exemplo:
- saldo
- nome
- cpf

---

# Métodos
São as ações/comportamentos de um objeto.

Exemplo:
- sacar
- depositar
- transferir

---

# Parâmetros
Valores recebidos por um método para executar alguma ação.

---

# Return
Usado para retornar um valor de um método.

---

# this
Referência para o próprio objeto atual.

Usado para acessar atributos e métodos do próprio objeto.

---

# Referências
Variáveis de objetos armazenam referências para objetos na memória.

Duas variáveis podem apontar para o mesmo objeto.

---

# Composição
Relacionamento onde uma classe possui outra classe dentro dela.

Exemplo:
- Conta possui Cliente

Vantagens:
- melhor organização
- reutilização
- evita repetição

---

# NullPointerException
Erro que acontece quando tentamos acessar algo que não foi inicializado.

Geralmente ocorre quando uma referência está `null`.

---

# Encapsulamento
Técnica usada para proteger os dados do objeto.

Os atributos ficam privados e o acesso é controlado por métodos.

Vantagens:
- segurança
- controle de alterações
- validações

---

# Getter
Método usado para ler/obter o valor de um atributo privado.

---

# Setter
Método usado para alterar/modificar um atributo privado.

---

# Construtor
Método especial executado automaticamente ao criar um objeto.

Usado para inicializar atributos obrigatórios.

---

# static
Indica que algo pertence à classe e não ao objeto.

Todos os objetos compartilham o mesmo atributo ou método estático.

---

# Método Estático
Método que pertence à classe.

Pode ser usado sem criar objeto.

Não utiliza `this`.

---

# Atributo Estático
Atributo compartilhado entre todos os objetos da classe.

---
