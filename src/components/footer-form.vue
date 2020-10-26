<template>
  <div>
    <h2 class="major">Get in touch</h2>
    <p>
      Cras mattis ante fermentum, malesuada neque vitae, eleifend erat.
      Phasellus non pulvinar erat. Fusce tincidunt, nisl eget mattis
      egestas, purus ipsum consequat orci, sit amet lobortis lorem lacus
      in tellus. Sed ac elementum arcu. Quisque placerat auctor laoreet.
    </p>
    <form method="post" action="#">
      <div class="fields">
        <div class="field">
          <label><input type="text" name="name" /></label>	
        </div>
        <div class="field">
          <label><input type="email" name="email" /></label>
        </div>
        <div class="field">
          <label><textarea name="message" rows="4"></textarea></label>
        </div>
      </div>
      <div class="actions">
        <button value="Send Message" />
      </div>
    </form>
  </div>
</template>

<script>
export default {
  props: {},
};
</script>

<style></style>
