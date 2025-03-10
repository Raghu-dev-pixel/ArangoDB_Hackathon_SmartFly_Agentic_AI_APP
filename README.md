## **SmartFly – AI-Powered Flight & Airport Analytics Assistant**

SmartFly is an advanced Agentic AI application designed to simplify air travel through intelligent flight and airport analytics. It leverages cutting-edge technologies such as GraphRAG, ArangoDB, NetworkX, and Nvidia acceleration to provide users with insights on the best flight routes, airport connectivity, and network analysis—all through a simple chat interface.

## **Key Features**
Flight & Airport Queries
SmartFly can answer a wide range of flight and airport-related queries, helping users quickly retrieve essential information about flights, airports, and their connections.

Shortest Path Analysis
SmartFly analyzes and suggests the most efficient flight routes, considering factors like layovers, distance, and travel time.

Network Connectivity Insights
The application uses network analytics to provide insights into airline connections and airport network structures, helping both passengers and industry professionals make smarter travel decisions.

Chat-based Interface
Unlike traditional travel apps that require navigating complex menus, SmartFly offers a simple, user-friendly chat interface that lets users ask questions in natural language and get instant responses.

#Technological Stack
ArangoDB
SmartFly uses ArangoDB’s FLIGHTS dataset, optimized for graph analytics and GraphRAG tasks, to power data queries and analytics.

GraphRAG Approach
Leveraging Graph Retrieval-Augmented Generation (GraphRAG), SmartFly provides context-aware and accurate responses by integrating graph-based retrieval with AI, ensuring smarter decision-making and eliminating issues like hallucinations in responses.

NetworkX & Nvidia CuGraph
For more complex queries, SmartFly uses NetworkX and Nvidia CuGraph acceleration to run complex network algorithms that power flight and network connectivity analysis.

Hybrid Query Execution
SmartFly intelligently combines ArangoDB for simple queries and NetworkX for complex queries, splitting and executing them separately before merging the results to generate the final response.

ArangoSearch
The application also takes advantage of ArangoSearch for multimodal search capabilities, improving query understanding and the richness of insights.

## **Benefits of Using SmartFly**
Simplicity
SmartFly’s easy-to-use chat interface removes the need for complex filter settings, making it simple to get answers to your travel-related questions.

Advanced Intelligence
Unlike traditional flight search apps, SmartFly provides intelligent, graph-based insights that consider contextual relationships between entities, leading to more accurate and relevant results.

Better Performance
With the combination of ArangoDB, NetworkX, and Nvidia CuGraph, SmartFly can perform complex data analysis and real-time insights with optimal performance and speed.

Beyond Booking
While other apps focus on ticket bookings, SmartFly provides deeper insights into airport connectivity, alternate routes, and travel optimization, helping users make smarter decisions.

## **Future Improvements**
Real-Time Data Integration
Plan to integrate live flight updates for real-time recommendations and to keep the app more dynamic.

Multi-Language Support
Expand SmartFly to support multiple languages, increasing accessibility for international users.

Personalized Travel Insights
Develop a system that tailors recommendations based on user preferences and travel history.

## **Usage**
The application (smartFly_Final.ipynb) works on Google Colab, ensure a suitable GPU hardware is selected in the Runtime.

Note:- The demo of this application is available in the PPT "Hackathon_Demo.pptx" along with the detailed explanation as to how to connect to ArangoDB client and to set the view for ArangoSearch.

