# Parallax-Scrolling
This Website (Parallax Scrolling)  Project for my portfolio - University

let get start

<!DOCTYPE html>
<html>
  <head>
      <title>My Profile I Theme animate vanilla</title>
      <link rel="stylesheet" type="text/css" href="style.css">    
  </head>
  <body>     
      <section>
          <div class="text">
              <h2 style="--i:0.5"><span>Name:Phonthat Saetang</span> <span>Name:Phonthat Saetang</span> <span>Name:Phonthat Saetang</span> <span>Name:Phonthat Saetang</span> <span>Name:Phonthat Saetang</span>
                <span>Name:Phonthat Saetang</span> <span>Name:Phonthat Saetang</span> <span>Name:Phonthat Saetang</span> <span>Name:Phonthat Saetang</span> <span>Name:Phonthat Saetang</span>
                <span>Name:Phonthat Saetang</span> <span>Name:Phonthat Saetang</span> 
                </h2> 
              <h2 style="--i:1.5"><span>Line:bizixindiiz</span> <span>Line:bizixindiiz</span> <span>Line:bizixindiiz</span> <span>Line:bizixindiiz</span> <span>Line:bizixindiiz</span> <span>Line:bizixindiiz</span> 
                <span>Line:bizixindiiz</span> <span>Line:bizixindiiz</span> <span>Line:bizixindiiz</span> <span>Line:bizixindiiz</span> <span>Line:bizixindiiz</span> <span>Line:bizixindiiz</span>
                </h2>
              <h2 style="--i:2.5"><span>Gmail:belikehalo92@gmail.com</span> <span>Gmail:belikehalo92@gmail.com</span> <span>Gmail:belikehalo92@gmail.com</span> <span>Gmail:belikehalo92@gmail.com</span>
                <span>Gmail:belikehalo92@gmail.com</span> <span>Gmail:belikehalo92@gmail.com</span> 
                </h2>
              <h2 style="--i:1.5"><span>Tel:095-875-0985</span> <span>Tel:095-875-0985</span> <span>Tel:095-875-0985</span> <span>Tel:095-875-0985</span>  <span>Tel:095-875-0985</span> <span>Tel:095-875-0985</span> <span>Tel:095-875-0985</span> <span>Tel:095-875-0985</span> <span>Tel:095-875-0985</span>
                <span>Tel:095-875-0985</span> <span>Tel:095-875-0985</span> <span>Tel:095-875-0985</span> <span>Tel:095-875-0985</span> <span>Tel:095-875-0985</span>
                </h2> 
              <h2 style="--i:0.75"><span>Let me join your college</span> <span>Let me join your college</span> <span>Let me join your college</span> <span>Let me join your college</span> <span>Let me join your college</span> 
                <span>Let me join your college</span> <span>Let me join your college</span> <span>Let me join your college</span> <span>Let me join your college</span> <span>Let me join your college</span> 
                <span>Let me join your college</span><h2>
          </div>
      </section>

      <script>
          const position = document.documentElement
          position.addEventListener("mousemove", e => {
            position.style.setProperty('--x', e.clientX +'px');
          })
      </script>
  </body>
</html>
