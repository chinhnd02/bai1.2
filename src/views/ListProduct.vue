<template>
  <div>
    <v-container>
      <div class="headerPage">
        <v-row>
          <v-col cols="2">
            <v-select
              width="136"
              label="Useless first"
              density="compact"
              :items="[
                'California',
                'Colorado',
                'Florida',
                'Georgia',
                'Texas',
                'Wyoming',
              ]"
              variant="outlined"
            ></v-select>
          </v-col>
          <v-col cols="2">
            <v-select
              label="Condition"
              density="compact"
              :items="[
                'California',
                'Colorado',
                'Florida',
                'Georgia',
                'Texas',
                'Wyoming',
              ]"
              variant="outlined"
            ></v-select>
          </v-col>
          <v-col cols="2">
            <v-select
              label="Delivery Options"
              density="compact"
              :items="[
                'California',
                'Colorado',
                'Florida',
                'Georgia',
                'Texas',
                'Wyoming',
              ]"
              variant="outlined"
            ></v-select>
          </v-col>
          <v-col class="py-2">
            <v-btn-toggle v-model="text" rounded="0" color="#FFFFFF" group>
              <v-btn
                style="font-size: 14px; border-radius: 2px"
                class="text-capitalize"
                value="left"
                height="36"
                width="85"
              >
                Show all
              </v-btn>

              <v-btn
                value="center"
                style="font-size: 14px; border-radius: 2px"
                class="text-capitalize"
                height="36"
                width="85"
              >
                Aution
              </v-btn>

              <v-btn
                value="right"
                style="font-size: 14px; border-radius: 2px"
                class="text-capitalize"
                height="36"
                width="85"
              >
                Buy now
              </v-btn>
            </v-btn-toggle>
          </v-col>
          <v-col cols="2">
            <v-btn-toggle v-model="options" rounded="0" color="#FFFFFF" group>
              <v-btn
                style="font-size: 14px; border-radius: 2px"
                class="text-capitalize"
                value="0"
                height="36"
                width="85"
              >
                <img src="../assets/image/Vector.png" alt="" />
              </v-btn>

              <v-btn
                value="1"
                style="font-size: 14px; border-radius: 2px"
                class="text-capitalize"
                height="36"
                width="85"
              >
                <img src="../assets/image/Vector (1).png" alt="" />
              </v-btn>
            </v-btn-toggle>
          </v-col>
        </v-row>
        <v-row>
          <p
            class="mr-5 ml-4"
            style="line-height: 46px; font-weight: 600; font-size: 14px"
          >
            Related
          </p>
          <v-chip-group>
            <v-chip style="font-size: 14px; font-weight: 400"
              >worldwide shipping</v-chip
            >

            <v-chip style="font-size: 14px; font-weight: 400">under $50</v-chip>

            <v-chip style="font-size: 14px; font-weight: 400"
              >plastic plugs</v-chip
            >
            <v-chip style="font-size: 14px; font-weight: 400"
              >pucker shoes</v-chip
            >
            <v-chip style="font-size: 14px; font-weight: 400"
              >vintage typewriter</v-chip
            >
          </v-chip-group>
        </v-row>
        <v-row>
          <v-card width="260" height="472" class="ml-8 mt-7">
            <img src="../assets/Image.png" alt="" />

            <!-- <v-card-title> -->
            <!-- <span style="font-size: 16px; font-weight: 400; line-height: 24px"
                >Vintage Typewriter to post awesome stories about UI design and
                webdev.</span
              > -->
            <v-card-text
              class="text-left"
              style="font-size: 16px; font-weight: 400; line-height: 24px"
            >
              Vintage Typewriter to post awesome stories about UI design and
              webdev.
            </v-card-text>
            <!-- </v-card-title> -->
            <!-- <v-card-item> -->
            <v-card-text style="padding: 0">
              <p
                class="text-left"
                style="
                  font-weight: 700;
                  font-size: 24px;
                  line-height: 36px;
                  padding: 0 15px 8px 15px;
                "
              >
                $49.50
              </p>
              <p class="text-left" style="padding: 0 15px 8px 15px">
                Eligible for Shipping To Mars or somewhere else
              </p>
            </v-card-text>
            <v-row>
              <!-- <v-col> -->
              <div class="rating" style="padding: 15px 15px 15px 26px">
                <input value="5" name="rate" id="star5" type="radio" />
                <label title="text" for="star5"></label>
                <input value="4" name="rate" id="star4" type="radio" />
                <label title="text" for="star4"></label>
                <input
                  value="3"
                  name="rate"
                  id="star3"
                  type="radio"
                  checked=""
                />
                <label title="text" for="star3"></label>
                <input value="2" name="rate" id="star2" type="radio" />
                <label title="text" for="star2"></label>
                <input value="1" name="rate" id="star1" type="radio" />
                <label title="text" for="star1"></label>
              </div>
              <p style="font-size: 14px; font-weight: 500; padding: 18px 0">
                4.05
              </p>
              <!-- </v-col> -->
              <!-- <v-col> -->
              <v-btn
                variant="outlined"
                color="#2264D1"
                width="88"
                height="32"
                class="text-capitalize mt-3 ml-8"
                style="font-size: 14px"
              >
                <v-icon
                  icon="mdi mdi-heart-outline"
                  small
                  class="mr-1"
                ></v-icon>
                Watch
              </v-btn>
              <!-- </v-col> -->
            </v-row>
            <!-- </v-card-item> -->
          </v-card>
          <v-card width="260" height="472" class="ml-8 mt-7">
            <img src="../assets/Image.png" alt="" />

            <!-- <v-card-title> -->
            <!-- <span style="font-size: 16px; font-weight: 400; line-height: 24px"
                >Vintage Typewriter to post awesome stories about UI design and
                webdev.</span
              > -->
            <v-card-text
              class="text-left"
              style="font-size: 16px; font-weight: 400; line-height: 24px"
            >
              Vintage Typewriter to post awesome stories about UI design and
              webdev.
            </v-card-text>
            <!-- </v-card-title> -->
            <!-- <v-card-item> -->
            <v-card-text style="padding: 0">
              <p
                class="text-left"
                style="
                  font-weight: 700;
                  font-size: 24px;
                  line-height: 36px;
                  padding: 0 15px 8px 15px;
                "
              >
                $49.50
              </p>
              <p class="text-left" style="padding: 0 15px 8px 15px">
                Eligible for Shipping To Mars or somewhere else
              </p>
            </v-card-text>
            <v-row>
              <!-- <v-col> -->
              <div class="rating" style="padding: 15px 15px 15px 26px">
                <input value="5" name="rate" id="star5" type="radio" />
                <label title="text" for="star5"></label>
                <input value="4" name="rate" id="star4" type="radio" />
                <label title="text" for="star4"></label>
                <input
                  value="3"
                  name="rate"
                  id="star3"
                  type="radio"
                  checked=""
                />
                <label title="text" for="star3"></label>
                <input value="2" name="rate" id="star2" type="radio" />
                <label title="text" for="star2"></label>
                <input value="1" name="rate" id="star1" type="radio" />
                <label title="text" for="star1"></label>
              </div>
              <p style="font-size: 14px; font-weight: 500; padding: 18px 0">
                4.05
              </p>
              <!-- </v-col> -->
              <!-- <v-col> -->
              <v-btn
                variant="outlined"
                color="#2264D1"
                width="88"
                height="32"
                class="text-capitalize mt-3 ml-8"
                style="font-size: 14px"
              >
                <v-icon
                  icon="mdi mdi-heart-outline"
                  small
                  class="mr-1"
                ></v-icon>
                Watch
              </v-btn>
              <!-- </v-col> -->
            </v-row>
            <!-- </v-card-item> -->
          </v-card>
          <v-card width="260" height="472" class="ml-8 mt-7">
            <img src="../assets/Image.png" alt="" />

            <!-- <v-card-title> -->
            <!-- <span style="font-size: 16px; font-weight: 400; line-height: 24px"
                >Vintage Typewriter to post awesome stories about UI design and
                webdev.</span
              > -->
            <v-card-text
              class="text-left"
              style="font-size: 16px; font-weight: 400; line-height: 24px"
            >
              Vintage Typewriter to post awesome stories about UI design and
              webdev.
            </v-card-text>
            <!-- </v-card-title> -->
            <!-- <v-card-item> -->
            <v-card-text style="padding: 0">
              <p
                class="text-left"
                style="
                  font-weight: 700;
                  font-size: 24px;
                  line-height: 36px;
                  padding: 0 15px 8px 15px;
                "
              >
                $49.50
              </p>
              <p class="text-left" style="padding: 0 15px 8px 15px">
                Eligible for Shipping To Mars or somewhere else
              </p>
            </v-card-text>
            <v-row>
              <!-- <v-col> -->
              <div class="rating" style="padding: 15px 15px 15px 26px">
                <input value="5" name="rate" id="star5" type="radio" />
                <label title="text" for="star5"></label>
                <input value="4" name="rate" id="star4" type="radio" />
                <label title="text" for="star4"></label>
                <input
                  value="3"
                  name="rate"
                  id="star3"
                  type="radio"
                  checked=""
                />
                <label title="text" for="star3"></label>
                <input value="2" name="rate" id="star2" type="radio" />
                <label title="text" for="star2"></label>
                <input value="1" name="rate" id="star1" type="radio" />
                <label title="text" for="star1"></label>
              </div>
              <p style="font-size: 14px; font-weight: 500; padding: 18px 0">
                4.05
              </p>
              <!-- </v-col> -->
              <!-- <v-col> -->
              <v-btn
                variant="outlined"
                color="#2264D1"
                width="88"
                height="32"
                class="text-capitalize mt-3 ml-8"
                style="font-size: 14px"
              >
                <v-icon
                  icon="mdi mdi-heart-outline"
                  small
                  class="mr-1"
                ></v-icon>
                Watch
              </v-btn>
              <!-- </v-col> -->
            </v-row>
            <!-- </v-card-item> -->
          </v-card>
          <v-card width="260" height="472" class="ml-8 mt-7">
            <img src="../assets/Image.png" alt="" />

            <!-- <v-card-title> -->
            <!-- <span style="font-size: 16px; font-weight: 400; line-height: 24px"
                >Vintage Typewriter to post awesome stories about UI design and
                webdev.</span
              > -->
            <v-card-text
              class="text-left"
              style="font-size: 16px; font-weight: 400; line-height: 24px"
            >
              Vintage Typewriter to post awesome stories about UI design and
              webdev.
            </v-card-text>
            <!-- </v-card-title> -->
            <!-- <v-card-item> -->
            <v-card-text style="padding: 0">
              <p
                class="text-left"
                style="
                  font-weight: 700;
                  font-size: 24px;
                  line-height: 36px;
                  padding: 0 15px 8px 15px;
                "
              >
                $49.50
              </p>
              <p class="text-left" style="padding: 0 15px 8px 15px">
                Eligible for Shipping To Mars or somewhere else
              </p>
            </v-card-text>
            <v-row>
              <!-- <v-col> -->
              <div class="rating" style="padding: 15px 15px 15px 26px">
                <input value="5" name="rate" id="star5" type="radio" />
                <label title="text" for="star5"></label>
                <input value="4" name="rate" id="star4" type="radio" />
                <label title="text" for="star4"></label>
                <input
                  value="3"
                  name="rate"
                  id="star3"
                  type="radio"
                  checked=""
                />
                <label title="text" for="star3"></label>
                <input value="2" name="rate" id="star2" type="radio" />
                <label title="text" for="star2"></label>
                <input value="1" name="rate" id="star1" type="radio" />
                <label title="text" for="star1"></label>
              </div>
              <p style="font-size: 14px; font-weight: 500; padding: 18px 0">
                4.05
              </p>
              <!-- </v-col> -->
              <!-- <v-col> -->
              <v-btn
                variant="outlined"
                color="#2264D1"
                width="88"
                height="32"
                class="text-capitalize mt-3 ml-8"
                style="font-size: 14px"
              >
                <v-icon
                  icon="mdi mdi-heart-outline"
                  small
                  class="mr-1"
                ></v-icon>
                Watch
              </v-btn>
              <!-- </v-col> -->
            </v-row>
            <!-- </v-card-item> -->
          </v-card>
          <v-card width="260" height="472" class="ml-8 mt-7">
            <img src="../assets/Image.png" alt="" />

            <!-- <v-card-title> -->
            <!-- <span style="font-size: 16px; font-weight: 400; line-height: 24px"
                >Vintage Typewriter to post awesome stories about UI design and
                webdev.</span
              > -->
            <v-card-text
              class="text-left"
              style="font-size: 16px; font-weight: 400; line-height: 24px"
            >
              Vintage Typewriter to post awesome stories about UI design and
              webdev.
            </v-card-text>
            <!-- </v-card-title> -->
            <!-- <v-card-item> -->
            <v-card-text style="padding: 0">
              <p
                class="text-left"
                style="
                  font-weight: 700;
                  font-size: 24px;
                  line-height: 36px;
                  padding: 0 15px 8px 15px;
                "
              >
                $49.50
              </p>
              <p
                class="text-left"
                style="padding: 0 15px 8px 15px; color: #787885"
              >
                Eligible for Shipping To Mars or somewhere else
              </p>
            </v-card-text>
            <v-row>
              <!-- <v-col> -->
              <div class="rating" style="padding: 15px 15px 15px 26px">
                <input value="5" name="rate" id="star5" type="radio" />
                <label title="text" for="star5"></label>
                <input value="4" name="rate" id="star4" type="radio" />
                <label title="text" for="star4"></label>
                <input
                  value="3"
                  name="rate"
                  id="star3"
                  type="radio"
                  checked=""
                />
                <label title="text" for="star3"></label>
                <input value="2" name="rate" id="star2" type="radio" />
                <label title="text" for="star2"></label>
                <input value="1" name="rate" id="star1" type="radio" />
                <label title="text" for="star1"></label>
              </div>
              <p style="font-size: 14px; font-weight: 500; padding: 18px 0">
                4.05
              </p>
              <!-- </v-col> -->
              <!-- <v-col> -->
              <v-btn
                variant="outlined"
                color="#2264D1"
                width="88"
                height="32"
                class="text-capitalize mt-3 ml-8"
                style="font-size: 14px"
              >
                <v-icon
                  icon="mdi mdi-heart-outline"
                  small
                  class="mr-1"
                ></v-icon>
                Watch
              </v-btn>
              <!-- </v-col> -->
            </v-row>
            <!-- </v-card-item> -->
          </v-card>
        </v-row>
        <v-row class="mt-10 mb-8">
          <v-card
            class="ml-7"
            style="background-color: #ededf0; width: 360px; height: 160px"
          >
            <img class="mt-8" src="../assets/image/Vector (2).png" alt="" />
            <v-card-item>
              <p
                style="
                  font-weight: 700;
                  font-size: 20px;
                  line-height: 30px;
                  color: #000000;
                "
              >
                Customizable & Reusable
              </p>
              <p
                style="
                  font-weight: 400;
                  font-size: 14px;
                  line-height: 30px;
                  color: #5a5b6a;
                "
              >
                Take our UX patterns and rebuild
              </p>
            </v-card-item>
          </v-card>
          <v-card
            class="ml-7 mr-7"
            style="background-color: #ededf0; width: 360px; height: 160px"
          >
            <img class="mt-8" src="../assets/image/Vector (2).png" alt="" />
            <v-card-item>
              <p
                style="
                  font-weight: 700;
                  font-size: 20px;
                  line-height: 30px;
                  color: #000000;
                "
              >
                Customizable & Reusable
              </p>
              <p
                style="
                  font-weight: 400;
                  font-size: 14px;
                  line-height: 30px;
                  color: #5a5b6a;
                "
              >
                Take our UX patterns and rebuild
              </p>
            </v-card-item>
          </v-card>
          <v-card
            style="background-color: #ededf0; width: 360px; height: 160px"
          >
            <img class="mt-8" src="../assets/image/Vector (2).png" alt="" />
            <v-card-item>
              <p
                style="
                  font-weight: 700;
                  font-size: 20px;
                  line-height: 30px;
                  color: #000000;
                "
              >
                Customizable & Reusable
              </p>
              <p
                style="
                  font-weight: 400;
                  font-size: 14px;
                  line-height: 30px;
                  color: #5a5b6a;
                "
              >
                Take our UX patterns and rebuild
              </p>
            </v-card-item>
          </v-card>
        </v-row>
      </div>
    </v-container>
  </div>
</template>

<script>
export default {
  data() {
    return {
      text: "center",
      icon: "justify",
      toggle_none: null,
      toggle_one: 0,
      toggle_exclusive: 2,
      toggle_multiple: [0, 1, 2],
      options: "left",
    };
  },
};
</script>

<style scoped>
.rating:not(:checked) > input {
  position: absolute;
  appearance: none;
}

.rating:not(:checked) > label {
  float: right;
  cursor: pointer;
  font-size: 16px;
  color: #666;
}

.rating:not(:checked) > label:before {
  content: "★";
}

.rating > input:checked + label:hover,
.rating > input:checked + label:hover ~ label,
.rating > input:checked ~ label:hover,
.rating > input:checked ~ label:hover ~ label,
.rating > label:hover ~ input:checked ~ label {
  color: #e58e09;
}

.rating:not(:checked) > label:hover,
.rating:not(:checked) > label:hover ~ label {
  color: #ff9e0b;
}

.rating > input:checked ~ label {
  color: #ffa723;
}
</style>