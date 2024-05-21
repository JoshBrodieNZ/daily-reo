This is where I'm keeping my notes for reo Māori study as I follow along with [Not Another's](https://www.na.studio/about) Daily Te Reo Māori bot posting new kupu each day into my work chat. I'm a relative beginner with te reo Māori, so don't go thinking any of this is going to be 100% correct, it's mostly my study notes.

Sources for the grammatical content and example sentences are generally Ray Harlow's "A Māori Reference Grammar", Winifred Bauer's "The Reed Reference Grammar of Māori", [kupu.maori.nz](https://kupu.maori.nz/) and [Te Aka](https://maoridictionary.co.nz/).

If anyone pays enough attention to this that you feel motivated to add corrections, you can create issues [here](https://github.com/JoshBrodieNZ/daily-reo/issues).

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
      <p>{{ post.excerpt }} 
        ({{ post.date | date_to_long_string }})
      </p>
    </li>
  {% endfor %}
</ul>
