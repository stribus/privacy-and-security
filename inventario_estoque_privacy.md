# Política de Privacidade - Inventário de Estoque

Esta política de privacidade descreve como o aplicativo **Inventário de Estoque** lida com suas informações.

## 1. Coleta de Informações
O aplicativo coleta apenas os dados necessários para o seu funcionamento local de gestão de estoque:
- Nomes de produtos, códigos SKU (opcionais), categorias e unidades de medida.
- Registros de quantidades em estoque, quantidades a comprar e marcações de urgência.
- Nome do perfil de usuário (opcional, utilizado apenas para identificar o autor do inventário no histórico local).

**Nenhum dado pessoal identificável ou sensível é coletado pelo desenvolvedor ou enviado para servidores externos.**

## 2. Armazenamento de Dados
O aplicativo foi desenvolvido com foco em privacidade e funcionamento offline. Todos os dados são armazenados localmente no seu dispositivo utilizando criptografia padrão do sistema Android (quando disponível) e banco de dados SQLite (Room). Não existe sincronização com servidores na nuvem controlados pelo desenvolvedor.

## 3. Uso de Permissões
Para habilitar todas as funcionalidades, o aplicativo solicita as seguintes permissões:
- **Câmera**: Para escanear QR Codes gerados por outros dispositivos para sincronização de catálogo.
- **Bluetooth e Localização**: Necessários para a tecnologia *Google Nearby Connections* e *Bluetooth LE*, permitindo a sincronização P2P (ponto-a-ponto) de dados entre aparelhos próximos. A localização não é utilizada para rastreamento geográfico, sendo uma exigência técnica do Android para detecção de dispositivos próximos.
- **Acesso ao Armazenamento (opcional)**: Para salvar arquivos de lista de compras (CSV/JSON) na pasta de Documentos do dispositivo.

## 4. Compartilhamento de Dados
O compartilhamento de dados ocorre exclusivamente por iniciativa do usuário:
- **Sincronização P2P**: Ao optar por enviar ou receber catálogo via Bluetooth ou QR Code.
- **Exportação via WhatsApp**: Ao clicar no botão de compartilhamento para enviar a lista de compras formatada para contatos ou grupos.
- **Exportação de arquivos**: Ao gerar arquivos CSV/JSON para uso externo.

## 5. Segurança
Como os dados residem no dispositivo do usuário, a segurança dos dados também depende da proteção do próprio aparelho (senhas, biometria). Recomendamos o uso de proteções nativas do Android para garantir que apenas pessoas autorizadas acessem o inventário local.

## 6. Direitos do Usuário e Exclusão de Dados
Você tem controle total sobre seus dados. Para excluir todas as informações cadastradas no aplicativo, você pode:
1. Utilizar a opção de "Limpar Dados" nas configurações do sistema Android para este app.
2. Desinstalar o aplicativo, o que removerá permanentemente o banco de dados local.

## 7. Alterações nesta Política
Esta política pode ser atualizada ocasionalmente para refletir melhorias no aplicativo. Recomendamos a revisão periódica desta página.

## 8. Contato
Para dúvidas ou suporte, entre em contato através de: [flavio.a.toldo@fatoldo.com.br](mailto:flavio.a.toldo@fatoldo.com.br).

---
*Última atualização: 11 de janeiro de 2026*
