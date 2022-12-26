<template>

    <div class="main">
        

            <form class="signup">
                <div class="container">
                    <label for="uname"><b>Name</b></label>
                    <input type="text" placeholder="Enter Name" name="uname" required>
                    
                    <label for="uname"><b>E-mail</b></label>
                    <input type="text" placeholder="Enter E-mail" name="uname" required>

                    <label for="psw"><b>Password</b></label>
                    <input type="password" placeholder="Enter Password" name="psw" required>

                    <label for="psw"><b>Repeat Password</b></label>
                    <input type="password" placeholder="Repeat Password" name="psw" required>

                    <button type="submit">Sign Up</button>                    
                </div>                
            </form>
        
    </div>
</template>

<style scoped>
body {
    font-family: Arial, Helvetica, sans-serif;
}

.main{
    width: 50vh;    
    margin: auto;
    margin-top: 20px;
}

/* Full-width input fields */
input[type=text],
input[type=password] {
    width: 100%;
    padding: 12px 20px;
    margin: 15px 0;
    display: inline-block;
    border: 1px solid #ccc;
    box-sizing: border-box;
}

/* Set a style for all buttons */
button {
    background-color: #281200;
    color: white;
    padding: 14px 20px;
    margin: 8px 0;
    border: none;
    cursor: pointer;
    width: 100%;
}

button:hover {
    opacity: 0.8;
}

.container {
    padding: 16px;
}

span.psw {
    float: right;
    padding-top: 16px;
}

</style>

<script>
export default {
    name: 'SignUp',
    components: {

    }
}
</script>
