# Ex04 Places Around Me

## DATE:19-10-2023

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

index.html:
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Map</title>
</head>
<body>
    <img src="Map.png" usemap="#image-map">

    <map name="image-map">
        <area target="_blank" alt="Chennai Central" title="Chennai Central" href="central.html" coords="962,331,1127,450" 
shape="rect">
        <area target="_blank" alt="Chennai Port" title="Chennai Port" href="port.html" coords="1762,307,1876,413" shape="rect">
        <area target="_blank" alt="Chennai Egmore " title="Chennai Egmore " href="egmore.html" coords="87,666,263,723" shape="rect">
        <area target="_blank" alt="Rajiv Gandhi Govt Hospital" title="Rajiv Gandhi Govt Hospital" href="hospital.html" coords="1031,487,1192,567" shape="rect">
        <area target="_blank" alt="Fort St. George Museum" title="Fort St. George Museum" href="fort.html" coords="1444,495,1647,597" shape="rect">
    </map>
</body>
</html>
```

central.html:
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Chennai Central</title>
    <style>
        h1{
            text-align: center;
            font-family: 'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;
            color:darkslategray;
        }
        p{
            text-align: justify;
            color:darkolivegreen;
            font-size: x-large;
            
        }
    </style>
</head>
<body>
    <h1>Puratchi Thalaivar Dr. M.G. Ramachandran Central Railway Station</h1>
    <br>
    <hr color="Brown">
    <p>Chennai Central, officially Puratchi Thalaivar Dr. M.G. Ramachandran Central Railway Station, and formerly known as Madras Central (station code: MAS), is the main railway terminus in the city of Chennai, Tamil Nadu, India. It is the busiest railway station in South India and one of the most important hubs in the country. It is connected to Moore Market Complex railway station, Chennai Central metro station, Chennai Park railway station, and Chennai Park Town railway station. It is about 1.8 km (1.1 mi) from the Chennai Egmore railway station. The terminus connects the city to northern India, including Kolkata, Mumbai, and New Delhi, and all the different parts of India.</p>

</body>
</html>
```

egmore.html:
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Chennai Egmore</title>
    <style>
        h1{
            text-align: center;
            font-family: 'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;
            color:darkslategray;
        }
        p{
            text-align: justify;
            color:darkolivegreen;
            font-size: x-large;
            
        }
    </style>
</head>
<body>
    <h1>Chennai Egmore Railway Station</h1>
    <br>
    <hr color="Brown">
    <p>Chennai Egmore, formerly known as Madras Egmore, also known as Chennai Elumbur (station code: MS), is a railway station in Chennai, Tamil Nadu, India. Situated in the neighborhood of Egmore, it is one of the four intercity railway terminals in the city; the other three are Chennai Central railway station, Tambaram railway station and Chennai Beach railway station. The station was built in 1906-1908 as the terminus of the South Indian Railway Company. The building built in Gothic style is one of the prominent landmarks of Chennai. The main entrance to the station is situated on Gandhi-Irwin Road and the rear entrance on Poonamallee High Road.</p>

</body>
</html>
```
fort.html:
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Fort St. George</title>
    <style>
        h1{
            text-align: center;
            font-family: 'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;
            color:darkslategray;
        }
        p{
            text-align: justify;
            color:darkolivegreen;
            font-size: x-large;
            
        }
    </style>
</head>
<body>
    <h1>Fort St. George, India</h1>
    <br>
    <hr color="Brown">
    <p>Fort St. George (or historically, White Town) is a fortress at the coastal city of Chennai, India. Founded in 1639, it was the first English (later British) fortress in India. The construction of the fort provided the impetus for further settlements and trading activity, in what was originally an uninhabited land. Thus, it is a feasible contention to say that the city (formerly named Madras) evolved around the fortress. The fort currently houses the Tamil Nadu legislative assembly and other official buildings.</p>

</body>
</html>
```
hospital.html:
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Hospital</title>
    <style>
        h1{
            text-align: center;
            font-family: 'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;
            color:darkslategray;
        }
        p{
            text-align: justify;
            color:darkolivegreen;
            font-size: x-large;
            
        }
    </style>
