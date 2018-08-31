# Introduction

This Contentful extension automatically sets the field with a reference to an `Author` entry, based on the current user. It does so by matching the e-mail of the user with an `Author` entry which has the same e-mail address. 

## Installation & Prerequisites
For this extension you'll need to have a content type `Author` in your space, with id `author`. This content type has a couple of fields:
- E-mail (id: email)
- Display name (id: display_name)
- First name (id: first_name)
- Last name (id: last_name)

To install: 
- Go to `Settings` -> `Extensions` from the Contentful menu. 
- Click `Add extensions` -> `Install from Github`
- Enter the URL to the extension.json file and click Install
