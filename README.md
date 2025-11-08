# 📋 Manual API Testing Projects

**Author:** Anuj Rajput  
**Repository Name:** ManualAPITestingProjects  
**Testing Tools:** Postman, Newman, Excel  
**Documentation:** Test Plans, Test Cases, Collections  

---

## 📘 Overview

This repository contains a comprehensive collection of **Manual API Testing Projects** covering various API types including **SOAP APIs**, **REST APIs**, and advanced testing concepts. Each project includes complete testing documentation with **Test Plans**, **Test Cases**, **Postman Collections**, and **Environment configurations**.

The repository serves as a complete guide for manual API testing practices, covering real-world testing scenarios across different domains and API architectures.

---

## 🚀 Testing Tools & Technologies

| Technology | Description |
|------------|-------------|
| **Postman** | API testing platform for manual and automated testing |
| **Newman** | Command-line collection runner for Postman |
| **SOAP API** | Testing SOAP-based web services |
| **REST API** | Testing RESTful web services |
| **Excel** | Test case management and documentation |
| **Word** | Test plan documentation |
| **JSON** | Data format for requests and responses |
| **Environment Variables** | Multi-environment testing configurations |

---

## 📚 Projects Overview

### 🔹 Project 1 – Number to Words (SOAP API)
- **API Type**: SOAP
- **Collections**: `NumberToWordsValidations.postman_collection.json`
- **Test Cases**: `NumberToWords_TestCases.xlsx`
- **Test Plan**: `NumberToWords_TestPlan.docx`
- **Focus**: SOAP API validation and testing

### 🔹 Project 2 – Currency ISO Code Lookup (SOAP API)
- **API Type**: SOAP
- **Collections**: `ISOCodeCurrencyValidations.postman_collection.json`
- **Focus**: Currency code validation and SOAP testing

### 🔹 Project 3 – Book ISBN Lookup (SOAP API)
- **API Type**: SOAP
- **Collections**: `BooksISBNValidations.postman_collection.json`
- **Focus**: ISBN validation and book data testing

### 🔹 Project 4 – Restful Booker (REST API)
- **API Type**: REST
- **Collections**: `RestfulBooker.postman_collection.json`
- **Test Cases**: `RestfulBooker_TestCases.xlsx`
- **Test Plan**: `RestfulBooker_TestPlan.docx`
- **Newman**: Command-line execution support
- **Focus**: Complete REST API testing

### 🔹 Project 5 – Imgur API (REST API)
- **API Type**: REST
- **Collections**: `ImgurAPI.postman_collection.json`
- **Focus**: Image hosting API testing

### 🔹 Project 6 – Restful Booker (REST API) ENV
- **API Type**: REST
- **Collections**: `Project 6 - Restful Booker (REST API) ENV.postman_collection.json`
- **Environments**: `Dev.postman_environment.json`, `QA.postman_environment.json`, `Prod.postman_environment.json`
- **Test Cases**: `RestfulBooker_TestCases.xlsx`
- **Test Plan**: `RestfulBooker_TestPlan.docx`
- **Focus**: Multi-environment testing

### 🔹 Project 7 – Test Cases - Restful Booker (REST API)
- **API Type**: REST
- **Collections**: Dedicated test case implementation
- **Environment**: `Prod.postman_environment.json`
- **Test Cases**: `RestfulBooker_TestCases.xlsx`
- **Test Plan**: `RestfulBooker_TestPlan.docx`
- **Focus**: Comprehensive test case development

### 🔹 Project 8 – CRUD Operation - Restful Booker (REST API)
- **API Type**: REST
- **Collections**: CRUD operations focused
- **Environment**: `Prod.postman_environment.json`
- **Test Cases**: `RestfulBooker_TestCases.xlsx`
- **Test Plan**: `RestfulBooker_TestPlan.docx`
- **Focus**: Create, Read, Update, Delete operations

### 🔹 Project 9 – MockAPI - Restful booker - By CMD
- **API Type**: REST (Mock API)
- **Collections**: `Project 9 MockAPI - Restful booker - By CMD.postman_collection.json`
- **Environment**: `Prod.postman_environment.json`
- **Test Cases**: `RestfulBooker_TestCases.xlsx`
- **Test Plan**: `RestfulBooker_TestPlan.docx`
- **Focus**: Mock API testing and command-line execution

