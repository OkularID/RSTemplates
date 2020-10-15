# Reservasi Dulu Revision (Double cek website nya)

## Navbar
- (DONE) Hover di navigation header template kayaknya kurang cepet naiknya.


## Footer
- (DONE) Footernya belom yg the latest ya.
- (DONE) About udah ada ya page nya.
- (DONE) How-To itu ada di mario, udah dikasih?
- (DONE) Button pricing navigate ke pricing di home. *(navigation dan section banner homepage masih nyangkut)*
- (DONE) Blog disembunyikan dulu ya.


## Page Home
- (DONE) "Build your invitation for less than 30 mins" 30 mins nya di bold.
- (DONE) Di header wedding, bisa ga lengan panjang nya dihilangin?
- (DONE) "Grab your invitation starting from Rp 500 K" 500 K nya di bold.
- (DONE) "Craft your invitations with no head - scratching" no head scratching underline & bold.
- (DONE) Ada masukkan setelah header abis, orangnya fade ke kiri aja, soalnya yg sekarang kek tenggelam. *(harus ubah struktur dan ubah gambar/major)*
- (DONE) I want to make invitation for ... itu ditambah ya drop shadow nya.
- (DONE) Bagian "Reservasi dulu is as easy as ABC" itu body copy nya boleh batasin deh. (naik turun juga)
- (DONE) "The best deal comes with great price" itu body copy nya udah bener belum yah? (sudah mengikuti yang ada di design)
- (    ) Featured template itu tampilannya mirip sama yang terakhir gue kasih (gambarnya persegi bukan persegi panjang) *(input database)*
- (DONE) "Are you not ready to sign up?" ga rapi.
- (DONE) Buat navigation & banner menghilang saat screen sedang berada disection bawahnya, soalnya pas ke halaman lain dan balik ke halaman homepage, masih nyangkut ornament nya *(major)*

## Page Why Us
- (DONE) Usahakan ga ada copy yang "orphan" *(orphan = 1 kalimat dijadikan 2 baris, jangan dijadikan 1 baris)*
- (DONE) Footernya gue denger2 masih nyasar2. *(nyasar gimana?)*
- (DONE) Tolong double check footer. *(bermasalah dimana?)*

## Page Template
- (    ) Bagian "Select a Category" sebenernya pengen kayak ada animasi yang wedding semua gitu (ketika dihover, gambar berupa gif) *(major/tinggal input content)*
- (    ) Nih semua bagian template kecuali yang select category harusnya kayak template yang latest gue kasi *(tinggal input data dan query database)*

## Page FAQ
- (    ) Apakah sudah di update dari yang terbaru? *(tinggal input data)*
- (DONE) Animasi kenapa lambat.

## Page Tour
- (    ) Kok belom keganti gambar nya. *(tinggal input data)*
- (DONE) Easy to use RSVP 2?
- (DONE) Show me the templates > masih ke tour?
- (DONE) Bagian preview, description dijadikan tab
- (DONE) Bagian rsvp, tab dihilangkan

## Page Edit Templates
- (DONE) Di Main Info itu jadinya dia tanyain :
		 * Nama Bride
		 * Nama Groom (trus nanti URL nya dari nama mereka)
		 * Title
		 * Hastag
- (DONE) Trus di Main Info ada : Theme tapi not editable.
- (DONE) Kalau ada text box >> Wedding Theme itu langsung diapus soalnya ga ada.

## Ko David
- (DONE) Dropdown templates geser ke bawah.
- (DONE) Dropdown templates yang "FREE" jadiin kuning.
- (DONE) Bagian pricing, feature2nya tolong di update. *(feature2nya sudah mengikuti design)*
- (    ) CMS belum ready. *(backend nya)*
- (DONE) Easy to Use (Tour) ga usah slider bambang. *(tab dihilangkan)*
- (DONE) FAQ bagian header nya dipendekkan. *(background diganti dengan gambar baru)*
- (DONE) Contact Us -> form sama ilustrasi ditukar tombol di kanan.
- (    ) Content = Message. *(backend nya)*
- (DONE) "Send us a message" a nya ngga kapital.

## Etc
- (DONE) Foto yang di testimony harusnya di dalam frame.
- (    ) Slidernya masih kaku.
- (DONE) Text nya terlalu turun yang copy di habis header.
- (DONE) Font yang dibawah header diganti warnanya ya.
- (DONE) Kasi spasi header.
- (DONE) Button nya kurang rapi.
- (DONE) Why Us header.
- (DONE) Animate nya make sure udah sama semua.
- (DONE) Scroll down. *(semua header disamakan, ada button ke section bawahnya)*





