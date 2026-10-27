# MuleSoft for Absolute Beginners

🚀 **MuleSoft Made Simple:** A step-by-step guide to MuleSoft integration, APIs, and DataWeave—written for beginners.

Welcome! Use the chapter links below to read the formatted Markdown lessons directly on GitHub.

## 📚 Learning Path

### Chapter 1: Introduction to MuleSoft
1. [**1.1 — Why MuleSoft?**](Chapter%201%3A%20Introduction%20to%20MuleSoft/1.1-Why-MuleSoft.md)  
   Understand why organizations integrate applications and how MuleSoft helps.
2. [**1.2 — Introduction to MuleSoft**](Chapter%201%3A%20Introduction%20to%20MuleSoft/1.2-Introduction-to-MuleSoft.md)  
   Learn the fundamentals of MuleSoft, Anypoint Platform, Mule applications, and runtime.

### Chapter 2: APIs and Connectivity
1. [**2.1 — APIs, REST, SOAP, and API-Led Connectivity**](Chapter%202%3A%20APIs%20and%20Connectivity/2.1-APIs-REST-SOAP-and-API-Led-Connectivity.md)  
   Explore API basics, compare REST and SOAP, and learn the System, Process, and Experience API layers.

### Chapter 3: Mule Flows
1. [**3.1 — Flow, Private Flow, and Subflow**](Chapter%203%3A%20Mule%20Flows/3.1-Flow-Private-Flow-and-Subflow.md)  
   Learn how a flow starts processing and how private flows and subflows reuse processing steps.

### Chapter 4: Setup and Installation
1. [**4.1 — Anypoint Studio Installation**](Chapter%204%3A%20Setup%20and%20Installation/4.1-Anypoint-Studio-Installation.md)  
   Install the MuleSoft development environment and verify it opens correctly.
2. [**4.2 — Postman Installation**](Chapter%204%3A%20Setup%20and%20Installation/4.2-Postman-Installation.md)  
   Install Postman and send a simple test request to confirm it works.

### Chapter 5: First Mule Application and HTTP Basics
1. [**5.1 — Basic Connectors and Components in Anypoint Studio**](Chapter%205%3A%20First%20Mule%20Application%20and%20HTTP%20Basics/5.1-Basic-Connectors-in-Anypoint-Studio.md)  
   Learn HTTP Listener, Logger, Set Variable, Set Payload, Transform Message, and HTTP Request.
2. [**5.2 — Understanding localhost, Port, and Path**](Chapter%205%3A%20First%20Mule%20Application%20and%20HTTP%20Basics/5.2-Localhost-Port-and-Path.md)  
   Understand the URL parts used to call a local Mule endpoint.
3. [**5.3 — HTTP Methods: GET, POST, PUT, PATCH, DELETE**](Chapter%205%3A%20First%20Mule%20Application%20and%20HTTP%20Basics/5.3-HTTP-Methods-GET-POST-PUT-PATCH-DELETE.md)  
   Learn common HTTP methods and how to try them in Postman.
4. [**5.4 — Build and Debug Your First Mule Application**](Chapter%205%3A%20First%20Mule%20Application%20and%20HTTP%20Basics/5.4-First-Mule-Application-Listener-Logger-Debug-Postman.md)  
   Build a Listener-and-Logger flow, run it, call it from Postman, and explore Studio debugging.

### Chapter 6: Connector Configuration Deep Dives
1. [**6.1 — HTTP Listener: Configuration Deep Dive**](Chapter%206%3A%20Connector%20Configuration%20Deep%20Dives/6.1-HTTP-Listener-Deep-Dive.md)  
   Configure Listener path, host, port, base path, methods, responses, and advanced options.
2. [**6.2 — Logger: Configuration Deep Dive**](Chapter%206%3A%20Connector%20Configuration%20Deep%20Dives/6.2-Logger-Deep-Dive.md)  
   Learn message expressions, log levels, categories, and safe logging practices.
3. [**6.3 — HTTP Request: Configuration Deep Dive**](Chapter%206%3A%20Connector%20Configuration%20Deep%20Dives/6.3-HTTP-Request-Deep-Dive.md)  
   Configure outbound HTTP calls, methods, paths, headers, query parameters, and responses.
4. [**6.4 — Transform Message: Configuration Deep Dive**](Chapter%206%3A%20Connector%20Configuration%20Deep%20Dives/6.4-Transform-Message-Deep-Dive.md)  
   Explore the DataWeave editor, input/output metadata, mappings, and previews.
