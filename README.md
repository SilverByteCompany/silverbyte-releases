# Silverbyte — instaladores e atualizações

Este repositório distribui os instaladores do Silverbyte Home e os pacotes Windows dos aplicativos Silverbyte.

## Baixar

As versões aprovadas aparecem em [Releases](https://github.com/SilverByteCompany/silverbyte-releases/releases). Enquanto não houver uma versão publicada, não há download público disponível.

## Atualizações pelo Home

A partir do Home 0.5.6, o launcher consulta este repositório e verifica a assinatura digital dos metadados e o SHA-256 dos arquivos antes de instalar uma atualização. Cada aplicativo é atualizado separadamente, preservando os dados do usuário.

- **Estável:** versões aprovadas pelo responsável.
- **Beta:** também recebe versões de teste, conforme a preferência escolhida no Home.
- **Rascunhos:** preparação do responsável; não são distribuídos aos usuários.

A publicação só fica disponível no computador de desenvolvimento autorizado. Contas do launcher continuam locais nesta etapa; o repositório de atualizações não sincroniza perfis.

## Conteúdo

Cada versão contém seu pacote e `silverbyte-release.json`, com versão, canal, notas, tamanho, hash e assinatura Ed25519. A chave privada e as credenciais de publicação não são distribuídas no instalador.

Este repositório contém arquivos de distribuição e não concede licença de reutilização do código ou das marcas Silverbyte.
