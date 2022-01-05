<template>
  <div class="container">
    <h3
      v-for="(card, index) in howItWorksCard"
      :title="card.title"
      :key="index"
    >
      {{ card.title }}
    </h3>

    <p
      v-for="(card, index) in howItWorksCard"
      :description="card.description"
      :key="index"
    >
      {{ card.description }}
    </p>
  </div>
</template>

<script>
export default {
  data() {
    return {
      howItWorksCard: [
        {
          title: "Search",
          description:
            "Find a home from our search bar. Enter your specific location and date",
        },
        {
          title: "Choose",
          description:
            "Choose your desire home on expected date for your events.",
        },
        {
          title: "Book",
          description: "Book your desire home expected date for your events.",
        },
      ],
    };
  },
};
</script>

<style>
.container {
  display: flex;
  width: 925px;
  height: 300px;
  justify-content: space-evenly;
  flex-wrap: wrap;
  border: 1px solid black;
}
.container h3 {
  font-weight: 400;
  font-size: 25px;
  border: 1px solid black;
  color: black;
  height: 50px;
  width: 240px;
  flex-grow: 1;
  padding-bottom: 0;
}
.container h3:nth-child(2) {
  line-height: 70px;
  margin-left: 85px;
}
.container h3:nth-child(3) {
  margin-left: 90px;
}
.container p {
  border: 1px solid red;
  margin-top: 0%;
  margin-right: 30px;
  width: 250px;
  height: 60px;

  font-size: 14px;
  color: #888888;
  margin-bottom: 300px;
}
</style>
