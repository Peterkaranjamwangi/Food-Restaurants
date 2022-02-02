<template>
  <div>
    <v-container>
      <v-row>
        <v-col cols="3" class="hidden-sm-and-down">
          <v-sheet rounded="lg">
            <v-list>
              <v-list-item
                v-for="link in links"
                :key="link.text"
                router
                :to="link.route"
              >
                <v-list-item-content>
                  <v-list-item-tittle>{{ link.title }}</v-list-item-tittle>
                </v-list-item-content>
              </v-list-item>
            </v-list>
          </v-sheet>
        </v-col>

        <v-col>
          <v-sheet min-height="70vh" rounded="lg">
            <div data-v-761b993f="" class="box-content">
              <button data-v-761b993f="" type="button" class="hidden-md-and-up">
                <v-app-bar-nav-icon @click="drawermob = !drawermob">
                </v-app-bar-nav-icon>
                Categories
              </button>
              <div data-v-761b993f="">
                <div data-v-761b993f="" class="px-8">
                  <div data-v-761b993f="" class="row">
                    <div data-v-761b993f="" class="col col-12">
                      <h3 data-v-761b993f="" class="fw-bold">Recommended</h3>
                    </div>
                    <div data-v-761b993f="" class="col col-12">
                      <div
                        data-v-761b993f=""
                        class="d-flex justify-space-between align-center flex-wrap"
                      >
                        <div data-v-761b993f="" class="d-flex flex-wrap">
                          <div
                            class="v-avatar me-3 rounded-0"
                            style="
                              height: 150px;
                              min-width: 150px;
                              width: 150px;
                            "
                            data-v-761b993f=""
                          >
                            <img
                              src="https://images.unsplash.com/photo-1643381367072-8a7b387f1c53?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHx0b3BpYy1mZWVkfDExfHhqUFI0aGxrQkdBfHxlbnwwfHx8fA%3D%3D&auto=format&fit=crop&w=500&q=60"
                              alt=""
                            />
                          </div>
                          <div data-v-761b993f="">
                            <h5 data-v-761b993f="" class="f-600 mb-3">
                              Tandoori Chicken (Full)
                            </h5>
                            <span
                              class="text-uppercase mb-2 v-chip theme--light v-size--small grey lighten-4 secondary--text"
                              data-v-761b993f=""
                              ><span class="v-chip__content"
                                >Must Try</span
                              ></span
                            >
                            <div data-v-761b993f="" class="d-flex mb-3">
                              <i
                                aria-hidden="true"
                                class="v-icon notranslate mdi mdi-star theme--light amber--text"
                                style="font-size: 16px"
                                data-v-761b993f=""
                              ></i>
                              <i
                                aria-hidden="true"
                                class="v-icon notranslate mdi mdi-star theme--light amber--text"
                                style="font-size: 16px"
                                data-v-761b993f=""
                              ></i>
                              <i
                                aria-hidden="true"
                                class="v-icon notranslate mdi mdi-star theme--light amber--text"
                                style="font-size: 16px"
                                data-v-761b993f=""
                              ></i>
                              <i
                                aria-hidden="true"
                                class="v-icon notranslate mdi mdi-star theme--light amber--text"
                                style="font-size: 16px"
                                data-v-761b993f=""
                              ></i>
                              <i
                                aria-hidden="true"
                                class="v-icon notranslate mdi mdi-star theme--light amber--text"
                                style="font-size: 16px"
                                data-v-761b993f=""
                              ></i>
                              <h6
                                data-v-761b993f=""
                                class="ms-3 grey--text text--darken-1 font-weight-light"
                              >
                                (57)
                              </h6>
                            </div>
                            <div data-v-761b993f="" class="d-flex mb-1">
                              <p
                                data-v-761b993f=""
                                class="text-14 grey--text text--darken-1 text-decoration-line-through me-2 mb-0"
                              >
                                $25
                              </p>
                              <p
                                data-v-761b993f=""
                                class="text-14 grey--text text--darken-4 me-2 mb-0"
                              >
                                $22.5
                              </p>
                              <p
                                data-v-761b993f=""
                                class="text-14 primary--text mb-0"
                              >
                                10% off
                              </p>
                            </div>
                            <p
                              data-v-761b993f=""
                              class="text-14 grey--text text--darken-1"
                            >
                              (4 Pcs mutton in chicken keema gravy)
                            </p>
                          </div>
                        </div>
                        <div data-v-761b993f="">
                          <button
                            type="button"
                            class="v-btn v-btn--outlined theme--light v-size--small primary--text"
                            data-v-761b993f=""
                          >
                            <span class="v-btn__content">
                              Add
                              <i
                                aria-hidden="true"
                                class="v-icon notranslate v-icon--right mdi mdi-plus theme--light"
                                style="font-size: 16px"
                              ></i
                            ></span>
                          </button>
                        </div>
                      </div>
                    </div>
                    <div data-v-761b993f="" class="col col-12">
                      <div
                        data-v-761b993f=""
                        class="d-flex justify-space-between align-center flex-wrap"
                      >
                        <div data-v-761b993f="" class="d-flex flex-wrap">
                          <div
                            class="v-avatar me-3 rounded-0"
                            style="
                              height: 150px;
                              min-width: 150px;
                              width: 150px;
                            "
                            data-v-761b993f=""
                          >
                            <img
                              src="https://images.unsplash.com/photo-1641977916755-a90f24d6c673?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHx0b3BpYy1mZWVkfDU3fHhqUFI0aGxrQkdBfHxlbnwwfHx8fA%3D%3D&auto=format&fit=crop&w=500&q=60"
                              alt=""
                            />
                          </div>
                          <div data-v-761b993f="">
                            <h5 data-v-761b993f="" class="f-600 mb-3">
                              Tandoori Chicken (Full)
                            </h5>
                            <span
                              class="text-uppercase mb-2 v-chip theme--light v-size--small grey lighten-4 secondary--text"
                              data-v-761b993f=""
                              ><span class="v-chip__content"
                                >Must Try</span
                              ></span
                            >
                            <div data-v-761b993f="" class="d-flex mb-3">
                              <i
                                aria-hidden="true"
                                class="v-icon notranslate mdi mdi-star theme--light amber--text"
                                style="font-size: 16px"
                                data-v-761b993f=""
                              ></i>
                              <i
                                aria-hidden="true"
                                class="v-icon notranslate mdi mdi-star theme--light amber--text"
                                style="font-size: 16px"
                                data-v-761b993f=""
                              ></i>
                              <i
                                aria-hidden="true"
                                class="v-icon notranslate mdi mdi-star theme--light amber--text"
                                style="font-size: 16px"
                                data-v-761b993f=""
                              ></i>
                              <i
                                aria-hidden="true"
                                class="v-icon notranslate mdi mdi-star theme--light amber--text"
                                style="font-size: 16px"
                                data-v-761b993f=""
                              ></i>
                              <i
                                aria-hidden="true"
                                class="v-icon notranslate mdi mdi-star theme--light amber--text"
                                style="font-size: 16px"
                                data-v-761b993f=""
                              ></i>
                              <h6
                                data-v-761b993f=""
                                class="ms-3 grey--text text--darken-1 font-weight-light"
                              >
                                (57)
                              </h6>
                            </div>
                            <div data-v-761b993f="" class="d-flex mb-1">
                              <p
                                data-v-761b993f=""
                                class="text-14 grey--text text--darken-1 text-decoration-line-through me-2 mb-0"
                              >
                                $25
                              </p>
                              <p
                                data-v-761b993f=""
                                class="text-14 grey--text text--darken-4 me-2 mb-0"
                              >
                                $22.5
                              </p>
                              <p
                                data-v-761b993f=""
                                class="text-14 primary--text mb-0"
                              >
                                10% off
                              </p>
                            </div>
                            <p
                              data-v-761b993f=""
                              class="text-14 grey--text text--darken-1"
                            >
                              (4 Pcs mutton in chicken keema gravy)
                            </p>
                          </div>
                        </div>
                        <div data-v-761b993f="">
                          <button
                            type="button"
                            class="v-btn v-btn--outlined theme--light v-size--small primary--text"
                            data-v-761b993f=""
                          >
                            <span class="v-btn__content">
                              Add
                              <i
                                aria-hidden="true"
                                class="v-icon notranslate v-icon--right mdi mdi-plus theme--light"
                                style="font-size: 16px"
                              ></i
                            ></span>
                          </button>
                        </div>
                      </div>
                    </div>
                    <div data-v-761b993f="" class="col col-12">
                      <div
                        data-v-761b993f=""
                        class="d-flex justify-space-between align-center flex-wrap"
                      >
                        <div data-v-761b993f="" class="d-flex flex-wrap">
                          <div
                            class="v-avatar me-3 rounded-0"
                            style="
                              height: 150px;
                              min-width: 150px;
                              width: 150px;
                            "
                            data-v-761b993f=""
                          >
                            <img
                              src="https://images.unsplash.com/photo-1642670719873-e1158da4c462?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHx0b3BpYy1mZWVkfDMzfHhqUFI0aGxrQkdBfHxlbnwwfHx8fA%3D%3D&auto=format&fit=crop&w=500&q=60"
                              alt=""
                            />
                          </div>
                          <div data-v-761b993f="">
                            <h5 data-v-761b993f="" class="f-600 mb-3">
                              Tandoori Chicken (Full)
                            </h5>
                            <span
                              class="text-uppercase mb-2 v-chip theme--light v-size--small grey lighten-4 secondary--text"
                              data-v-761b993f=""
                              ><span class="v-chip__content"
                                >Must Try</span
                              ></span
                            >
                            <div data-v-761b993f="" class="d-flex mb-3">
                              <i
                                aria-hidden="true"
                                class="v-icon notranslate mdi mdi-star theme--light amber--text"
                                style="font-size: 16px"
                                data-v-761b993f=""
                              ></i>
                              <i
                                aria-hidden="true"
                                class="v-icon notranslate mdi mdi-star theme--light amber--text"
                                style="font-size: 16px"
                                data-v-761b993f=""
                              ></i>
                              <i
                                aria-hidden="true"
                                class="v-icon notranslate mdi mdi-star theme--light amber--text"
                                style="font-size: 16px"
                                data-v-761b993f=""
                              ></i>
                              <i
                                aria-hidden="true"
                                class="v-icon notranslate mdi mdi-star theme--light amber--text"
                                style="font-size: 16px"
                                data-v-761b993f=""
                              ></i>
                              <i
                                aria-hidden="true"
                                class="v-icon notranslate mdi mdi-star theme--light amber--text"
                                style="font-size: 16px"
                                data-v-761b993f=""
                              ></i>
                              <h6
                                data-v-761b993f=""
                                class="ms-3 grey--text text--darken-1 font-weight-light"
                              >
                                (57)
                              </h6>
                            </div>
                            <div data-v-761b993f="" class="d-flex mb-1">
                              <p
                                data-v-761b993f=""
                                class="text-14 grey--text text--darken-1 text-decoration-line-through me-2 mb-0"
                              >
                                $25
                              </p>
                              <p
                                data-v-761b993f=""
                                class="text-14 grey--text text--darken-4 me-2 mb-0"
                              >
                                $22.5
                              </p>
                              <p
                                data-v-761b993f=""
                                class="text-14 primary--text mb-0"
                              >
                                10% off
                              </p>
                            </div>
                            <p
                              data-v-761b993f=""
                              class="text-14 grey--text text--darken-1"
                            >
                              (4 Pcs mutton in chicken keema gravy)
                            </p>
                          </div>
                        </div>
                        <div data-v-761b993f="">
                          <button
                            type="button"
                            class="v-btn v-btn--outlined theme--light v-size--small primary--text"
                            data-v-761b993f=""
                          >
                            <span class="v-btn__content">
                              Add
                              <i
                                aria-hidden="true"
                                class="v-icon notranslate v-icon--right mdi mdi-plus theme--light"
                                style="font-size: 16px"
                              ></i
                            ></span>
                          </button>
                        </div>
                      </div>
                    </div>
                    <div data-v-761b993f="" class="col col-12">
                      <div
                        data-v-761b993f=""
                        class="d-flex justify-space-between align-center flex-wrap"
                      >
                        <div data-v-761b993f="" class="d-flex flex-wrap">
                          <div
                            class="v-avatar me-3 rounded-0"
                            style="
                              height: 150px;
                              min-width: 150px;
                              width: 150px;
                            "
                            data-v-761b993f=""
                          >
                            <img
                              src="https://images.unsplash.com/photo-1643133277936-9f93d8792522?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHx0b3BpYy1mZWVkfDI0fHhqUFI0aGxrQkdBfHxlbnwwfHx8fA%3D%3D&auto=format&fit=crop&w=500&q=60"
                              alt=""
                            />
                          </div>
                          <div data-v-761b993f="">
                            <h5 data-v-761b993f="" class="f-600 mb-3">
                              Tandoori Chicken (Full)
                            </h5>
                            <span
                              class="text-uppercase mb-2 v-chip theme--light v-size--small grey lighten-4 secondary--text"
                              data-v-761b993f=""
                              ><span class="v-chip__content"
                                >Must Try</span
                              ></span
                            >
                            <div data-v-761b993f="" class="d-flex mb-3">
                              <i
                                aria-hidden="true"
                                class="v-icon notranslate mdi mdi-star theme--light amber--text"
                                style="font-size: 16px"
                                data-v-761b993f=""
                              ></i>
                              <i
                                aria-hidden="true"
                                class="v-icon notranslate mdi mdi-star theme--light amber--text"
                                style="font-size: 16px"
                                data-v-761b993f=""
                              ></i>
                              <i
                                aria-hidden="true"
                                class="v-icon notranslate mdi mdi-star theme--light amber--text"
                                style="font-size: 16px"
                                data-v-761b993f=""
                              ></i>
                              <i
                                aria-hidden="true"
                                class="v-icon notranslate mdi mdi-star theme--light amber--text"
                                style="font-size: 16px"
                                data-v-761b993f=""
                              ></i>
                              <i
                                aria-hidden="true"
                                class="v-icon notranslate mdi mdi-star theme--light amber--text"
                                style="font-size: 16px"
                                data-v-761b993f=""
                              ></i>
                              <h6
                                data-v-761b993f=""
                                class="ms-3 grey--text text--darken-1 font-weight-light"
                              >
                                (57)
                              </h6>
                            </div>
                            <div data-v-761b993f="" class="d-flex mb-1">
                              <p
                                data-v-761b993f=""
                                class="text-14 grey--text text--darken-1 text-decoration-line-through me-2 mb-0"
                              >
                                $25
                              </p>
                              <p
                                data-v-761b993f=""
                                class="text-14 grey--text text--darken-4 me-2 mb-0"
                              >
                                $22.5
                              </p>
                              <p
                                data-v-761b993f=""
                                class="text-14 primary--text mb-0"
                              >
                                10% off
                              </p>
                            </div>
                            <p
                              data-v-761b993f=""
                              class="text-14 grey--text text--darken-1"
                            >
                              (4 Pcs mutton in chicken keema gravy)
                            </p>
                          </div>
                        </div>
                        <div data-v-761b993f="">
                          <button
                            type="button"
                            class="v-btn v-btn--outlined theme--light v-size--small primary--text"
                            data-v-761b993f=""
                          >
                            <span class="v-btn__content">
                              Add
                              <i
                                aria-hidden="true"
                                class="v-icon notranslate v-icon--right mdi mdi-plus theme--light"
                                style="font-size: 16px"
                              ></i
                            ></span>
                          </button>
                        </div>
                      </div>
                    </div>
                  </div>
                </div>
              </div>
            </div>
          </v-sheet>
        </v-col>
        <v-navigation-drawer
          app
          class="float-left"
          v-model="drawermob"
          absolute
          temporary
        >
          <v-list>
            <v-list-item
              v-for="link in links"
              :key="link.text"
              router
              :to="link.route"
            >
              <v-list-item-action>
                <v-icon> {{ link.icon }} </v-icon>
              </v-list-item-action>
              <v-list-item-content>
                <v-list-item-tittle>{{ link.title }}</v-list-item-tittle>
              </v-list-item-content>
            </v-list-item>
          </v-list>
        </v-navigation-drawer>
      </v-row>
    </v-container>
  </div>
</template>

<script>
export default {
  data() {
    return {
      drawermob: false,

      links: [
        { title: "Recomended (40)", route: "/about" },
        { title: "DPB Special Combos (10)", route: "/about" },
        { title: "Chineese Starters (30)", route: "/about" },
        { title: "Chinese Main Course (75)", route: "/about" },
        { title: "Indian Main Course (63)", route: "/about" },
        { title: "Rice & Pulao (7)", route: "/about" },
        { title: "Desserts (1)", route: "/about" },
        { title: "Soup & wonton (15)", route: "/about" },
        { title: "My Account", route: "/about" },
        { title: "Accompaniment (4)", route: "/about" },
        { title: "Biryani (1)", route: "/about" },
      ],
    };
  },
};
</script>