</head>
<body>
    <h1>Rajiv Gandhi Government General Hospital</h1>
    <br>
    <hr color="Brown">
    <p>Rajiv Gandhi Government General Hospital is a major state-owned hospital situated in Chennai, India. The hospital is funded and managed by the state government of Tamil Nadu. Founded in 1664 by the British East India Company, it is the first modern hospital in India. In the 19th century, the Madras Medical College joined it. As of 2018, the hospital receives an average of 12,000 outpatients every day.</p>

</body>
</html>
```
hospital.html:
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Hospital</title>
    <style>
        h1{
            text-align: center;
            font-family: 'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;
            color:darkslategray;
        }
        p{
            text-align: justify;
            color:darkolivegreen;
            font-size: x-large;
            
        }
    </style>
</head>
<body>
    <h1>Rajiv Gandhi Government General Hospital</h1>
    <br>
    <hr color="Brown">
    <p>Rajiv Gandhi Government General Hospital is a major state-owned hospital situated in Chennai, India. The hospital is funded and managed by the state government of Tamil Nadu. Founded in 1664 by the British East India Company, it is the first modern hospital in India. In the 19th century, the Madras Medical College joined it. As of 2018, the hospital receives an average of 12,000 outpatients every day.</p>

</body>
</html>
```

port.html:
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Chennai Port</title>
    <style>
        h1{
            text-align: center;
            font-family: 'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;
            color:darkslategray;
        }
        p{
            text-align: justify;
            color:darkolivegreen;
            font-size: x-large;
            
        }
    </style>
</head>
<body>
    <h1>Port of Chennai</h1>
    <br>
    <hr color="Brown">
    <p>Chennai Port, formerly known as Madras Port, is the second largest container port of India, behind Mumbai's Nhava Sheva. The port is the largest one in the Bay of Bengal. It is the third-oldest port among the 13 major ports of India with official port operations beginning in 1881, although maritime trade started much earlier in 1639 on the undeveloped shore. It is an artificial and all-weather port with wet docks. Once a major travel port, it became a major container port in the post-Independence era. An established port of trade of British India since the 1600s, the port remains a primary reason for the economic growth of Tamil Nadu, especially for the manufacturing boom in South India, and has contributed greatly to the development of the city of Chennai. It is due to the existence of the port that the city of Chennai eventually became known as the Gateway of South India.</p>

</body>
</html>
```
## OUTPUT
![Nearmeimg1](https://github.com/Dhanush12022004/NearMe/assets/128135558/0cfb643e-16af-46d9-941c-e0bdc3d8b571)

![Nearmeimg2](https://github.com/Dhanush12022004/NearMe/assets/128135558/a53ab542-bc65-403f-93e3-e7d05890d208)

![Nearmeimg3](https://github.com/Dhanush12022004/NearMe/assets/128135558/9fb8bbe7-1dbb-4574-bea8-355c8a78149f)

![Nearmeimg4](https://github.com/Dhanush12022004/NearMe/assets/128135558/d0f63270-4a6d-466b-81c0-e5ae97f9faa3)

![Nearmeimg5](https://github.com/Dhanush12022004/NearMe/assets/128135558/a83aa09a-aa88-413f-a214-59bc99279b0c)

![Nearmeimg6](https://github.com/Dhanush12022004/NearMe/assets/128135558/540bc0dc-043a-4a5c-8674-eaae563cfa33)

![image](https://github.com/Dhanush12022004/NearMe/assets/128135558/e9175d4b-417a-40b3-8b2e-115973ae224c)

![image](https://github.com/Dhanush12022004/NearMe/assets/128135558/33dc64eb-b3a7-4e4d-9778-7992db36c8c5)



## RESULT
The program for implementing image maps using HTML is executed successfully.
