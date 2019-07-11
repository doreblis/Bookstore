let book1 = [
    {
        id : "1" ,
        name: "The Oh She Glows Cookbook: Over 100 Vegan Recipes to Glow from the Inside Out",
        author: "Angela Liddon",
        image: "https://images-na.ssl-images-amazon.com/images/I/51zlBTntF7L._SX398_BO1,204,203,200_.jpg",
        price: "$18.63",
        testimonial: {
            testimonial: "Angela Liddon knows that great cooks depend on fresh ingredients. You'll crave every recipe in this awesome cookbook!",
            writer: "—Isa Chandra Moskowitz, author of Isa Does It"
        }
        
    }
    ];

    
    
    
    
    document
        .querySelector('form')
        .addEventListener(
            'submit',
            (event) => {
                let data = event.target.elements;
                let newProduct = {
                    'name': data[0].value,
                    'author': data[1].value,
                    'image': data[2].value,
                    'price': data[3].value,
                    'testimonial': {}
                }
            }
        );