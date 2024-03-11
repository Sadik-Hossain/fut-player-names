# fut-player-names

1. create a git repo and push it to github

2. Configure npm and creating a package.json

3. go to [npm docs](https://docs.npmjs.com/cli/v10/using-npm/config) and you'll see a bunch of configuration options like:

- `init.author.name`
- `init.author.email`
- `init.author.url`

  You can also set the license and version and other things.

4. setting the author, email, url in the terminal

   ```bash
   npm set init-author-name "Your Name"
   npm set init-author-email "Your Email"
   npm set init-author-url "https://yourwebsite.com"
   npm set init-license "MIT"
   ```

> another property that kent recommends is the `save-exact` property, this will tell npm that Dependencies saved to package.json will be configured with an exact version rather than using npm's default semver range operator. Set this to true by running `npm set save-exact true`

> check the npm config by running `cat ~/.npmrc`

5.  create or log into your npm account.
6.  now in the terminal run `npm adduser` and enter your username, password, and email.
7.  after configuring npm, create a package.json file by running `npm init`

---
