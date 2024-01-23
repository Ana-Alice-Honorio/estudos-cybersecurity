# ☁️ Azure

## Principais conceitos

### Azure Directive Directory

- Usuários -> internos ou externos, podem fazer parte de grupos
- aplicativos -> identidades e softwares internos ou externos
- dispositivos -> equipamentos usados para acessar
- grupos -> organizar e gerenciar acessos dos usuários aos recursos. Podem conter aplicativos, outros grupos, usuários

### identidades externas

- convidados externos (clientes, usuários, colabs). Conta pessoal para acessar organização. O locatário pode definir permissões de acesso.

### identidades híbridas, Azure AD Connect

- Integração e ambientação do ambiente local Active Directory e Azure Active Directory. Protocolos de autenticação (PTA -> credenciais locais, THS -> senhas do AD local e o Azure AD)

### Autenticação Multifator

- Pode ser impressão digital, sms, token, chamada telefônica, chaves de segurança física. Mesmo se um invasor tiver a senha, há uma segunda autenticação por segurança