# Casos de Uso do Sistema de Reserva de Passagens Aéreas

## Descrição do Caso de Uso: Realizar Reserva

| **Atributo**             | **Descrição**                                                                                   |
|---------------------------|-----------------------------------------------------------------------------------------------|
| **Nome do caso de uso**   | Realizar Reserva                                                                              |
| **Escopo**                | Sistema de reserva de passagens aéreas                                                        |
| **Nível**                 | Objetivo do usuário                                                                          |
| **Ator principal**        | Cliente                                                                                      |
| **Interessados e interesses** | Cliente deseja reservar passagens de forma rápida e segura; a empresa quer maximizar vendas.          |
| **Pré-condições**         | Cliente deve estar autenticado no sistema; voos devem estar disponíveis no sistema.           |
| **Garantias de sucesso**  | Reserva criada com código único; status "Efetivada" após pagamento; confirmação enviada ao cliente. |
| **Cenário de sucesso**    | 1. Cliente seleciona voo.<br>2. Insere dados do passageiro.<br>3. Escolhe assento.<br>4. Efetua pagamento.<br>5. Reserva é confirmada. |
| **Extensões**             | 1. Dados inválidos → Solicitar correção.<br>2. Pagamento recusado → Informar cliente.         |
| **Requisitos especiais**  | Sistema deve realizar a reserva em menos de 3 segundos; integração com processadores de pagamento. |
