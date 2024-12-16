Aqui está um **README.md** simples e direto para o projeto:

---

```markdown
# 🏠 Consulta de CEP  

Este é um projeto simples em **Python** que realiza consultas de CEP utilizando a API pública do [ViaCEP](https://viacep.com.br/).  

---

## 🚀 Objetivo do Projeto  

O objetivo é permitir que o usuário digite um CEP e receba informações relacionadas, como:  
- Logradouro  
- Bairro  
- Cidade  
- Estado  

Além disso, o programa valida a quantidade de dígitos do CEP e permite realizar novas consultas de forma contínua.  

---

## 🛠️ Como funciona?  

1. O programa solicita ao usuário um **CEP** com 8 dígitos.  
2. Ele envia uma requisição para a **API do ViaCEP**.  
3. Se o CEP for válido, as informações são exibidas no terminal:  
   - Logradouro  
   - Bairro  
   - Cidade  
   - Estado  
4. Caso o CEP seja inválido, o programa informa ao usuário.  
5. Ao final, o usuário pode optar por realizar outra consulta ou sair.  

---

## 📦 Pré-requisitos  

- Python instalado (versão 3.6 ou superior).  
- Biblioteca `requests`. Caso não tenha, instale via pip:  
   ```bash
   pip install requests
   ```

---

## ▶️ Como executar  

1. Clone este repositório:  
   ```bash
   git clone https://github.com/seu-usuario/consulta-cep.git
   cd consulta-cep
   ```  

2. Execute o script:  
   ```bash
   python consulta_cep.py
   ```  

3. Digite o CEP quando solicitado e veja os resultados no terminal.

---

## 🧪 Exemplo de Uso  

```plaintext
###########
Consulta CEP
###########

Digite o CEP para consulta: 01001000
==> CEP ENCONTRADO <==
CEP: 01001-000
Logradouro: Praça da Sé
Complemento: lado ímpar
Bairro: Sé
Cidade: São Paulo
Estado: SP
----------------------------------
Deseja realizar uma nova consulta?
1. Sim
2. Não
```

---

## ✨ Tecnologias Utilizadas  

- **Python**  
- **Biblioteca Requests**  

---

## 📝 Licença  

Este projeto está sob a licença **MIT**. Fique à vontade para utilizá-lo e modificá-lo.  
