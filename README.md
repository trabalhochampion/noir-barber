# NOIR BARBER OS — Site + sistema

## Executar localmente
Requer Node.js 22.13 ou superior.

```bash
node server.js
```

Abra http://localhost:3000 para o site institucional e http://localhost:3000/app.html para o sistema de login, cadastro e gestão.

## Publicar
Use um servidor Node.js com HTTPS, armazenamento persistente e backups. A variável PORT é respeitada. O SQLite é criado na pasta do projeto: configure armazenamento persistente antes de implantar, ou migre para banco gerenciado.

## Estado do projeto
Protótipo funcional para testes locais. O painel de exemplo no site usa números fictícios. Não existe checkout de pagamentos real, WhatsApp automático nem Super Admin pronto. Antes de aceitar dados reais, implemente proteção CSRF, limites de requisição, agendamento transacional, regras de fuso horário, recuperação de senha, LGPD e testes de segurança. A assinatura não é ativada por pagamento nesta versão.
