jQuery(function($){
    $(document.body).on('click', '.page-numbers', function(){
        $('html, body').animate({scrollTop:0}, 'slow');
    });
});
