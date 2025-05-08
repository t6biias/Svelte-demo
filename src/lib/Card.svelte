<script>
    let CardData = {
        title: "my card",
        image: "https://static.invenglobal.com/upload/image/2021/10/22/i1634933295274309.jpeg",
        info: "this is the info of the card",
    }
</script>

<main>

</main>

<div>
    <h2>{CardData.title}</h2>
    <section class="card-info">
        <img src={CardData.image} alt="Cole">
        <p>{CardData.info}</p>
    </section>
</div>

<style>
    div {
        border: 23px solid greenyellow;
        max-width: 300px;
        background-color: indianred;
    }
    section {
        display: grid;
    }
</style>