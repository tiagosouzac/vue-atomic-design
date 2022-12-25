<template>
  <form class="search-form">
    <input type="search" placeholder="Buscar" />

    <button type="submit">
      <img src="@/assets/images/icons/search.svg" alt="Buscar" />
    </button>
  </form>
</template>

<style lang="scss" scoped>
.search-form {
  width: max-content;
  position: relative;

  input {
    padding: 0.5rem 1rem;
    border: none;
    border-radius: 1rem;
    box-shadow: 0px 5px 5px rgba(#000000, 0.08);

    &::placeholder {
      color: #a9b0be;
    }
  }

  button {
    width: 30px;
    height: 30px;
    border: none;
    border-radius: 5rem;
    background: #ff895f;
    transform: translateY(-50%);
    display: grid;
    justify-items: center;
    align-items: center;
    position: absolute;
    right: 3px;
    top: 50%;
  }
}
</style>
