Changelog

Todas as alterações notáveis neste projeto serão documentadas neste arquivo.

[1.0.0] - 2025-11-25

Adicionado

Versão estável do aplicativo lançada.

Sistema de Modo Offline implementado para garantir funcionamento sem internet.

Implementação de Trava de Segurança (Senha) no arquivo setup.html.

Lista expandida para 200 frases motivacionais (40 por categoria).

Corrigido

Correção Crítica no Firestore: Ajustada a estrutura de caminhos do banco de dados para respeitar a regra de segmentos pares (Coleção > Documento). Caminho antigo gerava erro invalid-argument.

Correção de Autenticação: Resolvido bug api-key-not-valid garantindo que as credenciais corretas sejam carregadas.

Correção de UI: Ajuste no carregamento do Tailwind CSS para evitar flash de estilo.

[0.5.0] - 2025-11-24

Alterado

Migração de React para HTML/JS Puro para facilitar hospedagem simples.

Remoção do sistema de Login com Senha, substituído por Login por Nome (UX simplificada).

[0.1.0] - 2025-11-23

Inicial

Criação do protótipo inicial.

Integração básica com Firebase.

Lógica de quebrar o biscoito (animação CSS).