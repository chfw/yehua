`{{name}}` - Let you focus on code, instead of setup scaffolding
================================================================================

:Author: {{author}}
:Source code: http://github.com/{{organisation}}/{{name}}.git
:Issues: http://github.com/{{organisation}}/{{name}}/issues
:License: {{license}} License
{% if version == release%}
:Released: |version|
{%else%}
:Development: |release|
:Released: |version|
{%endif%}
:Generated: |today|
