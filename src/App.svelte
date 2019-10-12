<script>
  import Header from "./UI/Header.svelte";
  import MeetupGrid from "./Meetups/MeetupGrid.svelte";
  const meetups = [
    {
      id: "1",
      title: "Coding Bootcamp",
      subtitle: "learn to code in 2 hours",
      content:
        "In this meetup, we will have some experts that teach you how to code",
      imageUrl: "sample-image.jpeg",
      address: "27th Nerd Road, 31231, New York",
      contactEmail: "code@test.com"
    },
    {
      id: "2",
      title: "Swim Together",
      subtitle: `Let's go for some swimming`,
      content: `Let's swim the canal!`,
      imageUrl: "sample-image.jpeg",
      address: "27th Nerd Road, 31231, New York",
      contactEmail: "code@test.com"
    }
  ];
</script>

<style>
  main {
    margin-top: 5rem;
  }
</style>

<Header />
<main>
  <MeetupGrid {meetups}/>
</main>
