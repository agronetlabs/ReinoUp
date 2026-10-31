<div align="center">
  <img src="assets/reinoup-logo.webp" alt="ReinoUp" width="480" />
  <h1>Aprender a Bíblia brincando</h1>
  <p>Histórias narradas, descobertas e jogos para a criança participar da aprendizagem.</p>
  <p><a href="https://reinoup.com"><strong>Conheça o aplicativo</strong></a> · <a href="https://reinoup.com/app/historias">Explore as histórias</a> · <a href="https://github.com/agronetlabs/ReinoUp/issues/new/choose">Envie uma sugestão</a></p>
</div>

<p align="center">
  <a href="https://github.com/agronetlabs"><img alt="Uma criação AgroNet Labs" src="https://img.shields.io/badge/AgroNet_Labs-ReinoUp-173F35?style=for-the-badge" /></a>
  <a href="#engenharia-e-criação-com-ia"><img alt="Desenvolvido com OpenAI Codex" src="https://img.shields.io/badge/OpenAI_Codex-Desenvolvimento-111111?style=for-the-badge" /></a>
  <a href="https://reinoup.com"><img alt="Experiência Web e PWA" src="https://img.shields.io/badge/Web_%2B_PWA-Experimente-2563EB?style=for-the-badge" /></a>
  <a href="#onde-experimentar"><img alt="Android em teste fechado" src="https://img.shields.io/badge/Android-Teste_fechado-3DDC84?style=for-the-badge&amp;logo=android&amp;logoColor=163024" /></a>
</p>
<p align="center">
  <a href="https://reinoup.com/app/historias"><img alt="A Criação: acesso gratuito" src="https://img.shields.io/badge/A_Cria%C3%A7%C3%A3o-Acesso_gratuito-F4BC38?style=for-the-badge" /></a>
  <a href="#uma-experiência-para-ouvir-explorar-e-jogar"><img alt="Vozes produzidas com ElevenLabs" src="https://img.shields.io/badge/ElevenLabs-Narra%C3%A7%C3%A3o-111111?style=for-the-badge" /></a>
  <a href="#como-é-construído"><img alt="Mídia entregue por Cloudflare Stream" src="https://img.shields.io/badge/Cloudflare_Stream-V%C3%ADdeos-F38020?style=for-the-badge&amp;logo=cloudflare&amp;logoColor=white" /></a>
  <a href="docs/evolucao.md"><img alt="Melhorias orientadas por feedback" src="https://img.shields.io/badge/Feedback-Melhorias_documentadas-256D46?style=for-the-badge" /></a>
</p>

**Uma jornada bíblica feita para a criança participar.** Ouvir uma história, explorar uma cena, encontrar uma palavra e celebrar uma descoberta: o ReinoUp reúne essas experiências em um aplicativo com identidade visual própria e orientação por voz.

## Quem está construindo