# Update Jum'at, 04 September 2020
- Penambahan file animation.css di frontend > static > css > animation.css
- Penambahan source code di file frontend > templates > static > css.html
- Penambahan source code font orange 2 di default.css
	```
	.font-orange2,.font-orange2 p,.font-orange2 a{color: #f8b133 !important;}
    .w-lg-300{width: 300px !important;}
	```
- Nabar
	* Navbar diberi background putih dan container-fluid diberi padding vh
		```
		#navigation{background: #fff;}
		#navigation .padres{padding-top: 4vh !important;}
		```
	* Bagian Submenu, transisi dipercepat dan posisi diturunkan
		```
		#navigation .menu ul li .submenu{
			margin: 25px auto 0;
			transition: max-height .4s ease-out;
		}
		```
	* Bagian Logo, hilangkan outline di anchor
		```
		p,a,label,th,td,li{outline: none;}
		```
	* Bagian button
		```
		#navigation .getstarted img{width: 150px;}
		```
- Footer
	* Bagian GoTop, adjust posisi text, anak kecil, dan balon
		```
		#footer .gotop img.text{left: 1vw;}
		#footer .gotop img.child{top: 18vh;}
		#footer .gotop img.baloon{top: 0;}
		```
	* Menu blog di hide
- Halaman Home
	* Bagian Banner, terdapat perubahan di app.js untuk animasi nya agar bisa onload
		```
		// ================================================HOMEPAGE BANNER================================================
		$(document).ready(function(){
		  // show first
		  $("#navigation").show();
		  $(".home-banner-ornament").show();
		  // Function navigation and ornament
		  function classOnScroll(){
		    // Navigation hide show on scroll and resize
		      if ($(this).scrollTop() > 2200) {
		        $('#navigation').fadeOut();
		      } else {
		        $('#navigation').fadeIn();
		      }
		    // Ornament hide show on scroll and resize
		      if ($(this).scrollTop() > 2100) {
		        $('.home-banner-ornament').addClass('fadeOutLeft');
		        $('.home-banner-ornament').removeClass('fadeInLeft');
		      } else {
		        $('.home-banner-ornament').removeClass('fadeOutLeft');
		        $('.home-banner-ornament').addClass('fadeInLeft');
		      }
		    // Navigation hide show on scroll and resize
		      // Detect request animation frame
		      var scroll = window.requestAnimationFrame ||
		          // IE Fallback
		          function(callback){ window.setTimeout(callback, 1000/60)};
		      var elementsToShow = document.querySelectorAll('.show-on-scroll');
		      function loop() {
		        Array.prototype.forEach.call(elementsToShow, function(element){
		          if (isElementInViewport(element)) {
		            element.classList.add('is-visible');
		          } else {
		            element.classList.remove('is-visible');
		          }
		        });
		        scroll(loop);
		      }
		      // Call the loop for the first time
		      loop();
		      // Helper function from: http://stackoverflow.com/a/7557433/274826
		      function isElementInViewport(el) {
		        // special bonus for those using jQuery
		        if (typeof jQuery === "function" && el instanceof jQuery) {
		          el = el[0];
		        }
		        var rect = el.getBoundingClientRect();
		        return (
		            (rect.top <= 0
		                && rect.bottom >= 900) //bottomfadeout
		            ||
		            (rect.bottom >= (window.innerHeight || document.documentElement.clientHeight) &&
		                rect.top <= (window.innerHeight || document.documentElement.clientHeight))
		            ||
		            (rect.top >= 0 &&
		                rect.bottom <= (window.innerHeight || document.documentElement.clientHeight))
		        );
		      }
		  }
		  //Run on first site run
		  classOnScroll();
		  //Run on scroll and resize
		  $(window).on('scroll resize',classOnScroll);
		});
		// ================================================HOMEPAGE BANNER================================================
		```
	* Bagian Banner, terdapat penambahan css untuk ornament
		```
		.home-banner .home-banner-ornament{
		    position: fixed;
		    display: none;
		    top: 30vh;
		    left: 7vw;
		    width: 24%;
		}
		```
	* Bagian Banner, terdapat perubahan untuk background dan ornament nya
		```
		<div class="container-fluid pos-rel d-none d-lg-block pl-lg-0 pr-lg-0 home-banner" style="background: url('images/01-home/home-background-01.png');">
            <img class="img-fluid home-banner-ornament animated" style="animation-duration: 200ms;" src="images/01-home/homepage-banner-ornament.png" />
		```
	* Bagian Price, target price dipisah dari container-fluid
		```
		#price{position: absolute;top: -40vh;}
		```
	* Bagian Banner, brief digeser lebih ke kanan
		```
  		.desc-animation-1,
  		.desc-animation-2,
  		.desc-animation-3{left:75%;}
		```
	* Bagian Banner, brief yang ada underline ditambahin tab <b></b> lalu ada styling baru untuk tag tersebut
		```
		search
		.home-banner{}
		tambahkan dibawahnya
		.home-banner .box-desc p u b{
            font-weight: bolder !important;
            font-family: unset !important;
        }
		```
	* Bagian Banner, gambar ornament wedding diganti menjadi gambar baru tanpa lengan "home-banner-ornament-01.png".
	* Bagian brief, text kurang keatas
		```
		.home-brief .quote{padding: 3vw 12%;}
		```
	* Bagian Invitation, dropshadow ditambah
		```
		.home-invitation .home-invitation-card{
			-webkit-box-shadow: 0px 0px 20px 0px rgba(0,0,0,0.5);
		    -moz-box-shadow: 0px 0px 20px 0px rgba(0,0,0,0.5);
		    box-shadow: 0px 0px 20px 0px rgba(0,0,0,0.5);
		}
		```
	* Bagian Testimoni, foto didalam frame
		```
		.home-testimony .box1 .pic{z-index: 1;}
		.home-testimony .box1 #sync1 .item{height: 15.8vw;}
		.home-testimony .box1 #sync1 img{
		    object-fit: cover;
		    width: 19.8VW;
		    height: 100%;
		}
		```
	* Bagian Steps, <div class="boxv"> diganti menjadi <div class="pt-lg-30p">
	* Bagian Featured Template, semua thumbnail template diganti menjadi image yang persegi
		```
		.templatesthumbnail-image{height: auto;}
		```
	* Bagian Free, berubah source code maupun styling nya
