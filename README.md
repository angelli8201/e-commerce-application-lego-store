# capstone-project

As a casual Lego enjoyer, I want to search for products so I can find something I might be interested in purchasing. In the 85+ years that LEGO has been running, they have released over 15,000 sets. With sets coming and in and out of rotation every year, I want to see a wide collection of new, popular, and even rare sets for sale. For my project, I want to build an e-comm app. The business model would be on Legos. The design of the store would be very colorful and nostalgic. I would create product pages with detailed product listings with descriptions, images, and prices. As a user, I want to add a product to my cart, so I may purchase it later. The cart should display current items added, in addition to the cart total. In addition, I would like to create a Lego news section, talking about what recent events the company has done. My learning goal is to look into React Stripe to mimic checkout and payment flow.

Database
- legoSet
- legoMiniFigure
- theme
- newsPost



-Lego Set - A LEGO set refers to a collection of LEGO bricks and elements packaged together in a box with instructions for building specific models or structures.
-Lego MiniFigure - A LEGO minifigure is a small, posable figure that typically stands around 1.5 inches (4 centimeters) tall. These figures are an essential component of many LEGO sets and play a crucial role in the LEGO building and play experience. 
-Lego theme - A lego theme refers to a specific category or concept around which a collection of LEGO sets is designed.
-NewsPost - A news post shows what LEGO has been doing recently or what new creations are planning to be released!




MySQL-
TABLE 1 - legoset
legoSetId, name,  pieces, ages, price, image_url


TABLE 2 - legoMiniFigure
figureId, name, pieces, image_url


TABLE 3 - theme
themeId, name

TABLE 4- newsPost
postId, title, caption, date