O ReinoUp é construído por **Leandro Lemos e Ramon Ferreira**, com a **[AgroNet Labs](https://github.com/agronetlabs)** e o apoio do **OpenAI Codex** no desenvolvimento. A criação combina decisões humanas de produto, programação assistida por IA e produção audiovisual.

Este espaço apresenta o produto, as decisões de experiência e sua evolução. Aqui você pode conhecer o trabalho, acompanhar melhorias e conversar diretamente com quem o constrói.

## Uma experiência para ouvir, explorar e jogar

A primeira história, **A Criação**, tem acesso gratuito. O Cordeirinho recebe a criança e acompanha uma jornada com imagens, narração e atividades interativas.

| Experiência | O que a criança encontra |
| --- | --- |
| Histórias bíblicas | Cenas audiovisuais, narração e legendas. |
| Jogos | Atividades como caça-palavras, memória e quebra-cabeça. |
| Desafios | Descobertas e tarefas com orientação narrada. |
| Recompensas | Talentos, progresso e um baú que celebra as conquistas. |
| Área dos pais | Um acesso separado para os responsáveis. |

A voz feminina **Clara**, usada nas interações dos jogos, também participa das celebrações. O objetivo é oferecer orientação que a criança possa ouvir enquanto brinca.

<table>
  <tr>
    <td align="center"><img src="assets/cordeirinho.webp" alt="Cordeirinho, mascote do ReinoUp" width="200" /><br /><strong>Nosso Cordeirinho</strong></td>
    <td align="center"><img src="assets/bau-recompensas.webp" alt="Ilustração do baú de recompensas" width="240" /><br /><strong>Celebrar cada conquista</strong></td>
  </tr>
</table>

## Melhorias que começam com quem usa

Os comentários recebidos viram ajustes verificáveis no aplicativo. Alguns exemplos:

- **Baú de Recompensas:** nova ilustração, comemoração narrada e redução de 20% do tamanho após avaliação no celular.
- **Saldo de talentos:** tocar no indicador agora abre um painel com a quantidade disponível e uma explicação das recompensas.
- **Caça-palavras:** seleção por arraste, mantendo a alternativa de tocar na primeira e na última letra, com orientação e comemoração narradas.

[Veja os três exemplos e como foram verificados →](docs/evolucao.md)

<details>
  <summary>Veja uma partida concluída no caça-palavras</summary>
  <p><img src="assets/caca-palavras.png" alt="Caça-palavras do ReinoUp com sete palavras encontradas e controles de narração" width="360" /></p>
  <p>Captura de validação no navegador. A interface pode evoluir entre versões.</p>
</details>

## Onde experimentar

- **Web:** [reinoup.com](https://reinoup.com).
- **PWA:** experiência web instalável em dispositivos compatíveis.
- **Android:** em fase de testes na Google Play. A distribuição aos participantes segue a liberação de cada versão na faixa de testes.

O lançamento público na Google Play ainda não é anunciado aqui. Esta apresentação foi atualizada em **31 de outubro de 2026**.

## Como é construído

O aplicativo usa **React e TypeScript**, com **Vite e Bun** no desenvolvimento, **Capacitor** na versão Android, **Supabase** nos serviços de backend e **Cloudflare** na hospedagem e entrega de mídia. A produção de voz utiliza **ElevenLabs**.

| Camada | Tecnologias utilizadas |
| --- | --- |
| Interface | React · TypeScript · Vite |
| Desenvolvimento | Bun · OpenAI Codex · GitHub |
| Aplicativo Android | Capacitor |
| Serviços de backend | Supabase |
| Hospedagem e mídia | Cloudflare · Cloudflare Stream |
| Produção de voz | ElevenLabs |

### Engenharia e criação com IA

O **OpenAI Codex** participa da implementação, investigação de falhas, revisão de código e preparação de entregas. Leandro e Ramon conduzem as decisões do projeto; a IA integra o processo de trabalho, com revisão humana e validação do resultado.

Nosso cuidado com a entrega se traduz em práticas concretas:

- **Mudanças rastreáveis:** commits e pull requests registram a evolução do aplicativo.
- **Validação em camadas:** testes automatizados, build, revisão no navegador e conferências no Galaxy S24, conforme a mudança.
- **Feedback aplicado:** problemas e sugestões dos participantes orientam ajustes de interação, áudio e apresentação.
- **Entregas acompanhadas:** publicação web, distribuição Android e verificação no aparelho são etapas distintas.

Os [casos de evolução](docs/evolucao.md) mostram exemplos desse processo e o que foi verificado em cada um.

### Uma trajetória de construção

[![Pull Shark x3 do perfil agronetlabs](https://img.shields.io/badge/Perfil_agronetlabs-Pull_Shark_x3-C0C0C0?style=for-the-badge&logo=github&logoColor=181717)](https://github.com/agronetlabs?achievement=pull-shark&tab=achievements)

Em **31 de outubro de 2026**, o perfil **agronetlabs**, de Leandro Lemos, contabilizava **255 pull requests de sua autoria integrados**, consultados pela API autenticada do GitHub. Esse total reúne projetos públicos e privados da trajetória do autor; não é uma contagem exclusiva do ReinoUp. O **Pull Shark x3** reconhece o marco de 128 PRs integrados.

As insígnias deste README identificam tecnologias, características do produto e uma conquista pessoal. O uso de OpenAI Codex e dos demais serviços não implica parceria, certificação ou endosso institucional.

## Participe da evolução

Encontrou uma dificuldade ou tem uma sugestão? [Abra uma issue](https://github.com/agronetlabs/ReinoUp/issues/new/choose) descrevendo a tela, o que tentou fazer e o resultado esperado. Para falhas, informe também o dispositivo e se estava usando web, PWA ou Android.

Este repositório é público: não inclua dados de crianças, senhas ou informações pessoais nas mensagens e capturas. Consulte o [guia de participação](CONTRIBUTING.md).

## Sobre este repositório

Este é o **repositório público de apresentação do ReinoUp**. O código-fonte do aplicativo é mantido em um repositório privado. As imagens e a documentação aqui publicadas apresentam o projeto; não foi concedida uma licença de reutilização do aplicativo, da marca ou dos conteúdos.

**Desenvolvimento: Leandro Lemos · Ramon Ferreira · AgroNet Labs**

[Aplicativo](https://reinoup.com) · [Perfil do desenvolvedor](https://github.com/agronetlabs)
