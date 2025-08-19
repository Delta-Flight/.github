# DeltaFlight

**DeltaFlight** é um ecossistema de softwares interconectados desenvolvidos por estudantes do projeto de extensão **DeltaV Drones**, da Escola Politécnica da Universidade de Pernambuco. O objetivo principal é oferecer um sistema completo para drones, composto por:

- **_Rádio Controle (DeltaRC)_** — o firmware que executa o rádio controle baseado no protocolo ESP-NOW.
- **_Firmware de Controle de Voo (DeltaFC)_** — o firmware que roda na controladora de voo, responsável por estabilização, modos de voo, comunicação com sensores e protocolos de motores/recepção.
- **_Ground Control Station (DeltaGCS)_** — a estação de controle multiplataforma que permite configuração e monitoramento via interface gráfica.

---

## Repositórios

| Repositório | Descrição |
|-------------|---------------------|
| [**DeltaRC**](https://github.com/Delta-Flight/DeltaRC) | Firmware para rádio controle, comunicando-se via protocolo ESP-NOW e projetado para uso com veículos de controle remoto de curto alcance.
| [**DeltaFC**](https://github.com/Delta-Flight/DeltaFC)  | Firmware para controladora de voo ESP32, com suporte a múltiplos protocolos de ESC, receptores, sensores e modos de voo, além de integração com DeltaGCS.
| [**DeltaGCS**](https://github.com/Delta-Flight/DeltaGCS) | Aplicativo de Estação de Controle (Ground Control Station) multiplataforma, que permite monitorar o status de voo, configurar e controlar o sistema de voo.

---

## Sobre nós

Este projeto é uma iniciativa do **projeto de extensão DeltaV Drones**, composto por estudantes da **Escola Politécnica da Universidade de Pernambuco** (UPE). O desenvolvimento do DeltaFlight busca ampliar a experiência acadêmica na área de drones de forma integral, envolvendo desde o desenvolvimento de software (firmware, protocolos de comunicação, interfaces gráficas) até a parte de hardware, incluindo a montagem de frames, integração de sensores e testes em campo.


Se quiser saber mais, sugerir ideias ou colaborar, entre em contato conosco através do nosso [site!](deltavquad.github.io)
