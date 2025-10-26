[mau8_Version2.txt](https://github.com/user-attachments/files/23147612/mau8_Version2.txt)
<!-- ... (phần đầu giữ nguyên như bạn đã gửi) ... -->
    <!-- SẢN PHẨM -->
    <section id="san-pham" class="section" aria-labelledby="sanpham-title">
      <h2 id="sanpham-title">Sản phẩm tiêu biểu</h2>

      <!-- Products grid -->
      <div class="cards" id="productsGrid">
        <article class="card">
          <img src="https://files.oaiusercontent.com/file-90cfdb4d-924a-4a14-99b6-7c4c690e5f95/IMG_20231001_155708.jpg" alt="Tranh kính & gạch lát sàn">
          <h4>Tranh kính nghệ thuật & Gạch lát sàn</h4>
          <p class="small">Trưng bày tranh kính nghệ thuật và các mẫu gạch lát sàn cao cấp.</p>
          <div style="margin-top:10px">
            <button class="btn" data-idx="0">Xem ảnh</button>
            <a class="btn" href="#lien-he">Mua hàng</a>
          </div>
        </article>
        <article class="card">
          <img src="https://files.oaiusercontent.com/file-2b90f7b8-3b37-425d-bcf0-3b2d9b3aa31e/IMG_20231001_155730.jpg" alt="Thiết bị chiếu sáng">
          <h4>Thiết bị chiếu sáng</h4>
          <p class="small">Đèn trang trí, đèn trần, đèn thả, đèn bàn và các thiết bị chiếu sáng.</p>
          <div style="margin-top:10px">
            <button class="btn" data-idx="1">Xem ảnh</button>
            <a class="btn" href="#lien-he">Mua hàng</a>
          </div>
        </article>
        <article class="card">
          <img src="https://files.oaiusercontent.com/file-9e7c2a4a-7c41-48f7-8b42-6b5e6ee9e09f/IMG_20231001_155735.jpg" alt="Thiết bị vệ sinh">
          <h4>Thiết bị vệ sinh & điện nước</h4>
          <p class="small">Vòi nước, máy nước nóng, bồn rửa, thiết bị điện nước và phụ kiện.</p>
          <div style="margin-top:10px">
            <button class="btn" data-idx="2">Xem ảnh</button>
            <a class="btn" href="#lien-he">Mua hàng</a>
          </div>
        </article>
        <article class="card">
          <img src="https://files.oaiusercontent.com/file-7c6b7b7f-fbfb-4c7b-9c25-8613de8b8bb2/IMG_20231001_155658.jpg" alt="Mặt tiền showroom">
          <h4>Mặt tiền showroom</h4>
          <p class="small">Hình ảnh mặt tiền cửa hàng Hưng Quế - uy tín và chuyên nghiệp.</p>
          <div style="margin-top:10px">
            <button class="btn" data-idx="3">Xem ảnh</button>
            <a class="btn" href="#lien-he">Liên hệ</a>
          </div>
        </article>
        <!-- Thêm các ảnh sản phẩm của bạn ở đây (4 ảnh mới) -->
        <article class="card">
          <img src="images/15486054566284251952.jpg" alt="Sản phẩm 5">
          <h4>Sản phẩm 5</h4>
          <p class="small">Mô tả sản phẩm 5...</p>
          <div style="margin-top:10px">
            <button class="btn" data-idx="4">Xem ảnh</button>
            <a class="btn" href="#lien-he">Mua hàng</a>
          </div>
        </article>
        <article class="card">
          <img src="images/15486054566284251956.jpg" alt="Sản phẩm 6">
          <h4>Sản phẩm 6</h4>
          <p class="small">Mô tả sản phẩm 6...</p>
          <div style="margin-top:10px">
            <button class="btn" data-idx="5">Xem ảnh</button>
            <a class="btn" href="#lien-he">Mua hàng</a>
          </div>
        </article>
        <article class="card">
          <img src="images/1f22e3604398cec697895.jpg" alt="Sản phẩm 7">
          <h4>Sản phẩm 7</h4>
          <p class="small">Mô tả sản phẩm 7...</p>
          <div style="margin-top:10px">
            <button class="btn" data-idx="6">Xem ảnh</button>
            <a class="btn" href="#lien-he">Mua hàng</a>
          </div>
        </article>
        <article class="card">
          <img src="images/7820b763179b9ac5c38a7.jpg" alt="Sản phẩm 8">
          <h4>Sản phẩm 8</h4>
          <p class="small">Mô tả sản phẩm 8...</p>
          <div style="margin-top:10px">
            <button class="btn" data-idx="7">Xem ảnh</button>
            <a class="btn" href="#lien-he">Mua hàng</a>
          </div>
        </article>
      </div>
    </section>
<!-- ... (phần tiếp theo giữ nguyên như bạn gửi) ... -->

  <script>
    (function(){
      // Cookie banner
      var cookieBanner = document.getElementById('cookieBanner');
      var accept = document.getElementById('acceptCookies');
      if(localStorage.getItem('hq_cookies')==='1') cookieBanner.style.display='none';
      if(accept) accept.addEventListener('click', function(){ localStorage.setItem('hq_cookies','1'); cookieBanner.style.display='none'; });

      // Images array used by lightbox. Indices must match buttons' data-idx.
      var images = [
        {src:"https://files.oaiusercontent.com/file-90cfdb4d-924a-4a14-99b6-7c4c690e5f95/IMG_20231001_155708.jpg", caption:"Tranh kính nghệ thuật & Gạch lát sàn"},
        {src:"https://files.oaiusercontent.com/file-2b90f7b8-3b37-425d-bcf0-3b2d9b3aa31e/IMG_20231001_155730.jpg", caption:"Thiết bị chiếu sáng"},
        {src:"https://files.oaiusercontent.com/file-9e7c2a4a-7c41-48f7-8b42-6b5e6ee9e09f/IMG_20231001_155735.jpg", caption:"Thiết bị vệ sinh & điện nước"},
        {src:"https://files.oaiusercontent.com/file-7c6b7b7f-fbfb-4c7b-9c25-8613de8b8bb2/IMG_20231001_155658.jpg", caption:"Mặt tiền showroom Hưng Quế"},
        // Thêm ảnh mới của bạn
        {src:"images/15486054566284251952.jpg", caption:"Sản phẩm 5"},
        {src:"images/15486054566284251956.jpg", caption:"Sản phẩm 6"},
        {src:"images/1f22e3604398cec697895.jpg", caption:"Sản phẩm 7"},
        {src:"images/7820b763179b9ac5c38a7.jpg", caption:"Sản phẩm 8"}
      ];

      // Lightbox handlers
      var productButtons = document.querySelectorAll('button[data-idx]');
      var lightbox = document.getElementById('lightbox');
      var lightboxImg = document.getElementById('lightboxImg');
      var lightboxCaption = document.getElementById('lightboxCaption');
      var lightboxContact = document.getElementById('lightboxContact');

      productButtons.forEach(function(btn){
        btn.addEventListener('click', function(){
          var idx = parseInt(this.getAttribute('data-idx'),10) || 0;
          var img = images[idx] || images[0];
          lightboxImg.src = img.src;
          lightboxCaption.textContent = img.caption;
          lightboxContact.href = "#lien-he";
          lightbox.style.display = 'flex';
          lightbox.setAttribute('aria-hidden','false');
          document.body.style.overflow = 'hidden';
        });
      });

      var closeLightbox = document.getElementById('closeLightbox');
      if(closeLightbox) closeLightbox.addEventListener('click', function(){ lightbox.style.display='none'; lightbox.setAttribute('aria-hidden','true'); document.body.style.overflow=''; });
      if(lightbox) lightbox.addEventListener('click', function(e){ if(e.target===lightbox){ lightbox.style.display='none'; lightbox.setAttribute('aria-hidden','true'); document.body.style.overflow=''; } });

      // Contact form simple handler
      var form = document.getElementById('contactForm');
      if(form) form.addEventListener('submit', function(e){ e.preventDefault(); alert('Cảm ơn bạn! Thông tin đã được gửi.'); form.reset(); });

      // Smooth scroll anchors
      document.querySelectorAll('a[href^="#"]').forEach(function(a){
        a.addEventListener('click', function(e){
          var href = this.getAttribute('href');
          if(href.length>1){ e.preventDefault(); var el = document.querySelector(href); if(el){ el.scrollIntoView({behavior:'smooth',block:'start'}); history.replaceState(null,null,href); } }
        });
      });
    })();
  </script>
<!-- ... phần còn lại giữ nguyên ... -->
