<style>
  table {
    width: 80%;
    margin: 30px auto;
    border-collapse: collapse;
    font-family: 'Segoe UI', sans-serif;
    font-size: 15px;
  }

  th {
    background: #f2f2f2;
    padding: 10px;
    text-align: left;
    border: 1px solid #ddd;
  }

  td {
    width: 900px;
    height: 10px;
    padding: 10px;
    text-align: left;
    border: 1px solid #ddd;
  }

  .description {
    margin: 0 auto;
    font-family: 'Segoe UI', sans-serif;
    font-size: 14px;
    color: #444;
  }

  .highlight-box {
    background: #f8f9fa;
    padding: 12px 24px 12px 32px; /* Top, Right, Bottom, Left */
    border-left: 4px solid #0078d4;
    margin: 20px auto;
    font-size: 14px;
    text-align: left;
}


  }
</style>

<div class="description">
  <h2 style="color: #333;">📄 Description</h2>
  <p>
    In this demonstration, you'll witness how <strong>Contoso</strong> unfolds the future of integration and innovation with <strong>Microsoft Fabric</strong>.
  </p>
  <ul>
    <li>Seamless collaboration enabled by <strong>OneLake</strong>, providing unified storage for innovation and teamwork.</li>
    <li>Intelligent <strong>Copilot</strong> in Data Warehouse, Data Science, and Real-Time Experience to assist coding needs.</li>
    <li>Enhanced data reliability with <strong>Database Mirroring</strong> and <strong>Shortcuts</strong> for secure data flow.</li>
    <li><strong>Data Activator</strong> triggers real-time alerts by monitoring activity continuously.</li>
    <li><strong>Power BI Copilot</strong> elevates business and technical insights for users.</li>
  </ul>
</div>

<div class="highlight-box">
  <strong>IMPORTANT:</strong><br>
  Please launch the demo <strong>15 minutes before presenting</strong>. Resources may take a few minutes to provision.<br>
  ODL access provisioning may take <strong>5–7 minutes</strong>.<br>
  If unauthorized errors occur, wait a few minutes and then press <strong>Ctrl + Shift + R</strong> to refresh.
</div>

<!-- Auth Table -->
<table style="width: 900px; margin: 20px auto; border-collapse: collapse; font-size: 15px; border: 1px solid #ddd;">
  <thead>
    <tr style="background: #f2f2f2;">
      <th style="padding: 12px 20px; text-align: left;">Field</th>
      <th style="padding: 12px 20px; text-align: left;">Value</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="padding: 12px 20px;">Username</td>
      <td style="padding: 12px 20px;"><inject key="AzureAdUserEmail" /></td>
    </tr>
    <tr>
      <td style="padding: 12px 20px;">Password</td>
      <td style="padding: 12px 20px;"><inject key="AzureAdUserPassword" /></td>
    </tr>
  </tbody>
</table>


<!-- Resource Details Table -->
<table>
  <thead>
    <tr>
      <th>Key</th>
      <th>Value</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Web App Link</td>
      <td>
        <a href="https://app-fabric-demo-4-prod.azurewebsites.net" target="_blank">
          https://app-fabric-demo-4-prod.azurewebsites.net
        </a>
      </td>
    </tr>
    <tr>
      <td>Microsoft Fabric Workspace</td>
      <td>
        <a href="https://app.powerbi.com/home?experience=fabric" target="_blank">
          https://app.powerbi.com/home?experience=fabric
        </a>
      </td>
    </tr>
    <tr>
      <td>Teams Login Username</td>
      <td>DemoUser1@CloudLabsAloutlook.onmicrosoft.com</td>
    </tr>
    <tr>
      <td>Teams Login Password</td>
      <td>Demou$e673&amp;Fhj</td>
    </tr>
  </tbody>
</table>
