<template>
  <div>
    <!--
    <div class="ui fluid orange card">
      <div class="content">
        <div class="header">
          Bonjour Invité
        </div>
      </div>
      <div class="extra content">
        <div class="ui two buttons">
          <div class="ui basic grey small button">Se connecter</div>
          <div class="ui blue button">S' inscrire</div>
        </div>
      </div>


    </div>
    
    <a class="item">
      <i class="home icon"></i>
      Accueil
    </a>
    -->
    <div class="ui relaxed divided list">
      <div class="ui left aligned item">
        <div class="content left aligned">
          <div class="ui orange header">
            <nuxt-link to="/">Accueil</nuxt-link>
          </div>
        </div>
      </div>
      <div class="ui left aligned item">
        <div class="content left aligned">
          <div class="ui orange header">
            <nuxt-link to="le-menu">Le menu</nuxt-link>
          </div>
        </div>
      </div>
      <div class="item left aligned">
        <div class="ui orange header">
          <nuxt-link to="/contact">contact</nuxt-link>
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped>
.ui .list {
  padding-left: 1rem;
  padding-top: 1rem;
}
</style>
