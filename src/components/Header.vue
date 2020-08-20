<template>
  <div class="row">
    <div class="col-sm-12">
      <nav class="navbar navbar-expand-lg navbar-light bg-light border rounded">
        <router-link class="navbar-brand" to="/">Stock Trader</router-link>
        <ul class="navbar-nav mr-auto">
          <li class="nav-item">
            <router-link class="nav-link" to="/portfolio">Portfolio</router-link>
          </li>
          <li class="nav-item">
            <router-link class="nav-link" to="/stocks">Stocks</router-link>
          </li>
        </ul>
        <ul class="navbar-nav ml-auto">
          <li class="nav-item">
            <a class="nav-link">End day</a>
          </li>
          <li class="nav-item dropdown">
            <a
              class="nav-link dropdown-toggle"
              role="button"
              data-toggle="dropdown"
              aria-haspopup="true"
              aria-expanded="false"
            >Save & Load</a>
            <div class="dropdown-menu" aria-labelledby="navbarDropdown">
              <a class="dropdown-item">Save</a>
              <a class="dropdown-item">Load</a>
            </div>
          </li>
          <li class="nav-item">
            <span class="nav-link">
              <strong>Funds: $</strong>
            </span>
          </li>
        </ul>
      </nav>
    </div>
  </div>
</template>
