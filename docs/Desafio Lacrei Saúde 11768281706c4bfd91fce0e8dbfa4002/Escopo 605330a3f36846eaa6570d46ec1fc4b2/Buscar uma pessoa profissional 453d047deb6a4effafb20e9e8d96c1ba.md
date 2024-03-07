# Buscar uma pessoa profissional

Critérios de Aceite: https://miro.com/app/board/uXjVNmWH66w=/?moveToWidget=3458764581387269002&cot=10
Prioridade: ⭐️⭐️⭐️⭐️
Severidade: Média
Status: Done
Tipo de Bug: Acessibilidaade
Tipo de Teste: Funcional

| ID | Caso de Teste | Resultados Esperados | Resultados Obtidos | Passou ou Nao Passou |
| --- | --- | --- | --- | --- |
| Buscar%20uma%20pessoa%20profissional%20453d047deb6a4effafb20e9e8d96c1ba.md | Buscar um pessoa profissional, usando palavras chaves como: medico, trans, medica e gay | Lista de medicos que incluem a palavra chave sera exibida |  |  |
| Buscar%20uma%20pessoa%20profissional%20453d047deb6a4effafb20e9e8d96c1ba.md | Buscar um pessoa profissional, usando palavras chaves como: carro, perna, dor, cabelo e nariz | Mensagem de "Não encontramos o que você procura” sera exibida |  |  |
| Buscar%20uma%20pessoa%20profissional%20453d047deb6a4effafb20e9e8d96c1ba.md | Buscar um pessoa profissional, usando palavras chaves utilizando caracteres especiais  | Mensagem de "Não encontramos o que você procura” sera exibida |  |  |
| Buscar%20uma%20pessoa%20profissional%20453d047deb6a4effafb20e9e8d96c1ba.md | Buscar um pessoa profissional, com campo input vazio | Lista todos os  medicos cadastrados na LS sem filtro de palavra chave sera exibida |  |  |

---

---

**CT008 - Buscar um pessoa profissional, usando palavras chaves como: medico, trans, medica, gay e preta**

- **Nome do caso de Teste: Realizar busca por pessoa profissional atraves do campo Input, utilizando palavras chaves**
- **Objetivo:** Verificar se o campo input busca por profissionais lista os profissionais relacionados com as palavras chaves inseridas no campo
- **Pré-condições:**

1. A PU deverá ja ter feito login na aplicacao
2. A PU deverá estar no link do site:[https://lacreisaude.com.br/](https://lacreisaude.com.br/)
[](https://paciente.lacreisaude.com.br/)

- **Passos:**
1. Identificar campo input “Buscar por profissionais”;
2. Inserir palavras chaves como Ex: “medico, trans, medica e gay ”;
3. Clicar no botão “Pesquisar”;
4. Visualizar a lista de profissionais relacionados com a palavra chave inserida.

- **Resultados esperados:** 
1. O sistema deverá redirecionar para a lista de profissionais relacionados a palavra chave inserida;
- **Resultados obtido:**
    
    1. O sistema redirecionou para a lista de profissionais relacionados a palavra chave inserida;
    
    ![BuscaMedi.gif](Buscar%20uma%20pessoa%20profissional%20453d047deb6a4effafb20e9e8d96c1ba/BuscaMedi.gif)
    

---

---

---

**CT009 - Buscar um pessoa profissional, usando palavras chaves como: carro, perna, dor, cabelo e nariz**

- **Nome do caso de Teste: Realizar busca por pessoa profissional atraves do campo Input, utilizando palavras chaves aleatorias (fora do contexto)**
- **Objetivo:** Verificar se o campo input busca por profissionais e lista os profissionais relacionados com as palavras chaves inseridas no campo utilizando palavras chaves não relacionadas.
- Pre-condições:
1. A PU deverá ja ter feito login na aplicacao
2. A PU deverá estar no link do site: [https://paciente.lacreisaude.com.br/buscar-profissional/](https://paciente.lacreisaude.com.br/buscar-profissional/)
[](https://paciente.lacreisaude.com.br/)
- **Passos:**
1. Identificar campo input “Buscar por profissionais”;
2. Inserir palavras chaves como Ex: “**carro, perna, dor, cabelo e nariz** ”;
3. Clicar no botão “Pesquisar”;
4. Visualizar a seguinte mensagem “**Não encontramos o que você procura.**”.

- **Resultados esperados:** 
1. O sistema deverá exibir a mensagem “**Não encontramos o que você procura.**”
- **Resultados obtido:**
    
    1. O sistema exibiu a mensagem esperada “**Não encontramos o que você procura.**”.
    
    ![NaoEncontrou.gif](Buscar%20uma%20pessoa%20profissional%20453d047deb6a4effafb20e9e8d96c1ba/NaoEncontrou.gif)
    

---

---

---

**CT010 - Buscar um pessoa profissional, usando palavras chaves utilizando caracteres especiais** 

- **N**ome do caso de Teste: Realizar busca utilizando caracteres especiais
- **Objetivo:** Verificar se o campo de busca aceita caracteres especiais
- Pre-condições:
1. A PU deverá ja ter feito login na aplicacao
2. A PU deverá estar no link do site: [https://paciente.lacreisaude.com.br/buscar-profissional/](https://paciente.lacreisaude.com.br/buscar-profissional/)
3. A lista de profissionais deve conter alguma palavra usando caracteres especiais.

- **Passos:**
1. Identificar campo input “Buscar por profissionais”;
2. Inserir palavras chaves como Ex: “n˜`’”;
3. Clicar no botão “Pesquisar”;
4. Visualizar lista com a “palavra” relacionada (caso algum profissional a tenha incluido em sua descrição)

- **Resultados esperados:** 
1. O sistema deverá exibir lista com a palavra relacionada (caso algum profissional a tenha incluido em sua descrição)
- **Resultados obtido:**
    
    1. O sistema exibiu lista com a palavra relaciona que continham o caracter especial em sua descrição.
    
    ![bucasCaracterEspecial.gif](Buscar%20uma%20pessoa%20profissional%20453d047deb6a4effafb20e9e8d96c1ba/bucasCaracterEspecial.gif)
    
    ---
    
    ---
    
    ---
    
    **CT011 - Buscar um pessoa profissional, com campo input vazio**
    
    - **N**ome do caso de Teste: Botão “Criar conta”
    - **Objetivo:** Verificar se o botão “Criar conta” redireciona a nova PU para o formulario de cadastro
    - **Pré-condições:** 1. A nova PU deverá estar no link do site: [https://paciente.lacreisaude.com.br/](https://paciente.lacreisaude.com.br/)
    2. A nova PU deverá identificar o botão “Criar uma conta”;
    - **Passos:**
    1. Clicar no botão de “Criar uma conta”;
    2. A nova PU devera visualizar o formulario de cadastro.
    
    - **Resultados esperados:** 
    1. O sistema deverá redirecionar para a tela de cadastro;
    - **Resultados obtido:**
        
        1. O sistema redirecionou para a tela de cadastro;
        
        ![InputVazio.gif](Buscar%20uma%20pessoa%20profissional%20453d047deb6a4effafb20e9e8d96c1ba/InputVazio.gif)
        
    
    ---
    
    ---