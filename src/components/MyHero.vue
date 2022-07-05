<template>
    <div>
      <div class="jumbotron-background">
        <div class="jumbotron-part">
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Corporis ipsum aspernatur atque, blanditiis quos ea assumenda magnam inventore deserunt reprehenderit laboriosam natus libero quod ex excepturi sequi repudiandae ipsa ut.
        </div>
        <div class="jumbotron-part">
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Molestias voluptatum rerum laudantium incidunt. Eveniet veritatis culpa dolorem quisquam maiores? Inventore praesentium distinctio qui eos atque ullam delectus totam perspiciatis porro.
        </div>
        <div class="jumbotron-part">
          Lorem ipsum dolor sit, amet consectetur adipisicing elit. Culpa totam architecto ad quos quaerat sit officia nemo earum voluptatum, voluptatem sint! Facere amet cumque repellendus voluptatum beatae. Veritatis, sit saepe!
        </div>
      </div>
    </div>
</template>

<script>

export default {
  name: 'MyJumbotron',
}
</script>

<style>
  .jumbotron-background{
    height: 200px;
    width: 100%;
    border-radius: 10px;
    display: flex;
    justify-content: space-between;
  }
  .jumbotron-part{
    width: calc(98% / 3);
    background-color: lightcyan;
    border-radius: 10px;
    display: flex;
    justify-content: center;
    align-items: center;
  }
</style>