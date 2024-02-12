<template>
  <h2>Mes compétences</h2>

  <div class="tables">
    <div class="table">
      <table>
        <h2>Compétences développement</h2>
        <tr>
          <td>HTML</td>
          <td>⭐⭐⭐⭐⭐</td>
        </tr>
        <tr>
          <td>CSS</td>
          <td>⭐⭐⭐⭐⭐</td>
        </tr>
        <tr>
          <td>JavaScript</td>
          <td>⭐⭐⭐⭐⭐</td>
        </tr>
        <tr>
          <td>Vue.js</td>
          <td>⭐⭐⭐⭐⭐</td>
        </tr>
        <tr>
          <td>React</td>
          <td>⭐⭐⭐⭐</td>
        </tr>
        <tr>
          <td>Node.js</td>
          <td>⭐⭐⭐⭐</td>
        </tr>
        <tr>
          <td>SQL</td>
          <td>⭐⭐⭐⭐</td>
        </tr>
        <tr>
          <td>Git</td>
          <td>⭐⭐⭐⭐</td>
        </tr>
        <tr>
          <td>VS Code</td>
          <td>⭐⭐⭐⭐⭐</td>
        </tr>
        <tr>
          <td>Ansible</td>
          <td>⭐⭐⭐⭐</td>
        </tr>
      </table>
    </div>
    <div>
      <table>
        <h2>Compétences autres</h2>
        <tr>
          <td>Photoshop</td>
          <td>⭐⭐</td>
        </tr>
        <tr>
            <td>Sony Vegas Pro</td>
            <td>⭐⭐⭐</td>
        </tr>
        <tr>
          <td>Canvas</td>
          <td>⭐⭐⭐⭐</td>
        </tr>
      </table>
    </div>
  </div>
</template>

<script>
export default {
  name: "SectionThree",
};
</script>

<style>
.tables {
  display: flex;
    justify-content: space-around;
}
.table{
    display: flex;
    flex-direction: column;
}
</style>
