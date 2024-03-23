Код JavaScript который будет автоматически поднимать верх страницу каталога WooCommerce при пагинации.


jQuery(function($){
    $(document.body).on('click', '.page-numbers', function(){
        $('html, body').animate({scrollTop:0}, 'slow');
    });
});
