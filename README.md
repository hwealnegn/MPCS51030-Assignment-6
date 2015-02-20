Grade: 9/10

Good job with:
    - Use of the master/detail controller
    - Creating custom cells
    - SharedNetworking code

Edit/done button does nothing in master view controller

You should create an "Article" class to pass around

There is a big lag between when the data is fetched and when the UI is updated because you are not updating it on the main thread - e.g.                                                    dispatch_async(dispatch_get_main_queue(), ^{...});

Additional point included for Tweet functionality