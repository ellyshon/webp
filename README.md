{
  "type": "website",
  "pages": [
    {
      "type": "homepage",
      "sections": [
        {
          "type": "hero-carousel",
          "slides": [
            {
              "image": "hero-slide-1.jpg",
              "title": "Featured Product 1",
              "description": "Check out our latest featured product!",
              "cta": "Shop Now"
            },
            {
              "image": "hero-slide-2.jpg",
              "title": "Promotion Sale",
              "description": "Big discounts on selected items!",
              "cta": "View Sale"
            }
          ]
        },
        {
          "type": "product-category",
          "title": "New Arrivals",
          "products": [
            {
              "image": "product-1.jpg",
              "name": "Product 1",
              "price": "$99.99",
              "rating": 4.5
            },
            {
              "image": "product-2.jpg",
              "name": "Product 2",
              "price": "$129.99",
              "rating": 4.8
            }
          ]
        },
        {
          "type": "product-category",
          "title": "Best Sellers",
          "products": [
            {
              "image": "product-3.jpg",
              "name": "Product 3",
              "price": "$79.99",
              "rating": 4.2
            },
            {
              "image": "product-4.jpg",
              "name": "Product 4",
              "price": "$149.99",
              "rating": 4.9
            }
          ]
        },
        {
          "type": "product-category",
          "title": "Discounts",
          "products": [
            {
              "image": "product-5.jpg",
              "name": "Product 5",
              "price": "$59.99",
              "rating": 4.0
            },
            {
              "image": "product-6.jpg",
              "name": "Product 6",
              "price": "$119.99",
              "rating": 4.7
            }
          ]
        },
        {
          "type": "footer",
          "links": [
            {
              "title": "Company",
              "items": ["About Us", "Careers", "Contact"]
            },
            {
              "title": "Customer Service",
              "items": ["FAQ", "Shipping", "Returns"]
            },
            {
              "title": "Social Media",
              "items": ["Facebook", "Instagram", "Twitter"]
            }
          ]
        }
      ]
    },
    {
      "type": "product-listings",
      "filters": [
        "Category",
        "Price",
        "Rating"
      ],
      "products": [
        {
          "image": "product-1.jpg",
          "name": "Product 1",
          "price": "$99.99",
          "rating": 4.5
        },
        {
          "image": "product-2.jpg",
          "name": "Product 2",
          "price": "$129.99",
          "rating": 4.8
        },
        {
          "image": "product-3.jpg",
          "name": "Product 3",
          "price": "$79.99",
          "rating": 4.2
        },
        {
          "image": "product-4.jpg",
          "name": "Product 4",
          "price": "$149.99",
          "rating": 4.9
        },
        {
          "image": "product-5.jpg",
          "name": "Product 5",
          "price": "$59.99",
          "rating": 4.0
        },
        {
          "image": "product-6.jpg",
          "name": "Product 6",
          "price": "$119.99",
          "rating": 4.7
        }
      ]
    },
    {
      "type": "product-detail",
      "product": {
        "image": "product-1.jpg",
        "gallery": ["product-1-thumb-1.jpg", "product-1-thumb-2.jpg", "product-1-thumb-3.jpg"],
        "name": "Product 1",
        "price": "$99.99",
        "description": "Detailed description of Product 1.",
        "specifications": ["Specification 1", "Specification 2", "Specification 3"],
        "reviews": [
          {
            "user": "User 1",
            "rating": 5,
            "comment": "Great product!"
          },
          {
            "user": "User 2",
            "rating": 4,
            "comment": "Good quality."
          }
        ]
      },
      "cta": "Add to Cart"
    },
    {
      "type": "cart",
      "items": [
        {
          "image": "product-1.jpg",
          "name": "Product 1",
          "quantity": 1,
          "price": "$99.99"
        },
        {
          "image": "product-3.jpg",
          "name": "Product 3",
          "quantity": 2,
          "price": "$79.99"
        }
      ],
      "total": "$259.97",
      "ctas": ["Checkout", "Continue Shopping"]
    }
  ],
  "global-styles": {
    "colors": {
      "primary": "#007bff",
      "secondary": "#6c757d",
      "background": "#f8f9fa",
      "text": "#343a40"
    },
    "typography": {
      "font-family": "Arial, sans-serif",
      "font-sizes": {
        "h1": "2.5rem",
        "h2": "2rem",
        "body": "1rem"
      }
    }
  },
  "header": {
    "type": "header",
    "elements": [
      {
        "type": "logo",
        "position": "left"
      },
      {
        "type": "search-bar",
        "position": "center"
      },
      {
        "type": "icon",
        "icon-type": "cart",
        "position": "right"
      },
      {
        "type": "icon",
        "icon-type": "user-profile",
        "position": "right"
      }
    ]
  }
}
