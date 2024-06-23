# COINS
COINSBITOMNE
<!DOCTYPE HTML>
<html lang="en">

<head>


<meta http-equiv="content-type" content="text/html; charset=UTF-8">
<meta property="og:image" content="https://bitcoin.org/img/icons/opengraph.png?1716491272" />
<meta name="viewport" content="width=device-width, initial-scale=1.0, user-scalable=no">
<title>Bitcoin - Open source P2P money</title>
<meta name="description" content="Bitcoin is an innovative payment network and a new kind of money. Find all you need to know and get started with Bitcoin on bitcoin.org.">
<link rel="stylesheet" href="/css/font-awesome-4.4.0/css/font-awesome.min.css">
<link rel="stylesheet" href="/css/main.css?1716491272">
<!--[if lt IE 8]><link rel="stylesheet" href="/css/ie.css"><script type="text/javascript" src="/js/ie.js"></script><![endif]-->
<!--[if IE 8]><link rel="stylesheet" href="/css/ie8.css"><![endif]-->


<script type="text/javascript" src="/js/base.js?1716491272"></script>
<script type="text/javascript" src="/js/main.js?1716491272"></script>
<script src="/js/jquery/jquery-1.11.2.min.js"></script>
<script src="/js/jquery/jquery-ui.min.js"></script>
<script src="/js/jquery/jquery.qrcode.min.js"></script>

<link rel="shortcut icon" href="/favicon.png?1716491272">
<link rel="apple-touch-icon-precomposed" href="/img/icons/logo_ios.png?1716491272"/>
<script>
    window.cookieconsent_options = {
        theme: 'light-floating'
    }
</script>
<script type="text/javascript" src="/js/cookieconsent/cookieconsent.js?1716491272"></script>
<script>
if( navigator.doNotTrack != "yes" && navigator.doNotTrack != "1" && window.doNotTrack != "1" && navigator.msDoNotTrack != "1" ){
	var script = document.createElement('script');
	script.src = '/js/analytics.js'
	document.getElementsByTagName("head")[0].appendChild(script);
}
</script>

</head>

<body>



<div class="donation-container">
  <div class="donation-text">
    <div class="donation-text-container">
      <button onclick="closeDonationBanner()" class="donation-modal-close">
        <img src="/img/icons/ico_close.svg?1716491272" alt="Close">
      </button>
      <p>
        Bitcoin.org is a community funded project, donations are appreciated and used to improve the website.
      </p>
      <button type="button" class="donation-btn" onclick="openDonationModal()">
        Make a donation
      </button>
    </div>
  </div>
  <button type="button" class="donation-visibility-toggle" onclick="toggleDonationBanner()">
    Bitcoin.org needs your support!
  </button>
</div>



<div id="donation-modal" style="display: none" class="donation-modal hidden">
  <div class="modal-dialog">
    <div class="modal-header">
      <div class="modal-close-btn" onclick="closeDonationModal()">×</div>
      <p class="modal-header-text section-title">Donate to Bitcoin.org</p>
    </div>
    <p class="modal-subheader">Use this QR code or address below</p>
    <div style="text-align: center;">
      <div id="donation-qr-code" data-address="bc1qx3u4njquj0ux63030r4nat8awqrlm0x2zlt96h"></div>
    </div>
    <div>
      <a
        class="donation-btc-address"
        href="bitcoin:bc1qx3u4njquj0ux63030r4nat8awqrlm0x2zlt96h"
        target="_blank">
        bc1qx3u4njquj0ux63030r4nat8awqrlm0x2zlt96h
      </a>
    </div>
    <div class="modal-body bg-white" style="overflow-y:hidden;text-align: center;">
      <div>
        
        <button type="button" class="donation-amount-btn" data-amount-usd="5">
          $5.00
          <div class="donation-amount-usd-in-btc">(... BTC)</div>
        </button>
        
        <button type="button" class="donation-amount-btn" data-amount-usd="25">
          $25.00
          <div class="donation-amount-usd-in-btc">(... BTC)</div>
        </button>
        
        <button type="button" class="donation-amount-btn" data-amount-usd="50">
          $50.00
          <div class="donation-amount-usd-in-btc">(... BTC)</div>
        </button>
        
      </div>

      <div>
        <input
          style="margin-right: 15px"
          type="text"
          placeholder="Or custom amount? (BTC)"
          id="donation-input-amount-btc" class="donation-amount-input">
        <input
          type="text"
          placeholder="Or custom amount? (USD)"
          id="donation-input-amount-usd" class="donation-amount-input">
      </div>

      <div>
        <textarea
          class="donation-amount-input"
          id="donation-input-message"
          placeholder="Optional description (for your wallet)"></textarea>
      </div>
    </div>
  </div>
