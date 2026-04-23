1. Requisitos Não Funcionais (NFR)
.Desempenho: O sistema deve responder em até 2 segundos para operações básicas.
.Usabilidade: Interface simples, permitindo cadastro de tarefas em até 1 minuto.
.Disponibilidade: O sistema deve estar disponível 95% do tempo.
.Segurança: Os dados do usuário devem ser protegidos contra acesso não autorizado.
.Escalabilidade: O sistema deve suportar aumento de usuários sem perda significativa de desempenho.

2. Justificativa Técnica
.Desempenho: Garante que o usuário não fique esperando, melhorando a experiência.
.Usabilidade: Facilita o uso, principalmente para estudantes que precisam de agilidade.
.Disponibilidade: Evita indisponibilidade em momentos importantes (provas, prazos).
.Segurança: Protege informações pessoais e acadêmicas dos usuários.
.Escalabilidade: Permite crescimento do sistema sem necessidade de refazer tudo.

3. Impacto Arquitetural

.Uso de estruturas eficientes (listas, arrays) para melhorar desempenho
.Possível uso de cache para acelerar consultas
.Organização do sistema em módulos (cadastro, tarefas, visualização)
.Preparação para uso futuro de banco de dados
.Separação entre lógica e interface

4. Estratégias de Mitigação
.Testes para garantir tempo de resposta adequado
.Validação de entradas do usuário para evitar erros
.Monitoramento básico do sistema
.Tratamento de falhas (ex: mensagens de erro claras)
.Organização do código para facilitar manutenção
