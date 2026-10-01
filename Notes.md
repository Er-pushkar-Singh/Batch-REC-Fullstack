# Validation =>
        Validations are used to validate the user to fill the criteria .
        There are Two types of Validation available .
        1. Client Side Validation
                Client Side validation are those validation which is applied at the client side (frontend) .
                1. Required => likha hai ya nhi
                2. length => kitna likha
                3. pattern => kya likha kitna likha
        2. Server Side Validation
                Server side Validation are those validation which is applied at the server side (backend). It is the more secure way to integrate the validation .
                1. Required
                2. length
                3. pattern
## Regular Expression =>
            Regular expression is a set of charecter which is used for search a pattern in javascript .
            Syntaxt 
                starting => /^
                ending => $/
                range => []
                limit => {}
                other => +  . \
        Ex => if we are check a name for matching the pattern
            let a = /^[a-zA-Z]{3,30}$/

        Ex -> if you want to check mobile number 
            let a = /^[0-9+]{13}$/
        Ex -> if you want to check adhar number 
            let a = /^[0-9]{12}$/
        Ex -> if you want to check email
            singhpushkar7830@gmail.com
            const a = /^[a-zA-Z0-9._]+@+[a-zA-Z]+\.+[a-zA-Z]$/
Regirstration Form
    name , email , mobile , adhar 

# Events =>
    Something which can happened on the browser is called events .
    like -=> onclick , onload , onmouseoever , onmouseout etc .
    Types to Implement the event --
        1. Using HTML Attributes 
            ex ->
            <button onclick="fun()">click</button>
        2. Using method
            addEventListener('eventName',callback)

# Synchronous js =>
    When a code executes in the blocking is called a s synchronous .
    Ex -> A =>
        - B => Downloading / 1h 
        - C => blocked unitll B completion 
# Asynchronous js 
    Asychronous way is a way in which code executed in the non blocking way .
    1. Event
    2. Timer Function
    3. Callbacks
    4. Promises
    5. Async/await 
### Promises =>
        Promises are used to handle asynchrnous task in js . in the promises there are three major state occured .
        1. fullfill
        2. pending
        3. rejected 

### Dictionary App =>   