### 🔹 Project 10 – FakeAPI - Restful booker - By Postman
- **API Type**: REST (Fake API)
- **Collections**: `Project 10 FakeAPI - Restful booker - By Postman.postman_collection.json`
- **Environment**: `FakeENV.postman_environment.json`
- **Test Cases**: `RestfulBooker_TestCases.xlsx`
- **Test Plan**: `RestfulBooker_TestPlan.docx`
- **Newman**: Command-line execution support
- **Focus**: Fake API testing with Postman

### 🔹 Project 11 – DataDrivenTesting - app.vwo.com
- **API Type**: REST
- **Collections**: `Project 11 - DataDrivenTesting - app.vwo.com.postman_collection.json`
- **Test Data**: Separate test data management
- **Focus**: Data-driven testing approaches

### 🔹 Project 12 – JSON Schema Validation
- **API Type**: REST
- **Collections**: JSON schema validation focused
- **Focus**: Response validation using JSON schemas

### 🔹 Project 13 – OAuth2
- **API Type**: REST
- **Collections**: `Project 13 - OAuth2.postman_collection.json`
- **Focus**: OAuth2 authentication testing

---

# 🧩 Testing Concepts Covered

| Category | Specific Concepts |
|----------|-------------------|
| **🏗 API Types** | SOAP APIs, REST APIs, Mock APIs, Fake APIs |
| **🔧 HTTP Methods** | GET, POST, PUT, PATCH, DELETE operations |
| **⚙️ Environment** | Multi-environment testing (Dev, QA, Prod) |
| **🧪 Testing Types** | Functional, Data-Driven, Schema Validation, OAuth2 |
| **📊 Documentation** | Test Plans, Test Cases, Test Data management |
| **🔨 Automation** | Newman for command-line execution |
| **🔐 Security** | OAuth2 authentication testing |

---

## 🛠 Tools & Setup

### Required Tools
- **Postman**: API testing platform
- **Newman**: Command-line collection runner
- **Excel**: Test case management
- **Word**: Test plan documentation

