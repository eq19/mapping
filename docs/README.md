{%- for item in site.html_pages -%}
	{%- if item.path == "assets/concept/map.md" -%}
		{{ item.content }}
	{%- endif -%}
{%- endfor -%}
