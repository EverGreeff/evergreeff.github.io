
<a name="top"></a>

## 🔗 Navigate

[🟦 C#](#csharp) &nbsp;|&nbsp;
[🟩 Flutter](#flutter) &nbsp;|&nbsp;
[🟨 PHP](#php) &nbsp;|&nbsp;


<section id="csharp">
  <h2>C# Projects</h2>

  <div class="project-card">
    <h3>💼 Equipment Tracking System for Mining Operations</h3>
    <p>
      A C# desktop application built for mining companies to manage safety equipment issued to employees. The app uses barcode scanning and stores all data in a local SQLite database.
    </p>
    <ul>
      <li>Register employees and safety gear</li>
      <li>Track items checked in/out via barcode</li>
      <li>Identify missing or unreturned equipment</li>
      <li>Fully offline with SQLite support</li>
    </ul>
    <p><strong>Tech used:</strong> C#, WinForms, SQLite, Barcode Scanning</p>
  </div>

  <div class="project-card">
  <h3>🔗 Paint Information API for Android Integration</h3>
  <p>
    A self-hosted C# API that runs on the client's local network and provides paint-related data such as manufacturer, color, and pricing. This API is accessed by an Android app used by employees to search and retrieve product information in real time.
  </p>
  <ul>
    <li>Serves paint data: fabricant, color codes, categories, and prices</li>
    <li>Communicates with an Android app via a local network link</li>
    <li>Supports JSON responses for fast and clean integration</li>
    <li>Lightweight and reliable — ideal for internal environments</li>
  </ul>
  <p><strong>Tech used:</strong> C#, ASP.NET (Self-Hosted API), JSON, Android (Client App)</p>
</div>

<div class="project-card">
  <h3>🛒 Supermarket Self-Service Kiosk (C#)</h3>
  <p>
    A standalone C# application designed for use in supermarkets, allowing customers to scan product barcodes and instantly view item details via a local web interface. The app serves a local route (e.g., <code>localhost:4000</code>) and reloads the browser with the product information after each scan.
  </p>
  <ul>
    <li>Local barcode scanning system for in-store product lookup</li>
    <li>Runs as a C# desktop app and serves an embedded local web server</li>
    <li>Product info is fetched from a local database</li>
    <li>After 20 seconds of inactivity, the app switches to a slideshow of promotional images from a configured folder</li>
  </ul>
  <p><strong>Tech used:</strong> C#, WinForms, SQLite, Embedded Web Server, HTML/JS (UI)</p>
</div>

</section>
[⬆️ Back to top](#top)
<br>
<section id="flutter">
  <h2>Flutter Projects</h2>
  <div class="project-card">
    <h3>📱 Client Support & Interaction App (Flutter)</h3>
    <p>
      A cross-platform mobile app built with Flutter, available for both Android and iOS. The app allows clients to log in, view and respond to support topics, and communicate directly with our company. It integrates with a REST API to handle authentication, data sync, and image uploads for system error reporting.
    </p>
    <ul>
      <li>User login and topic tracking via REST API</li>
      <li>View and reply to ongoing support discussions</li>
      <li>Send screenshots or photos related to system issues</li>
      <li>Compatible with both Android and iOS devices</li>
    </ul>
    <p><strong>Tech used:</strong> Flutter, Dart, REST API, Android, iOS</p>
</div>

<div class="project-card">
  <h3>📦 Product Stock Counting App (Flutter)</h3>
  <p>
    A mobile inventory management app built with Flutter for Android and iOS. Designed for field use in warehouses or retail stores, it enables users to scan product barcodes, count stock, and sync updates with the central system. Product data is initially received from a C# desktop application, and local storage via SQLite ensures offline functionality.
  </p>
  <ul>
    <li>Receives and updates product data from a C# desktop system</li>
    <li>Barcode scanning for quick and accurate item lookup</li>
    <li>Offline-friendly with local SQLite storage</li>
    <li>Automatic syncing of stock counts when reconnected</li>
    <li>Uses Provider for efficient state management</li>
    <li>Cross-platform: Android and iOS support</li>
  </ul>
  <p><strong>Tech used:</strong> Flutter, Dart, Provider, SQLite, Barcode Scanner, C#, Android, iOS</p>
</div>

<div class="project-card">
  <h3>🔍 Product Traceability App (Flutter)</h3>
  <p>
    A versatile Flutter app designed to track product movement and location within a store. It supports multiple operational modes—offline and online—and provides real-time traceability of inventory. Users can scan barcodes to register transfers, updates, and audits. The app supports local data storage with Realm and SQLite, and plays sound cues for confirmations using FlutterRingtonePlayer.
  </p>
  <ul>
    <li>Track product location and movement across store zones</li>
    <li>Supports offline and online operation modes</li>
    <li>Barcode scanning for quick identification and trace logging</li>
    <li>Local storage with Realm and SQLite for flexible data handling</li>
    <li>Auditory feedback using FlutterRingtonePlayer</li>
    <li>Cross-platform: Android and iOS support</li>
  </ul>
  <p><strong>Tech used:</strong> Flutter, Dart, Barcode Scanner, Realm, SQLite, FlutterRingtonePlayer, Android, iOS</p>
</div>

<div class="project-card">
  <h3>🎓 Student Evaluation App (Flutter)</h3>
  <p>
    A Flutter mobile application developed for students to evaluate their classes and teachers. The app provides a simple, user-friendly interface for submitting feedback, which is then processed and stored via a RESTful API.
  </p>
  <ul>
    <li>Students rate and review classes and instructors</li>
    <li>Clean and intuitive mobile UI</li>
    <li>Communicates with a backend RESTful API</li>
    <li>Real-time submission and validation</li>
  </ul>
  <p><strong>Tech used:</strong> Flutter, Dart, REST API, Android, iOS</p>
</div>

</section>
[⬆️ Back to top](#top)
<br>
<section id="php">
  <h2>PHP Projects</h2>
  <div class="project-card">
  <h3>🛠️ RESTful API for Student Evaluation System (PHP)</h3>
  <p>
    A custom RESTful API built in PHP to support the Student Evaluation mobile app. The API handles all backend logic, including authentication, evaluation submissions, and storing feedback securely in a MySQL database.
  </p>
  <ul>
    <li>Processes student feedback and ratings</li>
    <li>Handles user authentication and session control</li>
    <li>Secure endpoints with input validation</li>
    <li>Optimized for performance and mobile access</li>
  </ul>
  <p><strong>Tech used:</strong> PHP, RESTful API, MySQL, JSON</p>
</div>

<div class="project-card">
  <h3>🌐 RESTful API for Client Support App (PHP)</h3>
  <p>
    A PHP-based RESTful API developed to power the Client Support & Interaction App. This API handles authentication, topic management, image uploads, and real-time data syncing between clients and the company’s internal systems.
  </p>
  <ul>
    <li>User authentication and session management</li>
    <li>Provides support topic data and updates</li>
    <li>Handles image uploads and error report attachments</li>
    <li>Ensures secure and structured communication with the Flutter app</li>
  </ul>
  <p><strong>Tech used:</strong> PHP, RESTful API, MySQL, JSON</p>
</div>


</section>

[⬆️ Back to top](#top)

