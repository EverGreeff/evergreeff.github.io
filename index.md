<div id="tech-filter">
  <button onclick="filterProjects('all')">All</button>
  <button onclick="filterProjects('csharp')">C#</button>
  <button onclick="filterProjects('flutter')">Flutter</button>
  <button onclick="filterProjects('php')">PHP</button>
</div>

<div class="project csharp">
  <h3>Equipment Tracker</h3>
  <p>Built in C#, SQLite, WinForms...</p>
</div>

<div class="project flutter">
  <h3>Internal Chat App</h3>
  <p>Made in Flutter with WebSockets...</p>
</div>

<div class="project php">
  <h3>Support Portal</h3>
  <p>Built using PHP and MySQL...</p>
</div>

<script>
function filterProjects(tech) {
  const projects = document.querySelectorAll('.project');
  projects.forEach(p => {
    p.style.display = (tech === 'all' || p.classList.contains(tech)) ? 'block' : 'none';
  });
}
</script>
