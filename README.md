<style>
  .tab {
    overflow: hidden;
    border: 1px solid #ccc;
    background-color: #f1f1f1;
  }

  .tab button {
    background-color: inherit;
    float: left;
    border: none;
    outline: none;
    cursor: pointer;
    padding: 14px 16px;
    transition: 0.3s;
    font-size: 17px;
  }

  .tab button:hover {
    background-color: #ddd;
  }

  .tab button.active {
    background-color: #ccc;
  }

  .tabcontent {
    display: none;
    padding: 6px 12px;
    border: 1px solid #ccc;
    border-top: none;
  }
</style>

<h1 align="center"><strong>Final project website using  HTML</strong></h1>
<h1 align="center">CPE31S4 CPE232 | Allen Jerome B. Gonzales</h1>

<div class="tab">
  <button class="tablinks" onclick="openTab(event, 'Prelim')">Prelim Period</button>
  <button class="tablinks" onclick="openTab(event, 'Midterm')">Midterm Period</button>
  <button class="tablinks" onclick="openTab(event, 'Final')">Final Period</button>
</div>

<div id="Prelim" class="tabcontent">
  <h2>Prelim Period</h2>
  <p><strong>Prelim Period Content:</strong></p>

  - [Hands-on Activity 1 - Creating Virtual Machines](https://github.com/qajgonzales1/HOA1.git)
  - [Hands-on Activity 2 - SSH Key-Based Authentication and GIT Setup](https://github.com/qajgonzales1/HOA2.git)
  <!-- Add more content here -->
</div>

<div id="Midterm" class="tabcontent">
  <h2>Midterm Period</h2>
  <p><strong>Midterm Period Content:</strong></p>

  - [Hands-on Activity 6 - Targeting specific nodes](https://github.com/qajgonzales1/HOA6.git)
  - [Hands-on Activity 7 - Managing files and Creating Roles in Ansible](https://github.com/qajgonzales1/HOA7.git)
  <!-- Add more content here -->
</div>

<div id="Final" class="tabcontent">
  <h2>Final Period</h2>
  <p><strong>Final Period Content:</strong></p>

  - [Hands-on Activity 11 - Containerization](https://github.com/qajgonzales1/HOA11.git)
  - [Hands-on Activity 12 - Build a sample web app in a Docker Container](https://github.com/qajgonzales1/HOA12.git)
  <!-- Add more content here -->
</div>

<script>
  function openTab(evt, tabName) {
    var i, tabcontent, tablinks;
    tabcontent = document.getElementsByClassName("tabcontent");
    for (i = 0; i < tabcontent.length; i++) {
      tabcontent[i].style.display = "none";
    }
    tablinks = document.getElementsByClassName("tablinks");
    for (i = 0; i < tablinks.length; i++) {
      tablinks[i].className = tablinks[i].className.replace(" active", "");
    }
    document.getElementById(tabName).style.display = "block";
    evt.currentTarget.className += " active";
  }
</script>
