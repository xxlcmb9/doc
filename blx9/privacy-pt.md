# Política de Privacidade

Localizar+ · Última atualização: 17 de novembro de 2026

## 1. Sobre esta política

Localizar+ (o «App») é um app iOS para compartilhar manualmente uma posição de cada vez com quem você autorizar. Esta política explica quais dados o App trata, onde ficam armazenados e quais escolhas você tem. O App é oferecido pelo desenvolvedor do Localizar+ («nós»). Contato: https://github.com/xxlcmb9/doc/issues.

## 2. Dados que tratamos

- Número de compartilhamento: um número aleatório de 9 dígitos gerado no seu dispositivo. Não é necessário e-mail, telefone, senha ou conta social, e não pedimos nome, contatos ou fotos.
- Localização que você confirma: latitude, longitude, altitude e carimbos de data/hora, enviados só após tocar em compartilhar e confirmar.
- Lista de permitidos e lista de bloqueados: os números autorizados ou bloqueados, guardados no seu perfil.
- Mensagens que você nos envia: se entrar em contato pela página de suporte.

## 3. Como o compartilhamento funciona

- Nada é publicado automaticamente, em segundo plano ou por temporizador. Cada registro exige confirmação e pode ser cancelado.
- Cada registro envia uma única posição que substitui a anterior. O App não guarda histórico.
- O registro expira no App uma hora após a publicação e deixa de ser exibido a outros usuários. A expiração é apenas uma regra de exibição: não apaga o arquivo do armazenamento em nuvem. O arquivo é apagado quando você retira o compartilhamento ou exclui sua identidade.
- Exibir sua própria posição no mapa local é um ajuste opcional separado e não compartilha nada.

## 4. Onde os dados ficam armazenados

Registros compartilhados, listas e índice de números ficam no Tencent Cloud Object Storage (COS), região ap-nanjing (China continental), com credenciais temporárias emitidas pelo endpoint de autenticação do App. Seu número e suas listas também ficam no dispositivo. Não mantemos banco de análise separado para localizações. Após a exclusão, backups do provedor podem permanecer por um período limitado.

## 5. Serviços de terceiros

- Tencent Cloud COS: armazenamento dos registros e das listas.
- Google AdMob e Google User Messaging Platform: anúncios e telas de consentimento; o Google pode receber identificadores do dispositivo, endereço IP e interações com anúncios.
- Apple: App Store, compras no app e pagamentos. Nunca recebemos os dados do seu cartão.
- open-elevation.com: apenas quando você seleciona um ponto no mapa para consultar a altitude a coordenada escolhida é enviada, e você pode cancelar antes.

Não vendemos dados pessoais.

## 6. Anúncios e rastreamento

Os anúncios sustentam a versão gratuita. No iOS 14.5 ou superior o App solicita a autorização de Rastreamento (ATT) quando necessário; se recusar, você verá anúncios, mas não personalizados. Você pode alterar em Ajustes → Privacidade e Segurança → Rastreamento e nas opções de consentimento do App.

## 7. Segurança e limites

O tráfego usa HTTPS/TLS e credenciais temporárias com validade. Antes de cada consulta o App verifica a lista de bloqueados e a de permitidos nos dois lados; o bloqueio prevalece. Esse controle é aplicado pelo App e não isolado no servidor, portanto não impede que alguém com credenciais válidas leia objetos do bucket, nem que o destinatário faça capturas ou cópias. Compartilhe apenas o que você pode divulgar.

## 8. Suas escolhas

- Retirar o compartilhamento a qualquer momento (apaga o registro compartilhado).
- Bloquear ou desbloquear; desbloquear não restaura a lista de permitidos.
- Ocultar sua própria posição no mapa local.
- Excluir sua identidade no App: localização, perfil e entrada do índice são removidos e depois os dados locais. A compra vitalícia não é afetada.
- Revogar o acesso à localização nos Ajustes do iOS; mapa, bússola e altitude deixam de funcionar, o restante do App continua utilizável.
- Falar conosco pelo link de suporte para solicitar acesso, correção ou exclusão dos dados ligados ao seu número.

## 9. Crianças

O App não se destina a menores de 13 anos, ou à idade mínima exigida no seu país. Não coletamos dados de menores intencionalmente. Se acreditar que uma criança compartilhou dados, fale conosco e apagaremos.

## 10. Alterações e contato

Podemos atualizar esta política; a data acima mudará e a nova versão será publicada nesta página. Dúvidas: https://github.com/xxlcmb9/doc/issues.

Suporte: https://github.com/xxlcmb9/doc/issues
