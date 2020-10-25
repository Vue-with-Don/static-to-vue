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
          <div>NAME</div>
          <input type="text" name="name" />
        </div>
        <div class="field">
          <div>EMAIL</div>
          <input type="email" name="email" />
        </div>
        <div class="field">
          <div>MESSAGE</div>
          <textarea name="message" rows="4"></textarea>
        </div>
      </div>
      <div class="actions">
        <input type="button" value="Send Message" />
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
