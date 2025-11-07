jQuery(document).ready(function($) {

    jQuery('.et_pb_menu ul.nav').each(function(i) {
				i++;
				et_duplicate_menu( jQuery(this), jQuery(this).parents('.et_pb_row').find('div .mobile_nav'), 'mobile_menu' + i, 'et_mobile_menu' );
		});

		jQuery('.et_pb_menu').each(function() {
				var this_menu = jQuery( this ),
				bg_color = this_menu.data( 'bg_color' );
        
				if ( bg_color ) {
					this_menu.find( 'ul' ).css( { 'background-color' : bg_color } );
				}
		});

});