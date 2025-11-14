

## Funcionalidades

O sistema implementa:

- **Depósito**
- **Saque**
- **Extrato**
- **Cadastro de Usuário**
- **Cadastro de Conta Corrente**
- **Listagem de Contas**

---

## Regras do Projeto

### Depósito
- Recebe argumentos **somente por posição**.
- Não aceita valores negativos.

### Saque
- Recebe argumentos **somente por nome**.
- Limite de saques diários.
- Limite de valor por saque.
- Verificação de saldo.

### Extrato
- Exibe todas as movimentações.
- Argumentos híbridos (positional only + keyword only).

### Usuário
- Contém:
  - Nome
  - Data de nascimento
  - CPF (somente números)
  - Endereço completo
- Não permite usuários com o mesmo CPF.

### Conta Corrente
- Agência fixa: **0001**
- Número da conta gerado automaticamente (sequencial)
- Um usuário pode ter várias contas.

---

## Estrutura do Projeto

Arquivo principal:

- `Projeto_sistema_bancario.py`

Todas as funções estão organizadas de forma modular, deixando o sistema mais limpo e fácil de manter.

---

## Como executar

No terminal:

```bash
python Projeto_sistema_bancario.py
```