5. [**6.5 — Set Variable: Configuration Deep Dive**](Chapter%206%3A%20Connector%20Configuration%20Deep%20Dives/6.5-Set-Variable-Deep-Dive.md)  
   Store and reuse values across a Mule event.
6. [**6.6 — Set Payload: Configuration Deep Dive**](Chapter%206%3A%20Connector%20Configuration%20Deep%20Dives/6.6-Set-Payload-Deep-Dive.md)  
   Set message payloads, expressions, MIME types, and encoding.

### Chapter 7: Hands-On Mule API Exercises

Build ten worked applications step by step using screenshot references, then complete a similar independent challenge at the end of each lesson. Screenshots are included only in the worked tutorials—not in the challenge prompts.

1. [**7.1 — Employee Greeting API**](Chapter%207%3A%20Hands-On%20Mule%20API%20Exercises/7.1-Employee-Greeting-API.md) — Listener, Set Variable, Set Payload, Logger.
2. [**7.2 — Query-Parameter Calculator**](Chapter%207%3A%20Hands-On%20Mule%20API%20Exercises/7.2-Query-Parameter-Calculator.md) — query parameters and DataWeave calculations.
3. [**7.3 — POST JSON Order API**](Chapter%207%3A%20Hands-On%20Mule%20API%20Exercises/7.3-POST-JSON-Order-API.md) — POST body, JSON transformation, variables, and logging.
4. [**7.4 — Employee Directory API**](Chapter%207%3A%20Hands-On%20Mule%20API%20Exercises/7.4-Employee-Directory-API.md) — URI parameters, query parameters, and lookup logic.
5. [**7.5 — Call an External API with HTTP Request**](Chapter%207%3A%20Hands-On%20Mule%20API%20Exercises/7.5-HTTP-Request-External-API.md) — outbound HTTP calls and response transformation.
6. [**7.6 — Order Enrichment with a Reusable Subflow**](Chapter%207%3A%20Hands-On%20Mule%20API%20Exercises/7.6-Order-Enrichment-Subflow.md) — Flow Reference, subflows, variables, and logging.
7. [**7.7 — GET, POST, PUT, and DELETE API**](Chapter%207%3A%20Hands-On%20Mule%20API%20Exercises/7.7-CRUD-Methods-API.md) — HTTP methods and CRUD-style routes.
8. [**7.8 — DataWeave Product Catalog**](Chapter%207%3A%20Hands-On%20Mule%20API%20Exercises/7.8-DataWeave-Product-Catalog.md) — arrays, map, calculations, and JSON output.
9. [**7.9 — Request Validation and Error Responses**](Chapter%207%3A%20Hands-On%20Mule%20API%20Exercises/7.9-Request-Validation-Errors.md) — validation, conditionals, and predictable responses.
10. [**7.10 — Customer Integration Capstone**](Chapter%207%3A%20Hands-On%20Mule%20API%20Exercises/7.10-Customer-Integration-Capstone.md) — combine inbound API, DataWeave, variables, logging, HTTP Request, and subflows.

### Chapter 8: Mule Events

1. [**8.1 — Event, Mule Event, and Mule 3 vs Mule 4 Events**](Chapter%208%3A%20Mule%20Events/8.1-Event-Mule-Event-Mule3-vs-Mule4-Event.md)  
   Learn what a Mule event contains, follow payload/attributes/variables through a flow, compare Mule 3 and Mule 4, and build a sample order API with a Mermaid diagram.

### Chapter 9: Routing and Parallel Processing

1. [**9.1 — Choice Router with Implementation**](Chapter%209%3A%20Routing%20and%20Parallel%20Processing/9.1-Choice-Router-with-Implementation.md)  
   Route an event based on ordered conditions and build a discount-category API.
2. [**9.2 — Scatter-Gather with Implementation**](Chapter%209%3A%20Routing%20and%20Parallel%20Processing/9.2-Scatter-Gather-with-Implementation.md)  
   Run independent routes in parallel and gather their results into a combined response.

### Chapter 10: Batch Processing

1. [**10.1 — Batch Processing in Mule 4**](Chapter%2010%3A%20Batch%20Processing/10.1-Batch-Processing.md)  
   Learn when to use a Batch Job, configure Batch Steps, and build a customer-import example using JSON records.
