# aleph-error

```
$ aleph --version
aleph.js 0.3.0-alpha.22
deno 1.8.2
v8 9.0.257.3
typescript 4.2.2
```

# warning
```
Warning: useLayoutEffect does nothing on the server, because its effect cannot be encoded into the server renderer's output format. This will lead to a mismatch between the initial, non-hydrated UI and the intended UI. To avoid this, useLayoutEffect should only be used in components that render exclusively on the client. See https://reactjs.org/link/uselayouteffect-ssr for common fixes.
    at People (file:///Users/aadams/Projects/ms-email/.aleph/development/components/People.js#/components/People.tsx@1818f4:7:20)
    at main
    at App (file:///Users/aadams/Projects/ms-email/.aleph/development/app.js#543810:5:31)
Warning: useLayoutEffect does nothing on the server, because its effect cannot be encoded into the server renderer's output format. This will lead to a mismatch between the initial, non-hydrated UI and the intended UI. To avoid this, useLayoutEffect should only be used in components that render exclusively on the client. See https://reactjs.org/link/uselayouteffect-ssr for common fixes.
    at People (file:///Users/aadams/Projects/ms-email/.aleph/development/components/People.js#/components/People.tsx@1818f4:7:20)
    at main
    at App (file:///Users/aadams/Projects/ms-email/.aleph/development/app.js#543810:5:31)
```
# reference
https://github.com/alephjs/aleph.js/issues/221
