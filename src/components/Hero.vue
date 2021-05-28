<template>
  <div>
    <section>
      <h2>Hello, Vue!</h2>
      <p>
        This is a simple hero unit, a simple jumbotron-style component for
        calling extra attention to featured content or information.
      </p>
    </section>
  </div>
</template>

<script>
export default {
  name: "Hero",
};
</script>

<style scoped>
div {
  display: flex;
  flex-direction: column;
  justify-content: flex-end;
  height: 100%;
  padding: 20px;
  border-radius: 5px;
  background-image: url("https://images.pexels.com/photos/1038916/pexels-photo-1038916.jpeg?auto=compress&cs=tinysrgb&dpr=2&h=650&w=940");
  background-position: center;
  background-repeat: no-repeat;
  background-size: cover;
}
section {
  padding: 10px;
  background-color: rgba(0, 0, 0, 0.4);
}
h2 {
  font-size: 2.5em;
}
</style>