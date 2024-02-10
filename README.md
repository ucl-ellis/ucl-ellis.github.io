# UCL ELLIS Unit website

## Locally testing the website using docker

If you run this docker command inside the repo's folder, you will be able to access your version of the website
at http://localhost:4000:

```bash
docker run --rm -it --entrypoint bash \
	-v "$(pwd):/tmp" -w /tmp -p 4000:4000 \
	ghcr.io/actions/jekyll-build-pages:v1.0.9 \
	-c 'gem install bundler:2.4.22 && bundle install && bundle exec jekyll serve --host=0.0.0.0'
```

This is useful as it uses the version of Ruby as GitHub, allowing you to easily test your changes.

## How to add a new profile

Create a new markdown file in the _people directory following the
template:

File name: `{Year}-{Month}-{Day}_{department acronym}_{first name}_{last name}.md`

File contents:

```md
---
layout: default
website: {Website}
date: {Year}-{Month}-{Day}
img: {first name}_{last name}.jpg
interests: TBA.
department: {Deparment name}
name: {Name}
description:  "{Write profile's bio here.}"
---
```

The profile picture should be square (1:1 aspect ratio) and placed at: `img/people/{first name}_{last name}.jpg`

## How to add a new deparment.

In the file _config.yml, there is a property named `departments`, simply add the name of the deparment at the end of the
list. For example:

```yaml
departments: [
  Computer Science, Gatsby Computational Neuroscience Unit, Department of Statistical Science,
  Department of Electronic and Electrical Engineering, UCL Energy Institute, Department of Experimental Psychology,
  New Deparment Name,
]
```