</div>



<div id="detectmobile" class="detectmobile"></div>







<div class="head"><div>
  

<a class="logo" href="/en/"><img src="/img/icons/logotop.svg?1716491272" alt="Bitcoin"></a>

  

<ul id="menusimple" class="menusimple menumain" onclick="mobileMenuHover(event);" ontouchstart="mobileMenuHover(event);">
  <li><a class="is-expand">Introduction</a>
    <ul>
      <li><a href="/en/bitcoin-for-individuals">Individuals</a></li>
      <li><a href="/en/bitcoin-for-businesses">Businesses</a></li>
      <li><a href="https://developer.bitcoin.org/">Developers</a></li>
      <li><a href="/en/getting-started">Getting started</a></li>
      <li><a href="/en/how-it-works">How it works</a></li>
      
      <li><a href="/en/bitcoin-paper">White paper</a></li>
      
    </ul>
  </li>
  <li><a class="is-expand">Resources</a>
    <ul>
      <li><a href="/en/resources">Resources</a>
      <li><a href="/en/exchanges">Exchanges</a></li>
      <li><a href="/en/community">Community</a></li>
      
      
      <li><a href="https://developer.bitcoin.org/">Documentation</a></li>
      
      <li><a href="/en/vocabulary">Vocabulary</a></li>
      <li><a href="/en/events">Events</a></li>
      
        <li><a href="/en/bitcoin-core/">Bitcoin Core</a></li>
      
    </ul>
  </li>
  <li><a href="/en/innovation">Innovation</a></li>
  <li><a class="is-expand">Participate</a>
    <ul>
      <li><a href="/en/support-bitcoin">Support Bitcoin</a>
      <li><a href="/en/buy">Buy Bitcoin</a></li>
      <li><a href="/en/full-node">Running a full node</a></li>
      <li><a href="/en/development">Development</a></li>
    </ul>
  </li>
  <li><a href="/en/faq">FAQ</a></li>
</ul>

  

