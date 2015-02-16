# OpenDevResources
A collection of resources to be used in your projects

## Things to include :

* Licences
* Standard Language Headers
* Standard Language Package lists
* Standard Language Copyright Information


**An example: PHP::composer**

    {
        "name": "app/name",
        "type": "library",
        "description": "A description of your Package",
        "keywords": ["app","library","keywords"],
        "homepage": "link to package / library website.",
        "license": "Currently using GNU",
        "authors": [{
            "name": "Author Name",
            "email": "Author Email",
            "homepage": "Author Website"
        }],
        "require": {
            "php": ">=5.3.0"
        },
        "suggest": {
            "ext-mcrypt": "Used for cookie encryption"
        },
        "autoload": {
            "psr-0": { 
                "Namespace": "src" 
            }
        }
    }
    
I think if people can create a standard for their own languages this would help us keep code consistency - something that I think id very useful! 
