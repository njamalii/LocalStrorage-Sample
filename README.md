# Local Storage
---

To save the information into the local storage we must first convert the object into a string.

 	`var product = {
                "productname": document.getElementById("productName").value,
                "productprice": document.getElementById("ProductPrice").value,
                "productmodel": document.getElementById("productModel").value,
                "productdiscount": document.getElementById("productDiscount").value,
                "productinfo": document.getElementById("productInfo").value,
                "productRating": document.getElementById("productRate").value
            }
            var str = JSON.stringify(product);
            localStorage.setItem("product", str);
            console.log(str);`


Information such as:
1. Shopping Cart Data
2. Form Data
3. User information
Will be stored in Local Storage.
