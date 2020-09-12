<script lang="ts">
  import { Router } from "@sveltech/routify";
  import { routes } from "../.routify/routes";
  import "smelte/src/tailwind.css" ;
</script>

<style  global>
  @import "../static/global.css";
</style>

<Router {routes} />