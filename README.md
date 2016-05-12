# Quando-carregar-pagina-executa-tal-coisa
Quando carregar pagina executa tal coisa

    // this seleciona a div onde vai ser executada!
    $(this).load('.fieldTextUser', function() {
        var tamanhoTextdiv = $('.fieldTextUser').find('.heightDiv').height();
        $(".fieldTextUser").animate({ scrollTop: $('.fieldTextUser').height()+tamanhoTextdiv}, 'fast');
    });
