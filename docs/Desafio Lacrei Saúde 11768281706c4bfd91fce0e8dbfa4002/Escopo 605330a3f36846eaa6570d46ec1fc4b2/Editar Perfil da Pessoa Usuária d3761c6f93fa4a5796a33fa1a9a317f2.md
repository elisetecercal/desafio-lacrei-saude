# Editar Perfil da Pessoa Usuária

Critérios de Aceite: https://miro.com/app/board/uXjVNmWH66w=/?moveToWidget=3458764581407611085&cot=10
Prioridade: ⭐️
Severidade: Baixa
Status: Done
Tipo de Teste: Funcional

| ID | Caso de Teste | Resultados Esperados | Resultados Obtidos | Passou ou Não Passou |
| --- | --- | --- | --- | --- |
| Editar%20Perfil%20da%20Pessoa%20Usua%CC%81ria%20d3761c6f93fa4a5796a33fa1a9a317f2.md | Editar dados pessoais (Foto)do Perfil de usuário ativo  | Edição de foto deve ser realizada com sucesso | A foto foi adicionada ao perfil com sucesso | Passou |
| Editar%20Perfil%20da%20Pessoa%20Usua%CC%81ria%20d3761c6f93fa4a5796a33fa1a9a317f2.md | Editar senha de usuário ativo | Alteração da senha deve ser realizada com sucesso | A senha foi alterada com sucesso | Passou |
| Editar%20Perfil%20da%20Pessoa%20Usua%CC%81ria%20d3761c6f93fa4a5796a33fa1a9a317f2.md | Editar  e-mai/telefonel de usuário ativo | Alteração de e-mail e telefone deve ser realizada com sucesso | Não foi realizada com sucesso. Campo de alteração de e-mail não foi exibida | Não Passou |
| Editar%20Perfil%20da%20Pessoa%20Usua%CC%81ria%20d3761c6f93fa4a5796a33fa1a9a317f2.md | Solicitar dados PU | Dados devem ser enviados com sucesso para o e-mail indicado | Não foi recebido e-mail com dados solicitados | Não Passou |
| Editar%20Perfil%20da%20Pessoa%20Usua%CC%81ria%20d3761c6f93fa4a5796a33fa1a9a317f2.md | Apagar conta PU | Conta deve se apagada do sistema | Não foi realizada a exclusão da conta | Não Passou |

---

---

CT014 - Editar dados pessoais do perfil de uma PU.

- **Nome do caso de Teste:** Editar dados pessoais (Foto) do perfil  de uma PU cadastrado
- **Objetivo:** Testar se o fluxo de edição de dados (foto) de um perfil cadastrado acontece da maneira esperada.
- **Pré-condições:**

