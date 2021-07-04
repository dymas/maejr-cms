---
layout: default
title: Página Inicial
bannertitle: Essa empresa também é sua!
bannersubtitle: Agende já sua primeira consultoria
buttontext: Saiba Mais
bannerimage: /assets/imagens/leon-Oalh2MojUuk-unsplash.jpg
---
<section class="bloco" id="Sobre Nós"><h2>Sobre Nós</h2><p>A Multi Assessorial Empresarial Júnior é uma associação sem fins lucrativos, com finalidades educacionais na área de Consultoria Empresarial. Entre os principais objetivos, a empresa júnior pretende propiciar ao estudante a oportunidade de aplicar e aprimorar conhecimentos teóricos adquiridos em sala de aula.</p><p>Universidade</p></section>

{% assign array = "Universidade,Plano de Marketing,O Planejamento de Marketing tem como propósito descrever estratégias mercadológicas para a iniciativa de expansão do público-alvo do empreendimento ou para inserção de um novo produto ou serviço no mercado.,Universidade,Pesquisa de Mercado,O processo de pesquisa de mercado consiste na definição do problema e dos objetivos de pesquisa, desenvolvimento do plano de pesquisa, coleta de informações, análise das informações e apresentação dos resultados.,Universidade,Plano de Negócio,É um documento de planejamento capaz de nos mostrar toda a viabilidade e estratégias deste, do ponto de vista estrutural, administrativo, estratégico, mercadológico, técnico, operacional e financeiro de um empreendimento.,Universidade,Gestão de Talentos,A Gestão de Talentos é peça fundamental para alcançar os objetivos que uma empresa almeja. Com uma boa gestão essas metas serão atingidas de forma ainda mais rápida. Afinal, empresas são resultados de pessoas.,Universidade,Planejamento Estratégico,É um processo gerencial que se refere à formulação de objetivos para a seleção de programas de ação e para sua execução, levando em conta as condições internas e externas à empresa e sua evolução esperada.,Universidade,," | split: "," %} {% include nuvem.html %}

<section class="bloco">
    <p>Procurando por uma consultoria de qualidade?<br> Agende sua primeira consultoria!</p>
    <button><a href="#contato" >Agendar</a></button>
</section>

<section class="cards" id="consultoria">
    <div class="cabecalho-cards">
        <h2 class="titulo-cards">Processo de Consultoria</h2>
    </div>
    <div class="flex">
        <div class="item">
            <div class="cabecalho-item">
                <i class="fas fa-users"></i>
                <h3>Diagnóstico</h3>
            </div>
            <p>Momento o qual o cliente conhece a MAE JR e o Gerente entende as necessidades do cliente para dar insumos
                a elaboração da proposta.</p>
        </div>
        <div class="item">
            <div class="cabecalho-item">
                <i class="fas fa-suitcase"></i>
                <h3>Proposta</h3>
            </div>
            <p>Documento responsável por descrever todos os objetivos do projetos, as etapas da metodologia, o
                cronograma, a equipe envolvida e o investimento necessário para execução do projeto.</p>
        </div>
        <div class="item">
            <div class="cabecalho-item">
                <i class="far fa-clipboard"></i>
                <h3>Contrato</h3>
            </div>
            <p>As formas de pagamento são estabelecidas, um contrato de serviço é assinado e o projeto de consultoria é
                iniciado.</p>
        </div>
        <div class="item">
            <div class="cabecalho-item">
                <i class="fas fa-users-cog"></i>
                <h3>Execução</h3>
            </div>
            <p>Momento em que os consultores se envolvem no projeto e vivem a experiência de criar vantagens
                competitivas para os clientes.</p>
        </div>
    </div>
</section>

