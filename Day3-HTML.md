# HTML Nested Lists & Tables

## Nested Lists

- ul  :- Unordered list ( • , ◦)
- ol  :- Ordered List  (1. ,2. )

### Code

```html

<ul>
       
       <li>India<ul>
          <li>Delhi
            <ol>
              <li>Dwarka</li>
              <li>Noida</li>
            </ol>
          </li>
          <li>Mumbai
            <ol>
              <li>BKC</li>
              <li>Navi</li>
            </ol>
          </li>
       </ul></li>
       
       
       <li>USA<ul>
          <li>NewYork</li>
          <li>New Jersey</li>
       </ul></li>
       
     </ul>

```

### Output 

```bash
• India
  ◦ Delhi
      1. Dwarka
      2. Noida
  ◦ Mumbai
      1. BKC
      2. Navi
• USA
  ◦ NewYork
  ◦ New Jersey
```

## Table

- tr :- table row
- th :- table header
- td :- table default

### Code

```html

<table border="2">
      <thead>
        <tr>
            <th>Name</th>
            <th>Role</th>
        </tr>
      </thead>
      
      
      <tbody>
        <tr>
            <td>Avinash</td>
            <td>CEO</td>
        </tr>
        
        <tr>
            <td>Harshit</td>
            <td>CMO</td>
        </tr>
      </tbody>
      <tfoot>
        <tr>
          <td>Total</td>
          <td>2</td>
        </tr>
        
      </tfoot>
      
    </table>

```

### Output

```

|   Name     |     Role       |
|------------|----------------|
|  Avinash   |     CEO        |
|  Harshit   |     CMO        |
|------------|----------------|
|    Total   |     2          |


```























