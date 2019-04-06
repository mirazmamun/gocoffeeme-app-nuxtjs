<template>
  <nav class="navbar is-fixed-top" role="navigation" aria-label="main navigation">
    <div class="navbar-brand">
      <a class="navbar-item" href="#">
        <svg
          xmlns="http://www.w3.org/2000/svg"
          x="0px"
          y="0px"
          width="48"
          height="48"
          viewBox="0 0 192 192"
          style=" fill:#000000;"
        >
          <g
            fill="none"
            fill-rule="nonzero"
            stroke="none"
            stroke-width="1"
            stroke-linecap="butt"
            stroke-linejoin="miter"
            stroke-miterlimit="10"
            stroke-dasharray
            stroke-dashoffset="0"
            font-family="none"
            font-weight="none"
            font-size="none"
            text-anchor="none"
            style="mix-blend-mode: normal"
          >
            <path d="M0,192v-192h192v192z" fill="none"></path>
            <g>
              <g id="surface1">
                <path
                  d="M127.65625,24c-36.90625,0 -42.01563,34.25 -55.60938,48.35938c-13.45312,13.90625 -48.04688,24.10938 -48.04688,56.15625c0,7.40625 3.375,15.28125 11.9375,23.53125c4.53125,4.40625 10.82812,6.4375 18.20312,6.4375c18.98438,0 45.26563,-13.64062 67.85938,-37.01562c31.35938,-32.5 43.65625,-71.48438 27.53125,-87.09375c-7.67188,-7.40625 -14.96875,-10.375 -21.875,-10.375z"
                  fill="#1abc9c"
                ></path>
                <path
                  d="M150.5,35.53125c14.51562,16.26562 2.14062,54.17187 -28.5,85.9375c-22.59375,23.375 -48.875,37.01562 -67.85938,37.01562c-5.45312,0 -10.29687,-1.125 -14.29687,-3.48438c27.84375,22.53125 68.65625,14.82812 99.17187,-16.78125c31.10938,-32.25 40.51563,-73.23438 11.48438,-102.6875z"
                  fill="#6d4c41"
                ></path>
                <path
                  d="M101.10938,70.8125c-2.42188,6.73438 -4.51562,14.6875 -10.57812,20.96875c-5.82813,6.07812 -15.92188,10.4375 -22.125,13.53125c-16,7.90625 -21.92188,24.875 -20.76563,36.26562c3.51563,-12.89062 16.125,-20.64062 26.59375,-25.73437c6.89062,-3.39063 18.5625,-7.20313 26,-14.92188c7.96875,-8.20312 9.25,-17.85938 11.98438,-25.15625c3.75,-9.85937 15.51562,-24.53125 26.625,-30.98437c-9.9375,-0.28125 -30.21875,5.35937 -37.73438,26.03125z"
                  fill="#6d4c41"
                ></path>
              </g>
            </g>
          </g>
        </svg>
      </a>

      <a
        role="button"
        class="navbar-burger burger"
        aria-label="menu"
        aria-expanded="false"
        data-target="navbarBasicExample"
      >
        <span aria-hidden="true"></span>
        <span aria-hidden="true"></span>
        <span aria-hidden="true"></span>
      </a>
    </div>

    <div id="navbarBasicExample" class="navbar-menu">
      <div class="navbar-start">
        <a class="navbar-item">Home</a>

        <a class="navbar-item">Documentation</a>

        <div class="navbar-item has-dropdown is-hoverable">
          <a class="navbar-link">More</a>

          <div class="navbar-dropdown">
            <a class="navbar-item">About</a>
            <a class="navbar-item">Jobs</a>
            <a class="navbar-item">Contact</a>
            <hr class="navbar-divider">
            <a class="navbar-item">Report an issue</a>
          </div>
        </div>
      </div>

      <div class="navbar-end">
        <div class="navbar-item">
          <div class="buttons">
            <a class="button is-primary">
              <strong>Sign up</strong>
            </a>
            <a class="button is-light">Log in</a>
          </div>
        </div>
      </div>
    </div>
  </nav>
</template>
<style></style>
<script>
export default {
  components: {}
}
</script>