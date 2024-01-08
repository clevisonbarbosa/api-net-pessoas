# Api-Crud-Pessoas

Este é o backend da aplicação, responsável por fornecer APIs para o frontend.

## Configuração

1. **Configurações do Banco de Dados:**
   - Edite o arquivo `appsettings.json` na raiz do projeto para configurar a conexão com o banco de dados.
   - Certifique-se de não incluir informações sensíveis no repositório público.

2. **Executar as Migrações do Banco de Dados:**
   - Abra um terminal na raiz do projeto.
   - Execute os seguintes comandos:
     ```bash
     dotnet ef migrations add NomeDaMigracao
     dotnet ef database update
     ```

3. **Executar a Aplicação:**
   - Execute a aplicação usando o seguinte comando:
     ```bash
     dotnet run
     ```
   - Certifique-se de ajustar as configurações de ambiente conforme necessário.

## API Endpoints

- `/api/pessoas` - GET: Obter todas as pessoas.
- `/api/pessoas/{pessoaId}` - GET: Obter uma pessoa por ID.
- `/api/pessoas` - POST: Adicionar uma nova pessoa.
- `/api/pessoas` - PUT: Atualizar uma pessoa existente.
- `/api/pessoas/{pessoaId}` - DELETE: Excluir uma pessoa por ID.
