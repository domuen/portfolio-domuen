<script lang="ts">
  import PersonCard from "./components/PersonCard.svelte";
  import ContactCard from "./components/ContactCard.svelte";
  import ResumeCard from "./components/ResumeCard.svelte";

  import PersonalProjectsCard from "./components/PersonalProjectsCard.svelte";
</script>

<div class="flex justify-center p-4 gap-4">
  <div class="flex lg:flex-row flex-col w-6xl gap-4">
    <!-- left column -->
    <div class="flex flex-col lg:w-1/3 w-full gap-4">
      <PersonCard />

      <ContactCard />

      <ResumeCard />
    </div>

    <!-- right column -->
    <div class="flex flex-col lg:w-2/3 w-full gap-4">
      <PersonalProjectsCard />
    </div>
  </div>
</div>
