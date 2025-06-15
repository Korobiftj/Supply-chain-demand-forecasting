# Supply-chain-demand-forecasting
📋 Project Overview
This project implements a comprehensive supply chain demand forecasting system using deep learning techniques. The system analyzes historical sales data, operational metrics, and logistics information to predict future product demand and optimize inventory management.
🎯 Key Features

Deep Learning Model: Neural network architecture for demand prediction
Comprehensive Analytics: Business intelligence dashboards and visualizations
Multi-dimensional Analysis: Product types, suppliers, carriers, and quality metrics
Interactive Visualizations: Plotly-based charts and graphs
Performance Metrics: Detailed model evaluation and business KPIs

🏗️ System Architecture
├── Data Preprocessing
│   ├── Missing Value Handling
│   ├── Feature Engineering
│   └── One-Hot Encoding
├── Neural Network Model
│   ├── Input Layer (15 features)
│   ├── Hidden Layers (128→64→32 neurons)
│   ├── Dropout Regularization
│   └── Linear Output Layer
├── Business Analytics
│   ├── Sales Performance Analysis
│   ├── Operational Efficiency Metrics
│   ├── Quality Control Assessment
│   └── Supplier Performance Ranking
└── Visualization Dashboard
    ├── Interactive Charts
    ├── Performance Metrics
    └── Trend Analysis
📊 Dataset Features
The system analyzes 24 key variables across 100 products:
CategoryFeaturesProduct InfoProduct type, SKU, Price, AvailabilitySales MetricsNumber of products sold, Revenue generatedInventoryStock levels, Order quantitiesLogisticsLead times, Shipping times, Carriers, CostsOperationsManufacturing costs, Production volumesQualityDefect rates, Inspection resultsSuppliersSupplier performance, Locations
