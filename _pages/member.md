<style>
.networks {
    text-align: center;
    margin-top: 0.5em;
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

.avatar img {
    width: 125px;
    height: 125px;
    object-fit: cover;
    border: 1px solid #ddd; /* Gray border */
    border-radius: 4px;  /* Rounded border */
    padding: 5px; /* Some padding */
}


/* Add a hover effect (blue shadow) */
img:hover {
  box-shadow: 0 0 2px 1px rgba(0, 140, 186, 0.5);
}


p {
    display: block;
}
h5 
,h6 {
    margin-bottom: 0.2rem;
}

</style>

<div class="col-sm-6 col-md-4 col-lg-3 col-xl-3 mt-4 mb-3">
<div class="avatar">
<p>
{% if member.social.website %}<a href="{{ member.social.website }}"><img src="{{ site.baseurl }}/assets/images/{% if member.photo %}{{ member.photo }}{% else %}Michigan_State_University_seal.svg.png{% endif %}" class="img-thumbnail rounded-circle d-block m-auto"></a>{% else %} <img src="{{ site.baseurl }}/assets/images/{% if member.photo %}{{ member.photo }}{% else %}Michigan_State_University_seal.svg.png{% endif %}" class="rounded-circle d-block m-auto"> {% endif %}
</p>
</div>

{% if member.social.website %}<h5 class="font-weight-bold" style="text-align: center"><a href="{{ member.social.website }}">{{member.name}}</a></h5> {% else %} <h5 class="font-weight-bold" style="text-align: center">{{member.name}}</h5> {% endif %}
{% if member.bio.start %}<p style="font-size: 0.825em; text-align: center; margin-bottom: 0rem;">{{member.bio.start}} - Present</p>{% endif %}
{% if member.bio.content %}<p style="font-size: 0.825em; text-align: center; margin-bottom: 0rem;">{{member.bio.content}}</p>{% endif %}

<!-- <div class="networks">
<ul>
{% if member.social.email %}<li><a href="mailto:{{ member.social.email }}" target="_blank"><i class="fa fa-envelope-square fa-2x"></i></a></li>{% endif %}
{% if member.social.github %}<li><a href="{{ member.social.github }}" target="_blank"><i class="fa fa-github-square fa-2x"></i></a></li>{% endif %}
{% if member.social.linkedin %}<li><a href="{{ member.social.linkedin }}" target="_blank"><i class="fa fa-linkedin-square fa-2x"></i></a></li>{% endif %}
{% if member.social.scholar %}<li><a href="{{ member.social.scholar }}" target="_blank"><i class="ai ai-google-scholar-square ai-2x"></i></a></li>{% endif %}
{% if member.social.researchgate %}<li><a href="{{ member.social.researchgate }}" target="_blank"><i class="ai ai-researchgate-square ai-2x"></i></a></li> {% endif %}
{% if member.social.twitter %}<li><a href="{{ member.social.twitter }}" target="_blank"><i class="fa fa-twitter-square fa-2x"></i></a></li> {% endif %}
{% if member.social.website %}<li><a href="{{ member.social.website }}" target="_blank"><i class="fa fa-globe fa-2x"></i></a></li>{% endif %}
</ul>
</div> -->
</div>