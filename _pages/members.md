{% assign my_array = "" | split: ',' %}
{% for member in site.data.people %}
{% if member.groups contains group %}
{% assign my_array = my_array | push: member %}
{% endif %}
{% endfor %}

<!-- <script>
function convertSemester(array){
        if (array[0] == "Fall"){
            array[0] = "2";
        }else if(array[0] == "Spring"){
            array[0] = "0";
        }else if(array[0] == "Summer"){
            array[0] = "1";
        }
        console.log(array);
        return array;
    } 
</script> -->


<div class="row">
{% if group == "PI" or group ==  "PhD" or group ==  "BS"  or group ==  "MS" or group == "Visiting" %}
<!-- <script>
var products = [
    {% for member in my_array %}                              // Liquid
        { self: '{{member}}', startDate: '{{ member.bio.start }}' }, // JS & Liquid
    {% endfor %}                                                   // Liquid
].sort(function(productA, productB){
let tempA = productA.startDate.split(" ");
let tempB = productB.startDate.split(" ");
tempA = convertSemester(tempA);
tempB = convertSemester(tempB);
if (tempA[1] < tempB[1]) {
    return -1;
} else if (tempA[1] > tempB[1]) {
    return 1;
} else {
    if (tempA[0] < tempB[0]){
        return -1;
    }else if (tempA[0] > tempB[0]){
        return 1;
    }else{
        return 0;
    }
}
}); 
</script>-->

{% assign filtered_group = my_array | sort: sorting_criteria %}
{% for member in filtered_group %}
{% include_relative member.md %}
{% endfor %}
{% else %}
{% assign filtered_group = my_array | sort: sorting_criteria | reverse %}
{% for member in filtered_group %}
{% include_relative alumni.md %}
{% endfor %}
{% endif %}
</div>