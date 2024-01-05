<!DOCTYPE html>
<html lang="en">
<head>
  <title>Bootstrap 4 Website Example</title>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@4.6.2/dist/css/bootstrap.min.css">
  <script src="https://cdn.jsdelivr.net/npm/jquery@3.7.1/dist/jquery.slim.min.js"></script>
  <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.1/dist/umd/popper.min.js"></script>
  <script src="https://cdn.jsdelivr.net/npm/bootstrap@4.6.2/dist/js/bootstrap.bundle.min.js"></script>
  <style>
  .fakeimg {
    height: 200px;
    background: #aaa;
  }
  </style>
</head>
<body>

<div class="jumbotron text-center" style="margin-bottom:0">
  <h1>HARES AHŞAP </h1>
  <p>Soyadımızdan Gelen Sağlamlık</p> 
</div>
<div class="container">
   <div class="dropdown">
     <button type="button" class="btn btn-success dropdown-toggle" data-toggle="dropdown">Katalog</button>
     <div class="dropdown-menu"> 
       <a class="dropdown-item">Tiny House</a>
       <a class="dropdown-item">Bungalov</a>
       <a class="dropdown-item">Tek Katlı</a>
       <div class="dropdown-divider"></div>
       <a class="dropdown-item">İki Katlı</a>
     </div>
<nav class="navbar navbar-expand-sm bg-dark navbar-dark">
  <a class="navbar-brand" href="#">Ürünlerimiz</a>
  <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#collapsibleNavbar">
    <span class="navbar-toggler-icon"></span>
  </button>
  <div class="collapse navbar-collapse" id="collapsibleNavbar">
    <ul class="navbar-nav">
      <li class="nav-item">
        <a class="nav-link" href="#">Bungalov</a>
      </li>
      <li class="nav-item">
        <a class="nav-link" href="#">Tiny House</a>
      </li>
      <li class="nav-item">
        <a class="nav-link" href="#">Teras Katlı</a>
      </li>    
    </ul>
  </div>  
</nav>

<div class="container" style="margin-top:30px">
  <div class="row">
    <div class="col-sm-4">
      <h2>Hakkımızda</h2>
      <h5>Ürünlerimiz</h5>
      <img class img-fluid src="https://architab.net/img/cms/tinyhouse/tinyhouse-kapadokya-imalat.jpg" class="img-thumbnail"></img>
      <br><br>
      <img class img-fluid src="https://hips.hearstapps.com/hmg-prod/images/tiny-house-a-frame-1676320164.png?crop=0.668xw:1.00xh;0.147xw,0&resize=640:*" class="img-thumbnail"</img>
      
      <h5>Zengin Model Çeşitliliğimizle Hizmetinizdeyiz</h5>

     
      <ul class="nav nav-pills flex-column">
        <li class="nav-item">
          <a class="nav-link active" href="#">Hizmetlerimiz</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">Gündemde Biz</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">Sizden Gelenler</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">İletişim Bilgileri</a>
        </li>
      </ul>
      <hr class="d-sm-none">
    </div>
    <div class="container">
      
    <div class="col-sm-8">
      <h2>2000'den Bugüne</h2>
      <h5>Kalitemizin Sırrı Geçmişimizde Saklı</h5>
      <img class img-fluid src="https://www.stoneplusturkiye.com/wp-content/uploads/2021/01/1-1.jpg" class="img-thumbnail"></img>
    
      <p>Sağlam bir gelecek güçlü bir geçmişle mümkündür</p>
      
      <br>
      <h2>Neden Hares Ahşap?</h2>
      <h5>Haydi gelin öğrenelim</h5>
      <img  class img-fluid src="data:image/jpeg;base64,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" class="img-thumbnail"></img>
      <p>Şirketimizin kullandığı ürünler tamamen fırınlanmış ithaldir . Değişen hava şartlarında  sağlıklı kalacak şekide boya uygulamamızla uzun yıllarca kullanabilirsiniz .

        
        </p>
    </div>
  </div>
</div>
 
 </div>
<div class="jumbotron text-center" style="margin-bottom:0">
  <p>Tüm Hakları Saklıdır.</p><br>
  <p>Copyright &copy;Hares Ahşap </p>
</div>

</body>
</html>
