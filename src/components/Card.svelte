<script>
  import Comments from './Comments.svelte';
</script>

<div class="Card">
  <div class="Card-container">
    <div class="Card-header">
      <div class="Card-user">
        <img src="https://cdn.itoxic.me/low_profile.png" alt="Toxic#2381">
        <h2>
          Toxic#2381
          <span>Medellín, Colombia</span>
        </h2>
      </div>
      <div>
        <i class="fas fa-ellipsis-h" />
      </div>
    </div>
    <div class="Card-photo">
      <figure>
        <img src="https://cdn.itoxic.me/low_profile.png" alt="Toxic#2381">
      </figure>
    </div>
    <div class="Card-icons">
      <div class="Card-icons-first">
        <i class="fas fa-heart" />
        <i class="fas fa-share-alt" />
      </div>
      <div class="Card-icons-second">
        <i class="fas fa-bookmark" />
      </div>
      <div class="Card-description">
        <h3>Toxic#2381</h3>
        <span>Hola!</span>
      </div>
      <Comments />
    </div>
  </div>
</div>