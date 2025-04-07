
### Por que o Amazon SES?

- O Amazon Simple Email Service (Amazon SES) é um provedor de serviços de e-mail baseado em nuvem que pode ser integrado a qualquer aplicação para automação de e-mails de alto volume. Se você usa um software de e-mail para enviar e-mails transacionais, e-mails de marketing ou e-mails de boletim informativo, você paga apenas pelo que usa. O Amazon SES é uma ferramenta de e-mail que também oferece suporte a uma variedade de implantações, incluindo endereços IP dedicados, compartilhados ou próprios. Relatórios sobre estatísticas de remetentes e ferramentas de capacidade de entrega de e-mails ajudam as empresas a fazer com que cada e-mail conte.
  
  
### Códogio

```ts
import SES from 'aws-sdk/clients/ses';

    const ses = new SES({
      region: process.env.AWS_REGION,
      accessKeyId: process.env.AWS_ACCESS_KEY_ID,
      secretAccessKey: process.env.AWS_SECRET_ACCESS_KEY,
    });
    
      const params = {
        Source: `Rede Odonto <${process.env.AWS_SES_EMAIL}>`,
        Destination: {
          ToAddresses: [to],
        },
        Message: {
          Subject: {
            Data: subject,
            Charset: 'UTF-8',

          },
          Body: {
            Html: {
              Data: html,
              Charset: 'UTF-8',
            },
          },
        },
      };

      await this.ses.sendEmail(params).promise();
```