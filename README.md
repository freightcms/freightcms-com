# FreightCMS

## Summary

Static website for tracking the project of the open source freight cms project.

## Development

1. Install [rbenv](https://formulae.brew.sh/formula/rbenv) so you can manage ruby versions on your macbook

```
brew install rbenv
```

2. Add the setup code to your cmd prompt so that rbenv is setup on each terminal startup

```
echo "eval "$(rbenv init -)" >> ~/.zshrc
```

3. Install ruby version 3.4.2 or possibly whatever the latest version is

```
rbenv install 3.4.2 && source ~/.zshrc
```

4. Validate the install

```
type rbenv
```

**should output something like** 

> rbenv is a shell function from /Users/squishedfox/.zshrc

5. Set your global ruby environment

```
rbenv global 3.4.2
```

6. Install [bundler](https://bundler.io/guides/getting_started.html)

```
gem install bundler
```

7. Install [jekyll](https://jekyllrb.com/)

```
gem install jekyll
```

8. Install project gems

```
bundle install
```

### Running the project

Run the below command

```
bundle exec jekyll serve
````
