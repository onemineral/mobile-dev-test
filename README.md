# One Mineral Mobile Dev Test (React Native)

Your task is to implement a React Native application that displays a list of tv shows using [TV Maze API](https://www.tvmaze.com/api). The shows should be tappable and lead you to a show's detail page which renders the episodes in a list with the name and image of the episode.

Optional:

Allow the user to sign in locally (you are free to mock this) and favourite their preferred shows. This should be persisted across application restarts.

**Note:** You can use your preferred setup (RN cli, Expo cli, [Ignite](https://github.com/infinitered/ignite), etc.)


### What we're looking for

- **Build your components from scratch.** Try not to use any existing design toolkit for React Native.
- **Make custom components as general and reusable as possible.** We would like to see your approach to designing a component API design. Don't spend a lot of time making it completely universal or bullet-proof.


### What we're not looking for
- **You don't need to go crazy in terms of componentization.** Extract components when it helps you maintain what would otherwise be annoying duplication, but don't break things apart needlessly.
- **You don't need to write tests.** If they help you then sure go for it, but don't prioritize them over getting the requirements implemented.


### Nice to haves
- **Use typescript to build it.** We are heavy typescript users and it would be nice to see how you use it in this simple project.
- **Use react-navigation** Our preferred navigation solution for React Native apps is [react-navigation](https://reactnavigation.org/) and we recommend using it for this test.
- **Use Redux** We like Redux and we use it in almost all the apps we build. You can consider using the [toolkit](https://redux-toolkit.js.org/) for this.
- **Loading progress.** Currently there would be two external api calls that might make the app janky when it loads the information. You could consider implementing a loading indicator to show progress to the user without affecting the layout (or use a skeleton loading approach).