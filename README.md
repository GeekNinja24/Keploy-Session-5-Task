# Keploy-Session-5-Adding-Database-to-existing-API-along-with-Postman-Testing
Added database to existing API along with Postman Testing

# Postman Testing Code
    1)
    pm.test("Status code is 200", function() {
        pm.response.to.have.status(200);
    });


    2)
    pm.test("Status code is 404", function() {
        pm.response.to.have.status(404);
    });


    3)
    pm.test("Status code is 204", function() {
        pm.response.to.have.status(204);
    });


    4)
    pm.test("Body matches string", function() {
        pm.expect(pm.response.text()).to.include("Hello");
    });


    5)
    pm.test("Your test name", function() {
        var jsonData = pm.response.json();
        pm.expect(jsonData.value).to.eql(100);
    });





## Screenshots

![test](https://user-images.githubusercontent.com/72194471/217355874-306728dc-4833-4fe7-8dd5-1239964838e4.PNG)
![test1](https://user-images.githubusercontent.com/72194471/217355904-26d8e9f0-b9e1-4279-b36c-5ca9b286d891.PNG)
![test2](https://user-images.githubusercontent.com/72194471/217355992-f50208c2-37e0-4c3d-9cf7-2ba608bca8e4.PNG)

