# Linql.Client-Fetch

A linql client implementation that uses native fetch. 

[Linql Typescript Overview](https://github.com/LinqlLang/Linql.Typescript)

[Linql Language Overview](https://github.com/LinqlLang/Linql)



## Getting Started 

### Installation

```bash
npm i linql.client-fetch@^1.0.0-beta.1
```

Create a context, and then start using.

```typescript
import { FetchLinqlContext } from "linql.client-fetch";
import { LinqlSearch } from "linql.client";

const context = new FetchLinqlContext(LinqlSearch, "https://localhost:7113", { this: this });
const states = this.context.Set<State>(State);
const firstState = await states.FirstOrDefaultAsync();
```