<a id="menumobile" class="menumobile" onclick="mobileMenuShow(event);" ontouchstart="mobileMenuShow(event);"></a>

  
<ul class="lang is-expand">
  <li><a>English</a>
  <ul>
    <li><ul>
      
      
        
          <li><a href="/id/">Bahasa Indonesia</a></li>
        
        
          <li><a href="/ca/">Català</a></li>
        
        
          <li><a href="/da/">Dansk</a></li>
        
        
          <li><a href="/de/">Deutsch</a></li>
        
        
          <li><a href="/en/" class="active">English</a></li>
        
        
          <li><a href="/es/">Español</a></li>
        
        
          <li><a href="/fr/">Français</a></li>
        
        
          <li><a href="/it/">Italiano</a></li>
        
        
          <li><a href="/hu/">Magyar</a></li>
        
        
          <li><a href="/nl/">Nederlands</a></li>
        
        
          <li><a href="/pl/">Polski</a></li>
        
        
          <li><a href="/pt_BR/">Português Brasil</a></li>
        
        
          <li><a href="/ro/">Română</a></li>
        
        
          <li><a href="/sl/">Slovenščina</a></li>
        
        
          <li><a href="/sr/">Srpski</a></li>
        
        
          <li><a href="/sv/">Svenska</a></li>
        
        </ul></li><li><ul>
          <li><a href="/tr/">Türkçe</a></li>
        
        
          <li><a href="/el/">Ελληνικά</a></li>
        
        
          <li><a href="/bg/">български</a></li>
        
        
          <li><a href="/ru/">Русский</a></li>
        
        
          <li><a href="/uk/">Українська</a></li>
        
        
          <li><a href="/hy/">Հայերեն</a></li>
        
        
          <li><a href="/ar/">العربية</a></li>
        
        
          <li><a href="/fa/">فارسی</a></li>
        
        
          <li><a href="/he/">עברית</a></li>
        
        
          <li><a href="/hi/">हिन्दी</a></li>
        
        
          <li><a href="/ko/">한국어</a></li>
        
        
          <li><a href="/km/">ខ្មែរ</a></li>
        
        
          <li><a href="/ja/">日本語</a></li>
        
        
          <li><a href="/zh_CN/">简体中文</a></li>
        
        
          <li><a href="/zh_TW/">繁體中文</a></li>
        
      </ul></li>
    </ul>
  </li>
</ul>

  
<div id="langselect" class="langselect">
    <label for="select-input" class="center-select">
        <select id="select-input" class="center-select__input" onchange="window.location=this.value;">
            
            <option value="/id/" >Bahasa Indonesia</option>
            
            <option value="/ca/" >Català</option>
            
            <option value="/da/" >Dansk</option>
            
            <option value="/de/" >Deutsch</option>
            
            <option value="/en/"  selected="selected">English</option>
            
            <option value="/es/" >Español</option>
            
            <option value="/fr/" >Français</option>
            
            <option value="/it/" >Italiano</option>
            
            <option value="/hu/" >Magyar</option>
            
            <option value="/nl/" >Nederlands</option>
            
            <option value="/pl/" >Polski</option>
            
            <option value="/pt_BR/" >Português Brasil</option>
            
            <option value="/ro/" >Română</option>
            
            <option value="/sl/" >Slovenščina</option>
            
            <option value="/sr/" >Srpski</option>
            
            <option value="/sv/" >Svenska</option>
            
            <option value="/tr/" >Türkçe</option>
            
            <option value="/el/" >Ελληνικά</option>
            
            <option value="/bg/" >български</option>
            
            <option value="/ru/" >Русский</option>
            
            <option value="/uk/" >Українська</option>
            
            <option value="/hy/" >Հայերեն</option>
            
            <option value="/ar/" >العربية</option>
            
            <option value="/fa/" >فارسی</option>
            
            <option value="/he/" >עברית</option>
            
            <option value="/hi/" >हिन्दी</option>
            
            <option value="/ko/" >한국어</option>
            
            <option value="/km/" >ខ្មែរ</option>
            
            <option value="/ja/" >日本語</option>
            
            <option value="/zh_CN/" >简体中文</option>
            
            <option value="/zh_TW/" >繁體中文</option>
            
        </select>
        <span class="center-select__text">Language: <span class="is-capital">en</span></span>
    </label>
</div>

</div></div>

<div class="body">
  

<div class="breadcrumbs">
  <div class="container">
    
  </div>
</div>

  

<div id="content" class="content">
  


<div class="mainhero">
  <div class="container hero-container">
    <p class="mainsummary">Bitcoin is an innovative payment network and a new kind of money.</p>
    <div class="btn-container">
      <a class="btn btn-bright btn-home" href="/en/getting-started">Get started with Bitcoin</a>
      <a class="btn btn-light btn-home" href="/en/choose-your-wallet">Choose your wallet</a>
      <a class="btn btn-light btn-home" href="/en/buy">Buy Bitcoin</a>
    </div>

    <div class="mainvideo">
      <button class="mainvideo-btn-open" onclick="loadYoutubeVideo(event);" ontouchstart="loadYoutubeVideo(event);" data-youtubeurl="//www.youtube.com/embed/Gc2en3nHxA4?rel=0&amp;showinfo=0&amp;wmode=opaque&amp;autoplay=1">What is Bitcoin?</button>
    </div>

  </div>