<div class="space"></div>
<section class="minicards" id="diretoria">
    <div class="cabecalho-minicards">
        <h2 class="titulo-minicards">Diretoria</h2>
    </div>
    <div class="corpo-minicards">
        <div class="item-minicards">
            <div class="minicards-imagem">
                <img
                    src="https://images.unsplash.com/photo-1544005313-94ddf0286df2?ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&ixlib=rb-1.2.1&auto=format&fit=crop&w=334&q=80">
            </div>
            <div class="descricao-minicards">
                <h3 class="titulo-item-minicards">Juliana Lima</h3>
                <p class="cargo-minicards">Fundadora</p>
            </div>
        </div>
        <div class="item-minicards">
            <div class="minicards-imagem">
                <img
                    src="https://images.unsplash.com/photo-1545704881-d5dfa19efa38?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=334&q=80">
            </div>
            <div class="descricao-minicards">
                <h3 class="titulo-item-minicards">Matheus Costa</h3>
                <p class="cargo-minicards">Administrador Financeiro</p>
            </div>
        </div>
        <div class="item-minicards">
            <div class="minicards-imagem">
                <img
                    src="https://images.unsplash.com/photo-1554151228-14d9def656e4?ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&ixlib=rb-1.2.1&auto=format&fit=crop&w=333&q=80">
            </div>
            <div class="descricao-minicards">
                <h3 class="titulo-item-minicards">Laura Silva</h3>
                <p class="cargo-minicards">Diretora-Geral</p>
            </div>
        </div>
        <div class="item-minicards">
            <div class="minicards-imagem">
                <img
                    src="https://images.unsplash.com/photo-1491349174775-aaafddd81942?ixid=MnwxMjA3fDB8MHxwaG90by1yZWxhdGVkfDd8fHxlbnwwfHx8fA%3D%3D&ixlib=rb-1.2.1&auto=format&fit=crop&w=500&q=60">
            </div>
            <div class="descricao-minicards">
                <h3 class="titulo-item-minicards">Fernanda Mendes</h3>
                <p class="cargo-minicards">RH</p>
            </div>
        </div>
        <div class="item-minicards">
            <div class="minicards-imagem">
                <img
                    src="https://images.unsplash.com/photo-1552058544-f2b08422138a?ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&ixlib=rb-1.2.1&auto=format&fit=crop&w=344&q=80">
            </div>
            <div class="descricao-minicards">
                <h3 class="titulo-item-minicards">Jonas Meireles</h3>
                <p class="cargo-minicards">Gestão de Pessoas</p>
            </div>
        </div>
        <div class="item-minicards">
            <div class="minicards-imagem">
                <img
                    src="https://images.unsplash.com/photo-1541656300774-69cddcdd9ac1?ixid=MnwxMjA3fDB8MHxzZWFyY2h8MTN8fGxhdGlub3xlbnwwfHwwfHw%3D&ixlib=rb-1.2.1&auto=format&fit=crop&w=500&q=60">
            </div>
            <div class="descricao-minicards">
                <h3 class="titulo-item-minicards">Paulo Costa</h3>
                <p class="cargo-minicards">Gerente de Projetos</p>
            </div>
        </div>
    </div>
</section>
<div class="space"></div>

<section class="contato" id="contato">
    <div class="cabecalho-contato">
        <h2 class="titulo-contato">Contatos</h2>
    </div>
    <div class="container-contato">
        <form class="formulario">
            <div class="container-form-esquerda">
                <input class="input" type="text" placeholder="* Nome">
                <input class="input" type="email" placeholder="* E-mail">
                <input class="input" type="tel" placeholder="* Telefone">
                <input class="input" type="text" placeholder="* Assunto">
            </div>
            <div class="container-form-direita">
                <textarea class="input mensagem" placeholder="* Sua mensagem..."></textarea>
                <button class="button-form">Enviar</button>
            </div>
        </form>
        <div class="endereco-telefone">
            <p>MAE JR<br />
                BR 343, Rede Nova, SN<br />
                Floriano, PI 64 800 00<br />
                maejr.contato@gmail.com<br />
                (89) 9-9450-9707<br />
                ORÇAMENTO: (89) 9-9988-9312
            </p>
        </div>
    </div>
</section>