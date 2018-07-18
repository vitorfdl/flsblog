---
title: Sistema de Combate
author: Vitor Lima
date: 2018-01-05 15:05:23
thumbnail: /images/combat_background.jpg
tags:
  - Combate
  - Armadura
  - Arma
categories:
  - Sistemas
---
Há diversos elementos que compõe o sistema de combate do shard, mas sem dúvidas o mais importante dele é conhecimento e técnica do jogador. Não é possível cobrir em texto todas as mecânicas que envolve o combate, uma vez que novas podem ser adicionadas a qualquer momento, mas podemos oferecer um ponto de partida.

O recurso mais importante são seus atributos de vitalidade. Você recebe um ponto de vitalidade para cada level de personagem, mas eles representam valores diferentes dependendo da vitalidade em que é distribuído.

###### Vida
Seu número de vida equivale a capacidade do seu personagem de sofrer dano sem ser nocauteado. Distribuir 1 ponto de vitalidade em Vida equivale a + 200 de vida.

Quando seu personagem chegar a 0, você será nocauteado. Aliados poderão te estabilizar após 15 segundos. Caso ninguém te estabilize, você ficará nocauteado por até 1 minuto.

###### Mana
Representa sua capacidade de juntar energia espiritual e, consequentemente, dar ordem aos espíritos. O caminho do Sábio, Nomeador e Naturalista são os únicos que usa Mana como recurso.

Indiferente de você usar mana ou não, ter esta vitalidade reduzido a 0 irá lhe causar um atordoamento de 5 segundos.

###### Vigor
Mede suas capacidades de executar movimentos físicos sem se cansar. O vigor, junto da Vida, é um dos recursos mais utilizados. Correr, usar habilidades físicas e habilidades de armas (exceto varinhas e cajados) usam seu estoque de vigor como fonte.

Ter seu vigor reduzido a 0 irá impedi-lo de se mover, pegar itens ou trocar de armas.

---

### Ferimentos Graves
Para cada desmaio você sofrerá um Ferimento Grave. Após acumular 2, você não será capaz de ser estabilizado novamente. Neste caso, seu personagem permanecerá em estado letárgico por 4 horas. Caso não seja levado a uma templo/igreja ou receba uma Semente de Anar, você estará permanentemente morto e terá de começar um novo personagem.

---

### Esquiva e Bloqueio
Todo personagem automaticamente tem acesso a habilidade de Esquiva, enquanto apenas aqueles que usarem armas grandes ou escudos tem acesso a habilidade de Bloqueio. Uma vez que não há cálculos de acerto e erro, o uso correto destas habilidades se faz fundamental para aumentar a sobrevivência do seu personagem. 

Esquiva e Bloqueio dividem o mesmo tempo de cooldown. Isso é, ativar qualquer uma das duas colocará ambas em cooldown. Quando ativadas elas absorvem até 3 golpes/habilidades durante 2 segundos. Sofrer efeitos de atordoamento ou cair automaticamente forçam Esquiva para cooldown, quer você tenha ativado ou não.

É importante lembrar que há magias e habilidades que não podem ser defendidas por bloqueio, mas sim por esquiva, e vice versa.

---

### Armas e Poder
O atributo mais importante de qualquer arma, seja mágica ou não, é o seu Poder. Habilidades utilizam este parâmetro para definir porcentagens de dano e duração de efeitos. O poder também significa o dano por golpe da arma.

Armas também tem outros atributos como velocidade de ataque, habilidade ativa e habilidade passiva.

Seu level de personagem e experiência de classe são usados como requisitos para permitir que você equipe uma arma.

---

### Armaduras e Defesas
Cada equipamento tem uma taxa de Defesa e Defesa Elemental (Fogo, Raio, Veneno e Gelo). Esta taxa varia de 0% a 60%, aplicando redutores no dano sofrido pelo seu personagem.

Cada parte de uma armadura irá absorver apenas golpes que acertarem no local equipado. Quando uma habilidade apresenta a descrição "Dano Massivo", isso significa que sua defesa para o golpe é a média de todos os equipamentos equipados. Partes não equipadas tem defesa de 0%.

###### Tabela de Acerto
Torso: 44%
Cabeça: 17%
Braços: 16%
Pernas e Pés: 9%
Pescoço: 7%
Mãos: 7%

###### Roupas
Tecidos são úteis pelo peso leve e altas defesas elementais. Quando usadas em conjunto com armaduras leves ou pesadas, sua taxa de defesa física cairá para metade. Essa redução não conta para equipamentos em áreas que o tecido não cobre. Por exemplo, usar um manto com luvas pesadas não aplica redução nas luvas.

###### Armaduras Leves
Possuem peso mediano com defesa e defesa elemental médias. Cada parte de armadura leve equipada também reduz o cooldown de esquiva em 2%.

Normalmente são feitas de couro e tecido.

###### Armaduras Pesadas
Com peso maior e revestidas com placas metálicas, possuem altas taxas de defesa e baixa defesa elemental. Cada peça de armadura pesada aumenta o gasto de vigor e mana em habilidades em 5%.

###### Escudos
Qualquer personagem pode equipar escudos. Eles habilitam o uso da habilidade bloqueio e adicionam uma porcentagem extra de defesa física e/ou elemental a todas as partes do corpo.

