---
layout: post
title: "Cadastro de locais"
date: 2018-09-10
author: Daniel Araújo
cover: "https://system.soprojetos.com.br/files/1063/planta_humanizada_zoom/modelo-de-casa-terrea-com-3-quartos-cod-96-planta-humanizada.jpg?1491503662"
tags: usuario cadastro locais
comments: true
---

Neste post mostraremos como criar ou editar locais passo a passo pelo sistema [Saiot](https://saiot.ect.ufrn.br).

### O que são locais?
Para modelar o formato de casas, indústrias, instituições públicas e qualquer local físico, criamos os locais virtuais onde você pode definir os cômodos de sua casa, por exemplo, e conseguir descrever as divisões dos mesmos. Cada local possui permissões de acesso para usuários cadastrados.
<!-- Colocar o link do post sobre permissões -->

### Exemplo:
Para dividirmos a casa abaixo e conseguir cadastrar seus cômodos, precisamos ter uma noção de cômodos que pertencem a outros cômodos. Um banheiro, por exemplo, é um local que pode ser um banheiro social ou de uma suite, então o local banheiro pode pertencer a um quarto que por sua vez pertence ao primeiro andar da casa e que pertence a casa em si.
![Planta baixa de uma casa]({{site.baseurl}}/assets/local-planta-baixa.jpg)
Nesse exemplo, poderiamos criar o local **Casa de praia** onde ele possui locais como **Quarto 1**, **Quarto 2**, **Suíte**, **Cozinha**, dentre outros. A **Suíte** possui o local **Banheiro**.

### Cadastrando um local:
Na imagem abaixo mostramos o cadastro do local **Casa**.
![Cadastro do local Casa]({{site.baseurl}}/assets/cadastro-locais-1.png)
Em seguida vamos cadastrar um local chamado **Quarto** pertencente ao local **Casa**.
![Cadastro do local Quarto]({{site.baseurl}}/assets/cadastro-locais-2.png)

Assim nós cadastramos uma casa que possui um único quarto e podemos associar os dispositivos cadastrados aos locais e permitir uma mais fácil gestão de permissões de usuários e também a visualização e controle de dados.