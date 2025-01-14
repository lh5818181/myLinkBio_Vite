<template>
    <div class="biography">
        <h1 class="title">Luis H. Vieira de Oliveira</h1>
        <h2 class="subtitle">Desenvolvedor Full Stack</h2>
        <h3 class="about">SOBRE MIM</h3>
        <hr />
        <p>Olá! Eu sou <span class="name">Luis Henrique Vieira de Oliveira</span> um entusiasta de tecnologia com 25 anos, sempre em busca de ideias inovadoras. Tenho habilidades em desenvolvimento web e sou movido pela paixão por criar soluções que fazem a diferença.</p>
        <p>Acredito que a tecnologia e a inovação são catalisadores de grandes transformações, e minha missão é impulsionar mudanças positivas e impactantes. Estou comprometido com o aprendizado contínuo, enfrentando desafios e contribuindo para avanços significativos no mundo do desenvolvimento.</p>
        <hr />
        <a href="https://main.djaerr18p7b3q.amplifyapp.com/" target="_blank" rel="noopener noreferrer"> 
            <button class="skills-button">MINHAS HABILIDADES</button> 
        </a>
    </div>
</template>

<script>
export default {}
</script>

<style>
.biography {
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    padding: 20px;
    max-width: 600px;
}
h1, h3 {
    color: black;
}

.about {
    margin-top: 30px;
}

.name {
    font-weight: bold;
}

.subtitle {
    color: #fff;
    background-color: #0984E3;
    padding: 8px;
    border-radius: 6px;
    font-size: 14px;
    margin-top: 0;
}
hr {
    width: 100%;
    border: none;
    border-top: 1px solid rgba(21, 21, 21, 0.2);
    margin: 10px 0;
}
.skills-button {
    background-color: #0984E3;
    color: white;
    border: none;
    padding: 10px 20px;
    cursor: pointer;
}

/* Responsividade */
@media (max-width: 1024px) {
    .biography {
        max-width: 100%;
        align-items: center;
    }
    .subtitle, .skills-button {
        width: 100%;
        text-align: center;
    }
}
</style>
