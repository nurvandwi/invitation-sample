<template>
  <div class="bg-couple">
    <div class="container ">
      <div class=""></div>
      <Tabs>
        <Tab name="Akad Nikah" selected="true">
          <div class="text-center text-white border py-5">
            <h2 class="py-5">Akad Nikah</h2>
            <h3>Date : Des, 19, 2020 | 8 AM TILL END</h3>
            <br />
            <h3>
              Location: Jalan ABC, Komplek, Perumahan <br />Griya, Bandung, Jawa
              Barat
            </h3>
            <div class="py-5 ">
              <button
                type="button"
                class="btn bg-btn font-weight-bolder btn-outline-secondary text-dark py-3 col-3 "
              >
                Save The Date
              </button>
            </div>
          </div>
          <div class="py-5 text-center">
            <a
              type="button"
              class="btn bg-btn mx-4 font-weight-bolder btn-outline-secondary text-dark py-3 col-1 "
            >
              10 DAYS
            </a>
            <a
              type="button"
              class="btn bg-btn font-weight-bolder btn-outline-secondary text-dark py-3 col-2 "
            >
              12 HOURS
            </a>
          </div>
        </Tab>
        <Tab name="Resepsi Nikah">
          <div class="text-center text-white border py-5">
            <h2 class="py-5 ">Resepsi Nikah</h2>
            <h3>Date : Des, 19, 2020 | 8 AM TILL END</h3>
            <br />
            <h3>
              Location: Jalan ABC, Komplek, Perumahan <br />Griya, Bandung, Jawa
              Barat
            </h3>
            <div class="py-5 ">
              <button
                type="button"
                class="btn bg-btn font-weight-bolder btn-outline-secondary text-dark py-3 col-3 "
              >
                Save The Date
              </button>
            </div>
          </div>
          <div class="py-5 text-center ">
            <a
              type="button"
              class="btn bg-btn mx-4 font-weight-bolder btn-outline-secondary text-dark py-3 col-1 "
            >
              10 DAYS
            </a>
            <a
              type="button"
              class="btn bg-btn font-weight-bolder btn-outline-secondary text-dark py-3 col-1 "
            >
              12 HOURS
            </a>
          </div>
        </Tab>
      </Tabs>
    </div>
  </div>
</template>

<script>
import Tab from "@/components/Tab.vue";
import Tabs from "@/components/Tabs.vue";
export default {
  components: { Tab, Tabs }
};
</script>

<style scoped>
@import url("https://fonts.googleapis.com/css2?family=Parisienne&display=swap");
@import url("https://fonts.googleapis.com/css2?family=Montserrat&display=swap");
h1 {
  font-size: 4em;
}

h5,
a {
  font-family: "Montserrat", sans-serif;
  font-size: 1em;
}

.bg-btn {
  background: #ffffff;
  opacity: 0.4;
  border-radius: 8px;
}

.image-adjust img {
  height: 6rem;
}

.border {
  border-radius: 20px;
}

ul li {
  list-style: none;
  text-transform: uppercase;
}

.margin-custom {
  margin-top: 40vh;
}

.bg-couple {
  width: 100%;
  height: auto;
  background: url("../assets/invit.png") no-repeat center center;
  -webkit-background-size: cover;
  -moz-background-size: cover;
  -o-background-size: cover;
  background-size: cover;
}
</style>