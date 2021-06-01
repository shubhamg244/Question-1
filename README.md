# Question-1
# Define an array of numbers (use any random numbers). Write a program to print only the even numbers of the array. Do not use any library functions, need to do via for loops only

<!DOCTYPE html>
<html>
<script>
         function getEvenNumbers() {
        var array = [11, 12, 13, 14, 15, 16];

        for (var i = 0; i < array.length; i++) {
            if (array[i] % 2 === 0) {
                document.writeln(array[i] + "<br />");
            }
        }
    }

    getEvenNumbers();
</script>
</html>
