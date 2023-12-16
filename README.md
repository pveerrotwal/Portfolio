# Paramvir Rotwal Resume

Live demo at (https://pveerrotwal.github.io/Portfolio/)


***

# Screenshot

<p align="center">
 <img width="1440" alt="Screenshot 2023-12-16 at 10 24 21 PM" src="https://github.com/pveerrotwal/Portfolio/assets/108364147/b96f6879-90a8-469d-8ede-7c54c05d9817">

</p>

# Quick Setup

1. Install Jekyll: `gem install jekyll bundler`
2. Fork this repository and clone your fork
3. Edit `_config.yml` to personalize your site

# Settings

You have to fill some informations on `_config.yml` to customize your site:

## Site settings
```yml
description: A blog about lorem ipsum dolor sit amet
baseurl: "" # the subpath of your site, e.g. /blog/
url: "http://localhost:3000" # the base hostname & protocol for your site
```

## User settings
```yml
username: Lorem Ipsum
user_description: Software Engineer
user_title: Paramvir Rotwal
email: paramvirrotwal@gmail.com
```

> Don't forget to change your URL before you deploy your site!

# Color and Particle Customization

- Color Customization
  - Edit the `.sass` variables
- Particle Customization
  - Edit the json data in particle function in `app.js`
  - Refer to `Particle.js` for help

# Content

You can (and should) edit the `.html` files for adding your own information, icons, working experience, social links or whatever you want to add. I.e.:

```html
<a aria-label="My Github" target="_blank" href="https://github.com/pveerrotwal">
  <i class="icon fa fa-github-alt" aria-hidden="true"></i>
</a>
```

# Running locally

In order to compile the assets and run `Jekyll` locally you need to follow those steps:

1. Install Jekyll
2. Run `bundle install`
3. Run `bundle exec jekyll build`
4. Start and http-server in the folder `_site`

# Contribution

- Report issues
- Open pull request with improvements
- Spread the word
- Reach out to me directly at <paramvirrotwal@gmail.com>

