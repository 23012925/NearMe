# Ex04 Places Around Me
## Date: 07-04-2024

## AIM
To develop a website to display details about the places around my house.

## DESIGN STEPS

### STEP 1
Create a Django admin interface.

### STEP 2
Download your city map from Google.

### STEP 3
Using ```<map>``` tag name the map.

### STEP 4
Create clickable regions in the image using ```<area>``` tag.

### STEP 5
Write HTML programs for all the regions identified.

### STEP 6
Execute the programs and publish them.

## CODE

```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My City</title>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js" integrity="sha384-YvpcrYf0tY3lHB60NNkmXc5s9fDVZLESaAA55NDzOxhy9GkcIdslK1eN7N6jIeHz" crossorigin="anonymous"></script>

    
</head>
<script>
    function coord(event) {
        let x =event.clientX;
        let y =event.clientY;
        document.getElementById("txt1").value = x;
        document.getElementById("txt2").value = y;
    }
</script>
<body>
    <h1 align="center">
        <font color="red"><b>THANDALAM</b></font>
    </h1>
    <h3 align="center">
        <font color="blue"><b>JANARTHANAN K (212223040072)</b></font>
    </h3>
    <center>
    <img src="MAP.png" width="1000px" usemap="#MapNew" onmousemove="coord(event)">
    <MAP name="MapNew">
        <AREA shape="RECT" coords="72,72,154,104" href="https://apolloartsandsciencecollege.ac.in/"
            title="APOLLO ARTS AND SCIENCE">
        <AREA shape="RECT" coords="50,160,130,190" href="https://www.apollocollegeofpharmacy.ac.in/"
            title="APOLLO COLLEGE OF PHARMACY">
        <AREA shape="RECT" coords="590,30,690,60" href="http://www.apolloengineeringcollege.ac.in/"
            title="APOLLO ENGINEERING COLLEGE"> 
        <AREA shape="RECT" coords="530,150,600,180" href="https://apollocollegeofeducation.ac.in/"
            title="APOLLO COLLEGE OF EDUCTION">    
        <AREA shape="RECT" coords="590,440,680,460" href="https://www.scad.saveetha.com/"
            title="SAVEETHA COLLEGE OF ARCHITECTURE AND DESIGN">
        <AREA shape="RECT" coords="680,430,770,460" href="https://www.saveetha.com/"
            title="SAVEETHA DEEMED UNIVERSITY" > 
        <AREA shape="RECT" coords="830,410,910,440" href="https://www.saveetha.com/"
            title="SAVEETHA SCHOOL OF ENGINEERING">
        <AREA shape="RECT" coords="670,500,760,530" href="https://www.saveetha.ac.in/"
            title="SAVEETHA ENGINEERING COLLEGE"> 
        <AREA shape="RECT" coords="740,560,830,590" href="https://www.scahs-saveetha.com/"
            title="SAVEETHA COLLEGE OF ALLIED HEALTH SCIENCES">
        <AREA shape="RECT" coords="750,590,830,620" href="https://www.smc.saveetha.com/"
            title="SAVEETHA MEDICAL COLLEGE"> 
        <AREA shape="RECT" coords="550,530,630,560" href="https://www.scon.saveetha.com/"
            title="SAVEETHA COLLEGE OF NURSING">                      
    </MAP><br>
    </center>
    X coord : <input type="text" name="" id="txt1"><br>
    Y coord : <input type="text" name="" id="txt2">
</body>
</html>
```


## OUTPUT

![Output_ex no_4](https://github.com/23012925/NearMe/assets/150931013/b3c3e47e-0760-42bb-a667-fbaf53ee85e7)

![Apollo Arts and Science College](https://github.com/23012925/NearMe/assets/150931013/cb47e235-74f9-4578-b87f-0ca5dde80ec9)

![Apollo College of Pharmacy](https://github.com/23012925/NearMe/assets/150931013/f80c8f21-cecc-4ebd-ba8a-2543562845a9)

![Apollo Engineering College](https://github.com/23012925/NearMe/assets/150931013/bb09444a-ea6b-49ef-8988-922551b34941)

![Apollo College of Education](https://github.com/23012925/NearMe/assets/150931013/2124e520-8ddd-4f6f-8714-db08e88e79bd)

![Saveetha College of Architecture and Design](https://github.com/23012925/NearMe/assets/150931013/c601e2fc-7124-4858-ba13-50851c5a04df)

![Saveetha University](https://github.com/23012925/NearMe/assets/150931013/b01b7f81-e6cb-4c52-b029-8ca6707475b0)

![Saveetha Engineering College](https://github.com/23012925/NearMe/assets/150931013/d6134355-9c79-4726-84ed-4be54ad2732d)

![Saveetha College of Allied Health Sciences](https://github.com/23012925/NearMe/assets/150931013/301ac321-66e7-4c74-9d8e-6e12304ce4d6)

![Saveetha Medical College](https://github.com/23012925/NearMe/assets/150931013/d70bc62d-d095-4195-8190-dd8b945bdb0e)

![Saveetha College of Nursing](https://github.com/23012925/NearMe/assets/150931013/53420897-4d81-495e-98a8-e4a170fe9fe9)


## RESULT
The program for implementing image maps using HTML is executed successfully.
