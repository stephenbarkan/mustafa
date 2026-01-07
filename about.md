{% extends "layouts/base.njk" %}

{# Nested Components ------------------------------------------------------------------------------------------------------------------- #}

{% from "components/button.njk" import button %}
{% from "assets.njk" import logo, sparkle %}

{# Values ------------------------------------------------------------------------------------------------------------------------------ #}

{% set mainStyles = "py-section gap-section" %}
{% set showNavbar = true %}
{% set showBottomLine = false %}

{# ------------------------------------------------------------------------------------------------------------------------------------- #}

{% block content %}

    {% call container(props={size: "wide", type: "cols-1"}, attrs={class:""}) %}
    {% endcall %}

{% endblock %}

{% block footer %}
{% endblock footer %}

{% block blobs %}
{% endblock %}


{# ------------------------------------------------------------------------------------------------------------------------------------- #}
