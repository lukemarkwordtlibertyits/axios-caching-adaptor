# axios-caching-adaptor

```
await axios({
    method: "GET",
    url: { url },
    adapter: axiosCachingAdapter,
  })
    .then((res) => (response = res.data))
    .catch((err) => (error = err));
```