</div>
<div class="mainoverview">
  <div class="container">
    <div class="mainoverview-title">Get a quick overview for</div>
    <a href="/en/bitcoin-for-individuals" class="maincard">
      <img class="maincard-img" src="/img/icons/ico_individuals.svg?1716491272" alt="Icon">
      <div>
        <p class="maincard-title">Individuals</p>
        <p class="maincard-link">Learn more</p>
      </div>
    </a>
    <a href="/en/bitcoin-for-businesses" class="maincard">
      <img class="maincard-img" src="/img/icons/ico_business.svg?1716491272" alt="Icon">
      <div>
        <p class="maincard-title">Businesses</p>
        <p class="maincard-link">Learn more</p>
      </div>
    </a>
    <a href="https://developer.bitcoin.org/" class="maincard">
      <img class="maincard-img" src="/img/icons/ico_developers.svg?1716491272" alt="Icon">
      <div>
        <p class="maincard-title">Developers</p>
        <p class="maincard-link">Learn more</p>
      </div>
    </a>
  </div>
  <a class="btn-down" href="#maindesc-title">
    <img src="/img/icons/ico_arrow_down.svg?1716491272" alt="Link">
  </a>
</div>
<div class="maindesc">
  <div class="container">
    <p class="section-title center home-title" id="maindesc-title">Get started with Bitcoin</p>
    <div class="row maindesc-row">
      <div>
        <p class="maindesc-text">Bitcoin uses peer-to-peer technology to operate with no central authority or banks; managing transactions and the issuing of bitcoins is carried out collectively by the network. <b>Bitcoin is open-source; its design is public, nobody owns or controls Bitcoin and <a href="/en/support-bitcoin">everyone can take part</a></b>. Through many of its unique properties, Bitcoin allows exciting uses that could not be covered by any previous payment system.</p>
        <ul class="mainlist">
          
            <li class="mainlist-item">
              <img src="/img/icons/main_ico_instant.svg?1716491272" alt="Icon">
              <p>Fast peer-to-peer transactions</p>
            </li>
          
          
            <li class="mainlist-item">
              <img src="/img/icons/main_ico_worldwide.svg?1716491272" alt="Icon">
              <p>Worldwide payments</p>
            </li>
          
          
            <li class="mainlist-item">
              <img src="/img/icons/main_ico_lowfee.svg?1716491272" alt="Icon">
              <p>Low processing fees</p>
            </li>
          
        </ul>
      </div>
      <img class="maindesc-img" src="/img/home/bitcoin-img.svg?1716491272" alt="Bitcoin image">
    </div>
    <div class="btn-container">
      <a class="btn btn-dark btn-home center" href="/en/getting-started">Get started with Bitcoin</a>
    </div>
  </div>
</div>

<!-- Youtube popup video -->
<div class="modal closed">
  <iframe class="modal-video" allowfullscreen="" frameborder="0">
  </iframe>
  <button class="mainvideo-btn-close" onclick="loadYoutubeVideo(event);" ontouchstart="loadYoutubeVideo(event);"></button>
</div>
<div class="modal-overlay closed">
</div>


</div>

  <div class="footer">
    <div class="container">
       

<a class="logo-footer" href="/en/">
  <img src="/img/icons/logo-footer.svg?1716491272" alt="Bitcoin">
</a> 
       