### Running Collections with Newman
```bash
# Install Newman globally
npm install -g newman

# Run a collection
newman run "Project 4 - Restful Booker/RestfulBooker.postman_collection.json"

# Run with environment
newman run "collection.json" -e "environment.json"

# Run with reporters
newman run "collection.json" -r htmlextra,json

# 📊 Documentation Structure

Each major project includes:

---

## 📋 **Test Plan Document**

- **Testing objectives and scope**  
- **Test strategy and approach**  
- **Resource requirements**  
- **Schedule and deliverables**  
- **Risk assessment**

---

## 📝 **Test Cases (Excel)**

- **Test case ID and description**  
- **Preconditions and test steps**  
- **Expected vs actual results**  
- **Test data requirements**  
- **Pass/fail status tracking**

---

## 🔄 **Postman Collections**

- **Organized API requests**  
- **Test scripts and assertions**  
- **Environment variables**  
- **Pre-request scripts**  
- **Collection-level variables**

---

## 🌍 **Environment Configurations**

- **Base URLs and endpoints**  
- **Authentication tokens**  
- **Environment-specific variables**  
- **Headers and parameters**

---

## 🎯 **Learning Path**

- **Start with SOAP APIs** → Projects 1–3 for SOAP web services  
- **Move to REST Basics** → Project 4 for fundamental REST API testing  
- **Environment Testing** → Project 6 for multi-environment setups  
- **Advanced Concepts** → Projects 7–8 for comprehensive testing  
- **Mock & Fake APIs** → Projects 9–10 for simulated environments  
- **Specialized Testing** → Projects 11–13 for data-driven, schema, and OAuth2 testing

---

## 🤝 **Contributing**

Contributions are welcome!  
Please feel free to submit pull requests or open issues for improvements in test cases, collections, or documentation.

---

## 📜 **License**

This project is licensed under the **MIT License**.

---

## 📞 **Contact**

**Author:** Anuj Rajput  
**GitHub:** [AutomateWithAnuj](https://github.com/AutomateWithAnuj)  
**Repository:** ManualAPITestingProjects


## 🗂 Complete Folder Structure

```text
ManualAPITestingProjects/
│
├── 📁 Project 1 – Number to Words (SOAP API)/
│   ├── 📁 Collections/
│   │   └── NumberToWordsValidations.postman_collection.json
│   ├── 📁 Test-Cases/
│   │   └── NumberToWords_TestCases.xlsx
│   └── 📁 Test-Plan/
│       └── NumberToWords_TestPlan.docx
│
├── 📁 Project 2 – Currency ISO Code Lookup (SOAP API)/
│   └── 📁 Collections/
│       └── ISOCodeCurrencyValidations.postman_collection.json
│
├── 📁 Project 3 – Book ISBN Lookup (SOAP API)/
│   └── 📁 Collections/
│       └── BooksISBNValidations.postman_collection.json
│
├── 📁 Project 4 - Restful Booker (REST API)/
│   ├── 📁 Collections/
│   │   ├── 📁 newman/
│   │   └── RestfulBooker.postman_collection.json
│   ├── 📁 Test-Cases/
│   │   └── RestfulBooker_TestCases.xlsx
│   └── 📁 Test-Plan/
│       └── RestfulBooker_TestPlan.docx
│
├── 📁 Project 5 - Imgur API (REST API)/
│   └── 📁 Collections/
│       └── ImgurAPI.postman_collection.json
│
├── 📁 Project 6 - Restful Booker (REST API) ENV/
│   ├── 📁 Collections/
│   │   └── 📁 newman/
│   ├── Project 6 - Restful Booker (REST API) ENV.postman_collection.json
│   ├── Dev.postman_environment.json
│   ├── QA.postman_environment.json
│   ├── Prod.postman_environment.json
│   ├── 📁 Test-Cases/
│   │   └── RestfulBooker_TestCases.xlsx
│   └── 📁 Test-Plan/
│       └── RestfulBooker_TestPlan.docx
│
├── 📁 Project 7 - Test Cases - Restful Booker (REST API)/
│   ├── 📁 Collections/
│   │   └── 📁 newman/
│   ├── Prod.postman_environment.json
│   ├── 📁 Test-Cases/
│   │   └── RestfulBooker_TestCases.xlsx
│   └── 📁 Test-Plan/
│       └── RestfulBooker_TestPlan.docx
│
├── 📁 Project 8 - CRUD Operation - Restful Booker (REST API)/
│   ├── 📁 Collections/
│   │   └── 📁 newman/
│   ├── Prod.postman_environment.json
│   ├── 📁 Test-Cases/
│   │   └── RestfulBooker_TestCases.xlsx
│   └── 📁 Test-Plan/
│       └── RestfulBooker_TestPlan.docx
│
├── 📁 Project 9 MockAPI - Restful booker - By CMD/
│   ├── 📁 Collections/
│   │   └── 📁 newman/
│   ├── Project 9 MockAPI - Restful booker - By CMD.postman_collection.json
│   ├── Prod.postman_environment.json
│   ├── 📁 Test-Cases/
│   │   └── RestfulBooker_TestCases.xlsx
│   └── 📁 Test-Plan/
│       └── RestfulBooker_TestPlan.docx
│
├── 📁 Project 10 FakeAPI - Restful booker - By Postman/
│   ├── 📁 Collections/
│   │   └── 📁 newman/
│   ├── Project 10 FakeAPI - Restful booker - By Postman.postman_collection.json
│   ├── FakeENV.postman_environment.json
│   ├── 📁 Test-Cases/
│   │   └── RestfulBooker_TestCases.xlsx
│   └── 📁 Test-Plan/
│       └── RestfulBooker_TestPlan.docx
│
├── 📁 Project 11 - DataDrivenTesting - app.vwo.com/
│   ├── 📁 Collections/
│   ├── 📁 TestData/
│   └── Project 11 - DataDrivenTesting - app.vwo.com.postman_collection.json
│
├── 📁 Project 12 - JSON Schema Validation/
│   └── 📁 Collections/
│
├── 📁 Project 13 - OAuth2/
│   └── 📁 Collections/
│       └── Project 13 - OAuth2.postman_collection.json
│
├── README.md
└── .gitignore
