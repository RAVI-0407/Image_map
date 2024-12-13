# Ex04 Places Around Me
# Date:05/10/2024
# AIM
To develop a website to display details about the places around my house.

# DESIGN STEPS
## STEP 1
Create a Django admin interface.

## STEP 2
Download your city map from Google.

## STEP 3
Using <map> tag name the map.

## STEP 4
Create clickable regions in the image using <area> tag.

## STEP 5
Write HTML programs for all the regions identified.

## STEP 6
Execute the programs and publish them.

# CODE
 # Imagemap.html
 ~~~
<html>

    <head>

        <title>IMAGEMAP</title>

        <LINK REL="ICON" href="C:\Users\ravip\OneDrive\Documents\HTML\ImageMap\global.avif">

            <style>
                header{
                    background-color:moccasin;
                    color:darkred;
                    font-size: 50px;
                    text-align: center;
                    font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
                }
                body{
                    background-color: black;
                    color: azure;
                }
            </style>

    </head>

    <BODY>
        <header>AMBUR</header><br><br><br>
       <center> <img src="C:\Users\ravip\OneDrive\Documents\HTML\ImageMap\Screenshot 2024-11-23 173900.png" usemap="#image-map"></center>
        <map name="image-map">
            <area target="_blank" alt="Rahamaniya" title="Rahamaniya Briyani" href="C:\Users\ravip\OneDrive\Documents\HTML\ImageMap\Rahamaniya.html" coords="838,165,1053,227" shape="rect">
            <area target="_blank" alt="NR Briyani" title="NR Briyani" href="C:\Users\ravip\OneDrive\Documents\HTML\ImageMap\Nr .html" coords="791,255,978,336" shape="rect">
            <area target="_blank" alt="Poorvika" title="Poorvika" href="C:\Users\ravip\OneDrive\Documents\HTML\ImageMap\Poorvika.html" coords="237,472,479,523" shape="rect">
            <area target="_blank" alt="Dr Agarwals" title="Dr Agarwals Eye clinic" href="C:\Users\ravip\OneDrive\Documents\HTML\ImageMap\Dr Eye.html" coords="300,339,529,408" shape="rect">
            <area target="_blank" alt="GK pet" title="GK Pet shop" href="C:\Users\ravip\OneDrive\Documents\HTML\ImageMap\GK pet.html" coords="849,522,1064,637" shape="rect">
        </map>

    </BODY>

</html>  
~~~
 # Rahamaniya.html
 ~~~
<style>
    header{
        background-color:moccasin;
        color:darkred;
        font-size: 50px;
        text-align: center;
        font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
    }
    body{
        background-color: black;
        color: azure;
    }
    p{
        font-size: x-large;
    }
</style>
<body>
    <header>Rahamaniya Briyani</header><br><br><br>
    <center><img src="rahamaniya.jpg" width="350" height="300"></center>
<p>
    Rahamaniya Biryani in Ambur is a well-known destination for biryani lovers, offering the authentic taste of Ambur-style biryani. Famous for its unique preparation method, the biryani is cooked with aromatic spices and short-grain seeraga samba rice, which gives it a distinct flavor. The restaurant is popular for its perfectly balanced spices and tender, flavorful meat, whether it's chicken, mutton, or beef.

    Rahamaniya Biryani is cherished by locals and visitors alike for maintaining the traditional Ambur biryani legacy. It is a go-to spot for those seeking high-quality, flavorful biryani in a casual and welcoming dining atmosphere.
</p>
</body> 
~~~
 # Nr.html
 ~~~
<style>
    header{
        background-color:moccasin;
        color:darkred;
        font-size: 50px;
        text-align: center;
        font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
    }
    body{
        background-color: black;
        color: azure;
    }
    p{
        font-size: x-large;
    }
</style>
<body>
    <header>NR Briyani & Kabab Center</header><br><br><br>
    <center><img src="NR.jpg" width="350" height="300"></center>
<p>
    NR Hotel in Ambur is renowned for its mouthwatering biryani and delectable kebabs, making it a must-visit for food lovers. Their signature biryani, crafted with fragrant basmati rice, tender meat, and a blend of aromatic spices, reflects the rich culinary heritage of Ambur-style biryani. It is known for its subtle flavors, perfect balance of spice, and a unique preparation technique that sets it apart.

The kebabs at NR Hotel are equally impressive, featuring juicy, well-marinated pieces of chicken or mutton cooked to perfection. Grilled over open flames or cooked on skewers, the kebabs are flavorful, tender, and infused with a smoky aroma that enhances their taste.

NR Hotel’s reputation for serving high-quality, authentic dishes has made it a favorite among locals and travelers alike. The combination of its inviting ambiance and affordable prices makes it a popular spot to savor these culinary delights.
</p>
</body> 
~~~
 # Poorvika.html
 ~~~
<style> 
header{ 
    background-color:moccasin;
    color:darkred;
    font-size: 50px;
    text-align:center; 
    font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif; }
