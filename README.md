# OneMain Dad Jokes App
Simple, fast secure. Shows dad jokes from https://icanhazdadjoke.com when launched 

# Project Setup
Build with gradle as usual. Edit with Android Studio.

# Roadmap
- Swipe to Refresh joke https://developer.android.com/training/swipe/add-swipe-interface
- Show some sort of a loading spinner
- Show list of jokes as per https://icanhazdadjoke.com/search API or similar
- Search for jokes
- Share a joke (looks like there is a way to generate a permalink)

# Tech debt
- Communicate user-agent as per https://icanhazdadjoke.com/api#custom-user-agent
- Add Repository layer as recommended in https://developer.android.com/jetpack/docs/guide
- Some mature dependency injection would be nice https://insert-koin.io
- Add testing (unit tests and/or espresso tests). Need to make sure tests are runnable via gradle CL.

# Bugs
- Screen rotation fetches new joke