<div class="row footer-row">
  <div class="donate">
    <div class="row donate-row">
      <div>
        <span class="footer-title">Support Bitcoin.org:</span>
        <a onclick="openDonationModal()" class="donate-btn btn-bright">Donate</a>
        <p class="donate-text">
          <a class="donate-link" href="bitcoin:bc1qx3u4njquj0ux63030r4nat8awqrlm0x2zlt96h" target="_blank">bc1qx3u4njquj0ux63030r4nat8awqrlm0x2zlt96h</a>
        </p>
      </div>
    </div>
  </div>

  <div class="row footermenu">
    <div class="footermenu-item footermenu-introduction">
      <p class="footer-title">Introduction:</p>
      <ul class="footermenu-list">
        <li>
          <a href="/en/bitcoin-for-individuals">Individuals</a>
        </li>
        <li>
          <a href="/en/bitcoin-for-businesses">Businesses</a>
        </li>
        <li>
          <a href="https://developer.bitcoin.org/">Developers</a>
        </li>
        <li>
          <a href="/en/getting-started">Getting started</a>
        </li>
        <li>
          <a href="/en/how-it-works">How it works</a>
        </li>
        <li>
          <a href="/en/you-need-to-know">You need to know</a>
        </li>
        
        <li>
          <a href="/en/bitcoin-paper">White paper</a>
        </li>
        
      </ul>
    </div>
    
    <div class="footermenu-item footermenu-resources">
      <p class="footer-title">Resources:</p>
      <ul class="footermenu-list">
        <li>
          <a href="/en/resources">Resources</a>
        <li>
          <a href="/en/exchanges">Exchanges</a>
        </li>
        <li>
          <a href="/en/community">Community</a>
        </li>
        <li>
          <a href="/en/vocabulary">Vocabulary
          </a>
        </li>
        <li>
          <a href="/en/events">Events</a>
        </li>
        
        <li>
          <a href="/en/bitcoin-core/">Bitcoin Core</a>
        </li>
        
      </ul>
    </div>
    
    <div class="footermenu-item footermenu-participate">
      <p class="footer-title">Participate:</p>
      <ul class="footermenu-list">
        <li>
          <a href="/en/support-bitcoin">Support Bitcoin</a>
        
        <li>
          <a href="/en/buy">Buy Bitcoin</a>
        </li>
        
        
        <li>
          <a href="/en/full-node">Running a full node</a>
        </li>
        
        <li>
          <a href="/en/development">Development</a>
        </li>
      </ul>
    </div>
    <div class="footermenu-item footermenu-other">
      <p class="footer-title">Other:</p>
      
      <a href="/en/scams">Avoid Scams</a>
      
      <a href="/en/legal">Legal</a>
      
      <a href="/en/privacy">Privacy Policy</a>
      
      <a href="/en/press">Press</a>
      <a href="/en/about-us">About bitcoin.org</a>
      <a href="/en/blog">Blog</a>
    </div>
  </div>
</div>
 
       

<div class="footersponsor">
  <!--<div><span>A community website sponsored by</span> <a href="https://bitcoinfoundation.org/"><img src="/img/brand/bitcoinfoundation.png?1716491272" alt="Bitcoin Foundation"></a></div>-->
</div>

    </div>
    

<div class="footer-bottom">
  <div class="container">
    <div class="row footer-bottom-row">
      <div class="footerlicense">© Bitcoin Project 2009-2024 Released under the <a href="http://opensource.org/licenses/mit-license.php" target="_blank">MIT license</a></div>
      <div class="row footer-status-block">
        <a href="/en/alerts" class="statusmenu">Network Status</a>
        
