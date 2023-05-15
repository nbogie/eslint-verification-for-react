# eslint-found issues

### Important (lint):

`/Users/neill/Developer/Academy/codinggarden-react-ts-starter/src/MyComponent.tsx`

```text
13:6   error    React Hook useEffect has a missing dependency: 'foo'. Either include it or remove the dependency array  react-hooks/exhaustive-deps
```

# Unimportant (lint):

```text
   6:1   error    Prefer default export on a file with single export                                                      import/prefer-default-export
   8:5   warning  Unexpected console statement                                                                            no-console
   8:17  error    Must use destructuring props assignment                                                                 react/destructuring-assignment
   9:5   warning  Unexpected console statement                                                                            no-console  15:44  error    Must use destructuring props assignment                                                                 react/destructuring-assignment
```

### Type-checking failures:

`App.tsx`

    "message": "Property 'stuff' is missing in type '{}' but required in type 'MyComponentProps'.",
