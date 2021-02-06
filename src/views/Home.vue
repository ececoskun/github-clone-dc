<template>
  <div class="home">
    <repo-card />
  </div>
</template>

<script>
import RepoCard from "@/components/Home/RepoCard";
export default {
  name: "Home",
  components: {
    RepoCard
  }
};
</script>
