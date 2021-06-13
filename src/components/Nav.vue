<template>
  <div class="navigation">
    <input
      type="checkbox"
      class="navigation__checkbox"
      id="navi-toggle"
      :class="{ navigation__checkbox_checked: isOpen }"
      @click="toggle()"
    />

    <label for="navi-toggle" class="navigation__button">
      <span class="navigation__icon"></span>
    </label>

    <div class="navigation__background">&nbsp;</div>
    <nav class="navigation__nav">
      <ul class="navigation__list">
        <li class="navigation__item" @click="toggle()">
          <a href="#about" class="navigation__link">About</a>
        </li>
        <li class="navigation__item" @click="toggle()">
          <a href="#features" class="navigation__link">Features</a>
        </li>
        <li class="navigation__item" @click="toggle()">
          <a href="#offers" class="navigation__link">our offers</a>
        </li>
        <li class="navigation__item" @click="toggle()">
          <a href="#stories" class="navigation__link">Stories</a>
        </li>
        <li class="navigation__item" @click="toggle()">
          <a href="#book" class="navigation__link">Book yours now !</a>
        </li>
      </ul>
    </nav>
  </div>
</template>

<script>
export default {
  data() {
    return {
      isOpen: false,
    };
  },
  methods: {
    toggle() {
      this.isOpen = !this.isOpen;
    },
  },
};
</script>
