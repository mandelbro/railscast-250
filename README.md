# Authentication from Scratch

A Ruby on Rails app with application content type and authentication system built from scratch. Based on [Railscast #250](http://railscasts.com/episodes/250-authentication-from-scratch-revised)

## Models
* Article
  * Title (String): Name of the article
  * Author (String): Name of the user who wrote the article
  * Body (Text): Text body of the article
* User
  * Email (String): Email of user
  * Password Digest (String): User Password hash
