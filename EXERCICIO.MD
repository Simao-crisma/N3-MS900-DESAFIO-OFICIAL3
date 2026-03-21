# LAB-A05: Configuração do Microsoft 365

## Descrição
Repositório com passos e configurações realizadas no LAB-A05 para o Microsoft 365, incluindo SharePoint, Teams, Exchange e Azure AD.

## Índice
1. [Configuração de Utilizadores](#configuração-de-utilizadores)
2. [Grupos e Equipas](#grupos-e-equipas)
3. [SharePoint e Teams](#sharepoint-e-teams)
4. [Email e Regras](#email-e-regras)
5. [Passos Detalhados](#passos-detalhados)

## Configuração de Utilizadores
- Criação de utilizadores (`trainee-LAB-A05`, `support-LAB-A05`)
- Atribuição de licenças e permissões

## Grupos e Equipas
- Criação de grupos de segurança (`GRP-IT-LAB-A05`, `GRP-HR-LAB-A05`)
- Criação de grupos Microsoft 365 e Teams (`M365-PROJECT-LAB-A05`, `TEAM-IT-LAB-A05`)

## SharePoint e Teams
- Criação de sites (`SITE-PROJECT-LAB-A05`, `SITE-HR-LAB-A05`)
- Configuração de bibliotecas e pastas

## Email e Regras
- Criação de Shared Mailboxes e Distribution Lists
- Configuração de regras de email e encaminhamento

## Passos Detalhados

1. **Criar utilizador trainee-LAB-A05**
   - No Microsoft 365 Admin Center, vá para **Utilizadores > Utilizadores ativos**.
   - Clique em **Adicionar um utilizador** e preencha os detalhes.
2. **Atribuir licença Microsoft 365 Business Premium**
   - No perfil do utilizador, vá para **Licenças e aplicativos**.
   - Atribua a licença **Microsoft 365 Business Premium**.
3. **Editar propriedades do utilizador**
   - Department: IT, Job Title: Administrator.
4. **Criar utilizador support-LAB-A05**
   - Repita o passo 1.
5. **Bloquear login do support-LAB-A05**
   - No perfil, vá para **Conta** e selecione **Bloquear login**.
6. **Criar grupo GRP-IT-LAB-A05**
   - No Entra ID, vá para **Grupos > Novo grupo**.
7. **Adicionar trainee-LAB-A05 ao grupo**
   - No grupo, vá para **Membros** e adicione `trainee-LAB-A05`.
8. **Criar grupo dinâmico GRP-DYN-IT-LAB-A05**
   - Regra: `user.department -eq "IT"`.
9. **Criar grupo M365-PROJECT-LAB-A05**
   - No Microsoft 365 Admin Center.
10. **Definir Owner do grupo**
    - Adicione `trainee-LAB-A05` como Owner.
11. **Criar Team TEAM-IT-LAB-A05**
    - No Microsoft Teams.
12. **Criar canais Operations, Projects, Documentation**
    - No Team `TEAM-IT-LAB-A05`.
13. **Adicionar membros ao Team**
    - No Team, vá para **Membros**.
14. **Criar canal privado Management**
    - No Team `TEAM-IT-LAB-A05`.
15. **Promover membro para Owner**
    - No Team, altere status de um membro.
16. **Criar Shared Mailbox support-LAB-A05@tenant.com**
    - No Exchange Admin Center.
17. **Atribuir Full Access ao trainee-LAB-A05**
    - No Exchange.
18. **Criar DL-IT-LAB-A05**
    - No Exchange.
19. **Adicionar utilizadores à DL**
    - Na lista de distribuição.
20. **Criar regra Disclaimer-LAB-A05**
    - No Exchange, crie uma regra de transporte.
21. **Adicionar texto de disclaimer**
    - "Confidential Message LAB-A05".
22. **Criar site SITE-PROJECT-LAB-A05**
    - No SharePoint.
23. **Criar biblioteca Docs-LAB-A05**
    - No site SharePoint.
24. **Criar pastas Policies, Projects, Reports**
    - Na biblioteca `Docs-LAB-A05`.
25. **Conceder permissões ao GRP-IT-LAB-A05**
26. **Criar site SITE-TEAM-LAB-A05**
   - No SharePoint admin center, crie um novo site de equipe.
27. **Adicionar utilizadores ao site**
   - No site, vá em "Permissões" e adicione membros.
28. **Criar biblioteca Resources-LAB-A05**
   - No site SharePoint, crie uma biblioteca de documentos.
29. **Criar pasta Templates**
   - Dentro da biblioteca, crie uma pasta "Templates".
30. **Configurar permissões exclusivas**
   - Na pasta, vá em "Gerenciar permissões".
31. **Criar grupo M365-SALES-LAB-A05**
   - No Microsoft 365 admin center.
32. **Adicionar membros ao grupo**
   - No grupo, adicione dois usuários.
33. **Criar Team baseado no grupo**
   - No Microsoft Teams.
34. **Criar canal Deals**
   - No Teams, crie um canal "Deals".
35. **Criar canal Forecast**
   - No mesmo Teams, crie "Forecast".
36. **Criar Shared Mailbox sales-LAB-A05@tenant.com**
   - No Exchange admin center.
37. **Criar DL-SALES-LAB-A05**
   - No Exchange.
38. **Criar regra de email com prefixo [INTERNAL]**
   - No Exchange, crie uma regra de transporte.
39. **Criar alias para trainee-LAB-A05**
   - No Exchange.
40. **Criar regra de encaminhamento**
   - No Exchange, configure o encaminhamento.
41. **Criar grupo GRP-HR-LAB-A05**
   - No Azure AD.
42. **Criar Team TEAM-HR-LAB-A05**
   - No Microsoft Teams.
43. **Criar canal Recruitment**
   - No Teams, crie um canal.
44. **Criar canal Policies**
   - No mesmo Teams.
45. **Criar site SITE-HR-LAB-A05**
   - No SharePoint.
46. **Criar biblioteca HRDocs-LAB-A05**
   - No site SharePoint.
47. **Criar pasta Contracts**
   - Na biblioteca.
48. **Criar pasta EmployeeRecords**
   - Na mesma biblioteca.
49. **Adicionar GRP-HR-LAB-A05 ao site**
   - No site, adicione o grupo às permissões.
50. **Validar objetos criados**
   - No Microsoft 365 admin center, busque "LAB-A05".
## Contribuições
Sugestões e contribuições são bem-vindas!



