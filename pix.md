<!--

Contexto
Você atua como Technical Writer em uma empresa e o Product Manager do projeto
que você faz parte pediu um tutorial, em português, de como utilizar o produto.


Para isso, ele te orientou a criar um repositório no Github e escrever em markdown um
texto com o tema "Como configurar sua chave PIX".


Instruções
● Pense que este tutorial poderia ser publicado em uma documentação pública. Por isso,
além do texto, seria interessante entender como você estruturaria as informações da
página com menu, submenu e demais recursos, como tabelas, listas ou tabs.
● Crie um repositório em sua conta no Github com o nome pix-tutorial. Você pode
consultar a documentação oficial do Github para entender desde como abrir uma conta
até como criar um repositório do zero.

-->
# Pix

![logo_pix](https://user-images.githubusercontent.com/30627500/180342797-c089ae51-aa91-4222-b30f-3a173a67db79.png)

## Sumário
[Chave Pix](#chave-pix)
[QR Code](#qr-code)
[Configurando uma chave Pix](#configurando-uma-chave-pix)

O Pix é o sistema de pagamento instântaneo lançado em 2020 pelo Banco Central do Brasil. Esse meio de pagamento deve ser disponibilizado 24 horas por dia, durante os 7 dias da semana, sem diferenciar finais de simana e feriados.

O seu diferencial é que em poucos segundos a transferência deve ser concluída, permitindo que o dinheiro saia de uma conta A para uma conta B rapidamente. O Pix pode ser realizado a partir de uma conta corrente, conta poupança ou conta de pagamento pré-paga.

Exemplo: o recebedor cadastrou previamente seu número de telefone celular para receber o crédito em determinada conta. Então, em vez de informar manualmente todos os dados, inclui apenas o número do telefone celular. Ao fazer um Pix, o sistema identifica as informações da conta do credor a partir dessa chave.

O Banco Central do Brasil (Bacen) é o órgão regulador responsável pelas normativas referentes ao Pix. Saiba mais em: [Banco Central do Brasil](https://www.bcb.gov.br/estabilidadefinanceira/pix).

![pix](https://user-images.githubusercontent.com/30627500/180342812-bf905b90-62ea-4806-aea1-b9bb8680f0ba.PNG)

> #### Observação
> Não há limite mínimo para pagamentos ou transferências via Pix. Entretanto, as instituições que ofertam o Pix poderão estabelecer limites máximos de valor baseados em critérios de mitigação de riscos de fraude e de critérios de prevenção à lavagem de dinheiro e ao financiamento do terrorismo. Os usuários podem solicitar ajustes nos limites estabelecidos, devendo a instituição acatar imediatamente a solicitação caso o pedido seja para redução de valor.

### Chave Pix

A chave Pix é um identificador utilizado para facilitar a transação, necessitando apenas de uma informação do recebedor para que a transferência seja realizada.

Ela contém as informações de seus usuários, com suas respectivas contas transacionais e fica armazenada numa base de dados chamada Pix DICT - Diretório de Identificadores de Contas Transacionais.  A chave pix previamente cadastrada pode ser:

- CPF ou CNPJ;
- E-mail;
- Número de celular;
- Chave aleatória (sequência alfanumérica gerada aleatoriamente). 

Atualmente, uma conta de pessoa física pode ter no máximo 5 chaves cadastradas, enquanto que uma conta de pessoa jurídica pode ter até 20 chaves. Contudo, as chaves do tipo CPF/CNPJ possuem um limite de uma chave por conta, tendo as demais chaves uma quantidade limite permitida diferente para cada caso. 

### QR Code

É possível também fazer transações Pix utilizando QR codes como identificadores de transações. Existem dois tipos distintos, sendo eles:

- QR code estático;
- QR code dinâmico.

O QR code estático permite que várias transações sejam realizadas a partir de um mesmo QR code. Com isso, é possível definir valores fixos para produtos e serviçoes e disponibilizar o QR code previamente como método de pagamento. O QR code dinâmico é exlusivo de cada transação, só podendo ser utilizados uma única vez. Isso significa que idealmente ele será gerado no ato da compra.
