<template>
  <div id="app">
      <header class="header">
          <nav class="inner">
              <router-link to="/" exact>
                <img src="~public/logo-48.png" alt="logo" class="logo"> 
              </router-link>
              <router-link to="/top">Top</router-link>
            <router-link to="/new">New</router-link>
            <router-link to="/show">Show</router-link>
            <router-link to="/ask">Ask</router-link>
            <router-link to="/job">Jobs</router-link>
            <a  href="https://github.com/vuejs/vue-hackernews-2.0" target="_blank" rel="noopener" class="github"></a>
          </nav>
      </header>
      <transition name="fade" mode="out-in">
        <router-view class="view"></router-view>
        </transition>
  </div>
</template>
