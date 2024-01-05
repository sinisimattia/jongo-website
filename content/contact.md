---
title: Contattaci
---
<div class="columns">
    <form name="contact" method="POST" action="/thanks" netlify>
        <label>Piacere di conoscerla</label>
        <div>
            <input type="text" name="first_name" placeholder="Nome" required />
            <input type="text" name="last_name" placeholder="Cognome" required />
        </div>
        <label>Verrà contattat* qui</label>
        <div>
            <input type="email" name="email" placeholder="E-Mail" required />
            <input type="tel" name="phone" placeholder="Cellulare" required />
        </div>
        <label>Qual'è il progetto?</label>
        <div>
            <select name="type" required>
                <option selected disabled hidden>Selezioni il tipo di lavoro</option>
                <option value="home">Abitazione</option>
                <option value="office">Ufficio</option>
                <option value="supermarket">Supermercato</option>
                <option value="restaurant">Ristorante</option>
                <option value="pub">Pub</option>
                <option value="bar">Bar</option>
                <option value="other">Altro</option>
            </select>
        </div>
        <div>
            <textarea name="message" placeholder="Descriva il progetto nella maniera più dettagliata possibile..."></textarea>
        </div>
        <div>
            <button type="submit">Invia</button>
        </div>
    </form>
</div>
