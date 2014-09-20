Climbers use bolts so that they don't fail the climb. That's a very similar analogy as to why I write tests before features.
Tests show you that what you're writing code for is a real solution. You need to see it fail, then make it pass.

Testing has many benefits, and they multiply when you are on a team.
- Consistency of code
- Integrity of code
- give coders confidence
- gives a collective visibility
- visibility
- reference

I've heard it said that tests are only written for complex methods. Who defines that line? I say, that if it's an easy method, then the test will be easy to write.

I think peopel avoid b/c they've never worked well in a team, or they have never taken the time to learn it the right way.

testing also keeps you focused on the task at hand.
It prevents scope creep b/c you have to write a test first, which is a pre-qualifier.

books
- everyday rails - rspec, capybara, factory girl
- testing by example

Share;
tweet
facebook

for example - i made a simple seo change broke all my tests. I wouldn't have realized that had I not seen my tests which showed me that I had called it in other places as well.