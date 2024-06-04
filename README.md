# IoT-Real-Time-Data-Project-using-Azure

 <h2>Overview</h2>
    <p>
        This project demonstrates a real-time data processing system using a Raspberry Pi simulator and various Azure services. The simulated IoT devices collect data and send it to Azure IoT Hub, where it is processed and stored. The project includes data visualization and real-time monitoring using Azure Stream Analytics and Power BI.
    </p>

 <h2>Architecture</h2>
    <p>The architecture of this project includes the following components:</p>
    <ul>
        <li><strong>Raspberry Pi Simulator:</strong> Generates and sends simulated data to Azure IoT Hub.</li>
        <li><strong>Azure IoT Hub:</strong> Receives and manages messages from IoT devices.</li>
        <li><strong>Azure Stream Analytics:</strong> Processes the data in real-time.</li>
        <li><strong>Azure SQL Database:</strong> Stores the processed data for querying and analysis.</li>
        <li><strong>Power BI:</strong> Visualizes the data in real-time dashboards.</li>
    </ul>

  <h2>Services Used</h2>
    <ul>
        <li><strong>Azure IoT Hub:</strong> Manages IoT devices and ingests data.</li>
        <li><strong>Azure Stream Analytics:</strong> Processes and analyzes streaming data in real-time.</li>
        <li><strong>Azure SQL Database:</strong> Stores processed data for further analysis.</li>
        <li><strong>Power BI:</strong> Creates interactive visualizations and dashboards.</li>
        <li><strong>Raspberry Pi Simulator:</strong> Simulates IoT devices for data generation.</li>
    </ul>

  <h2>Data Flow</h2>
    <ul>
        <li><strong>Data Generation:</strong> The Raspberry Pi simulator generates data points, including temperature and humidity readings.</li>
        <li><strong>Data Ingestion:</strong> The generated data is sent to Azure IoT Hub.</li>
        <li><strong>Real-Time Processing:</strong> Azure Stream Analytics processes the data, performing transformations and computations as needed.</li>
        <li><strong>Data Storage:</strong> The processed data is stored in Azure SQL Database.</li>
        <li><strong>Visualization:</strong> Power BI retrieves data from the SQL database and visualizes it in real-time dashboards.</li>
    </ul>

  <h2>Screenshots</h2>
   <p><strong>Azure IoT Hub</strong></p>
    <img src="https://github.com/Savan2110/IoT-Real-Time-Data-Project-using-Azure/assets/51812887/f056626a-100a-42ec-a309-ec41ed3fb4d8">

   <p><strong>Registered IoT Device</strong></p>
    <img src="path_to_image_2" alt="Registered Io![Screenshot 2024-06-04 143011](https://github.com/Savan2110/IoT-Real-Time-Data-Project-using-Azure/assets/51812887/1717c982-6ebe-43a0-b980-2b1b6222011b)
T Device">

   <p><strong>Azure SQL Database</strong></p>
    <img src="path_to_image_3" alt="Azure SQL Data![Screenshot 2024-06-04 143200](https://github.com/Savan2110/IoT-Real-Time-Data-Project-using-Azure/assets/51812887/8d43ebf0-045d-4c4d-9ce6-e864547fb37e)
base">![Screenshot 2024-06-04 143244](https://github.com/Savan2110/IoT-Real-Time-Data-Project-using-Azure/assets/51812887/be8a9957-d5c8-43db-bd5f-b0962bca0186)


  <h2>Conclusion</h2>
    <p>
        This project showcases the integration of multiple Azure services to build a scalable and efficient IoT data processing pipeline. By using Azure IoT Hub, Stream Analytics, SQL Database, and Power BI, real-time data from IoT devices can be ingested, processed, stored, and visualized effectively. This setup can be extended to accommodate various IoT applications, providing valuable insights and analytics from the collected data.
    </p>
