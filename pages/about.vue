<template>
  <div>
    <nav>
      <h1>Laaggeletterdheid op het web</h1>
      <ul>
        <li>Leesbaarheid</li>
      </ul>
    </nav>
    <header>
      <h2>Laaggeletterdheid.click</h2>
    </header>
    <main>
      <aside>
        <h2>Laaggeletterden op het web?</h2>
        <p>
          Lorem ipsum dolor sit amet, consectetur adipisicing elit. Nemo voluptate, debitis. Vel vitae ipsum totam eius
          necessitatibus illo, dolorem nihil ullam nam quo! Velit quia, fuga vel quos, officia voluptates.Lorem ipsum
          dolor sit amet, consectetur adipisicing elit. Nemo voluptate, debitis. Vel vitae ipsum totam eius necessitatibus
          illo, dolorem nihil ullam nam quo! Velit quia, fuga vel quos, officia voluptates.
        </p>
      </aside>

      <ul class="choices">
        <li>
          <article>
            <section>
              <h3>Leesbaarheid</h3>
              <img src alt>
            </section>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Eligendi quia magnam quos doloremque, ipsum, non accusantium eos, sunt error quidem nam deserunt praesentium odit commodi sed? Necessitatibus fugiat voluptate adipisci?</p>
          </article>
        </li>
        <li>
          <article>
            <section>
              <h3>Leesbaarheid</h3>
              <img src alt>
            </section>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Eligendi quia magnam quos doloremque, ipsum, non accusantium eos, sunt error quidem nam deserunt praesentium odit commodi sed? Necessitatibus fugiat voluptate adipisci?</p>
          </article>
        </li>
        <li>
          <article>
            <section>
              <h3>Leesbaarheid</h3>
              <img src alt>
            </section>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Eligendi quia magnam quos doloremque, ipsum, non accusantium eos, sunt error quidem nam deserunt praesentium odit commodi sed? Necessitatibus fugiat voluptate adipisci?</p>
          </article>
        </li>
        <li>
          <article>
            <section>
              <h3>Leesbaarheid</h3>
              <img src alt>
            </section>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Eligendi quia magnam quos doloremque, ipsum, non accusantium eos, sunt error quidem nam deserunt praesentium odit commodi sed? Necessitatibus fugiat voluptate adipisci?</p>
          </article>
        </li>
        <li>
          <article>
            <section>
              <h3>Leesbaarheid</h3>
              <img src alt>
            </section>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Eligendi quia magnam quos doloremque, ipsum, non accusantium eos, sunt error quidem nam deserunt praesentium odit commodi sed? Necessitatibus fugiat voluptate adipisci?</p>
          </article>
        </li>
        <li>
          <article>
            <section>
              <h3>Leesbaarheid</h3>
              <img src alt>
            </section>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Eligendi quia magnam quos doloremque, ipsum, non accusantium eos, sunt error quidem nam deserunt praesentium odit commodi sed? Necessitatibus fugiat voluptate adipisci?</p>
          </article>
        </li>
      </ul>
    </main>
    <footer>
      <p>vincent kempers 2020</p>
    </footer>
  </div>
</template>

<script>
export default {}
</script>

<style lang="less">
:root {
  --orange-main: #ff6900;
  --orange-secundar: #ffbb86;
}

html,
body {
  margin: 0;
  padding: 0;
}

nav {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 0 1.4em;
  background-color: var(--orange-main);
}

nav > ul {
  display: flex;
  align-items: right;
  list-style: none;
}

nav > ul > li {
  margin-right: 2em;
}

header {
  display: flex;
  background-color: var(--orange-secundar);
  height: 15em;
  flex-direction: column;
  justify-content: center;
  align-items: center;
}

header > h2 {
  text-align: center;
  font-size: 3em;
}

main > aside {
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  text-align: center;
  margin: 4rem 0;
}

main {
  display: block;
  max-width: 60em;
  margin: 0 auto;
}

main > aside > p {
  max-width: 40em;
}

main > h3 {
  text-align: center;
}

main > section {
  background-color: white;
  padding: 2em;
  margin: 0;
  display: flex;
  box-shadow: 0px 1px 23px 0px rgba(0, 0, 0, 0.1);
  -webkit-box-shadow: 0px 1px 23px 0px rgba(0, 0, 0, 0.1);
  transition: background-color, margin 0.5s ease-in;
}

main > section > a {
  text-decoration: none;
}

main > section:hover {
  background-color: var(--orange-secundar);
  box-shadow: 4px 4px 4px 4px black;
  -webkit-box-shadow: 0px 1px 23px 0px rgba(0, 0, 0, 0.2);
  -moz-box-shadow: 0px 1px 23px 0px rgba(0, 0, 0, 0.2);
  box-shadow: 0px 1px 23px 0px rgba(0, 0, 0, 0.2);
  z-index: +1;
  margin: 20px 0;
  transition: all 0.3s ease-in;
}

main > section:hover > a > article > p {
  transition: all 0.3s ease-in;
}

main > section > a {
  display: flex;
  flex-direction: row;
  justify-content: space-between;
  align-items: center;
}

main > section a article > p {
  color: black;
  max-width: 25em;
}

.choices {
  list-style: none;
  display: grid;
  grid-template-columns: 1fr 1fr 1fr;
  grid-gap: 10px;
}

.choices > li {
  background-color: white;
  /* border: 1px solid black; */
  border-radius: 10px;
  box-shadow: 2px 1px 10px 1px rgba(0, 0, 0, 0.1);
}

.choices > li > article {
  padding: 1em;
}
</style>