Escudo se diferenciam pelo acréscimo de defesa e pelo cooldown de bloqueio. Maiores escudos costumam ter cooldown maior.

###### Barreiras
Quando uma criatura é envolvida por um escudo de proteção do véu, que desvia os golpes para outros mundos, é chamado de Barreira. Barreiras decaem ao decorrer do tempo e anulam completamente o dano enquanto durarem.

---

### Habilidades de Armas
Cada arma tem uma habilidade ativa, usada em modo combate ao dar dois cliques na arma, e uma habilidade passiva que será ativada caso as condições descritas sejam cumpridas.

A seguir tem uma lista de todas as habilidades disponíveis.

###### Ativas
**Arremesso:** A arma pode ser arremessada para causar dano, com uma chance de 20% de atordoar o alvo por 2 segundos.

**Disparo Poderoso:** Você prepara um poderoso disparo que causa dano massivo no primeiro alvo e dano menor nos demais.

**Chuva de Flechas:** Prepara várias flechas em sequência fazendo cair uma chuva de flechas sobre inimigos em uma área.

**Puxão Violento:** Dá um golpe certeiro que causa dano e puxa o alvo em sua direção e reduz a velocidade de movimento por 1 segundo.

**Ignorar Armadura:** Permite ignorar completamente a armadura do alvo por um ataque, mas o dano sofre uma redução de 10%.

**Golpe Devastador:** Drena 10% do vigor do alvo ao impacto.

**Desmontar:** Seu próximo golpe terá a capacidade de derrubar o alvo. No caso de um sucesso, ele sofrerá dano massivo e não poderá montar novamente por 20 segundos.

**Ataque em Movimento:** Permite a usuários de arcos e armas de arremesso a atacarem enquanto em movimento. Ataques desta maneira tem 10% de chance de errar o alvo.

**Golpe Sombrio:** Causa dano extra se usado pelas costas do alvo e automaticamente reseta o cooldown de esquiva/bloqueio.

**Golpe Giratório:** Ataca todos os alvos ao seu redor em um movimento giratório poderoso.

**Golpe Desorientador:** Acerta o alvo com um golpe poderoso, deixando-o desorientado por 2 segundos, afastando-o e fazendo-o esquecer quem estava atacando.

**Empalar:** Ataca uma linha reta de 3 tiles, atravessando todos os inimigos e causando dano.

**Partir Armadura:** Desfere um golpe poderoso que leva 2 segundo para carregar, em um acerto quebra a armadura do alvo no local atingido. NPC's sofrem redução de defesa por 6 segundos.

**Encantamento da Lua:** Confere propriedades elementais a arma durante um período de tempo, acrescentando algum dano elemental (Fogo, Gelo, Raio ou Veneno).

---

###### Passivas
**Sangramento:** Tem 6% de chance de aplicar sangramento em um alvo, impedindo-o de recuperar vida por qualquer fonte durante 3 segundos.

**Diferença de Altura:** Atacar um alvo estando em um terreno mais elevado aumenta o dano causado.

**Riposte:** Tem uma chance de 50% de atacar o alvo imediatamente após ele errar um golpe. 

**Duelista:** Tem uma chance de 25% de atacar duas vezes em qualquer golpe.

**Devorador do Véu:** Consome mais rapidamente a barreira do alvo caso ele possua uma.

**Barreira:** Cada golpe tem uma chance de 15% de gerar uma barreira por alguns segundos.

**Poderoso:** Ao atacar com sua arma você também acerta até 2 outros inimigos com 25% do dano total ao primeiro.

**Gigante:** Seus ataques ignoram até 10% de defesa do alvo.

**Êxtase:** Aumenta recuperação de vigor em 30% após matar um alvo.

---

### Efeitos de Controle
Efeitos de controle permitem mudar o estado físico ou mental de uma criatura. Em suas habilidades, armadilhas e venenos podem conter um ou mais efeitos de controle que sera aplicados nos alvos.

**Atordoamento** Incapaz de se mover, atacar ou usar habilidades. Esquiva e bloqueio entra em cooldown.

**Congelado** Aumento de defesa para 100% e redução de defesa mágica em até 60% e impossibilitado de atacar, mover ou usar habilidades.

**Tombar/Cair** Incapaz de se mover, atacar ou usar habilidades por 1 segundo. Esquiva entra em cooldown. Ataques sofridos neste tempo tem dano massivo.

**Confusão** Alvos de ataque, habilidades e magias são trocados por qualquer criatura próxima. NPC`s podem atacar os próprios aliados.

**Silenciado** Não pode usar magias ou habilidades, também não é capaz de falar e apenas usar ações.

**Encantado** Incapaz de atacar o alvo que conjurou o encantamento.

**Enraizado** Não pode se mover, mas pode atacar e trocar equipamentos.

**Queimando** Sofre dano por fogo a cada 2 segundos. 15% de chance de ficar atordoado por 0.5 segundos a cada rodada de dano.

**Sangrando** Sofre dano físico a cada 2 segundos. Incapaz de se curar pela duração do efeito.

**Cego** Todos os ataques e habilidades erram qualquer alvo. Incapaz de ler ações.

**Retardamento** Redução na velocidade de ataque e de movimento.
