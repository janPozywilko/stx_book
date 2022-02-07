STX Recruitment Task

App is available at: https://powerful-cove-34240.herokuapp.com/

Available endpoints:

/api/test - returns if api is working

GET /api/books - returns all books that are in database

  available filtering:
    
    ?authors= - get books where author the same as passed as parameter
    
    ?title= - get books where title the same as passed as parameter
    
    ?language= - get books where language the same as passed as parameter
    
    ?published_data_before= - get books with published_date after specified date
    
    ?published_data_after= - get books with published_date before specified date
