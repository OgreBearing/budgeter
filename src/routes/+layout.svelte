<script lang="ts">
    import Header from  "../stories/Header.svelte";

    let user = null;

</script>
<Header
  {user}
  on:login={()=>""}
  on:logout={()=>""}
/>
<slot></slot>