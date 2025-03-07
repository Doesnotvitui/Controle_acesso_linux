# Gerenciamento de Usuários e Controle de Acesso no Linux

## Descrição
Este repositório contém atividades relacionadas à administração de usuários e controle de acesso em sistemas Linux. O objetivo é demonstrar boas práticas de segurança, gerenciamento de permissões e organização de diretórios e arquivos.

As tarefas são baseadas em um cenário fictício onde a segurança do sistema deve ser garantida, aplicando conceitos de controle de acesso para diferentes grupos de usuários.

## Estrutura do Projeto
O repositório está organizado da seguinte forma:

```
/
|-- usuarios_grupos.sh   # Script para criação de usuários e grupos
|-- organizacao_arquivos.sh  # Script para criação de diretórios e arquivos
|-- permissoes.sh  # Script para configurar permissões de acesso
|-- protecao_sistema.sh  # Script para restringir acessos indesejados
|-- README.md  # Documentação do repositório
```

## Objetivos

### 1. Criação de Usuários e Grupos
- Criar grupos: "Líderes", "Mestres", "Jedi", "Padawan" e "Lorde Sith".
- Criar usuários e associá-los aos grupos.
- Definir acessos ao shell para determinados usuários.

### 2. Organização de Diretórios e Arquivos
- Criar diretórios temáticos (ex: "licoes", "manuais", "missoes", "segredos").
- Criar arquivos dentro de cada diretório.
- Adicionar conteúdo nos arquivos.

### 3. Configuração de Permissões
- Definir permissões de leitura, escrita e execução.
- Garantir acesso controlado conforme os grupos e usuários.

### 4. Proteção do Sistema
- Implementar restrições para impedir acessos indesejados.
- Impedir que "Lorde Sith" navegue pelo sistema.

## Como Executar os Scripts
1. Clone este repositório:
   ```sh
   git clone https://github.com/seu-usuario/repositorio.git
   cd repositorio
   ```
2. Dê permissão de execução aos scripts:
   ```sh
   chmod +x *.sh
   ```
3. Execute os scripts na ordem correta:
   ```sh
   sudo ./usuarios_grupos.sh
   sudo ./organizacao_arquivos.sh
   sudo ./permissoes.sh
   sudo ./protecao_sistema.sh
   ```

## Tecnologias Utilizadas
- **Linux** (Distribuição Debian/Ubuntu recomendada)
- **Bash Scripting**
- **Comandos de gerenciamento de usuários e permissões**

## Contribuição
Contribuições são bem-vindas! Para sugerir melhorias:
1. Fork o repositório.
2. Crie um branch: `git checkout -b minha-feature`
3. Commit suas alterações: `git commit -m "Minha contribuição"`
4. Push para o branch: `git push origin minha-feature`
5. Abra um Pull Request.

## Autor
Leonardo de Goes da Silva e Vithor Augusto Andrade - Turma 1U - Cibersegurança
