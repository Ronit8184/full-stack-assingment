<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Responsive Image Gallery</title>
<link rel="stylesheet" href="style.css">
</head>
<body>
<div class="gallery">
<img
src="https://images.unsplash.com/photo-1731865274308-d98c94287603?q=80&w=1864&auto=f
ormat&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D
%3D" alt="Image 2">
<img
src="https://images.unsplash.com/photo-1731848558736-45b827aa65d3?w=500&auto=format&
fit=crop&q=60&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHx0b3BpYy1mZWVkfDI1fE04alZiTGJUUndzfH
xlbnwwfHx8fHw%3D" alt="Image 3">
<img
src="https://images.unsplash.com/photo-1731889043744-f8e5cf5286d6?w=500&auto=format&
fit=crop&q=60&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHx0b3BpYy1mZWVkfDEyfE04alZiTGJUUndzfH
xlbnwwfHx8fHw%3D" alt="Image 4">
<img
src="https://images.unsplash.com/photo-1732020283419-38e938352c3c?w=500&auto=format&
fit=crop&q=60&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHx0b3BpYy1mZWVkfDR8TThqVmJMYlRSd3N8fG
VufDB8fHx8fA%3D%3D" alt="Image 5">
<img
src="https://images.unsplash.com/photo-1732053860376-b620f02baac6?w=500&auto=format&
fit=crop&q=60&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHx0b3BpYy1mZWVkfDd8TThqVmJMYlRSd3N8fG
VufDB8fHx8fA%3D%3D" alt="Image 6">
</div>
</body>
</html>
-------------------------------------------------------------------------------
5-CSS
* {
box-sizing: border-box;
margin: 0;
padding: 0;
}
body {
font-family: Arial, sans-serif;
background-color: #f4f4f4;
}
.gallery {
display: grid;
grid-template-columns: repeat(auto-fill, minmax(250px, 1fr));
gap: 10px;
padding: 20px;
}
.gallery img {
width: 100%;
height: auto;
border-radius: 8px;
transition: transform 0.2s;
}
.gallery img:hover {
transform: scale(1.05);
}
------------------------
