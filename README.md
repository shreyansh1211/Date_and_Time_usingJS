# Date_and_Time_usingJS
Display Time and Date using Java Script.

# Code

<br>
<script>   <br>
        let a;    <br>
        let date;  <br>
        let time;  <br>
        const options = { weekday: 'long', year: 'numeric', month: 'long', day: 'numeric' };  <br>
        setInterval(() => {    <br>
            a = new Date();     <br>
            date = a.toLocaleDateString(undefined, options);     <br>
            time = a.getHours() + ':' + a.getMinutes() + ':' + a.getSeconds();     <br>
            document.getElementById('time').innerHTML = time + "<br>on " + date;     <br>
        }, 1000);    <br>
    </script>
