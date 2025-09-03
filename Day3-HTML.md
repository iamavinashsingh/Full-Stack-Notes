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
            <th>Column 1</th>
            <th>Column 2</th>
            <th>Column 3</th>
        </tr>
      </thead>
      
      
      <tbody>
        <tr >
            <td rowspan="2">Row 1 Col 1</td>
            <td>Row 1 Col 2</td>
            <td>Row 1 Col 3</td>
            
        </tr>
        
        <tr>
            
            <td>Row 2 Col 2</td>
            <td>Row 2 Col 3</td>
        </tr>
      </tbody>
      <tfoot>
        <tr >
          <td colspan='3'>Row 3 Col 1</td>
        </tr>
        
      </tfoot>
      
    </table>

```

### Output


|   Col 1    |    Col 2       |    Col 3       |
|------------|----------------|----------------|
| Row 1 Col 1| Row 1 col 2    |  Row 1 Col 3   |
|            | Row 2 col 2    |  Row 2 Col 3   |
|              Row 3 Col 1                     |


























