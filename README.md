<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Final Project Website</title>
    <style>
        /* Add your CSS styles here */
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }

        header {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 15px 0;
        }

        nav {
            background-color: #f2f2f2;
            overflow: hidden;
        }

        nav a {
            float: left;
            display: block;
            color: #333;
            text-align: center;
            padding: 14px 20px;
            text-decoration: none;
        }

        nav a:hover {
            background-color: #ddd;
        }

        .tabcontent {
            display: none;
            padding: 20px;
        }
    </style>
    <script>
        // JavaScript to toggle between tabs
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
</head>

<body>

    <header>
        <h1>Final Project Website using HTML</h1>
        <h2>CPE31S4 CPE232 | Allen Jerome B. Gonzales</h2>
    </header>

    <nav>
        <a href="#" class="tablinks" onclick="openTab(event, 'Prelim')">Prelim Period</a>
        <a href="#" class="tablinks" onclick="openTab(event, 'Midterm')">Midterm Period</a>
        <a href="#" class="tablinks" onclick="openTab(event, 'Final')">Final Period</a>
    </nav>

    <!-- Prelim Period Content -->
    <div id="Prelim" class="tabcontent">
        <h3 align="center">Prelim Period</h3>
        <!-- Add your prelim period content here -->
        <p><strong>Prelim Period:</strong></p>
        <!-- ... Your prelim content ... -->
- Hands-on Activity 1 [Creating Virtual Machines](https://github.com/qajgonzales1/HOA1.git)

- Hands-on Activity 2 [SSH Key-Based Authentication and GIT Setup](https://github.com/qajgonzales1/HOA2.git)

- Hands-on Activity 3 [Install SSH server on CentOS or RHEL 8](https://github.com/qajgonzales1/HOA3.git)

- Hands-on Activity 4 [Ansible Basics](https://github.com/qajgonzales1/HOA4.git)

- Hands-on Activity 5 [Implementing Ansible roles in playbooks](https://github.com/qajgonzales1/HOA5.git)

- Prelim Examination [Major Examination](https://github.com/qajgonzales1/Gonzales_PrelimExam.git)

    <!-- Midterm Period Content -->
    <div id="Midterm" class="tabcontent">
        <h3 align="center">Midterm Period</h3>

    <p><strong>Midterm Period: </strong></p>

- Hands-on Activity 6 [Targeting specific nodes](https://github.com/qajgonzales1/HOA6.git)

- Hands-on Activity 7 [Managing files and Creating Roles in Ansible](https://github.com/qajgonzales1/HOA7.git)

- Hands-on Activity 8 [Install, Configure and Manage Enterprise Availability Monitoring via Ansible](https://github.com/qajgonzales1/HOA-8.git)

- Hands-on Activity 9 [Install, Configure and Manage Enterprise Performance Monitoring via Ansible](https://github.com/qajgonzales1/HOA9.git)

- Hands-on Activity 10 [Install, Configure and Manage Enterprise Log Monitoring via Ansible](https://github.com/qajgonzales1/HOA10.git)

- Midterm Exam [Major Examination](https://github.com/qajgonzales1/CPE_MIDEXAM_GONZALES.git)

    <!-- Final Period Content -->
    <div id="Final" class="tabcontent">
        <h3 align="center">Final Period</h3>
        <!-- Add your final period content here -->
        <p><strong>Final Period:</strong></p>
        <!-- ... Your final content ... -->
    - Hands-on Activity 11 [Containerization](https://github.com/qajgonzales1/HOA11.git)

- Hands-on Activity 12 [Build a sample web app in a Docker Container](https://github.com/qajgonzales1/HOA12.git)

- Hands-on Activity 13 [Openstack Prerequisite Installation](https://github.com/qajgonzales1/HOA13.git)

- Hands-on Activity 14 [Openstack Installation(Keystone, Glance, Nova)]()

- Hands-on Activity 15 [Openstack Installation(Neutron, Horizon, Cinder)]()


    <footer>
        <p>Contact: <a href="mailto:qajgonzales1@tip.edu.ph">qajgonzales1@tip.edu.ph</a></p>
    </footer>

</body>

</html>