1. A PU deverá ter cadastro ativo na aplicação LS
2. A PU deverá estar logado na aplicação LS
3. A PU deve estar na pagina - [https://paciente.lacreisaude.com.br/perfil/](https://paciente.lacreisaude.com.br/perfil/)
4. Ter um arquivo de imagem compatível para carregar na aplicação.
[](https://paciente.lacreisaude.com.br/)

- **Passos:**
1. Identificar página “Perfil”;
2. Clicar no botão “Editar foto” abaixo do icone de foto;
3. Visualizar os botões para “enviar foto” e “câmera”
4. Clicar no botão de “enviar foto” para carregar um arquivo de imagem;
5. Abrirá seus arquivos;
6. Clicar na imagem escolhida;
7. Clicar no botão “abrir” para carregar a imagem.
8. Inserir uma descrição para a foto

Resultado esperado

1. Uma nova imagem será adicionada a seu perfil.

- **Resultados obtido:**
    
    1. Uma nova imagem foi adicionada ao perfil da PU.
    
    ![EdicaoFotoPerfil.gif](Editar%20Perfil%20da%20Pessoa%20Usua%CC%81ria%20d3761c6f93fa4a5796a33fa1a9a317f2/EdicaoFotoPerfil.gif)
    
    ---
    
    ---
    
    CT015 - Editar senha de usuário ativo
    
    - **Nome do caso de Teste:** Editar dados pessoais Senha  do perfil  de uma PU cadastrado
    - **Objetivo:** Testar se o fluxo de edição de dados Senha de um perfil cadastrado acontece da maneira esperada.
    - **Pré-condições:**
    
    1. A PU deve ter cadastro ativo na aplicação LS
    2. A PU deve estar logado na aplicação LS
    3. A PU deve estar na página - [https://paciente.lacreisaude.com.br/perfil/](https://paciente.lacreisaude.com.br/perfil/)
    
    [](https://paciente.lacreisaude.com.br/)
    
    - **Passos:**
    1. Estar na página “Perfil”;
    2. Clicar na Aba “Segurança” ao lado da Aba “Informações Pessoais”;
    3. Visualizar os botões para “alterar senha” e “editar dados”
    4. Clicar no botão de “alterar senha” para ser redirecionado para a pagina de alteração de senha;
    5. Inserir no primeiro campo input  sua “senha atual”;
    6. Inserir no segundo campo input  sua “nova senha” respeitando os criterios abaixo;
    7. Repetir no terceiro campo input  sua “nova senha”;
    8. Clicar em “salvar senha”.
    
    Resultado esperado
    
    1. A senha deverá atualizada 
    
    - **Resultados obtido:**
        
        1. A nova senha foi atualizada com sucesso
        
        ![EdicaSenha.gif](Editar%20Perfil%20da%20Pessoa%20Usua%CC%81ria%20d3761c6f93fa4a5796a33fa1a9a317f2/EdicaSenha.gif)
        
                                                                             Captura Alteração Senha
        
        ---
        
        ---
        
        CT016 - Editar  e-mail/telefone de usuário ativo
        
        - **Nome do caso de Teste:** Editar dados pessoais e-mail/telefone do perfil  de uma PU cadastrado
        - **Objetivo:** Testar se o fluxo de edição de dados e-mail/telefone de um perfil cadastrado acontece da maneira esperada.
        - **Pré-condições:**
        
        1. A PU deverá ter cadastro ativo na aplicação LS
        2. A PU deverá estar logado na aplicação LS
        3. A PU deve estar na pagina - [https://paciente.lacreisaude.com.br/perfil/](https://paciente.lacreisaude.com.br/perfil/)
        
        - **Passos:**
        1. Estar na página “Perfil”;
        2. Clicar na Aba “Segurança” ao lado da Aba “Informações Pessoais”;
        3. Visualizar o botão “editar dados”
        4. Clicar no botão de “editar dados” para habilitar o campo de edição “Telefone” e “E-mail”
        5. Visualizar os campos “Telefone” e “E-mail”;
        6. Inserir novo numero de telefone seguindo o padrão (xx) xxxxx-xxxx no campo “telefone”
        7. Inserir novo e-mail no campo “e-mail”;
        8. Clicar em “salvar dados”.
        
        Resultado esperado
        
        1. Numero de telefone sera atualizado no cadastro da PU;
        
        1. Novo e-mail sera atualizado no cadastro da PU.
        
        - **Resultados obtido:**
            
            1. Não houve atualização do dado “Telefone”;
            
            1. O sistema não apresentou campo para edição do e-mail.
            
            ![Tefone.gif](Editar%20Perfil%20da%20Pessoa%20Usua%CC%81ria%20d3761c6f93fa4a5796a33fa1a9a317f2/Tefone.gif)
            
            ---
            
            ---
            
            CT017 - Solicitar dados PU
            
            - **Nome do caso de Teste: Solicitar dados da PU**
            - **Objetivo:** Verificar se o sistema realiza com sucesso a solicitação de dados atraves do formulário **Solicitação de direitos da pessoa titular.**
            - **Pré-condições:**
            
            1. A PU deve ter cadastro ativo na aplicação LS
            2. A PU deve estar logado na aplicação LS
            3. A PU deve estar na pagina - [https://paciente.lacreisaude.com.br/perfil/](https://paciente.lacreisaude.com.br/perfil/)
            
            - **Passos:**
            1. Estar na página “Perfil”;
            2. Clicar na Aba “Privacidade” ao lado da Aba “Segurança”;
            3. Rolar a página para cima e visualizar o botão “Solicitar meus dados”
            4. Clicar no botão de “Solicitar meus dados” para ser redirecionado a página “Direito do titular”;
            5. Na página direito do titular inserir seus dados no campos “Nome”, “e-mail” e escolher na caixa de opções “Paciente”
            6. Marcar as opções da lista de solicitações de dados:
            - Confirmação da existência do tratamento
            - Acesso aos dados
            - Apagar a conta
            - Correção de dados
            - Tornar anônimo, bloquear ou eliminar dados desnecessários
            - Portabilidade de dados
            - Eliminação dos dados pessoais tratados com o consentimento da pessoa titular
            - Informações sobre o compartilhamento de dados
            - Informação sobre a possibilidade de não fornecer consentimento sexual
            - Anular o consentimento dos dados
            - Outro direito
            1. Clicar em “solicitar dados”.
            2. Mensagem de “Solicitação enviada!” será exibida.
            
            Resultado esperado
            
            1. Pessoa PU recebe as informações solicitadas no e-mail indicado no formulário de solicitação.
                
                
            - **Resultados obtido:**
                
                1. E-mail com a solicitação de dados não foi recebido pela PU.
                
                ![envioDeSolicitacao.gif](Editar%20Perfil%20da%20Pessoa%20Usua%CC%81ria%20d3761c6f93fa4a5796a33fa1a9a317f2/envioDeSolicitacao.gif)
                
                ---
                
                ---
                
                ---
                
                ---
                
                CT018 - Apagar conta PU
                
                - **Nome do caso de Teste:**  Apagar conta de PU cadastrada
                - **Objetivo:** Testar ação de apagar conta da PU atraves do formulario “Solicitação de direitos da pessoa titular”.
                - **Pré-condições:**
                
                1. A PU deverá ter cadastro ativo na aplicação LS
                2. A PU deverá estar logado na aplicação LS
                3. A PU deve estar na pagina - [https://paciente.lacreisaude.com.br/perfil/](https://paciente.lacreisaude.com.br/perfil/)
                
                - **Passos:**
                1. Estar na página “Perfil”;
                2. Clicar na Aba “Privacidade” ao lado da Aba “Segurança”;
                3. Visualizar o botão vermelho “Apaga conta”.
                4. Clicar no botão de “Apaga conta” para ser redirecionado para uma pagina de confirmação.
                5. Visualizar os botões “Sim” e “Não” que confirmam a intensão de excluir conta de PU;
                6. Clicar no botão de “Sim” para ser redirecionado para o formulario “Solicitação de direitos da pessoa titular”.
                7. Inserir os dados “Nome”, “e-mail ” e selecionar “Paciente” na caixa de opções.
                8. Marcar a opção “Apagar conta”.
                9. Clicar no botão “Solicitar”
                10. Mensagem de “**Solicitação enviada!**” sera exibida.
                
                Resultado esperado
                
                1. Pessoa PU recebe confirmação de solicitação da conta apagada.
                
                - **Resultados obtido:**
                    
                    1. E-mail com a confirmação de solicitação de exclusão de conta não foi recebido pela PU.
                    
                    ![ApagarConta2.gif](Editar%20Perfil%20da%20Pessoa%20Usua%CC%81ria%20d3761c6f93fa4a5796a33fa1a9a317f2/ApagarConta2.gif)
                    
                    ![SCR-20240306-oaad.png](Editar%20Perfil%20da%20Pessoa%20Usua%CC%81ria%20d3761c6f93fa4a5796a33fa1a9a317f2/SCR-20240306-oaad.png)
                    
                    Captura de tela, mostra caixa de e-mail sem mensagem de Solicitação