- Halaman FAQ
	* Bagian Banner, text dipercepat delay nya
	* Bagian banner, background diganti, ornament dan text di adjust
		```
		.faq-banner .boxv.image.birthday{
			top: 45%;
			width: 34%;
		}
		.faq-banner .boxv.desc{
			top: 30%;
			right: 20%;
		}
		```
- Halaman Tour
	* Bagian banner, ditambahkan animasi dan brief dikanan
	* Bagian preview, brief diganti menjadi tab
		```
		hapus bagian
		.tour-rsvp .content{}
		ubah value
		.tour-rsvp .image{
		    background-size: cover !important;
		    background-repeat: no-repeat !important;
		    background-position: top left !important;
		    position: absolute;
		    z-index: -1;
		    margin: 0 auto;
		    top: 6% !important;
		    left: 0;
		    right: 15vw;
		    width: 39vw;
		    height: 46vh;
		}
		ubah value width
		.tour-template .content{width: 40.8vw;}
		```
	* Bagian rsvp, diubah menjadi tidak menggunakan tab
		```
		```
	* Bagian get started, ditambahkan animasi
- Halaman Landing Templates
	* Bagian category, terdapat penambahan source code di app.js, style.css, dan html
		```
		app.js
		// ===============================LANDING TEMPLATE PAGE===============================
		$(document).ready(function() {
		  $(this).find('.cathov').hide();
		  $('.catwrap').hover(function() {
		      $(this).find('.catdef').hide();
		      $(this).find('.cathov').show();
		  }, function() {
		      $(this).find('.catdef').show();
		      $(this).find('.cathov').hide();
		  });
		});
		// ===============================LANDING TEMPLATE PAGE===============================
		style.css
		.landing-category .catwrap .catdef,
  		.landing-category .catwrap .cathov{height: 257px;}
  		html
  		<div class="col-lg-4 catwrap mb-m-15p text-center">
            <img class="catdef w-lg-100p" src="images/04-templates/templates-landing-image-02.png" alt="reservasidulu" />
            <img class="cathov w-lg-100p" src="images/okular-preloader.gif" alt="reservasidulu" />
            <a class="button-orange" href="templates-wedding.html">
                <p class="font-white">All Wedding Templates</p>
            	<img src="images/button-03.png">
        	</a>
		</div>
		```