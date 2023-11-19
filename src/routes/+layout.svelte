<script lang="ts">
  import "../app.css";
  import { user, userData } from "../lib/firebase";

  $user;
  $userData;
</script>

<div class="min-h-screen flex flex-col">
  <slot />
</div>
