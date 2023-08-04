# spring-tips

### @RequestParam default value
```
    @GetMapping("/greeting")
    public Greeting greeting(@RequestParam(value = "name", defaultValue = "World") String name) {
        // Controller implementation
    }
```
This annotation allows you to set a default value that is activated when the request does not contain the expected parameter.
