<template>
  <div class="home">
    <div class="timeline">
      <IconHome width="60" height="60" />
      <p>
        Lorem ipsum dolor sit amet, consectetur adipisicing elit. Aut culpa,
        doloremque ducimus ea eligendi hic incidunt ipsum minus neque obcaecati
        omnis optio placeat porro quasi recusandae reprehenderit tenetur vitae
        voluptatem!
      </p>
      <p>
        Lorem ipsum dolor sit amet, consectetur adipisicing elit. Aut culpa,
        doloremque ducimus ea eligendi hic incidunt ipsum minus neque obcaecati
        omnis optio placeat porro quasi recusandae reprehenderit tenetur vitae
        voluptatem!
      </p>
      <p>
        Lorem ipsum dolor sit amet, consectetur adipisicing elit. Aut culpa,
        doloremque ducimus ea eligendi hic incidunt ipsum minus neque obcaecati
        omnis optio placeat porro quasi recusandae reprehenderit tenetur vitae
        voluptatem!
      </p>
      <p>
        Lorem ipsum dolor sit amet, consectetur adipisicing elit. Aut culpa,
        doloremque ducimus ea eligendi hic incidunt ipsum minus neque obcaecati
        omnis optio placeat porro quasi recusandae reprehenderit tenetur vitae
        voluptatem!
      </p>
      <h1>H11111111111111111111</h1>
      <p>
        Lorem ipsum dolor sit amet, consectetur adipisicing elit. Aut culpa,
        doloremque ducimus ea eligendi hic incidunt ipsum minus neque obcaecati
        omnis optio placeat porro quasi recusandae reprehenderit tenetur vitae
        voluptatem!
      </p>
      <p>
        Lorem ipsum dolor sit amet, consectetur adipisicing elit. Aut culpa,
        doloremque ducimus ea eligendi hic incidunt ipsum minus neque obcaecati
        omnis optio placeat porro quasi recusandae reprehenderit tenetur vitae
        voluptatem!
      </p>
      <p>
        Lorem ipsum dolor sit amet, consectetur adipisicing elit. Aut culpa,
        doloremque ducimus ea eligendi hic incidunt ipsum minus neque obcaecati
        omnis optio placeat porro quasi recusandae reprehenderit tenetur vitae
        voluptatem!
      </p>
      <p>
        Lorem ipsum dolor sit amet, consectetur adipisicing elit. Aut culpa,
        doloremque ducimus ea eligendi hic incidunt ipsum minus neque obcaecati
        omnis optio placeat porro quasi recusandae reprehenderit tenetur vitae
        voluptatem!
      </p>
    </div>
    <div class="sidebar">
      <p>
        Lorem ipsum dolor sit amet, consectetur adipisicing elit. Aut culpa,
        doloremque ducimus ea eligendi hic incidunt ipsum minus neque obcaecati
        omnis optio placeat porro quasi recusandae reprehenderit tenetur vitae
        voluptatem!
      </p>
      <p>
        Lorem ipsum dolor sit amet, consectetur adipisicing elit. Aut culpa,
        doloremque ducimus ea eligendi hic incidunt ipsum minus neque obcaecati
        omnis optio placeat porro quasi recusandae reprehenderit tenetur vitae
        voluptatem!
      </p>
    </div>
  </div>
</template>

<script>
import IconHome from '@/icons/home.svg'
export default {
  name: 'Home',
  components: {
    IconHome
  }
}
</script>

<style scoped>
.home {
  max-width: 605px;
  margin-left: auto;
  margin-right: auto;
  @media (--t) {
    max-width: none;
    display: grid;
    grid-template-columns: 1fr 295px;
    grid-gap: 30px;
  }
}

.sidebar {
  display: none;
  @media (--t) {
    display: block;
  }
}
</style>
