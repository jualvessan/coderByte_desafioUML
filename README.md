# coderByte_desafioUML
🤘 Rock in Rio: Uma Experiência Épica, Ingressos Justos! 🤘
           Prepare-se para o show da sua vida! 🎸🎤

Este sistema de logins e compra de ingressos para o Rock in Rio foi desenvolvido com o objetivo de garantir uma experiência justa e eficiente para todos os fãs, durante a venda dos ingressos limitados. Sua chance de curtir o festival dos sonhos!

# Objetivo:
Acesso Fair-Play: Garantir que apenas usuários com ingressos disponíveis efetivem a compra, sem "furadas" na fila.
Adeus, Filas Virtuais! Eliminar filas virtuais e garantir a ordem de acesso à compra dos ingressos.
Sua Oportunidade: Assegurar que todos os usuários tenham uma chance justa de adquirir um ingresso.

# Observações:
Esta é uma visão geral simplificada do sistema, gerada a partir de um desafio proposto pela plataforma CoderByte.
O sistema real pode ter componentes adicionais, como gerenciador de pagamentos, banco de dados, etc.
A implementação do sistema leva em consideração a escalabilidade, performance e segurança.

# Componentes:

1. Usuário:
Você, o fã!
Realiza login, cadastro e solicita a compra de ingressos.
Seus dados são protegidos com segurança.

2. Sistema de Login:
Porta de Entrada: Autentica os usuários.
Banco de Dados: Armazena seus dados com segurança.
Senha Segura: Utiliza um mecanismo de hash para proteger suas senhas.
Token de Acesso: Gera e valida tokens de autenticação para acesso seguro.

3. Fila de Espera:
Sua Posição: Implementa um sistema de fila virtual para garantir a ordem de acesso à compra dos ingressos.
Organização: Mantém uma lista de usuários aguardando, com suas respectivas posições.
Controle: Permite adicionar, remover e consultar a posição atual dos usuários na fila.

4. Gerenciador de Ingressos:
Controle Total: Responsável por gerenciar a disponibilidade de ingressos.
Estoque: Controla a quantidade total e disponível de ingressos.
Reserva: Permite verificar a disponibilidade, reservar e confirmar a compra de ingressos.
Liberação: Permite cancelar reservas, liberando ingressos novamente.

5. Serviço de Compra:
Sua Compra: Responsável por processar a compra de ingressos.
Detalhes do Ingresso: Armazena informações sobre o ingresso, como tipo, setor e preço.
Pagamento Seguro: Permite solicitar a compra, processar o pagamento, confirmar a compra e gerar o código de barras do ingresso.

# Fluxo da Compra:

Login: Faça login no sistema usando suas credenciais.
Fila de Espera: Você será adicionado à fila de espera para compra de ingressos.
Disponibilidade: Verificamos se há ingressos disponíveis para você.
Reserva: Se houver ingressos disponíveis, você receberá uma reserva por tempo limitado.
Pagamento: Você será direcionado para a página de pagamento.
Confirmação: Após o pagamento confirmado, sua compra será confirmada, liberando o ingresso e removendo-o da fila de espera.
Código de Barras: Seu código de barras único será gerado, pronto para a aventura no Rock in Rio!

Benefícios:
Compra Justa: O sistema de fila garante que você seja atendido na ordem de chegada, evitando "furadas".
Disponibilidade Real: Garante que apenas os ingressos disponíveis sejam vendidos, evitando frustrações.
Segurança: O sistema de login e autenticação protege seus dados.

# Veja o diagrama UML da arquitetura no arquivo UML_sist_login_compras.png
