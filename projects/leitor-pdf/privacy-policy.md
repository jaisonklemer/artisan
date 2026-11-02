---
layout: page
lang: pt-BR
title: Política de privacidade — Leitor PDF
permalink: /leitor-pdf/privacy-policy
---

Última atualização: 2 de novembro de 2026.

## 1. Aplicativo e contato

Esta política explica o tratamento de dados pelo Leitor PDF para Android (`com.androidhub.pdfreader`), disponibilizado sob o nome público **MobileCineApps**.

Para dúvidas sobre privacidade ou solicitações relacionadas a dados, escreva para [mobilecineapps@gmail.com](mailto:mobilecineapps@gmail.com). Não envie documentos ou informações sensíveis que não sejam necessários para explicar sua solicitação.

## 2. Documentos e processamento no aparelho

O aplicativo utiliza os PDFs que você abre para exibir páginas, extrair texto disponível para seleção e cópia, adicionar marcações, comentários, desenhos e assinaturas visuais e salvar cópias com alterações. Se você escolher uma imagem para assinatura, ela será lida para exibição e incorporada ao PDF ao posicioná-la. Uma assinatura visual não equivale a uma assinatura digital com certificado.

No fluxo normal de leitura e edição, o aplicativo copia o documento para uma sessão em seu armazenamento privado. Ao editar, pode criar e preservar um rascunho para continuar o trabalho. Documentos e imagens podem conter dados pessoais seus ou de outras pessoas.

Também são utilizados localmente:

- Nome, referência de acesso, número de páginas e horário de acesso para apresentar até dez documentos recentes e tentar reabri-los.
- Preferências, como tema, tela ligada, lembrança da última página e estado dos avisos de acesso a arquivos.
- Posição de leitura associada ao documento, quando essa opção está ativa, e referência da última cópia exportada.
- Texto e imagens das páginas, imagem de assinatura e estados de edição em memória para renderizar e desfazer ou refazer alterações.

## 3. Permissões e biblioteca de PDFs

Você pode abrir PDFs e selecionar imagens pelo seletor de documentos do Android. O aplicativo tenta conservar as autorizações de acesso aos itens escolhidos quando o Android e o provedor permitirem.

A biblioteca consulta PDFs indexados no armazenamento compartilhado. Ela utiliza nomes, referências de acesso, tamanhos e datas de modificação para apresentar até 500 candidatos PDF, ordenados pela data de modificação. A identificação por tipo ou extensão não garante que todo candidato seja um PDF válido. A biblioteca não é uma varredura completa do aparelho e não inclui, por esse mecanismo, documentos em nuvem, áreas privadas de outros aplicativos ou todos os arquivos não indexados.

No Android 11 e posteriores, a biblioteca implementada depende da autorização especial de acesso a todos os arquivos. Essa autorização pode permitir tecnicamente leitura e escrita mais amplas do que a seleção de um único documento. A descoberta na biblioteca consulta o índice para leitura; a edição normal utiliza cópias privadas. Em versões antigas compatíveis, a biblioteca utiliza a permissão de leitura do armazenamento. No Android 10, o aplicativo orienta o uso do seletor em vez da busca ampla.

Você pode recusar ou revogar o acesso amplo nas configurações do Android e continuar abrindo documentos específicos pelo seletor. Revogar uma permissão pode impedir a reabertura de itens que dependam dela, mas não deve ser entendido como exclusão dos arquivos ou das cópias de trabalho já existentes.

## 4. Transferências e serviços externos

A leitura e a edição descritas nesta política são realizadas no dispositivo. No código-fonte consultado, não foram identificados conta do aplicativo, publicidade, analytics ou componente próprio de envio automático de documentos. Essa constatação é baseada na revisão do código-fonte, não em uma verificação completa do artefato de distribuição, de todas as dependências resolvidas ou de seu comportamento em execução. O processamento por bibliotecas incorporadas não significa, por si só, envio dos PDFs aos autores dessas bibliotecas.

Quando você copia texto, o trecho selecionado é colocado na área de transferência do Android. Seu tratamento pelo sistema e por outros aplicativos depende das configurações e permissões deles.

Ao exportar ou compartilhar um PDF, você escolhe o destino ou aplicativo que receberá o documento. Um provedor de armazenamento em nuvem, e-mail ou outro serviço escolhido pode transmitir e processar o conteúdo conforme suas próprias práticas. MobileCineApps não controla o uso ou a retenção realizados pelo destinatário escolhido.

Se você entrar em contato por e-mail, sua mensagem e os dados que incluir serão tratados para responder à solicitação. Não envie PDFs pessoais para obter suporte quando uma descrição sem o documento for suficiente. O serviço de e-mail utilizado também está sujeito às práticas de seu provedor.

## 5. Retenção e exclusão

As cópias de trabalho e os rascunhos ficam no armazenamento privado do aplicativo. Fechar o documento ou voltar à tela inicial pode preservar o rascunho. Não há prazo automático de expiração em dias implementado para essas sessões.

O descarte de uma sessão solicita a exclusão de seu diretório de trabalho. Remover um documento dos recentes remove esse registro e tenta liberar sua autorização persistente de leitura; não apaga o documento original e não equivale a limpar todas as sessões, posições de leitura, referências de exportação, preferências ou autorizações de imagens.

Você pode usar os controles de armazenamento do Android para limpar os dados locais do aplicativo. A desinstalação normalmente remove seu armazenamento privado. O comportamento de backup ou transferência entre aparelhos pode depender do sistema e do fabricante; a configuração fonte do aplicativo desabilita backup automático, mas não há garantia universal contra toda forma de transferência do sistema.

Cópias exportadas para pastas, provedores ou outros aplicativos não são apagadas por limpar os dados ou desinstalar o Leitor PDF; devem ser gerenciadas nos respectivos destinos. A exclusão lógica não garante apagamento físico irrecuperável da mídia.

Mensagens de suporte não são removidas ao limpar os dados ou desinstalar o aplicativo. Para solicitar sua exclusão ou esclarecer retenção relacionada ao atendimento, use o contato acima. Esta política não estabelece prazo fixo de retenção para mensagens de e-mail.

## 6. Proteção dos dados

O aplicativo usa armazenamento privado do Android para sessões de trabalho e concede acesso ao documento ao aplicativo escolhido para compartilhamento. A proteção também depende do sistema Android, do bloqueio do aparelho e dos serviços que você selecionar. Não há promessa de criptografia própria dos PDFs, segurança absoluta ou controle sobre documentos entregues a terceiros.

## 7. Acesso a esta página

Esta página é hospedada no GitHub Pages. Ao acessá-la, o navegador se comunica com a infraestrutura do GitHub, que pode tratar dados técnicos de acesso conforme a [Declaração de Privacidade do GitHub](https://docs.github.com/pt/site-policy/privacy-policies/github-general-privacy-statement). Isso é distinto do processamento local dos PDFs pelo aplicativo. Não é necessário enviar um PDF para consultar esta política.

## 8. Alterações

Esta política pode ser atualizada para refletir mudanças nas funcionalidades ou no tratamento de dados. A data da última atualização será indicada no início da página. A versão pública estará disponível em [Política de privacidade do Leitor PDF](https://jaisonklemer.github.io/artisan/leitor-pdf/privacy-policy).
