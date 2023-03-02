# test-repository
Just a test repository to experiment with some internal work at GitHub :octocat:

## First feature
- Testing push hook job system 🎉
- Wow, it is working, lets generate some more data to see idle times and where time is spent
- Checking if all db clusters are affected equally
  - Definitely not, will I get lucky and get some throttling generated stats?
- No errors on the throttling side :(, where are the errors when you need them? 😂 It's all good I guess 😄
- Checking now if we have some errors. Gaining confidence 💪

## Second feature
- Testing now that stats make it to the data warehouse
  - Will they? Not seeing anything yet :(
  - Maybe wait for some more minutes to make sure??
  - I was querying the wrong time window!! It works! 🎉

## Third feature
- Let's try to add some overall generic logging for our message system
  - Making another commit, will this be available in the log index? How long will it take?
  - It seems to be working 💪 Let's try one more time...
  - wow! 15s e2e latency, did i get lucky with the flush period?! Let's try again
  - And another try, making sure we don't have any errors...
  - Mmmm, no errors, but this last commit did not show up. Network partition?
  - Starring repository, will I see the job going through?
  - This is in production!

## Fourth feature
- While logging worked, it is too much for production. Let's make it configurable depending on environment