body{ 
    background-color: black; 
    color: azure; } 
p{ 
    font-size: x-large; } 
    </style>
    <body>
      <header>Poorvika</header><br><br><br>
      <center><img src="poorvika.jpg" width="350" height="300"></center>
      <p>
        Poorvika Mobile Shop is a leading retail chain in India, specializing in mobile
        phones, gadgets, and accessories. Founded in 2004, it has grown to over 400 outlets
        across India, known for offering a wide range of smartphones from top brands like
        Apple, Samsung, Xiaomi, Vivo, Oppo, and more. In addition to mobiles, the shop
        provides tablets, smartwatches, audio devices, and accessories like cases, chargers,
        and earphones.
        Poorvika is popular for its competitive pricing, attractive offers, and convenient
        financing options, making premium gadgets accessible to customers. The store is
        known for excellent customer service, knowledgeable staff, and a personalized
        shopping experience. Many branches also provide additional services such as device
        insurance, exchange offers, and extended warranties. With its combination of
        affordability and quality, Poorvika Mobile Shop has established itself as a trusted
        destination for tech enthusiasts
      </p>
    </body>
~~~
 # Dr Eye
 ~~~
<style>
    header{
        background-color:moccasin;
        color:darkred;
        font-size: 50px;
        text-align: center;
        font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
    }
    body{
        background-color: black;
        color: azure;
    }
    p{
        font-size: x-large;
    }
</style>
<body>
    <header>Dr Agarwals Eye clinic</header><br><br><br>
    <center><img src="Screenshot 2024-11-23 165303.png" width="450" height="300"></center>
    <P>
        Dr. Agarwal's Eye Clinic is a globally recognized leader in ophthalmology, offering advanced treatments and cutting-edge technology in eye care. Founded in 1957 by Dr. Jaiveer Agarwal and his wife, Dr. Tahira Agarwal, the clinic has grown into a vast network of over 150 eye hospitals spread across India and more than 10 international locations. It has been a pioneer in introducing innovative procedures, such as Glued IOL and Micro Incision Cataract Surgery (MICS).

The clinic caters to a wide range of eye health needs, including cataract surgeries, glaucoma management, LASIK and refractive surgeries, retina treatments, corneal transplants, and pediatric eye care. Dr. Agarwal's Eye Clinic emphasizes personalized patient care, ensuring each treatment plan is tailored to individual needs. It also conducts training programs for ophthalmologists and invests in continuous research to push the boundaries of eye care innovation. Renowned for its quality and expertise, it remains a trusted name for patients seeking world-class vision care solutions.
    </P>
</body> 
~~~
 # GK pet
 ~~~
<style>
    header{
        background-color:moccasin;
        color:darkred;
        font-size: 50px;
        text-align: center;
        font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
    }
    body{
        background-color: black;
        color: azure;
    }
    p{
        font-size: x-large;
    }
</style>
<body>
    <header>GK Pet Shop</header><br><br><br>
    <center><img src="pet.jpg" width="550" height="300"></center>
<p>
    Pet and fish shops in Ambur are popular among animal enthusiasts, offering a wide range of pets and supplies to meet the diverse needs of their customers. These shops typically feature various pet options, including colorful ornamental fish, exotic birds like budgerigars and lovebirds, small mammals such as rabbits and guinea pigs, and occasionally puppies or kittens.

In addition to pets, these stores stock an extensive selection of pet care products, including high-quality pet food, aquariums, fish tank decorations, water conditioners, pet bedding, cages, and grooming accessories. Many shops also provide specialized services such as aquarium installation and maintenance, customized fish tank designs, and basic advice on pet care and training.

With knowledgeable staff and a commitment to providing healthy, well-cared-for animals, Ambur’s pet and fish shops serve as a one-stop solution for pet lovers. They often create a friendly atmosphere for customers to explore and learn about different pets, making them an integral part of the local community for animal care and companionship.
</p>
</body> 
~~~
# OUTPUT

![Screenshot 2024-12-02 131800](https://github.com/user-attachments/assets/350bee54-c46c-4081-90d9-a6a1034c2a10)

![Screenshot 2024-12-02 131817](https://github.com/user-attachments/assets/0e0983c6-0705-4508-bf9d-8585c2b4eb44)

![Screenshot 2024-12-02 131829](https://github.com/user-attachments/assets/26d2145a-23c1-46e5-ad80-b905437495db)

![Screenshot 2024-12-02 131900](https://github.com/user-attachments/assets/add6721c-97bf-4ef4-9416-757ac3fccb1d)

![Screenshot 2024-12-02 131912](https://github.com/user-attachments/assets/b81bbaed-2f73-4fac-a1ca-0075f9468176)

![Screenshot 2024-12-02 131847](https://github.com/user-attachments/assets/b5f8dcdc-809e-4dd7-b965-3bf7e502a8ad)

# RESULT
The program for implementing image maps using HTML is executed successfully.
