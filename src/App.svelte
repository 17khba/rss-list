<script lang="ts">
  import "rss-list";
  import rssListData from "./data/rss-list.json";
</script>

<main>
  <rss-list data={rssListData}>
    <h1>Rss List</h1>
  </rss-list>
</main>

<style>
  :root {
    font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Oxygen,
      Ubuntu, Cantarell, "Open Sans", "Helvetica Neue", sans-serif;
  }

  main {
    width: 800px;
    text-align: left;
    padding: 1em;
    margin: 0 auto;
  }
</style>
