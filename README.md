# apollo-schemas

NoSQL Schemas for Apollo(n)

## Examples

### Simple Schema

```
{
  schema: 'car',
  car: {
    vendor: 'bmw',
    model: 'z4'
  }
}
```

### Schema as Object

```
{
  schema: {
    name: 'car'
  },
  car: {
    vendor: 'bmw',
    model: 'z4'
  }
}
```

### Schema with Version as Object

```
{
  schema: {
    name: 'car',
    version: '1'
  },
  
  car: {
    vendor: 'bmw',
    model: 'z4'
  }
}
```

### Timestamps

```
{
  createdAt: '',
  updatedAt: ''
}
```
