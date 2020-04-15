# Monitoramento Ubíquo da Saúde Mental: Detectando Padrões de Sociabilidade Enriquecidos pelo Contexto Através do Processamento de Eventos Complexos
## Tradicionalmente, o modelo para o acompanhamento das pessoas que sofrem com problemas relacionados à saúde mental é realizado através de encontros presenciais com profissionais da área (psicólogos e/ou psiquiatras) em uma frequência que varia de acordo com a avaliação do caso, usualmente uma ou duas vezes por semana. No entanto, com o advento e popularização da computação móvel e vestível, que inclui o uso de smartphones, smartwatches (relógios inteligentes), smartbands (pulseiras inteligentes), passou a ser possível se obter uma grande quantidade de informações e se explorar novas formas de interação entre os profissionais da saúde e seus pacientes de forma a complementar o tratamento tradicional, melhorando sua eficácia e eficiência. 

## Nesse contexto, desenvolvemos uma ferramenta capaz de processar inferências de atividades sociais derivadas de dispositivos pervasivos para detectar padrões de sociabilidade sensíveis ao contexto. A ferramenta é uma biblioteca com uma API bem definida em linguagem Java. O reconhecimento dos padrões de sociabilidade é realizado para contextos específicos (por exemplo, dias úteis, dias chuvosos e fins de semana), permitindo a identificação da variabilidade do comportamento em diferentes condições de contexto. A solução desenvolvida também é capaz de identificar mudanças nos padrões de sociabilidade que refletem comportamentos sociais anormais e variações nas rotinas sociais. Esta solução foi implementada com base na combinação da abordagem de Mineração de Padrões Frequentes (FPM) com o Processamento de Eventos Complexos (CEP). 

# Funcionalidades:
- Realiza o aprendizado incremental de padrões de sociabilidade enriquecidos por contexto através da combinação de FPM e CEP. Em particular, a ferramenta detecta os períodos do dia em que o indivíduo geralmente socializa com base em informações contextuais; 
- Identifica mudanças nos padrões de sociabilidade que refletem comportamentos sociais anormais e variações nas rotinas sociais;
- Utiliza a lógica fuzzy para modelar o conhecimento do especialista na tarefa de detecção de comportamentos anormais e mudanças de rotinas sociais;
- Fornece uma API para permitir a rápida implementação de estratégias para detectar padrões de sociabilidade enriquecidos por contexto e configurar o reconhecimento de mudanças comportamentais.

## Basicamente, este projeto contém o código fonte da ferramenta desenvolvida, que pode ser executado em qualquer ambiente com um interpretador java. Após executá-lo, qualquer dispositivo pervasivo pode enviar eventos que represente inferência de situações sociais. Para simular este processo, disponibilizamos um script Python ([aqui](https://github.com/Ivan-Rodrigues/SocialStreamGenerator)) que gera um fluxo de dados para a ferramenta. Este script também recebe as notificações da ferramenta, como padrões de sociabilidade identificados, comportamentos sociais anormais e mudanças de rotinas sociais.

## A documentação completa da ferramenta [aqui](https://www.overleaf.com/read/yhvqffjpqyhq)

# Mais
## [Projeto Ubiquitous Mental Care (UMC)](http://www.lsdi.ufma.br/~iotsaude/)
## [Laboratório de Sistemas Distribuídos Inteligentes (LSDi)](http://www.lsdi.ufma.br/)
## [Universidade Federal do Maranhão (UFMA)](https://portais.ufma.br/PortalUfma/)






"# SocialStreamGenerator" 
