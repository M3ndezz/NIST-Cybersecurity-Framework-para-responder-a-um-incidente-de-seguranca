## Cenário 🚨

Você é analista de segurança cibernética e trabalha para uma empresa de multimídia que oferece serviços de Web design, design gráfico e soluções de marketing de mídia social para pequenas empresas. Sua organização sofreu recentemente um ataque DDoS, que comprometeu a rede interna por duas horas até ser resolvido.

Durante o ataque, os serviços de rede de sua organização pararam de responder repentinamente devido a um fluxo de entrada de pacotes ICMP. O tráfego normal da rede interna não conseguia acessar nenhum recurso da rede. A equipe de gerenciamento de incidentes respondeu bloqueando a entrada de pacotes ICMP, interrompendo todos os serviços de rede não críticos off-line e restaurando os serviços de rede críticos.

Em seguida, a equipe de segurança cibernética da empresa investigou o evento de segurança. Eles descobriram que um agente mal-intencionado havia enviado um ataque flood de pings ICMP para a rede da empresa por meio de um firewall não configurado. Essa vulnerabilidade permitiu que o invasor mal-intencionado sobrecarregasse a rede da empresa por meio de um ataque distribuído de negação de serviço (DDoS).

- Uma nova regra de firewall para limitar a taxa de entrada de pacotes ICMP

- Verificação do endereço IP de origem no firewall para verificar se há endereços IP falsos nos pacotes ICMP recebidos

- Software de monitoramento de rede para detectar padrões de tráfego anormais

- Um sistema IDS/IPS para filtrar algum tráfego ICMP com base em características suspeitas

## Objetivo 🎯

Criar um plano para melhorar a segurança de rede da sua empresa, seguindo a Estrutura de Segurança Cibernética (CSF) do Instituto Nacional de Padrões e Tecnologia (NIST). Utilizar o CSF para ajudá-lo a navegar pelas diferentes etapas de análise desse evento de segurança cibernética e integrar sua análise a uma estratégia geral de segurança.

## Modelo 📋

- **Identificar:** riscos de segurança por meio de auditorias regulares de redes internas, sistemas, dispositivos e privilégios de acesso para identificar possíveis lacunas na segurança.

- **Proteger:** os ativos internos por meio da implementação de políticas, procedimentos, treinamento e ferramentas que ajudem a mitigar as ameaças à segurança cibernética.

- **Detectar:** possíveis incidentes de segurança e melhorar os recursos de monitoramento para aumentar a velocidade e a eficiência das detecções.

- **Responder:** para conter, neutralizar e analisar incidentes de segurança; implementar melhorias no processo de segurança.

- **Recuperar:** os sistemas afetados para a operação normal e restaurar os dados e/ou ativos dos sistemas que tenham sido afetados por um incidente.

## Glossário 📖

- **Ataque de negação de serviço (DoS):** Um ataque que visa uma rede ou servidor e o inunda com tráfego de rede.

- **Ataque distribuído de negação de serviço (DDoS):** Um tipo de ataque de negação de serviço que usa vários dispositivos ou servidores localizados em diferentes locais para inundar a rede-alvo com tráfego indesejado.

- **Inundação do Protocolo de Mensagens de Controle da Internet (ICMP):** Um tipo de ataque DoS realizado por um invasor que envia repetidamente pacotes de solicitação ICMP a um servidor de rede.
