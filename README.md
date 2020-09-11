# add-to-cart
//Hey everybody, I am building my own website, and i have a problem. When I try to send the product to the cart all it does is send you to the cart. How can I send all the info to the cart?



<!DOCTYPE html>
<html>
<head>
<title>Congradulations</title>
<meta charset="utf-8" />
<link rel="stylesheet" href="../cart/cart-test.css" media="screen" type="text/css" />
<script type="text/javascript" src="http://ajax.googleapis.com/ajax/libs/jquery/2.0.3/jquery.min.js"></script>
<script type="text/javascript" src="../cart/cart-test.js"></script>
</head>
<body>
<div id="site">
	<header id="masthead">
		<h1>Congradulations <span class="tagline">I'm Not A Father</h1>
	</header>
	<div id="content">
		<div id="products">
			<ul>
				<li>
					
					<div class="product-image">
						<img src="../images/ice-blue.PNG" alt="" />
					</div>
					<div class="product-description">
					<div class="product-description" data-name="congradulations" data-price="16.99">
						<h3 class="product-name">Congradulations T-Shirt</T-Shirt></h3>
						<p class="product-price">$16.99</p>
						<form class="add-to-cart" action="../cart/cart-test.html" method="post">
							<div>
								<label for="qty-1">Quantity</label>
                                <input type="text" name="qty-1" id="qty-1" class="qty" value="1" />
                                <select for="qty-1">
                                    <option type="text" name="qty-1" id="qty-1" class="qty" >Small</option>
                                    <option type="text" name="qty-1" id="qty-1" class="qty" >Medium</option>
                                    <option type="text" name="qty-1" id="qty-1" class="qty" >Large</option>
                                </select>
                            </div>
                            
                            <p><input type="submit" value="Add to cart" class="btn" /></p>
						</form>
					</div>
				</li>
				
			</ul>
		</div>
	</div>
	
	
</div>
<footer id="site-info">
		
	</footer>
</body>
</html>	
