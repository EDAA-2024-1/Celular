# Celular

Crie um sistema em Java para que simule o comportamento básico de um celular através do uso de interfaces e classes. O programa deve ser capaz de simular ações como ligar/desligar, fazer ligações e enviar mensagens. Sua solução deve incluir as seguintes classes e interface:

- **Interface Celular**: Deve definir os métodos ligar(), desligar(), fazerLigacao(String numero) e enviarMensagem(String numero, String mensagem).

- **Classe ModeloBasico**: Deve implementar a interface Celular. Esta classe representa um modelo básico de celular que apenas registra em console as ações executadas (por exemplo, exibir uma mensagem quando uma ligação é feita ou uma mensagem é enviada).

- **Classe ModeloAvancado**: Deve também implementar a interface Celular. Esta classe representa um modelo mais avançado de celular que, além de registrar as ações, mantém um histórico das ligações feitas e mensagens enviadas.

- **Classe Principal**: Uma classe com um método main para testar as funcionalidades dos modelos de celular. Deve criar instâncias de ModeloBasico e ModeloAvancado, usar todos os métodos definidos e demonstrar o funcionamento das funcionalidades.
