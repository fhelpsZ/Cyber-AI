                                                Cyber-AI

Motor de Análise Heurística contra Phishing e Engenharia Social

O CyberGuard AI é uma aplicação web front-end projetada para atuar como uma primeira linha de defesa (SOC local) contra ataques de phishing, smishing e táticas de engenharia social. O sistema analisa URLs suspeitas e textos de e-mails/mensagens para identificar padrões maliciosos em tempo real.
 
  Objetivo do Projeto

Demonstrar a aplicação prática de conceitos de Cibersegurança e lógica de programação através de um motor de inferência heurística, simulando o processamento inicial de ameaças que antecede a análise profunda por Inteligência Artificial.

 Funcionalidades e Motor Heurístico

O sistema não depende apenas de blacklists estáticas, mas sim de um algoritmo de pontuação de risco baseado em padrões lógicos:

Análise de URL (DOM & Regex):

Detecção de ausência de protocolos seguros (HTTPS).

Identificação de ofuscação por IP direto ao invés de resolução DNS.

Análise de entropia estrutural (tamanho excessivo, uso anômalo de hífens).

Rastreamento de palavras-chave isca (login, verify, secure).

Análise de Texto (Engenharia Social):

Mapeamento de gatilhos psicológicos de urgência ("sua conta será bloqueada").

Detecção de chamadas para ação suspeitas exigindo credenciais.

Identificação de iscas financeiras e prêmios falsos.

💻 Tecnologias Utilizadas

Este projeto foi construído focado em performance, sem dependência de frameworks externos pesados:

HTML5: Estruturação semântica.

CSS3 Avançado: Interface Dark Mode responsiva inspirada em terminais de Operações de Segurança (Blue Team), utilizando Flexbox, animações de varredura e variáveis de estado.

Vanilla JavaScript (ES6+): Lógica do motor de análise, manipulação de Arrays (filter, includes), Expressões Regulares (Regex) e manipulação dinâmica do DOM.

 Roadmap (Próximos Passos)



 Integração com a API do Google Web Risk / VirusTotal.



 Substituição do motor de regex por uma chamada a uma API de LLM (Large Language Model) para análise profunda de contexto em textos complexos.



 Extensão para navegador (Chrome/Edge) para análise em background.

 Autor

Fillipe Melo da Cruz Estudante de Inteligência Artificial e Estudante de Cloud Security.

Email: fillipemelo927@gmail.com
