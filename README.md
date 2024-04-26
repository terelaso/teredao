# Teredao

**[Documentation](https://github.com/terelaso/teredao)**
**·**

## Why this library?

Although there are existing libraries (e.g. praw) to interact with Reddit developer's API,
there are still several drawbacks when we trying to collect vast amount of data.
**teredao** tries to counter these problems to provide these features:

- No authentication (API key) is needed to access the data.
- Extra attributes is presented using the Reddit webAPI compared to the public devAPI.
- Fully Async based.
- Proxy support via [httpx](https://www.python-httpx.org/advanced/#http-proxying).
