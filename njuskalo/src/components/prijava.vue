<template> 
    <div>
        <form action="/action_page.php">
            <label for="fname">First name:</label><br>
            <input type="text" id="fname" name="fname" value="John"><br>
            <label for="lname">Last name:</label><br>
            <input type="text" id="lname" name="lname" value="Doe"><br><br>
            <input type="submit" value="Submit">
        </form> 
    </div>

</template>

<script>
export default { }

</script>


<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped> </style>
