<script>
    
</script>

<style>
    nav {
        background-color: maroon;
        color: white;
        padding: 8px;
        display: flex;
        place-content: center;
        place-items: center;
        position: relative;
    }

    legend {
        font-weight: bold;
        letter-spacing: 0.5px;
        font-size: 2rem;
        text-transform: uppercase;
    }

    .hamburger {
        position: absolute;
        top: 16px;
        left: 26px;
        cursor: pointer;
    }

    .bar {
        display: block;
        background-color: white;
        width: 30px;
        height: 3px;
        margin: 4px 0;
        border-radius: 2px;
    }

    .menu {
        position: absolute;
        top: 42px;
        left: 26px;
        display: flex;
        flex-direction: column;
        background-color: #490202;
        box-shadow: 0 0 8px rgba(0, 0, 0, 0.3);
        padding: 24px;
        border-radius: 8px;
    }

    a {
        color: white;
        padding: 4px 0;
    }
</style>

<nav>
    <legend>Rebeldes de Arkanna</legend>
    <div class="hamburger">
        <div class="bar"></div>
        <div class="bar"></div>
        <div class="bar"></div>
    </div>
    <div class="menu">
        <a href="/">Início</a>
        <a href="/mundo">Criação do Mundo</a>
        <a href="/guilda">A Guilda</a>
        <a href="grupo">O Grupo</a>
        <a href="diario">Diário de Aventuras</a>
    </div>
</nav>