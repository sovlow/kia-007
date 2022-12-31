<script src="https://code.jquery.com/jquery-3.3.1.min.js" 
        integrity="sha384-tsQFqpEReu7ZLhBV2VZlAu7zcOV+rXbYlF2cqB8txI/8aZajjp4Bqd+V6D5IgvKT" 
        crossorigin="anonymous">
</script>
<script src="jquery.gh-readme.min.js"></script>
<div id="readme"></div>
$(function () {
    var options = {
        owner: 'kia-007',
        repo: 'kia-007'
    };
    $('#readme').readme(options);
});
