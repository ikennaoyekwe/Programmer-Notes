> **Get header, see if site is Up**
>
> ```bash
> xh -h https://www.bbc.com
> ```

> This is **Curl** :
>
> ```bash
> curl -X POST http://localhost:3000/api -H "Content-Type: application/json" -d '{"name": "John"}'
> ```
>
> Is This in **xh** :
>
> ```bash
> xh POST localhost:3000/api name=John job=Developer
> ```

> **Send a Number/Boolean (using `:=`):**
>
> ```bash
> xh POST localhost:3000/api isAdmin:=true age:=25
> ```

> **Send Object**
>
> ```bash
> xh POST localhost:3000/api user:='{"id": 1, "name": "John"}'
> ```

> **Send Auth Header**
>
> ```bash
> xh https://api.github.com/user Authorization:"Bearer YOUR_TOKEN"
> ```

> **Download a Page**
>
> ```bash
> xh https://www.bbc.com > bbc.html
> ```