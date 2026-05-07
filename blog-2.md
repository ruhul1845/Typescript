
### `blog-2.md`


# How Generics Help Build Reusable and Type-Safe Code in TypeScript

Instead of creating separate functions or classes for different data types, generics make it possible to write one reusable solution that works with multiple types.

Example :
function getValue<T>(value: T): T {
  return value;
}

---

## The Problem Without Generics

Without generics, developers often need to create multiple versions of the same function.

Example:
function getString(value: string): string {
  return value;
}

function getNumber(value: number): number {
  return value;
}
