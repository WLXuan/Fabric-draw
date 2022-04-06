<template>
  <div>
    <nav class="navbar navbar-inverse navbar-fixed-top" role="navigation">
      <div class="container-fluid">
        <div class="navbar-header">
          <a class="navbar-brand" >Fabric Draw</a>
        </div>
        <div>
          <ul class="nav navbar-nav">
            <li class="active"><a href="#">iOS</a></li>
            <li><a href="#">SVN</a></li>
            <li class="dropdown">
              <a href="#" class="dropdown-toggle" data-toggle="dropdown">
                Java <b class="caret"></b>
              </a>
              <ul class="dropdown-menu">
                <li><a href="#">jmeter</a></li>
                <li><a href="#">EJB</a></li>
                <li><a href="#">Jasper Report</a></li>
                <li class="divider"></li>
                <li><a href="#">分离的链接</a></li>
                <li class="divider"></li>
                <li><a href="#">另一个分离的链接</a></li>
              </ul>
            </li>
          </ul>
        </div>
      </div>
    </nav>
    <div id="visualization" class="vis-container m-auto"></div>
    <div id="mynetwork"></div>
  </div>
</template>

<script>
export default {
  name: 'fabric-draw',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  }
}
// var nodes = new vis.DataSet([
//   { id: 1, label: "Node 1" },
//   { id: 2, label: "Node 2" },
//   { id: 3, label: "Node 3" },
//   { id: 4, label: "Node 4" },
//   { id: 5, label: "Node 5" },
// ]);
//
// // create an array with edges
// var edges = new vis.DataSet([
//   { from: 1, to: 3 },
//   { from: 1, to: 2 },
//   { from: 2, to: 4 },
//   { from: 2, to: 5 },
//   { from: 3, to: 3 },
// ]);
//
// // create a network
// var container = document.getElementById("mynetwork");
// var data = {
//   nodes: nodes,
//   edges: edges,
// };
// var options = {};
// var network = new vis.Network(container, data, options);
</script>

import Vis from "vis";

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.vis-container {
  width: 960px;
  height: 540px;
  background-color: red;
}
.navbar {

}
</style>
