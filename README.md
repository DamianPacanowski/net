# CookieSet 

is a class for setting cookies in the user's browser, together with saving on the server.

One of best data for this porpouse it is the data from the user himself, obtained after connecting to our server.

I am taking three parameters from the user as basic data, user host, ip, programs, to create a cookie connection.

So I created a class and called it in this example:

    include('../cookie.set.php');
    $_cookie_set = new cookie;
    if(($_cookie_set->catch())==true)
    {
        echo'<pre>';
            print_r($_COOKIE); // print cookie 
        echo'</pre>';
    }
    else
    {
        echo'COOKIE SET ERROR';
    } 


if you have more relevant and useful variables to suggest, feel free to discuss.
