<!-- TRABALHOS: Com Mockups Coloridos e Hover Dinâmico -->
<section id="trabalhos" class="section-trabalhos container">
    <span class="kicker" data-aos="fade-up">Trabalhos</span>
    <h2 data-aos="fade-up">O que já construí</h2>
    
    <div class="grid-trabalhos">
        
        <!-- CARD 1: Pousada (Tema Escuro/Natureza) -->
        <article class="card-trabalho" 
                 onmouseenter="setTheme('recanto')" 
                 onmouseleave="resetTheme()"
                 data-aos="fade-up" data-aos-delay="100">
            <div class="mockup-preview mockup-recanto">
                <div class="mockup-line short"></div>
                <div class="mockup-line medium"></div>
                <div class="mockup-block" style="background: rgba(255,255,255,0.2)"></div>
                <div class="mockup-line"></div>
            </div>
            <h3>Pousada Recanto</h3>
            <p>Site focado em reservas diretas via WhatsApp.</p>
        </article>

        <!-- CARD 2: Agência (Tema Azul/Profissional) -->
        <article class="card-trabalho" 
                 onmouseenter="setTheme('turismo')" 
                 onmouseleave="resetTheme()"
                 data-aos="fade-up" data-aos-delay="200">
            <div class="mockup-preview mockup-turismo">
                <div class="mockup-line short"></div>
                <div class="mockup-line medium"></div>
                <div class="mockup-block" style="background: rgba(255,255,255,0.2)"></div>
                <div class="mockup-line"></div>
            </div>
            <h3>DF Turismo</h3>
            <p>Redução da dependência de redes sociais.</p>
        </article>

        <!-- CARD 3: Editorial (Tema Amarelo/Arte) -->
        <article class="card-trabalho" 
                 onmouseenter="setTheme('cantar')" 
                 onmouseleave="resetTheme()"
                 data-aos="fade-up" data-aos-delay="300">
            <div class="mockup-preview mockup-cantar">
                <div class="mockup-line short"></div>
                <div class="mockup-line medium"></div>
                <div class="mockup-block" style="background: rgba(255,255,255,0.2)"></div>
                <div class="mockup-line"></div>
            </div>
            <h3>Contar e Cantar</h3>
            <p>Site editorial sobre música brasileira.</p>
        </article>

    </div>
</section>
