<!-- TODO: Update with your values. -->
# Playground
> Short Guide to use Framework
Welcome to the playground for xel framework. This guide will help you understand how to use various features of the framework, including RESTful API services, dynamic routing, middleware, and server-side rendering (SSR) of static content.


# Service Restfull API
The Service Restful API section covers how to implement RESTful services in the Xel framework. RESTful APIs allow your application to communicate with other services using standard HTTP methods.

## Dynamic Routing Implementation
Dynamic routing allows you to define routes that can change based on variables in the URL.

```php
    // Get Request dynamic Router
    #[GET("/")]
    public function index():void
    {
        $this->return
        ->workSpace(function (Responses $response){
            $response->Display('landing.php');
        });  
    }

    // POST Request dynamic Router
    #[POST("/")]
    public function index():void
    {
        $this->return
        ->workSpace(function (Responses $response){
            $response->Display('landing.php');
        });  
    }


    // PUT Request dynamic Router
    #[PUT("/")]
    public function index():void
    {
        $this->return
        ->workSpace(function (Responses $response){
            $response->Display('landing.php');
        });  
    }

    // DELETE Request dynamic Router
    #[DELETE("/")]
    public function index():void
    {
        $this->return
        ->workSpace(function (Responses $response){
            $response->Display('landing.php');
        });  
    }
```


## Middlewares



# SSR Render Static Content

## Non-Cache Render

## Cache Render


