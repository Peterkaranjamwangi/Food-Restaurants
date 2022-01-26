<template>
  <div>
    <!-- <v-app-bar app shrink-on-scroll>
      <v-toolbar-title>Application</v-toolbar-title>

      <v-spacer></v-spacer>

      <v-app-bar-nav-icon @click="drawermob = !drawermob"
        ><v-icon>mdi-dots-grid</v-icon></v-app-bar-nav-icon
      >
    </v-app-bar> -->
    <div>
      <div
        data-app="true"
        id="app"
        class="v-application v-application--is-ltr theme--light"
      >
        <div class="v-application--wrap">
          <div class="hero-section">
            <div class="nav" data-v-42ba0752="">
              <header
                class="v-sheet theme--light v-toolbar v-app-bar v-app-bar--elevate-on-scroll v-app-bar--fixed v-app-bar--is-scrolled white"
                style="
                  width: 100%;
                  height: 64px;
                  margin-top: 0px;
                  transform: translateY(0px);
                  left: 0px;
                  right: 0px;
                "
                data-v-42ba0752=""
                data-booted="true"
              >
                <div class="v-toolbar__content" style="height: 64px">
                  <div class="container d-flex align-center" data-v-42ba0752="">
                    <a
                      href="/"
                      aria-current="page"
                      class="nuxt-link-exact-active nuxt-link-active"
                      data-v-42ba0752=""
                      ><div
                        class="v-avatar me-10 rounded-0"
                        style="height: 48px; min-width: 48px; width: 48px"
                        data-v-42ba0752=""
                      >
                        <img
                          src="/_nuxt/img/logo.4a3964e.png"
                          alt=""
                          data-v-42ba0752=""
                        /></div
                    ></a>
                    <div
                      class="form-location flex-grow-1 d-none d-md-flex border rounded"
                      data-v-42ba0752=""
                    >
                      <div class="d-flex align-center ps-5" data-v-42ba0752="">
                        <i
                          aria-hidden="true"
                          class="v-icon notranslate v-icon--left mdi mdi-map-marker theme--light"
                          style="font-size: 16px"
                          data-v-42ba0752=""
                        ></i>
                        <span
                          class="grey--text text--darken-1 me-3"
                          data-v-42ba0752=""
                          >New York</span
                        >
                      </div>
                      <button
                        type="button"
                        class="text-capitalize rounded-0 v-btn v-btn--icon v-btn--round v-btn--text v-btn--tile theme--light v-size--large"
                        data-v-42ba0752=""
                      >
                        <span class="v-btn__content"
                          ><i
                            aria-hidden="true"
                            class="v-icon notranslate mdi mdi-crosshairs-gps theme--light"
                            style="font-size: 16px"
                            data-v-42ba0752=""
                          ></i
                        ></span>
                      </button>
                      <input
                        placeholder="Search for restaurant "
                        class="white flex-grow-1 ps-5"
                        data-v-42ba0752=""
                      />
                      <button
                        type="button"
                        class="rounded-l-0 text-capitalize v-btn v-btn--icon v-btn--round v-btn--tile theme--light v-size--large"
                        data-v-42ba0752=""
                      >
                        <span class="v-btn__content"
                          ><i
                            aria-hidden="true"
                            class="v-icon notranslate mdi mdi-magnify theme--light"
                            style="font-size: 16px"
                            data-v-42ba0752=""
                          ></i
                        ></span>
                      </button>
                    </div>
                    <div class="spacer" data-v-42ba0752=""></div>
                    <div
                      role="dialog"
                      class="v-dialog__container"
                      data-v-42ba0752=""
                    >
                      <!---->
                    </div>
                    <button
                      type="button"
                      role="button"
                      aria-haspopup="true"
                      aria-expanded="false"
                      class="v-btn v-btn--text theme--light v-size--default"
                      data-v-42ba0752=""
                    >
                      <span class="v-btn__content"
                        ><i
                          aria-hidden="true"
                          class="v-icon notranslate me-0 me-sm-3 mdi mdi-account-circle-outline theme--light"
                          data-v-42ba0752=""
                        ></i>
                        <span class="d-none d-sm-block" data-v-42ba0752=""
                          >Account</span
                        ></span
                      >
                    </button>
                    <button
                      type="button"
                      class="me-2 v-btn v-btn--text v-btn--tile theme--light v-size--default"
                      data-v-42ba0752=""
                    >
                      <span class="v-btn__content"
                        ><i
                          aria-hidden="true"
                          class="v-icon notranslate mdi mdi-cart-outline theme--light"
                          style="font-size: 16px"
                          data-v-42ba0752=""
                        ></i
                        >(8)
                      </span>
                    </button>
                    <button
                      type="button"
                      text=""
                      light=""
                      class="v-app-bar__nav-icon v-btn v-btn--icon v-btn--round v-btn--text theme--light v-size--default"
                      data-v-42ba0752=""
                    >
                      <span class="v-btn__content"
                        ><i
                          aria-hidden="true"
                          class="v-icon notranslate mdi mdi-menu theme--light"
                          data-v-42ba0752=""
                        ></i
                      ></span>
                    </button>
                  </div>
                </div>
              </header>
              <aside
                class="v-navigation-drawer v-navigation-drawer--close v-navigation-drawer--fixed v-navigation-drawer--right v-navigation-drawer--temporary theme--light"
                style="
                  height: 100%;
                  top: 0;
                  transform: translateX(100%);
                  width: 320px;
                "
                data-v-42ba0752=""
                data-booted="true"
              >
                <div class="v-navigation-drawer__content">
                  <div data-v-42ba0752="">
                    <div
                      class="d-flex justify-space-between align-center ps-4 pe-3 mt-3 mb-2"
                    >
                      <div class="d-flex align-center">
                        <i
                          aria-hidden="true"
                          class="v-icon notranslate me-1 mdi mdi-shopping-outline theme--light"
                        ></i>
                        <h4 class="mb-0 grey--text text--darken-1 f-600">
                          1 Item
                        </h4>
                      </div>
                      <button
                        type="button"
                        class="v-btn v-btn--icon v-btn--round theme--light v-size--default"
                        data-v-42ba0752=""
                      >
                        <span class="v-btn__content"
                          ><i
                            aria-hidden="true"
                            class="v-icon notranslate mdi mdi-close theme--light primary--text"
                            data-v-42ba0752=""
                          ></i
                        ></span>
                      </button>
                    </div>
                    <hr
                      role="separator"
                      aria-orientation="horizontal"
                      class="v-divider theme--light"
                    />
                    <div class="navbar-scroll">
                      <div>
                        <div
                          class="d-flex align-center justify-space-between pa-3 mb-4"
                        >
                          <div class="d-flex align-center">
                            <div class="text-center me-3">
                              <button
                                type="button"
                                class="v-btn v-btn--icon v-btn--outlined v-btn--round theme--light v-size--small primary--text"
                              >
                                <span class="v-btn__content"
                                  ><i
                                    aria-hidden="true"
                                    class="v-icon notranslate mdi mdi-plus theme--light"
                                  ></i
                                ></span>
                              </button>
                              <p class="my-1">1</p>
                              <button
                                type="button"
                                class="v-btn v-btn--icon v-btn--outlined v-btn--round theme--light v-size--small primary--text"
                              >
                                <span class="v-btn__content"
                                  ><i
                                    aria-hidden="true"
                                    class="v-icon notranslate mdi mdi-minus theme--light"
                                  ></i
                                ></span>
                              </button>
                            </div>
                            <div
                              class="v-avatar me-4 rounded-0"
                              style="height: 64px; min-width: 64px; width: 64px"
                            >
                              <img
                                src="/_nuxt/img/1.d289046.png"
                                alt=""
                                class="br-10"
                              />
                            </div>
                            <div>
                              <h5
                                class="text-truncate d-inline-block mw-120 mb-0 f-600"
                              >
                                Mughal Masala Order Food Online With 50% Off
                              </h5>
                              <p class="text-12 mb-0">$530 x 1</p>
                              <h5 class="primary--text">500</h5>
                            </div>
                          </div>
                          <button
                            type="button"
                            class="v-btn v-btn--icon v-btn--round theme--light v-size--default"
                          >
                            <span class="v-btn__content"
                              ><i
                                aria-hidden="true"
                                class="v-icon notranslate mdi mdi-close theme--light"
                              ></i
                            ></span>
                          </button>
                        </div>
                      </div>
                      <div>
                        <div
                          class="d-flex align-center justify-space-between pa-3 mb-4"
                        >
                          <div class="d-flex align-center">
                            <div class="text-center me-3">
                              <button
                                type="button"
                                class="v-btn v-btn--icon v-btn--outlined v-btn--round theme--light v-size--small primary--text"
                              >
                                <span class="v-btn__content"
                                  ><i
                                    aria-hidden="true"
                                    class="v-icon notranslate mdi mdi-plus theme--light"
                                  ></i
                                ></span>
                              </button>
                              <p class="my-1">1</p>
                              <button
                                type="button"
                                class="v-btn v-btn--icon v-btn--outlined v-btn--round theme--light v-size--small primary--text"
                              >
                                <span class="v-btn__content"
                                  ><i
                                    aria-hidden="true"
                                    class="v-icon notranslate mdi mdi-minus theme--light"
                                  ></i
                                ></span>
                              </button>
                            </div>
                            <div
                              class="v-avatar me-4 rounded-0"
                              style="height: 64px; min-width: 64px; width: 64px"
                            >
                              <img
                                src="/_nuxt/img/2.2633985.png"
                                alt=""
                                class="br-10"
                              />
                            </div>
                            <div>
                              <h5
                                class="text-truncate d-inline-block mw-120 mb-0 f-600"
                              >
                                Mughal Masala Order Food Online With 50% Off
                              </h5>
                              <p class="text-12 mb-0">$530 x 1</p>
                              <h5 class="primary--text">500</h5>
                            </div>
                          </div>
                          <button
                            type="button"
                            class="v-btn v-btn--icon v-btn--round theme--light v-size--default"
                          >
                            <span class="v-btn__content"
                              ><i
                                aria-hidden="true"
                                class="v-icon notranslate mdi mdi-close theme--light"
                              ></i
                            ></span>
                          </button>
                        </div>
                      </div>
                      <div>
                        <div
                          class="d-flex align-center justify-space-between pa-3 mb-4"
                        >
                          <div class="d-flex align-center">
                            <div class="text-center me-3">
                              <button
                                type="button"
                                class="v-btn v-btn--icon v-btn--outlined v-btn--round theme--light v-size--small primary--text"
                              >
                                <span class="v-btn__content"
                                  ><i
                                    aria-hidden="true"
                                    class="v-icon notranslate mdi mdi-plus theme--light"
                                  ></i
                                ></span>
                              </button>
                              <p class="my-1">1</p>
                              <button
                                type="button"
                                class="v-btn v-btn--icon v-btn--outlined v-btn--round theme--light v-size--small primary--text"
                              >
                                <span class="v-btn__content"
                                  ><i
                                    aria-hidden="true"
                                    class="v-icon notranslate mdi mdi-minus theme--light"
                                  ></i
                                ></span>
                              </button>
                            </div>
                            <div
                              class="v-avatar me-4 rounded-0"
                              style="height: 64px; min-width: 64px; width: 64px"
                            >
                              <img
                                src="/_nuxt/img/3.4e7d7b9.png"
                                alt=""
                                class="br-10"
                              />
                            </div>
                            <div>
                              <h5
                                class="text-truncate d-inline-block mw-120 mb-0 f-600"
                              >
                                Mughal Masala Order Food Online With 50% Off
                              </h5>
                              <p class="text-12 mb-0">$530 x 1</p>
                              <h5 class="primary--text">500</h5>
                            </div>
                          </div>
                          <button
                            type="button"
                            class="v-btn v-btn--icon v-btn--round theme--light v-size--default"
                          >
                            <span class="v-btn__content"
                              ><i
                                aria-hidden="true"
                                class="v-icon notranslate mdi mdi-close theme--light"
                              ></i
                            ></span>
                          </button>
                        </div>
                      </div>
                    </div>
                  </div>
                </div>
                <div class="v-navigation-drawer__append">
                  <div class="pa-2" data-v-42ba0752="">
                    <button
                      type="button"
                      class="text-capitalize mb-3 v-btn v-btn--block v-btn--is-elevated v-btn--has-bg theme--light v-size--default primary"
                      data-v-42ba0752=""
                    >
                      <span class="v-btn__content"> Checkout Now ($ 220) </span>
                    </button>
                    <button
                      type="button"
                      class="text-cappitalise v-btn v-btn--block v-btn--outlined theme--light v-size--default primary--text"
                      data-v-42ba0752=""
                    >
                      <span class="v-btn__content"> View Cart </span>
                    </button>
                  </div>
                </div>
                <div class="v-navigation-drawer__border"></div>
              </aside>
              <aside
                class="v-navigation-drawer v-navigation-drawer--close v-navigation-drawer--fixed v-navigation-drawer--temporary theme--light"
                style="
                  height: 100%;
                  top: 0;
                  transform: translateX(-100%);
                  width: 320px;
                "
                data-v-42ba0752=""
                data-booted="true"
              >
                <div class="v-navigation-drawer__content">
                  <div data-v-42ba0752="">
                    <div
                      class="d-flex justify-space-between align-center ps-4 pe-3 mt-3"
                    >
                      <h5 class="m-0">Navbar</h5>
                      <button
                        type="button"
                        class="v-btn v-btn--icon v-btn--round theme--light v-size--default"
                        data-v-42ba0752=""
                      >
                        <span class="v-btn__content"
                          ><i
                            aria-hidden="true"
                            class="v-icon notranslate mdi mdi-close theme--light"
                            data-v-42ba0752=""
                          ></i
                        ></span>
                      </button>
                    </div>
                    <div class="navbar-scroll">
                      <div
                        role="list"
                        class="v-list v-sheet theme--light v-list--dense"
                      >
                        <div
                          class="v-list-group v-list-group--active v-list-group--no-action primary--text"
                        >
                          <div
                            tabindex="0"
                            aria-expanded="true"
                            role="button"
                            class="v-list-group__header v-list-item v-list-item--active v-list-item--link theme--light"
                          >
                            <div
                              class="v-list-item__icon v-list-group__header__prepend-icon"
                            >
                              <i
                                aria-hidden="true"
                                class="v-icon notranslate mdi mdi-view-dashboard-variant-outline theme--light"
                              ></i>
                            </div>
                            <div class="v-list-item__content">
                              <div class="v-list-item__title">Dashboards</div>
                            </div>
                            <div
                              class="v-list-item__icon v-list-group__header__append-icon"
                            >
                              <i
                                aria-hidden="true"
                                class="v-icon notranslate mdi mdi-chevron-down theme--light"
                              ></i>
                            </div>
                          </div>
                          <div class="v-list-group__items">
                            <a
                              href="/dashboard/Review"
                              tabindex="0"
                              role="listitem"
                              class="v-list-item v-list-item--link theme--light"
                              ><div class="v-list-item__content">
                                <div class="v-list-item__title">Review</div>
                              </div></a
                            ><a
                              href="/dashboard/Photos"
                              tabindex="0"
                              role="listitem"
                              class="v-list-item v-list-item--link theme--light"
                              ><div class="v-list-item__content">
                                <div class="v-list-item__title">Photos</div>
                              </div></a
                            ><a
                              href="/dashboard/OrderList"
                              tabindex="0"
                              role="listitem"
                              class="v-list-item v-list-item--link theme--light"
                              ><div class="v-list-item__content">
                                <div class="v-list-item__title">Order List</div>
                              </div></a
                            ><a
                              href="/dashboard/OrderHistory"
                              tabindex="0"
                              role="listitem"
                              class="v-list-item v-list-item--link theme--light"
                              ><div class="v-list-item__content">
                                <div class="v-list-item__title">
                                  Order History
                                </div>
                              </div></a
                            ><a
                              href="/dashboard/Followers"
                              tabindex="0"
                              role="listitem"
                              class="v-list-item v-list-item--link theme--light"
                              ><div class="v-list-item__content">
                                <div class="v-list-item__title">Followers</div>
                              </div></a
                            ><a
                              href="/dashboard/Bookmarks"
                              tabindex="0"
                              role="listitem"
                              class="v-list-item v-list-item--link theme--light"
                              ><div class="v-list-item__content">
                                <div class="v-list-item__title">Bookmarks</div>
                              </div></a
                            >
                          </div>
                        </div>
                        <div class="v-list-group v-list-group--no-action">
                          <div
                            tabindex="0"
                            aria-expanded="false"
                            role="button"
                            class="v-list-group__header v-list-item v-list-item--link theme--light"
                          >
                            <div
                              class="v-list-item__icon v-list-group__header__prepend-icon"
                            >
                              <i
                                aria-hidden="true"
                                class="v-icon notranslate mdi mdi-silverware-fork-knife theme--light"
                              ></i>
                            </div>
                            <div class="v-list-item__content">
                              <div class="v-list-item__title">Resturant</div>
                            </div>
                            <div
                              class="v-list-item__icon v-list-group__header__append-icon"
                            >
                              <i
                                aria-hidden="true"
                                class="v-icon notranslate mdi mdi-chevron-down theme--light"
                              ></i>
                            </div>
                          </div>
                          <!---->
                        </div>
                      </div>
                    </div>
                  </div>
                </div>
                <div class="v-navigation-drawer__border"></div>
              </aside>
            </div>
            <div id="navbar-hero">
              <div class="container">
                <div class="d-flex align-center mt-6 mb-10 navbar-container">
                  <a
                    href="/"
                    aria-current="page"
                    class="nuxt-link-exact-active nuxt-link-active"
                    ><div
                      class="v-avatar rounded-0"
                      style="height: 48px; min-width: 48px; width: 48px"
                    >
                      <img src="/_nuxt/img/logo.4a3964e.png" alt="" /></div
                  ></a>
                  <div class="spacer"></div>
                  <div role="dialog" class="v-dialog__container"><!----></div>
                  <button
                    type="button"
                    role="button"
                    aria-haspopup="true"
                    aria-expanded="false"
                    class="v-btn v-btn--text theme--dark v-size--default"
                  >
                    <span class="v-btn__content"
                      ><i
                        aria-hidden="true"
                        class="v-icon notranslate me-0 me-sm-3 mdi mdi-account-circle-outline theme--dark"
                      ></i>
                      <span class="d-none d-sm-block">Account</span></span
                    >
                  </button>
                  <button
                    type="button"
                    class="me-2 v-btn v-btn--text v-btn--tile theme--dark v-size--default"
                  >
                    <span class="v-btn__content"
                      ><i
                        aria-hidden="true"
                        class="v-icon notranslate mdi mdi-cart-outline theme--dark white--text"
                        style="font-size: 16px"
                      ></i
                      >(8)
                    </span>
                  </button>
                  <aside
                    class="v-navigation-drawer v-navigation-drawer--close v-navigation-drawer--fixed v-navigation-drawer--right v-navigation-drawer--temporary theme--light"
                    style="
                      height: 100%;
                      top: 0;
                      transform: translateX(100%);
                      width: 320px;
                    "
                    data-booted="true"
                  >
                    <div class="v-navigation-drawer__content">
                      <div>
                        <div
                          class="d-flex justify-space-between align-center ps-4 pe-3 mt-3 mb-2"
                        >
                          <div class="d-flex align-center">
                            <i
                              aria-hidden="true"
                              class="v-icon notranslate me-1 mdi mdi-shopping-outline theme--light"
                            ></i>
                            <h4 class="mb-0 grey--text text--darken-1 f-600">
                              1 Item
                            </h4>
                          </div>
                          <button
                            type="button"
                            class="v-btn v-btn--icon v-btn--round theme--light v-size--default"
                          >
                            <span class="v-btn__content"
                              ><i
                                aria-hidden="true"
                                class="v-icon notranslate mdi mdi-close theme--light primary--text"
                              ></i
                            ></span>
                          </button>
                        </div>
                        <hr
                          role="separator"
                          aria-orientation="horizontal"
                          class="v-divider theme--light"
                        />
                        <div class="navbar-scroll">
                          <div>
                            <div
                              class="d-flex align-center justify-space-between pa-3 mb-4"
                            >
                              <div class="d-flex align-center">
                                <div class="text-center me-3">
                                  <button
                                    type="button"
                                    class="v-btn v-btn--icon v-btn--outlined v-btn--round theme--light v-size--small primary--text"
                                  >
                                    <span class="v-btn__content"
                                      ><i
                                        aria-hidden="true"
                                        class="v-icon notranslate mdi mdi-plus theme--light"
                                      ></i
                                    ></span>
                                  </button>
                                  <p class="my-1">1</p>
                                  <button
                                    type="button"
                                    class="v-btn v-btn--icon v-btn--outlined v-btn--round theme--light v-size--small primary--text"
                                  >
                                    <span class="v-btn__content"
                                      ><i
                                        aria-hidden="true"
                                        class="v-icon notranslate mdi mdi-minus theme--light"
                                      ></i
                                    ></span>
                                  </button>
                                </div>
                                <div
                                  class="v-avatar me-4 rounded-0"
                                  style="
                                    height: 64px;
                                    min-width: 64px;
                                    width: 64px;
                                  "
                                >
                                  <img
                                    src="/_nuxt/img/1.d289046.png"
                                    alt=""
                                    class="br-10"
                                  />
                                </div>
                                <div>
                                  <h5
                                    class="text-truncate d-inline-block mw-120 mb-0 f-600"
                                  >
                                    Mughal Masala Order Food Online With 50% Off
                                  </h5>
                                  <p class="text-12 mb-0">$530 x 1</p>
                                  <h5 class="primary--text">500</h5>
                                </div>
                              </div>
                              <button
                                type="button"
                                class="v-btn v-btn--icon v-btn--round theme--light v-size--default"
                              >
                                <span class="v-btn__content"
                                  ><i
                                    aria-hidden="true"
                                    class="v-icon notranslate mdi mdi-close theme--light"
                                  ></i
                                ></span>
                              </button>
                            </div>
                          </div>
                          <div>
                            <div
                              class="d-flex align-center justify-space-between pa-3 mb-4"
                            >
                              <div class="d-flex align-center">
                                <div class="text-center me-3">
                                  <button
                                    type="button"
                                    class="v-btn v-btn--icon v-btn--outlined v-btn--round theme--light v-size--small primary--text"
                                  >
                                    <span class="v-btn__content"
                                      ><i
                                        aria-hidden="true"
                                        class="v-icon notranslate mdi mdi-plus theme--light"
                                      ></i
                                    ></span>
                                  </button>
                                  <p class="my-1">1</p>
                                  <button
                                    type="button"
                                    class="v-btn v-btn--icon v-btn--outlined v-btn--round theme--light v-size--small primary--text"
                                  >
                                    <span class="v-btn__content"
                                      ><i
                                        aria-hidden="true"
                                        class="v-icon notranslate mdi mdi-minus theme--light"
                                      ></i
                                    ></span>
                                  </button>
                                </div>
                                <div
                                  class="v-avatar me-4 rounded-0"
                                  style="
                                    height: 64px;
                                    min-width: 64px;
                                    width: 64px;
                                  "
                                >
                                  <img
                                    src="/_nuxt/img/2.2633985.png"
                                    alt=""
                                    class="br-10"
                                  />
                                </div>
                                <div>
                                  <h5
                                    class="text-truncate d-inline-block mw-120 mb-0 f-600"
                                  >
                                    Mughal Masala Order Food Online With 50% Off
                                  </h5>
                                  <p class="text-12 mb-0">$530 x 1</p>
                                  <h5 class="primary--text">500</h5>
                                </div>
                              </div>
                              <button
                                type="button"
                                class="v-btn v-btn--icon v-btn--round theme--light v-size--default"
                              >
                                <span class="v-btn__content"
                                  ><i
                                    aria-hidden="true"
                                    class="v-icon notranslate mdi mdi-close theme--light"
                                  ></i
                                ></span>
                              </button>
                            </div>
                          </div>
                          <div>
                            <div
                              class="d-flex align-center justify-space-between pa-3 mb-4"
                            >
                              <div class="d-flex align-center">
                                <div class="text-center me-3">
                                  <button
                                    type="button"
                                    class="v-btn v-btn--icon v-btn--outlined v-btn--round theme--light v-size--small primary--text"
                                  >
                                    <span class="v-btn__content"
                                      ><i
                                        aria-hidden="true"
                                        class="v-icon notranslate mdi mdi-plus theme--light"
                                      ></i
                                    ></span>
                                  </button>
                                  <p class="my-1">1</p>
                                  <button
                                    type="button"
                                    class="v-btn v-btn--icon v-btn--outlined v-btn--round theme--light v-size--small primary--text"
                                  >
                                    <span class="v-btn__content"
                                      ><i
                                        aria-hidden="true"
                                        class="v-icon notranslate mdi mdi-minus theme--light"
                                      ></i
                                    ></span>
                                  </button>
                                </div>
                                <div
                                  class="v-avatar me-4 rounded-0"
                                  style="
                                    height: 64px;
                                    min-width: 64px;
                                    width: 64px;
                                  "
                                >
                                  <img
                                    src="/_nuxt/img/3.4e7d7b9.png"
                                    alt=""
                                    class="br-10"
                                  />
                                </div>
                                <div>
                                  <h5
                                    class="text-truncate d-inline-block mw-120 mb-0 f-600"
                                  >
                                    Mughal Masala Order Food Online With 50% Off
                                  </h5>
                                  <p class="text-12 mb-0">$530 x 1</p>
                                  <h5 class="primary--text">500</h5>
                                </div>
                              </div>
                              <button
                                type="button"
                                class="v-btn v-btn--icon v-btn--round theme--light v-size--default"
                              >
                                <span class="v-btn__content"
                                  ><i
                                    aria-hidden="true"
                                    class="v-icon notranslate mdi mdi-close theme--light"
                                  ></i
                                ></span>
                              </button>
                            </div>
                          </div>
                        </div>
                      </div>
                    </div>
                    <div class="v-navigation-drawer__append">
                      <div class="pa-2">
                        <button
                          type="button"
                          class="text-capitalize mb-3 v-btn v-btn--block v-btn--is-elevated v-btn--has-bg theme--light v-size--default primary"
                        >
                          <span class="v-btn__content">
                            Checkout Now ($ 220)
                          </span>
                        </button>
                        <button
                          type="button"
                          class="text-cappitalise v-btn v-btn--block v-btn--outlined theme--light v-size--default primary--text"
                        >
                          <span class="v-btn__content"> View Cart </span>
                        </button>
                      </div>
                    </div>
                    <div class="v-navigation-drawer__border"></div>
                  </aside>
                  <button
                    type="button"
                    tile=""
                    dark=""
                    class="v-app-bar__nav-icon rounded v-btn v-btn--icon v-btn--round v-btn--tile theme--dark v-size--default"
                  >
                    <span class="v-btn__content"
                      ><i
                        aria-hidden="true"
                        class="v-icon notranslate mdi mdi-menu theme--dark"
                      ></i
                    ></span>
                  </button>
                  <aside
                    class="v-navigation-drawer v-navigation-drawer--close v-navigation-drawer--fixed v-navigation-drawer--temporary theme--light"
                    style="
                      height: 100%;
                      top: 0;
                      transform: translateX(-100%);
                      width: 320px;
                    "
                    data-booted="true"
                  >
                    <div class="v-navigation-drawer__content">
                      <div>
                        <div
                          class="d-flex justify-space-between align-center ps-4 pe-3 mt-3"
                        >
                          <h5 class="m-0">Navbar</h5>
                          <button
                            type="button"
                            class="v-btn v-btn--icon v-btn--round theme--light v-size--default"
                          >
                            <span class="v-btn__content"
                              ><i
                                aria-hidden="true"
                                class="v-icon notranslate mdi mdi-close theme--light"
                              ></i
                            ></span>
                          </button>
                        </div>
                        <div class="navbar-scroll">
                          <div
                            role="list"
                            class="v-list v-sheet theme--light v-list--dense"
                          >
                            <div
                              class="v-list-group v-list-group--active v-list-group--no-action primary--text"
                            >
                              <div
                                tabindex="0"
                                aria-expanded="true"
                                role="button"
                                class="v-list-group__header v-list-item v-list-item--active v-list-item--link theme--light"
                              >
                                <div
                                  class="v-list-item__icon v-list-group__header__prepend-icon"
                                >
                                  <i
                                    aria-hidden="true"
                                    class="v-icon notranslate mdi mdi-view-dashboard-variant-outline theme--light"
                                  ></i>
                                </div>
                                <div class="v-list-item__content">
                                  <div class="v-list-item__title">
                                    Dashboards
                                  </div>
                                </div>
                                <div
                                  class="v-list-item__icon v-list-group__header__append-icon"
                                >
                                  <i
                                    aria-hidden="true"
                                    class="v-icon notranslate mdi mdi-chevron-down theme--light"
                                  ></i>
                                </div>
                              </div>
                              <div class="v-list-group__items">
                                <a
                                  href="/dashboard/Review"
                                  tabindex="0"
                                  role="listitem"
                                  class="v-list-item v-list-item--link theme--light"
                                  ><div class="v-list-item__content">
                                    <div class="v-list-item__title">Review</div>
                                  </div></a
                                ><a
                                  href="/dashboard/Photos"
                                  tabindex="0"
                                  role="listitem"
                                  class="v-list-item v-list-item--link theme--light"
                                  ><div class="v-list-item__content">
                                    <div class="v-list-item__title">Photos</div>
                                  </div></a
                                ><a
                                  href="/dashboard/OrderList"
                                  tabindex="0"
                                  role="listitem"
                                  class="v-list-item v-list-item--link theme--light"
                                  ><div class="v-list-item__content">
                                    <div class="v-list-item__title">
                                      Order List
                                    </div>
                                  </div></a
                                ><a
                                  href="/dashboard/OrderHistory"
                                  tabindex="0"
                                  role="listitem"
                                  class="v-list-item v-list-item--link theme--light"
                                  ><div class="v-list-item__content">
                                    <div class="v-list-item__title">
                                      Order History
                                    </div>
                                  </div></a
                                ><a
                                  href="/dashboard/Followers"
                                  tabindex="0"
                                  role="listitem"
                                  class="v-list-item v-list-item--link theme--light"
                                  ><div class="v-list-item__content">
                                    <div class="v-list-item__title">
                                      Followers
                                    </div>
                                  </div></a
                                ><a
                                  href="/dashboard/Bookmarks"
                                  tabindex="0"
                                  role="listitem"
                                  class="v-list-item v-list-item--link theme--light"
                                  ><div class="v-list-item__content">
                                    <div class="v-list-item__title">
                                      Bookmarks
                                    </div>
                                  </div></a
                                >
                              </div>
                            </div>
                            <div class="v-list-group v-list-group--no-action">
                              <div
                                tabindex="0"
                                aria-expanded="false"
                                role="button"
                                class="v-list-group__header v-list-item v-list-item--link theme--light"
                              >
                                <div
                                  class="v-list-item__icon v-list-group__header__prepend-icon"
                                >
                                  <i
                                    aria-hidden="true"
                                    class="v-icon notranslate mdi mdi-silverware-fork-knife theme--light"
                                  ></i>
                                </div>
                                <div class="v-list-item__content">
                                  <div class="v-list-item__title">
                                    Resturant
                                  </div>
                                </div>
                                <div
                                  class="v-list-item__icon v-list-group__header__append-icon"
                                >
                                  <i
                                    aria-hidden="true"
                                    class="v-icon notranslate mdi mdi-chevron-down theme--light"
                                  ></i>
                                </div>
                              </div>
                              <!---->
                            </div>
                          </div>
                        </div>
                      </div>
                    </div>
                    <div class="v-navigation-drawer__border"></div>
                  </aside>
                </div>
              </div>
            </div>
            <div class="container">
              <div class="mt-15">
                <div class="row">
                  <div class="mx-auto col-xl-5 col-12">
                    <h1
                      class="white--text text-center display-2 font-weight-regular mb-4"
                    >
                      Discover the best food &amp; drinks in
                      <span class="font-weight-bold">New York</span>
                    </h1>
                    <h4
                      class="text-h6 white--text text-center font-weight-light mb-5"
                    >
                      The meals you love, delivered with care
                    </h4>
                  </div>
                </div>
                <div class="row">
                  <div class="mx-auto mb-15 col-md-12 col-lg-7 col-12">
                    <div class="form-location d-flex white rounded flex-wrap">
                      <div class="d-flex align-center ps-5">
                        <i
                          aria-hidden="true"
                          class="v-icon notranslate v-icon--left mdi mdi-map-marker theme--light"
                        ></i>
                        <span class="grey--text text--darken-1 me-10"
                          >New York</span
                        >
                      </div>
                      <button
                        type="button"
                        class="text-capitalize rounded-0 btn-location v-btn v-btn--text theme--light v-size--x-large"
                      >
                        <span class="v-btn__content"
                          ><i
                            aria-hidden="true"
                            class="v-icon notranslate v-icon--left mdi mdi-crosshairs-gps theme--light"
                          ></i>
                          <span
                            class="grey--text text--darken-4 font-weight-regular"
                            >Locate me</span
                          ></span
                        >
                      </button>
                      <input
                        placeholder="Search for restaurant "
                        class="white flex-1 ps-5"
                      />
                      <a
                        href="/resturant/ResturantTwoColumn"
                        class="rounded-l-0 text-capitalize v-btn v-btn--is-elevated v-btn--has-bg v-btn--router theme--light v-size--x-large primary"
                        ><span class="v-btn__content"> Search </span></a
                      >
                    </div>
                  </div>
                </div>
              </div>
            </div>
          </div>
          <div class="content">
            <div class="bg-grey-light">
              <div class="container py-15">
                <div class="row">
                  <div
                    data-aos="fade-up"
                    class="col-sm-6 col-md-4 col-lg-3 col-12"
                  >
                    <a href="/resturant/FoodMenu" class="text-decoration-none"
                      ><div
                        class="br-10 bg-transparent o-hidden v-card v-sheet v-sheet--outlined theme--light elevation-0"
                      >
                        <div>
                          <div class="v-image v-responsive theme--light">
                            <div
                              class="v-responsive__sizer"
                              style="padding-bottom: 66.5625%"
                            ></div>
                            <div
                              class="v-image__image v-image__image--contain"
                              style="
                                background-image: url('https://foodhub-nuxt.vercel.app/_nuxt/img/15.15c95d2.jpg');
                                background-position: center center;
                              "
                            ></div>
                            <div
                              class="v-responsive__content"
                              style="width: 640px"
                            ></div>
                          </div>
                        </div>
                        <div class="pa-4 text-center">
                          <h3 class="me-3">Order Food Online</h3>
                        </div>
                      </div></a
                    >
                  </div>
                  <div
                    data-aos="fade-up"
                    class="col-sm-6 col-md-4 col-lg-3 col-12"
                  >
                    <a href="/resturant/FoodMenu" class="text-decoration-none"
                      ><div
                        class="br-10 bg-transparent o-hidden v-card v-sheet v-sheet--outlined theme--light elevation-0"
                      >
                        <div>
                          <div class="v-image v-responsive theme--light">
                            <div
                              class="v-responsive__sizer"
                              style="padding-bottom: 66.5625%"
                            ></div>
                            <div
                              class="v-image__image v-image__image--contain"
                              style="
                                background-image: url('https://foodhub-nuxt.vercel.app/_nuxt/img/16.bbc24cb.jpg');
                                background-position: center center;
                              "
                            ></div>
                            <div
                              class="v-responsive__content"
                              style="width: 640px"
                            ></div>
                          </div>
                        </div>
                        <div class="pa-4 text-center">
                          <h3 class="me-3">Go Out For Meal</h3>
                        </div>
                      </div></a
                    >
                  </div>
                  <div
                    data-aos="fade-up"
                    class="col-sm-6 col-md-4 col-lg-3 col-12"
                  >
                    <a href="/resturant/FoodMenu" class="text-decoration-none"
                      ><div
                        class="br-10 bg-transparent o-hidden v-card v-sheet v-sheet--outlined theme--light elevation-0"
                      >
                        <div>
                          <div class="v-image v-responsive theme--light">
                            <div
                              class="v-responsive__sizer"
                              style="padding-bottom: 66.5625%"
                            ></div>
                            <div
                              class="v-image__image v-image__image--contain"
                              style="
                                background-image: url('https://foodhub-nuxt.vercel.app/_nuxt/img/17.3634737.jpg');
                                background-position: center center;
                              "
                            ></div>
                            <div
                              class="v-responsive__content"
                              style="width: 640px"
                            ></div>
                          </div>
                        </div>
                        <div class="pa-4 text-center">
                          <h3 class="me-3">Nightlife &amp; Clubs</h3>
                        </div>
                      </div></a
                    >
                  </div>
                  <div
                    data-aos="fade-up"
                    class="col-sm-6 col-md-4 col-lg-3 col-12"
                  >
                    <a href="/resturant/FoodMenu" class="text-decoration-none"
                      ><div
                        class="br-10 bg-transparent o-hidden v-card v-sheet v-sheet--outlined theme--light elevation-0"
                      >
                        <div>
                          <div class="v-image v-responsive theme--light">
                            <div
                              class="v-responsive__sizer"
                              style="padding-bottom: 66.5625%"
                            ></div>
                            <div
                              class="v-image__image v-image__image--contain"
                              style="
                                background-image: url('https://foodhub-nuxt.vercel.app/_nuxt/img/18.2a12c1e.jpg');
                                background-position: center center;
                              "
                            ></div>
                            <div
                              class="v-responsive__content"
                              style="width: 640px"
                            ></div>
                          </div>
                        </div>
                        <div class="pa-4 text-center">
                          <h3 class="me-3">Pro Membership</h3>
                        </div>
                      </div></a
                    >
                  </div>
                </div>
              </div>
            </div>
            <div>
              <div class="container py-15">
                <div class="row">
                  <div class="col col-12">
                    <div
                      class="d-flex justify-space-between align-end flex-wrap"
                    >
                      <div>
                        <h2>Collections</h2>
                        <h6
                          class="grey--text grey--lighten-3 font-weight-regular"
                        >
                          Explore curated lists of top restaurants, cafes, pubs,
                          and bars in New York, based on trends
                        </h6>
                      </div>
                      <div>
                        <a
                          href="/"
                          aria-current="page"
                          class="text-decoration-none nuxt-link-exact-active nuxt-link-active"
                          >View all collections</a
                        >
                      </div>
                    </div>
                  </div>
                  <div class="col-sm-6 col-md-4 col-lg-3 col-12">
                    <a
                      href="/resturant/SearchResturant"
                      class="text-decoration-none"
                      ><div class="br-10 v-card v-sheet theme--light">
                        <div
                          class="v-image v-responsive p-relative theme--light"
                        >
                          <div
                            class="v-responsive__sizer"
                            style="padding-bottom: 114.695%"
                          ></div>
                          <div
                            class="v-image__image v-image__image--cover"
                            style="
                              background-image: linear-gradient(
                                  rgba(0, 0, 0, 0),
                                  rgba(0, 0, 0, 0),
                                  rgba(0, 0, 0, 0),
                                  rgb(0, 0, 0)
                                ),
                                url('https://foodhub-nuxt.vercel.app/_nuxt/img/5.8a5927f.png');
                              background-position: center center;
                            "
                          ></div>
                          <div
                            class="v-responsive__content"
                            style="width: 279px"
                          >
                            <div class="p-absolute bottom-0 pa-5">
                              <h5 class="white--text">Most Searched of 2020</h5>
                              <div class="d-flex">
                                <p class="text-sm white--text mb-0">
                                  30 Places
                                </p>
                                <i
                                  aria-hidden="true"
                                  class="v-icon notranslate mdi mdi-chevron-right theme--light white--text"
                                  style="font-size: 16px"
                                ></i>
                              </div>
                            </div>
                          </div>
                        </div></div
                    ></a>
                  </div>
                  <div class="col-sm-6 col-md-4 col-lg-3 col-12">
                    <a
                      href="/resturant/SearchResturant"
                      class="text-decoration-none"
                      ><div class="br-10 v-card v-sheet theme--light">
                        <div
                          class="v-image v-responsive p-relative theme--light"
                        >
                          <div
                            class="v-responsive__sizer"
                            style="padding-bottom: 114.695%"
                          ></div>
                          <div
                            class="v-image__image v-image__image--cover"
                            style="
                              background-image: linear-gradient(
                                  rgba(0, 0, 0, 0),
                                  rgba(0, 0, 0, 0),
                                  rgba(0, 0, 0, 0),
                                  rgb(0, 0, 0)
                                ),
                                url('https://foodhub-nuxt.vercel.app/_nuxt/img/6.729f74b.png');
                              background-position: center center;
                            "
                          ></div>
                          <div
                            class="v-responsive__content"
                            style="width: 279px"
                          >
                            <div class="p-absolute bottom-0 pa-5">
                              <h5 class="white--text">Best Openings of 2020</h5>
                              <div class="d-flex">
                                <p class="text-sm white--text mb-0">
                                  30 Places
                                </p>
                                <i
                                  aria-hidden="true"
                                  class="v-icon notranslate mdi mdi-chevron-right theme--light white--text"
                                  style="font-size: 16px"
                                ></i>
                              </div>
                            </div>
                          </div>
                        </div></div
                    ></a>
                  </div>
                  <div class="col-sm-6 col-md-4 col-lg-3 col-12">
                    <a
                      href="/resturant/SearchResturant"
                      class="text-decoration-none"
                      ><div class="br-10 v-card v-sheet theme--light">
                        <div
                          class="v-image v-responsive p-relative theme--light"
                        >
                          <div
                            class="v-responsive__sizer"
                            style="padding-bottom: 114.695%"
                          ></div>
                          <div
                            class="v-image__image v-image__image--cover"
                            style="
                              background-image: linear-gradient(
                                  rgba(0, 0, 0, 0),
                                  rgba(0, 0, 0, 0),
                                  rgba(0, 0, 0, 0),
                                  rgb(0, 0, 0)
                                ),
                                url('https://foodhub-nuxt.vercel.app/_nuxt/img/7.ea86fb7.png');
                              background-position: center center;
                            "
                          ></div>
                          <div
                            class="v-responsive__content"
                            style="width: 279px"
                          >
                            <div class="p-absolute bottom-0 pa-5">
                              <h5 class="white--text">Trending This Week</h5>
                              <div class="d-flex">
                                <p class="text-sm white--text mb-0">
                                  30 Places
                                </p>
                                <i
                                  aria-hidden="true"
                                  class="v-icon notranslate mdi mdi-chevron-right theme--light white--text"
                                  style="font-size: 16px"
                                ></i>
                              </div>
                            </div>
                          </div>
                        </div></div
                    ></a>
                  </div>
                  <div class="col-sm-6 col-md-4 col-lg-3 col-12">
                    <a
                      href="/resturant/SearchResturant"
                      class="text-decoration-none"
                      ><div class="br-10 v-card v-sheet theme--light">
                        <div
                          class="v-image v-responsive p-relative theme--light"
                        >
                          <div
                            class="v-responsive__sizer"
                            style="padding-bottom: 114.695%"
                          ></div>
                          <div
                            class="v-image__image v-image__image--cover"
                            style="
                              background-image: linear-gradient(
                                  rgba(0, 0, 0, 0),
                                  rgba(0, 0, 0, 0),
                                  rgba(0, 0, 0, 0),
                                  rgb(0, 0, 0)
                                ),
                                url('https://foodhub-nuxt.vercel.app/_nuxt/img/8.d53c60b.png');
                              background-position: center center;
                            "
                          ></div>
                          <div
                            class="v-responsive__content"
                            style="width: 279px"
                          >
                            <div class="p-absolute bottom-0 pa-5">
                              <h5 class="white--text">Best Of New York</h5>
                              <div class="d-flex">
                                <p class="text-sm white--text mb-0">
                                  30 Places
                                </p>
                                <i
                                  aria-hidden="true"
                                  class="v-icon notranslate mdi mdi-chevron-right theme--light white--text"
                                  style="font-size: 16px"
                                ></i>
                              </div>
                            </div>
                          </div>
                        </div></div
                    ></a>
                  </div>
                </div>
              </div>
            </div>
            <div>
              <div class="container py-15">
                <div class="row">
                  <div class="col col-12"><h2>Popular Near You</h2></div>
                  <div class="col-sm-6 col-md-4 col-lg-3 col-12">
                    <a href="/resturant/FoodMenu" class="text-decoration-none"
                      ><div
                        class="br-10 o-hidden v-card v-sheet v-sheet--outlined theme--light elevation-0"
                      >
                        <div class="position-relative">
                          <div
                            class="v-image v-responsive btr-10 theme--light"
                            style="width: 100%"
                          >
                            <div
                              class="v-responsive__sizer"
                              style="padding-bottom: 66.5625%"
                            ></div>
                            <div
                              class="v-image__image v-image__image--cover"
                              style="
                                background-image: url('https://foodhub-nuxt.vercel.app/_nuxt/img/15.15c95d2.jpg');
                                background-position: center center;
                              "
                            ></div>
                            <div
                              class="v-responsive__content"
                              style="width: 640px"
                            ></div>
                          </div>
                          <div>
                            <span
                              draggable="false"
                              flat=""
                              class="p-absolute top-0 rounded-r-xl rounded-l-0 mt-3 v-chip v-chip--label theme--light v-size--default primary"
                              ><span class="v-chip__content"
                                >Flat 30% Off</span
                              ></span
                            >
                          </div>
                        </div>
                        <div
                          class="pa-4 d-flex justify-space-between align-center"
                        >
                          <span
                            class="d-inline-block text-truncate me-3 f-600 text-18 card-title"
                            >Starbucks</span
                          >
                          <div class="d-flex align-center card-rating">
                            <i
                              aria-hidden="true"
                              class="v-icon notranslate me-1 mdi mdi-star theme--light yellow--text text--darken-2"
                              style="font-size: 16px"
                            ></i>
                            <div>
                              <span class="font-weight-bold text-14">4.5</span>
                              <span class="grey--text text--darken-1 text-14"
                                >/5</span
                              >
                            </div>
                          </div>
                        </div>
                        <p class="px-4 grey--text text--darken-1">
                          <span class="primary--text f-600 me-1">$20</span> •
                          Cofee, set menu • 15 - 20 min
                        </p>
                      </div></a
                    >
                  </div>
                  <div class="col-sm-6 col-md-4 col-lg-3 col-12">
                    <a href="/resturant/FoodMenu" class="text-decoration-none"
                      ></a
                    >
                  </div>
                  <div class="col-sm-6 col-md-4 col-lg-3 col-12">
                    <a href="/resturant/FoodMenu" class="text-decoration-none"
                      ><div
                        class="br-10 o-hidden v-card v-sheet v-sheet--outlined theme--light elevation-0"
                      >
                        <div class="position-relative">
                          <div
                            class="v-image v-responsive btr-10 theme--light"
                            style="width: 100%"
                          >
                            <div
                              class="v-responsive__sizer"
                              style="padding-bottom: 66.5625%"
                            ></div>
                            <div
                              class="v-image__image v-image__image--cover"
                              style="
                                background-image: url('https://foodhub-nuxt.vercel.app/_nuxt/img/17.3634737.jpg');
                                background-position: center center;
                              "
                            ></div>
                            <div
                              class="v-responsive__content"
                              style="width: 640px"
                            ></div>
                          </div>
                          <div></div>
                        </div>
                        <div
                          class="pa-4 d-flex justify-space-between align-center"
                        >
                          <span
                            class="d-inline-block text-truncate me-3 f-600 text-18 card-title"
                            >Woondal</span
                          >
                          <div class="d-flex align-center card-rating">
                            <i
                              aria-hidden="true"
                              class="v-icon notranslate me-1 mdi mdi-star theme--light yellow--text text--darken-2"
                              style="font-size: 16px"
                            ></i>
                            <div>
                              <span class="font-weight-bold text-14">4.5</span>
                              <span class="grey--text text--darken-1 text-14"
                                >/5</span
                              >
                            </div>
                          </div>
                        </div>
                        <p class="px-4 grey--text text--darken-1">
                          <span class="primary--text f-600 me-1">$20</span> •
                          Cofee, set menu • 15 - 20 min
                        </p>
                      </div></a
                    >
                  </div>
                  <div class="col-sm-6 col-md-4 col-lg-3 col-12">
                    <a href="/resturant/FoodMenu" class="text-decoration-none"
                      ><div
                        class="br-10 o-hidden v-card v-sheet v-sheet--outlined theme--light elevation-0"
                      >
                        <div class="position-relative">
                          <div
                            class="v-image v-responsive btr-10 theme--light"
                            style="width: 100%"
                          >
                            <div
                              class="v-responsive__sizer"
                              style="padding-bottom: 66.5625%"
                            ></div>
                            <div
                              class="v-image__image v-image__image--cover"
                              style="
                                background-image: url('https://foodhub-nuxt.vercel.app/_nuxt/img/18.2a12c1e.jpg');
                                background-position: center center;
                              "
                            ></div>
                            <div
                              class="v-responsive__content"
                              style="width: 640px"
                            ></div>
                          </div>
                          <div>
                            <span
                              draggable="false"
                              flat=""
                              class="p-absolute top-0 rounded-r-xl rounded-l-0 mt-3 v-chip v-chip--label theme--light v-size--default primary"
                              ><span class="v-chip__content"
                                >Flat 30% Off</span
                              ></span
                            >
                          </div>
                        </div>
                        <div
                          class="pa-4 d-flex justify-space-between align-center"
                        >
                          <span
                            class="d-inline-block text-truncate me-3 f-600 text-18 card-title"
                            >Red Chillies</span
                          >
                          <div class="d-flex align-center card-rating">
                            <i
                              aria-hidden="true"
                              class="v-icon notranslate me-1 mdi mdi-star theme--light yellow--text text--darken-2"
                              style="font-size: 16px"
                            ></i>
                            <div>
                              <span class="font-weight-bold text-14">4.5</span>
                              <span class="grey--text text--darken-1 text-14"
                                >/5</span
                              >
                            </div>
                          </div>
                        </div>
                        <p class="px-4 grey--text text--darken-1">
                          <span class="primary--text f-600 me-1">$20</span> •
                          Cofee, set menu • 15 - 20 min
                        </p>
                      </div></a
                    >
                  </div>
                  <div class="col-sm-6 col-md-4 col-lg-3 col-12">
                    <a href="/resturant/FoodMenu" class="text-decoration-none"
                      ><div
                        class="br-10 o-hidden v-card v-sheet v-sheet--outlined theme--light elevation-0"
                      >
                        <div class="position-relative">
                          <div
                            class="v-image v-responsive btr-10 theme--light"
                            style="width: 100%"
                          >
                            <div
                              class="v-responsive__sizer"
                              style="padding-bottom: 66.5625%"
                            ></div>
                            <div
                              class="v-image__image v-image__image--cover"
                              style="
                                background-image: url('https://foodhub-nuxt.vercel.app/_nuxt/img/19.a1e7280.jpg');
                                background-position: center center;
                              "
                            ></div>
                            <div
                              class="v-responsive__content"
                              style="width: 640px"
                            ></div>
                          </div>
                          <div>
                            <span
                              draggable="false"
                              flat=""
                              class="p-absolute top-0 rounded-r-xl rounded-l-0 mt-3 v-chip v-chip--label theme--light v-size--default primary"
                              ><span class="v-chip__content"
                                >Flat 30% Off</span
                              ></span
                            >
                          </div>
                        </div>
                        <div
                          class="pa-4 d-flex justify-space-between align-center"
                        >
                          <span
                            class="d-inline-block text-truncate me-3 f-600 text-18 card-title"
                            >Starbucks</span
                          >
                          <div class="d-flex align-center card-rating">
                            <i
                              aria-hidden="true"
                              class="v-icon notranslate me-1 mdi mdi-star theme--light yellow--text text--darken-2"
                              style="font-size: 16px"
                            ></i>
                            <div>
                              <span class="font-weight-bold text-14">4.5</span>
                              <span class="grey--text text--darken-1 text-14"
                                >/5</span
                              >
                            </div>
                          </div>
                        </div>
                        <p class="px-4 grey--text text--darken-1">
                          <span class="primary--text f-600 me-1">$20</span> •
                          Cofee, set menu • 15 - 20 min
                        </p>
                      </div></a
                    >
                  </div>
                  <div class="col-sm-6 col-md-4 col-lg-3 col-12">
                    <a href="/resturant/FoodMenu" class="text-decoration-none"
                      ><div
                        class="br-10 o-hidden v-card v-sheet v-sheet--outlined theme--light elevation-0"
                      >
                        <div class="position-relative">
                          <div
                            class="v-image v-responsive btr-10 theme--light"
                            style="width: 100%"
                          >
                            <div
                              class="v-responsive__sizer"
                              style="padding-bottom: 66.5625%"
                            ></div>
                            <div
                              class="v-image__image v-image__image--cover"
                              style="
                                background-image: url('https://foodhub-nuxt.vercel.app/_nuxt/img/20.ce4b89f.jpg');
                                background-position: center center;
                              "
                            ></div>
                            <div
                              class="v-responsive__content"
                              style="width: 640px"
                            ></div>
                          </div>
                          <div></div>
                        </div>
                        <div
                          class="pa-4 d-flex justify-space-between align-center"
                        >
                          <span
                            class="d-inline-block text-truncate me-3 f-600 text-18 card-title"
                            >Mughal Masala</span
                          >
                          <div class="d-flex align-center card-rating">
                            <i
                              aria-hidden="true"
                              class="v-icon notranslate me-1 mdi mdi-star theme--light yellow--text text--darken-2"
                              style="font-size: 16px"
                            ></i>
                            <div>
                              <span class="font-weight-bold text-14">4.5</span>
                              <span class="grey--text text--darken-1 text-14"
                                >/5</span
                              >
                            </div>
                          </div>
                        </div>
                        <p class="px-4 grey--text text--darken-1">
                          <span class="primary--text f-600 me-1">$20</span> •
                          Cofee, set menu • 15 - 20 min
                        </p>
                      </div></a
                    >
                  </div>
                  <div class="col-sm-6 col-md-4 col-lg-3 col-12">
                    <a href="/resturant/FoodMenu" class="text-decoration-none"
                      ><div
                        class="br-10 o-hidden v-card v-sheet v-sheet--outlined theme--light elevation-0"
                      >
                        <div class="position-relative">
                          <div
                            class="v-image v-responsive btr-10 theme--light"
                            style="width: 100%"
                          >
                            <div
                              class="v-responsive__sizer"
                              style="padding-bottom: 66.5625%"
                            ></div>
                            <div
                              class="v-image__image v-image__image--cover"
                              style="
                                background-image: url('https://foodhub-nuxt.vercel.app/_nuxt/img/21.eee29b5.jpg');
                                background-position: center center;
                              "
                            ></div>
                            <div
                              class="v-responsive__content"
                              style="width: 640px"
                            ></div>
                          </div>
                          <div></div>
                        </div>
                        <div
                          class="pa-4 d-flex justify-space-between align-center"
                        >
                          <span
                            class="d-inline-block text-truncate me-3 f-600 text-18 card-title"
                            >Woondal</span
                          >
                          <div class="d-flex align-center card-rating">
                            <i
                              aria-hidden="true"
                              class="v-icon notranslate me-1 mdi mdi-star theme--light yellow--text text--darken-2"
                              style="font-size: 16px"
                            ></i>
                            <div>
                              <span class="font-weight-bold text-14">4.5</span>
                              <span class="grey--text text--darken-1 text-14"
                                >/5</span
                              >
                            </div>
                          </div>
                        </div>
                        <p class="px-4 grey--text text--darken-1">
                          <span class="primary--text f-600 me-1">$20</span> •
                          Cofee, set menu • 15 - 20 min
                        </p>
                      </div></a
                    >
                  </div>
                  <div class="col-sm-6 col-md-4 col-lg-3 col-12">
                    <a href="/resturant/FoodMenu" class="text-decoration-none"
                      ><div
                        class="br-10 o-hidden v-card v-sheet v-sheet--outlined theme--light elevation-0"
                      >
                        <div class="position-relative">
                          <div
                            class="v-image v-responsive btr-10 theme--light"
                            style="width: 100%"
                          >
                            <div
                              class="v-image__image v-image__image--preload v-image__image--cover"
                              style="background-position: center center"
                            ></div>
                            <div class="v-responsive__content"></div>
                          </div>
                          <div>
                            <span
                              draggable="false"
                              flat=""
                              class="p-absolute top-0 rounded-r-xl rounded-l-0 mt-3 v-chip v-chip--label theme--light v-size--default primary"
                              ><span class="v-chip__content"
                                >Flat 30% Off</span
                              ></span
                            >
                          </div>
                        </div>
                        <div
                          class="pa-4 d-flex justify-space-between align-center"
                        >
                          <span
                            class="d-inline-block text-truncate me-3 f-600 text-18 card-title"
                            >Red Chillies</span
                          >
                          <div class="d-flex align-center card-rating">
                            <i
                              aria-hidden="true"
                              class="v-icon notranslate me-1 mdi mdi-star theme--light yellow--text text--darken-2"
                              style="font-size: 16px"
                            ></i>
                            <div>
                              <span class="font-weight-bold text-14">4.5</span>
                              <span class="grey--text text--darken-1 text-14"
                                >/5</span
                              >
                            </div>
                          </div>
                        </div>
                        <p class="px-4 grey--text text--darken-1">
                          <span class="primary--text f-600 me-1">$20</span> •
                          Cofee, set menu • 15 - 20 min
                        </p>
                      </div></a
                    >
                  </div>
                </div>
              </div>
            </div>

            
          </div>
          <button
            type="button"
            class="v-btn v-btn--bottom v-btn--is-elevated v-btn--fab v-btn--fixed v-btn--has-bg v-btn--right v-btn--round theme--dark v-size--small primary d-none"
          >
            <span class="v-btn__content"
              ><i
                aria-hidden="true"
                class="v-icon notranslate mdi mdi-chevron-up theme--dark"
              ></i
            ></span>
          </button>
        </div>
      </div>
    </div>

    <v-navigation-drawer
      app
      class="float-left"
      v-model="drawermob"
      absolute
      temporary
      dark
    >
      <v-list>
        <v-list-item>
          <v-list-item-content>
            <v-list-item-title class="text-h6"> Application </v-list-item-title>
            <v-list-item-subtitle> subtext </v-list-item-subtitle>
          </v-list-item-content>
        </v-list-item>
      </v-list>

      <v-divider></v-divider>

      <v-list>
        <v-list-item v-for="bar in bar" :key="bar.text" router :to="bar.route">
          <v-list-item-action>
            <v-icon> {{ bar.icon }} </v-icon>
          </v-list-item-action>
          <v-list-item-content>
            <v-list-item-tittle>{{ bar.title }}</v-list-item-tittle>
          </v-list-item-content>
        </v-list-item>
      </v-list>
    </v-navigation-drawer>
  </div>
</template>

<script>
export default {
  data: () => ({
    drawermob: false,

    bar: [
      { title: "Dashboard", icon: "mdi-view-dashboard", route: "/dashboard" },
      { title: "Photos", icon: "mdi-image", route: "/photos" },
      { title: "About", icon: "mdi-help-box", route: "/about" },
      { title: "Received", icon: "mdi-email-receive", route: "/received" },
      { title: "Sent", icon: "mdi-send", route: "/sent" },
      { title: "Trash", icon: "mdi-delete", route: "/trash" },
      { title: "Span", icon: "mdi-alert-octagon", route: "/span" },
    ],
  }),
};
</script>
