# Petful Server

[Live App](https://rb-petful.vercel.app/)

## Stack used:

Express and Node 

## API Documentation:

Base URL: https://damp-brushlands-31039.herokuapp.com

### GET /people

Returns an array of people.

---
### GET /pets/dogs

Returns the dog at the top of a queue to be adopted.

---

### GET /pets/cats

Returns the cat at the top of the queue to be adopted.

---

### DELETE /people

Dequeue person at the top.

---

### DELETE /pets/dogs

Dequeue dog at the top and return new top of queue.

---

### DELETE /pets/cats

Dequeue cat at the top and return new top of queue.

---

### POST /people

Add new person to the end of the queue. 