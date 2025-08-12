# Arrays Data Structure

Yeah, the most common data structure used in the world of programming. Like, everyone know how to use it, everyone knows how it works, they're perfection. Just a list, a group of elements order with an index. Useful for most of things.

# Video

Premise: _This is not an array_

```typescript
const a = [];
```

Array = Simple contigous memory space

Ok, ok, ok, this is heavy. The way ThePrimeagen shows how an array works it's a bit crazy for someone who just understand the superficial performance and not how it works indeed. Seeing the array as a contigous memory space it's a hard definition than just seeing it as a list. He shows how we can affect the spaces depending of the offset you use and bites. And the important thing and related to Big O notation is know that arrays have an `O(1)` time complexity to access to a memory space. Why? Because of: `a + width * offset`. Where:

- `a` is your address memory (people who use C++ before will understand better)
- `width` is the amount of bytes between each element like 4 bytes for an `int`
- `offset` the position you want to access

To understand better is like you have a street with mailboxes, so you want to know where is the 5 mailbox, you don't ask door by door where is. You just walk the amount of houses from the start to get there. So, you a or base or address is `a`, the distance between each mailbox is `width` and the mailbox you need to locate is `offset`.