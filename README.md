# Atividade: Implementação de Conectivos Lógicos em Python

## Descrição
Este repositório contém cinco códigos Python que necessitam de correção. Cada código tem um problema a ser resolvido com o uso de conectivos lógicos adequados. Seu objetivo é corrigir os códigos, testar e enviar as correções por meio de um pull request.

## Enunciados das Questões

### Questão 1: Parque de Diversões
Em um parque de diversões, um brinquedo tem os seguintes requisitos: a criança deve ter pelo menos 1,20m de altura **e** ter no mínimo 10 anos de idade. Complete o código abaixo:

```python
altura = float(input("Digite sua altura em metros: "))
idade = int(input("Digite sua idade: "))

if altura >= 1.20 ___ idade >= 10:
    print("Você pode entrar no brinquedo!")
else:
    print("Desculpe, você não atende aos requisitos.")
```

### Questão 2: Promoção de Loja
Uma loja oferece desconto se o cliente comprar mais de 5 itens **ou** se o valor total da compra for superior a R$100. Complete o código abaixo:

```python
quantidade_itens = int(input("Quantos itens você comprou? "))
valor_total = float(input("Qual foi o valor total da compra? "))

if quantidade_itens > 5 ___ valor_total > 100:
    print("Você recebeu um desconto!")
else:
    print("Sem desconto desta vez.")
```

### Questão 3: Acesso ao Sistema
Um usuário só pode acessar um sistema se fornecer a senha correta **e** estiver cadastrado. Complete o código abaixo:

```python
senha_correta = "1234"
usuario_cadastrado = True

senha = input("Digite sua senha: ")

if senha == senha_correta ___ usuario_cadastrado:
    print("Acesso permitido.")
else:
    print("Acesso negado.")
```

### Questão 4: Sensor de Temperatura
Um sistema de segurança ativa um alerta se a temperatura for maior que 50°C **ou** menor que 0°C. Complete o código:

```python
temperatura = float(input("Digite a temperatura atual: "))

if temperatura > 50 ___ temperatura < 0:
    print("Alerta! Temperatura fora dos limites seguros.")
else:
    print("Temperatura dentro dos limites normais.")
```

## Como Configurar o Git

Se você ainda não configurou o Git na sua máquina, siga os passos abaixo:

1. Configure seu nome de usuário:

   ```sh
   git config --global user.name "Seu Nome"
   ```

2. Configure seu e-mail:

   ```sh
   git config --global user.email "seuemail@example.com"
   ```

3. Verifique se a configuração foi aplicada corretamente:

   ```sh
   git config --global --list
   ```

## Como Clonar o Repositório e Enviar a Correção

1. Clone este repositório para sua máquina:

   ```sh
   git clone <URL_DO_REPOSITORIO>
   ```

2. Acesse a pasta do repositório:

   ```sh
   cd nome-do-repositorio
   ```

3. Crie uma nova branch para sua correção:

   ```sh
   git checkout -b minha-correcao
   ```

4. Faça as alterações necessárias nos arquivos e teste os códigos.

5. Adicione os arquivos modificados ao commit:

   ```sh
   git add .
   ```

6. Faça o commit das alterações:

   ```sh
   git commit -m "Correção dos conectivos lógicos nos códigos"
   ```

7. Envie a branch para o repositório remoto:

   ```sh
   git push origin minha-correcao
   ```

8. Acesse o GitHub e abra um Pull Request para que suas alterações sejam analisadas.

---

Após concluir todas as etapas, aguarde o feedback sobre suas correções. Bom trabalho!
