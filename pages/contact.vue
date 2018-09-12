<template>
  <div>
    <h2>Contact</h2>
    <form action="">
      <label for="name">Name: <input type="text" name="name" id="name" required></label>
      <label for="email">Email: <input type="email" name="email" id="email" required></label>
      <label for="content">Content:<textarea name="content" id="content" cols="30" rows="10" required></textarea></label>
      <button type="submit">Submit</button>
      <button type="reset">Reset</button>
    </form>
  </div>
</template>

<script>
export default {

}
</script>

<style>
form {
  display: block;
}
form label {
  display:block;
}
form label textarea {
  display:block;
}
</style>
