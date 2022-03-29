## Rock, Paper, Scissors

A simple Sinatra application that will play rock, paper, scissors. The player inserts their move as URL parameter at the end of `http://localhost:4567/throw/`. Then computer will randomly pick a move and the final result will appear on the page. :rock: :page_with_curl: :scissors:

### To play 
- Clone repository `git clone git@github.com:fi-ya/rock_paper_scissors.git`
- `cd` into directory 
- Check to see if you have `sinatra` & `thin`,  installed by running command `gem list`
  - if you don't you can install using `gem install <name>`
- Start game by running command in terminal  `ruby game.rb`
- Decide your move (rock, paper, scissors)
- Open browser on `http://localhost:4567/throw/scissors` where scissors is the move you have made
- Have fun playing!


## Resources 
- [Sinatra Docs](http://sinatrarb.com/intro.html)
- [Sinatra The Book](https://sinatra-org-book.herokuapp.com/#toc_0)
- [Sinatra Gem Docs](https://rubydoc.info/gems/sinatra)
- [Sinatra CORS GitHub Doc](https://github.com/jdesrosiers/sinatra-cors)
- [Thin GitHub](https://github.com/macournoyer/thin)