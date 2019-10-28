<template>
  <div>
    <div class="columns is-mobile is-fullheight">
      <div class="column is-2 border is-sidebar-menu">
        <aside class="menu">
          <p class="menu-label">General</p>
          <ul class="menu-list">
            <li>
              <a>Dashboard</a>
            </li>
            <li>
              <a>Customers</a>
            </li>
          </ul>
          <p class="menu-label">Administration</p>
          <ul class="menu-list">
            <li>
              <a>Team Settings</a>
            </li>
            <li>
              <a class="is-active">Manage Your Team</a>
              <ul>
                <li>
                  <a>Members</a>
                </li>
                <li>
                  <a>Plugins</a>
                </li>
                <li>
                  <a>Add a member</a>
                </li>
              </ul>
            </li>
            <li>
              <a>Invitations</a>
            </li>
            <li>
              <a>Cloud Storage Environment Settings</a>
            </li>
            <li>
              <a>Authentication</a>
            </li>
          </ul>
          <p class="menu-label">Transactions</p>
          <ul class="menu-list">
            <li>
              <a>Payments</a>
            </li>
            <li>
              <a>Transfers</a>
            </li>
            <li>
              <a>Balance</a>
            </li>
          </ul>
        </aside>
      </div>
      <div class="column border">
        <div class="columns">
          <div class="column">
            <nav class="navbar" role="navigation" aria-label="main navigation">
              <div class="navbar-brand">
                <a class="navbar-item" href="https://bulma.io">
                  <img src="https://bulma.io/images/bulma-logo.png" width="112" height="28" />
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
                      <hr class="navbar-divider" />
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
          </div>
        </div>
        <div class="columns">
          <div class="column">
            <p>This is the main area where everything is</p>
          </div>
          <div class="column">
            <p>This is the main area where everything is</p>
          </div>
        </div>
        <div class="columns">
          <div class="column">
            <p>This is the main area where everything is</p>
          </div>
          <div class="column">
            <p>This is the main area where everything is</p>
          </div>
        </div>
      </div>
    </div>
    <footer class="footer border">
      <div class="content has-text-centered">
        <p>
          <strong>Bulma</strong> by
          <a href="https://jgthms.com">Jeremy Thomas</a>. The source code is licensed
          <a href="http://opensource.org/licenses/mit-license.php">MIT</a>. The website content
          is licensed
          <a
            href="http://creativecommons.org/licenses/by-nc-sa/4.0/"
          >CC BY NC SA 4.0</a>.
        </p>
      </div>
    </footer>
  </div>
</template>

<script>
export default {
  name: "HelloWorld"
};
</script>

<style scoped lang="scss">
</style>
