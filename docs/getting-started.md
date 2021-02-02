---
id: getting-started
title: Comienza Aquí
sidebar_label: Comienza Aquí
---

Bienvenido a la Wiki de Polkadot! Esta fuente de verdad contiene guías para interactuar con la
funcionalidad central del sistema. Nuestra wiki tiene tres secciones principales: Aprender (para
quienes están aprendiendo), Desarrolla (para quienes quieran desarrollar en Polkadot), y Mantener
(para quiene quieran mantener la red).

## Qué es Polkadot?

Polkadot hace posible la escalabilidad a través de permitir que blockchains especializados se
comuniquen entre ellos en forma segura, en un ambiente que no requiere confianza entre partes.

Polkadot esta desarrollado para conectar y asegurar blockchains únicas, ya sean redes públicas, sin
necesidad de permisos, redes privadas, oráculos u otras tecnologías de la Web3. Además, hace posible
un internet donde blockchains independientes puedan intercambiar información debajo de ciertas
garantías de seguridad.

Polkadot es una red viva que tiene como pilares fundamentales a la Governanza y Capacidad de
Actualización. La red contiene un conjunto avanzado de herramientras de gobierno y, haciendo uso del
estándard [WebAssembly](https://webassembly.org/) como "meta-protocolo", puede realizar
actualizaciones de la red de forma autónoma. Polkadot se adapta a las nuevas necesidades sin el
riesgo de las bifurcaciones de red.

> Nota: Si nunca has escuchado de Governanza, una gran forma de empezar es ir a la
> [Página de Governanza](learn-governance)

Al conectar estos puntos (_dots_), Polkadot se convierte en una parte fundacional de la web
decentralizada, donde los usuarios controlan su información personal y no están limitados por los
límites de confianza dentro de la red.

## Por qué Polkadot?

Allá por los comienzos de los 2000's, cuando internet ganaba popularidad por primera vez, internet
tenía páginas web básicas, que permitían solamente lectura y eran estáticas. El mundo conectado
online era el principio de la información virtual, identidades y más. El internet de ese entonces es
conocido como la Web 1.0.

A medida que las pataformas de Redes Sociales y negociones online emergieron, internet se transformó
en la Web 2.0. Este internet actualizado, que todavía usamos hoy, contiene páginas web dinámicas,
interactivas, donde los usuarios pueden leer y escribir información, publicando sus ideas para que
otros las vean. Sin embargo esta versión de la web tiene inconvenientes relacionados como el control
datos, problemas de privacidad y confianza. Es aquí donde la Web 3.0 tiene un rol.

La Web 3.0 transforma aplicaciones centralizadas en protrocolos decentralizados que no requieren
confianza. El objectivo es transformar internet en una red decentralizada, donde los usuarios
controlan sus datos e identidad en un ambiente que no requiere confianza. El movimiento de Web 3.0
busca remover intermediarios y construir una infraestructura que no requiera de confianza entre
partes.

> Para aprender más del moviemiento de Web3, mira el siguiente video de la
> [Conferencia Web3](https://youtu.be/l44z35vabvA)

## Cómo funciona Polkadot?

La red de Polkadot utiliza un
[modelo de shard](<https://es.wikipedia.org/wiki/Shard_(arquitectura_de_base_de_datos)>) donde cada
shard o fragmento - llamado "[parachains](learn-parachains)", permite que las transacciones sean
procesadas en paralelo en lugar de en serie. Cada parachain en la red contiene una única función de
transición de estado (STF por sus siglas en inglés). Basado en el diseño de Polkadot, mientras la
lógica de una parachain pueda ser compilada a Wasm y se adhiera a la API de la Relay Chain (cadena
de relés), entonces una parachain puede conectarse a la red de Polkadot.

Polkadot tiene una Relay Chain que actúa como la cadena principal del sistema. Las parachains
construyen y proponen bloques a ser varlidados por la Relay Chain, donde los bloques se someten a
rigurosos chequeos de [disponibilidad y validez](learn-availability) antes de ser agregados a la
cadena finalizada. Como la Relay Chain provee las garantías de seguridad, los
[collators (intercaladores)](learn_collator) - son nodos completos de las parachains - no tienen
responsabilidad en la seguridad y por ende no requieren de un sistema robusto de incentivos. Así es
como la red se mantiene actualizada con las muchas transacciones que ocurren.

![polkadot-relay-chain](assets/polkadot_relay_chain.png)

Para poder interactuar con cadenas que tienen su propio proceso de finalización (por ejemplo
Bitcoin), Polkadot tiene [parachains puente](learn-bridges) que ofrencen compatibilidad
bidireccional, lo que significa que se pueden hacer transaciones entre las distitnas parachains.

El [Protocolo de Mensajería entre cadenas (XCMP)](learn-crosschain) permite el envío de distintos
tipos de mensajes entre las distintas parachains. El sistema de seguridad compartida junto con la
lógica de validación de la Relay Chain proveen el ecosistema necesario para el paso de mensajes en
un ambiente que no requiere confianza, habilitando así la verdadera interoperabilidad.

> Para ver una animación pequeña, pensada para principiantes, puedes ver el
> [Video Explicativo de Polkadot](https://www.youtube.com/watch?v=_-k0xkooSlA)

## Por qué tu deberías usar Polkadot?

Ya sea que eres un Desarrollador de Blockchain o si estás interesado en ser parte de la
[Comunidad de Polkadot](https://polkadot.network/polkadot-ambassador-program/), Polkadot ofrece una
plataforma para todos. Esta wiki es el lugar para que desarroladores y mantenedores utilicen
distintas [herramientas](build-tools-index) y para que quienes quieran aprender tengan todo el
material educativo a disposición.

## Cómo empezar

Para quienes recién comienzan a aprender Blockchain:

- El [Curso en Fundamentales de Blockchain][mooc] es una gran herramienta para familiarizarse con
  criptografía, conceptos de blockchain, decenrtalización, redes, criptomoneda, y más. Este curso es
  recomendado para usuarios de todos los niveles. Además, es gratis.

Para quienes recién comienzan a aprender acerca de Polkadot:

- El [White paper de Polkadot][white-paper] es un resumen técnico de una de las posibles direcciones
  de implementación de la red Polkadot. Este documento utiliza detalles técnicos y lógicos para
  justificar por qué dicha dirección es benficiosa. Este documento también explica cómo funcionan
  los distintos compoenentes de Polkadot y cómo trabajan en conjunto.
- El [Documento de descripción general de Polkadot][overview-paper] es una versión actualizada del
  whitepaper que describe el protocol en términos más técnicos. Recomendamos leer este documento si
  se está interesado en explorar más a detalle el protocolo.
- El [Documento de Presentación][light-paper] es más visual, fácil de leer, y menos técnico. El
  documento se adentra en los componentes de Polkadot, pero es entendible para lectores técnicos y
  no técnicos.
- La [Especificación de Polkadot][spec] es un repositorio de Github que contiene la información más
  actualizada del protocolo Host de Polkadot, la especificación de las pruebas de los distintos
  componentes de la red, y de la lógica de ejecución (Runtime) de Polkadot. Este repositorio
  contiene algoritmos y explora el funcionamiento de varios procesos en la red Polkadot. La
  Especificación de Polkadot toma ideas y conceptos de los distintos documentos, pero se focaliza en
  los aspectos más técnicos del a tecnología.
- [Ver videos de Explicación Ténica][teched videos]. Estos videos son una buena introducción para
  explicar y demostrar comó usar Polkadot is su [Interfaz de Usuario][ui].
- Leer [What is Polkadot? A Brief Introduction][article] en Medium. Existen otros muy buenos
  documentos en el [Medium de Polkadot][p medium] o [Medium de Web3 Foundation][w medium].
- [Crear una cuenta en Polkadot][account generation]
- [Envío de una Transferencia de Saldo][transfer]
- [Participación (Staking) como Nominador][nominator]
- [Ser un Validador][validator]
- [Crear una Identidad][identity]
- [Crear una cuenta Proxy][proxy]
- [Realizar una propuestsa y votar una Referanda][democracy]
- [Postularse para el Consejo][council]
- [Votar Consejales][council voting]
- [Usar Fondos del Tesoro][treasury]

Para quienses quieren aprender de Kusama, la red canaria de Polkadot: Para aprender más acerca de
cómo desarrollar y mantener en la red Kusama, por favor ver la [Guía de Kusama][kusama guide].

## Recursos

- [Polkadot Crowdcast](https://www.crowdcast.io/polkadot) - Listado de todos los eventos en
  Crowdcast que realizó la Fundación Web3.
- [Explorador de Polkadot](https://polkadot.js.org/apps/#/explorer) - Navegador de la red de
  Polkadot. Puede usarse para Polkadot, Kusama, o cualquier otra red basada en Substrate.
- [Polkascan](http://polkascan.io/) \- Información en tiempo real de la Relay Chain de Polkadot y
  otras cadenas basadas en Substrate.
- [Subscan.io](https://subscan.io) - Navegador para cadenas basadas en Substrate.
- [Descripción general de Polkadot](https://youtu.be/lIghiCmHz0U) - El Dr. Gavin Wood presenta una
  descripción general de Polkadot. (Video)
- [Descripción general de Polkadot](https://techcrunch.com/video/fireside-chat-with-jutta-steiner-parity-technologies/) -
  La Dra. Jutta Steiner presenta Polkadot. (Video)
- [Descripción general de Polkadot y Substrate](https://www.youtube.com/watch?v=0IoUZdDi5Is&feature=youtu.be) -
  El Dr. Gavin Wood presenta Substrate (Kit de Blockchain) y Polkadot, y desarrolla un blockchain en
  el escanario en 30 minutos usando Substrate. (Video)
- [Comunidad / Ecosistema](community) - Listado de canales de comunicación y otros recuros sobre
  Polkadot.
- [Aplicaciones Ejemplo](build-examples-index) - Ejemplo de aplicaciones que se han desarrolado o
  están siendo desarrolladas en Polkadot.
- [Guía para Contribuir](contributing) - Reglas para Contribuir a la Wiki.
- [Base de Conocimiento de Polkadot](https://support.polkadot.network/) - Recursos de resolución
  para errores y problemas específicos.

[mooc]: https://mooc.web3.foundation/course/blockchain-fundamentals/
[white-paper]: https://polkadot.network/PolkaDotPaper.pdf
[overview-paper]: https://github.com/w3f/research/blob/master/docs/papers/OverviewPaper-V1.pdf
[light-paper]: https://polkadot.network/Polkadot-lightpaper.pdf
[spec]: https://github.com/w3f/polkadot-spec
[teched videos]: https://www.youtube.com/watch?v=mNStMPZjiHM&list=PLOyWqupZ-WGuAuS00rK-pebTMAOxW41W8
[article]: https://medium.com/polkadot-network/what-is-polkadot-a-brief-introduction-ca3eac9ddca5
[p medium]: https://medium.com/polkadot-network
[w medium]: https://medium.com/web3foundation
[ui]: https://polkadot.js.org/apps/
[account generation]: learn-account-generation
[transfer]: learn-balance-transfers
[nominator]: maintain-guides-how-to-nominate-polkadot
[validator]: maintain-guides-how-to-validate-polkadot
[identity]: learn-identity
[proxy]: learn-proxies
[democracy]: maintain-guides-democracy
[council]: maintain-guides-how-to-join-council
[council voting]: maintain-guides-how-to-vote-councillor
[treasury]: learn-treasury
[kusama guide]: https://guide.kusama.network/
