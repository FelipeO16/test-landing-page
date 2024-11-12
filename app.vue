<template>
  <div>
    <header class="header">
      <h1>LOJA</h1>
      <nav class="menu">
        <ul>
          <li><a href="#">Home</a></li>
          <li><a href="#">Produtos</a></li>
          <li><a href="#">Contato</a></li>
        </ul>
      </nav>
    </header>
    <main>
      <section>
        <div class="banner">
          <h1>PRODUTOS</h1>
          <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Quos vero, 
            quam nostrum repellat molestiae iure magni at eius. Quam provident, 
            minus deleniti non error nemo laborum dignissimos illo cumque unde?</p>
        </div>
        <div>
          <button>MAIS</button>
          <button>COMPRAR</button>
        </div>
      </section>
    </main>
  </div>
</template>

<style>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

.header {
  background-color: #333;
  color: white;
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 0 20px;
}

.menu ul {
  display: flex;
  list-style: none;
}

li > {
  margin-right: 20px;
  color: wihte;

}

</style>
