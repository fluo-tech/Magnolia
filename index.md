## Welcome to GitHub Pages

You can use the [editor on GitHub](https://github.com/fluo-tech/Magnolia/edit/master/index.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/fluo-tech/Magnolia/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
<head>
    <meta charset="utf-8">
    <title>Bienvenue sur Magnolia déménagement</title>
    <style>
      input:invalid {
        border: 2px dashed red;
      }

      input:valid {
        border: 2px solid black;
      }
    </style>
</head>

<body>
    <form>
      <fieldset>
      <label for="choose">Pour commencer quel est votre prénom et votre nom?</label>
      <input id="choose" name="prenom nom" required pattern="[A-Za-z' -]+">
      </fieldset>
<fieldset>
      <div>
      <label for="choose">Indiquez votre adresse</label>
      <input id="choose" name="adresse" required pattern="[0-9]+[A-Za-z' -]+">
      </div>
      <fieldset>
    <label for="number">Quelle est votre type d'habitation ?</label>
     <select>
      <option>Résidence principale</option>
      <option>Résidence secondaire</option>
      <option>Local professinnel</option>
    </select>
  </fieldset>
  <div>
    <label for="choose">Indiquez le type de logement </label>
    <select>
      <option>Appartement</option>
      <option>Maison</option>
    </select>
  </div>
  <div>
    <label for="choose">Combien d'étages  </label>
    <select>
      <option>Appartement</option>
      <option>Maison</option>
    </select>
  </div>
  </fieldset>
  <div>
      </form>
      <button>Etape suivante</button>
      <fieldset>
      <label for="DateDemenagement">A quelle date déménagez vous?</label>
      <input type= "date" id="DateDemenagement" min="2020-03-28" name="DateDemenagement" required pattern="[[0-9]{4}-[0-9]{2}-[0-9]{2}">
      </fieldset>
      <button>Etape suivante</button>
      <fieldset>
     <form novalidate>
  <p>
    <label for="mail">
      <span>Veuillez saisir une adresse e-mail :</span>
      <input type="email" id="mail" name="mail">
      <span class="error" aria-live="polite"></span>
    </label>
  <p>
  <button>Envoyer</button>
</form>
      </fieldset>
</body>

</html>
