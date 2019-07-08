# Code Drills

## Array Drills

#### Array Set 1
Consider this variable:

```javascript
const headphones = [
    {
        brand: 'Skullcandy',
        color: 'blue',
        wireless: true,
        price: 24.99
    },
    {
        brand: 'Skullcandy',
        color: 'black',
        wireless: false,
        price: 12.99
    },
    {
        brand: 'Bose',
        color: 'black',
        wireless: true,
        price: 149.99
    },
    {
        brand: 'AKG',
        color: 'black',
        wireless: false,
        price: 49.99
    },
    {
        brand: 'Sennheiser',
        color: 'black',
        wireless: false,
        price: 99.99
    },
    {
        brand: 'Philips',
        color: 'white',
        wireless: false,
        price: 10.99
    }
]
```

For each prompt, write a function that takes `headphones` as an argument and returns appropriate output.

- Write a function that returns the cheapest set.
- Write a function that returns the most expensive set.
- Write a function called `affordable` that returns all sets that cost less than `50`.
- Write a function called `wirelessSets` that returns all wireless headphones.
- Write a function called `wiredSets` that returns all wired headphones.