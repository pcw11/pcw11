## Hi there 👋

### Statistics
<div>
  <canvas id="languageChart" width="400" height="400"></canvas>
  <script src="https://cdn.jsdelivr.net/npm/chart.js"></script>
  <script>
    const ctx = document.getElementById('languageChart').getContext('2d');
    const languageChart = new Chart(ctx, {
      type: 'pie',
      data: {
        labels: ['Python', 'Java', 'Git'],
        datasets: [{
          data: [50, 35, 15],
          backgroundColor: ['#306998', '#f89820', '#F05033']
        }]
      }
    });
  </script>
</div>

