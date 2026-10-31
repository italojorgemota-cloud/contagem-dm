# Contagem de Inventário – Filial AW

Banco de dados próprio (projeto Firebase `contagem-aw`), separado do Dois Marcos.

## Já feito
- Projeto Firebase criado, Authentication (e-mail/senha) e Firestore (São Paulo) ativos
- Regras do `firestore.rules` publicadas
- `firebase-config.js` já preenchido com os dados deste projeto

## Falta fazer
1. GitHub: crie um repositório novo (ex.: `contagem-aw`) e suba `index.html` e `firebase-config.js`.
2. Vercel: Add New > Project > importe esse repositório > Deploy. Anote o endereço (ex.: `contagem-aw.vercel.app`).
3. Firebase (projeto Contagem AW): Authentication > Configurações > Domínios autorizados > Adicionar domínio > cole o endereço da Vercel (sem https://).
4. Abra o link, toque em "Primeiro acesso: criar o gestor" e cadastre o gestor da filial. Depois cadastre os usuários na aba Usuários.
5. Importe a planilha do ERP da filial (grupos próprios) para abrir o inventário.

Atualizações do app: troque só o `index.html` no repositório. Não mexa no `firebase-config.js`.