<ul class="lang is-expand">
  <li><a>English</a>
  <ul>
    <li><ul>
      
      
        
          <li><a href="/id/">Bahasa Indonesia</a></li>
        
        
          <li><a href="/ca/">Català</a></li>
        
        
          <li><a href="/da/">Dansk</a></li>
        
        
          <li><a href="/de/">Deutsch</a></li>
        
        
          <li><a href="/en/" class="active">English</a></li>
        
        
          <li><a href="/es/">Español</a></li>
        
        
          <li><a href="/fr/">Français</a></li>
        
        
          <li><a href="/it/">Italiano</a></li>
        
        
          <li><a href="/hu/">Magyar</a></li>
        
        
          <li><a href="/nl/">Nederlands</a></li>
        
        
          <li><a href="/pl/">Polski</a></li>
        
        
          <li><a href="/pt_BR/">Português Brasil</a></li>
        
        
          <li><a href="/ro/">Română</a></li>
        
        
          <li><a href="/sl/">Slovenščina</a></li>
        
        
          <li><a href="/sr/">Srpski</a></li>
        
        
          <li><a href="/sv/">Svenska</a></li>
        
        </ul></li><li><ul>
          <li><a href="/tr/">Türkçe</a></li>
        
        
          <li><a href="/el/">Ελληνικά</a></li>
        
        
          <li><a href="/bg/">български</a></li>
        
        
          <li><a href="/ru/">Русский</a></li>
        
        
          <li><a href="/uk/">Українська</a></li>
        
        
          <li><a href="/hy/">Հայերեն</a></li>
        
        
          <li><a href="/ar/">العربية</a></li>
        
        
          <li><a href="/fa/">فارسی</a></li>
        
        
          <li><a href="/he/">עברית</a></li>
        
        
          <li><a href="/hi/">हिन्दी</a></li>
        
        
          <li><a href="/ko/">한국어</a></li>
        
        
          <li><a href="/km/">ខ្មែរ</a></li>
        
        
          <li><a href="/ja/">日本語</a></li>
        
        
          <li><a href="/zh_CN/">简体中文</a></li>
        
        
          <li><a href="/zh_TW/">繁體中文</a></li>
        
      </ul></li>
    </ul>
  </li>
</ul>
 
        <div id="footer-langselect" class="footer-langselect langselect">
          <label for="select-input-footer" class="center-select">
            <select class="center-select__input" onchange="window.location=this.value; ">
              
              <option value="/id/" >Bahasa Indonesia</option>
              
              <option value="/ca/" >Català</option>
              
              <option value="/da/" >Dansk</option>
              
              <option value="/de/" >Deutsch</option>
              
              <option value="/en/"  selected="selected">English</option>
              
              <option value="/es/" >Español</option>
              
              <option value="/fr/" >Français</option>
              
              <option value="/it/" >Italiano</option>
              
              <option value="/hu/" >Magyar</option>
              
              <option value="/nl/" >Nederlands</option>
              
              <option value="/pl/" >Polski</option>
              
              <option value="/pt_BR/" >Português Brasil</option>
              
              <option value="/ro/" >Română</option>
              
              <option value="/sl/" >Slovenščina</option>
              
              <option value="/sr/" >Srpski</option>
              
              <option value="/sv/" >Svenska</option>
              
              <option value="/tr/" >Türkçe</option>
              
              <option value="/el/" >Ελληνικά</option>
              
              <option value="/bg/" >български</option>
              
              <option value="/ru/" >Русский</option>
              
              <option value="/uk/" >Українська</option>
              
              <option value="/hy/" >Հայերեն</option>
              
              <option value="/ar/" >العربية</option>
              
              <option value="/fa/" >فارسی</option>
              
              <option value="/he/" >עברית</option>
              
              <option value="/hi/" >हिन्दी</option>
              
              <option value="/ko/" >한국어</option>
              
              <option value="/km/" >ខ្មែរ</option>
              
              <option value="/ja/" >日本語</option>
              
              <option value="/zh_CN/" >简体中文</option>
              
              <option value="/zh_TW/" >繁體中文</option>
              
            </select>
            <span class="center-select__text">en</span>
          </label>
        </div>
      </div>
<!--      <div class="row">  -->
        
<!--    </div> -->
    </div>
  </div>
</div>

  </div>
</div>



<script type="text/javascript">
  fallbackSVG();
  addAnchorLinks();
  trackOutgoingLinks();
  toggleDarkMode();
</script>






</body>

</html>
