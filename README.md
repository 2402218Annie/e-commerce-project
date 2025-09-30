[index.html](https://github.com/user-attachments/files/22618743/index.html)# e-commerce-project
my HTML and CSS e-commerce table project
[<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, intial-scale=1.0">
        <title>E-commerce Produts Table</title>
        <link rel="stylesheet" href="style2.css">
    </head>
    <body>
        <div class="container">
            <header>
               <h1>E-commerce Products Table</h1>
               <p class="subtitle">Browse our extensive collection of Products</p>
            </header>
            <div class="table-container"></div>
           <table>
            <thead>
            <tr>
                <th>E-commerce Firm</th>
                <th>Product Name</th>
                <th>Product Category</th>
                <th>Product Description</th>
            </tr>
            </thead>
            <tbody>
             <tr>
                <td>
                    <div class="firm=cell">
                    <div class="firm-icon"><i class="fas fa-shopping"></i></div>
                    <div class="firm-name">Carrefour</div>
                    </div>
                </td>
                <td>
                <div class="product-name">Oryx Cooker</div>
                </td>
                <td>
                    <span class="category category-home">Home & Kitchen</span>
                </td>
                <td>
                    <ul class="descprition-list">
                        <li>Has a double glass oven door</li>
                        <li>Uses less power</li>
                        <li>Has a timer to allow precise cooking</li>
                        <li>Has a top lid to protect burners</li>
                    </ul>
                </td>
            </tr>
            <tr>
                <td>
                    <div class="firm-cell">
                        <div class="firm-icon"><i class="fab fa-apple"></i></div>
                        <div class="firm-name">Apple Store</div>
                    </div>
                </td>
                <td>
                    <div class="product-name">iphone 16 Pro Max</div>
                </td>
                <td>
                    <span class="categroy category-electronics">Electronics</span>
                </td>
                <td>
                    <ul class="description-list">
                        <li>Large 6.9-inch Super Retina XDR display</li>
                        <li>Powerful A18 Pro chip</li>
                        <li>Advanced tripl-camera system</li>
                        <li>Offers robust battery life</li>
                    </ul>
                </td>
            </tr>
            <tr>
                <td>
                    <div class="firm-cell">
                        <div class="firm-icon"><i class="fas fa-shirt"></i></div>
                        <div class="firm-name">Mr Price</div>
                    </div>
                </td>
                <td>
                    <div class="product-name">Men's suit</div>
                </td>
                <td>
                    <span class="category category-fashion">Fashion</span>
                </td>
                <td>
                    <ul class="description-list">
                        <li>A matching suit jacket and trousers</li>
                        <li>Trousers are made from the fabric as the jacket</li>
                        <li>It can be worn with a tie</li>
                        <li>Available in mutliple sizes and colors</li>
                    </ul>
                </td>
            </tr>
            <tr>
                <td>
                    <div class="firm-cell">
                        <div class="firm-icon"><i class="fas fa-home"></i></div>
                        <div class="firm-name">Victoria Homestore</div>
                    </div>
                </td>
                <td>
                    <div class="product-name">Morden Sofa Set</div>
                </td>
                <td>
                    <span class="category category-home">Home $ Furniture</span>
                </td>
                <td>
                    <ul class="description-list">
                        <li>Designed with sharp,cleans lines and geometric forms</li>
                        <li>Have sleek metal or wooden legs</li>
                        <li>Designed with both natural and industrial materials</li>
                        <li>Easy to assamble with included tools</li>
                    </ul>
                </td>
            </tr>
            <tr>
                <td>
                    <div class="firm-cell">
                        <div class="firm-icon"><i class="fab fa-amazon"></i></div>
                        <div class="firm-name">Amazon</div>
                    </div>
                </td>
                <td>
                    <div class="product name">Echo Dot (4th Gen)</div>
                </td>
                <td>
                    <span class="category category-electronics">Electronics</span>
                </td>
                <td>
                    <ul class="description-lists">
                        <li>Alexa built in</li>
                        <li>Bluetooth connectivity</li>
                        <li>Smart speaker</li>
                        <li>Compact spherial design</li>
                    </ul>
                </td>
            </tr>
            <tr>
                <td>
                    <div class="firm-cell">
                        <div class="firm-icon"><i class="fab fa-ebay"></i></div>
                        <div class="firm name">eBay</div>
                    </div>
                </td>
                <td>
                    <div class="product-name">Google Pixel Watch (1st Gen)</div>
                </td>
                <td>
                    <span class="category category-electronics">Electronics</span>
                </td>
                <td>
                    <ul class="descprition-list">
                        <li>Circular doomed display</li>
                        <li>Made of stainless steel</li>
                        <li>Uses a proprietary band attachment system</li>
                        <li>Compatible with Andriod phones</li>
                    </ul>
                </td>
            </tr>
            <tr>
                <td>
                    <div class="firm-cell">
                        <div class="firm-icon"><i class="fas fa-sport"></i></div>
                        <div class="firm-name">Adidas</div>
                    </div>
                </td>
                <td>
                    <div class="product-name">Road running shoes</div>
                </td>
                <td>
                    <span class="category category-sports">Sports $ fitness</span>
                </td>
                <td>
                    <ul class="description-list">
                        <li>Smooth and durable outsoles</li>
                        <li>Lightweight</li>
                        <li>Midsole that contains reponsive cushioning</li>
                        <li>AHARPLUS heel plug rubber</li>
                    </ul>
                </td>
            </tr>
            <tr>
                <td>
                    <div class="firm-cell">
                        <div class="firm-icon"><i class="fas fa-book"></i></div>
                        <div class="firm-name">Ubuy</div>
                    </div>
                </td>
                <td>
                    <div class="product-name">Act Like a Lady, Think Like a Man</div>
                </td>
                <td>
                    <span class="category category-books">Books</span>
                </td>
                <td>
                    <ul class="descprition-list">
                        <li>Written by Steve Harvey</li>
                        <li>Offers women a candid look into the male perpective</li>
                        <li>Reveals how men think and what they want</li>
                        <li>Published in 2009</li>
                    </ul>
                </td>
            </tr>
            <tr>
                <td>
                    <div class="firm-cell">
                        <div class="firm-icon"><i class="fas fa-home"></i></div>
                        <div class="firm-name">Wayfair</div>
                    </div>
                </td>
                <td>
                    <div class="product-name">Queen Size Bed</div>
                </td>
                <td>
                    <span class="category category-home">Home $ Furniture</span>
                </td>
                <td>
                    <ul class="descprition-list">
                        <li>Solid wood construction</li>
                        <li>Measures 60 inches wide by 80 inches long</li>
                        <li>Solid headboard and footboard</li>
                        <li>Ample under-bed stoarage</li>
                    </ul>
                </td>
            </tr>
            <tr>
                <td>
                    <div class="firm-cell">
                        <div class="firm-icon"><i class="fas fa-magic"></i></div>
                        <div class="firm - name">Sephora</div>
                    </div>
                </td>
                <td>
                    <div class="product-name">Hydrating Face Moisturizer</div>
                </td>
                <td>
                    <span class="category category-beuty">Beauty</span>
                </td>
                <td>
                    <ul class="descprition-list">
                        <li>24-hour hydration</li>
                        <li>Ingredients such as hydration acid and glycerin</li>
                        <li>Soothes dryness</li>
                        <li>Keeps the skin soft</li>
                    </ul>
                </td>
            </tr>
            <tr>
                <td>
                    <div class="firm-cell">
                        <div class="firm-icon"><i class="fas fa-shopping"></i></div>
                        <div class="firm-name">Walmat</div>
                    </div>
                </td>
                <td>
                    <div class="product-name">Halloween costume</div>
                </td>
                <td>
                    <span class="category category-fashion">Fashion</span>
                </td>
                <td>
                    <ul class="descprition-list">
                        <li>Spooky</li>
                        <li>Either traditional or modern choice</li>
                        <li>Simple and detailed</li>
                        <li>Express creativity</li>
                    </ul>
                </td>
            </tr>
            <tr>
                <td>
                    <div class="firm-cell">
                        <div class="firm-icon"><i class="fas fa-shopping"></i></div>
                        <div class="firm-name">LC Wakiki</div>
                    </div>
                </td>
                <td>
                    <div class="product-name">Women's Dress</div>
                </td>
                <td>
                    <span class="category category-fashion">Fashion</span>
                </td>
                <td>
                    <ul class="descprition-list">
                        <li>One-piece garmet</li>
                        <li>Offers comfort and elegance</li>
                        <li>Lengths such as mini,midi or maxi</li>
                        <li>Fabrics either cotton, silk or chiffon</li>
                    </ul>
                </td>
            </tr>
            <tr>
                <td>
                    <div class="firm-cell">
                        <div class="firm-icon"><i class="fas fa-shopping"></i></div>
                        <div class="firm-name">Nike</div>
                    </div>
                </td>
                <td>
                    <div class="product-name">Women's leggings</div>
                </td>
                <td>
                    <span class="category category-fashion">Fashion</span>
                </td>
                <td>
                    <ul class="descprition-list">
                        <li>Stretchy bottoms</li>
                        <li>Fabrics cotton,spandex and polyester</li>
                        <li>High-waisted and ankle=length</li>
                        <li>Versatile and fashionable</li>
                    </ul>
                </td>
            </tr>
            <tr>
                <td>
                    <div class="firm-cell">
                        <div class="firm-icon"><i class="fas fa-amazon"></i></div>
                        <div class="firm-name">Amazon</div>
                    </div>
                </td>
                <td>
                    <div class="product-name">Makeup</div>
                </td>
                <td>
                    <span class="category category-beuty">Beauty</span>
                </td>
                <td>
                    <ul class="descprition-list">
                        <li>Enhances natural features</li>
                        <li>Creates srtistic looks</li>
                        <li>Essentials such as foundation and concealar</li>
                        <li>Form of self -expression</li>
                    </ul>
                </td>
            </tr>
            <tr>
                <td>
                    <div class="firm-cell">
                        <div class="firm-icon"><i class="fas fa-alibaba"></i></div>
                        <div class="firm-name">Alibaba</div>
                    </div>
                </td>
                <td>
                    <div class="product-name">Necklace</div>
                </td>
                <td>
                    <span class="category category-beuty">Beauty</span>
                </td>
                <td>
                    <ul class="descprition-list">
                        <li>Various styles and Lengths</li>
                        <li>materialslike gold, silver and platinum</li>
                        <li>Worn everyday for elegance</li>
                        <Li>Express personal style</Li>
                    </ul>
                </td>
            </tr>
        </tbody>
        </table>
        </div>
        <div class="footer">
            <p>E-commerce Produts table &copy; 2025 | Displaying 15 products </p>
        </div>
    </body>
</html>Uploading index.html…]()

[registration.html](https://github.com/user-attachments/files/22618763/registration.html)
<!DOCTYPE html>
<html>
    <head>
        <title>E-commerce Registration Form</title>
        <meta name="viewport" content="width=device-wdth, intial-scale=1.0">
        <link rel="stylesheet" href="style.css">
    </head>
    <body>

       
