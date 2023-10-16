<h1 align="center">
  <b>RESTful API</b>
</h1>
<div align="center">

<p>Made with <b>Java 17</b>.</p>
</div>



<div align="center">
<img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white">
<img src="https://img.shields.io/badge/Spring-6DB33F?style=for-the-badge&logo=spring&logoColor=white">

<p></p>
</div>
<p align="center" >
Welcome to my <b>RESTful API</b>.</p>
<h2 align="center">Class Diagram</h2>

```mermaid
classDiagram
  class User {
    -String name
    -Account account
    -Feature[] features
    -Card card
    -News[] news
  }

  class Account {
    -String number
    -String agency
    -Number balance
    -Number limit
  }

  class Feature {
    -String icon
    -String description
  }

  class Card {
    -String number
    -Number limit
  }

  class News {
    -String icon
    -String description
  }

  User "1" *-- "1" Account
  User "1" *-- "N" Feature
  User "1" *-- "1" Card
  User "1" *-- "N" News

````
<p align="center">This project was made during <b>Digital Innovation One Java+Angular Bootcamp.</b>
</p>
<div align="center">
<img width="230px" align="right" src="https://static.vecteezy.com/system/resources/previews/023/363/877/original/orange-cat-feline-domestic-pet-animal-portrait-cute-png.png">
</div>

## 🔗 Connect with me!
[![Linkedin](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/nicole-musciacchio/) 
[![GitHub](https://img.shields.io/badge/GitHub-000?style=for-the-badge&logo=github&logoColor=30A3DC)](https://github.com/htpnia/)
<br>
<table>
  <tr>
    <td>
      <img width="80px" align="center" src="https://avatars.githubusercontent.com/htpnia"/>
    </td>
    <td align="left">
      <div>
        <b>Nicole Musciacchio</b>
      </div>
      Front-end developer
      <br>
    </td>
  </tr>
</table>