2. [**10.2 — Batch Execution Phases in Mule 4**](Chapter%2010%3A%20Batch%20Processing/10.2-Batch-Execution-Phases.md)  
   Explore Load and Dispatch, Process, and On Complete with official MuleSoft screenshots, diagrams, and a two-step customer-sync implementation.

### Chapter 11: Anypoint Platform

1. [**11.1 — Anypoint Platform: Complete Beginner's Guide**](Chapter%2011%3A%20Anypoint%20Platform/11.1-Anypoint-Platform-Complete-Guide.md)  
   Explore the platform architecture, control plane and runtime plane, Studio, Design Center, Exchange, API Manager, Runtime Manager, Access Management, Governance, Monitoring, MQ, Object Store, deployment options, CI/CD, and a practical deployment walkthrough.

### Chapter 12: Messaging and Communication Patterns

This chapter moves from communication fundamentals to messaging technology and then to production-style designs. Four subchapters are used so the topics build in the right order.

1. [**12.1 — Synchronous vs Asynchronous Communication and Orchestration**](Chapter%2012%3A%20Messaging%20and%20Communication%20Patterns/12.1-Synchronous-Asynchronous-Communication-and-Orchestration.md)  
   Learn request/response vs messaging, orchestration vs choreography, timeouts, retries, idempotency, and when to use each style.
2. [**12.2 — JMS, Queues, Topics, and Message Delivery**](Chapter%2012%3A%20Messaging%20and%20Communication%20Patterns/12.2-JMS-Messaging-Queues-Topics-and-Delivery.md)  
   Understand JMS, producers and consumers, point-to-point queues, publish-subscribe topics, acknowledgements, delivery semantics, retries, and dead-letter queues.
3. [**12.3 — Message Brokers, ActiveMQ, and Anypoint MQ**](Chapter%2012%3A%20Messaging%20and%20Communication%20Patterns/12.3-Message-Brokers-ActiveMQ-and-Anypoint-MQ.md)  
   Learn what a broker does, distinguish ActiveMQ Classic and Artemis, compare self-managed ActiveMQ with managed Anypoint MQ, and choose the correct Mule connector.
4. [**12.4 — Real-World Messaging Patterns and Capstone**](Chapter%2012%3A%20Messaging%20and%20Communication%20Patterns/12.4-Real-World-Messaging-Patterns-and-Capstone.md)  
   Apply the concepts to e-commerce, payment/inventory, banking alerts, healthcare reminders, and background imports, then design an end-to-end order-processing integration.

### Chapter 13: Error Handling in Mule 4

A practical, implementation-focused chapter built around a memorable decision process: **Find the failure → Handle it at the right scope → Recover or Propagate → Respond and Record**.

1. [**13.1 — Error Handling Fundamentals and Mule Errors**](Chapter%2013%3A%20Error%20Handling%20in%20Mule%204/13.1-Error-Handling-Fundamentals-and-Mule-Errors.md)  
   Learn error types, handler scope, On Error Continue vs On Error Propagate, common error categories, and a simple decision tree.
2. [**13.2 — Hands-On: Implement On-Error-Continue and On-Error-Propagate**](Chapter%2013%3A%20Error%20Handling%20in%20Mule%204/13.2-Implementing-On-Error-Continue-and-Propagate.md)  
   Build and test a `GET /orders/{orderId}` example with success, not-found, and simulated-failure paths, plus HTTP status configuration and curl tests.
3. [**13.3 — Try Scope, Error Types, and Choosing the Right Handler**](Chapter%2013%3A%20Error%20Handling%20in%20Mule%204/13.3-Try-Scope-Error-Types-and-Error-Handling-Strategy.md)  
   Handle optional enrichment locally, let required operations fail honestly, and learn why payment timeouts need special care.
4. [**13.4 — Retries, Transactions, and Production Error Handling**](Chapter%2013%3A%20Error%20Handling%20in%20Mule%204/13.4-Retries-Transactions-and-Production-Error-Handling.md)  
   Learn safe retries, message redelivery, transactions, the transactional outbox pattern, secure logging, observability, and failure-path testing.

### Chapter 14: Salesforce Platform Events with MuleSoft

Learn event-driven integration step by step: understand Salesforce Platform Events, define and publish an event, subscribe from Mule 4, and build an end-to-end integration.

1. [**14.1 — Platform Events: Fundamentals and Architecture**](Chapter%2014%3A%20Salesforce%20Platform%20Events%20with%20MuleSoft/14.1-Platform-Events-Fundamentals-and-Architecture.md)  
   Understand publishers, subscribers, Salesforce Event Bus, Platform Events vs Change Data Capture (CDC), publish behavior, replay, and real-time use cases.
2. [**14.2 — Hands-On: Create and Publish a Salesforce Platform Event**](Chapter%2014%3A%20Salesforce%20Platform%20Events%20with%20MuleSoft/14.2-Create-and-Publish-a-Salesforce-Platform-Event.md)  
   Create `Order_Placed__e`, define fields, choose publish behavior, and publish a test event through Flow Builder or Apex.
3. [**14.3 — Hands-On: Subscribe to Salesforce Platform Events from Mule 4**](Chapter%2014%3A%20Salesforce%20Platform%20Events%20with%20MuleSoft/14.3-Subscribe-to-Platform-Events-from-Mule-4.md)  
   Configure a Salesforce Replay Channel Listener, receive events in Mule, inspect and transform the payload, and troubleshoot the subscription.
4. [**14.4 — Publish Platform Events from Mule and Build an End-to-End Integration**](Chapter%2014%3A%20Salesforce%20Platform%20Events%20with%20MuleSoft/14.4-Publish-Platform-Events-from-Mule-and-End-to-End-Use-Cases.md)  
   Publish `Shipment_Dispatched__e` from Mule, connect both directions, compare Platform Events with Anypoint MQ, and complete a capstone.

### Chapter 14: Salesforce Platform Events with MuleSoft

Learn Salesforce event-driven integration in the order that makes implementation easiest: concepts, publishing, subscribing from Mule, then production reliability.

1. [**14.1 — Salesforce Platform Events: Fundamentals**](Chapter%2014%3A%20Salesforce%20Platform%20Events%20with%20MuleSoft/14.1-Salesforce-Platform-Events-Fundamentals.md)  
   Understand publishers, subscribers, event bus, channels, Publish After Commit, and the difference between Platform Events and Change Data Capture (CDC).
2. [**14.2 — Create and Publish a Salesforce Platform Event**](Chapter%2014%3A%20Salesforce%20Platform%20Events%20with%20MuleSoft/14.2-Create-and-Publish-a-Salesforce-Platform-Event.md)  
   Define Order_Ready__e, add custom fields, publish a test message with Apex or Flow, and understand the event channel.
3. [**14.3 — Subscribe to Platform Events from MuleSoft**](Chapter%2014%3A%20Salesforce%20Platform%20Events%20with%20MuleSoft/14.3-Subscribe-to-Platform-Events-from-MuleSoft.md)  
   Build a Mule 4 subscriber using the appropriate Salesforce Connector or Salesforce Pub/Sub Connector, inspect the payload, transform it, and call a downstream API.
4. [**14.4 — Publish Platform Events from Mule and Production Patterns**](Chapter%2014%3A%20Salesforce%20Platform%20Events%20with%20MuleSoft/14.4-Publish-Platform-Events-from-Mule-and-Production-Patterns.md)  
   Learn the reverse direction, implement an inventory alert architecture, and plan for replay, duplicate delivery, errors, security, and monitoring.


### Chapter 15: RAML API Design and Implementation

Learn RAML 1.0 from fundamentals through types, reusable patterns, security, mock APIs, APIkit implementation, testing, and production governance.

1. [**15.1 — RAML Fundamentals and API Design**](Chapter%2015%3A%20RAML%20API%20Design%20and%20Implementation/15.1-RAML-Fundamentals-and-API-Design.md)  
   Understand API contracts, RAML vs YAML/OpenAPI/DataWeave, resources, methods, parameters, responses, and design checklists.
2. [**15.2 — RAML Data Types, Parameters, Examples, and Validation**](Chapter%2015%3A%20RAML%20API%20Design%20and%20Implementation/15.2-RAML-DataTypes-Parameters-Examples-and-Validation.md)  
   Model request/response bodies, optional properties, constraints, named examples, headers, and parameters.
3. [**15.3 — Reuse, Traits, Resource Types, Libraries, and Security**](Chapter%2015%3A%20RAML%20API%20Design%20and%20Implementation/15.3-RAML-Reuse-Traits-ResourceTypes-Libraries-and-Security.md)  
   Refactor repetitive contracts, use fragments and libraries, and describe security without confusing contract declarations with runtime enforcement.
4. [**15.4 — Hands-On: Design and Mock a Bookstore API**](Chapter%2015%3A%20RAML%20API%20Design%20and%20Implementation/15.4-Hands-On-RAML-Bookstore-API-Design-and-Mocking.md)  
   Create a Bookstore API contract, review behavior, and try mock requests.
5. [**15.5 — Implement RAML with APIkit in Mule 4**](Chapter%2015%3A%20RAML%20API%20Design%20and%20Implementation/15.5-Implement-RAML-with-APIkit-in-Mule-4.md)  
   Scaffold Mule flows, implement operations, test using Postman/curl, and troubleshoot.
6. [**15.6 — RAML to Production: Versioning, Governance, and Troubleshooting**](Chapter%2015%3A%20RAML%20API%20Design%20and%20Implementation/15.6-RAML-to-Production-Governance-Versioning-and-Troubleshooting.md)  
   Cover contract evolution, CI/CD quality gates, security, observability, interview questions, and a capstone.
7. [**Bookstore API starter contract (RAML 1.0)**](Chapter%2015%3A%20RAML%20API%20Design%20and%20Implementation/bookstore-api.raml)  
   A companion practice file. Validate with your RAML editor/parser and adapt the placeholder host before using it.

### Chapter 16: DataWeave

A comprehensive, implementation-focused DataWeave course covering language fundamentals, types, coercion, null handling, selectors, functions, collections, strings, dates, object reshaping, error-aware mappings, modules, performance, Mule flow usage, and testing. Includes **24 worked examples** and **30 independent implementation problems**.

1. [**16.0 — DataWeave Intermediate Learning Path**](Chapter%2016%3A%20DataWeave/16.0-README-DataWeave-Intermediate-Learning-Path.md) — course roadmap, outcomes, and official references.
2. [**16.1 — Fundamentals, Syntax, and Execution**](Chapter%2016%3A%20DataWeave/16.1-DataWeave-Fundamentals-Syntax-and-Execution.md) — script structure, directives, expressions, formats, and Mule event data.
3. [**16.2 — Types, Coercion, Null, and Defaults**](Chapter%2016%3A%20DataWeave/16.2-DataWeave-Types-Coercion-Null-and-Defaults.md) — type declarations, casts, missing vs null, safe navigation, and money handling.
4. [**16.3 — Selectors, Arrays, Objects, and Paths**](Chapter%2016%3A%20DataWeave/16.3-DataWeave-Selectors-Arrays-Objects-and-Paths.md) — key/index/descendant selectors, nested paths, and dynamic keys.
5. [**16.4 — Functions, Lambdas, Variables, and Scope**](Chapter%2016%3A%20DataWeave/16.4-DataWeave-Functions-Lambdas-Variables-and-Scope.md) — reusable functions, lambdas, local scope, and composition.
6. [**16.5 — Collection Functions and Data Reshaping**](Chapter%2016%3A%20DataWeave/16.5-DataWeave-Collection-Functions-and-Data-Reshaping.md) — map, filter, flatMap, flatten, reduce, groupBy, orderBy, distinctBy, pluck, and object functions.
7. [**16.6 — Strings, Numbers, Dates, and Formatting**](Chapter%2016%3A%20DataWeave/16.6-DataWeave-Strings-Numbers-Dates-and-Formatting.md) — normalization, parsing, regex concepts, numeric precision, and timezone-aware dates.
8. [**16.7 — Objects, Flattening, and Dynamic Keys**](Chapter%2016%3A%20DataWeave/16.7-DataWeave-Objects-Flattening-and-Dynamic-Keys.md) — conditional fields, object merging, nested arrays, XML namespaces, and CSV output.
9. [**16.8 — Conditions, Pattern Matching, and Robust Mappings**](Chapter%2016%3A%20DataWeave/16.8-DataWeave-Conditions-Pattern-Matching-and-Robust-Mappings.md) — business rules, match expressions, validation, and error strategy.
10. [**16.9 — Multi-Input, Modules, Reuse, and Performance**](Chapter%2016%3A%20DataWeave/16.9-DataWeave-Multi-Input-Modules-Reuse-and-Performance.md) — read(), reusable modules, lookup data, streaming considerations, and optimization.
11. [**16.10 — DataWeave in Mule Flows and Testing**](Chapter%2016%3A%20DataWeave/16.10-DataWeave-in-Mule-Flows-and-Testing.md) — Transform Message, Set Payload, Set Variable, MUnit, and troubleshooting.
12. [**16.11 — 24 Worked DataWeave Practice Examples**](Chapter%2016%3A%20DataWeave/16.11-DataWeave-24-Worked-Practice-Examples.md) — 24 scripts to run, inspect, modify, and test.
13. [**16.12 — 30 Independent Implementation Problems**](Chapter%2016%3A%20DataWeave/16.12-DataWeave-30-Implementation-Problems.md) — 30 progressively harder tasks with acceptance criteria and a scoring rubric.

### Chapter 17: API-Led Connectivity

Build the same Customer 360 integration in two ways: one contract-first POC using RAML imported into Anypoint Studio with APIkit, and one manually implemented without RAML. Both POCs use System, Process, and Experience APIs as separate layers and include independent testing, end-to-end tests, troubleshooting, and implementation challenges.

1. [**17.0 — API-Led Connectivity: Two POCs Learning Path**](Chapter%2017%3A%20API-Led%20Connectivity/17.0-README-API-Led-Connectivity-Two-POCs.md) — overview, outcomes, project plan, and official references.
2. [**17.1 — Architecture and Lab Design**](Chapter%2017%3A%20API-Led%20Connectivity/17.1-API-Led-Connectivity-Architecture-and-Lab-Design.md) — responsibilities, request flow, sample contracts, local ports, and project layout.
3. [**17.2 — POC 1: Design the Experience API in RAML**](Chapter%2017%3A%20API-Led%20Connectivity/17.2-POC-1-Design-Experience-API-with-RAML.md) — create and validate a RAML 1.0 contract.
4. [**17.3 — POC 1: Import RAML into Anypoint Studio with APIkit**](Chapter%2017%3A%20API-Led%20Connectivity/17.3-POC-1-Import-RAML-into-Studio-with-APIkit.md) — scaffold API routing and implement the generated Experience API resource flow.
5. [**17.4 — POC 1: Implement All Three Layers**](Chapter%2017%3A%20API-Led%20Connectivity/17.4-POC-1-Implement-All-Three-Layers.md) — build System, Process, and Experience APIs and test the end-to-end request.
6. [**17.5 — POC 2: Build API-Led Connectivity Without RAML**](Chapter%2017%3A%20API-Led%20Connectivity/17.5-POC-2-API-Led-Without-RAML.md) — manually configure routes and mappings while preserving the same architecture.
7. [**17.6 — Test, Troubleshoot, and Compare Both POCs**](Chapter%2017%3A%20API-Led%20Connectivity/17.6-Test-Troubleshoot-and-Compare-Both-POCs.md) — test matrix, failure behavior, design trade-offs, and production considerations.
8. [**17.7 — Practice Set and Independent Challenges**](Chapter%2017%3A%20API-Led%20Connectivity/17.7-API-Led-Practice-and-Challenges.md) — 10 concept checks and 10 implementation challenges, plus a scoring rubric.


### Chapter 18: Data Transformation CSV JSON PDF and Binary: CSV, JSON, PDF, and Binary

A practical chapter on reading and writing structured data with DataWeave, configuring MIME types, converting CSV ↔ JSON, transforming files with the File Connector, returning CSV downloads, preserving PDF/octet-stream bytes, Base64 encoding/decoding, flow diagrams, testing, troubleshooting, and a capstone.

1. [**18.0 — Data Transformation Learning Path**](Chapter%2018%3A%20Data%20Transformation%20CSV%20JSON%20PDF%20and%20Binary/18.0-README-Data-Transformation-CSV-JSON-PDF-Binary.md) — roadmap, architecture diagrams, lab scope, and official references.
2. [**18.1 — Data Formats, MIME Types, and the Transformation Pipeline**](Chapter%2018%3A%20Data%20Transformation%20CSV%20JSON%20PDF%20and%20Binary/18.1-Data-Formats-MIME-Types-and-Transformation-Pipeline.md) — readers/writers, structured text vs binary, format metadata, and common mistakes.
3. [**18.2 — CSV to JSON: End-to-End HTTP API**](Chapter%2018%3A%20Data%20Transformation%20CSV%20JSON%20PDF%20and%20Binary/18.2-CSV-to-JSON-End-to-End-HTTP-API.md) — build a POST endpoint, configure the CSV reader, map records, type-convert safely, and test errors.
4. [**18.3 — JSON to CSV: End-to-End Download API**](Chapter%2018%3A%20Data%20Transformation%20CSV%20JSON%20PDF%20and%20Binary/18.3-JSON-to-CSV-End-to-End-Download-API.md) — select export fields, serialize CSV, set download headers, and test with curl.
5. [**18.4 — File Connector: Read CSV, Transform, and Write JSON**](Chapter%2018%3A%20Data%20Transformation%20CSV%20JSON%20PDF%20and%20Binary/18.4-File-Connector-CSV-to-JSON.md) — local file conversion, File Read/Write settings, and filesystem error handling.
6. [**18.5 — Binary, Octet-Stream, and PDF Handling**](Chapter%2018%3A%20Data%20Transformation%20CSV%20JSON%20PDF%20and%20Binary/18.5-Binary-Octet-Stream-and-PDF-Handling.md) — preserve bytes, return a PDF safely, distinguish pass-through from PDF parsing/generation, and address upload safety.
7. [**18.6 — Base64, Attachments, HTTP Headers, and Safe Binary Delivery**](Chapter%2018%3A%20Data%20Transformation%20CSV%20JSON%20PDF%20and%20Binary/18.6-Base64-Attachments-and-HTTP-Responses.md) — binary/Base64 distinction, decode/encode examples, multipart awareness, and response headers.
8. [**18.7 — Testing, Troubleshooting, and Studio Flow Snapshots**](Chapter%2018%3A%20Data%20Transformation%20CSV%20JSON%20PDF%20and%20Binary/18.7-Testing-Troubleshooting-and-Flow-Snapshots.md) — flow diagrams to recreate in Studio, test matrix, curl commands, and troubleshooting guide.
9. [**18.8 — Practice Questions, Mini Labs, and Capstone**](Chapter%2018%3A%20Data%20Transformation%20CSV%20JSON%20PDF%20and%20Binary/18.8-Practice-Questions-Mini-Labs-and-Capstone.md) — concept checks, DataWeave drills, five labs, Employee Export Service capstone, and a 100-point rubric.


### Chapter 19: Database Integration MySQL and CRUD POC

Learn how to configure a MySQL JDBC connection in Anypoint Studio, use the Database Connector operations, write parameterized SQL, map database results with DataWeave, handle errors/transactions, and build a complete Employee Management REST API backed by MySQL.

1. [**19.0 — Database Connector, MySQL, and CRUD POC Learning Path**](Chapter%2019%3A%20Database%20Integration%20MySQL%20and%20CRUD%20POC/19.0-README-Database-Connector-MySQL-and-CRUD-POC.md) — roadmap, operations, architecture, endpoints, and official references.
2. [**19.1 — Database Integration Fundamentals and Architecture**](Chapter%2019%3A%20Database%20Integration%20MySQL%20and%20CRUD%20POC/19.1-Database-Integration-Fundamentals-and-Architecture.md) — JDBC, global configuration vs operations, flow diagrams, and design principles.
3. [**19.2 — Install MySQL and Prepare the Database**](Chapter%2019%3A%20Database%20Integration%20MySQL%20and%20CRUD%20POC/19.2-Install-MySQL-and-Prepare-the-Database.md) — schema/table SQL, sample records, least-privilege user, and connection prerequisites.
4. [**19.3 — Configure MySQL Connection in Anypoint Studio**](Chapter%2019%3A%20Database%20Integration%20MySQL%20and%20CRUD%20POC/19.3-Configure-MySQL-Connection-in-Anypoint-Studio.md) — driver setup, MySQL Connection, secure properties, Test Connection, and troubleshooting.
5. [**19.4 — Database Connector Operations Reference**](Chapter%2019%3A%20Database%20Integration%20MySQL%20and%20CRUD%20POC/19.4-Database-Connector-Operations-Reference.md) — Select, Query Single, Insert, Update, Delete, bulk operations, stored procedures, DDL, scripts, source concepts, and transactions.
6. [**19.5 — SQL Parameters, DataWeave Mapping, and Error Handling**](Chapter%2019%3A%20Database%20Integration%20MySQL%20and%20CRUD%20POC/19.5-SQL-Parameters-DataWeave-and-Error-Handling.md) — safe input parameters, DB-to-API mapping, validation, SQL injection prevention, and error mapping.
7. [**19.6 — POC Part 1: Employee API — Create and Read**](Chapter%2019%3A%20Database%20Integration%20MySQL%20and%20CRUD%20POC/19.6-POC-Employee-API-Create-and-Read.md) — POST, list, and get-one endpoints with SQL and test requests.
8. [**19.7 — POC Part 2: Update, Delete, Search, and Bulk Import**](Chapter%2019%3A%20Database%20Integration%20MySQL%20and%20CRUD%20POC/19.7-POC-Update-Delete-Search-and-Bulk-Import.md) — update/delete/search, bulk insert, pagination challenge, and advanced operations.
9. [**19.8 — Transactions, Testing, Troubleshooting, and Flow Snapshots**](Chapter%2019%3A%20Database%20Integration%20MySQL%20and%20CRUD%20POC/19.8-Transactions-Testing-Troubleshooting-and-Flow-Snapshots.md) — transaction diagrams, test matrix, troubleshooting, and real Studio screenshot checklist.
10. [**19.9 — Practice Set, Interview Questions, and Capstone**](Chapter%2019%3A%20Database%20Integration%20MySQL%20and%20CRUD%20POC/19.9-Practice-Questions-and-Capstone.md) — implementation challenges, Employee Management API capstone, and 100-point scoring rubric.

## 🖼️ Diagram Assets

- [**API-Led Connectivity diagram (SVG)**](assets/api-led-connectivity.svg)

## 💡 Reading tip

Open the chapter links above—not the extensionless source files—to see rendered headings, lists, code formatting, and links in GitHub's reading view.


### Chapter 20 — Keystore, Truststore, TLS, and Mutual TLS in Mule 4

A complete learning path covering TLS fundamentals, X.509 certificates and chains, keystore vs truststore, JKS/PKCS12/PEM/DER, aliases and passwords, Java keytool, inbound HTTPS Listener, outbound HTTPS Requester, mutual TLS (mTLS), troubleshooting, certificate rotation, production security, diagrams, practice labs, and a capstone.

1. [**20.0 — Keystore and Truststore Learning Path**](Chapter%2020/20.0-README-Keystore-Truststore-TLS-Learning-Path.md) — roadmap, outcomes, architecture, and official references.
2. [**20.1 — TLS, Certificates, and the Trust Model**](Chapter%2020/20.1-TLS-Certificates-and-Trust-Model.md) — encryption, keys, certificate chains, TLS handshake, HTTPS, and mTLS.
3. [**20.2 — Keystore vs Truststore, Formats, Aliases, and Passwords**](Chapter%2020/20.2-Keystore-Truststore-Formats-Aliases-and-Passwords.md) — store contents, formats, aliases, passwords, and secure handling.
4. [**20.3 — Generate, Inspect, and Export Certificates with keytool**](Chapter%2020/20.3-Keytool-Generate-Inspect-and-Export-Certificates.md) — lab identity, public certificate export, truststore import, and inspection.
5. [**20.4 — Configure an Inbound HTTPS Listener**](Chapter%2020/20.4-Mule-Inbound-HTTPS-Listener.md) — server identity, TLS context, listener setup, and verification.
6. [**20.5 — Configure Outbound HTTPS with a Truststore**](Chapter%2020/20.5-Mule-Outbound-HTTPS-Truststore.md) — remote server trust, custom truststore, hostname verification, and errors.
7. [**20.6 — Mutual TLS (mTLS)**](Chapter%2020/20.6-Mutual-TLS-Mule-Client-and-Server-Certificates.md) — client certificates, two-way trust, and authorization.
8. [**20.7 — TLS Troubleshooting and Flow Snapshots**](Chapter%2020/20.7-TLS-Troubleshooting-and-Flow-Snapshots.md) — PKIX errors, SAN mismatch, expiry, key/password issues, and diagrams.
9. [**20.8 — Certificate Lifecycle and Production Security**](Chapter%2020/20.8-Certificate-Lifecycle-and-Production-Security.md) — rotation, secrets, least privilege, monitoring, and incident response.
10. [**20.9 — Practice, Labs, and Capstone**](Chapter%2020/20.9-Keystore-Truststore-Practice-and-Capstone.md) — hands-on labs, interview questions, rubric, and secure partner API capstone.

**Security reminder:** keep private keys, keystore files containing private keys, and passwords out of GitHub. Diagrams are schematic; capture actual Studio screenshots after running the labs. Verify version-sensitive XML against your installed Mule Runtime and HTTP Connector.
