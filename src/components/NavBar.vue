<template>
 <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css">
  <div id="navbar">
      <div id="brand">
        Pinayflix
      </div>
      
      <div id="main-nav">
        <img src="https://scontent.fceb1-1.fna.fbcdn.net/v/t39.30808-1/380767014_213809971706290_5084843887004841307_n.jpg?stp=dst-jpg_s200x200&_nc_cat=105&ccb=1-7&_nc_sid=fe8171&_nc_eui2=AeFMv20QYKW123DOGNVgYW0g5UjY0fo7Jp3lSNjR-jsmneHBGJ-595tdslW5I4qZPiF5dMJlUp7xQqoc3G9FWGJO&_nc_ohc=xuJIR9ySh3UAX8K6Zls&_nc_ht=scontent.fceb1-1.fna&oh=00_AfD_EwaLkYcHjlvXMPmK8EePSY8FX__NHfd8ZvEsfh6ThQ&oe=65194094" alt="profile">
      <a href="#">Logout</a>
      </div>

  </div>
  

</template>

<style scoped>
.sud {
  padding: 5px;
  background-color: white;
  border-radius: 10px;
}
#navbar {
    padding: 15px;
    background-color: rgb(13, 227, 181);
    display: flex;
    justify-content: space-between;
    align-items: center;
   
}
#main-nav {
    display: flex;
    align-items: center; /* Vertically center-align items */
}

#main-nav img {
    width: 45px;
    height: 45px;
    border-radius: 50%;
    margin-right: 10px;
}

#main-nav a {
    text-decoration: none;
    color: rgb(46, 7, 7);
    font-size: 20px;
}

.search {
   
    color: white;
    font-size: 20px;
    margin-bottom: 1px;
}


#brand {
   
    border: 4px solid white;
    background-color: white;
    border-radius: 5px; 
    margin-left: 20px;
    font-size: 30px;
    
    
}

.search input {
  padding: 9px;
  width: 250px;
  border-radius: 1px;
}

.search button {
  padding: 9px;
  border-radius: 1px;
  cursor: pointer;
}

.search button:hover {
  background: rgb(142, 212, 240);
  transition: 0.2s;
}
</style>