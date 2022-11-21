# Ciro-Rockert-App-Awards
<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
    <meta name="viewport" content="initial-scale=1, maximum-scale=1, user-scalable=no, width=device-width">
    <title></title>

    
    
    <script src="lib/ionic/js/ionic.bundle.js"></script>

    <!-- cordova script (this will be a 404 during development) -->
    <script src="cordova.js"></script>

    <!-- IF using Sass (run gulp sass first), then uncomment below and remove the CSS includes above
    <link href="css/ionic.app.css" rel="stylesheet">
    -->

    <link href="css/ionic.app.css" rel="stylesheet">

    <style type="text/css">
      .platform-ios .manual-ios-statusbar-padding{
        padding-top:20px;
      }
      .manual-remove-top-padding{
        padding-top:0px; 
      }
      .manual-remove-top-padding .scroll{
        padding-top:0px !important;
      }
      ion-list.manual-list-fullwidth div.list, .list.card.manual-card-fullwidth {
        margin-left:-10px;
        margin-right:-10px;
      }
      ion-list.manual-list-fullwidth div.list > .item, .list.card.manual-card-fullwidth > .item {
        border-radius:0px;
        border-left:0px;
        border-right: 0px;
      }
      .show-list-numbers-and-dots ul{
        list-style-type: disc;
        padding-left:40px;
      }
      .show-list-numbers-and-dots ol{
        list-style-type: decimal;
        padding-left:40px;
      }
    </style>

    <script src="js/app.js"></script>
    <script src="js/controllers.js"></script>
    <script src="js/routes.js"></script>
    
    <script src="js/directives.js"></script>
    <script src="js/services.js"></script>

    
    <script src="lib/ionicuirouter/ionicUIRouter.js"></script>
    

  </head>
  <body ng-app="app" animation="slide-left-right-ios7">
  <div>
  <ion-side-menus enable-menu-with-back-views="false" data-componentid="side-menu21">
    <ion-side-menu-content>
      <ion-nav-bar class="bar-royal">
        <ion-nav-back-button></ion-nav-back-button>
        <ion-nav-buttons side="left">
          <button class="button button-icon button-clear ion-navicon" menu-toggle="left"></button>
        </ion-nav-buttons>
      </ion-nav-bar>
      <ion-nav-view></ion-nav-view>
    </ion-side-menu-content>
    <ion-side-menu side="left" id="side-menu21">
      <ion-content ng-controller="perfilCtrl" padding="false" style="top:0px !important;" class="side-menu-left ">
        <div class="spacer" data-componentid="spacer5" style="width: 268px; height: 32px;"></div>
        <div data-componentid="image7">
          <img src="img/dAlFw0gcR9Sv22wRtDcw_zyro-image2.png" style="display: block; width: 40%; height: auto; margin-left: auto; margin-right: auto;">
        </div>
        <h5 id="perfil-heading3" style="color:#000000;font-weight:300;text-align:center;" data-componentid="heading3"> Estephanie Racy</h5>
        <div class="spacer" data-componentid="spacer6" style="width: 268px; height: 36px;"></div>
        <ion-list id="perfil-list3" data-componentid="list3">
          <ion-item class="item-icon-left royal" id="perfil-list-item6" ui-sref="tabsController.minhasCompras_tab3()" menu-close="" data-componentid="list-item6">
            <i class="icon ion-bag"></i>Minhas Compras</ion-item>
          <ion-item class="item-icon-left royal" id="perfil-list-item3" ui-sref="tabsController.carteira_tab6()" menu-close="" data-componentid="list-item3">
            <i class="icon ion-card"></i>Carteira</ion-item>
          <ion-item class="item-icon-left royal" id="perfil-list-item8" ui-sref="tabsController.favoritos_tab4()" menu-close="" data-componentid="list-item8">
            <i class="icon ion-ios-heart-outline"></i>Favoritos</ion-item>
          <ion-item class="item-icon-left royal" id="perfil-list-item2" ui-sref="endereO()" menu-close="" data-componentid="list-item2">
            <i class="icon ion-ios-location-outline"></i>Endereço</ion-item>
          <ion-item class="item-icon-left royal" id="perfil-list-item7" ui-sref="meusCupons()" menu-close="" data-componentid="list-item7">
            <i class="icon ion-ios-pricetags-outline"></i>Meus Cupons</ion-item>
          <ion-item class="item-icon-left royal" id="perfil-list-item9" ui-sref="notificaEs()" menu-close="" data-componentid="list-item9">
            <i class="icon ion-ios-bell-outline"></i>Notifcações</ion-item>
          <ion-item class="item-icon-left royal" id="perfil-list-item1" data-componentid="list-item1">
            <i class="icon ion-ios-gear-outline"></i>Configurações</ion-item>
          <ion-item class="item-icon-left royal" id="perfil-list-item4" data-componentid="list-item4">
            <i class="icon ion-information"></i>Informações</ion-item>
          <ion-item class="item-icon-left royal" id="perfil-list-item5" data-componentid="list-item5">
            <i class="icon ion-log-out"></i>Sair
            <span class="item-note">Até breve!</span>
          </ion-item>
        </ion-list>
      </ion-content>
    </ion-side-menu>
  </ion-side-menus>
</div>
  </body>
</html>
