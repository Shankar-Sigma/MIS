<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1.0" />
<title>Prepress MIS</title>
<style>
body {
margin: 0;
font-family: Arial, sans-serif;
display: flex;
background-color: #e0f2e9;
height: 100vh;
}
.sidebar {
width: 220px;
background-color: #2e7d32;
color: white;
display: flex;
flex-direction: column;
align-items: center;
padding-top: 20px;
}
.icon-bar {
display: flex;
justify-content: center;
gap: 10px;
margin-bottom: 20px;
}
.icon-bar button {
background: none;
border: none;
cursor: pointer;
color: white;
font-size: 1.2em;
}
.sidebar button {
background: none;
color: white;
border: none;
text-align: left;
padding: 15px 20px;
width: 100%;
font-size: 1em;
cursor: pointer;
}
.sidebar button:hover {
background-color: #1b5e20;
}
.main {
flex-grow: 1;
display: flex;
align-items: center;
justify-content: center;
color: #2e7d32;
font-size: 2em;
}
</style>
<script src="https://kit.fontawesome.com/a076d05399.js" crossorigin="anonymous"></script>
</head>
<body>
<div class="sidebar">
<div class="icon-bar">
<button title="Search"><i class="fas fa-search"></i></button>
<button title="Back" onclick="history.back()"><i class="fas fa-arrow-left"></i></button>
<button title="Forward" onclick="history.forward()"><i class="fas fa-arrow-right"></i></button>
<button title="Save" onclick="saveData()"><i class="fas fa-save"></i></button>
</div>
<button>Dashboard</button>
<button>Timesheet</button>
<button>Charts</button>
</div>
<div class="main">
<p>Welcome to Prepress MIS</p>
</div>
<script>
function saveData() {
alert('Data saved successfully!');
}
</script>
</body>
</html>
