# 📘 Assignment: FastAPI REST APIs

## 🎯 Objective

Build a simple REST API with FastAPI to practice routing, request validation, and JSON responses.

## 📝 Tasks

### 🛠️	Design the API endpoints

#### Description
Define the core endpoints for a resource (e.g., tasks or books) and implement basic request/response models.

#### Requirements
Completed program should:

- Include at least 3 endpoints (GET all, GET by id, POST create)
- Use FastAPI path and query parameters appropriately
- Validate request bodies with Pydantic models


### 🛠️	Add update and delete operations

#### Description
Extend the API to support modifying and removing resources while handling missing items.

#### Requirements
Completed program should:

- Implement PUT or PATCH to update an existing item
- Implement DELETE to remove an item
- Return clear JSON error messages for missing ids
