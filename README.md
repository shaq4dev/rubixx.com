# rubixx.com

Rubixx Company stationeries and more online store and blog site

Project scope { "E-commerce website that also produces blogs"}

- info: {

  - general:

    -------- "E-commerce site that adds items to cart and processes payment on checkout (pseudo)"
    -------- "Site must be able to produce and populate blogs"
    -------- "Must be able to search blog page by word, category and theme"
    -------- "Must be able to search for products by word and category"
    -------- "Must be able to filter for products by category"
    -------- "Must have a light and dark mode UI: able to switch on click"
    -------- "Site must be responsive on Mobile, Tablet and Desktop"
    -------- "UI must include atleast one animation (not transition)"

  - for users
    -------- "The website must authenticate users upon login, and verify the type of user"
    -------- "Users go directly to the home page after approved validation"
    -------- "Visitor gets redirected to login page when they try to add item to cart"
    -------- "User will be able to add to cart after logging in"

  - for admin
    -------- "The website must authenticate user upon login and verify the type of user"
    -------- "Admins go directly to the dashboard after approved validation"
    -------- "An admin page will be needed for administrators to add new products and also to update blogs (add, update and delete blogs)"
    -------- "This website should be able to search all products available in the store"
    -------- ""

    }

* pages: { TOTAL PAGES = 14

        ======= USER PAGES =======

        - home:

        -------- "Navigation:
                  {Logo, Home, About, Products: (School, Office)}, Blogs, Contact Us, social{links} "

        -------- "hero:
                  {-welcome message, cta button: ./products, welcome graphics}

        -------- "about-us-snippet:
                  {-summary of about us page, button: ./about-us}

        -------- "companies who trust us:
                  {-list of brands that trust us, button: ./#}

        -------- "call-to-action:
                  {- final call to action message, button: ./products }

        -------- "footer:
                  {logo-icon, footer statement, boilerplate links, Blogs, contact form, copyright-info} "

        - about:

        -------- "Navigation:
                  {Logo, Home, About, Products: (School, Office)}, Blogs, Contact Us, social{links} "

        -------- "about-us:
                  {general info on company} "

        -------- "our-journey/over-the-years:
                  {timeline for company's growth} "

        -------- "meet-our-team:
                  {card with images, titles, description, social links to individuals} "

        -------- "footer:
                  {logo-icon, footer statement, boilerplate links, Blogs, contact form, copyright-info} "

        - products:

        -------- "Navigation:
                  {Logo, Home, About, Products: (School, Office)}, Blogs, Contact Us, social{links} "

        -------- "all-products:
                  {category(school | office), display image, title, button{school}: ./school-products, button{office}: ./office-products} "

        -------- "footer:
                  {logo-icon, footer statement, boilerplate links, Blogs, contact form, copyright-info} "

        - school:

        -------- "Navigation:
                  {Logo, Home, About, Products: (School, Office)}, Blogs, Contact Us, social{links} "

        -------- "school-products:
                  {select product {Product image, title, product description}, product quantity, button{add to cart}: ./cart} "

        -------- "footer:
                  {logo-icon, footer statement, boilerplate links, Blogs, contact form, copyright-info} "

        - office:

        -------- "Navigation:
                  {Logo, Home, About, Products: (School, Office)}, Blogs, Contact Us, social{links} "

        -------- "office-products:
                  {select product {Product image, title, product description}, product quantity, button{add to cart}: ./cart} "

        -------- "footer:
                  {logo-icon, footer statement, boilerplate links, Blogs, contact form, copyright-info} "

        - contact-us:

        -------- "Navigation:
                  {Logo, Home, About, Products: (School, Office)}, Blogs, Contact Us, social{links} "

        -------- "contact-form:
                  {simple-contact form} "

        -------- "footer:
                  {logo-icon, footer statement, boilerplate links, Blogs, contact form, copyright-info} "

        ======= ADMIN PAGES =======

        - Dashboard:

        -------- "Navigation:
                  {Logo, Dashboard, Manage Blogs} "

        -------- "welcome-admin:
                  {write a blog, button: ./manage-blogs} "

        -------- "footer:
                  {logo-icon, footer statement, boilerplate links, Blogs, contact form, copyright-info} "

        - Manage Blogs:

        -------- "Navigation:
                  {Logo, Dashboard, Manage Blogs} "


        -------- "manage blogs:
                  {add blog, update blog, delete blog} "

        -------- "footer:
                  {logo-icon, footer statement, boilerplate links, Blogs, contact form, copyright-info} "

        ======= AUTHENTICATION PAGES =======

        - login:

        -------- "Navigation:
                  {Logo, Home, About, Products: (School, Office)}, Blogs, Contact Us, social{links} "

        -------- "footer: {none} "

        - sign Up:

        -------- "Navigation:
                  {Logo, Home, About, Products: (School, Office)}, Blogs, Contact Us, social{links} "

        -------- "footer: {none}

        ======= PAYMENT PROCESSING PAGES =======

        - my-cart:

        -------- "Navigation:
                  {Logo, Home, About, Products: (School, Office)}, Blogs, Contact Us, social{links} "

        -------- "footer:
                  {logo-icon, footer statement, boilerplate links, Blogs, contact form, copyright-info} "

        - checkout:

        -------- "Navigation:
                  {Logo, Home, About, Products: (School, Office)}, Blogs, Contact Us, social{links} "

        -------- "footer:
                  {logo-icon, footer statement, boilerplate links, Blogs, contact form, copyright-info} "

        ======= BLOG PAGES =======

        - blogs:

        -------- "Navigation:
                  {Logo, Home, About, Products: (School, Office)}, Blogs, Contact Us, social{links} "

        -------- "search bar: {searches blog page for all existing titles by word and category}"

        -------- "blog list: {this container will hold all cards for individual blogs: these will include, title, description, author, publishing date. This page will hold 9 blogs at a time and will have buttons for viewing page 2 etc. if total blogs are more than 9}"

        -------- "footer:
                  {logo-icon, footer statement, boilerplate links, Blogs, contact form, copyright-info} "

}

- technologies: {

        ======= TECHNOLOGIES & RESOURCES =======

        - styling: tailwindcss, css
        - images: pexels, pixabay, gratisogarphy
        - illustrations: storyset.com
        - color palette: coolors.com
        - gradient:  https://www.colorzilla.com/gradient-editor/
        - icons: font awesome
        - fonts: google fonts
        - other: html, javascript

}

- styling conventions: {

        ======= LIGHT MODE =======

  - colors

    - dominant color:
    - secondary color:
    - accent color:

    ======= DARK MODE =======

    - dominant color:
    - secondary color:
    - accent color:

}

- Iconography: {

      ======= LIGHT MODE =======

- icons

  <i class="fa-brands fa-facebook"></i>
  <i class="fa-brands fa-facebook-messenger"></i>
  <i class="fa-brands fa-linkedin"></i>
  <i class="fa-brands fa-x-twitter"></i>
  <i class="fa-brands fa-instagram"></i>

}
