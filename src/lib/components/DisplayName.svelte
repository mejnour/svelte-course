<script lang="ts">
    let name = "Mejnour";
    let src = "https://picsum.photos/250/300";
    let bio = 'Hello tags <b>this</b> is me.';
</script>

<h1>Hello {name}</h1>

<img src={src} alt={`Photo of ${name}`} />

<img src={src} alt="Photo of {name}" />

<p>
  {bio}
</p>

<p>
  {@html bio}
</p>

<style>
  h1 {
    color: red;
  }
</style>
