<style>
.networks {
    text-align: center;
}

.networks ul {
    display: inline-flex; 
    flex-direction: row; 
    flex-wrap: wrap; 
    justify-content: center; 
    list-style: none; 
    padding: 0; 
    margin: 0;
}

.networks li {
    margin-right: 10px;
}

.team-role {
    text-align: center;
    margin-top: 0.5em;
}

.container-xs {
    font-size: 1rem;
    margin-top: 0 !important;
    margin-bottom: 0 !important;
}

.container ul {
    margin-top: 0 !important;
    margin-bottom: 0 !important;
}

</style>

<div class="container"> 
- {% if member.social.website %}<a href="{{ member.social.website }}">**{{member.name}}**</a>{% else %} **{{member.name}}** {% endif %} ({{member.bio.end}})<br>
{{member.bio.role}} at {{member.institution}}

</div>
