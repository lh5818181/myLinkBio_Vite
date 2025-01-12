<template>
    <div class="profile-picture">
        <img class="picture" src="../assets/perfil.jpg" alt="Profile Picture" />
    </div>
</template>

<script>
export default {}
</script>

<style>
.profile-picture {
    display: flex;
    justify-content: center;
    align-items: center;
}
.picture {
    width: 100%;
    max-width: 260px;
    padding: 45px;
}

/* Responsividade */
@media (max-width: 1024px) {
    .picture {
        max-width: 200px;
        padding: 20px;
    }
}
</style>
