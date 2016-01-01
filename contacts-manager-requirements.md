## Contacts Manager

Your task is to create a simple Ruby on Rails application for managing contacts - details below.

![workflow](https://goo.gl/7i5fSL)

## Requirements

### Authentication

Give users the ability to login and logout. Protect all routes from anonymous access (i.e. a user has to be authenticated in order to view/create/edit/update/delete contacts)

### Design

The application needs to have a modern look and feel. You are encouraged to use Bootstrap but are welcomed to use any other frontend CSS framework if you'd like.

### Functionality

Once the user is authenticated, the are presented with a list of their contacts in alphabetical order. This list should display the user's avatar (or a default avatar if the user hasn't uploaded an image for the particular contact), full name, email, and phone number. From this view the user can add a new contact or select an existing contact. Contacts need to capture the following information

- first name
- last name
- email
- phone number
- avatar

If the user selects an existing contact, they are taken to the contact details page where the following information is to be displayed

- full name
- email
- phone number
- avatar (the image the user uploaded or a default avatar if none was uploaded)

From the details view, the user can choose the edit the contact information or delete the contact entirely. If the user decides to delete the contact, they need to be presented with a confirmation prior to actual deletion.

### Resources

#### Rails Guides

[Rails guides](http://guides.rubyonrails.org/) is an excellent resource for all things related to Rails. The following sections are relevant to this project

- http://guides.rubyonrails.org/getting_started.html
- http://guides.rubyonrails.org/active_record_basics.html
- http://guides.rubyonrails.org/migrations.html
- http://guides.rubyonrails.org/association_basics.html
- http://guides.rubyonrails.org/layouts_and_rendering.html
- http://guides.rubyonrails.org/routing.html

#### Railscasts

[Railscasts](http://railscasts.com/) is a collection of screencasts created by Ryan Bates which cover an incredible amount of topics. If you don't feel like watching the video, there is an asciicast for every episode which transcribes the video. This episode will be relevant to this project

- http://railscasts.com/episodes/270-authentication-in-rails-3-1


#### Miscellenous

[Using Dragonfly to handle uploads in Rails](http://markevans.github.io/dragonfly/rails/)
[Avatar Magick](https://github.com/bjedrocha/avatar_magick)