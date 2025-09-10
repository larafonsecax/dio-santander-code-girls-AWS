# 💻 Introdução à AWS 
## 🌐 Infraestrutura Global da AWS
- Características principais:
   - Plataforma de nuvem mais segura, abrangente e confiável.
   - Oferece mais de 200 serviços em todo o mundo.
   - Infraestrutura para implantar workloads com latência inferior a 10 milissegundos, próxima aos usuários finais.

- Regions e Availability Zones:
  - Regions: Áreas geográficas com múltiplas Availability Zones.
  - Availability Zones: Data centers independentes, conectados logicamente para alta disponibilidade (mínimo 2, máximo 3 por região).
  - Atualmente: 105 zonas de disponibilidade em 33 regiões geográficas, com planos para mais 12 zonas e 4 regiões (Alemanha, Malásia, Nova Zelândia, Tailândia).

- Tolerância a falhas:
  - Regiões são isoladas para maior estabilidade.
  - Recursos não são replicados automaticamente entre regiões, exigindo configuração manual.
 
- Pontos para escolher uma região:
  - Compliance
  - Disponibilidade de serviços
  - Custo
  - Latência


## 💲 Modelo de Negócio
- Modelo OPEX (Pagamento por Uso):
   - Diferente do modelo CAPEX (infraestrutura física inicial), não exige grande investimento inicial.
   - Pricing flexível: Paga-se apenas pelos recursos consumidos.
- Variedade de serviços:
  - Computação, armazenamento, banco de dados, machine learning, IoT, análise de dados, entre outros.
- Benefícios do modelo cloud:
  - Escalabilidade, baixo custo inicial, acesso imediato, alta disponibilidade.
 
## ☁️ Tipos de Nuvem
| Modelo | Vantagens | Desvantagens |
|----------|----------|----------|
| Pública | Baixo custo, escalabilidade, acesso rápido | Maior risco de privacidade |
| Híbrida | Flexibilidade, escalabilidade, segurança | Requer integração mais complexa |
| Privada | Controle total,  maior segurança	| Alto investimento e custo contínuo |

## 🖥️ Modelos de Serviços em Nuvem
| Modelo | Nome | Exemplos de uso | Palavra-chave | 
|----------|----------|----------|----------|
| SaaS | Software as a Service | E-mail, CRM, ERP | USE |
| PaaS | Platform as a Service | Desenvolvimento de apps, streaming, web, suporte a decisões | CONSTRUA |
| IaaS | Infrastructure as a Service | Sistemas legados, servidores de arquivos, segurança, cache| MIGRE |

## Serviços Gerenciados
- Alta escalabilidade:
   - Suporta sistemas de grande porte, como Amazon.com, Netflix e sistemas bancários.
- Robustez:
   - Infraestrutura capaz de atender alta demanda com confiabilidade.
     
## Práticas de Segurança
- Recomendações:
1. Criar conta root e protegê-la.
2. Não compartilhar credenciais.
3. Monitorar e-mails de cobrança.
4. Usar autenticação multifator (MFA).
5. Estabelecer barreiras de proteção para permissões.

## IAM (Identity and Access Management)
- Função: Gerencia usuários, grupos e permissões na plataforma AWS.
- Importância: Estrutura central para provisionamento de acessos.
- Políticas e permissões: Configurações detalhadas para controle de acesso.

## Formas de Acesso à Plataforma AWS
- AWS Console:
  - Interface gráfica amigável para gerenciar serviços, contas e perfis.
- AWS CLI (Command Line Interface):
  - Ferramenta de linha de comando para interagir com a AWS via terminal, utilizando credenciais.
- Cloud Shell:
  - Ambiente de linha de comando baseado em Python, pré-configurado, para criar recursos diretamente na plataforma.

## Controle de Gastos e Alertas
  - Ferramentas disponíveis para monitoramento e configuração de alertas de custos, garantindo controle financeiro.

## Aplicações Práticas da AWS
- Casos de uso:
1. Aumentar recursos de TI usando a nuvem.
2. Migrar aplicativos e dados existentes para a nuvem.
3. Construir novos aplicativos, sites, serviços e linhas de negócios.

## Inovação e Adaptabilidade
- A AWS se destaca pela inovação constante e adaptação às necessidades de empresas de todos os tamanhos e setores.

		

  
 
  


