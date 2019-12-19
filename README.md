# bootstrap-customization

1. Download bootstrap 4 in your local network.
    /*In my case, I downloaded a bare theme for customization: https://startbootstrap.com/templates/modern-business/*/
    
2. After downloading a theme, create a custom.css file inside your css folders.

3. Don't forget to add the <link src=""/> for your custom.css

4. When customizing a theme, always get the class and put the new style on your custom.css folder

example:

````
<button class="btn btn-primary">SUBMIT</button>

/*original class in bootstrap.min.css*/
.btn-primary {
    color: #fff;
    background-color: #007bff;
    border-color: #007bff;
}

/*updated css style in custom.css*/
.btn-primary {
    color: pink;
    background-color: #000000;
    border-color: #000000;
}

````
5. Use your creativity! You can choose what color you want and styles!
