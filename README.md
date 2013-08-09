
# HALF

[HAL](http://stateless.co/hal_specification.html) + Forms

```js
{
  "_links": {
    "self": { "href": "http://example.com/xyz" },
    "next": { "href": "http://example.com/xyz?page=2" },
  },
  "_forms": {
    "href": "http://example.com/xyz", // could default to self
    "method": "POST",
    "fields": {
      { "name": "name", "required": true },
      { "name": "age" }
      { "name": "profession", "default": "docker" }
    }
  }
}
```

## Motivation

I need it.

Based on [HAL](http://stateless.co/hal_specification.html), inspired by [DocJSON](https://github.com/docjson/docjson).

Could work out of the box with existing HAL clients.

## License

same as HAL

