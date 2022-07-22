# Pix

![logo_pix](https://user-images.githubusercontent.com/30627500/180342797-c089ae51-aa91-4222-b30f-3a173a67db79.png "Figura 1. Pix logo - Banco Central do Brasil.")

## Sumário
- [Chave Pix](#chave-pix) <br>
- [QR Code](#qr-code)<br>
- [Configurando uma chave Pix](#configurando-uma-chave-pix) <br>
- [Documentação de suporte](#documentação-de-suporte)
---

O Pix é o sistema de pagamento instântaneo lançado em 2020 pelo **Banco Central do Brasil**. Esse meio de pagamento deve ser disponibilizado 24 horas por dia, durante os 7 dias da semana, sem diferenciar finais de semana ou feriados. 

O seu diferencial é que em poucos segundos a transferência será concluída, permitindo que o dinheiro saia de uma conta A para uma conta B rapidamente. Tudo isso será feito bastando saber a chave Pix, ao invés de pedir agência, conta e dados pessoais do recebedor.

O Pix pode ser realizado a partir de uma conta corrente, conta poupança ou conta de pagamento pré-paga. O **Banco Central do Brasil (Bacen)** é o órgão regulador responsável pelas normativas referentes ao Pix. 

Saiba mais em: [Banco Central do Brasil](https://www.bcb.gov.br/estabilidadefinanceira/pix).

![pix](https://user-images.githubusercontent.com/30627500/180342812-bf905b90-62ea-4806-aea1-b9bb8680f0ba.PNG "Figura 2. Vantagens Pix - Banco Central do Brasil.")

> ### Observação
> **Não existe limite mínimo de valores para pagamentos ou transferências via Pix.** Entretanto, as instituições que ofertam o Pix poderão estabelecer limites máximos de valor baseados em critérios de mitigação de riscos de fraude e de critérios de prevenção à lavagem de dinheiro e ao financiamento do terrorismo. Os usuários podem solicitar ajustes nos limites estabelecidos caso achem necessário, **devendo a instituição acatar imediatamente** a solicitação se o pedido seja para redução de valor.

## Chave Pix

A chave Pix é um identificador utilizado para facilitar a transação, necessitando apenas de uma informação do recebedor para que a transferência seja realizada.

Ela contém as informações de seus usuários, com suas respectivas contas transacionais e fica armazenada numa base de dados chamada _Pix DICT - Diretório de Identificadores de Contas Transacionais_.  A chave pix previamente cadastrada pode ser:

- CPF ou CNPJ;
- E-mail;
- Número de celular;
- Chave aleatória (sequência alfanumérica gerada aleatoriamente). 

Atualmente, uma conta de pessoa física pode ter no máximo 5 chaves cadastradas, enquanto que uma conta de pessoa jurídica pode ter até 20 chaves. Contudo, as chaves do tipo CPF/CNPJ possuem um limite de uma chave por conta, tendo as demais chaves uma quantidade limite diferente para cada caso. 

## QR Code

É possível também fazer transações Pix utilizando QR codes como identificadores de transações. Existem dois tipos distintos, sendo eles:

- QR code estático;
- QR code dinâmico.

O **QR code estático** permite que várias transações sejam realizadas a partir de um mesmo QR code. Com isso, é possível definir valores fixos para produtos e serviços e disponibilizar o QR code previamente como método de pagamento. 

O **QR code dinâmico** é exlusivo de cada transação, só podendo ser utilizado uma única vez. Isso significa que idealmente ele será gerado no ato da compra.

## Configurando uma chave Pix

O processo de configuração de uma chave Pix se inicia através do aplicativo da instituição financeira a qual você deseja atrelar o sistema à sua conta. As seguintes entidades fazem parte dele:

- Usuário;
- Instituições financeiras;
- Banco Central do Brasil.

O fluxograma abaixo representa a experiência de criação de uma chave Pix.

![fluxograma](https://user-images.githubusercontent.com/30627500/180355155-d96d765b-eede-4941-a065-5c0e007f1b3b.jpeg "Figura 3. Fluxograma da jornada do usuário.")

> ### Observação
> É possível realizar a migração de uma chave já existente entre diferentes instituições financeiras. Caso um usuário queira cadastrar uma chave com um dado já utilizado, será dada a opção de portar essa chave para a nova conta no momento de criação da chave. **O DICT, sistema do Banco Central que gerencia o cadastro das chaves do Pix**, será o responsável por conectar as duas instituições e garantir que a portabilidade seja feita.

## Documentação de suporte
[FAQ Pix - Bacen](https://www.bcb.gov.br/acessoinformacao/perguntasfrequentes-respostas/faq_pixpagtoinstantaneo). <br>
[Regulamento Pix](https://www.bcb.gov.br/estabilidadefinanceira/exibenormativo?tipo=Resolu%C3%A7%C3%A3o%20BCB&numero=1).
