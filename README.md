# The Significance of Union and Intersection Types in TypeScript

TypeScript brings type-safety to JavaScript, allowing developers to catch errors at compile time. Two powerful tools within TypeScript that improve its flexibility and expressiveness are **Union** and **Intersection Types**. These types help model complex data structures and real-world scenarios with precision, making TypeScript code more resilient and maintainable.

---

## What Are Union Types?

Union types allow a variable to hold multiple types, providing flexibility without sacrificing type safety. By using a union, you can specify that a variable can be of one type or another, making it possible to manage different possible values effectively.

### Example

```typescript
let response: string | number;
response = "Success"; // Valid
response = 200;       // Also valid
```
